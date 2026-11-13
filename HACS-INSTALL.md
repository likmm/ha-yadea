# HACS / Marketplace 安装

本仓库派生自 [flyqgs/ha-yadea](https://github.com/flyqgs/ha-yadea)，保留原作者代码与 MIT 许可证，并补充根目录 hacs.json，解决 Marketplace 提示缺少该文件的问题。

1. 打开 HACS / Marketplace → 右上角菜单 → 自定义存储库。
2. 添加 https://github.com/likmm/ha-yadea ，类型选择 Integration（集成）。
3. 搜索 Yadea 并下载安装；若版本列表中需要选择分支，请选 main。
4. 重启 Home Assistant。
5. 设置 → 设备与服务 → 添加集成 → 搜索 Yadea，输入雅迪智行账号。

本次修改仅修复仓库安装元数据；实际云端登录和车辆数据读取仍需在你的 Home Assistant 环境验证。
