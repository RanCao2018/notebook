# 自然科学杂志文章总结

## 2019 Trends and challenges in robot manipulation

__Object__: Building machines inspired by human hands that have a fantastic ability to manipulate objects of various shapes. Achieving robust and flexible collaboration between humans and robots is hence the next major challenge.

__Solution__:

* Prompts robots to learn skills from observing humans  performing complex manipulation. This allows robots to acquire manipulation capabilities in only a few trials. However, generalizing the acquired knowledge to apply to actions that differ from those previously demonstrated remains difficult.  
* Constructs databases of real object manipulation, with the goal to better inform the simulators and generate examples that are as realistic as possible. Yet achieving realistic simulation of friction, material deformation, and other physical properties may not be possible anytime soon, and real experimental evaluation will be unavoidable for learning to manipulate highly deformable objects.

## The central nervous system stabilizes unstable dynamics by learning optimal impedance

__内容__: 文章揭示了人体内的中央神经系统（CNS）可以通过不断的尝试来调节自身阻抗来适应变化（存在干扰）的环境。文中在没有干扰的环境（Null field）和存在发散干扰的环境（divergent force field）间进行了对比试验，结果显示人体提高了在干扰方向上的阻抗以抵抗干扰影响，而在任务方向上的阻抗保持不变。

__总结__: Why does the CNS use the difficult and computationally costly strategy of controlling the full impedance geometry rather than the simple strategy of co-contracting all muscles? The particular shape of endpoint stiffness learned in the DF, large in the direction of instability and small in the direction of movement, suggests a trade-off between stability and high muscle activation. Increasing impedance enhances the robustness to external perturbations, but co-contraction of muscles increases metabolic cost. Moreover, motor output variability increases with muscle activation. Therefore, reducing the impedance will decrease both the metabolic cost and movement error. For these reasons, it is desirable to optimize impedance. The control problem faced by the CNS is to optimize the magnitude, shape and orientation of impedance to achieve stability while minimizing metabolic cost.

## Differential game theory for versatile physical human–robot interaction

__内容__: 文章将机器人和人的任务目标建立成一个博弈体系 (GT framework) 内的 cost function, 并据此设计期望的控制算法。 文章将协作问题转化成了一个为达到纳什平衡的博弈控制问题。并设计了自适应率来估计人类的控制出入。

__特点__: 无力传感器，目前仅能实现一致（到达固定期望点）的情况。