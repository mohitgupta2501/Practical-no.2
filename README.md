# Practical-no.2

### **COCOMO Model Table for Ayurvedic Management System**

| **Parameter**         | **Organic Mode (Estimated Values)** |
|-----------------------|------------------------------------|
| **Estimated Lines of Code (KLOC)** | 20 KLOC (Assumed) |
| **Effort (Person-Months)** | E = 2.4 × (KLOC)^1.05 |
| **Development Time (Months)** | D = 2.5 × (Effort)^0.38 |
| **Average Team Size** | T = Effort / Development Time |

#### **COCOMO Calculation Example (Assuming 20 KLOC)**

1. **Effort Calculation:**
   \[
   E = 2.4 \times (20)^{1.05} = 2.4 \times 22.245 = 53.39 \text{ PM}
   \]

2. **Development Time Calculation:**
   \[
   D = 2.5 \times (53.39)^{0.38} = 2.5 \times 5.04 = 12.6 \text{ months}
   \]

3. **Team Size Calculation:**
   \[
   T = \frac{53.39}{12.6} = 4.24 \approx 4 \text{ members}
   \]

### **Final Estimations for Ayurvedic Management System**
- **Effort Required:** 53.39 Person-Months
- **Development Time:** 12.6 Months (~1 year)
- **Team Size:** 4 Members

### **Explanation of the COCOMO Model for Ayurvedic Management System**  

The **COCOMO (Constructive Cost Model)** is a software estimation model used to predict the effort, time, and personnel required to develop a software project. It is categorized into three types: **Basic, Intermediate, and Detailed COCOMO.**  

For our **Ayurvedic Management System**, we have used the **Basic COCOMO Model**, which considers the estimated **Lines of Code (KLOC)** to calculate development parameters.  

---

### **Breakdown of the Calculation:**
1. **Effort (Person-Months)**
   - Effort refers to the total amount of work needed to complete the project, measured in **person-months (PM)** (i.e., the work done by one person in a month).
   - The formula used:  
     \[
     E = 2.4 \times (KLOC)^{1.05}
     \]
   - For **20 KLOC** (20,000 lines of code), the estimated effort is **53.39 person-months**.

2. **Development Time (Months)**
   - The time required to complete the project, given by:  
     \[
     D = 2.5 \times (Effort)^{0.38}
     \]
   - Using our calculated effort, the estimated development time is **12.6 months** (~1 year).

3. **Team Size**
   - The number of developers required to complete the project efficiently.
   - Formula:  
     \[
     T = \frac{\text{Effort}}{\text{Development Time}}
     \]
   - For our system, it results in **approximately 4 developers** working on the project.

---

### **Interpretation**
- Since the **Ayurvedic Management System** is a **moderate-sized web-based system**, it falls into the **Organic Model** category, where projects are relatively small, well-understood, and developed by small teams.
- The estimated **development time of 12.6 months** and a **team of 4 members** suggest that it is a **medium-scale project**, requiring systematic planning and execution.
- The **effort (53.39 PM)** indicates the total workload needed, which can be distributed among developers based on their expertise in **frontend, backend, database management, and system integration**.

---

### **Conclusion**
The **COCOMO Model** helps in project planning by estimating the required resources, duration, and effort needed for software development. Based on these calculations, the **Ayurvedic Management System** requires **around 4 developers working for approximately 12.6 months** to complete the project efficiently.  

Let me know if you need further modifications or a comparison with other COCOMO models! 🚀
