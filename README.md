# 🛡️ Insurance Dashboard

This dashboard was built using **Power BI Desktop** to analyze insurance policy and claim data.  
The goal is to provide insight into product performance, policy distribution, number of claims, and financial trends so that companies can make more informed decisions.

---

## 📊 Dashboard Preview

### 🔹 Page 1 – Overview
![Insurance Dashboard Page 1](/page1.png)

**Key Features:**
- Summary of key values: **Premium Amount**, **Coverage Amount**, and **Claim Amount**
- Customer gender distribution (Female vs Male)
- Number of claims based on status (Rejected, Settled, Pending)
- Premium Amount by Policy Type
- Claim Amount by Age Group
- Proportion of Active vs Inactive Policies
- Summary table of claims based on Policy Type & status

---

### 🔹 Page 2 – Policy & Claim Details
![Insurance Dashboard Page 2](/page2.png)

**Key Features:**
- Detailed data for each policy and claim:
  - **PolicyNumber, CustomerID, ClaimNumber**
  - **Age, Gender**
  - **CoverageAmount, PremiumAmount**
  - **Policy Start & End Date**
  - **Policy Type**
  - **Claim Status & Claim Date**
  - **Claim Amount**
  - **Age Group**
  - **Active / Inactive**
- Enables granular analysis for each specific customer or policy
- Supports filter via Drill Through from page 1 (by Policy Type)

---

## 🛠️ Tech Stack

- **Power BI** → for data visualization  
- **Power Query** → for data transformation  
- **DAX** → for aggregate value & ratio calculations  

---

## 💡 Insights from the Dashboard

- Travel Insurance products generated the highest premiums (0.23B).
- The highest claims were submitted by the Adult age group, totaling 0.79B.
- Active policies dominate (58.13%), indicating a fairly good customer retention rate.
- Rejected claims (23.7B) are greater than Settled claims (18.4B), indicating potential for further investigation.
- Policy and claim details can be traced down to the individual customer level.
