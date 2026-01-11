# Minting Primitive

Minting defines how value is created inside the Finovia ecosystem.  
It is not “printing money” — it is the controlled issuance of *economic units* tied to real activity, obligations, or collateral.

---

## 🎯 Goals of the Minting Primitive

- Ensure value creation is **explicit**, **auditable**, and **bounded**
- Tie issuance to **events**, **programs**, or **collateral**
- Enable programmatic creation of:
  - credits
  - obligations
  - claims
  - entitlements
  - rewards
  - settlement instructions

---

## 🧱 Minting Types

### 1. **Execution Mint**
Value created when an action is performed.
Examples:
- task completion
- service delivery
- workflow execution

### 2. **Collateralized Mint**
Value created against locked assets.
Examples:
- deposits
- reserves
- escrow

### 3. **Programmatic Mint**
Value created by rules.
Examples:
- rewards
- rebates
- incentives
- loyalty

### 4. **Settlement Mint**
Value created to reconcile multi-party flows.

---

## 🔐 Constraints

Minting must always be:
- deterministic  
- logged  
- reversible only through explicit burn  
- tied to a program or event  
- visible to the accounting kernel  

Minting is the foundation of Finovia’s economic engine.
