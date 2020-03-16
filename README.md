# 个人修改的open3d源码

1. global registration RANSAC based on feature matching:

   修改RANSAC跳出条件，修改相关接口调用方法

2. registration.h :: RegistrationResult():

   修改构造函数，默认rmse=1e-16，默认fitness=1e16