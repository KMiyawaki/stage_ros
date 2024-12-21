# stage_ros

This is a fork of [stage_ros](https://github.com/ros-simulation/stage_ros).

The difference from original is a controllable model.

Add 'human' on the model like this.

```
middle_block(
  pose [10.5 3 0 0]
  color "yellow"
  name "human"
)
```

Then you can control the block by publishing `Twist` to the topic `human/cmd_vel`.
