
# 📊 Visa-Sponsored Job Opportunities Dashboard

A Power BI dashboard designed to help international students explore and analyze visa-sponsored job opportunities across leading companies in the United States. This tool offers insights into job types, hiring trends, salaries, and company-specific details to make the job search more informed and efficient.

---

## 📜 Project Charter

### 🎯 Project Title:
**Visa-Sponsored Job Opportunities Dashboard**

### 🧭 Problem Statement:
International students face major hurdles in securing employment due to visa restrictions, cultural barriers, and a fragmented job search experience. There is no centralized, data-driven platform that consolidates sponsorship availability, hiring trends, and role-specific information in a clear and accessible format. This leads to wasted time, anxiety, and missed opportunities.

### 👥 Stakeholders:
- **Primary Decision Maker**: International job seekers requiring visa sponsorship.
- **End Users**: Students, recent graduates, and educational institutions supporting career services.

### 🎯 Project Goal:
To create a streamlined, interactive dashboard that simplifies the job search process for visa-sponsored roles. This tool empowers users to identify top employers, in-demand roles, and high-paying sectors—enabling informed, confident, and strategic career decisions.

### 💡 Objectives:
- Centralize visa-sponsored job postings from various data sources.
- Provide real-time insights into job availability, salary, and hiring trends.
- Allow comparison of employers based on reputation, job types, and compensation.
- Enable filtering by role, industry, location, and company rating.

### 🧱 Data Model Summary:
The system is built on three core entities:
- **Company**: Employer metadata including name, rating, description, and review metrics.
- **JobPosting**: Contains role-specific info like title, type, location, and status.
- **JobDetails**: Adds deep-dive elements such as salary, description, and apply links.

These are structured to support one-to-many relationships, enabling comprehensive drill-downs by company or job.

### 🛠️ Tools & Technologies:
- Power BI for visualization and dashboard creation.
- CSV/Excel datasets representing job postings and company data.
- Data transformation in Power Query.
- ER modeling to guide schema and interactivity.

### ✅ Success Criteria:
- The dashboard provides intuitive navigation and filtering.
- Users can compare employers and roles easily.
- Real-time trends are accessible and accurate.
- Students report increased confidence and efficiency in their job search.

---

## 📁 Dashboard Pages

### 1️⃣ Cover Page  
![image](https://github.com/user-attachments/assets/ee17457f-2ff3-44d5-85e9-d822597634b2)

An interactive introduction screen featuring a clean layout and tab-style navigation for seamless movement between dashboard sections.  
It sets the stage for the dashboard experience with clear headings and visual design.  
The open-door visual metaphorically represents career opportunity and exploration.

---

### 2️⃣ Introduction  
![image](https://github.com/user-attachments/assets/0f6807d2-49df-43dc-96c5-2ff14394ce47)

This page provides an overview of the dashboard’s purpose and structure.  
It introduces the key components and highlights how users can interact with the dashboards to access job trends and employer-specific data.

---

### 3️⃣ Visa-Sponsored Job Search Dashboard  
![image](https://github.com/user-attachments/assets/9a12e8d9-247d-4f5e-9453-b540892d1d7b)

This dashboard presents a market-level view of visa-sponsored job data using intuitive visuals and KPIs.

**Visuals Explained:**
- **KPI Cards** show the average salary (115.06K), job posting growth rate (2%), and percentage of jobs with salary info.
- **Job Type Pie Chart** reveals the proportions of Full-time, Internship, Part-time, Contract, and Temporary jobs.
- **U.S. Map** shows job posting concentrations by state.
- **Line Chart** displays monthly job posting trends.
- **Top Companies Bar Chart** ranks employers by number of sponsored job listings.
- **Job Field Pie Chart** displays demand in fields like Network Engineering and Software Development.

This dashboard helps users understand where and what types of jobs are available at a high level.

---

### 4️⃣ Job Role Deep Dive Dashboard  
![image](https://github.com/user-attachments/assets/76228ef8-b592-4039-97db-6ba2031650ae)

This page lets users explore a selected job title in detail, such as ML Engineer.

**Visuals Explained:**
- **Salary Cards** show hourly and yearly averages.
- **Job Type and Experience Level Charts** highlight role composition.
- **Industry Breakdown** shows which sectors hire this role the most.
- **Job Posting Frequency** tracks monthly trends.
- **Top Companies Bar Chart** ranks employers for the selected job.

This dashboard helps users focus their efforts on a specific role, understand where it’s in demand, and who is hiring for it.

---

### 5️⃣ Company Insights Dashboard  
![image](https://github.com/user-attachments/assets/cf1bfec0-5df8-4df6-9c14-657b845a4036)

This page provides detailed, company-specific insights to compare employers and understand their hiring patterns.

**Visuals Explained:**
- **Average Yearly Salary by Company** compares top-paying firms.
- **Top Industries Pie Chart** highlights which sectors offer the most sponsored jobs.
- **Job Type Breakdown** shows employment types across all companies.
- **Job Postings by Experience Level** informs users about entry- vs. senior-level trends.
- **Date Range & Company Filters** allow focused, real-time exploration.

This view enables users to strategically prioritize employers based on reputation, job type, compensation, and demand.

---

### 6️⃣ Top 10 Job Explorer Dashboard  
![image](https://github.com/user-attachments/assets/fe932ebe-e11b-4adb-9051-dd882d0d2d44)

This dashboard is designed for users who may not know where to start — it automatically surfaces the top 10 job opportunities based on roles, companies, salaries, and industries.

**Visuals Explained:**
- **Top 10 Highest Salary Job Roles:** Identify top-paying roles like ML Engineer and DevOps Engineer.
- **Top 10 Companies by Number of Jobs:** See who is sponsoring the most roles (e.g., Wells Fargo, BOEING).
- **Top 10 Job Locations:** Focus on states like CA, TX, and IL with the most listings.
- **Top 10 Industries:** Spot high-sponsorship sectors like Tech, Finance, and Education.
- **KPI Cards** display total sponsored jobs, average salary, and average company rating.
- **Filters** let users refine by job type and company rating.

This page is perfect for quick, informed discovery — especially for users new to the job search.

---

### 7️⃣ Conclusion  
![image](https://github.com/user-attachments/assets/79783e70-5440-421f-b2c9-0d3d93092c66)

A summary page that ties together insights from all dashboards.  
It reinforces how users can combine market-level trends with company- and role-level data for a smarter, more strategic job hunt.

---

## 📌 Dashboard Purpose

By combining high-level trends, deep job-role insights, and employer comparisons, this Power BI dashboard equips international job seekers with the tools they need to:
- Identify top companies hiring visa-sponsored talent
- Focus on high-demand job roles and locations
- Compare salaries and hiring trends across industries
- Make confident, data-backed career decisions

## 👥 Project Team
- Nikhila Sree Inti
- Ramoji Jajam
- Pavan Barapati
- Bhargavi Indla
- Megha Shyam Dora Hanumanthu
---

## 📄 License  
MIT License. See [LICENSE](LICENSE) for details.
