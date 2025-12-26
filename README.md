# 🔥 Spark Internals Lab

Deep dive into **Apache Spark internals** — understanding how Spark executes jobs under the hood, including **jobs, stages, tasks, shuffle, memory management, AQE, and execution plans**.

This repository is focused on **how Spark actually works**, not just how to use APIs.

---

## 🚀 Why this Repository?

Most Spark tutorials stop at:
```python
df.groupBy("col").count()

## Project Goals

This project goes deeper and answers the following questions:

- How many **jobs, stages, and tasks** are created?
- When and **why shuffle happens**
- How **memory is used** inside executors
- Why Spark **spills to disk**
- How **Spark 3 Adaptive Query Execution (AQE)** changes execution
- How to read the **Spark UI** and **execution plans**

---

## Who This Repository Is For

This repository is designed for:

- Data Engineers
- Big Data Engineers
- Senior Spark Developers
- Engineers preparing for **system design** and **performance interviews**

---

## 🧠 What You Will Learn

- ✔ Jobs vs Stages vs Tasks (with examples)
- ✔ Narrow vs Wide transformations
- ✔ Shuffle mechanics (map side & reduce side)
- ✔ Spark 2 vs Spark 3 execution differences
- ✔ Adaptive Query Execution (AQE)
- ✔ Executor & Driver memory internals
- ✔ Cache vs Persist
- ✔ Memory spill (execution & storage)
- ✔ How to read Spark UI correctly
- ✔ How to read Catalyst execution plans

