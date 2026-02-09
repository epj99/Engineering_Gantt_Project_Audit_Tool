# Engineering_Gantt_Project_Audit_Tool
Automated Engineering Gannt Project Schedule Audit Tool with Graph Theory logic.

# 🏗️ Automated Engineering Schedule Audit Tool
**Bridging 11 Years of Engineering Expertise with Python Data Science**

## 📌 Project Overview
In industrial construction and food processing line installations, schedule delays are often rooted in **latent logic failures** that are invisible in traditional Gantt charts. This tool automates the "Health Check" of project schedules, identifying financial and logical risks before they manifest on-site.

## 🛠️ Key Audit Features
* **Recursive Dependency Detection:** Leverages **Graph Theory** (`networkx`) to identify circular logic loops that break Critical Path Method (CPM) calculations.
* **Site Access Violation Engine:** Cross-references technical tasks against physical site constraints (e.g., concrete curing windows) to prevent standby labor charges.
* **Granularity Audit:** Flags "Black Hole" tasks with durations exceeding 30 days that lack sufficient detail for Earned Value Management (EVM).
* **Complex Logic Parsing:** Utilizes **Regular Expressions (Regex)** to deconstruct industrial-standard predecessor strings (e.g., `120FS+7`).

## 📊 Data Visualization
The tool generates an **Interactive Risk Dashboard** using `Plotly`. This allows stakeholders to:
* Visualize the "No-Go" curing windows.
* Identify "Critical" tasks with logic or site conflicts in red.
* Hover over task bars to see technical metadata (Predecessors, Duration, IDs).



## 💻 Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NetworkX, Plotly, Re (Regex)
* **Platform:** Google Colab / Jupyter

## 📈 Business Impact
By identifying a site-access conflict during the concrete curing phase, this audit tool provides recommendations that can prevent an estimated **€15,000+** in subcontractor standby fees.

---
**How to use:**
1. Upload your `.xlsx` Gantt export.
2. Run the `run_full_audit(df_clean)` function.
3. Review the terminal output and the Interactive Dashboard.
