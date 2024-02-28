<div align=center>

# Rime config

**自用**小狼毫配置

主要基于 [iDvel/rime-ice](https://github.com/iDvel/rime-ice) 修改，部分配置参考 [Rime auto deploy](https://github.com/Mark24Code/rime-auto-deploy)

</div>

---

修改内容不完全记录：

- **样式：**
  - 添加 `macos` `搜狗` 和 `微信` 主题
  - 调整字体为：`思源黑体 CN, HarmonyOS Sans SC, Microsoft YaHei`
  - 候选词数量调整为 `6`
- **功能：**
  - 启用小鹤双拼 melt_eng: `melt_eng.schema.yaml/speller/algebra/__include: algebra_flypy`
  - 启用小鹤双拼 radical_pinyin: `radical_pinyin.schema.yaml/speller/algebra/__include: algebra_flypy`

---

## Usage

1. 安装 `git`
2. 在合适位置右键打开 `git bash` 并运行：`git clone git@github.com:SymmFz/rime_config.git`
3. 将仓库内容移动至小狼毫用户文件夹
4. 重新部署小狼毫

## Customization

修改输入方案:

- `melt_eng.schema.yaml/speller/algebra/__include`
- `radical_pinyin.schema.yaml/speller/algebra/__include`
