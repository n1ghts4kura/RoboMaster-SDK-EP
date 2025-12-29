# RoboMaster-SDK

## RoboMaster-SDK ( _**@n1ghts4kura**_ )
删除了 `robot.py` 中有关摄像头的操作（因为我们用不到 lol  
这样就不需要安装有关 视觉处理 的依赖了

### 使用 Usage

导出新的 `whl` 包:

```bash
# 切换至 **Python 3.8.0** !!!
# $ source ./venv/bin/activate

# 更新 `pip` & 安装打包工具
$ pip install --upgrade pip
$ pip install setuptools wheel

# 导出 whl 包
$ python setup.py clean sdist bdist_wheel

# 找到打包好的 whl 包
$ ls dist/
# robomaster-0.1.1.68-py3-none-any.whl
```

安装新的 `whl` 包:

```bash
# 切换至 **Python 3.8.0** !!!
# $ source ./venv/bin/activate

# 安装 robomaster 包
$ pip install robomaster-0.1.1.68-py3-none-any.whl
```

## RoboMaster-SDK (origin)

[![Gitter](https://badges.gitter.im/RoboMaster-SDK/community.svg)](https://gitter.im/RoboMaster-SDK/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

<img src="docs/source/images/robomaster.jpg" width="600">

Learn more about the RoboMaster Education Robot: https://www.dji.com/robomaster-ep

RoboMaster Developer Guide: https://robomaster-dev.rtfd.io/

Gitee link for RoboMaster SDK download: https://gitee.com/xitinglin/RoboMaster-SDK
