# ReasoningLLM - 推理类大模型

[← 返回主页](../README.md#reasoningllm)

> 收集推理能力比较突出的中文大模型


> 收集推理能力比较突出的中文大模型

|            模型            |            大小            | 时间      |  语言 |  领域 |                                                                     下载                                                                    |                                        项目地址                                       |                              机构/个人                             |   结构   |                                                                                 文                                                                                 |
| :----------------------: | :----------------------: | ------- | :-: | :-: | :---------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------: | :------------------------------------------------------------: | :----: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|        Hy4-preview        |         A49/770B         | 2026-08 |  中英 |  通用 |                                             [🤗HF](https://huggingface.co/tencent/Hy4-preview)                                            |                                 [Hy4-preview](https://github.com/Tencent-Hunyuan/Hy4-preview)                                 |      [Tencent-Hunyuan](https://github.com/Tencent-Hunyuan)     |   MoE  |                          Gated DSA 稀疏注意力+IndexCache 跨层索引复用，iHC 残差，1M 上下文，内置 MTP 推测解码，Apache-2.0 开源                          |
|       GLM-5.3-Flash       |         A18/320B         | 2026-08 |  中英 | 多模态 |                                          [🤗HF](https://huggingface.co/zai-org/GLM-5.3-Flash)                                           |                                    [GLM-5](https://github.com/zai-org/GLM-5)                                    |              [zai-org](https://github.com/zai-org)             |   MoE  |                     [Blog](https://z.ai/blog/glm-5.3-flash)，GLM-5 首个原生多模态，稀疏+线性注意力混合架构，mHC，MIT 开源                      |
|          GLM-5.3          |             /            | 2026-08 |  中英 |  通用 |                                             [🤗HF](https://huggingface.co/zai-org/GLM-5.3)                                              |                                    [GLM-5](https://github.com/zai-org/GLM-5)                                    |              [zai-org](https://github.com/zai-org)             |   MoE  |                                [Tech Report](https://arxiv.org/abs/2602.15763)，与 GLM-5.2 同底座，开放权重编码 SOTA，CyberGym 漏洞发现 SOTA                                |
|     Qwen3.8-Flash-Next    |         A6/180B          | 2026-08 |  中英 |  通用 |                                        [🤗HF](https://huggingface.co/Qwen/Qwen3.8-Flash-Next)                                          |                             [Qwen3.8-Flash-Next](https://github.com/QwenLM/Qwen3.8-Flash-Next)                             |               [QwenLM](https://github.com/QwenLM)              |   MoE  |                     [Blog](https://qwen.ai/blog?id=qwen3.8-flash-next)，Qwen4 架构预览，QSA 稀疏注意力+N-gram Embedding，262K→1M 上下文                      |
|    Ornith-1.5-35B-A3B     |           A3/35B         | 2026-08 |  中英 |  代码 |                                       [🤗HF](https://huggingface.co/ornith-ai/Ornith-1.5-35B-A3B)                                        |                                         /                                         |            [ornith-ai](https://huggingface.co/ornith-ai)        |   MoE  |                            [Blog](https://ornith.ai/ornith_1_5.html)，端到端自改进（任务生成+scaffold+rollout 联合优化），MIT 开源                            |
|        Qwen3.8-27B        |            27B           | 2026-08 |  中英 | 多模态 |                                            [🤗HF](https://huggingface.co/Qwen/Qwen3.8-27B)                                              |                                         /                                         |               [QwenLM](https://github.com/QwenLM)              |  Dense |                                   原生视觉语言模型，支持图像/视频理解，灵活思考控制，262K→1M 上下文，Apache-2.0 开源                                   |
|         Kimi-K3           |         A104/2.8T        | 2026-06 |  中英 |  通用 |                                            [🤗HF](https://huggingface.co/moonshotai/Kimi-K3)                                            |                                     [Kimi-K3](https://github.com/MoonshotAI/Kimi-K3)                                   |           [MoonshotAI](https://github.com/MoonshotAI)          |   MoE  |                    [Tech Blog](https://www.kimi.com/blog/kimi-k3)，全球首个开放 3T 级模型，KDA+AttnRes 架构，原生多模态，1M 上下文                    |
|          GLM-5.2           |             /            | 2026-06 |  中英 |  通用 |                                           [🤗HF](https://huggingface.co/zai-org/GLM-5.2)                                                  |                                         /                                         |              [zai-org](https://github.com/zai-org)             |   /    |                     [Blog](https://z.ai/blog/glm-5.2)，1M上下文，IndexShare稀疏注意力，MTP推测解码，MIT开源                      |
|       Kimi-K2.7-Code       |          A32/1T          | 2026-06 |  中英 |  代码 |                                           [🤗HF](https://huggingface.co/moonshotai/Kimi-K2.7-Code)                                          |                                         /                                         |           [MoonshotAI](https://github.com/MoonshotAI)          |   MoE  |                                         coding-focused agentic model，thinking-token 降低约 30%                                         |
|         MiniMax-M3         |         A23/428B         | 2026-06 |  中英 | 多模态 |                                           [🤗HF](https://huggingface.co/MiniMaxAI/MiniMax-M3)                                           |                                         /                                         |           [MiniMax-AI](https://github.com/MiniMax-AI)          |   MoE  |                              native multimodal model，1M context，MSA 稀疏注意力，9× prefill / 15× decode 加速                              |
|    DeepSeek-V4-Pro   |         A49/1.6T         | 2026-04 |  中英 |  通用 |                                         [🤗HF](https://huggingface.co/collections/deepseek-ai/deepseek-v4)                                        |                 [DeepSeek-V4](https://github.com/deepseek-ai/DeepSeek-V4)                 |            [deepseek-ai](https://github.com/deepseek-ai)           |   MoE  |                                    **[Tech Report](https://huggingface.co/deepseek-ai/DeepSeek-V4-Pro/blob/main/DeepSeek_V4.pdf)**                                    |
|   DeepSeek-V4-Flash  |         A13/284B         | 2026-04 |  中英 |  通用 |                                         [🤗HF](https://huggingface.co/collections/deepseek-ai/deepseek-v4)                                        |                 [DeepSeek-V4](https://github.com/deepseek-ai/DeepSeek-V4)                 |            [deepseek-ai](https://github.com/deepseek-ai)           |   MoE  |                                    **[Tech Report](https://huggingface.co/deepseek-ai/DeepSeek-V4-Pro/blob/main/DeepSeek_V4.pdf)**                                    |
|       MiMo-V2.5-Pro      |         A42/1.02T        | 2026-04 |  中英 |  通用 |                                         [🤗HF](https://huggingface.co/XiaomiMiMo/MiMo-V2.5-Pro)                                       |                 [MiMo](https://github.com/XiaomiMiMo/MiMo)                 |            [XiaomiMiMo](https://github.com/XiaomiMiMo)           |   MoE  |                                    [Tech Report](https://mimo.xiaomi.com/mimo-v2-5-pro)                                    |
|         Kimi-K2.6        |          A32/1T          | 2026-04 |  中英 |  通用 |                                            [🤗HF](https://huggingface.co/moonshotai/Kimi-K2.6)                                            |                [Kimi-K2.6](https://github.com/MoonshotAI/Kimi-K2.6)               |           [MoonshotAI](https://github.com/MoonshotAI)          |   MoE  |                                                          [Tech Blog](https://www.kimi.com/blog/kimi-k2-6)                                                         |
|          Qwen3.6         |          A3/35B          | 2026-04 |  中英 |  通用 |                                            [🤗HF](https://huggingface.co/Qwen/Qwen3.6-35B-A3B)                                            |                    [Qwen3.6](https://github.com/QwenLM/Qwen3.6)                   |               [QwenLM](https://github.com/QwenLM)              |   MoE  |                                                          [Blog](https://qwen.ai/blog?id=qwen3.6-35b-a3b)                                                          |
|       MiniMax-M2.7       |         A10/230B         | 2026-04 |  中英 |  通用 |                                           [🤗HF](https://huggingface.co/MiniMaxAI/MiniMax-M2.7)                                           |                [GitHub](https://github.com/MiniMax-AI/MiniMax-M2.7)               |           [MiniMax-AI](https://github.com/MiniMax-AI)          |   MoE  |                                                         [Blog](https://www.minimax.io/news/minimax-m27-en)                                                        |
|          Qwen3.5         | 0.5/2/4/9/27/35/122/397B | 2026-02 |  中英 |  通用 |                                           [🤗HF](https://huggingface.co/collections/Qwen/qwen35)                                          |                    [Qwen3.5](https://github.com/QwenLM/Qwen3.5)                   |               [QwenLM](https://github.com/QwenLM)              |   MoE  |                                                              [Blog](https://qwen.ai/blog?id=qwen3.5)                                                              |
|      Step-3.5-Flash      |             /            | 2026-02 |  中英 |  通用 |                                          [🤗HF](https://huggingface.co/stepfun-ai/Step-3.5-Flash)                                         |                                         /                                         |           [stepfun-ai](https://github.com/stepfun-ai)          |    /   |                                                                                 /                                                                                 |
|           GLM-5          |         A40/744B         | 2026-02 |  中英 |  通用 |                                                [🤗HF](https://huggingface.co/zai-org/GLM-5)                                               |                                         /                                         |              [zai-org](https://github.com/zai-org)             |    /   |                                                                  [blog](https://z.ai/blog/glm-5)                                                                  |
|       MiniMax-M2.5       |             /            | 2026-02 |  中英 |  通用 |                                           [🤗HF](https://huggingface.co/MiniMaxAI/MiniMax-M2.5)                                           |                                         /                                         |          [MiniMaxAI](https://huggingface.co/MiniMaxAI)         |    /   |                                                                                 /                                                                                 |
|         Kimi-K2.5        |            1T            | 2026-02 |  中英 |  通用 |                                            [🤗HF](https://huggingface.co/moonshotai/Kimi-K2.5)                                            |                                         /                                         |         [moonshotai](https://huggingface.co/moonshotai)        |   moe  |                                                             [paper](https://arxiv.org/abs/2602.02276)                                                             |
|        Ring-2.5-1T       |            1T            | 2026-02 |  中英 |  通用 |                                           [🤗HF](https://huggingface.co/inclusionAI/Ring-2.5-1T)                                          |                                         /                                         |        [inclusionAI](https://huggingface.co/inclusionAI)       |    /   |                                                                                 /                                                                                 |
|        Ring-2.6-1T       |            1T            | 2026-05 |  中英 |  通用 |                                           [🤗HF](https://huggingface.co/inclusionAI/Ring-2.6-1T)                                          |                                         /                                         |        [inclusionAI](https://huggingface.co/inclusionAI)       |    /   |                                    万亿参数旗舰推理模型，支持 Agent 执行、Reasoning Effort 机制、异步强化学习训练                                    |
|       Ling-2.6-1T        |            1T            | 2026-05 |  中英 |  通用 |                                           [🤗HF](https://huggingface.co/inclusionAI/Ling-2.6-1T)                                          |                                         /                                         |        [inclusionAI](https://huggingface.co/inclusionAI)       |    /   |                                    万亿参数旗舰模型，MLA+Linear Attention 混合架构，Fast Thinking 机制，Agent 工作流优化                                    |
|      Ling-2.6-flash      |         104B / A7.4B     | 2026-05 |  中英 |  通用 |                                           [🤗HF](https://huggingface.co/inclusionAI/Ling-2.6-flash)                                       |                                         /                                         |        [inclusionAI](https://huggingface.co/inclusionAI)       |    /   |                                    推理效率优化模型，104B 总参数/7.4B 激活参数，面向高频 Agent 场景                                    |
|       DeepSeek-V3.2      |             /            | 2025-12 |  中英 |  通用 |                                          [🤗HF](https://huggingface.co/deepseek-ai/DeepSeek-V3.2)                                         |       [DeepSeek-V3.2-Exp](https://github.com/deepseek-ai/DeepSeek-V3.2-Exp)       |          [deepseek-ai](https://github.com/deepseek-ai)         |   MoE  |                                **[Technical Report](https://huggingface.co/deepseek-ai/DeepSeek-V3.2/blob/main/assets/paper.pdf)**                                |
|  **Tongyi DeepResearch** |          A3/30B          | 2025-09 |  中英 |  通用 |                                   [🤗HF](https://huggingface.co/Alibaba-NLP/Tongyi-DeepResearch-30B-A3B)                                  |            [DeepResearch](https://github.com/Alibaba-NLP/DeepResearch)            |          [Alibaba-NLP](https://github.com/Alibaba-NLP)         |   MoE  |                                         [Tech Blog](https://tongyi-agent.github.io/blog/introducing-tongyi-deep-research)                                         |
|      **Qwen3-Next**      |          A3/80B          | 2025-09 |  中英 |  通用 |                                      [🤗HF](https://huggingface.co/Qwen/Qwen3-Next-80B-A3B-Thinking)                                      |                      [Qwen3](https://github.com/QwenLM/Qwen3)                     |               [QwenLM](https://github.com/QwenLM)              |   MoE  |                       [Qwen3-Next](https://qwen.ai/blog?id=4074cca80393150c248e508aa62983f9cb7d27cd\&from=research.latest-advancements-list)                      |
|    Magistral Small 1.2   |            24B           | 2025-09 |  多语 |  通用 |                                  **[Hugging Face](https://huggingface.co/baichuan-inc/Baichuan-M2-32B)**                                  |                                         /                                         |          [mistralai](https://huggingface.co/mistralai)         |   CD   |                                                          [blog post](https://mistral.ai/news/magistral/)                                                          |
|        gpt-oss-20B       |          A2/20B          | 2025-08 |  中英 |  通用 |                                             [🤗HF](https://huggingface.co/openai/gpt-oss-20b)                                             |                    [gpt-oss](https://github.com/openai/gpt-oss)                   |               [openai](https://github.com/openai)              |   MoE  |                                                  **[OpenAI blog](https://openai.com/index/introducing-gpt-oss/)**                                                 |
|       gpt-oss-120B       |          A5/120B         | 2025-08 |  中英 |  通用 |                                        [🤗HF](https://huggingface.co/tencent/Hunyuan-0.5B-Instruct)                                       |                    [gpt-oss](https://github.com/openai/gpt-oss)                   |               [openai](https://github.com/openai)              |   MoE  |                                                  **[OpenAI blog](https://openai.com/index/introducing-gpt-oss/)**                                                 |
|        Baichuan-M2       |            32B           | 2025-08 |  中英 |  医疗 |                                  **[Hugging Face](https://huggingface.co/baichuan-inc/Baichuan-M2-32B)**                                  |         [Baichuan-M2-32B](https://github.com/baichuan-inc/Baichuan-M2-32B)        |         [baichuan-inc](https://github.com/baichuan-inc)        |   CD   |                                                   [technical blog](https://www.baichuan-ai.com/blog/baichuan-M2)                                                  |
|        **Ovis2.5**       |           2/9B           | 2025-08 |  中英 | 多模态 |                                             [🤗HF](https://huggingface.co/AIDC-AI/Ovis2.5-9B)                                             |                      [Ovis](https://github.com/AIDC-AI/Ovis)                      |              [AIDC-AI](https://github.com/AIDC-AI)             |   CD   |                                                             [Paper](https://arxiv.org/abs/2405.20797)                                                             |
|         GLM-4.5V         |           108B           | 2025-07 |  中英 | 多模态 |                                        **[Hugging Face](https://huggingface.co/zai-org/GLM-4.5V)**                                        |                     [GLM-V](https://github.com/zai-org/GLM-V)                     |              [zai-org](https://github.com/zai-org)             |   MoE  |                                                             [Paper](https://arxiv.org/abs/2507.01006)                                                             |
|          GLM-4.5         |         A32/355B         | 2025-07 |  中英 |  通用 |                                      **[Hugging Face](https://huggingface.co/zai-org/GLM-4.5-Base)**                                      |                   [GLM-4.5](https://github.com/zai-org/GLM-4.5)                   |              [zai-org](https://github.com/zai-org)             |   MoE  |                                                            [technical blog](https://z.ai/blog/glm-4.5)                                                            |
|        GLM-4.5-Air       |         106B-A12B        | 2025-07 |  中英 |  通用 |                                      **[Hugging Face](https://huggingface.co/zai-org/GLM-4.5-Base)**                                      |                   [GLM-4.5](https://github.com/zai-org/GLM-4.5)                   |              [zai-org](https://github.com/zai-org)             |   MoE  |                                                            [technical blog](https://z.ai/blog/glm-4.5)                                                            |
|          Hunyuan         |         0.5/4/7B         | 2025-07 |  中英 |  通用 |                                        [🤗HF](https://huggingface.co/tencent/Hunyuan-0.5B-Instruct)                                       |               [Tencent-Hunyuan](https://github.com/Tencent-Hunyuan)               |      [Tencent-Hunyuan](https://github.com/Tencent-Hunyuan)     |    /   |                                                                                 /                                                                                 |
|    Qwen3-Thinking-2507   |          A3/30B          | 2025-07 |  中英 |  通用 | **[🤗 Huggingface](https://huggingface.co/Qwen/Qwen3-30B-A3B-Thinking-2507)**[](https://huggingface.co/Qwen/Qwen3-30B-A3B-Thinking-2507)  |                      [Qwen3](https://github.com/QwenLM/Qwen3)                     |               [QwenLM](https://github.com/QwenLM)              |   MoE  |                                                             [Paper](https://arxiv.org/abs/2505.09388)                                                             |
|           Step3          |         A38/321B         | 2025-07 |  中英 | 多模态 |                                               [HF](https://huggingface.co/stepfun-ai/step3)                                               |                    [Step3](https://github.com/stepfun-ai/Step3)                   |           [stepfun-ai](https://github.com/stepfun-ai)          |   MoE  |                                                             [Paper](https://arxiv.org/abs/2507.19427)                                                             |
|      Dhanishtha-2.0      |            14B           | 2025-07 |  多语 |  通用 |                                **[Hugging Face](https://huggingface.co/HelpingAI/Dhanishtha-2.0-preview)**                                |                                         /                                         |          [HelpingAI](https://huggingface.co/HelpingAI)         |   CD   |                                                                                 /                                                                                 |
|     GLM-4.1V-Thinking    |            9B            | 2025-07 |  中英 | 多模态 |                                         [🤗HF](https://huggingface.co/THUDM/GLM-4.1V-9B-Thinking)                                         |          [GLM-4.1V-Thinking](https://github.com/THUDM/GLM-4.1V-Thinking)          |                [THUDM](https://github.com/THUDM)               |    /   |                                                             [paper](https://arxiv.org/abs/2507.01006)                                                             |
|   Kimi-VL-Thinking-2506  |            A3B           | 2025-06 |  中英 | 多模态 |                                    [🤗HF](https://huggingface.co/moonshotai/Kimi-VL-A3B-Thinking-2506)                                    |                  [Kimi-VL](https://github.com/MoonshotAI/Kimi-VL)                 |       [MoonshotAI](https://github.com/MoonshotAI/Kimi-VL)      |    /   |                                    **[📄 Tech Report](https://arxiv.org/abs/2504.07491)**[](https://arxiv.org/abs/2504.07491)                                     |
|       Hunyuan-A13B       |          A13/80B         | 2025-06 |  中英 |  通用 |                                  **[Hugging Face](https://huggingface.co/tencent/Hunyuan-A13B-Instruct)**                                 |          [Hunyuan-A13B](https://github.com/Tencent-Hunyuan/Hunyuan-A13B)          |      [Tencent-Hunyuan](https://github.com/Tencent-Hunyuan)     |   MoE  |                     **[Technical Report](https://github.com/Tencent-Hunyuan/Hunyuan-A13B/blob/main/report/Hunyuan_A13B_Technical_Report.pdf)**                    |
|      LongWriter-Zero     |            32B           | 2025-06 |  中英 |  /  |                                         [🤗HF](https://huggingface.co/THU-KEG/LongWriter-Zero-32B)                                        |                                         /                                         |              [THU-KEG](https://github.com/THU-KEG)             |    /   |                                                             [Paper](https://arxiv.org/abs/2506.18841)                                                             |
|        MiniMax-M1        |         A46/456B         | 2025-06 |  中英 |  通用 |                                                  [🤗HF](https://huggingface.co/MiniMaxAI)                                                 |               [MiniMax-M1](https://github.com/MiniMax-AI/MiniMax-M1)              |           [MiniMax-AI](https://github.com/MiniMax-AI)          |   MoE  |                                                             [Paper](https://arxiv.org/abs/2506.13585)                                                             |
|     DeepSeek-R1-0528     |         A37/671B         | 2025-05 |  中英 |  通用 |                                           [🤗HF](https://huggingface.co/deepseek-ai/DeepSeek-R1)                                          |             [DeepSeek-R1](https://github.com/deepseek-ai/DeepSeek-R1)             |          [deepseek-ai](https://github.com/deepseek-ai)         |   MoE  | **[Paper Link](https://github.com/deepseek-ai/DeepSeek-R1/blob/main/DeepSeek_R1.pdf)**[👁️](https://github.com/deepseek-ai/DeepSeek-R1/blob/main/DeepSeek_R1.pdf) |
|        QwenLong-L1       |            32B           | 2025-05 |  中英 |  通用 |                                        [🤗HF](https://huggingface.co/Tongyi-Zhiwen/QwenLong-L1-32B)                                       |            [QwenLong-L1](https://github.com/Tongyi-Zhiwen/QwenLong-L1)            |        [Tongyi-Zhiwen](https://github.com/Tongyi-Zhiwen)       |   CD   |                                                             [Paper](https://arxiv.org/abs/2505.17667)                                                             |
|        GLM-Z1-0414       |            32B           | 2025-04 |  中英 |  通用 |                            [🤗HF](https://huggingface.co/collections/THUDM/glm-4-0414-67f3cbcb34dd9d252707cb2e)                           |                      [GLM-4](https://github.com/THUDM/GLM-4)                      |                [THUDM](https://github.com/THUDM)               |
|         DeepCoder        |          1.5/14B         | 2025-04 |  中英 |  代码 |                                     [🤗HF](https://huggingface.co/agentica-org/DeepCoder-14B-Preview)                                     |                  [rllm](https://github.com/agentica-project/rllm)                 |     [agentica-project](https://github.com/agentica-project)    |   CD   |
|     Kimi-VL-Thinking     |          A3/16B          | 2025-04 |  中英 | 多模态 |                                       [🤗HF](https://huggingface.co/moonshotai/Kimi-VL-A3B-Thinking)                                      |                  [Kimi-VL](https://github.com/MoonshotAI/Kimi-VL)                 |           [MoonshotAI](https://github.com/MoonshotAI)          |   MoE  |                                      **[Tech Report](https://arxiv.org/abs/2504.07491)**[](https://arxiv.org/abs/2504.07491)                                      |
|        Skywork-OR1       |           7/32B          | 2025-04 |  中英 |  通用 |                                       [🤗HF](https://huggingface.co/Skywork/Skywork-OR1-32B-Preview)                                      |              [Skywork-OR1](https://github.com/SkyworkAI/Skywork-OR1)              |           [SkyworkAI](https://github.com/SkyworkAI)/           |   MoE  |                      [Notion Blog](https://capricious-hydrogen-41c.notion.site/Skywork-Open-Reaonser-Series-1d0bc9ae823a80459b46c149e4f51680)                     |
|        Skywork-R1V       |            38B           | 2025-03 |  中英 | 多模态 |                                           [🤗HF](https://huggingface.co/Skywork/Skywork-R1V-38B)                                          |              [Skywork-R1V](https://github.com/SkyworkAI/Skywork-R1V)              |            [SkyworkAI](https://github.com/SkyworkAI)           |   CD   |                                            [Paper](https://github.com/SkyworkAI/Skywork-R1V/blob/main/Skywork_R1V.pdf)                                            |
|          Fin-R1          |            7B            | 2025-03 |  中英 |  金融 |                                            [🤗HF](https://huggingface.co/SUFE-AIFLM-Lab/Fin-R1)                                           |                 [Fin-R1](https://github.com/SUFE-AIFLM-Lab/Fin-R1)                |       [SUFE-AIFLM-Lab](https://github.com/SUFE-AIFLM-Lab)      |   CD   |                                                             [Paper](https://arxiv.org/abs/2503.16252)                                                             |
|          QwQ-32B         |            32B           | 2025-03 |  中英 |  通用 |                                                [🤗HF](https://huggingface.co/Qwen/QwQ-32B)                                                |                                         /                                         |               [QwenLM](https://github.com/QwenLM)              |   CD   |                                                         [📑 blog](https://qwenlm.github.io/blog/qwq-32b/)                                                         |
|        DeepSeek-R1       |         A37/671B         | 2025-01 |  中英 |  通用 |                                           [🤗HF](https://huggingface.co/deepseek-ai/DeepSeek-R1)                                          |             [DeepSeek-R1](https://github.com/deepseek-ai/DeepSeek-R1)             |          [deepseek-ai](https://github.com/deepseek-ai)         |   MoE  | **[Paper Link](https://github.com/deepseek-ai/DeepSeek-R1/blob/main/DeepSeek_R1.pdf)**[👁️](https://github.com/deepseek-ai/DeepSeek-R1/blob/main/DeepSeek_R1.pdf) |
|     DeepSeek-R1-Zero     |         A37/671B         | 2025-01 |  中英 |  通用 |                                        [🤗HF](https://huggingface.co/deepseek-ai/DeepSeek-R1-Zero)                                        |             [DeepSeek-R1](https://github.com/deepseek-ai/DeepSeek-R1)             |          [deepseek-ai](https://github.com/deepseek-ai)         |   MoE  | **[Paper Link](https://github.com/deepseek-ai/DeepSeek-R1/blob/main/DeepSeek_R1.pdf)**[👁️](https://github.com/deepseek-ai/DeepSeek-R1/blob/main/DeepSeek_R1.pdf) |
| DeepSeek-R1-Distill-Qwen |       1.5/7/14/32B       | 2025-01 |  中英 |  通用 |                        [🤗HF](https://huggingface.co/collections/deepseek-ai/deepseek-r1-678e1e131c0169c0bc89728d)                        |             [DeepSeek-R1](https://github.com/deepseek-ai/DeepSeek-R1)             |          [deepseek-ai](https://github.com/deepseek-ai)         |   MoE  | **[Paper Link](https://github.com/deepseek-ai/DeepSeek-R1/blob/main/DeepSeek_R1.pdf)**[👁️](https://github.com/deepseek-ai/DeepSeek-R1/blob/main/DeepSeek_R1.pdf) |
|      MiniMax-Text-01     |         A46/456B         | 2025-01 |  中英 |  通用 |                                          [🤗HF](https://huggingface.co/MiniMaxAI/MiniMax-Text-01)                                         |               [MiniMax-01](https://github.com/MiniMax-AI/MiniMax-01)              |           [MiniMax-AI](https://github.com/MiniMax-AI)          |   MoE  |                                                             [Paper](https://arxiv.org/abs/2501.08313)                                                             |
|       MiniMax-VL-01      |         A46/456B         | 2025-01 |  中英 | 多模态 |                                           [🤗HF](https://huggingface.co/MiniMaxAI/MiniMax-VL-01)                                          |               [MiniMax-01](https://github.com/MiniMax-AI/MiniMax-01)              |           [MiniMax-AI](https://github.com/MiniMax-AI)          |   MoE  |                                                             [Paper](https://arxiv.org/abs/2501.08313)                                                             |
|          Sky-T1          |            32B           | 2025-01 |  中英 |  通用 |                                        [🤗HF](https://huggingface.co/NovaSky-AI/Sky-T1-32B-Preview)                                       |               [SkyThought](https://github.com/NovaSky-AI/SkyThought)              |           [NovaSky-AI](https://github.com/NovaSky-AI)          |   CD   |                                                         [Blog](https://novasky-ai.github.io/posts/sky-t1/)                                                        |
|         Search-O1        | 2025-01 |  中英 |  通用 |                                                                     /                                                                     |                [Search-o1](https://github.com/sunnynexus/Search-o1)               |           [sunnynexus](https://github.com/sunnynexus)          |   CD   |                                                             [Paper](https://arxiv.org/abs/2501.05366)                                                             |
|       HuatuoGPT-o1       |        7/8/70/72B        | 2025-01 |  中英 |  医疗 |                    [🤗HF](https://huggingface.co/collections/FreedomIntelligence/huatuogpt-o1-677261a3711767cce7c64e13)                   |        [HuatuoGPT-o1](https://github.com/FreedomIntelligence/HuatuoGPT-o1)        | [FreedomIntelligence](https://github.com/FreedomIntelligence)/ |   CD   |                                                             [Paper](https://arxiv.org/pdf/2412.18925)                                                             |
|      QwQ-32B-Preview     |            32B           | 2024-11 |  中英 |  通用 |                                            [🤗HF](https://huggingface.co/Qwen/QwQ-32B-Preview)                                            |                                         /                                         |               [QwenLM](https://github.com/QwenLM)              |   CD   |
|         Marco-o1         |            7B            | 2024-11 |  中英 |  通用 |                                              [🤗HF](https://huggingface.co/AIDC-AI/Marco-o1)                                              |                  [Marco-o1](https://github.com/AIDC-AI/Marco-o1)                  |              [AIDC-AI](https://github.com/AIDC-AI)             |   CD   |                                                           **[Paper](https://arxiv.org/abs/2411.14405)**                                                           |
|      Skywork-01-Open     |            8B            | 2024-11 |  中英 |  通用 |                        [🤗HF](https://huggingface.co/collections/Skywork/skywork-o1-open-67453df58e12f6c3934738d0)                        | [skywork-o1-prm-inference](https://github.com/SkyworkAI/skywork-o1-prm-inference) |            [SkyworkAI](https://github.com/SkyworkAI)           |   CD   |                                                            [Blog](https://nexusflow.ai/blogs/athene-v2)                                                           |
|          HK-01aw         |            8B            | 2024-11 |  中文 |  法律 |                                              [🤗HF](https://huggingface.co/HKAIR-Lab/HK-O1aw)                                             |                  [HK-O1aw](https://github.com/HKAIR-Lab/HK-O1aw)                  |            [HKAIR-Lab](https://github.com/HKAIR-Lab)           |   CD   |
|      QVQ-72B-Preview     |            72B           | 2024-12 |  中英 |  多模 |                               [🤗 HF](https://huggingface.co/collections/Qwen/qvq-676448c820912236342b9888)                               |                   [Qwen2-VL](https://github.com/QwenLM/Qwen2-VL)                  |               [QwenLM](https://github.com/QwenLM)              |                                                     [Blog](https://qwenlm.github.io/zh/blog/qvq-72b-preview/)                                                     |
|       MiniCPM5-1B        |            1B            | 2026-05 |  中英 |  通用 |                                         [🤗HF](https://huggingface.co/openbmb/MiniCPM5-1B)                                        |               [MiniCPM](https://github.com/OpenBMB/MiniCPM)               |            [OpenBMB](https://github.com/OpenBMB)           |   Dense   |                                    1B 级开源 SOTA  dense Transformer，面向端侧本地部署和资源受限场景                                    |

---

## 模型更新说明

### Hy4-preview

**模型简介**

Hy4-preview 是腾讯混元 Hy 团队推出的新一代 MoE 旗舰模型，总参数 770B、每 token 激活 49B，支持 1M Token 上下文，另内置 1 层原生 MTP（10B 总参数/0.7B 激活）用于推测解码。

**核心亮点**

- **Gated DSA 稀疏注意力**：采用 Gated DeepSeek Sparse Attention，并结合 IndexCache 实现跨层稀疏索引复用，大幅降低长上下文推理开销。
- **iHC 残差连接**：identity Hyper-Connections 扩展层间信息流。
- **大规模 MoE**：78 层，256 路由专家 + 1 共享专家，每 token 激活 top-8 路由专家。
- **Pure Open**：Apache-2.0 开源许可证。

**参考链接**

- [GitHub](https://github.com/Tencent-Hunyuan/Hy4-preview)
- [HuggingFace](https://huggingface.co/tencent/Hy4-preview)

### GLM-5.3

**模型简介**

GLM-5.3 是 zai-org 推出的开放权重旗舰模型，与 GLM-5.2 共用同一底座，全部增益来自后训练，是目前最强的开放权重编码模型。

**核心亮点**

- **Stronger Coding**：在 Z.ai Code Bench 上较 GLM-5.2 提升 50%，并在 Terminal Bench 3.0、Agents' Last Exam 等公开基准上达到开源 SOTA。
- **Emergent Cyber Capability**：在 CyberGym 漏洞发现上达到 SOTA，在利用链基准上较 GLM-5.2 翻倍以上。
- **Flexible Effort**：支持 `reasoning_effort`（low/high/max）思考力度控制。

**参考链接**

- [技术报告](https://arxiv.org/abs/2602.15763)
- [HuggingFace](https://huggingface.co/zai-org/GLM-5.3)

### GLM-5.3-Flash

**模型简介**

GLM-5.3-Flash 是 GLM-5 系列首个原生多模态模型，320B 总参数/18B 激活，以约 1/10 的成本在基准与实际工作负载上超越 GLM-5.2，编码与 agentic 基准接近 Claude Opus 4.8。

**核心亮点**

- **Hybrid Attention**：首次在 GLM 系列引入稀疏+线性注意力混合架构，显著降低长上下文服务成本。
- **mHC**：采用流形约束超连接（Manifold-Constrained Hyper-Connections）提升 scaling 效率。
- **多模态预训练**：基于最新的 30T Token 多模态预训练语料。
- **Pure Open**：MIT 开源许可证。

**参考链接**

- [技术博客](https://z.ai/blog/glm-5.3-flash)
- [HuggingFace](https://huggingface.co/zai-org/GLM-5.3-Flash)

### Qwen3.8-Flash-Next

**模型简介**

Qwen3.8-Flash-Next 是 Qwen 团队发布的 Qwen4 底层架构实验性预览模型，语言模型 125B 总参数/6B 激活，另含 51B N-gram Embedding 与 4B MTP，原生 262K 上下文可扩展至 1M。

**核心亮点**

- **QSA 稀疏注意力**：Gated DeltaNet 与 Qwen Sparse Attention（微块级稀疏）混合架构，显著降低长上下文延迟。
- **Gated Residual**：门控残差流，通过逐元素数据依赖读门与分支标量写门实现细粒度表达。
- **N-gram Embedding**：以短 n-gram 索引实现低算力参数扩展（2 亿规模 bigram/trigram），适合内存受限场景。
- **视觉理解**：带视觉编码器，支持图像输入。

**参考链接**

- [技术博客](https://qwen.ai/blog?id=qwen3.8-flash-next)
- [技术报告](https://github.com/QwenLM/Qwen3.8-Flash-Next/blob/main/tech_report.pdf)
- [HuggingFace](https://huggingface.co/Qwen/Qwen3.8-Flash-Next)

### Qwen3.8-27B

**模型简介**

Qwen3.8-27B 是 Qwen3.8 系列中面向部署友好的紧凑稠密模型（27B），也是原生视觉语言模型，支持图像与视频（含小时级长视频）理解。

**核心亮点**

- **核心能力提升**：编码、专业工作、研究与长程 agentic 任务全面增强，Terminal Bench 2.1 达 73.0、SWE-bench Pro 达 61.7。
- **Agent 执行**：更强的自主规划与环境反馈处理，端到端任务完成更可靠。
- **灵活思考控制**：thinking 默认开启可按请求关闭，支持 `reasoning_effort` 调节推理深度，`preserve_thinking` 保留历史思考上下文。
- **Pure Open**：Apache-2.0 开源许可证。

**参考链接**

- [HuggingFace](https://huggingface.co/Qwen/Qwen3.8-27B)

### Ornith-1.5-35B-A3B

**模型简介**

Ornith-1.5-35B-A3B 是 ornith-ai 推出的端到端自改进基础模型，35B 总参数 MoE、每 token 仅激活约 3B；在 Ornith-1.0（基于 Qwen3.5 与 Gemma4 继续训练）基础上，将自改进循环从 scaffold/rollout 优化扩展到任务生成、scaffold 构建与解法 rollout 的联合优化。

**核心亮点**

- **自改进闭环**：不依赖人工固定任务与手工 harness，持续生成新训练任务、发现有效解题策略并通过强化学习改进策略。
- **编码与 agentic 能力**：全面超越同尺寸 Qwen3.6-35B，SWE-bench Verified 达 79，Terminal-Bench 2.1 达 67.8。
- **Pure Open**：MIT 开源许可证。

**参考链接**

- [技术博客](https://ornith.ai/ornith_1_5.html)
- [HuggingFace](https://huggingface.co/ornith-ai/Ornith-1.5-35B-A3B)

### Kimi K3

**模型简介**

Kimi K3 是 MoonshotAI 最新旗舰模型，总参数 2.8T/激活 104B，是全球首个开放的 3T 级模型；原生多模态，支持文本、图像与视频理解，拥有 1M Token 上下文窗口。

**核心亮点**

- **新架构**：基于 Kimi Delta Attention (KDA) 与 Attention Residuals (AttnRes)，Stable LatentMoE 框架在 896 专家中激活 16 个，整体 scaling 效率较 Kimi K2 提升约 2.5 倍。
- **长程编码**：在最少人工监督下可持续长程工程会话，覆盖 GPU kernel 优化、编译器开发、视觉闭环游戏开发、CAD 乃至芯片设计。
- **Agentic 知识工作**：可产出带交互式可视化、组件与仪表盘的深度研究，以及动效设计与视频编辑。
- **原生多模态与长上下文**：同一模型内理解文本/图像/视频，1M Token 上下文。

**参考链接**

- [技术博客](https://www.kimi.com/blog/kimi-k3)
- [完整技术报告](https://github.com/MoonshotAI/Kimi-K3/blob/main/k3_tech_report.pdf)
- [HuggingFace](https://huggingface.co/moonshotai/Kimi-K3)

### GLM-5.2

**模型简介**

GLM-5.2 是 zai-org 推出的最新旗舰模型，专为长程任务（long-horizon tasks）设计。相比前代 GLM-5.1，它在长程任务能力上实现了实质性飞跃，并首次在稳定的 1M Token 上下文上交付该能力。

**核心亮点**

- **Solid 1M Context**：稳定的 1M Token 上下文，可持续支撑长程工作。
- **Advanced Coding with Flexible Effort**：更强的编码能力，支持多种思考力度（thinking effort levels），以平衡性能与延迟。
- **Improved Architecture**：提出 IndexShare，在每四个稀疏注意力层之间复用相同的索引器，在 1M 上下文长度下将每 Token 的 FLOPs 降低 2.9 倍；同时改进了 MTP 层以支持推测解码，接受长度提升高达 20%。
- **Pure Open**：采用 MIT 开源许可证，无地域限制，技术访问无国界。

**参考链接**

- [技术博客](https://z.ai/blog/glm-5.2)
- [HuggingFace](https://huggingface.co/zai-org/GLM-5.2)

### Kimi K2.7 Code

**模型简介**

Kimi K2.7 Code 是基于 Kimi K2.6 构建的面向代码领域的 agentic 模型，在真实长程编码任务上有显著提升，强化了复杂软件工程工作流中的端到端任务完成能力，同时提升了 token 效率，thinking-token 使用量较 Kimi K2.6 降低约 30%。

**模型概要**

- **架构**：Mixture-of-Experts (MoE)
- **总参数量**：1T
- **激活参数量**：32B
- **层数（含 Dense 层）**：61
- **Dense 层数**：1
- **Attention Hidden Dimension**：7168
- **MoE Hidden Dimension（单专家）**：2048
- **Attention Heads**：64
- **专家总数**：384
- **每 Token 选中专家数**：8
- **共享专家数**：1
- **词表大小**：160K
- **上下文长度**：256K
- **注意力机制**：MLA
- **激活函数**：SwiGLU
- **视觉编码器**：MoonViT（400M 参数）

### MiniMax-M3

**模型简介**

MiniMax-M3 是一个原生多模态模型，支持 1M 上下文。总参数量约 428B，激活参数量约 23B。

**核心亮点**

- **原生多模态**：从训练第一步即进行混合模态训练，实现文本、图像、视频的深度语义融合。
- **稀疏注意力实现上下文扩展**：引入 MiniMax Sparse Attention (MSA)，显著提升长上下文效率。在 1M 上下文场景下，相比 M2 实现 9 倍 prefill 加速和 15 倍 decode 加速，单 token 计算量降至 1/20。
- **编码与协作能力**：在长程 agentic 基准测试中达到前沿水平，在编码和协作任务上表现出色。

[← 返回主页](../README.md#reasoningllm)

