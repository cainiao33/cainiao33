# Cainiao · CV · Robotics · LLM Post-Training

> 计算机视觉 · 机器人 · 大模型后训练 — 竞赛级方案 · 代码级复盘 · 开源。

🎯 **currently**: edge deployment of detection / fusion models（检测 / 融合算法的边缘部署）

## 📌 Featured

| Competition | Approach | Result |
|------|--------|------|
| [Qwen-Cup-Multimodal-RL](https://github.com/cainiao33/Qwen-Cup-Multimodal-RL) | Two-stage post-training of Qwen3.5-0.8B (multimodal): teacher-distillation SFT from Qwen3.6-27B (113K distillate → 24K curated) + small-dose GRPO RL (+2.0 over the SFT baseline); verbatim reward–eval alignment, statistical submission budgeting | Preliminary **20/337** → Finals **9/20 · Defense 3rd**, Qwen Cup Multimodal Reasoning (Alibaba Qwen) · **¥20,000 prize** |
| [AIC-4D-Radar-Detection](https://github.com/cainiao33/AIC-4D-Radar-Detection) | 3D detection from 4D mmWave radar point clouds (radar-only): SFA3D network kept as-is, original 8D→4D SNR mapping + cross-class NMS · 110 FPS · INT8 12.3 MB | **National 2nd Prize**, AIC 2025 Global Campus AI Algorithm Elite Competition · 75 mAP@0.5 |
| [Scientific-Image-Forgery-Detection](https://github.com/cainiao33/Recod.AI-LUC-Scientific-Image-Forgery-Detection-Silver-Medal-Solution) | Copy-move forgery segmentation in scientific images: frozen DINOv2 + lightweight CNN decoder, conservative dual gating against false positives, honest retrospective incl. gold-solution paradigm analysis | 🥈 **Kaggle Silver Medal** (1,564 teams, top 5%) |
| [Go2_RL](https://github.com/cainiao33/Go2_RL) | Unitree Go2 quadruped RL: autonomous navigation + locomotion (PPO + reward engineering aligned with the scoring formula + curriculum learning) | Regional **Second Prize** · National Finals **Third Prize** (2026 Tencent AI Arena Global Open) |

Every competition gets a code-level retrospective, open sourced — the methodology is worth as much as the result.

## Other Experience

Outstanding undergraduate thesis award for an agent project.

## Contact

📧 [webcainiao@gmail.com](mailto:webcainiao@gmail.com) · [Kaggle @web3cainiao](https://www.kaggle.com/web3cainiao)

<details>
<summary>中文</summary>

计算机视觉 · 机器人 · 大模型后训练。每场竞赛都做代码级复盘并开源——复盘方法论和名次一样值钱。

- **千问杯多模态推理** — [Qwen-Cup-Multimodal-RL](https://github.com/cainiao33/Qwen-Cup-Multimodal-RL)：Qwen3.5-0.8B 两阶段后训练——教师蒸馏 SFT（Qwen3.6-27B 教师，113K 蒸馏 → 24K 精选）+ GRPO 小剂量强化（同口径较 SFT 基线 **+2.0**；奖励-评测口径逐字对齐、提交额度统计化决策）。初赛 **20/337** 晋级 · 决赛 **9/20** · 线上答辩**第 3** · **2 万元奖金**（阿里巴巴千问杯）。
- **4D 毫米波雷达 3D 检测** — [AIC-4D-Radar-Detection](https://github.com/cainiao33/AIC-4D-Radar-Detection)：基于 SFA3D（网络沿用原版），原创 8D→4D SNR 映射 + 跨类别 NMS，110 FPS，INT8 量化后 12.3 MB。AIC 2025 全球校园算法精英大赛**全国二等奖** · 75 mAP@0.5。
- **Kaggle 银牌** — [科学图像伪造检测](https://github.com/cainiao33/Recod.AI-LUC-Scientific-Image-Forgery-Detection-Silver-Medal-Solution)（1,564 队，前 5%）：冻结 DINOv2 + 轻量 CNN 解码器做 copy-move 伪造分割，保守双门控压误检，附诚实复盘（做对/做错 + 金牌方案范式分析）。
- **四足机器人强化学习** — [Go2_RL](https://github.com/cainiao33/Go2_RL)：Unitree Go2 自主导航 + 运动控制（PPO + 奖励工程深度对齐评分公式 + 课程学习）。腾讯开悟全球公开赛**区域二等奖** · **全国三等奖**。

currently：检测 / 融合算法的边缘部署。

其他：智能体课题获优秀学士毕业论文。

📧 webcainiao@gmail.com

</details>
