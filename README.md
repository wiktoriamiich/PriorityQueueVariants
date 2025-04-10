# 🧮 PriorityQueueVariants – C++ Implementations of Priority Queues

This project explores multiple implementations of **priority queues** in C++. Each version demonstrates a different approach to managing elements with priorities, allowing comparisons in efficiency, complexity, and memory usage.

---

## 🧩 What does the project include?

- ⚙️ **Two priority queue variants**:
  - **Max Heap**
  - **Fibonacci Heap**
- 🧪 **Operation benchmarking** – execution time of each operation is measured
- 📊 **Theoretical vs. practical analysis** – confirmed time complexity matches theoretical expectations (in nearly all cases!)
- 🧠 **Object-Oriented Design** – the code uses encapsulation, inheritance, polymorphism, and abstraction
- 🛠️ Each structure supports classic operations like:
  - `insert`
  - `extractMax`
  - `modifyKey`
  - and more...

---

## 📂 Folder Overview

- **`src/`** – Core implementations of priority queue variants
- **`include/`** – Headers and interfaces for each variant
- **`main/`** – Test files and benchmarking code
- **`Makefile`** *(optional)* – Compile automation if present

---

## 📈 Benchmarking

We've measured the time of each fundamental operation to compare both data structures and determine which one performs better under specific scenarios.

🔍 Key goals:
- Understand trade-offs between **simplicity (Max Heap)** and **theoretical performance (Fibonacci Heap)**
- Test whether theoretical time complexities match practice (spoiler: mostly yes ✅)

---

## 🧪 How It Works

When you run the application, an interactive **console menu** is displayed. It allows users to select a data structure and perform various operations such as insertion, deletion, and display.

![{8EA9B4A8-907D-4437-AFFF-62C92E957B0C}](https://github.com/user-attachments/assets/d07cd7a5-3c08-470f-866e-a7f203bd972b)

![{FB22778D-71C3-475E-8BCE-9E679667FB78}](https://github.com/user-attachments/assets/d8c7033b-61b9-4f7f-a57c-c8fe21653a00)

---

## ▶️ Getting Started

1. **Clone the Repository**

   ```bash
   git clone https://github.com/wiktoriamiich/PriorityQueueVariants.git
   cd PriorityQueueVariants

2. **Compile the Program**

   ```bash
   g++ main.cpp -o PriorityQueueVariants

3. **Run the Application**

   ```bash
   ./PriorityQueueVariants



