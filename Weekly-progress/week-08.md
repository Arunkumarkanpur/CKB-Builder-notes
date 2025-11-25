# Builder Track – Weekly Progress Report 

---

###  Topics Covered
- Intro to Script – **Class 5: Debugging**
- Intro to Script – **Class 6: Type ID**

---

##  Class 5 – Debugging

This week, I learned how to **debug CKB scripts** using two different methods:

1. **GDB (GNU Debugger)**  
   - Used for debugging **C/Rust compiled scripts**.  
   - Helps run failed transactions inside the debugger and step through the code.

2. **REPL (JavaScript Debugging)**  
   - Helps call **CKB syscalls** interactively.  
   - Useful for quickly checking values and identifying logic issues.

I practiced running a failed transaction inside the CKB debugger and stepping line-by-line to locate bugs.

---

##  Class 6 – Type ID

I learned the concept of **Type ID** and why it is important in the Nervos CKB blockchain:

- Helps create **unique** and **upgradable** scripts  
- Ensures each script has a **unique identity**  
- Allows **safe contract upgrades**  
- Prevents duplicate or fake Type IDs through special validation rules  

---

##  Key Takeaways

- Debugging becomes easy once tools are properly setup.  
- **GDB** → for compiled scripts  
- **REPL** → for JavaScript scripts  
- **Type ID** enables controlled and secure smart contract upgradability  
- Maintains **security**, **uniqueness**, and **integrity** of scripts on CKB.

