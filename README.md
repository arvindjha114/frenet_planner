# FrenetPlanner
Optimal Trajectory Generation


# Installation
```shell
cd "your_workspace"/src
git clone https://github.com/AGV-IIT-KGP/frenet_planner.git
cd ..
rosdep install --from-paths src --ignore-src -r -y
sudo apt-get install ros-kinetic-teb-local-planner-tutorials #if required
catkin_make
source devel/setup.bash
```

# Running
```terminal
foo@bar$ roslaunch robot_carlike_in_stage.launch
```

## Things to do

### Phase I

- [x] Set up stage simulator
    Clone the teb_local_planner_tutorials repository   
    Launch the file robot_carlike_in_stage.launch   
    Remove the teb planner from the pipeline   
    Plug in our planner node in the launch file   
- [ ] List out and subscribe to the required inputs
- [ ] Test vanilla frenet planning with hardcoded global path
