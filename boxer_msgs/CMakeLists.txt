cmake_minimum_required(VERSION 2.8.3)
project(boxer_msgs)

find_package(catkin REQUIRED COMPONENTS
  message_generation
  std_msgs
)

add_message_files(
  FILES
  Drive.msg
  Lift.msg
  LiftPosition.msg
  MCUResetReason.msg
  MotorFeedback.msg
  Pid.msg
  SafetyMode.msg
  Status.msg
  TractionStatus.msg
)

generate_messages(
  DEPENDENCIES
  std_msgs
)

catkin_package(CATKIN_DEPENDS std_msgs message_runtime)
