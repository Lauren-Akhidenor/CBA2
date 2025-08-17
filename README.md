# 🌱 Cost-Benefit Analysis of Amaranth and Corchorus Farming

## 📑 Table of Contents
1. [Project Overview](#-project-overview)
2. [Cost Projections](#-cost-projections)
   - [Project 1: Organic Farming](#project-1-organic-farming)
   - [Project 2: Integrated Farming](#project-2-integrated-farming)
3. [Benefit Projections](#-benefit-projections)
   - [Project 1: Organic Farming](#project-1-organic-farming-1)
   - [Project 2: Integrated Farming](#project-2-integrated-farming-1)
4. [Metrics & Findings](#-metrics--findings)
5. [Farming Process Images](#-farming-process-images)
6. [Formulas Used](#-formulas-used)
7. [Insights](#-insights)
8. [How to Run](#-how-to-run)
9. [Contributing](#-contributing)

---

## 📘 Project Overview
This project analyzes the economic viability of **Amaranth** and **Corchorus** farming under two approaches:

- **Project 1:** Strictly organic farming using manure.  
- **Project 2:** Integrated farming using fertilizer, pesticide, and manure.  

Amaranth and Corchorus are highly nutritious leafy vegetables commonly cultivated in Nigeria. The project compares costs, revenues, and profitability metrics using **Excel-based Cost-Benefit Analysis (CBA)**.

---

## 📊 Cost Projections

### Project 1: Organic Farming (Manure Only)

| Item                   | Quantity | Unit Cost (₦) | Total Cost (₦) | Notes                     |
|------------------------|----------|---------------|----------------|---------------------------|
| Land                   | 1        | 5,000         | 5,000          | Rent                      |
| Manure                 | 5        | 5,000         | 25,000         | Organic manure            |
| Labor                  | 5        | 2,000         | 10,000         | 1 person/bed 3× week      |
| Seeds – Amaranth       | 1        | 700           | 700            | 1 tin                     |
| Seeds – Corchorus      | 1        | 500           | 500            | 1 tin                     |
| Off-season Cost        | 1        | 500           | 500            | Adjustment                |
| **Total Cost**         | —        | —             | **41,700**     |                           |

### Project 2: Integrated Farming (Fertilizer + Pesticide + Manure)

| Item                   | Quantity | Unit Cost (₦) | Total Cost (₦) | Notes                     |
|------------------------|----------|---------------|----------------|---------------------------|
| Land                   | 1        | 5,000         | 5,000          | Rent                      |
| Fertilizer (NPK)       | 5        | 1,200         | 6,000          | 5kg each                  |
| Pesticide (Cypermetrine)| 1       | 3,750         | 3,750          | 120ml                     |
| Manure                 | 5        | 5,000         | 25,000         | Organic manure            |
| Labor                  | 5        | 2,000         | 10,000         | 1 person/bed 3× week      |
| Seeds – Amaranth       | 1        | 700           | 700            | 1 tin                     |
| Seeds – Corchorus      | 1        | 500           | 500            | 1 tin                     |
| Off-season Cost        | 1        | 500           | 500            | Adjustment                |
| **Total Cost**         | —        | —             | **51,450**     |                           |

---

## 📈 Benefit Projections

### Project 1: Organic Farming

| Crop         | Qty (kg) | Price/kg (₦) | Revenue (₦) |
|--------------|----------|---------------|-------------|
| Amaranth     | 150      | 200           | 30,000      |
| Corchorus    | 100      | 200           | 20,000      |
| **Total Revenue** | —    | —             | **50,000**  |

**Net Benefit** = 50,000 − 41,700 = **₦8,300**

---

### Project 2: Integrated Farming

| Crop         | Qty (kg) | Price/kg (₦) | Revenue (₦) |
|--------------|----------|---------------|-------------|
| Amaranth     | 120      | 200           | 24,000      |
| Corchorus    | 90       | 200           | 18,000      |
| **Total Revenue** | —    | —             | **42,000**  |

**Net Benefit** = 42,000 − 51,450 = **−₦9,450**

---

## 📊 Metrics & Findings

| Metric       | Project 1 (Organic) | Project 2 (Integrated) |
|-------------|-------------------|------------------------|
| Total Cost  | 41,700            | 51,450                 |
| Total Revenue | 50,000          | 42,000                 |
| Net Benefit | 8,300             | −9,450                 |
| ROI (%)     | 19.90             | −18.37                 |
| BCR         | 1.20              | 0.82                   |
| NPV (₦)     | 3,754.55          | −13,268.18             |
| IRR (%)     | 20                | −18                     |

---

## 🖼️ Farming Process Images

<details>
<summary>Click to expand images</summary>
<img src="IMG_5142.jpg" width="600">
<img src="IMG_5152.jpg" width="600">
</details>

---

## 🧮 Formulas Used
- **Net Present Value (NPV)**  
NPV = ∑ (Net Cash Flow_t / (1 + r)^t) - Initial Investment

*Where `r` is the discount rate (Excel formula: =NPV(rate, value1, [value2], …) - initial investment)*

- **Internal Rate of Return (IRR)**  


IRR = Discount rate where NPV = 0

*Excel formula: =IRR(values, [guess])*  

- **Return on Investment (ROI)**  


ROI (%) = (Net Benefit / Total Cost) * 100


- **Benefit-Cost Ratio (BCR)**  


BCR = Total Revenue / Total Cost


---


---

## 🔍 Insights
- Organic farming (Project 1) is **more profitable** than integrated farming in this scenario.  
- Strictly organic methods generate higher yield in this trial, reducing input costs while maintaining revenue.  
- Integrated farming (Project 2) incurs **higher costs** from fertilizers and pesticides, resulting in a negative net benefit.  
- Metrics such as **ROI, NPV, and IRR** clearly show Project 1 as economically viable.

---

## 🚀 How to Run
1. Clone the repository:
```bash
git clone https://github.com/Lauren-Akhidenor/CBA2.git


