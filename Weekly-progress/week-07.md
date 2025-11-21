# Builder Track – Weekly Progress Report (Week 07)


---

##  Overview
This README summarizes the weekly progress made during Week 07 of the Builder Track. The focus areas were **User-Defined Tokens (UDT)** on CKB and **WebAssembly (WASM) execution on CKB’s RISC-V VM**.

---

##  Class 3: User-Defined Token (UDT)

###  Key Learnings
- CKB uses a **cell-based model** instead of centralized contract storage.
- Each UDT cell stores:
  - **Amount** (first 4 bytes)
  - **Lock script**
  - **Type script**

###  Type Script Rules
1. **Total input UDT = total output UDT**  
   Ensures no extra tokens are forged.
2. **Only issuer can mint initial tokens**  
   Controlled using a unique script argument.

###  Practical Work
- Explored a **JavaScript UDT script example**.
- Understood:
  - Token issuance  
  - Token transfer  
  - Script deployment on CKB  

###  Key Insight
CKB ensures **decentralized ownership** without depending on a single storage cell, removing bottlenecks.

---

##  Class 4: WebAssembly on CKB

###  Concepts Covered
- Why CKB prefers **RISC-V VM** over native WASM VM.
- How **WASM binaries are converted into RISC-V instructions** for execution.

###  Performance Notes
- WASM-on-RISC-V works but may be slower for complex programs due to:
  - Conversion overhead  
  - Memory handling limitations  

###  Future Enhancements
- Improved performance expected using:
  - **LLVM-based compilation**
  - Better WASM → RISC-V optimization pipelines

---

## 📈 Summary
This week included:
- Deep understanding of UDT architecture and token rules.  
- Practical script-level experience in issuing and transferring UDTs.  
- Learning how WASM programs run on CKB via RISC-V.  
