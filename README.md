# cppdoc 
cppdoc is a C++ documentation generator inspired by `rustdoc`

## Features
- `rustdoc`-like documentation comments, rendered using markdown
- Documentation tests using codeblocks
- Extra documentation pages in markdown
- mermaid.js graphs
- Flexible styling options, with user-supplied stylesheets (see default themes in `example/`)
- libclang-based parser with support for records, enums, functions and namespaces
- Fair performance, with generation usually being faster than clang-backed Doxygen

## Usage
See [USAGE.md](USAGE.md)

## Preview
There is a live demo available [here](https://rdmsr.github.io/cppdoc).

Here is what cppdoc looks like with three different stylesheets:

`example/static/light.css`:
![light preview](assets/light-preview.png)

`example/static/ayu.css`:
![ayu preview](assets/ayu-preview.png)

`example/static/gruvbox.css`:
![gruvbox preview](assets/gruvbox-preview.png)

