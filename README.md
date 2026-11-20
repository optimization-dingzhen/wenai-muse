# wenai for Meta Muse

一个供 Meta Muse 手机端使用的中文文字陪伴技能。它保留角色设定、剧情续接、约定、事件计数和可复制的存档。

## 安装

把本仓库链接和下面这段话发到手机 Muse。

> 请读取这个仓库里的 `SKILL.md` 和 `skill.yaml`，把两个文件原样安装到你的自定义技能目录 `~/workspace/custom-skills/wenai/`。如果同名文件已经存在且有差异，请先告诉我。安装后回读核对，并检查技能是否可以按名称调用。若只能确认文件写入，就报告「文件已写入，技能加载待验证」。

自定义技能目录和清单格式参考 Muse 社区的实际用法。 [社区安装示例](https://github.com/inuro/muse-chat-relay#installation)

## 使用

在新对话里发 `wenai 状态`。收到「wenai 文字版 v1 已加载」后，发 `用 wenai` 并告诉 Muse 角色名、性格和关系起点。

- `继续` 从上一幕接着聊。
- `档案` 查看角色设定、当前进度和计数。
- `存档` 获取可复制的快照。换对话时调用 wenai，再发 `读档` 并附上快照。

互动和档案的设计思路来自 wenai。 [原项目](https://github.com/Straniero44/wenai)
