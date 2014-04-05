moveit_simple_grasps
====================

Note: this code is mostly moved from [block_grasp_generator](https://github.com/davetcoleman/block_grasp_generator)

Generate basic grasp poses for simple objects such as blocks or cylinders for use with MoveIt! pick and place

This is research code by [Dave Coleman](http://davetcoleman.com) at the Correll Robotics Lab. 

## Install

NEW: This package now depends on [moveit_visual_tools](https://github.com/davetcoleman/moveit_visual_tools)

## Tested Robots

 - [Baxter](https://github.com/davetcoleman/baxter)
 - [ClamArm](https://github.com/davetcoleman/clam)
 - [REEM](http://wiki.ros.org/Robots/REEM) - only with block_grasp_generator

## Build Status

[![Build Status](https://travis-ci.org/davetcoleman/moveit_simple_grasps.png?branch=hydro-devel)](https://travis-ci.org/davetcoleman/moveit_simple_grasps)

## Testing and Example Code

There are currently test scripts and examples in the [baxter_pick_place](https://github.com/davetcoleman/baxter/tree/hydro-devel/baxter_pick_place) package for using this grasp generator and in [reem_tabletop_grasping](https://github.com/pal-robotics/reem_tabletop_grasping).
