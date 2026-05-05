# 🧮 Student Grading Program

This is a simple Python program that classifies a student's mark into a grade category using conditional statements.

---

## 📌 Features

* Uses `if-elif-else` conditions
* Categorizes marks into grades
* Easy to understand for beginners

---

## 🛠️ Requirements

* Python 3 installed

---

## 📂 Code

```python
student_mark = 80

if 75 <= student_mark <= 100:
    print("distinction")
elif 60 <= student_mark <= 75:
    print("pass")
elif 50 <= student_mark <= 60:
    print("credit")
elif 35 <= student_mark <= 50:
    print("almost")
elif 20 <= student_mark <= 35:
    print("fail")
elif 0 <= student_mark <= 20:
    print("ungraded")
else:
    print("enter the right mark")
```

---

## 🚀 How to Run

1. Save the code in a file called `grading.py`
2. Open terminal or command prompt
3. Run the program:

```bash
python grading.py
```

---

## 📊 Grading System

* 75 – 100 → Distinction
* 60 – 75 → Pass
* 50 – 60 → Credit
* 35 – 50 → Almost
* 20 – 35 → Fail
* 0 – 20 → Ungraded

---

## ⚠️ Note

Some mark ranges overlap (e.g., 75, 60, 50). Python will use the first matching condition.

---

## ✨ Future Improvements

* Take user input
* Fix overlapping ranges
* Add comments for each grade
* Convert into a function
