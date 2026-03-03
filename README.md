# ☕➡️🌐 Java Projects

An experimental repository for translating Java code blocks into JavaScript.  
Focused on understanding language paradigms, type systems, and runtime differences between the two languages.

---

## 📌 Description

**Java Projects** is a study-oriented repository that explores the similarities and differences between Java and JavaScript by directly translating code patterns from one language to the other. The repo also contains standalone Java programs, mini-games, and a library management system — all written as learning exercises.

---

## 🧠 Focus Areas

- 🔤 **Type Systems** — static typing (Java) vs dynamic typing (JavaScript)
- 🏗️ **OOP Paradigms** — classes, inheritance vs prototypes
- ⚙️ **Runtime Differences** — JVM vs V8 engine behavior
- 🔁 **Control Flow** — loops, conditionals, switch/case, nested structures
- 🧮 **Practical Exercises** — billing, averages, age calculator, Q&A
- 🎮 **Mini Games** — dice, coin flip, zodiac, Chinese game, quiz

---

## 🛠 Technologies Used

| Language   | Role                         |
|------------|------------------------------|
| Java       | Source language / reference  |
| JavaScript | Target translation language  |

---

## 📁 Project Structure
```
Java-Projects/
│
├── SistemaBiblioteca/          # Library management system (Java)
│   └── Main.java
│
├── juegos/                     # 3 mini games (Java)
│
├── — Translated Exercises (Java → JS) —
│
├── BillElectricity.js          # Electricity bill calculator
├── EasyPreguntasRespuestas.js  # Easy Q&A exercise
├── Edad.js                     # Age calculator
├── Idioma.js                   # Language selector exercise
├── Imagenazar.js               # Image/name exercise
│
├── — Conditional Exercises —
├── Ej1cond.js / Ej2cond.js     # Conditionals exercises 1–2
├── Ex1SwitchCase.js            # Switch/case exercise 1
├── Ex2SwitchCase.js            # Switch/case exercise 2
│
├── — Loop Exercises —
├── Ej1para.js / Ej2para.js     # For-loop exercises 1–2
├── Ej1sec.js / Ej2sec.js       # Sequential exercises 1–4
├── Ej3sec.js / Ej4sec.js
│
├── — Nested & Extra Exercises —
├── Ej1anidado.js / Ej2anidados.js  # Nested loop exercises
├── Ej1extra.js / Ej2extra.js       # Extra exercises
├── Ej3extra.js
├── Ej2.js / Ej4select.js / ej5.js  # Misc exercises
│
├── — Java-only Files —
├── Promedios.java              # Averages calculator
├── Sueldorepite.java           # Salary repetition exercise
├── Juegodados.java             # Dice game
├── Juegomoneda.java            # Coin flip game
├── juegopreguntasrespuestas.java  # Quiz game
├── juegozodiac.java            # Zodiac game
├── ej3juegochino.java          # Chinese game exercise
├── ej1.java / ej2pers.java     # Basic Java exercises
│
└── README.md
```

---

## 💡 Translation Examples

### Variables & Types
```java
// Java — statically typed
int number = 42;
String name = "Library";
boolean isActive = true;
```
```javascript
// JavaScript — dynamically typed
let number = 42;
let name = "Library";
let isActive = true;
```

---

### Control Flow — Switch/Case
```java
// Java
switch (day) {
    case 1: System.out.println("Monday"); break;
    case 2: System.out.println("Tuesday"); break;
    default: System.out.println("Other");
}
```
```javascript
// JavaScript
switch (day) {
    case 1: console.log("Monday"); break;
    case 2: console.log("Tuesday"); break;
    default: console.log("Other");
}
```

---

### Loops
```java
// Java
for (int i = 0; i < 5; i++) {
    System.out.println(i);
}
```
```javascript
// JavaScript
for (let i = 0; i < 5; i++) {
    console.log(i);
}
```

---

## 🔍 Key Differences at a Glance

| Concept            | Java                          | JavaScript                        |
|--------------------|-------------------------------|-----------------------------------|
| Typing             | Static, strongly typed        | Dynamic, weakly typed             |
| Runtime            | JVM                           | Browser / Node.js (V8)            |
| OOP model          | Class-based                   | Prototype-based (ES6 classes)     |
| Null safety        | NullPointerException risk     | `null` and `undefined`            |
| Compilation        | Compiled to bytecode          | Interpreted / JIT compiled        |
| Concurrency        | Threads                       | Event loop, async/await           |
| Method overloading | Supported natively            | Not supported — use defaults      |

---

## 🎮 Mini Games (Java)

| File                          | Description                        |
|-------------------------------|------------------------------------|
| `Juegodados.java`             | Dice rolling game                  |
| `Juegomoneda.java`            | Coin flip game                     |
| `juegozodiac.java`            | Zodiac sign game                   |
| `ej3juegochino.java`          | Chinese finger game                |
| `juegopreguntasrespuestas.java` | Quiz / Q&A game                  |

---

## 🏛️ SistemaBiblioteca

A standalone Java project implementing a basic **library management system**.  
Located in the `SistemaBiblioteca/` folder with `Main.java` as the entry point.

**Likely features:**
- Add, search, and remove books
- Manage loans and returns
- Basic console-driven interface

---

## 📈 Goals

This repository is useful for:

- Developers transitioning from Java to JavaScript
- Understanding how control flow and OOP map across languages
- Studying type system design and runtime behavior
- Learning through practical exercises and mini-games

---
## 📄 License

Open source — free to use, fork, and adapt for personal or educational projects.
