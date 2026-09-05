# 👥 People You May Know

A simple Python project that suggests people you may know based on mutual connections.

## 📌 Project Description

This project demonstrates a basic **People You May Know** recommendation system using Python.

It checks the connections between people and suggests users who have common friends.

## ⚙️ How It Works

1. Store people and their connections.
2. Select a person.
3. Find their friends.
4. Check friends-of-friends.
5. Count mutual connections.
6. Suggest people who are not already directly connected.

## 🐍 Technologies Used

* Python
* Lists
* Dictionaries
* Sets
* Loops
* Functions

## ▶️ Example

```text
Person: 1
Person: 2
Both Have Comman Friends: Person 3

Suggestions:
For Person 1 ---> Person 2 is suggested
For Person 2 ---> Person 1 is suggested
```
## ▶️ Example With Diagram
                 👤 Alice
                /        \
               /          \
          👤 Bob          👤 Charlie
               \          /
                \        /
                 👤 David
```
Alice's friends:
    ↓
Bob + Charlie
    ↓
Bob and Charlie both know David
    ↓
David is NOT Alice's friend
    ↓
David becomes a suggestion
```
The suggestions are based on connections shared with Mutual friends.

## 🚀 How to Run

Clone the repository and run:

```bash
python main.py
```

## 🎯 Learning Purpose

This project is created to practice:

* Python data structures
* Functions
* Sets and dictionaries
* Basic recommendation logic
* Problem-solving with Python

## 📂 Project Structure

```text
people-you-may-know/
│
├── main.py
└── data.json
└── README.md
```

## 🔮 Future Improvements

* Add a graphical interface
* Store users in a database
* Add user profiles
* Improve recommendation ranking
* Build a web version using Flask

```
