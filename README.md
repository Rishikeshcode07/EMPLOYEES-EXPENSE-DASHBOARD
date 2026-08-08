# Corporate Employees Expense & Budget Analytics

### Project Link: https://drive.google.com/file/d/1WK8zeHtrISgrTDFCQIrS50izLKYF9b3b/view?usp=sharing

## Situation (The Problem)

Managing corporate expenses is often a massive logistical headache for HR and Finance departments. Companies process hundreds or thousands of reimbursement claims every month—ranging from client dinners and flights to software subscriptions and office supplies. 

Historically, the management team was relying on disjointed spreadsheets and manual receipt tracking. This created massive data blind spots. HR and Finance managers could not quickly answer essential budget questions:
1. What is the exact total amount of money being claimed across the company?
2. What categories of expenses (Travel, Meals, Equipment) are draining the most cash?
3. Are specific departments (like Operations, Marketing, or C-Level) exceeding their allocated budgets?
4. Who are the top individual spenders within the organization?
5. Are there any unusual spikes in spending during specific fiscal quarters?

Without a centralized system, the company risked budget overruns, delayed reimbursements, and an inability to identify wasteful corporate spending.

## Task (The Goal)

My objective was to eliminate the spreadsheet chaos and engineer a unified, interactive data model for corporate spending using Power BI.

The goal was to build a comprehensive analytics dashboard where HR and Finance leadership could instantly track the flow of outgoing cash. By processing raw expense claims into clear financial metrics, the team needed a tool to enforce corporate spending policies, ensure budget compliance, and optimize resource allocation across all departments.

## Action (How I Processed the Data)

To transform raw reimbursement data into a strategic financial tool, I broke the project down into a rigorous data modeling workflow:

* **Step 1: Data Normalization:** I extracted the raw expense reports spanning multiple fiscal years. I cleaned up inconsistent data entries, standardized the expense categories (e.g., grouping various tech costs into "Internet" or "Mobile"), handled missing approval dates, and ensured all metrics were structured for accurate aggregation.
* **Step 2: Core Financial Engineering:** I programmed custom DAX calculations to establish the high-level financial health of the company. I calculated the absolute **Total Expenses Claimed** and aggregated the data to track overall financial outflows dynamically.
* **Step 3: Category Deep-Dives:** I segmented the data by specific expense types, separating massive corporate costs (like Airfare and Hotels) from everyday expenses to understand exactly where corporate funds were being allocated.
![image alt](https://github.com/user-attachments/assets/83b6d8f7-8084-4fbc-93d2-3a58cd3dfba9)

* **Step 4: Departmental & Personnel Mapping:** To track compliance and accountability, I grouped the spending data by specific company departments (such as Operations and Marketing) and linked expenses directly to individual employee profiles (e.g., Carter Petti).
![image alt](https://github.com/user-attachments/assets/19f8038e-a472-4ff6-8c77-98f262ee4a0b)

* **Step 5: Temporal Trend Tracking:** Finally, I mapped the approved expenses across a quarterly and monthly timeline (spanning the 2013-2014 dataset) to identify historical spending spikes, allowing the finance team to forecast future cash flow needs accurately.
![image alt](https://github.com/user-attachments/assets/4b8bf481-da94-4b14-86c5-0c5cb9309174)

## Result (The Business Impact)

By organizing the expense data into this interactive Power BI model, we unlocked critical financial visibility for the leadership team. The data revealed several powerful operational insights:

### 1. The Big Picture
The dashboard successfully processed and modeled a massive **$3.47 Million** in total corporate expenses. Management now has an instantaneous, bird's-eye view of every dollar leaving the company through employee reimbursements.
![image lat](https://github.com/user-attachments/assets/68ba005a-2ade-4bef-8a65-7bd4b7e97376)

### 2. Identifying Cash Drains (The Cost of Travel)
Categorizing the expenses revealed exactly how capital is moving. The data showed that travel is the ultimate cash drain for the organization. **Airfare ($787K)** and **Hotels ($321K)** combined to cost the company over **$1.1 Million**. Armed with this insight, management can negotiate better corporate discount rates with specific airline or hotel chains to save thousands of dollars annually. Additionally, **Internal Cross Charges** accounted for another massive **$811K**, while **Marketing** expenses tracked at **$276K**.

### 3. Streamlining HR Operations & Accountability
By providing a clear view of spending mapped directly to individual employees and specific departments (like C-Level executives vs. standard Operations), the HR team can audit expenses much faster. They can quickly identify spending anomalies and ensure all reimbursements fall strictly within corporate policy guidelines.

### 4. Forecasting and Cash Flow
The temporal trend analysis removed the surprise element from corporate spending. Finance teams can now look at the historical timeline (Q1 to Q4) to anticipate when expenses typically spike and ensure there is enough liquid capital available to process those reimbursements on time without disrupting operations.

## Future Enhancements

To make this ecosystem even more powerful in the future, we could introduce:
* **Automated Policy Flagging:** Setting up dynamic alerts in Power BI to automatically flag claims that exceed standard daily allowances (e.g., meal claims over $100).
* **Predictive Budgeting:** Using machine learning to predict next quarter's travel expenses based on historical data and seasonal business cycles.
