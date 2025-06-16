
# 🗳️ Electronic Voting Machine (GUI-based Voting System)

A simple yet functional **Electronic Voting Machine** (EVM) built using **Java Swing**, designed to simulate the real-world voting process with features like input validation, secure vote handling, and result generation. This project provides an educational and practical demonstration of digital voting systems.

---

## 📌 Project Overview

This project replicates the core features of an electronic voting system:

* Voter ID validation
* Vote casting for predefined candidates
* Prevention of double voting
* Real-time vote counting
* Display of election results

The interface is user-friendly and interactive, making it suitable for academic, organizational, and small-scale democratic exercises.

---

## 🎯 Features

* **Graphical User Interface (GUI):** Built with Java Swing for a clean and intuitive design.
* **Input Validation:** Only registered Voter IDs can vote.
* **Vote Security:** One vote per ID; re-voting is not allowed.
* **Dynamic Result Display:** Real-time counting and display of votes with winner announcement.
* **Custom Candidate Setup:** Easily modify candidate names and symbols.

---

## 👩‍💻 Technologies Used

* **Language:** Java
* **GUI Library:** Java Swing
* **IDE Recommended:** IntelliJ IDEA / NetBeans / Eclipse

---

## 📂 Project Structure

```
├── ElectionCommisionOFPakistan.java   # Main driver class
├── Candidate.java                     # Candidate class with vote counting logic
├── VotingMachineGUI.java              # GUI implementation using Swing
```

---

## ▶️ How to Run

1. Open the project in your preferred Java IDE.
2. Ensure Java JDK 8 or above is installed.
3. Compile and run the `ElectionCommisionOFPakistan.java` file.
4. Interact with the GUI to simulate the voting process.

---

## 📷 GUI Preview

![Voting System Flowchart](A_flowchart_depicts_the_process_of_a_voting_system.png)

---

## 🔒 Valid Voter IDs

The system is initialized with 10 voter IDs:

```
11, 22, 33, 44, 55, 66, 77, 88, 99, 100
```

You can change or expand this list in the source code easily.

---

## 📘 Use Cases

* Educational institutes for student elections
* Organizations for internal polls
* Clubs and societies for voting activities
* Learning resource for GUI and event-driven programming

---

## ⚖️ Limitations

* Voter data is hardcoded.
* No database connectivity (votes are reset on rerun).
* Limited scalability for large-scale elections.

---

## ✅ Future Improvements

* Add database or file system for persistent vote storage.
* Integrate authentication system (e.g., OTP or face recognition).
* Support candidate registration dynamically.
* Export results to PDF or CSV.

