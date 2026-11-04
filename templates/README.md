# 通用设备仓库模板

[device-repository](device-repository/README.md) 是可复制的空白骨架，覆盖快速上手、资料文档和典型 Demo 三大部分。[Franka_Panda](https://github.com/FSII-Robotics-LAB/Franka_Panda) 将提供实际填写示范，目前内容待完善。

## 如何使用

1. 建立或克隆自己的设备仓库，确认仓库归属和名称。
2. 将本目录下 `device-repository` **里面的内容**复制到目标仓库根目录，包含按需使用的 `.gitignore`。不要额外嵌套一层 `device-repository`。
3. 已有 README、代码或配置时逐项合并，不要整目录覆盖；保留目标仓库自身的 `.git` 目录。
4. 替换 `[待填写：…]` 字段。未知信息保留待填写状态，不编造设备信息。
5. 将 `demos/example_demo` 改为真实示例名称，填写说明并加入实际代码，或链接到准确版本的官方示例。
6. 补充照片、官方资料来源和验证记录；无需使用的可选目录可以移除，并同步调整引用。
7. 按 [规范](../docs/repository-standard.md) 完成检查，再将设备信息交给 Hub 维护人接入导航。

## 模板的边界

- 模板没有预设 Ubuntu、ROS、SDK、固件版本或机器人 IP。
- 模板不包含可直接运行的 Demo，也不预设厂商启动命令。
- `configs/` 和 `assets/` 按需保留；Demo 代码可采用原有工程结构。
- 通用模板在 Hub 维护；复制得到的各设备仓库独立维护自己的实际内容。

模板中的“待填写”需要负责人补充；写出具体步骤后仍需实际验证，才能标记为“已验证”。

[返回总导航](../README.md)
