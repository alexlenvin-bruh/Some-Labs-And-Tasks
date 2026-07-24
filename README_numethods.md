# 📐 Численные методы и ML — учебные проекты

Набор Jupyter-ноутбуков с лабораторными и учебными задачами по вычислительной математике, статистическому моделированию и машинному обучению.

> Всё написано руками, разобрано и (в основном) понято.

---

## 📂 Структура репозитория

| Файл | Тема | Кратко |
|---|---|---|
| `interpolation.ipynb` | Интерполяционные многочлены | Многочлены Лагранжа и Ньютона, разделённые и конечные разности, таблицы |
| `splines.ipynb` | Кубические сплайны | Построение кубического интерполяционного сплайна для cos(x²), сравнение точности при n = 5 и n = 25, графики |
| `random-generators.ipynb` | Генераторы ПСЧ и статтесты | Генератор на основе метода середин квадратов; тесты хи-квадрат, Колмогорова–Смирнова, покер-тест, тест дней рождения |
| `normal-distribution.ipynb` | Нормальное распределение | Генерация нормально распределённых величин |
| `pca-knn.ipynb` | PCA + k-NN | Снижение размерности методом главных компонент и классификация k ближайших соседей на датасете Iris |
| `wavelets/` | Вейвлет-анализ | Лабораторные по вейвлетам (отдельная папка) |

---

## 🛠 Стек

- **Python 3**
- **NumPy**, **SciPy** — вычисления и линейная алгебра
- **SymPy** — символьные вычисления (интерполяция, сплайны)
- **Matplotlib** — визуализация
- **scikit-learn** — PCA, k-NN
- **Jupyter Notebook** — среда

---

## 🚀 Как запустить

```bash
git clone https://github.com/alexlenvin-bruh/Some-Labs-And-Tasks.git
cd <название-репо>
pip install numpy scipy sympy matplotlib scikit-learn jupyter
jupyter notebook
```

---

## 📌 Примечание

Это учебные работы, а не продакшн-код. Где-то могут быть костыли, где-то — избыточные комментарии (я так разбиралась с темой и писала отчёты). Цель написания всего этого – разобраться с представленными темами.


# 📐 Numerical Methods & ML — Study Projects

A collection of Jupyter notebooks with lab work and study tasks on computational mathematics, statistical modelling, and machine learning.

> Written by hand, worked through, and (mostly) understood.

> ⚠️ Note: all notebooks are currently written in Russian.

---

## 📂 Repository Structure

| File | Topic | Summary |
|---|---|---|
| `interpolation.ipynb` | Interpolation polynomials | Lagrange and Newton polynomials, divided and finite differences, lookup tables |
| `splines.ipynb` | Cubic splines | Cubic interpolation spline for cos(x²), accuracy comparison at n = 5 and n = 25, plots |
| `random-generators.ipynb` | PRNGs & statistical tests | Middle-squares PRNG; chi-squared, Kolmogorov–Smirnov, poker test, birthday spacing test |
| `normal-distribution.ipynb` | Normal distribution | Generating normally distributed random variables |
| `pca-knn.ipynb` | PCA + k-NN | Dimensionality reduction via PCA and k-nearest neighbours classification on the Iris dataset |
| `wavelets/` | Wavelet analysis | Lab work on wavelets (separate folder) |

---

## 🛠 Stack

- **Python 3**
- **NumPy**, **SciPy** — computations and linear algebra
- **SymPy** — symbolic math (interpolation, splines)
- **Matplotlib** — visualisation
- **scikit-learn** — PCA, k-NN
- **Jupyter Notebook** — environment

---

## 🚀 How to Run

```bash
git clone https://github.com/alexlenvin-bruh/Some-Labs-And-Tasks.git
cd <repo-name>
pip install numpy scipy sympy matplotlib scikit-learn jupyter
jupyter notebook
```

---

## 📌 Note

These are study projects, not production code. Some parts may be a bit hacky, others over-commented — that's how I was figuring things out and writing reports along the way. The goal was to actually understand the topics, not just get things running.
