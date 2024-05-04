微信公众号：西书北影。

欢迎交流！日后将把大模型相关的实践实时更新。

## 项目介绍
本项目包含三部分：

1.向量模型垂域微调：基于llama_index和qwen微调BGE向量模型。http://t.csdnimg.cn/vSmRW

2.大模型垂域微调：基于PEFT微调qwen1.5-7b-chat，做了sft和dpo。http://t.csdnimg.cn/ndZ47

3.高阶检索增强生成(RAG)系统：基于以上垂域化工作，实现两阶段的RAG系统。增加了query改写、召回重排、检索重排、多轮对话等。http://t.csdnimg.cn/6nw4D

## 硬件配置

显卡：L20(48GB) * 1 
内存：100GB

## 环境配置

1部分的Python环境配置是：
```
cd enhance_llm/ebedding_finetune
pip install -r requirements.txt
```

2.3部分的Python环境配置是：
```
cd enhance_llm
pip install -r requirements.txt
```

## star_history

<iframe style="width:100%;height:auto;min-width:600px;min-height:400px;" src="https://star-history.com/embed?secret=Z2hwX3F4TW1KQWM2MEpscEtlS0NkYW5TbEhzTEV1SjNMZjNEVWxscA==#stay-leave/enhance_llm&Date" frameBorder="0"></iframe>


## LICENSE

enhance_llm is licensed under Apache 2.0 License


