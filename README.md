# Udacity 强化学习项目

### 项目文件夹包含三个目录:
* /logs/: 这个文件夹存放模拟过程中满足特定条件情况下产生的所有的日志文件。
* /images/: 这个文件夹包含了图形用户界面中车辆的图片。这里你不需要更改或创建任何文件。
* /smartcab/: 这个文件夹包含了创建环境、用户图形界面、模拟器和智能车的 python 脚本，除了 agent.py 之外，这里你不需要修改或创建任何文件。


### 项目还包括两个独立的文件：
* smartcab.ipynb: 这里包括你完成项目需要做的分析和需要回答的问题。 -visuals.py: 这是对分析作可视化 Python 脚本。你不需要修改这个文件。

### 在 /smartcab/ 中，有以下4个文件:
* 修改:
    * agent.py: 这是你要完成项目作业的 python 主文件。
* 不要修改: 
    * environment.py: 这个 python 文件会创建智能车的环境。
    * planner.py: 这个 python 文件会为智能车向既定目标移动创建一个高阶的计划。
    * simulation.py: 这个 python 文件用来创建模拟器和用户图形界面。

## 运行代码
在 terminal 或命令行界面，把当前目录切换到 smartcab/ 的最顶层 （包含这两个项目文件夹）运行下面两条命令之一：
```python smartcab/agent.py```
```python -m smartcab.agent```
这会运行 agent.py 文件，在环境中执行你实现的智能车的代码。你可以使用命令 jupyter notebook smartcab.ipynb 在浏览器中打开你需要做分析的 notebook。.还有一个 README 文件包含在项目文件中，其中有些帮助信息。

# Machine Learning Engineer Nanodegree
# Reinforcement Learning
## Project: Train a Smartcab How to Drive

### Install

This project requires **Python 2.7** with the [pygame](https://www.pygame.org/wiki/GettingStarted
) library installed

### Code

Template code is provided in the `smartcab/agent.py` python file. Additional supporting python code can be found in `smartcab/enviroment.py`, `smartcab/planner.py`, and `smartcab/simulator.py`. Supporting images for the graphical user interface can be found in the `images` folder. While some code has already been implemented to get you started, you will need to implement additional functionality for the `LearningAgent` class in `agent.py` when requested to successfully complete the project. 

### Run

In a terminal or command window, navigate to the top-level project directory `smartcab/` (that contains this README) and run one of the following commands:

```python smartcab/agent.py```  
```python -m smartcab.agent```

This will run the `agent.py` file and execute your agent code.
