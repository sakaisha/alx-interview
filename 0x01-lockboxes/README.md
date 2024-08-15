This repository is part of the Specializations - Web Stack Programming course within the Back-end curriculum of the ALX Software Engineering Program. In this project, we tackle the "Lockboxes" problem, which is a common interview question.

Tasks
0. Lockboxes
You have n locked boxes in front of you. Each box is numbered sequentially from 0 to n - 1, and each box may contain keys to the other boxes.

Your task is to write a method that determines if all the boxes can be opened.

Prototype: def canUnlockAll(boxes):
boxes is a list of lists
A key with the same number as a box opens that box
You can assume all keys will be positive integers
There can be keys that do not have boxes
The first box boxes[0] is unlocked
Return: True if all boxes can be opened, otherwise False