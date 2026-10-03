ros2 run turtlesim turtlesim_node	//运行小海龟
ros2 run turtlesim draw_square		//画正方形
ros2 run turtlesim turtle_teleop_key	//键盘方向键控制
ros2 node list				//看有哪些节点在跑
	/turtlesim	画海龟
	/teleop_turtle	读键盘
ros2 topic list                         //看靠哪些话题相互通信
	/turtle1/cmd_vel	速度频道
	/turtle1/pose		坐标频道	
ros2 topic echo /turtle1/pose		//实时刷出海龟坐标
	
	
