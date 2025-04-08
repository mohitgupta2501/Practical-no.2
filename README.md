
## **Practical No. 2**  
### **COCOMO Model Table for Ayurvedic Management System**

| **Parameter**                     | **Organic Mode (Estimated Values)**       |
|----------------------------------|-------------------------------------------|
| Estimated Lines of Code (KLOC)   | 20 KLOC (Assumed)                          |
| Effort (Person-Months)           | E = 2.4 × (KLOC)^1.05                      |
| Development Time (Months)        | D = 2.5 × (Effort)^0.38                    |
| Average Team Size                | T = Effort / Development Time             |

---

### **COCOMO Calculation Example (Assuming 20 KLOC)**

- **Effort Calculation**:  
  \[ E = 2.4 \times (20)^{1.05} = 2.4 \times 22.245 = \textbf{53.39 Person-Months} \]

- **Development Time Calculation**:  
  \[ D = 2.5 \times (53.39)^{0.38} = 2.5 \times 5.04 = \textbf{12.6 Months} \]

- **Team Size Calculation**:  
  \[ T = \frac{53.39}{12.6} = \textbf{4.24} \approx \textbf{4 Members} \]

---

### **Cost Estimation**  
Assuming an **average cost per developer per month** is ₹40,000:

\[
\text{Total Cost} = \text{Effort} \times \text{Cost per Person-Month}
= 53.39 \times 40,000 = \textbf{₹21,35,600}
\]

---

### **Final Estimations for Ayurvedic Management System**
- **Effort Required**: 53.39 Person-Months  
- **Development Time**: 12.6 Months (~1 year)  
- **Team Size**: 4 Members  
- **Estimated Total Cost**: ₹21,35,600

---

### **Explanation of the COCOMO Model for Ayurvedic Management System**

The **COCOMO (Constructive Cost Model)** is a widely used software estimation model to predict:
- **Effort** (in person-months)
- **Development time** (in months)
- **Team size**
- **Cost (₹)**

It helps in planning resources for software development.

#### **Model Used:**  
We have applied the **Basic COCOMO Model (Organic Type)**, suitable for:
- Relatively small
- Well-understood
- In-house developed projects with small teams

#### **Breakdown of the Calculation:**

- **Effort (Person-Months):**  
  Measures the total work required for the project.  
  \[ E = 2.4 \times (KLOC)^{1.05} \Rightarrow 53.39 PM \]

- **Development Time (Months):**  
  Measures how long the project will take.  
  \[ D = 2.5 \times (Effort)^{0.38} \Rightarrow 12.6 Months \]

- **Team Size:**  
  Number of developers needed.  
  \[ T = \frac{Effort}{Development Time} \Rightarrow 4 Members \]

- **Cost Estimation:**  
  Based on an average salary of ₹40,000 per month:  
  \[ 53.39 \times 40,000 = ₹21,35,600 \]

---

### **Interpretation**

Since the **Ayurvedic Management System** is a **moderate-sized web-based application**, it fits well into the **Organic Mode** category.

- The **team of 4 members** over a **12.6-month period** suggests a balanced workload.
- The **estimated effort (53.39 PM)** will be distributed across modules like:
  - Frontend Development
  - Backend Integration
  - Database Management
  - User Authentication
  - Reporting and Admin Panel
- The **budget** (₹21.35 Lakhs) helps stakeholders in planning project funding.

---

### **Conclusion**

The COCOMO Model enables efficient project planning and management.  
For the **Ayurvedic Management System**, the following resources are estimated:

- **Effort**: 53.39 Person-Months  
- **Duration**: 12.6 Months  
- **Team**: 4 Developers  
- **Cost**: ₹21,35,600

With this estimation, the project can be executed with realistic timelines, effective resource allocation, and accurate budgeting.
