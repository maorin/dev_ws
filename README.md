# 只能用一台机器打败另一台机器  人类的顶级操作就是滑铲 滑铲打虎

colcon build

colcon build --symlink-install --packages-select action_cj_py

. install/setup.bash

ros2 run action_cj_py fibonacci_action_server

ros2 run action_cj_py fibonacci_action_client