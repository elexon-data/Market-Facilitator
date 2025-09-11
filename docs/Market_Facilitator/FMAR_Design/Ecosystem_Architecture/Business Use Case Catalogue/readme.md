# Business Use Cases & Stakeholders Overview

## BUC 1: Simplify market entry and reduce administrative burden
**Goal:**  
The goal of this BUC is to streamline the process of registering and onboarding flexible assets by creating a "one-stop-shop" for Flexibility Service Providers (FSPs). This will reduce the complexity, time, and cost involved in market entry. 

**Primary Beneficiaries / Stakeholders:**  
- **Flexibility Service Providers (FSPs)**
- **Independent Market Platforms (IMPs)**
- Actors: Installer, Original Equipment Manufacturer (OEM), Asset Owner, Public

**High-Level Supporting SUCs:**  
- UC-01.01: Register User – Establish user identities for FSP personnel  
- UC-01.02: Register Organisation – Persistent identity for FSP entity  
- UC-02.02: Register and Validate Asset – “Register once” for physical assets  
- UC-01.03 / UC-01.04 / UC-02.03 / UC-02.04 – Update and De-register SUCs  
- UC-02.01 / UC-05.03 / UC-05.05 / UC-05.06 – Trust and governance for market entry  

---

## BUC 2: Enhance network planning and investment efficiency
**Goal:**  
Provide SOs with a trusted, comprehensive view of registered flexible resources to improve planning and investment decisions. It aims to enhance planning accuracy, helping Distribution Network Operators (DNOs) make better investment decisions based on reliable, up-to-date data. The system also provides insights for long-term forecasting and supports efficient regulatory reporting.

**Primary Beneficiaries / Stakeholders:**  
- **National Energy System Operator (NESO)**
- **Distribution System Operators (DSOs)**
- **Distribution Network Operators (DNOs)**
- Actors: Asset Owner, Installer, Public

**High-Level Supporting SUCs:**  
- UC-02.02: Register and Validate Asset – Foundational locational/technical data  
- UC-05.01: Share FMAR System Details – API for SOs to query data  
- UC-05.02: Provide Analytics – Aggregated reports for investment planning  

---

## BUC 3: Enable efficient and coordinated market operation
**Goal:**  
Provide foundational data and rules to manage stacking and primacy conflicts; unify monitoring of participation, performance, and compliance. This ensures that assets are utilized in the most efficient manner while maintaining compliance and preventing service conflicts.

**Primary Beneficiaries / Stakeholders:**  
- **System Operators (DSOs, NESO)**
- **FSPs**
- Actors: Asset Owner, Installer, OEM

**High-Level Supporting SUCs:**  
- UC-03.01: Create Market Unit – Unique Market Units (SPUs/SPGs)  
- UC-04.01: Create and Maintain Product Catalogue – Central product definitions  
- UC-04.02: Record Market Unit Qualification Status – Eligibility tracking  
- UC-02.06: Manage Connection Limit – Grid constraint data  

---

## BUC 4: Increase market liquidity and competition
**Goal:**  
Increase the number/diversity of assets in flexibility markets, lowering barriers and improving transparency. By providing clear visibility and making it easier for assets to switch service providers, it encourages diversity in market participation and increases overall liquidity.

**Primary Beneficiaries / Stakeholders:**  
- **FSPs**
- **System Operators**
- Actors: Asset Owner, Installer, OEM, Public

**High-Level Supporting SUCs:**  
- UC-04.03: Discover Market Opportunities – Proactive asset notifications  
- UC-03.02 / UC-03.04: Reassign Market Unit & Owner-Initiated Asset Switch – Enable competitive switching  
- UC-01.xx / UC-02.xx: Simplified registration – Reducing barriers to entry  

---

## BUC 5: Assure regulatory compliance, market oversight, and inform policy strategy
**Goal:**  
The primary goal of this BUC is to create a transparent, auditable record of market participants and assets to ensure compliance with market rules. It also supports ongoing monitoring of flexibility volumes, growth trends, and market health. This system will provide the necessary data for regulators like Ofgem to assess performance and inform policy strategies.

**Primary Beneficiaries / Stakeholders:**  
- **Ofgem**
- **Elexon (Market Facilitator)**
- **NESO / DESNZ**
- Actors: Asset Owner, Installer, Public

**High-Level Supporting SUCs:**  
- All Register, Update, De-register SUCs (UC-01.xx, UC-02.xx, UC-03.xx) – Master record  
- UC-05.02: Provide Analytics – Market monitoring, performance assessment  
- UC-05.03: Dispute Resolution & Data Correction – Governance process  
- UC-05.06: Audit Trail Access & Reporting – Transparency and traceability  

---

## BUC 6: Foster innovation and reduce technology integration costs
**Goal:**  
This BUC aims to accelerate the adoption of new technologies by providing standardised data models and APIs, reducing the costs and complexity of technology integration. It ensures that all participants can integrate seamlessly into the system, promoting innovation while maintaining consistency across platforms.

**Primary Beneficiaries / Stakeholders:**  
- **Original Equipment Manufacturers (OEMs)**
- **Software Platforms / Integrators**
- Actors: Installer, Asset Owner, Public

**High-Level Supporting SUCs:**  
- UC-02.01: Maintain Asset Categories and Schemas – Standardised specifications  
- UC-02.02: Register and Validate Asset – Standardised asset registration  
- UC-05.01: Share FMAR System Details – Unified API for integration  
- UC-05.04: Onboard & Manage Third-Party Platforms – Streamlined integration  

---

## BUC 7: Enable new local and peer-to-peer flexibility models
**Goal:**  
Provide trust and data layer for granular, location-specific markets; support peer-to-peer trading and ANM optimisation.

**Primary Beneficiaries / Stakeholders:**  
- **Local Market Operators**
- **FSPs**
- **System Operators**
- Actors: Asset Owner, Installer, Public

**High-Level Supporting SUCs:**  
- UC-02.02: Register and Validate Asset – Precise locational data (MPAN)  
- UC-01.02: Register Organisation – Trusted register of participants  
- UC-05.01: Share FMAR System Details – Secure API access for local operators  
- UC-05.05: Consumer Consent Interface & Verification – Integration with national consent solution  

