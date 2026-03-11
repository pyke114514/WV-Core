# WV-Core (Fork)

这是 `EvanatorM/WV-Core` 的修复版 fork。  
如果你原来依赖的是官方仓库，请把依赖地址改成这个仓库即可。

This is a patched fork of `EvanatorM/WV-Core`.  
If your project currently depends on the original repository, just replace the dependency URL with this one.



## 用法 Usage

把你项目里原来的：

```cmake
_fetch_git_project(WVCore https://github.com/EvanatorM/WV-Core.git alpha-v0.3.0)

改成：

cmake
_fetch_git_project(WVCore https://github.com/pyke114514/WV-Core.git master)

改完后删除 build 目录并重新 CMake 配置/构建。

原作者仓库
https://github.com/EvanatorM/WV-Core


Replace this in your project:

```cmake
_fetch_git_project(WVCore https://github.com/EvanatorM/WV-Core.git alpha-v0.3.0)

with:

cmake
_fetch_git_project(WVCore https://github.com/pyke114514/WV-Core.git master)

After that, delete your build directory and run CMake configure/build again.

Original repository
https://github.com/EvanatorM/WV-Core
