# 📊 SAP MM / Procurement / Inventory Management Portfolio  

This portfolio documents my knowledge and practical experience with **SAP MM (Materials Management)**, focusing on **Inventory Management, Procurement, Reporting, and Master Data**.  
Each T-Code is explained with its **function** and **business utilization**.  

---

## 🗂 Reporting & Analysis  

| **T-Code** | **Description** | **Utilization** |
|------------|-----------------|-----------------|
| MB5T | Stock in Transit | Track goods moving between plants before receipt. |
| ME2N | Purchase Orders by PO Number | Analyze purchase orders by number sequence. |
| ME2L | Purchase Orders by Vendor | Monitor supplier performance & delivery. |
| ME2M | Purchase Orders by Material | Review procurement history for specific materials. |
| MB51 | Material Document List | Audit trail of goods movement & postings. |
| MB52 | Warehouse Stock Overview | Check stock balance by material/location. |
| MMBE | Stock Overview | View stock availability across plants & storage. |
| MM03 | Display Material Master | View material details for reference. |

---

## 📦 Inventory Management (Stock Management)  

| **T-Code** | **Description** | **Utilization** |
|------------|-----------------|-----------------|
| MB5B | Stocks for Posting Date | Check stock values on specific dates (e.g., month-end). |
| MBIA | Goods Issue | Record stock removal (e.g., for production). |
| MBIB | Transfer Posting | Move materials between storage locations. |
| MBIC | Goods Receipt | Post incoming goods into stock. |
| MR21 | Price Change | Update material valuation price. |
| MMSC | Material Master Change | Update storage/purchasing info for materials. |
| MM01 | Create Material Master | Add new materials (raw, finished, or packaging). |
| MM02 | Change Material Master | Edit existing material data. |
| MM03 | Display Material Master | View details of existing material records. |

---

## 🛒 Purchasing / Procurement  

| **T-Code** | **Description** | **Utilization** |
|------------|-----------------|-----------------|
| ME21N | Create Purchase Order | Generate vendor purchase orders. |
| ME22N | Change Purchase Order | Modify quantities, prices, or dates. |
| ME23N | Display Purchase Order | Review PO details across departments. |
| ME52N | Change Purchase Requisition | Adjust material requests before PO creation. |
| ME53N | Display Purchase Requisition | View requisition details for approval. |
| ME31K | Create Contract | Create long-term vendor agreements. |
| ME32K | Change Contract | Update terms or validity of contracts. |
| ME33K | Display Contract | Reference existing vendor contracts. |
| ME41 | Create RFQ | Request vendor quotations. |
| ME42 | Change RFQ | Edit RFQ details (quantities, deadlines). |
| ME47 | Quotation Evaluation | Compare and evaluate vendor quotes. |
| ME11 | Create Purchasing Info Record | Link material to vendor pricing & conditions. |
| ME13 | Display Purchasing Info Record | Review vendor-material relationship. |

---

## 📑 Material & Vendor Master  

| **T-Code** | **Description** | **Utilization** |
|------------|-----------------|-----------------|
| MM01 | Create Material Master | Add new product/material records. |
| MM02 | Change Material Master | Update material details. |
| XK01 | Create Vendor Master | Register new vendor details. |
| XK03 | Display Vendor Master | View supplier information (address, bank, etc.). |

---

## ⚙️ Additional Transactions  

| **T-Code** | **Description** | **Utilization** |
|------------|-----------------|-----------------|
| COOISPI | Production Order Info System | Track production order progress. |
| ZPP418 | Custom Transaction (Client-Specific) | Used for production/planning reports. |
| MB21 | Create Reservation | Reserve stock for future use (e.g., production). |
| MB22 | Change Reservation | Adjust reserved stock quantities/dates. |

---

## 🖥 Example Workflow  

A typical **Procure-to-Stock Process** in SAP:  

1. **ME21N** – Create Purchase Order for vendor.  
2. **MBIC** – Post Goods Receipt once items arrive.  
3. **MB52/MMBE** – Check updated stock levels.  
4. **MB51** – Review movement documents for auditing.  

This ensures complete visibility from **procurement → goods receipt → stock monitoring → reporting**.  

---

## 📊 Workflow Diagram  

![Procure-to-Stock Workflow](sap_procure_to_stock_flow.png)  

---

## 📌 About Me  

I am a **Certified Data Analyst & Manufacturing/Warehouse Professional** with over **10 years of experience** in **supply chain operations and ERP systems**.  
I specialize in:  
- SAP MM Transactions (Inventory, Procurement, Vendor & Material Master)  
- Data Analysis & Reporting (Excel, SQL, Power BI, Tableau)  
- Warehouse Operations & Production Planning  

🔗 Connect with me on [LinkedIn](#)  
📂 Explore more of my projects on [GitHub](#)  
