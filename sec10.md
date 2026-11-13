# 智能与未来（第 36—40 集）

> 自然语言处理、机器人、人机交互心理学，最后落到奇点与对未来的判断。

### 第 36 集 自然语言处理-Natural Language Processing（11.8 分钟）
- **主旨**：讲计算机如何理解和使用人类语言，从词性切分、知识图谱、语音识别一路走到用机器学习代替手工规则。
- **关键点**：
  1. 人类语言被称为"自然语言"（natural language），与编程语言那种严格形式化的语言完全不同。
  2. 英语的基本词类被归纳为 9 种 fundamental types of English words：名词 nouns、代词 pronouns、冠词 articles、动词 verbs、形容词 adjectives 等。
  3. 知识图谱（knowledge graph）用节点和带标签的边表示实体与关系，画面给出的规模是"roughly seventy billion facts"（约七百亿条事实），例如《Thriller》→ Michael Jackson、发行年份 1983、时长 5:57。
  4. 一次语音搜索要走完整流水线：先把声波转换成频率（waveform → frequency）的算法处理，再把连续的词切分开（separate words from one another），最后才做语义理解。
  5. 自然语言处理的算法经历了一次同步革新：从人工手写的语法规则（hand-crafted rules），转向能从人类语言语料库中自动学习的机器学习技术（machine learning techniques）。
- **易错/考点**：画面里 Alice/Bob 那段"balls have zero to me to me to me…"的对话实验被媒体渲染得很吓人，但主持人强调那只是实验被夸大报道，不等于机器人真的自创语言。
### 第 37 集 机器人-Robots（12.4 分钟）
- **主旨**：从古代自动机讲到工业机械臂与控制理论，说明机器人是机械、传感器、控制算法和 AI 的组合体。
- **关键点**：
  1. 自动化装置古已有之，很多自动机（automaton）做成动物或人形，能跳舞、唱歌、打鼓。
  2. 工业机器人取代人手的直接原因是精度：飞机螺旋桨等零件的误差容忍度（tolerance）太小，无法手工加工。
  3. 机器人控制的核心是负反馈环（negative feedback loop）：reference 与 measured 比较得出 error，controller 输出 system input，system output 再由 sensor 测回。
  4. PID controller 把 proportional、integral、derivative 三个值按不同权重相加后驱动系统，比单一比例控制更稳。
  5. 科幻作品里的机器人形象之所以流行，是因为它们"安全又便宜"（safe and expedient）；现实中的机器人则是把 AI 等各项技术结合起来的诱人目标。
- **易错/考点**：负反馈环里 sensor 测的是 system output 并回送比较，方向不能画反；PID 是三部分加权求和，不是三选一。
### 第 38 集 计算机心理学-Psychology of Computing（12.6 分钟）
- **主旨**：讲人如何感知和使用计算机界面，以及计算机反过来如何影响人的心理与行为。
- **关键点**：
  1. 视觉感知（visual perception）决定界面布局：颜色块谁在前谁在后、绿色该放哪里，都取决于人眼的知觉规律而非逻辑。
  2. 界面设计大量使用分块（chunking），下拉菜单、按钮、菜单栏把功能按组归类，降低一次要处理的项数。
  3. 拟物化纹理（如"浇花"按钮的 blending/纹理）是为了提示可抓取位置、改善握持感，让用户一眼看出哪里能点、能拖。
  4. 2012 年 Facebook 做过一项"影响用户"（user affect）的研究，通过操纵信息流观察情绪传播，引发伦理争议。
  5. 恐怖谷（uncanny valley）：机器人的可信度（believability）随拟人度上升，但在接近真人之前会突然下跌，产生怪异不安感，之后才回升到 real human。
- **易错/考点**：恐怖谷是曲线中段的"下陷"，不是单调上升；视频会议里"像在向下看"是摄像头位置造成的，不是网络问题。
### 第 39 集 教育科技-Educational Technology（11.9 分钟）
- **主旨**：讲技术一次次宣称要革新教育，以及真正有效的教育软件靠什么设计。
- **关键点**：
  1. 在线视频的观看量高度集中在 Gangnam Style、Despacito 这类娱乐内容上，说明"有技术"不等于"有学习"。
  2. 历史上每一波新技术浪潮都自称要革新教育（revolutionize education），但多数没有兑现。
  3. 真正的难题往往要靠人与技术混合的系统（hybrid human-technology systems）解决，而不是纯软件替代老师。
  4. 智能辅导系统用学生模型（student model）记录学生已掌握的产生式规则（production rules），据此决定下一题；对 3x+7=4 这类题，它知道正确的下一步是两边同减 7。
  5. 系统还要避免"瞎猜的概率"（probability of guess）干扰判断，并挑选最合适的问题来提高效率；即使不是程序员，也可以在纸上写伪代码（pseudocode）试试编程。
- **易错/考点**：学生模型记的是"已掌握哪些规则"，不是"做对了几题"；猜对不等于会做。
### 第 40 集 奇点、天网、计算机的未来-The Singularity, Skynet, and the Future of Computing（12.5 分钟）
- **主旨**：作为全系列收尾，讨论算力增长、奇点（singularity）与人工智能取代人类工作的可能性，以及个人该如何面对。
- **关键点**：
  1. 界面设计的理想被描述为"戏剧性机器"（dramatic machine）：把计算机做得如此有趣，让人一刻也不想离开它。
  2. 算力增长图用对数坐标展示 1900—2100 年的每秒计算次数，把摩尔定律曲线与细菌、蠕虫、人脑放在同一标尺上比较；画面称今天的计算机比 1970 年代强约 10 万倍。
  3. 微软联合创始人保罗·艾伦（Paul Allen）把这种增长受到的制约称为"复杂性刹车"（complexity brake）。
  4. 工作可以用两个维度（job quadrants）来概括，据此判断哪些岗位容易被自动化取代；没人知道未来到底会怎样。
  5. 应对之道是不断上升到新的抽象层次（a new level of abstraction），例如"亿万年后的太阳燃尽、地球化为星尘，我们的机器人孩子继续探索宇宙"这种远景，以及亲自学习计算机、参与这场惊人的转型。
- **易错/考点**：奇点（singularity）指技术增长失控、超出人类预测的临界点，与"天网"（Skynet）这种科幻设定要区分开；算力曲线是对数坐标，直线代表指数增长。
---
