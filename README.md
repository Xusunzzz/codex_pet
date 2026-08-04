# 小英子（Xiaoyingzi）

小英子是一只自定义 Codex 动画宠物：戴深蓝色棒球帽、背红色背包的可爱人形小伙伴。

![小英子精灵图](xiaoyingzi/spritesheet.webp)

## 文件结构

```text
xiaoyingzi/
├── pet.json
└── spritesheet.webp
```

- `pet.json`：宠物名称、描述和精灵图版本等元数据。
- `spritesheet.webp`：Codex v2 动画图集。

## 安装

将整个 `xiaoyingzi` 文件夹复制到 Codex 的自定义宠物目录：

```text
~/.codex/pets/xiaoyingzi/
```

安装后应保持以下路径不变：

```text
~/.codex/pets/xiaoyingzi/pet.json
~/.codex/pets/xiaoyingzi/spritesheet.webp
```

## 规格

- Pet ID：`xiaoyingzi`
- 显示名称：`小英子`
- 精灵版本：`2`
- 图集格式：WebP（RGBA）
- 图集尺寸：1536 × 2288
- 图集布局：8 列 × 11 行
- 单帧尺寸：192 × 208

## 验证

精灵图已通过 Codex v2 图集结构校验，没有错误或警告。

## 使用说明

本仓库中的 `pet.json` 和 `spritesheet.webp` 是可直接安装的完整宠物包。使用或分发时，请将两个文件放在同一个 `xiaoyingzi` 目录中，不要修改 `spritesheetPath`。
筛选文件
