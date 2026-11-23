# Advanced Machine Learning: Regularization, Ensembles & OOP Pipelines

[English](#english) | [Русский](#русский)

---

## English

An advanced **Machine Learning** project in **Python 3** using **scikit-learn**, progressing from model regularization and automated hyperparameter optimization to ensemble learning architectures and clean Object-Oriented ML pipelines.

### Tech Stack & Tools
* **ML & Ensembles:** `scikit-learn` (`LogisticRegression`, `DecisionTreeClassifier`, `RandomForestClassifier`, `GridSearchCV`, `VotingClassifier`, `BaggingClassifier`, `StackingClassifier`)
* **Data & Utilities:** `pandas`, `numpy`, `tqdm`
* **Environment:** Jupyter Notebook

### Project Structure (`src/`)

* **`ex00/regularization.ipynb`** — **Model Regularization:** Controlling overfitting in linear models via L1 (feature sparsity) and L2 weight penalties, and tuning structural complexity constraints (`max_depth`, `min_samples_split`, `min_samples_leaf`, `max_leaf_nodes`) in Decision Trees and Random Forests.
* **`ex01/gridsearch.ipynb`** — **Hyperparameter Optimization:** Automating parameter space exploration and cross-validated model selection using `GridSearchCV` with progress tracking (`tqdm`).
* **`ex02/metrics.ipynb`** — **Evaluation Metrics for Imbalanced & Multiclass Data:** Moving beyond accuracy to analyze confusion matrices, `Precision`, `Recall`, `F1-score`, `ROC` curves, and `AUC` across binary and multiclass classification settings.
* **`ex03/ensembles.ipynb`** — **Ensemble Learning Techniques:** Combining diverse base estimators to improve generalization using `VotingClassifier`, `BaggingClassifier`, and `StackingClassifier`.
* **`ex04/pipelines.ipynb`** — **OOP Refactoring & ML Pipelines:** Consolidating preprocessing, model selection, tuning, and evaluation steps into modular, reusable Object-Oriented Python classes and methods.

### Usage
* Place the required datasets inside `src/data/` and open any notebook in Jupyter Lab / Jupyter Notebook or VS Code: `jupyter notebook src/ex04/pipelines.ipynb`

---

## Русский

Продвинутый проект по **машинному обучению** на **Python 3** и библиотеке **scikit-learn**, охватывающий регуляризацию моделей, автоматический подбор гиперпараметров, построение ансамблей алгоритмов и рефакторинг ML-экспериментов в чистую объектно-ориентированную архитектуру.

### Стек и инструменты
* **ML и ансамбли:** `scikit-learn` (`LogisticRegression`, `DecisionTreeClassifier`, `RandomForestClassifier`, `GridSearchCV`, `VotingClassifier`, `BaggingClassifier`, `StackingClassifier`)
* **Данные и утилиты:** `pandas`, `numpy`, `tqdm`
* **Среда разработки:** Jupyter Notebook

### Структура проекта (`src/`)

* **`ex00/regularization.ipynb`** — **Регуляризация моделей:** Предотвращение переобучения в линейных моделях с помощью L1- и L2-штрафов, а также ограничение сложности деревьев решений и случайных лесов (`max_depth`, `min_samples_split`, `min_samples_leaf`, `max_leaf_nodes`).
* **`ex01/gridsearch.ipynb`** — **Подбор гиперпараметров:** Автоматизация поиска оптимальной комбинации параметров на кросс-валидации с помощью `GridSearchCV` и отслеживанием прогресса через `tqdm`.
* **`ex02/metrics.ipynb`** — **Метрики качества классификации:** Оценка моделей в условиях дисбаланса классов и мультиклассовой классификации с использованием матрицы ошибок, `Precision`, `Recall`, `F1-меры`, `ROC`-кривых и площади `AUC`.
* **`ex03/ensembles.ipynb`** — **Ансамблирование моделей:** Объединение различных базовых алгоритмов для повышения обобщающей способности с помощью `VotingClassifier`, `BaggingClassifier` и `StackingClassifier`.
* **`ex04/pipelines.ipynb`** — **ООП-пайплайны в анализе данных:** Структурирование этапов предобработки, обучения, валидации и оценки моделей в виде модульных классов и методов в парадигме объектно-ориентированного программирования.

### Запуск
* Поместите необходимые датасеты в директорию `src/data/` и откройте нужный ноутбук в Jupyter Notebook / Jupyter Lab или VS Code: `jupyter notebook src/ex04/pipelines.ipynb`
