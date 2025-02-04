<a href="https://colab.research.google.com/github/GoogTech/langchain-learning-note/blob/master/langchain_learning_note.ipynb">
<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>
<br>
<br>

版本信息：
```
langchain                          0.3.16
langchain-community                0.3.16
langchain-core                     0.3.33
langchain-openai                   0.3.3
```

学习笔记目录结构：
```
01.Hello Langchain
└── 1.安装最新版的库: langchain, openai
└── 2.核查库版本号
└── 3.安装 langchain_community
└── 4.尝试运行第一个 langchain 程序

02.模型 Model
└── 1.模型的类型
    └── 1.1.大语言模型 LLM
    └── 1.2.对话模型 ChatModel
    └── 1.3.嵌入模型 EmbeddingModel
└── 2.OpenAI 主要模型介绍（GPT 系列 & 嵌入模型）
    └── 2.1.GPT 系列（文本生成 & 对话）
        └── 2.1.1.普通文本生成
        └── 2.1.2.多轮对话（ChatGPT模式）
    └── 2.2.OpenAI Embeddings（文本向量化）
    └── 2.3.简洁总结
    └── 2.4.注意事项⭐️
        └── 2.4.1.ChatOpenAI 将代替 OpenAI
        └── 2.4.2.gpt-3.5-turbo-instruct 取代了 gpt-3.5-turbo

03.数据连接 Data Connection
└── 1.数据链接简介
└── 2.数据连接步骤
    └── 2.1.加载文档
    └── 2.2.拆分文档
        └── 2.2.1.按字符拆分
        └── 2.2.2.拆分代码
        └── 2.2.3.Markdowm 文档拆分
        └── 2.2.4.按字符递归拆分
        └── 2.2.5.按 token 拆分
    └── 2.3.向量化文档分块
    └── 2.4.向量数据存储 & 检索
        └── 2.4.1.向量数据存储
        └── 2.4.2.向量数据检索

04.提示词模版 Prompt
└── 1.PromptTemplate
    └── 1.1.基础使用实例
    └── 1.2.模拟简单的问答场景
└── 2.ChatPromptTemplate
    └── 2.1.基础使用实例
    └── 2.2.模拟旅游推荐助手

05.输出解释器 Ouput Parser
└── 1.相关知识点
└── 2.输出解析器的作用
└── 3.常见的输出解析器
    └── 3.1.解释器 PydanticOutputParser
    └── 3.2.解释器 RegexParser
    └── 3.3.解释器 CommaSeparatedListOutputParser
    └── 3.4.自定义解释器

06.链 Chain
└── 1.核心组件(相关知识点)
└── 2.基本工作流程
└── 3.类型及程序实例
    └── 3.1.使用 LLMChain 处理简单任务
    └── 3.2.使用 SequentialChain 执行多步骤任务
    └── 3.3.使用 RouterChain 实现动态路由❌
    └── 3.4.使用 TransformChain 自定义数据转换逻辑
    └── 3.5.自定义链

07.记忆组件 Memory
└── 1.ConversationBufferMemory（对话缓冲记忆）
└── 2.ConversationSummaryMemory（对话摘要记忆）
└── 3.ConversationBufferWindowMemory（对话窗口记忆）
└── 4.ConversationKGMemory（知识图谱记忆）
└── 5.简洁总结

08.代理 Agent
└── 1.代理 Agent 与链 Chain 的区别
└── 2.代理的核心组件
└── 3.代理的类型
    └── 2.1.Zero-shot Agent 程序示例
    └── 2.2.ReAct Agent 程序示例
    └── 2.3.OpenAI Functions Agent 程序示例

09.回调 Callback
└── 1.常见的回调方法
└── 2.程序示例：简单回调日志记录
```
