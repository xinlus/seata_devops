# DEVOPS

## 添加子模块

git submodule add path

## 初始化以及更新

### 初始化
git submodule update --init --recursive

## 常用命令

### 递归方式克隆整个项目
git clone  --recursive

###添加子模块
git submodule add  path

### 初始化子模块
git submodule init

### 更新子模块
git submodule update

### 拉取所有子模块
git submodule foreach git pull
git设置检出部分目录

### 设置允许克隆子目录
git config core.sparsecheckout true
