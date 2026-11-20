# Lab 3: Component Modelling & Architectural Pattern Selection

**Student Name:** Soumik Sinha  
**Student USN:** PES1UG24CS463  
**Section:** 5H  
**Roll / Sl. No:** 32  
**Assigned Scenario:** Self-Service Coffee Kiosk System  

---

## Architectural Choice
**Layered Architecture (3-Tier Component-Based Architecture)**

## Deliverables Included
1. **Component Diagram**:
   - `Component_Diagram_Coffee_Kiosk.png` (High-resolution image)
   - `Component_Diagram_Coffee_Kiosk.pdf` (UML Vector PDF)
   - Models 5 primary components:
     - `<<component>> Touchscreen UI Controller`
     - `<<component>> Order Manager Component` (Given)
     - `<<component>> Payment Service Component` (Given)
     - `<<component>> Menu & Pricing Data Service`
     - `<<component>> Receipt Printer Hardware Interface`
   - Explicit ball (provided) and socket (required) interfaces:
     - `IOrderService`
     - `IPayment`
     - `IMenuCatalog`
     - `IPrintService`

2. **Written Justification**:
   - `Architecture_Justification_PES1UG24CS463.docx` (Microsoft Word Document, 1 page)
   - `Architecture_Justification_PES1UG24CS463.pdf` (PDF Document)
   - Detailed justification addressing scenario fit, hardware abstraction, single-direction workflow, PCI-DSS payment security isolation, and in-memory caching performance benefits.
