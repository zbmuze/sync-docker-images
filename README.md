# sync-docker-images

# [skopeo-sync](https://github.com/containers/skopeo/blob/main/docs/skopeo-sync.1.md)
```shell
skopeo sync --src yaml --dest docker sync.yml my-registry.local.lan/repo/
```
# DOCKER_USERNAME和DOCKER_PASSWORD为仓库的登录密码，本来要写入配置文件容易暴露，所以脱敏一下
设置入口
Settings --> 左侧菜单栏 secrets --> New repository secret
