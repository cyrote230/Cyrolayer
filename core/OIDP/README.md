# OIDP (Offchain Intent Disclosure Protocol)

OIDP is a core protocol of CryoLayer, designed to provide **transaction intent transparency**.  
Its primary goal is to detect and record *intents* (planned transactions) **before** they are executed on the blockchain.  
This approach enables users, institutions, and partners to understand large-scale transaction flows in **real time**, without waiting for final confirmation on L1.

## Objectives of OIDP
- Deliver transparency on significant on-chain asset movements.  
- Reduce information asymmetry by exposing transaction intents.  
- Support ecosystems, exchanges, and institutions in making faster and more informed decisions.  

## Key Features
- **Real-time feed**: captures and displays transaction intents prior to confirmation.  
- **Neutral reporting**: provides factual data only, without market predictions or interpretations.  
- **Cross-chain integration**: can be deployed across various L1 and L2 networks without interfering with main chain activities.  

## Example Workflow
1. A large transaction is planned (≥100 ETH or equivalent).  
2. OIDP captures the intent through its gateway.  
3. The data is recorded and published, with a delay applied according to access policies.  
4. CryoDelta compares the disclosed intent with the actual execution.  

---

OIDP serves as the foundation of CryoLayer’s mission to deliver **trustless transparency**, available to partners through licensing or dedicated integrations.
