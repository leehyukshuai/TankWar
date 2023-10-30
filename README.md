# 坦克大战 TankWar🐏

![](https://github.com/leehyukshuai/TankWar/blob/main/tankwar.png)

## Description
一个简单的双人游戏。
A simple two-person game using pgzero.

## Manual
利用小羊的大炮摧毁方块并攻击对手。
In the game, all blocks can be destroyed. Using sheep's cannon to hit your competitor untill he has no hp.

玩家1：`wad`移动跳跃, `cvb`调整射角并发射。
Player 1: `wad` to move and jump, `cvb` to raise and lower you gun and shoot.

玩家1：`ijl`移动跳跃, `[]\`调整射角并发射。
Player 2: `ijl` to move and jump, `[]\` to raise and lower you gun and shoot.

## How to Play This Game
First `pip install pgzero easygui` and then `python -m pgzero 'tank war.py'`.
## Error Fix

- ModuleNotFoundError: No module named 'tkinter'
  - See this [link](https://stackoverflow.com/questions/25905540/importerror-no-module-named-tkinter).
