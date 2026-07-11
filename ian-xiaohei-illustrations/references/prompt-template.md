# 全局强制约束（置顶优先级最高）
最高优先级：先读取并严格遵循 character-turnaround.png 三视图参考。小女孩必须保持1.5头身，大头小身体，短手短脚，黄色长卷发，头顶左侧浅蓝色小鱼发卡，蓝色背带裤，白色内搭，黄色小圆扣。禁止改变角色比例、发型、服装、发卡位置和整体软萌蜡笔风格。
整张插图唯一核心主体为【1.5头身黄发小鱼发卡蓝背带裤蜡笔小女孩】，全程禁止出现原版黑色椭圆小黑；角色必须放在画面视觉中心，用全身动作诠释文案内容，不能放在角落；严格锁定角色造型，不更改黄色长发、浅蓝色小鱼发卡、天蓝色背带裤三件标志性外观；整体16:9纯白背景，大面积留白，抖动蜡笔短线手绘质感，仅少量红/橙色手写中文短句标注，一张图只表达一个概念。

# 生图提示词模板
每张图单独生成。根据正文内容替换变量，不要把多张图拼在一起。
```text
Generate one standalone 16:9 horizontal Chinese article illustration.
Reference first: always follow the character turnaround image. The character must have a 1.5 head-to-body ratio, large head, small body, short round limbs, blonde long curly hair, light blue fish hairclip, blue overalls, white inner shirt, yellow buttons.

Visual DNA:
Pure white background. Minimalist crayon hand-drawn line art. Slightly wobbly short crayon stroke lines. Lots of empty white space. Sparse red/orange/blue handwritten Chinese annotations. Clean absurd product-sketch feeling. No gradients, no shadows, no paper texture, no complex background, no commercial vector style, no PPT infographic look, no over-sweet cute mascot poster, no heavy children's illustration, no realistic UI.

Recurring IP character required:
【强制1.5头身，超大头部、极小短圆身体四肢，幼态Q版，严禁正常人体比例】1.5头身 Q版小女孩，浅金黄色中长卷发，齐刘海，头顶左侧佩戴浅蓝色小鱼形状发卡，圆圆的深棕色大眼睛，两团圆形淡粉色腮红，纯白色内搭+宽松天蓝色卷边背带裤，四肢短短圆圆，全部线条为断续蜡笔短线，软萌冷静平淡表情，手绘不均匀圆润身体轮廓。小女孩必须执行画面核心概念动作，不能仅作为场景装饰，整体气质干净克制，不刻意甜腻。


Theme:
{正文配图主题}

Structure type:
{结构类型：Workflow / 系统局部 / 前后对比 / 角色状态 / 概念隐喻 / 方法分层 / 地图路线 / 小漫画分镜}

Core idea:
{这张图要表达的核心意思}

Composition:
{具体画面：小女孩在哪里、正在做什么、主要物件是什么、信息如何流动}

Suggested elements:
{元素1} / {元素2} / {元素3} / {元素4}

Chinese handwritten labels:
{标注词1} / {标注词2} / {标注词3} / {标注词4} / {可选标注词5}

Color use:
Black for main line art. Orange for main flow/path/arrows. Red only for key warnings/problems/results. Blue only for secondary notes or feedback/system state；小女孩固定配色：#FFE899金黄色头发、#89C8FF小鱼发卡、#5799E8天蓝色背带裤、#FFC8D0淡粉色腮红。

Constraints:
One image explains only one core structure. Keep the main subject (小女孩) around 40%-60% of the canvas. Preserve at least 35% blank white space. Use at most 5-8 short handwritten Chinese labels. Do not write a title in the top-left corner. Do not write the structure type on the image. Do not make it a formal diagram, course slide, or dense explainer. Do not copy prior examples or reuse known case compositions unless explicitly requested; invent a fresh visual metaphor for this specific article. It should be clear but not instructional, interesting but not childish, strange but clean.
```

## 图像编辑提示

去掉左上角标题：

```text
Edit the provided image. Remove only the handwritten title "{要删除的文字}" and its underline from the top-left corner. Fill that area with the same clean white background, matching the surrounding blank paper. Preserve everything else exactly: the little girl IP character, labels, paths, line style, composition, aspect ratio, and image quality. Do not add any new text or objects.
```

强化角色主体存在感：

```text
Regenerate this illustration with the same core meaning and simple layout, but make the yellow-haired little girl with fish hairpin more central to the conceptual action. The little girl should be doing the core work that explains the idea, not standing beside the diagram. Keep it clean, sparse, crayon hand-drawn style.
```
