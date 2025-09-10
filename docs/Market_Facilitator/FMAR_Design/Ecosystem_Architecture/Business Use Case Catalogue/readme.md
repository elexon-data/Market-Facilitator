# FMAR Business Use Cases Overview

---

This document provides a snapshot of the key business use cases FMAR is proposed to deliver as discussed in our Flexibility Market Asset Registration (FMAR) solution workshops. 



## BUC 1: Simplify market entry and reduce administrative burden

**ID:** `BUC1`  
**Goal:** Create a "one-stop-shop" for all registration activities, drastically reducing the time, cost, and complexity for Flexibility Service Providers (FSPs) and Independent Market Platforms bring flexible assets into the market.  


**Primary Beneficiaries:**  
- Flexibility Service Providers (FSPs)  
- Independent Market Platforms (IMPs)  

**Primary Supporting SUCs:**  
- `UC-01.01`: Register User  
- `UC-01.02`: Register Organisation  
- `UC-02.01`: Register and Validate Asset  
- `UC-01.03`: Update Organisation  
- `UC-01.04`: De-register Organisation and Deactivate User  
- `UC-02.02`: De-register Asset  
- `UC-02.03`: Update Asset Details  
- `UC-02.04`: Export Asset Data  
- `UC-02.05`: Manage Connection Limit  
- `UC-05.03`: Dispute Resolution and Data Correction  
- `UC-05.05`: Consumer Consent Interface and Verification  
- `UC-05.06`: Audit Trail Access and Reporting  

**Key Considerations:**  
 

---

## BUC 2: Enhance network planning and investment efficiency

**ID:** `BUC2`  
**Goal:** Provide System Operators (SOs) with a trusted, comprehensive, and near real-time view of registered flexible resources to improve accuracy and accelerate planning and investment decisions. Supports DNOs in investment decisions and evidence for regulators.  

**Primary Beneficiaries:**  
- National Energy System Operator (NESO)  
- Distribution System Operators (DSOs)  
- Distribution Network Operators (DNOs)  
- Public  

**Primary Supporting SUCs:**  
- `UC-02.01`: Register and Validate Asset  
- `UC-05.01`: Share FMAR System Details  
- `UC-05.02`: Provide Analytics  

**Key Considerations:**  
- Full value (e.g., “untapped potential analysis”) is realised when `UC-02.01` captures assets at installation. FMAR API endpoint could be the ‘single point of notification’ for installers, as referenced in the Department for Energy Security and Net Zero (DESNZ) recent call for evidence, is a key enabler. 

---

## BUC 3: Enable efficient and coordinated market operation

**ID:** `BUC3`  
**Goal:** Provide foundational data and rules to manage stacking and resolve primacy conflicts. Helps regulators and stakeholders monitor participation, performance, and compliance in a unified way, while preventing service conflicts.  

**Primary Beneficiaries:**  
- System Operators (DSOs, NESO)  
- Flexibility Service Providers (FSPs)  
- Public  

**Primary Supporting SUCs:**  
- `UC-03.01`: Create Market Unit  
- `UC-04.01`: Create and Maintain Product Catalogue  
- `UC-04.02`: Record Market Unit Qualification Status  
- `UC-02.05`: Manage Connection Limit  

**Key Considerations:**  
- None noted.  

---

## BUC 4: Increase market liquidity and competition

**ID:** `BUC4`  
**Goal:** Increase the number and diversity of assets participating in flexibility markets by lowering barriers and improving transparency of opportunities. Communicates with site owners, asset owners, and operators to demonstrate added-value opportunities.  

**Primary Beneficiaries:**  
- Flexibility Service Providers (FSPs)  
- Independent Market Platforms (IMPs)  
- Asset Owners  
- Installers  
- Public  

**Primary Supporting SUCs:**  
- `UC-04.03`: Discover Market Opportunities  
- `UC-03.02`: Re-assign Market Unit to a New Service Provider  
- `UC-03.04`: De-register Market Unit  
- `UC-02.06`: Process Owner-Triggered Asset Switch between FSPs
- Core simplification from `UC-01.xx` and `UC-02.xx` lowers barriers to entry.  

**Key Considerations:**  
- None noted.  

---

## BUC 5: Assure regulatory compliance, market oversight, and inform policy strategy

**ID:** `BUC5`  
**Goal:** Create an auditable, transparent, and authoritative record of market participants and assets to support compliance monitoring and overall market health.  
- Enables Ofgem to track and forecast flexibility volumes, growth, and trends.  
- Prevents double counting of single assets across market units.  

**Primary Beneficiaries:**  
- Ofgem  
- Elexon (Market Facilitator)  
- NESO  
- DESNZ  
- Public  

**Primary Supporting SUCs:**  
- `UC-01.xx` / `UC-02.xx` / `UC-03.xx`: All Register, Update, and De-register SUCs  
- `UC-05.02`: Provide Analytics  
- `UC-05.03`: Dispute Resolution and Data Correction  
- `UC-05.06`: Audit Trail Access and Reporting  

**Key Considerations:**  
- None noted.  

---

## BUC 6: Foster innovation and reduce technology integration costs

**ID:** `BUC6`  
**Goal:** Accelerate adoption of new flexible technologies and software by providing standardised data models and APIs.  

**Primary Beneficiaries:**  
- Original Equipment Manufacturers (OEMs)  
- Flexibility Service Providers (FSPs)  
- Independent Market Platforms (IMPs)  
- Public  

**Primary Supporting SUCs:**  
- `UC-05.07`: Maintain Categories and Schemas  
- `UC-02.01`: Register and Validate Asset  
- `UC-05.01`: Share FMAR System Details  
- `UC-05.04`: Onboard and Manage Third-Party Platforms  

**Key Considerations:**  
- None noted.  

---

## BUC 7: Enable new local and peer-to-peer flexibility models

**ID:** `BUC7`  
**Goal:** Provide the trust and data foundation for granular, location-specific flexibility markets, including peer-to-peer trading and local energy markets. Supports optimisation of Active Network Management (ANM).  

**Primary Beneficiaries:**  
- Local Market Operators  
- Distribution System Operators (DSOs)  
- Asset Owners  
- Consumers / Public  

**Primary Supporting SUCs:**  
- `UC-02.01`: Register and Validate Asset  
- `UC-01.02`: Register Organisation  
- `UC-05.01`: Share FMAR System Details  
- `UC-05.05`: Consumer Consent Interface and Verification  

**Key Considerations:**  
- None noted.  

---
