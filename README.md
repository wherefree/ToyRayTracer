# ToyRayTracerOnGPU
A toy ray tracer on GPU, achieve by OpenGL. First git on https://github.com/Kitcham/ToyRayTracer/tree/OnGPU. This is a Graduation Project coded by me and Kitcham.


# Finished
- package OpenGL pipe as a ray tracer pipe
- build BVH on CPU, run on GPU
- base ray tracing 
- Monte Carlo Integration
- 

# Todo
- [ ] Data Struct simplify
- [ ] optimization shader 'if' and 'for'

这是一个简易的基于蒙特卡洛积分的光线追踪渲染器，由OpenGL实现。这个工程为我与Kitcham 的本科毕业设计。

# 已完成
- 将OpenGL管线封装为光线追踪渲染管线
- 用C++在CPU端实现BVH构建， 用GLSL在GPU实现BVH搜索
- 在shader上实现了基本的光线追踪迭代计算
- 在shader上实现了基于蒙特卡洛积分的光照计算
