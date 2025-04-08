# Project Introduction
In order to better develop applications based on large language models, this project analyzes the source code of the popular industry tool langchain. It aims to better utilize large predictive models to provide higher quality, more efficient, and more convenient interactive services for humanity.

# Feature Introduction
The images, code, configuration, and other information used in the source code analysis are all placed in the anal directory; the step-by-step explanations in the source code can be found in the corresponding code files in this project.

## How to Use the Module Dependency Graph Tool
A video demonstrating how to use the module dependency graph tool has been recorded and can be found on [Bilibili](https://www.bilibili.com/video/BV1iP411v7vY/?spm_id_from=333.999.0.0&vd_source=cd62f6bf001b64bc3c0e062e4c37bc6b) and in a [Zhihu article](https://zhuanlan.zhihu.com/p/639056301) as well as a [Zhihu video](https://www.zhihu.com/zvideo/1655946356811079680). The steps for using the tool are as follows:

    1. Install graphviz  
       Download graphviz from the official website and install it just like a Python environment.
    2. Install the module dependency graph tool  
       pip install pydeps
    3. Use the tool  
       pydeps xx.py -T png -o yy.png --max-bacon 3 --cluster

## How to Use the Class Diagram Tool

    1. Install pyreverse  
       pip install pylint   # pyreverse tool is included in pylint
    2. Use the tool  
       pyreverse -ASmy -o png ./xx.py   # Specific parameters can be viewed with "pyreverse -h"

# Completed Parts
0. Overall introduction to langchain, [Bilibili Video](https://www.bilibili.com/video/BV1fF41197XT/?spm_id_from=333.999.0.0&vd_source=cd62f6bf001b64bc3c0e062e4c37bc6b), [Zhihu Video](https://www.zhihu.com/zvideo/1658864628527525888), [Zhihu Article](https://zhuanlan.zhihu.com/p/640848809)
1. Source code analysis of chat_models, [Bilibili Video](https://www.bilibili.com/video/BV1fF41197XT?p=2&vd_source=cd62f6bf001b64bc3c0e062e4c37bc6b), [Zhihu Video](https://www.zhihu.com/zvideo/1661208710797172736)
2. Source code analysis of promptTemplate, [Bilibili Video](https://www.bilibili.com/video/BV1fF41197XT?p=3&vd_source=cd62f6bf001b64bc3c0e062e4c37bc6b), [Zhihu Video](https://www.zhihu.com/zvideo/1663740505211957248)
