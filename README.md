# gitlab-ci
gitlab-ci相关

## 流程
before_script/环境准备 -> codebuild -> 获取jar包进行dockerbuild并push到aws ecr -> 清理相关镜像 -> 通过相关通讯工具进行通知