# 💻 Online Learning Applications Project

## 📘 Overview

This project was developed for the *Online Learning Applications* course (OLA) taught by M. Castiglioni. The aim is to design online learning algorithms to dynamically price multiple types of products under production constraints in both stochastic and non-stationary environments.

---

## 👥 Team

- 👤 Pasqual M.
- 👤 Vigasio S.
- 👤 Ragusa S.
- 👤 Nicosia A.

---

## 🧩 Problem Description

We simulate a company that must dynamically set prices for a portfolio of products across multiple rounds, subject to an overall production budget. Buyers have private valuations and purchase products priced below their valuations.

---

## 📌 Requirements

### 1️⃣ Single Product - Stochastic Environment
- Build a UCB1-based pricing algorithm **without** inventory constraint.
- Extend UCB1 to include **inventory constraints**.

### 2️⃣ Multiple Products - Stochastic Environment
- Use **Combinatorial-UCB** with inventory constraint on a joint distribution of valuations.

### 3️⃣ Best-of-Both-Worlds - Single Product
- Simulate a highly **non-stationary** environment (changing distributions).
- Implement a **primal-dual algorithm** with inventory constraint.

### 4️⃣ Best-of-Both-Worlds - Multiple Products
- Extend the environment to multiple correlated products.
- Design a **primal-dual regret minimizer** per product.

### 5️⃣ Slightly Non-Stationary Environment
- Partition rounds into intervals with fixed (but different) valuation distributions.
- Compare:
  - **Combinatorial-UCB with sliding window**
  - **Primal-dual method**
  

---
