# 使用工具
请自行 goolge 并安装 aegisub

# 文档目录结构

* 视频文件因为 size 较大，所以放在百度盘上
* `src/` 中为英文的 transcript 
* `translation/` 中为翻译成中文的 transcript
* `chn/` 中为打轴后的中文字幕文件，格式为 `.srt`


# 翻译规范
* 英文的逗号，句号，分号通通换成空格（行末直接去掉）
* 保留问号和感叹号，使用中文的
* 括号使用英文括号，左右各留一个空格
* 破折号保留，使用中文的
* 省略号使用三个英文句号
* 引号保留，使用中文的
* 代码相关：除了字符串以外，所有的返回值，函数名，数值等都不带引号。函数名在函数名后加上英文括号，以区分一般符号和函数名。

# 协作形式

翻译者：

* 请从标记为 `待领取` 的 issues 中领取任务，写清楚预估的 DDL，并分配给自己。任务有三类：
  * `听校` 任务需要对照视频，更正 `src/` 中的英文 transcript 可能的错误
  * `翻译` 任务需要将 `src/` 中的 transcript 翻译成中文 transcript 并放入 `translation/`。
  * `打轴` 任务需要将 `translation/` 中的中文提取出来，打上时间轴之后，以 `.srt` 格式放在 `chn/` 文件夹
* 如果超过预估时间无法完成请在 issue 中 at 管理员，说明接替者信息或请管理员重新分配该任务；
* 完成任务后提交 PR

校对员:
* 将 `待校对` 的 PR 更改为 `校对中`，并进行校对
* 校对通过则将 PR 改为 `已校对`，并分配给管理员
* 校对不通过则将 PR 改为 `待修改`，并分配给 PR 提交者

管理员
* 将 `待校对` 的 PR 分配给校对员
* 若 `已校对` 的 PR 可以合并，则直接合并。合并后请及时更新进度表，以及添加新的 issues
* 若 `已校对` 的 PR 不能合并，分配给 PR 提交者并将 PR 标记为 `待修改`


现任管理员：@hymRedemption

现任校对员：@Mr-Wiredancer

# 任务认领情况与进度(deprecated)
任务 | 译者 | 校对 | 进度
---- | ---- | ---- | ---
04 | [lx7575000](https://github.com/lx7575000)| | 正在进行

# 新的进度表
章节 | 听校| 状态 | 翻译| 状态 | 打轴 | 状态 
---- | ---- | ---- | ---- | --- | ---- | ---- 
01 |Mr-Wiredancer | ✔️ |Mr-Wiredancer | ✔️|Mr-Wiredancer | ✔️
02 |Mr-Wiredancer | ✔️ |Mr-Wiredancer | ✔️|Mr-Wiredancer | ✔️
03 |[baurine](https://github.com/baurine) | ✔️ |[baurine](https://github.com/baurine) | ✔️|[baurine](https://github.com/baurine) | ✔️
05 | Mr-Wiredancer| ✔️ | [baurine](https://github.com/baurine) | ✔️
06 | [baurine](https://github.com/baurine) |✔️ | [baurine](https://github.com/baurine) |✔️ | Mr-Wiredancer | ✔️
07 |Mr-Wiredancer |✔️ | [baurine](https://github.com/baurine) |✔️
08 |Mr-Wiredancer |✔️ |Mr-Wiredancer | ✔️| Mr-Wiredancer |  ✔️ 
09 |[baurine](https://github.com/baurine)| ✔️ |[baurine](https://github.com/baurine) | 进行中
10 |Mr-Wiredancer | ✔️ | | 
11 |Mr-Wiredancer |✔️ | | 
12 |[baurine](https://github.com/baurine) |✔️ | | 
13 |[baurine](https://github.com/baurine) |✔️ | | 
14 |[baurine](https://github.com/baurine) |✔️ | | 
15 |[baurine](https://github.com/baurine)|✔️ | | |
16 |[baurine](https://github.com/baurine)|进行中 | | |
17 |Mr-Wiredancer|进行中
18 |[baurine](https://github.com/baurine)|进行中
19 |[baurine](https://github.com/baurine)|进行中
20 |
21 |
22 | 
23 | 
24 |
25 |
26 | 
27 |
28 |
29 |
30 |
