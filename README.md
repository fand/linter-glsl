# linter-glsl

linter-glsl is a package for the Atom editor that lints GLSL shaders.

It uses the Khronos GLSL Validator which is part of the [GL Shading Language reference compiler](https://www.khronos.org/opengles/sdk/tools/Reference-Compiler/) as well as the [language-glsl](https://atom.io/packages/language-glsl) Atom package.

It also works nicely alongside [autocomplete-glsl](https://atom.io/packages/autocomplete-glsl).

![](https://andystanton.github.io/linter-glsl/images/linter-glsl-1.0.0.png)

## Requirements

 * [glslangValidator](https://www.khronos.org/opengles/sdk/tools/Reference-Compiler/)
 * [language-glsl](https://atom.io/packages/language-glsl)
 * Shaders must be named ```*.(vert|frag)```

## Installation

1. Install [glslangValidator](https://www.khronos.org/opengles/sdk/tools/Reference-Compiler/)
2. Install [language-glsl](https://atom.io/packages/language-glsl) and [linter-glsl](https://atom.io/packages/linter-glsl), either through 'Install Packages And Themes' or with apm:

   ```sh
   $ apm install language-glsl linter-glsl
   ```
3. Configure the path to glslangValidator in preferences.
4. Lint!

## Todo

 * [x] Add Atom package that uses glslangValidator to lint GLSL files named ```*.(vert|frag)```.
 * [ ] Add ability to lint ```*.(v|f).glsl``` files.
 * [ ] Add ability to link vertex and fragment shaders with the same root name within the current project.