## Motivation
Stastical generation provides an option to syntheize a slimilar trajectory, appropriate for a new task within the trainning space, from a set of recorded movements.
There are two main challenges the applicability of generalization.
- The database need to be provided beforehand, resulting in substantial initial programming effort for the user. （数据库需要之前就提供好，没有在线学习的能力）
- Generation only works within the training space. (泛化能力不足)
  
The author proposes an algorithm for autonomous expansion of the database, where the robot use iterative learning to optimize its behavior for new task conditions. (迭代学习适用于轨迹相对固定的任务，也包括康复训练中的任务) 