#  Weekly progress

##  Topics Covered
- **Validation Model**
- **Script Basics**

---

##  Summary
In this section, I learned about the **Nervos CKB validation model** and how **scripts** operate within the **Cell Model**.  
Each cell contains:
- A **Lock Script** – controls who can spend the cell.  
- An optional **Type Script** – defines the validation logic for the cell’s data.  

During a transaction, **all scripts are executed**, and if any script fails, the **entire transaction is rejected**.  
This ensures consistency and security within the blockchain.

---

##  Script Structure
A CKB script consists of the following components:
- **code_hash** – identifies the script code.  
- **hash_type** – defines how the hash is calculated (data or type).  
- **args** – provides the input parameters for the script.  

---

##  Learning Highlights
- Wrote **simple scripts in C**.  
- Compiled them to **RISC-V architecture** for CKB execution.  
- Deployed the scripts on the **Nervos CKB test network**.  
- Learned that the **same script can be reused** with different arguments.  
- Explored running **JavaScript inside the CKB environment** using **Duktape**.

