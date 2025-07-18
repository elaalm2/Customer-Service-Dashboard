
### Link to [MY LinkedIn](https://www.linkedin.com/in/hakeem-data-analyst/)
### Link to [Download The Dashboard file](https://drive.google.com/file/d/1kgbHsX_2_hzXFdgShx4Yrocw8_hEF7iq/view?usp=sharing) 

<br>
<div align="center">
    <img src="https://github.com/user-attachments/assets/bf50e636-6a1e-4964-a9be-6bc4cc78b8f4" alt="image" width="800" height="500">
</div>


## Introduction
<details>
   <summary><strong>📌 Overview (click)</strong></summary>

 ### 🔍 **Overview**  
> This multi-page Customer Service Dashboard offers a 360° view of operational efficiency, customer satisfaction, and team performance. Built using Microsoft Power BI, it enables decision-makers to monitor ticket volume, resolution efficiency, CSAT scores, SLA compliance, and agent performance in real time.    
> Designed for both executive overviews and deep operational insights, this report supports quick identification of bottlenecks and improvement areas in customer support operations.

</details>


<details>
   <summary><strong>📂 Data Sources (click)</strong></summary>

### **Data Sources**  
> The dataset used for this analysis is the **"Customer_Service_Dataset_Final"** Excel workbook which is custom made.  

**▼ 📑Dataset Files Explanation** [[Download]](https://docs.google.com/spreadsheets/d/15NNmCALT3iGQuEVeqhOOHXfX5tQYDmyz/edit?usp=sharing&ouid=109235881739082264954&rtpof=true&sd=true)  


1. **Tickets Sheet**  
   > - **<ins>TicketID</ins>**: Unique **ID** for each **Ticket**.
   > - **<ins>CustomerID</ins>**: Unique **ID** for each **Customer**.
   > - **<ins>AgentID</ins>**: Unique **ID** for each **Agent**.
   > - **<ins>CreatedDate</ins>**: Date of receiving the Contact or openning the Ticket.
   > - **<ins>ClosedDate</ins>**: Date of closing the Ticket.
   > - **<ins>Status</ins>**: The current status of the Ticket, whether it is closed, Escalated, in Progress, Open or Resolved.
   > - **<ins>Priority</ins>**: It indicates the urgency of the Ticket.
   > - **<ins>Category</ins>**: It is the Category of the issue or the inquiry which the customer is contacting us about.
   > - **<ins>SubCategory</ins>**: It is the Sub-Category of the issue or the inquiry which the customer is contacting us about.
   > - **<ins>Channel</ins>**: The communication channel which the customer is using.
   > - **<ins>FirstResponseTimeMin</ins>**: The time (in minutes) it takes for an agent to send their initial response to a customer inquiry.
   > - **<ins>ResolutionTimeHrs</ins>**: The time (in hours) it takes for an agent to resolve the Ticket.
   > - **<ins>SLAMet</ins>**: Whether the Ticket was resolved within the expected period or not.  
   
2. **Customers Sheet**  
   > - **<ins>CustomerID</ins>**: Unique **ID** for each **Customer**.
   > - **<ins>FirstName</ins>**: First Name of each **Customer**.
   > - **<ins>LastName</ins>**: Last Name of each **Customer**. 
   > - **<ins>Email</ins>**: The email of the customer.
   > - **<ins>Phone</ins>**: The phone number of the customer.
   > - **<ins>Country</ins>**: The country of the customer.
   > - **<ins>City</ins>**: The city of the customer.
   > - **<ins>CreatedDate</ins>**: The customer's account creation date.

3. **Agents Sheet**
   > - **<ins>AgentID</ins>**: Unique **ID** for each **Agent**.
   > - **<ins>FullName</ins>**: The full name of the agent.
   > - **<ins>Email</ins>**: The company email of the agent.
   > - **<ins>Team</ins>**: The team to which the agent is assigned.
   > - **<ins>Manager</ins>**: The manager of the agent.
   > - **<ins>Location</ins>**: The city of the agent.
   > - **<ins>HireDate</ins>**: The hiring date of the agent.
   > - **<ins>Status</ins>**: Whether the agent is still hired in the company or not.

4. **Feedback Sheet**
   > - **<ins>TicketID</ins>**: Unique **ID** for each **Ticket**.
   > - **<ins>CustomerID</ins>**: Unique **ID** for each **Customer**.
   > - **<ins>FeedbackID</ins>**: Unique **ID** for each **Feedback**.
   > - **<ins>Date</ins>**: The date of the feedback.
   > - **<ins>CSAT</ins>**: Customer Satisfaction Score (CSAT), typically rated 1–5.
   > - **<ins>Comments</ins>**: The written feedback of the customer.

5. **QualityScores Sheet**:
   > - **<ins>AgentID</ins>**: Unique **ID** for each **Agent**.
   > - **<ins>ReviewDate</ins>**: The date on which the quality audit was conducted.
   > - **<ins>ReviewDate</ins>**: A numerical rating that reflects the quality of the agent’s interaction based on predefined audit criteria.
   > - **<ins>ReviewedBy</ins>**: The name of the Quality Specialist who reviewed the ticket.

</details>

<!-- ------------------------------------------------------------------------------------------- -->

## 🗂️ Case Study
A rapidly growing tech support center was struggling with visibility into service quality, agent performance, and customer satisfaction. With support tickets coming from multiple channels and countries, leadership needed a consolidated reporting system to track performance and identify areas for improvement.  

## 🎯 Objective  
Build an interactive dashboard that helps:
> - Monitor ticket lifecycle and SLA adherence
> - Evaluate CSAT (Customer Satisfaction) trends
> - Pinpoint sub-categories with high complaint volumes
> - Assess overall efficiency and areas needing process improvement

## Main 𝐊𝐏𝐈𝐬
- **<ins>Total Tickets</ins>**: This represent the number of contacts we have received.
- **<ins>Tickets Resolved</ins>**: This represents the number of contacts Resolved and Closed.
- **<ins>Tickets Pending</ins>**: This represents the number of contacts Open, In Progress and Escalated.
- **<ins>AVG CSAT Score</ins>**: It is the average customer statisfaction score which indicates how much the customer is satisfied with our service. 
- **<ins>SLA Compliance %</ins>**: The percentage of tickets resolved or responded to within the agreed Service Level Agreement (SLA) timeframe.

## Process
1) Imported, explored and validated the data
2) Cleaned the data using Power Query
3) Created calculated Date table
4) Built a data model
5) Created key measures using DAX 
6) Designed an interactive and insightful dashboard

## Measures (Dax)
;
<img width="179" height="352" alt="Image" src="https://github.com/user-attachments/assets/c49835b0-f300-4c04-8033-2772bcffb482" />

## Data Model
<img width="450" height="700" alt="Image" src="https://github.com/user-attachments/assets/2401dbc0-bda0-48ae-a35a-9a04d00a7842" />

## Dashboard
<img src="https://github.com/user-attachments/assets/bf50e636-6a1e-4964-a9be-6bc4cc78b8f4" alt="image" width="800" height="500">  

<img width="800" height="500" alt="Image" src="https://github.com/user-attachments/assets/2c2e9091-a01d-4f35-9184-7032569167f2" />  

<img width="800" height="500" alt="Image" src="https://github.com/user-attachments/assets/88dd1d3e-cafb-4c71-87a5-d01d9e39c397" />  

<img width="800" height="500" alt="Image" src="https://github.com/user-attachments/assets/3667d84e-db03-4810-b626-f0efb986d692" />


[![Watch the demo](https://github.com/user-attachments/assets/aebcf8a2-c6c8-428e-8811-1ca8a15637b2)](https://github.com/user-attachments/assets/aebcf8a2-c6c8-428e-8811-1ca8a15637b2)


## 📌 Important Insights

## 🎯 Executive Overview (Page 1)
 1) **High Ticket Resolution Rate**
    - Out of 6,000 total tickets, 5,817 were resolved, achieving a 97% resolution rate, indicating strong operational efficiency.
 2) **Customer Satisfaction Needs Improvement**
    - The average CSAT score is 3.01 (out of 5), signaling a need to improve customer experience and service quality.
 3) **SLA Compliance at 85.7%**
    - We are achieving the SLA target without any issues.
 4) **Top Issue Categories**
    - The most reported sub-categories include Delayed, App Crash, and Bug Report, each with over 400+ tickets — pointing to key pain points in service or product experience.
 3) **CSAT Trend**
    - Monthly CSAT scores fluctuate slightly, with a noticeable dip in late Q3 (Oct–Nov), suggesting service inconsistency during that period.

## 📊 Tickets Overview (Page 2)

 1) **Even Distribution Across Channels**
    - Tickets are evenly distributed across Phone (24.8%), Email (23.95%), Chat (25.67%), and Social Media (25.58%) — indicating the need for balanced resourcing across all channels.
 2) **Ticket Priorities Are Evenly Spread**
    - High, Medium, Low, and Urgent priority tickets each make up around 25% of the total, highlighting the need to manage all urgency levels consistently.
 3) **Major Account Issues**
    - Most issues comes from Billing and Account categories. These represent the highest share of total support volume and need special process attention.
 4) **Ticket Status Breakdown**
    - Most tickets are Closed (5,760), with very few still Open (51), In Progress (70), or Escalated (62) — further proving operational control.

## 👥 Agent Performance (Page 3)
 1) **Agent Productivity**
    - Most agents resolved over 90% of their assigned tickets, with some like Joshua Roberts, Andrew Wilson, and Christopher Parker handling over 130 tickets each.
 2) **Response Time Gaps**
    - FRT ranges between 87 to 102 minutes — some agents like Michael Zamora and Amanda Martinez show higher-than-average FRT, indicating training or process issues.
 3) **CSAT Score Distribution**
    - CSAT scores vary from 2.80 to 3.03, with only a few agents exceeding the 3.0 mark (e.g., Yvette Bradley, Natalie Mullins) — room for overall improvement.
 4) **SLA Compliance by Agent**
    - Some agents maintain SLA above 90% (e.g., Christopher Lyons, Yvette Bradley), while others fall below 80%, indicating training opportunities.




