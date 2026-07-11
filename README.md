# Kirin 710 Kernel Build

GitHub Actions 自动编译华为 Kirin 710 自定义内核（permissive SELinux）。

## 使用方法

1. 在 GitHub 创建一个新仓库（public 或 private 都行）
2. 把这个文件夹的内容推送到仓库
3. Actions 会自动开始编译
4. 编译完成后在 Actions 页面下载 artifact

## 编译产物

- `kernel_Image` — 编译好的内核镜像，用 `fastboot flash kernel` 刷入
