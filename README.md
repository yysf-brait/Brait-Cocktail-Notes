# Brait’s Cocktail Notes 🍸

## 项目简介

**Brait’s Cocktail Notes** 是一个非商业化的个人鸡尾酒笔记项目，旨在记录家庭调酒的经验与配方。  
本项目强调 **安全性、精准性、性价比与可复现性**，而非追求商业环境中的调制效率或美学效果。

### 项目目标

- **家庭调酒**：配方适用于家庭制作，尽量避免依赖昂贵或复杂的专业设备。
- **可复现性**：确保每次调制的结果一致，降低不确定性。  
- **安全性**：关注食材搭配的安全性，并提供已知的过敏风险预警。  
- **开放交流**：虽然本仓库以个人笔记为主，但欢迎大家提出建议或通过 PR 贡献新配方。

---

## 免责声明与警告 ⚠️

### 使用或改编本仓库配方的任何人，须明确以下信息

- 本项目的配方属于 **开放式化学实验方案**，其最终效果可能受原料、设备、环境等多种因素影响。
- 配方**仅供参考**，实际效果可能因原料、设备、环境或者其他未知因素的不同而有所差异。
- 本项目的配方**不保证符合您所在地的《食品安全生产法》**，请自行查阅相关法规并严格遵守。  
- **尚未对所有原料的致敏性/毒性组合进行全面验证**，使用者需自行评估潜在健康风险。  
- **部分配方可能涉及专业设备操作**（如酒精燃烧、萃取、高压容器等），操作前请确保具备必要的安全知识。  
- **强烈不建议向未成年人提供酒精饮品**，尤其在法律明确禁止的情况下。

### 使用本仓库中任意配方，即表示您已确认并接受以下条款

- 遵守当地**酒类法规**。  
- **完整阅读**并理解配方中的最新过敏原列表（如有），并知晓该列表**可能存在疏漏**。  
- 确保所有原料**合法且已进行个人过敏测试**。  
- 掌握必要的化学、食品安全或专业设备操作技能（如适用）。  
- **自行承担**执行配方的所有风险和后果。

---

## 配方卡片体系

本仓库中的鸡尾酒配方均以 **配方卡片** 形式存档，遵循以下原则：

- **Markdown 语法**  
  所有配方均采用 `.md` 文件格式，便于阅读、编辑和版本管理。

- **编程语言符号体系**  
  利用 `<<`（倒入）、`.`（对象方法）等符号，使配方描述更为简洁明确。

- **高度量化**  
  以标准单位精确描述原料、步骤、用量等参数，确保配方具有极高的可复现性。

- **简洁与精准**  
  去除冗余信息，确保每一步骤表达清晰，避免模棱两可。

- **详细特征参数**  
  提供感官体验、适宜人群、最佳饮用时限等详细信息，让用户对预期效果有直观认识。

---

## 配方卡片结构

每张配方卡片通常包含以下模块：

1. **基础参数**  
    （如酒精度、总量、最佳饮用时限等）
2. **感官体验**  
    （包括视觉、嗅觉、质地、味觉、酒精感等）
3. **风味简述**  
    （对整体风味及特色的简要描述）
4. **材料表**  
    （定量描述所有原料及其过敏风险）
5. **道具清单**  
    （必备的设备和器具）
6. **操作步骤**  
    （采用符号体系记录的标准化制备流程）

---

## 编程语言符号体系

为提升配方卡片的可读性和逻辑性，本仓库采用了一套基于编程语言的符号体系。以下是各符号的具体含义：

| 符号 | 含义 | 示例 | 解释 |
| :-: | :-: | :-: | :- |
| `*` | **数量乘法** | `24 * 小型冰块` | 表示加入 **24** 颗小型冰块 |
| `#` | **补充** | `#缓慢` | 提示该步骤需**缓慢进行** |
| `<<` | **倒入** | `柯林杯 << 摇酒壶`<br>`柯林杯 << 苏打水` | 将摇酒壶中的内容或苏打水**倒入**柯林杯 |
| `<<`（多个） | **经介质倒入** | `柯林杯 << 滤网 << 柠檬汁` | 柠檬汁**经过**滤网后**倒入**柯林杯 |
| `.` | **对象方法** | `柯林杯.插入吸管` | **对**“柯林杯”**执行**“插入吸管”的操作 |
| `()` | **方法参数** | `摇酒壶.摇匀(波士顿摇, 中等力度, 持续10s)` | **对**“摇酒壶”**执行**“摇匀”操作，**参数**：摇法=波士顿摇，力度=中等，时间=10s |
| `[? ]` | **可选部分** | `[? 柯林杯.插入吸管]` | **该步骤可省略**，不影响配方核心流程 |

---

## 如何贡献

虽然本项目以个人笔记为主，但欢迎大家提出改进建议或贡献新配方。您可以通过以下方式参与：

- **Issue**  
  如果发现配方错误、步骤不合理或有其他疑问，请提交 Issue 进行讨论。

- **Pull Request**  
  若您希望贡献新的配方或对现有配方进行优化，请 fork 本仓库后提交 PR。
