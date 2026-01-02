# Week 0: Python Fundamentals

## Overview

This week provides essential Python programming skills needed for the Web and Social Network Analytics course. It's designed for complete beginners and covers everything from basic syntax to data analysis and visualization.

**Note:** Week 0 is **optional but highly recommended** if you're not familiar with Python.

---

## Learning Objectives

By completing Week 0, you will be able to:

- ✓ Create and manipulate Python variables and data types
- ✓ Control program flow with conditionals and loops
- ✓ Work with data structures (lists, dictionaries, sets, tuples)
- ✓ Define and use functions
- ✓ Read and write files
- ✓ Analyze data with Pandas DataFrames
- ✓ Perform numerical operations with NumPy
- ✓ Create visualizations with Matplotlib
- ✓ Apply basic machine learning with scikit-learn

---

## Materials

| File | Description | Time |
|------|-------------|------|
| `Week0-notes-python-fundamentals.ipynb` | Main tutorial with examples | 2-3 hours |
| `Week0-Exercise.ipynb` | Practice exercises | 1-2 hours |
| `Week0-Exercise-Solutions.ipynb` | Solutions to exercises | Reference |
| `data/DM_1.csv`, `data/DM_2.csv` | Sample customer/activity data | - |
| `data/attrition.csv` | HR dataset for analysis (37 columns) | - |

---

## Topics Covered

### 1. Python Basics (45 mins)
- Variables and data types (strings, numbers)
- String manipulation (upper, lower, strip, split)
- Number operations (arithmetic, rounding, absolute)

### 2. Control Flow (30 mins)
- Conditional statements (if/elif/else)
- Comparison operators
- Loops (for, while)
- Indentation and code blocks

### 3. Data Structures (45 mins)
- **Lists**: creation, indexing, slicing, sorting, copying
- **Tuples**: immutable sequences
- **Sets**: unique elements, set operations
- **Dictionaries**: key-value pairs, looping

### 4. Functions & Comprehensions (30 mins)
- Defining functions with parameters and return values
- List comprehensions for efficient code
- Enumeration and iteration

### 5. File I/O (20 mins)
- Reading CSV files
- Writing to files
- Parsing structured data

### 6. NumPy (30 mins)
- Creating arrays and matrices
- Matrix operations (transpose, sum, indexing)
- Shape manipulation

### 7. Pandas (60 mins)
- Creating DataFrames
- Reading CSV files
- Accessing columns and rows
- Merging datasets (left, right, inner, outer joins)
- Data preprocessing

### 8. Scikit-learn (30 mins)
- Loading datasets
- Building simple models (linear regression)
- Making predictions

### 9. Matplotlib Visualization (45 mins)
- Pie charts and bar charts
- Histograms
- Boxplots
- Scatterplots and line plots
- Customization (colors, labels, titles)

---

## Getting Started

### 1. Setup Environment

```bash
# Install required packages
pip install numpy pandas scikit-learn matplotlib
```

### 2. Verify Installation

Open `Week0-notes-python-fundamentals.ipynb` and run the setup cell to verify all packages are installed correctly.

### 3. Work Through Tutorial

Follow the notes notebook sequentially. Each section builds on previous concepts.

### 4. Practice Exercises

Complete `Week0-Exercise.ipynb` to test your understanding. Try solving without looking at solutions first!

---

## Exercise Overview

| # | Topic | Difficulty | Concepts |
|---|-------|------------|----------|
| 1 | Compound Interest | Easy | Loops, arithmetic |
| 2 | Investment Calculator | Easy | While loops, conditions |
| 3 | Remove Duplicates | Easy | Sets, type conversion |
| 4 | String Indexing | Easy | Lists, string slicing |
| 5 | Temperature Conversion | Medium | List comprehensions |
| 6 | Functions & Loops | Medium | Functions, nested loops |
| 7 | Dictionary Lookups | Medium | Dictionaries, iteration |
| 8 | Most Common Letter | Medium | Dictionaries, max() |
| 9 | Decision Tree Classifier | **Advanced** | Pandas, scikit-learn, ML pipeline |

**Note:** Exercise 9 is an advanced challenge that integrates multiple concepts. It's okay to skip it and revisit later if needed.

---

## Common Pitfalls

Watch out for these common mistakes:

1. **Index starts at 0** - Lists and strings use 0-based indexing
2. **Indentation matters** - Python uses indentation to define code blocks
3. **Shallow vs deep copy** - Use `.copy()` to create independent copies of lists
4. **Type mismatches** - Can't directly concatenate strings and numbers
5. **Mutable default arguments** - Don't use lists as default function parameters
6. **Variable scope** - Variables inside functions are local

📚 See the "Common Pitfalls & Best Practices" section in the notes for detailed examples.

---

## Tips for Success

1. **Run code frequently** - Execute cells as you go to catch errors early
2. **Experiment** - Try modifying examples to see what happens
3. **Read error messages** - They usually tell you exactly what's wrong
4. **Use print()** - Print intermediate values to debug
5. **Don't copy-paste blindly** - Type out code to build muscle memory
6. **Google is your friend** - Search for error messages and documentation

---

## Next Steps

After completing Week 0, you'll be ready for:

- **Week 1**: Web scraping with BeautifulSoup and Selenium
- **Week 2**: LLM-based scraping and PageRank algorithms
- **Week 3**: Network analysis with NetworkX
- **Week 4**: Clustering and recommendation systems

---

## Additional Resources

### Official Documentation
- [Python 3 Documentation](https://docs.python.org/3/)
- [NumPy Documentation](https://numpy.org/doc/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Gallery](https://matplotlib.org/stable/gallery/)
- [Scikit-learn Tutorials](https://scikit-learn.org/stable/tutorial/)

### Interactive Learning
- [Python Official Tutorial](https://docs.python.org/3/tutorial/)
- [Pandas Getting Started](https://pandas.pydata.org/docs/getting_started/index.html)
- [NumPy Quickstart](https://numpy.org/doc/stable/user/quickstart.html)

### Cheat Sheets
- [Python Cheat Sheet](https://www.pythoncheatsheet.org/)
- [Pandas Cheat Sheet](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)
- [NumPy Cheat Sheet](https://numpy.org/doc/stable/user/absolute_beginners.html)

---

## Questions?

If you're stuck:
1. Check the "Common Pitfalls" section in the notes
2. Read the error message carefully
3. Review relevant sections in the tutorial
4. Look at the solutions notebook for guidance (but try first!)
5. Ask for help during lab sessions

---

**Estimated Total Time:** 3-4 hours

Good luck, and enjoy learning Python! 🐍
