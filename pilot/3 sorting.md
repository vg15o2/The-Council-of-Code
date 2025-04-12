<!-- sorting algos, gotta refine content and update with snippets -->


# The Sorting Fellowship of Middle-Earth

## 🌍 The World of Arrays – *Middle-Earth in Disarray*

The Numbers were scattered across the lands—some in Mordor, some in the Shire. The Dark Lord of Disorder had struck again. Only the **Great Sorters** could restore the balance.

---

## 🌊 1. **Bubble Sort – Samwise the Faithful**
> “I can’t carry the array, but I can carry you!”

Just like **Sam**, Bubble Sort is loyal and stubborn. He goes through the array, **pair by pair**, and **bubbles up the largest** like he’s pushing Frodo up Mount Doom. Again. And again. Until peace is achieved (or runtime error).

- 📜 Time: O(n²)  
- 🧠 Best for: Small lists, or teaching your Hobbit nephews
- 🛡️ Stable? Yes
- 🪶 Memory: O(1)

> *"Even the smallest sort can change the course of the future."*

---

## 🛡️ 2. **Selection Sort – Boromir of Gondor**
> “One does not simply avoid O(n²).”

Noble but flawed. Selection Sort **searches the entire array**, picks the smallest (or largest), and **puts it in its rightful place**—like Boromir trying to protect Gondor with brute force. He doesn’t care about stability. He just **wants it done.**

- 📜 Time: O(n²)
- 🛡️ Stable? No
- 🪶 Memory: O(1)

> *“The smallest number is out there… I will find it.”*

---

## 📜 3. **Insertion Sort – Frodo the Quiet Sort**
> “I will carry this number to its place, though I do not know the way.”

Starts with one number in order, then inserts others **one by one into the sorted part**. Like Frodo’s careful journey through Mordor, step-by-step, always moving toward order.

- 📜 Best case: O(n)
- 🧠 Worst case: O(n²)
- 🛡️ Stable? Yes
- 🪶 Memory: O(1)

> *“Even in the darkest disorder, one can sort a path.”*

---

## 🧙‍♂️ 4. **Merge Sort – Gandalf the Grey**
> “Fly, you fools! (Recursively.)”

The wise old wizard of the sorts. Merge Sort **divides the array** into tiny pieces (like separating Fellowship), **sorts them**, and **merges them** gracefully back together. Always predictable. Always dependable.

- 📜 Time: O(n log n)
- 🛡️ Stable? Yes
- 🪶 Memory: O(n)

> *“A sort is never late. It arrives exactly when it means to.”*

---

## 🔥 5. **Quick Sort – Aragorn the Ranger**
> “I am no brute-force sort.”

Elegant and fast, **Aragorn** (aka Quick Sort) picks a **pivot** (a leader), and **partitions** the others—smaller to the left, larger to the right—and **recursively sorts** the kingdom. But beware! A **bad pivot** is like walking into Mordor unprepared.

- ⚔️ Time: O(n log n) avg, O(n²) worst
- 🛡️ Stable? No
- 🪶 Memory: O(log n)

> *“There is always hope… if the pivot is wise.”*

---

## 🏔️ 6. **Heap Sort – Gimli the Dwarf**
> “Nobody tosses a dwarf. But I toss max elements.”

**Gimli** builds a massive **max-heap** mountain (a binary tree), digs out the **largest elements**, and rebuilds until everything is sorted. He’s a rough gem—efficient, grounded, not very elegant.

- 📜 Time: O(n log n)
- 🛡️ Stable? No
- 🪶 Memory: O(1)

> *“Let them come! There is still one dwarf sorting in Moria.”*

---

## 👁️ 7. **Counting Sort – Legolas the Elf**
> “I see the range… and I count them.”

Legolas doesn’t waste time comparing. With **sharp vision**, he **counts the frequencies** of each number (within a known range), and places them accordingly. Elegant, efficient, but only works when numbers are in a known domain.

- 📜 Time: O(n + k)
- 🛡️ Stable? Yes
- 🪶 Memory: O(k)

> *“A red number is counted. And another. And another.”*

---

## ✨ 8. **Radix Sort – The Eagles of the Sky**
> “Sort by digits. Fly over the comparisons.”

Used when numbers are uniform in format. Radix Sort **sorts digit by digit** (from least to most significant), using **Counting Sort** underneath. Majestic, fast, and flies above the rest—but needs uniformity and consistency.

- 📜 Time: O(nk)
- 🛡️ Stable? Yes
- 🪶 Memory: O(n + k)

> *“The age of comparison-based sorts is over. The time of digit magic has come.”*

---

## 📚 The Red Book of Sorting: TL;DR

| Sort          | Role           | Time (Avg) | Stable | Space | Famous Quote |
|---------------|----------------|------------|--------|--------|-----------------|
| Bubble        | Sam            | O(n²)      | ✅     | O(1)   | “I’ll keep going!” |
| Selection     | Boromir        | O(n²)      | ❌     | O(1)   | “One does not simply…” |
| Insertion     | Frodo          | O(n²)      | ✅     | O(1)   | “Step by step…” |
| Merge         | Gandalf        | O(n log n) | ✅     | O(n)   | “Divide and merge!” |
| Quick         | Aragorn        | O(n log n) | ❌     | O(log n) | “There is always hope.” |
| Heap          | Gimli          | O(n log n) | ❌     | O(1)   | “Toss max, sort fast!” |
| Counting      | Legolas        | O(n + k)   | ✅     | O(k)   | “I can see the count.” |
| Radix         | Eagles         | O(nk)      | ✅     | O(n + k) | “Digit by digit.” |

