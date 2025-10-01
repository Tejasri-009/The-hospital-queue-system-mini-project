# The-hospital-queue-system-mini-project
# 🏥 Hospital Queue System

This is my mini project on a hospital queue system.  
The idea is to arrange patients based on how serious their disease is, so that critical cases get treated first instead of just following arrival order.  
I used the concept of a priority queue to handle this in a simple way.

## Features
- Add patients with name, disease, and severity.
- Patients are sorted by priority (critical first).
- Easy and straightforward implementation.

---

## How It Works
- Each patient is given a priority value:
  - 1 → Critical (like heart attack, stroke, accidents)  
  - 2 → Serious (like high fever, infections)  
  - 3 → Normal (like cold, mild headache)  
- The system always treats patients with the highest priority first.

---

## Example
If we add these patients:
- Ravi → Heart Attack → Priority 1  
- Anu → Fever → Priority 2  
- John → Cold → Priority 3  

The treatment order will be:  
1. Ravi  
2. Anu  
3. John  

---

## Technologies Used
 Programming Language: (Python / C++ / Java)  
 Data Structures: Priority Queue .
 
---Here the small example to make it more clear---
 ## Example
Patients:
- Ravi → Heart Attack → Priority 1  
- Anu → Fever → Priority 2  
- John → Cold → Priority 3  

Order of treatment: Ravi → Anu → John 
 


