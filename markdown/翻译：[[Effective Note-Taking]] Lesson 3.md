- Metadata::
    - Tags:: #[[翻译]] #[[Done]] #[[未发布]]
    - Source:: #[[Andy Henson Series]]
    - 初翻: #wangxh1000
    - 校对: #Alex
    - Url: https://www.notion.so/Lesson-2-2f1dd175d36a45d1bc7f8778c78371a7
- 原文：[[[[Effective Note-Taking]] Lesson 3]]
- 
- 嗨，
- 让我们再来谈谈 Roam 的导航功能。在全局层面，你可以通过点击 **All Pages** 链接查看所有页面。另外，还有 **Graph Overview**。点击图中的节点会突出与之的连接。双击节点则进入对应页面。
- **搜索栏**
- 你还可以在搜索栏查找包含你所输内容的页面或 block。匹配的单词短语会被突出显示在结果列表中。如果同时搜索多个信息，则只会查找包含所有信息的结果。如果没有找到任何信息，你也可以用输入的内容创建一个新的页面。Command-U 是搜索栏的键盘快捷键。
- **被标注星号的页面或快捷方式**
- 对经常访问的页面，在页面中点击星号图标，会把它添加到左侧的Shortcuts 列表。再次点击星号则将其从列表删除。你可以用拖放的方式，对列表的任意内容做重新排序。
- **大纲**
- 让我们快速回到 Roam 大纲，你应该早就玩过这个功能，但现在让我们更详细地说说它的内容。block 可以无限嵌套。点击 Tab 键可以缩进 block，点击 Shift-Tab 键则取消缩进。你也能用鼠标进行操作，左键点击 bullet (block 前的圆点) 拖动它到新的位置。 当你松开鼠标键时，会出现插入线告诉你 block 的最终位置。当把 block 移进和移出缩进层级时，你会看到插入线相应地变长和变短。
- **编辑**
- 有件事情可能不太明显，其实存在两种模式：编辑模式和选择模式。当 block 处于编辑模式时，你会看到光标闪烁，你在 block 中输入文字等等信息。此时按回车键会离开当前 block，并在下方创建新的 block。然后你编辑新的 block，这个交互相当直观。另外，你也可以按 Escape 键而不是回车键，这将使 block 进入选择模式，当前编辑的 block 将被选中。当 block 进入选择模式，你会看到 markdown 语句被转换为可视化形式，此时可以点击链接进行跳转。
- **选择**
- 当 block 被选中时，你可以用 Shift 和上下箭头键选择更多 block。你可以用鼠标抓取所有被选 block，将它们一起移到新的地方 (把鼠标移到被选 block 的某个 bullet 上，变成手的形状，然后点击左键拖动)。你也可以用 Tab 和 Shift-Tab 键缩进或取消缩进被选 block。或者按 Delete 和 Backspace 键删除 block。当你删除 block 时，不会收到任何提示，但你之后能用 Command-Z (在 Mac 上) 和 Control-Z (在 Windows 上) 键执行撤销操作。如果你想再次执行已被撤销的操作，只要按 Command-Shift-Z 或 Control-Shift-Z键即可实现。在我写这篇文章的时候，当 block 处于选择状态时，你可以用 Command-Shift-Up 和 Command-Shift-Down 键来上下移动 block。但不幸的是，你还不能对多个 block 执行这种操作。我希望将来会有这个功能。
- **折叠和缩放**
- 你能用折叠和缩放功能帮你在写作时管理注意力。点击 block 的 bullet 将把内容聚焦到该 block 和它的子元素上。你会看到页面上方的面包屑路径，点击它可以返回原始内容。这也被称为__"Focus on this block"__，右键点击 bullet 就会看到该菜单项。同样的，你也能用提示三角符来折叠和展开 block，当你把鼠标悬停在包含子元素的 block 上时，提示三角符就会出现。当 block 处于编辑模式时，你也能用键盘快捷键执行同样的操作。用 Command-Period(句号符) 和 Command-Comma(逗号符) 键执行内容缩放。当光标位于含有子元素的 block 中时，用 Command-Up 和 Command-Down 键执行内容的折叠和展开。
- **标题**
- 在昨天的课程中，当我们讲到格式的时候，我故意没讲标题的内容。标题与大纲功能结合使用往往更有意义。你可以将任何一个 block 变成三种标题样式之一，在右键菜单中选择 H1、H2 或 H3，也可以用键盘快捷键 Command-Alt-(1 或 2 或 3) 设置它们。用 Command-Alt-0 将把标题格式恢复为标准文本。
- **文档模式**
- 如果你想让页面看起来更像典型的笔记页面，你可以右键点击页面标题选择__View as Document__。这样，除了鼠标悬停的 block 以外，其他 block 的 bullet 都会隐藏，但页面会保留格式缩进。Roam 的功能并没改变。如果你选择所有文本，复制并粘贴到其他编辑器，你会看到复制的内容中没有 bullet，但其他的 markdown 语句是被完整复制的。再次右键点击页面标题，可以将它设回 Bulleted List。也可以选择 Numbered List。你也可以在 block 层面，右键点击 bullet 在这些模式间进行切换。
- **用于导航的键盘快捷键**
- 当你处于编辑模式时，还可以用一些更"高级"的键盘快捷键。如果你的光标位于页面引用或 block 引用中，你可以按 Control-O 键跳转到引用的内容页面。在 block 的其他任何位置按 Control-O 键将会像上面讨论的那样把内容聚焦到该 block 所属的范围。按住 Shift 键点击页面引用或 block 引用，或者按 Control-Shift-O 键则会在侧边栏打开引用的内容。当你使用搜索栏，也能对搜索结果做类似操作。在搜索时，用上下方向键在搜索结果间进行移动。按回车键在页面位置打开内容。按 Shift-Enter 键在侧边栏中打开内容。或者你也可以按住 Shift 键点击搜索结果在侧边栏中打开内容。
- 在明天的课程中，我们将更详细地介绍**侧边栏**。
- 如果你有任何反馈或者迫切想得到回答的问题，欢迎回复这封邮件。我会尽最大努力回复，并将其纳入修订版和今后的课程中。
- 明天见
- Andy Henson
