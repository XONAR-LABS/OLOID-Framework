<!-- README.zh-CN.md -->

[English](./README.md) | [中文](./README.zh-CN.md)

# OLOID Framework

## 关于 OLOID
OLOID Framework 是一套面向汽车设计生成的开源 LoRA 框架。

基于 Flux.1 dev 训练，适合 Agent 检索和调用，旨在将设计抽卡中繁杂的调参过程交给 Agent 完成，释放设计师的时间。  
同时也支持设计师手动组合使用。



## 框架结构
当前版本共包含 49 个 LoRA，按四个维度组织，可根据不同设计目标进行组合调用：  
如：PRD（定体量） + CRT（加造型语言） + INS（扩展创意可能性） + VIS（控制输出观感）

| 维度 | 代码 | 作用 |
| -- | --- | ----------------- |
| 量产体量 | PRD | 更接近量产车的体量、比例和结构基础 |
| 创意造型 | CRT | 推进造型语言和设计变化       |
| 灵感启发 | INS | 引入跨领域设计语言和额外刺激    |
| 视觉表现 | VIS | 控制图像表现方式、材质感和整体观感 |

完整结构总览如下：  
![Structure](./assets/Structure_CN.webp)  
*图：按 PRD / CRT / INS / VIS 与 EXT / INT / PART 组织的完整结构。*



## 索引
每个 LoRA 的触发词、参考 Prompt 和推荐权重请查看索引：

- [GitHub](./INDEX.zh-CN.md)
- [飞书文档](https://ucnd3tftqho9.feishu.cn/wiki/UUe5wZy9CiaQspkNEErcuzMqnie)



## 下载
全部 LoRA 文件已上传至 Hugging Face：

- [Hugging Face](https://huggingface.co/XonarLabs/OLOID_Framework)



## 项目状态
OLOID 在 Flux.1 上的阶段性验证已完成。我们已经开始探索下一代模型训练以及更完整的 Agent 化流程，后续将不再继续更新这一代模型。  
欢迎试用和反馈。

如有兴趣讨论面向真实汽车设计流程的 AI 生成系统，欢迎联系 OkeyDesign：hello@okeydesign.com  
如有兴趣进一步交流定制训练、Agent 等技术相关内容，欢迎联系 XonarLabs：info@xonarlabs.com



## 许可证
本模型基于 FLUX.1 dev 构建。  
使用时需遵循其基础模型的许可协议限制。



## Credits
OkeyDesign & XonarLabs
