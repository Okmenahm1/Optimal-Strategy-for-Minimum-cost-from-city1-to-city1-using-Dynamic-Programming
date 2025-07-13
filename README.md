# Optimal Travel Strategy with Minimum Cost using Dynamic Programming

This project solves the problem of finding the **minimum-cost travel path** from a starting city (City1) to a destination city (City2), considering hotel and petrol costs along the way.

---

## 🎯 Problem Definition

- Travel from **City1** to **City2**, staying in a hotel at the end.
- The route includes **N stopovers**, each offering:
  - Multiple **cities** to choose from.
  - Multiple **hotels** per city.
- Travel and hotel costs vary by location.
- The goal is to find the **cheapest path and hotel** combination.

---

## 🔧 Features

- ✅ Computes the **optimal path and total cost**
- 🏨 Includes **hotel cost and petrol cost** at each step
- 📊 Builds and displays the **Dynamic Programming table**
- 🖥️ Provides a **simple user interface** for input/output

---

## ⚠️ Known Limitation

- The program **successfully generates some valid alternative paths** (e.g., second-best, third-best),  
  but **not all possible alternatives are explored**.
- This is likely due to a **limitation in the current algorithm**, which may **miss some viable paths**  
  or fail to fully search the solution space.

---

## 📌 Example Output

- **Best Path**: City1 → CityA → CityB → City2  
- **Final Hotel**: Hotel Z  
- **Total Cost**: 195

- **DP Table**:  
  (Displayed through the UI)

---

<img width="1467" height="919" alt="image" src="https://github.com/user-attachments/assets/ce8a8a88-6d08-4a5d-bf9c-00944b77511c" />

<img width="1477" height="950" alt="image" src="https://github.com/user-attachments/assets/1b6a475c-86ce-4cab-8330-ec3bd2173570" />

