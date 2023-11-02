electron在国内的安装经常因为github的原因下载依赖失败，推荐使用国内源

yarn:

yarn config set registry https://registry.npmmirror.com --global

yarn config set ELECTRON_MIRROR https://cdn.npm.taobao.org/dist/electron/ --global

yarn config set ELECTRON_BUILDER_BINARIES_MIRROR http://npm.taobao.org/mirrors/electron-builder-binaries/ --global

npm:

npm config edit

增加以下配置：

registry=https://registry.npmmirror.com

ELECTRON_MIRROR=https://cdn.npm.taobao.org/dist/electron/

ELECTRON_BUILDER_BINARIES_MIRROR=http://npm.taobao.org/mirrors/electron-builder-binaries/