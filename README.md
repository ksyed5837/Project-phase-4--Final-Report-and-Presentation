
# Developing and Optimizing Data Structures for Real-World Applications Using Python
### A Unified Framework for Scalable E-Commerce Inventory & Recommendation Systems
**Author:** Kashif Ali Syed  
**Course:** MSCS-532 – Algorithms and Data Structures  
**University of the Cumberlands**  
**Instructor:** Brandon Bass  

---

## Project Overview
This repository contains a multi-phase project that demonstrates the full lifecycle of designing, implementing, optimizing, and integrating data structures for a real-world e-commerce application.  
The system supports both:

- **Dynamic inventory management**
- **Scalable recommendation generation**

The project showcases how theoretical concepts in data structures translate into practical, optimized Python solutions.

---

## Project Goals
- Build efficient, scalable data structures using Python  
- Support fast SKU lookups, updates, and category indexing  
- Implement a graph-based recommendation engine  
- Optimize performance across hashing, graph traversal, caching, and search  
- Evaluate memory usage and runtime improvements  
- Integrate all phases into a complete final system  

---

##  Repository Structure
```
📦 Project-Data-Structures
│
├── phase1_design/          # Data structure design
├── phase2_inventory/       # Inventory proof-of-concept
├── phase3_optimization/    # Optimization, AVL, hashing, graph
├── final_report/           # Final DOCX/PDF report
├── final_presentation/     # PowerPoint slides (PPTX)
└── README.md               # Project documentation
```

---

##  Phase 1 — Data Structure Design
Core data structures designed:

- **Hash Maps** – O(1) lookups  
- **Adjacency Lists** – similarity graph  
- **Heaps (min-heap)** – top‑K ranking  
- **LRU Cache** – repeated query optimization  
- **AVL Trees** – balanced search  

---

##  Phase 2 — Inventory Proof of Concept
Features:

- SKU → Product mapping  
- Category → SKU sets  
- Add/remove/update operations  
- Input validation  
- Demonstration tests  

---

##  Phase 3 — Optimization & Scaling
### Major performance improvements:
- Open addressing + quadratic probing  
- Dynamic hash table resizing  
- Adjacency list conversion  
- Graph pruning (70%+ memory saved)  
- AVL balanced search tree  
- Lazy loading + __slots__  

### Performance Gains:
- Hash lookups: **4× faster**  
- Graph traversal: **3–4× faster**  
- AVL search: **5× faster**  
- Recommendation latency: **2.48s → 0.41s**  

---

##  Integrated Architecture
### 1. Data Layer  
Inventory store, category index, user–item interactions.

### 2. Recommendation Layer  
Similarity graph, AVL trees, heaps, LRU cache.

### 3. Application Layer  
Inventory API + Recommendation API.

---

##  Deliverables Included
- ✔ **Final 12–16 page APA report**  
- ✔ **Final 15–20 slide presentation**  
- ✔ **Optimized Python code**  
- ✔ **README documentation**  

---

##  Future Enhancements
- ML-based recommendations  
- Graph databases (Neo4j, RedisGraph)  
- Distributed processing  
- Real-time streaming  
- Auto-tuned thresholds  

---

##  Technologies Used
- Python 3.x  
- Custom data structures  
- Performance profiling  
- Jupyter / VS Code  
- PPTX + DOCX  

---

##  Learning Outcomes
This project demonstrates the ability to:

✔ Analyze & compare DS performance  
✔ Build scalable Python systems  
✔ Optimize algorithms & memory  
✔ Integrate multiple subsystems  
✔ Present a professional project  

---

