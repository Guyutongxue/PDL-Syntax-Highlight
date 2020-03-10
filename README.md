# PDL Syntax Highlight Extension for VS Code

## About PDL

PDL is a language designed by a certain lab at Peking University. This extension provides **very limited** syntax highlighting support, and **doesn't support compiling or debuging PDL**. Hope you enjoy it.

### Official Brief Introduction

PDL (Problem Description Language) is a modeling language for specifying constraint optimization problems. When using PDL, users only need to list all constraints between the variables without indicating how to solve the problem -- the PDL runtime system will automatically design a feasible solving algorithm and generate the corresponding code.

### Grammar

View [pdlteam/pdl-manual](https://github.com/pdlteam/pdl-manual) for detail. We students do have a Chinese version of this manual, but I'm afraid that I can't share it here. 

### Install from VSIX

Make sure you have npm installed.

```bash
npm install -g vsce
git clone https://github.com/Guyutongxue/PDL-Syntax-Highlight.git
cd PDL-Syntax-Highlight
vsce package
```

The VSIX file will be generated in your working directory. If it failed, try sudo again.

### Compiler

Certainly, the compiler hasn't released yet. But it is built into an Online Judge Platform [OpenJudge](http://openjudge.cn), which is maintained by Peking University too.

You cannot find the choice to compile your code by PDL in most of the submit pages. But you might be able to find some example problems [here](http://pdl.openjudge.cn/), and be careful that it will expire at any time.