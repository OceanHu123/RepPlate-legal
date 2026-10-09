# RepPlate Privacy Policy · 食练记隐私政策

[English](#english) · [中文](#中文)

---

## English

**Effective date: 2026-10-09**  
**Developer: Oakley (RepPlate / 食练记)**

This policy explains how RepPlate ("the app") handles your information.

### 1. Data that stays on your device

The following is stored locally on your iPhone (SwiftData) and is **never uploaded to a server run by the developer** (there is no developer backend):

- Recipes, shopping lists, meal calorie and macro logs
- Water logs
- Workout plans, sets, weights, training logs, body measurements and weight
- Your profile (sex, height, goals) and app settings
- The "today" snapshot shown in widgets (shared locally through an App Group)

### 2. Data that leaves your device only when you use a feature

| Feature | Sent to | What is sent |
| --- | --- | --- |
| Photo or text calorie estimates, recipe extraction from videos, AI workout or body recaps, AI training plans | [DeepSeek](https://www.deepseek.com/) API | The text, meal photo (JPEG), workout summary or body measurements needed for that analysis |
| Packaged-food nutrition search | [Open Food Facts](https://world.openfoodfacts.org/) | Your search keywords |
| Workout duration and calories | Apple HealthKit (on device) | Only the workout data you authorize is read, for that day's training recap. Raw HealthKit data is not sent to DeepSeek; if you request an AI recap, the summary may include duration and calorie numbers |
| Pro subscription | Apple App Store / StoreKit | Apple processes payments and receipts; the developer never sees your card details |

**International transfer.** DeepSeek is operated by a company based in the People's Republic of China, and content you submit for AI analysis is processed on its servers. Only use AI features if you are comfortable with this, and do not include unnecessary personal or identifying information in photos or prompts.

We **do not track you for advertising**, do not use the advertising identifier (ATT), and do not build cross-app ad profiles.

### 3. Why we use it

Only to provide the app's features: logging food, estimating calories, managing training, optional AI analysis, and checking your subscription status. AI requests are made only when you start them; sending that content is the basis on which we process it.

### 4. Third parties

- **DeepSeek** handles the content of your AI requests under its own privacy policy and terms.
- **Open Food Facts** is a public food database queried with your search keywords.
- **Apple** — HealthKit, notifications, StoreKit and (if enabled) iCloud sync follow Apple's system privacy controls.

The developer does not store copies of your AI requests or results on any server.

### 5. Storage and security

- Data is stored on your device. You can **export a backup** in Settings; backup files contain personal data, so keep them safe.
- If iCloud / CloudKit sync is enabled, data may sync to your Apple Account's private iCloud database. It still never passes through a developer server.

### 6. Your choices and rights

- You can deny photo, camera, Health and notification permissions; the related features stop working and everything else still works.
- In Settings you can read this policy, export a backup, or **erase all app data on this device**. Your subscription stays with your Apple Account and can be restored later.
- Deleting the app removes its local data. Data already synced to iCloud is managed in your Apple Account.
- Because your logs are not held by the developer, you can access, export, correct or delete them yourself at any time in the app. For questions about data sent to DeepSeek, contact DeepSeek or us using the details below.

### 7. Children

The app is not directed to children under 13 and does not knowingly collect their personal information.

### 8. Changes

When this policy changes, the effective date above is updated. Significant changes will be highlighted in the app or in release notes where possible.

### 9. Contact

Email: **3038816821@qq.com**  
Or open a [GitHub issue](https://github.com/OceanHu123/RepPlate-legal/issues).

---

## 中文

# 食练记（RepPlate）隐私政策

**生效日期：2026-08-31**  
**开发者：Oakley（RepPlate / 食练记）**

本政策说明「食练记」如何处理你的信息。使用本 App 即表示你已阅读并理解本政策。

## 1. 我们收集什么

### 主要保存在本机的数据

以下内容默认写在你的 iPhone 本地（SwiftData），**不会上传到开发者自建服务器**（当前也没有自建后端）：

- 食谱、购物清单、餐食热量与宏量营养素记录
- 喝水记录
- 训练计划、组数重量、训练日志、身体围度与体重等
- 个人资料（性别、身高、目标等）与 App 设置
- 小组件用到的「今日概览」快照（App Group 本机共享）

### 仅在你主动使用功能时，才会离开本机的数据

| 场景 | 发往何处 | 内容 |
| --- | --- | --- |
| 拍照/文字估热量、食谱 AI 提取、训练/身体 AI 复盘、AI 训练计划 | [DeepSeek](https://www.deepseek.com/) API | 你提交的文字、餐食图片（JPEG）、训练摘要或身体围度等分析所需内容 |
| 包装食品营养查询 | [Open Food Facts](https://world.openfoodfacts.org/) | 搜索关键词 |
| 读取训练时长/消耗 | Apple HealthKit（本机） | 仅读取你授权的「体能训练」相关数据，用于当日训练复盘；**不会**把 HealthKit 原始数据发给 DeepSeek，除非你使用「AI 复盘」且摘要里包含时长/消耗数字 |
| 会员订阅 | Apple App Store / StoreKit | 由 Apple 处理支付与收据；我们不接触银行卡号 |

我们**不做广告追踪**，不使用 ATT 广告标识符，不把数据用于跨 App 广告画像。

## 2. 用途

仅用于提供 App 功能：记饮食、估热量、管理训练、可选 AI 分析，以及会员权益校验。

## 3. 第三方

- **DeepSeek**：按对方隐私政策与服务条款处理你发起请求时提交的内容。请勿在提示词或图片中包含不必需的敏感身份信息。
- **Open Food Facts**：公开食品数据库查询。
- **Apple**：HealthKit、通知、StoreKit、（开通后）iCloud 同步遵循 Apple 的系统隐私机制。

## 4. 存储与安全

- 默认本机存储；你可在设置中**导出备份**（备份文件含个人数据，请自行妥善保管）。
- 开通 iCloud / CloudKit 后，数据可能同步到你的 Apple ID iCloud 私有数据库，仍不经过开发者服务器。
- API 密钥仅用于调用 AI 服务，打包进 App 的密钥属于开发者配置；请勿把个人密钥提交到公开仓库。

## 5. 你的选择

- 可拒绝相册、相机、健康、通知等系统权限；拒绝后对应功能不可用，其余功能仍可使用。
- 可在设置中查看本政策、导出备份，或**清除本机全部 App 数据**（订阅状态由 Apple 账户保留，重新登录后仍可恢复会员资格）。
- 可随时在系统设置中删除 App；删除后本机数据一并清除（iCloud 中已同步的数据需在 Apple 账户侧另行管理）。

## 6. 儿童

本 App 不面向 13 岁以下儿童，不故意收集儿童个人信息。

## 7. 变更

政策更新时会修订本页「生效日期」。重大变更会尽量在 App 内或发布说明中提示。

## 8. 联系

隐私相关问题请通过邮件联系：  
**3038816821@qq.com**

或在本仓库提交 [GitHub Issues](https://github.com/OceanHu123/RepPlate-legal/issues)。

---

App Store Connect 隐私问卷可参考本页第 1 节；正式上架链接（推荐 raw，审核 bot 友好）：  
https://raw.githubusercontent.com/OceanHu123/RepPlate-legal/main/privacy-policy.md
