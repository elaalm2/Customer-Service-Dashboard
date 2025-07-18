
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

<img width="800" height="500" alt="Image" src="https://github.com/user-attachments/assets/683827d5-ec3c-4210-9954-25c3ae9db22e" />  

<img width="800" height="500" alt="Image" src="https://github.com/user-attachments/assets/88dd1d3e-cafb-4c71-87a5-d01d9e39c397" />  

<img width="800" height="500" alt="Image" src="https://github.com/user-attachments/assets/3667d84e-db03-4810-b626-f0efb986d692" />



[![Watch the demo](https://github.com/user-attachments/assets/2509495d-7fbf-4781-88c7-67f0db18b34f)](https://github.com/user-attachments/assets/eeb2cb96-1bd4-416c-8281-7c89d84cdc17)


## Important Insights
 1) **Service Level is On Target**
    - At 92.0%, we’re meeting our goal (91.5%), showing good responsiveness, but we need to keep monitoring performance on certain days.
 3) **Hold Time** 
    - Current hold rate is 10.8%, exceeding the 10% target. Process optimization may help reduce this
 3) **First Call Resolution (FCR)**
    - We achieved 92.1% FCR, which is well above the target (80%). This means most customer issues are solved on the first call a strong sign of quality service.
4) **Answer Rate Needs Improvement**
    - Current rate is 93.2%, slightly below the 95% target. This means we need to improve staffing or efficiency during busy hours.
 5) **Peak Hour is 3–4 PM**
    - The highest call volume occurs between 3:00 and 4:00 PM with over 2,450 calls. This is a key time to ensure strong agent coverage.
 6) **Sunday & Saturday weekends volume & performance**
    - Saturday and Sunday show 100% service level, mainly due to very low call volume and sufficient staffing.
 7) **Customer Inquiries & Resolution Rate**
    - The resolution rate is highest for Tech Support (80.2%) and slightly lower for Billing and Complaints (78–79%).
 8) **Some agents rated below target**
    - A few agents didn’t meet the target in several KPIs like rating, AHT, and hold %. This shows they may need more training or support to improve their performance.












