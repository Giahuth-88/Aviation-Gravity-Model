# ✈️ Avianca Gravity Modeling Project

**Capstone Project | 2023**  
*Data-driven Route Optimization for Avianca Airlines using Gravity Model & OLS Regression*  
（基于引力模型与OLS回归的Avianca航空航线优化项目）

---

## 🌍 Overview | 项目概览
This project applies a **Gravity Model** and **Ordinary Least Squares (OLS) Regression** to predict passenger demand and revenue for potential Avianca routes.  
Our goal was to identify **profitable new flight routes** based on economic, geographic, and competitive variables.

本项目运用 **引力模型（Gravity Model）** 与 **OLS回归分析**，预测Avianca航空潜在航线的乘客需求与收入表现，  
旨在通过数据驱动方法寻找 **最具盈利潜力的新航线组合**。

---

## 🧩 Key Objectives | 核心目标
- Predict new routes and estimate passenger & revenue performance  
- Build and compare Geo-economic and Service-level regression models  
- Introduce a **Weighted Scoring Model** for final route prioritization  
- Deliver **Top 10 Recommended New Routes** for Avianca’s post-COVID recovery strategy  

主要目标：
- 预测潜在航线并估计乘客与收益表现  
- 构建并比较地缘经济与服务层面的回归模型  
- 提出加权评分模型（Weighted Scoring Model）用于路线筛选  
- 产出 **后疫情时代Avianca最具潜力的10条新航线**

---

## 🧠 Methods & Features | 方法与特征工程
| Category | Techniques |
|-----------|-------------|
| **Modeling** | OLS Regression, Log-transformation, Feature Engineering |
| **Variables** | GDP, Population, Distance, Domestic/Intercontinental, Competitors |
| **Feature Engineering** | Dummy Variables, Flight Length Categories |
| **Validation Metrics** | R², MAPE |
| **Tools** | Python, Pandas, NumPy, Matplotlib, Excel |

主要技术：
- **模型构建**：OLS回归、对数变换、特征工程  
- **核心变量**：人均GDP、人口、航距、竞争者数量、洲际航线哑变量  
- **特征工程**：航线长度分组、竞争程度量化  
- **评估指标**：R²（越高越好）、MAPE（越低越好）  
- **主要工具**：Python、Pandas、NumPy、Matplotlib、Excel  

---

## 📊 Results | 结果与结论
- Final **Geo-economic Model (Rev_PAX target)** achieved **R² = 0.87**, **MAPE = 3.35**
- Identified and validated **Top 10 new routes**, including:
  - Bogotá – Las Vegas ✅ *(validated by Avianca sponsor and planned for 2024 launch)*  
  - Bogotá – Paris  
  - Medellín – Berlin  
  - Cali – Paris  
  - Bogotá – Tokyo  
- Developed a **Weighted Scoring Model** combining quantitative performance and strategic feasibility
- **Sponsor Feedback:** “The Bogotá–Las Vegas prediction was completely accurate, and the route will be executed in 2024.”

最终结果：
- 最优Geo-economic模型（以Rev_PAX为目标）达到 **R² = 0.87, MAPE = 3.35**
- 确定并验证了 **Top 10 条潜在航线**，其中包括：
  - **波哥大 – 拉斯维加斯 ✅（被Avianca官方认可，并将在2024年正式启航）**
  - 波哥大 – 巴黎  
  - 麦德林 – 柏林  
  - 卡利 – 巴黎  
  - 波哥大 – 东京  
- 构建了融合经济表现与战略可行性的 **加权评分模型**
- **导师反馈：** “波哥大–拉斯维加斯航线的预测完全正确，且该航线已被采纳，将于2024年执行。”
