# Set Game – Java Multithreaded Simulation

A concurrent simulation of the card game **Set**, built in Java. The game supports multiple players and a synchronized dealer using threads, semaphores, and atomic variables. Developed as part of university coursework to demonstrate advanced multithreading, synchronization, and real-time system coordination.

---

## 🧩 Game Overview

- Players compete to find valid sets of cards on the board.
- A dealer thread manages the board and game flow.
- Multiple player threads independently search for and claim sets.
- Java concurrency primitives ensure proper synchronization and coordination.

---

## 🧪 Features

- ✅ Java-based concurrency using `Threads`, `Semaphores`, and `AtomicInteger`
- ✅ Fully synchronized, real-time simulation
- ✅ Modular OOP design
- ✅ Built-in logging system for thread actions
- ✅ Maven-based build and dependency management

---

## 🛠️ Technologies Used

- Java 11
- Maven
- JUnit 5 & Mockito (for testing)

---

## 🚀 How to Run

> Make sure you have **Java 11+** and **Maven** installed.

1. **Clone the repository**
   ```bash
   git clone https://github.com/YovelBit/SetGame.git
   cd SetGame/SetGame
   ```

2. **Run the game**
   ```bash
   mvn clean compile
   mvn exec:java
   ```

3. **Customize settings**
   - Edit the `config.properties` file to configure:
     - Number of players
     - Turn timeout
     - Logging preferences

---

## 🧪 How to Run Tests

> Tests are written using **JUnit 5** and **Mockito**

```bash
mvn test
```

---

> *(Optional – add later if you want)*  
Example log output:

```
[Dealer] Dealt cards to the board.
[Player 1] Claimed slot 3
[Dealer] Accepted set from Player 1
```

---

## 📚 What I Learned

- Real-world concurrency debugging
- Designing multi-threaded systems
- Synchronization with shared memory
- Maven project structure and build automation

---

## 🤝 Acknowledgments

This project was developed as part of the **System Programming Lab** at Ben-Gurion University.

---

## 📬 Contact

**Yovel Biton**  
📧 yovelbiton123@gmail.com  
🔗 [GitHub](https://github.com/YovelBit) | [LinkedIn](https://linkedin.com/in/yovelbiton)