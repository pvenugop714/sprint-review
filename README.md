### **📝 Sprint Review**  

---

## Completed Work & Achievements

1️⃣ **User Authentication**
   - **JWT-based authentication** for login and registration.  
   - Users receive a **secure token** upon login.  

2️⃣ **OAuth Login**
   - Integrated **Google & Facebook login** using **Passport.js**.  
   - Allows users to log in without needing a password.  

3️⃣ **Role-Based Access Control (RBAC)**
   - Implemented **role-based permissions** for **Student, Instructor, and Admin**.  
   - Ensures **restricted access** to specific functionalities.  

4️⃣ **Security Questions for Password Reset**
   - Users **set up a security question & answer** during registration.  
   - Required before **resetting a password**.  

5️⃣ **Password Reset via Link & OTP**
   - Users can reset their password using a **reset link** sent via email.  
   - **OTP-based password reset** (email verification).  

6️⃣ **API Security Enhancements**
   - Implemented **authentication middleware** to **protect routes**.  
   - Added **error handling & validation** for API requests.  

*"All these implementations make our backend secure and user-friendly."*

---

## Challenges Faced & How We Resolved Them
1️⃣ **OAuth Integration Delays**  
   - Initially faced issues in setting up **Google & Facebook login**.  
   - **Solution:** Used **Passport.js** and debugged API redirections.  

2️⃣ **Security Question Verification Issues**  
   - Issue: The security answer stored was **hashed**, and direct comparison failed.  
   - **Solution:** Implemented **bcrypt.compare()** for correct validation.  

3️⃣ **Password Reset Token Expiry & Handling**  
   - Initially, **tokens were not invalidating** after use.  
   - **Solution:** Implemented **token expiration & auto-removal after reset**.  

*"Despite these challenges, we managed to overcome them and improve our authentication flow."*

---

##  Pending Items & Blockers
**You:**  
*"While we accomplished most of the planned features, a few tasks are still pending and will be carried over to the next sprint."*

| **Pending Feature** | **Reason for Delay** | **Next Steps** |
|---------------------|---------------------|----------------|
| **Duo MFA Implementation** | Still researching best integration approach | Will be implemented next sprint. |
| **PostgreSQL Database Integration**  | Awaiting database setup. |

*"We are prioritizing these tasks in the upcoming sprint."*

---

##  Next Steps & Sprint Planning
✅ **Implementing Duo Multi-Factor Authentication (MFA)**  
   - Require **Duo push notification or OTP verification** before login.  
   - Protect sensitive actions with **step-up authentication**.  

✅ **Migrating from JSON storage to PostgreSQL**  
   - Move user data from **temporary JSON files** to **PostgreSQL database**.  
   - Ensure **scalability and long-term data persistence**.  

✅ **Enhancing API Security**  
   - Implement **rate limiting & monitoring** for API endpoints.  
   - Add **logging & alerts** for suspicious login attempts.  

*"Completing these will significantly enhance the security and performance of our LMS backend."*

---
