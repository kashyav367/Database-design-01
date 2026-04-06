# Instagram Thrift Store - ER Diagram

##  Overview
Database design for an Instagram-based thrift & handmade store. It manages products, customers, orders, payments, and shipping.

##  Key Points
- Thrifted items → single quantity  
- Handmade items → multiple stock  
- One customer → many orders  
- One order → many products (via Order_Items)

## Entities
- Customers  
- Products  
- Orders  
- Order_Items  
- Payments  
- Shipping  
- ThriftedProducts  
- HandmadeProducts  

##  Relationships
- Customer → Orders (1:M)  
- Orders → Order_Items (1:M)  
- Products → Order_Items (1:M)  
- Order → Payment (1:1)  
- Order → Shipping (1:1)  

## ER Diagram
![ER Diagram](diagram-export-4-6-2026-11_13_43-PM.png)

---
 Database design assignment
