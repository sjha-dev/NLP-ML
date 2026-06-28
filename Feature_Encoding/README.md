# 🏷️ Feature Encoding

Welcome to the **Feature Encoding** section of the **NLP-ML** repository.

Feature Encoding is the process of converting **categorical data** into a numerical format so that Machine Learning algorithms can understand and process it effectively.

Since most Machine Learning models cannot work directly with text or categorical values, feature encoding is an essential preprocessing step.

---

# 📚 Topics Covered

| S.No | Topic | Status |
|------|-------|--------|
| 01 | One Hot Encoding | ✅ Completed |
| 02 | Label Encoding | ⏳ Coming Soon |

---

# 📖 About the Topics

## 🔤 One Hot Encoding

One Hot Encoding converts each unique category into a separate binary column (0 or 1).

**Best suited for:** Nominal categorical data (where there is no natural order).

**Example**

| Color |
|-------|
| Red |
| Blue |
| Green |

⬇️

| Color_Red | Color_Blue | Color_Green |
|-----------|------------|-------------|
| 1 | 0 | 0 |
| 0 | 1 | 0 |
| 0 | 0 | 1 |

---

## 🏷️ Label Encoding

Label Encoding assigns a unique integer value to each category.

**Best suited for:** Ordinal categorical data (where categories have a meaningful order).

**Example**

| Size |
|------|
| Small |
| Medium |
| Large |

⬇️

| Size |
|------|
| 0 |
| 1 |
| 2 |

---

# 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

---

# 🎯 Goal

The goal of this section is to understand different feature encoding techniques, learn when to use each method, and implement them using Python.

---

# 👨‍💻 Author

**Sudhanshu Shekhar Jha**

Learning AI/ML, NLP, DSA & Full Stack Development 🚀