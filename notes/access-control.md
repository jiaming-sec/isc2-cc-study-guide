# 🔐 **Access Control: Principles, Models & Best Practices**

Access control is a fundamental security mechanism used to regulate who or what can view, modify, or interact with digital resources. It ensures that only authorized individuals have access to specific data and systems, helping to prevent unauthorized actions and security breaches.

---

## 📌 **1. Key Principles of Access Control**

### 🔹 **1.1 The Principle of Least Privilege (PoLP)**
> Users should be granted the **minimum level of access** necessary to perform their job functions.

✅ Apply **Role-Based Access Control (RBAC)** to restrict user permissions.  
✅ Implement **Just-In-Time (JIT) access** to limit prolonged high-privilege use.  
✅ Regularly **review and audit user permissions** to prevent privilege creep.

### 🔹 **1.2 Separation of Duties (SoD)**
> Dividing critical tasks among multiple individuals reduces the risk of fraud or insider threats.

✅ Ensure that **no single user** has full control over a sensitive operation.  
✅ Require **dual approval processes** for high-risk activities (e.g., financial transactions, account modifications).  
✅ Implement **multi-user authorization** for privileged actions.

### 🔹 **1.3 Defense in Depth**
> Multiple layers of security controls help protect access at various levels.

✅ Combine **physical, administrative, and technical controls** for stronger security.  
✅ Use **multi-factor authentication (MFA)** as an added layer of identity verification.  
✅ Monitor **logins and access events** to detect anomalies.

---

## 🔄 **2. Access Control Models**

### 🔹 **2.1 Discretionary Access Control (DAC)**
> Owners of the resource determine access rights.

✅ Flexible but **high risk** due to user-controlled permissions.  
✅ Common in **Windows NTFS and UNIX file systems**.

### 🔹 **2.2 Mandatory Access Control (MAC)**
> Access is enforced by strict policies, often used in **government and military** environments.

✅ Users cannot change permissions; enforced by administrators.  
✅ **Example:** Security labels like **Top Secret, Confidential, Public**.

### 🔹 **2.3 Role-Based Access Control (RBAC)**
> Access is assigned based on **job roles and responsibilities**.

✅ Used in enterprises to enforce **consistent permission structures**.  
✅ **Example:** HR employees have access to payroll data, but not IT configurations.

### 🔹 **2.4 Attribute-Based Access Control (ABAC)**
> Access is determined based on **user attributes, context, and policies**.

✅ Highly flexible and scalable for **cloud security**.  
✅ **Example:** Allow access to documents **only during business hours** from company-approved devices.
