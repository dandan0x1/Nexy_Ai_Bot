# Nexy_Ai 项目介绍
### 项目介绍
nexyai.io 是一个结合 DeFi 和 AI 的项目（即 DeFAI，Decentralized Finance + Artificial Intelligence），部署在 Solana 区块链上。它的核心目标是通过去中心化金融与人工智能技术相结合，为用户提供创新的金融服务。用户可以通过完成平台上的任务获取 Nexy 积分（Nexy Points），这些积分未来可以兑换为项目的原生代币 $NEXYAI。项目旨在通过积分机制激励用户参与，同时利用 Solana 区块链的高性能和低成本特性，提供快速、低费用的交易体验。

### 融资情况
未查到

### 空投说明
积分兑换代币的比例和具体时间表尚未明确，但空投已被项目方确认。

### 注册地址

https://point.nexyai.io/?ref=WVVVL

# Nexy Ai Bot 1.0 食用说明
### token抓取
``token.txt``
![image](https://github.com/user-attachments/assets/492f553f-3be0-48f7-9b06-5923e200da21)

### 项目id更新教程
这个非必要修改
``task_ids.json``
```json
{
  # 一次性任务
  "OneTimeTasks": [
    "e9583d56-a176-4bf3-93e1-eae0e1e878f4",
    .........
    "42cfcd7a-31f1-4aa1-8c5b-938d43359698"
  ],
# 每天任务
  "DailyTasks": [
    "60aad274-e2b5-441e-bab3-d55dbea49706"
  ],
# 推荐积分领取任务
  "DailyCheckTasks": [
    "46f96482-359c-4eb2-b906-7eac3d4e509e",
    .........
    "883a646d-65e7-4b60-8dd3-f26bbf8df44d"
  ]
}
```
怎么更新了呢？

打开chrome开发者->找到你要抓取的区域(1)点击检查->元素(2)下面就有任务id(3)
![image](https://github.com/user-attachments/assets/faaa7587-1f3f-4398-9889-2191db5d23fc)
