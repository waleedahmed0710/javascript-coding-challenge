# javascript-coding-challenge

Below is a sample **README.md** that you can include in your repository to explain the challenge requirements and submission process clearly. Feel free to adjust any details to match your team’s preferences or the specifics of your repo setup.

---

# Full-Stack Junior Developer Challenge

Welcome to our coding challenge! This exercise is designed for **full-stack junior developers** who have a solid grasp of **JavaScript** and front-end development in **React Native**. It consists of two parts—one **Node.js** challenge focusing on data structures, and one **React Native** challenge focusing on front-end UI.

We expect the entire challenge to take about **90 minutes** in total:
- **Node.js (Data Structures)**: ~30 minutes
- **React Native (UI)**: ~60 minutes

---

## Table of Contents
1. [General Instructions](#general-instructions)
2. [Part 1: Node.js Data Structures Challenge](#part-1-nodejs-data-structures-challenge)
3. [Part 2: React Native UI Challenge](#part-2-react-native-ui-challenge)
4. [Deliverables Checklist](#deliverables-checklist)
5. [Evaluation Criteria](#evaluation-criteria)
6. [Submission Steps](#submission-steps)
7. [Getting Started](#getting-started)
8. [Notes](#notes)

---

## General Instructions

1. **Timebox**: Please aim to complete both challenges within **90 minutes**.
2. **Focus**: Write clear, understandable code—prefer readability and correctness over complexity.
3. **Git Workflow**: We recommend small, frequent commits.
4. **Optional Tests**: You are encouraged to include basic tests if time allows (e.g., Jest for Node.js).

---

## Part 1: Node.js Data Structures Challenge

### Overview
Implement a function to process an array of data using a **custom data structure** (e.g., a heap or a balanced tree) and perform some filtering and sorting logic.

### Requirements
1. In the folder `node-challenge` (or a similar folder):
   - Create a file `index.js` that exports or logs the result of the function `processScores()`.
2. The function `processScores()` should:
   - Take an **array of objects**. Each object has an `id` (string or number) and a `score` (number).
   - **Ignore** any items where `score` is invalid (not a number) or is below 0.
   - **Sort** the remaining items by `score` in **descending** order.
   - Return or log the **top 5** items (based on `score`).
3. **Custom Data Structure**:
   - Internally, use a basic custom data structure (e.g., a min-heap, max-heap, or another structure) to handle sorting or to retrieve the top 5 elements efficiently.
4. **Input & Output**:
   - For simplicity, define an array of **sample data** in your code.
   - Print the final array to the console or return it from the function.
5. **Testing (Optional)**:
   - If time permits, add a test file (e.g., `__tests__/processScores.test.js`) using a testing framework like Jest.

---

## Part 2: React Native UI Challenge

### Overview
Build a minimal React Native screen to **display and filter** a list of items and show item details in a modal or alert.

### Requirements
1. In the folder `react-native-challenge` (or a similar folder):
   - Create a basic React Native (or Expo) project.
   - You only need one screen/component.
2. **Data**:
   - Hardcode an array of items (e.g., `[{ title: "...", description: "..." }, ...]`).
3. **Display**:
   - Render these items in a list (e.g., using `FlatList`).
   - Each item should show its `title` and `description`.
4. **Search/Filter**:
   - Implement a **TextInput** at the top of the screen.
   - As the user types, the list should **filter** to show only items whose `title` matches the search query (case-insensitive).
5. **Interaction**:
   - Tapping on an item should display the item’s `description` in an **Alert** or a **Modal** component.
6. **Running**:
   - Add any setup details (e.g., `npm install`, `npx expo start`) in a local `README.md` inside this folder.

---

## Deliverables Checklist

1. **Node.js**:
   - [ ] `processScores()` function implemented with a custom data structure (heap, BST, etc.).
   - [ ] `index.js` that logs or returns the final top 5 scores.
   - [ ] (Optional) Unit test file, e.g., `__tests__/processScores.test.js`.

2. **React Native**:
   - [ ] A minimal React Native project that displays and filters a list of items.
   - [ ] A simple alert or modal on item press to show `description`.
   - [ ] A short `README.md` describing how to run it.

3. **Git & PR**:
   - [ ] Frequent commits with descriptive commit messages.
   - [ ] A Pull Request (PR) against the main branch in this repository.

---

## Evaluation Criteria

1. **Correctness & Readability**  
   - Does your Node.js function produce the correct, sorted, top 5 results?
   - Does the React Native UI correctly display and filter items?
   - Is the code easy to follow?

2. **Data Structure Usage (Node.js)**  
   - Did you implement a basic custom data structure (heap, tree, etc.)?
   - Is it clear, concise, and correct?

3. **React Native Knowledge**  
   - Correct usage of components (`Text`, `TextInput`, `FlatList`, `Modal`/`Alert`).
   - Basic state management for filtering.

4. **Code Organization**  
   - Are your files logically structured?
   - Is naming consistent and meaningful?

5. **Optional Tests**  
   - If tests are included, do they effectively cover the core functionality?

6. **Overall Approach**  
   - Your ability to solve problems under time constraints.
   - Clarity, maintainability, and correctness over complexity.

---

## Submission Steps

1. **Fork** this repository to your own GitHub account.
2. **Create a new branch** (e.g., `feature/solution`).
3. **Implement** both challenges (Node.js and React Native).
4. **Commit** your code frequently as you develop.
5. **Open a Pull Request** to the main branch of this repository.
6. In your PR description, briefly outline:
   - Any **assumptions** or design decisions made.
   - How to run your Node.js and React Native projects.
   - Any known limitations or incomplete sections.

---

## Getting Started

1. **Clone your fork** locally:
   ```bash
   git clone https://github.com/<your-username>/full-stack-jr-challenge.git
   ```
2. **Install Dependencies**:
   - For Node.js: `cd node-challenge && npm install`
   - For React Native: `cd react-native-challenge && npm install`
3. **Run the Node.js Script**:
   ```bash
   cd node-challenge
   node index.js
   ```
4. **Start the React Native App**:
   ```bash
   cd react-native-challenge
   npx expo start
   ```
   - Or use the React Native CLI if not using Expo.

---

## Notes

- **Timebox**: We recommend you spend about **30 minutes** on the Node.js challenge and about **60 minutes** on the React Native portion.
- **Partial Solutions**: If you run out of time, feel free to describe how you would finish or improve your solution.
- **Feel Free to Ask Questions**: If anything is unclear, you can note your questions in the PR description.

**Good luck, and we look forward to reviewing your submission!**
