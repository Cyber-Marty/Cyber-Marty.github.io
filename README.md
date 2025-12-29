# **📈 AI Scaling Laws Interactive Report (AI 扩展定律互动报告)**

一个探索人工智能“物理学”的互动式单页应用（SPA）。从 Kaplan 定律到 Chinchilla 修正，再到最新的推理时间扩展（Inference-Time Scaling）。

## **📖 项目简介**

这个项目旨在将复杂的 AI 扩展定律（Scaling Laws）论文转化为直观、可交互的网页体验。它不仅仅是一份静态报告，更是一个允许用户调整参数、模拟计算预算并观察模型性能变化的互动沙盒。

**核心目标：** 将枯燥的数学公式和论文结论可视化，帮助研究人员、开发者和 AI 爱好者理解大模型发展的底层逻辑。

## **✨ 核心功能**

应用分为四个主要部分，涵盖了 AI 扩展定律的三个时代：

### **1\. 💾 基础时代 (Kaplan Era, 2020\)**

* **交互式幂律曲线**：展示测试损失（Test Loss）与计算量（Compute）之间的对数线性关系。  
* **模拟器**：拖动滑块模拟从 GPT-2 到 GPT-4 规模的算力变化。

### **2\. ⚖️ 计算最优时代 (Chinchilla Era, 2022\)**

* **Chinchilla 计算器**：基于 DeepMind 的 Hoffmann 等人的研究，通过输入总算力（FLOPs），自动计算模型参数量与训练数据量的**最优配比**。  
* **模型散点图**：直观对比 GPT-3（训练不足）与 Llama 3 / Chinchilla（计算最优）在参数/数据平面的位置差异。

### **3\. 🧠 推理时代 (Inference Era, 2024+)**

* **System 1 vs System 2 模拟**：演示 OpenAI o1 等模型引入的“测试时计算（Test-Time Compute）”概念。  
* **思维滑块**：用户可以调整“思考时间”，观察其对数学基准测试准确率的非线性提升。

### **4\. 🚧 挑战与瓶颈**

* **数据墙可视化**：直观展示高质量人类文本数据的枯竭进度。  
* **能源方程**：解析训练与推理成本的经济学模型。

## **🛠️ 技术栈**

本项目坚持**极简主义**和**零依赖**原则，无需复杂的构建工具即可运行：

* **核心结构**：HTML5 (Single File Component)  
* **样式框架**：Tailwind CSS (CDN 加载，响应式设计)  
* **数据可视化**：Chart.js \+ Chart.js Annotation Plugin  
* **逻辑处理**：原生 Vanilla JavaScript (ES6+)

## **🚀 快速开始**

### **在线预览**

*https://cyber-marty.github.io/*

### **本地运行**

由于本项目是单文件 HTML，无需安装 Node.js 或运行 npm install。

如果您想快速体验，可以直接复制 index.html 的源码保存到本地并双击打开。

## **📚 参考引文**

本项目的数据模型和可视化基于以下开创性论文：

1. **Kaplan et al. (2020)**: *Scaling Laws for Neural Language Models* (OpenAI)  
2. **Hoffmann et al. (2022)**: *Training Compute-Optimal Large Language Models* (DeepMind, "Chinchilla")  
3. **OpenAI o1 System Card (2024)**: regarding Inference-Time Scaling and Chain of Thought.

## **📄 许可证**

本项目采用 [MIT License](https://www.google.com/search?q=LICENSE) 开源。欢迎用于教育、演讲或个人学习。

* Circle-Cheng for learn | 2025*
