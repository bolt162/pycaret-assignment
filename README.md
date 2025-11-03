# PyCaret Low-Code Data Mining Assignment

This repository contains a collection of Google Colab notebooks demonstrating various machine learning and data mining tasks using the **PyCaret** low-code machine learning library, fulfilling all requirements of the assignment.

---

## 🎯 Assignment Goals

The primary goal of this assignment is to demonstrate proficiency in using PyCaret's AutoML capabilities to solve six distinct data mining tasks. All code is original (rewritten) and executes successfully in the provided Colab notebooks, using dedicated datasets unique to this submission.

### Key Requirements

1.  **PyCaret Version:** All notebooks use `pycaret==2.3.5`.
2.  **Code Integrity:** All code has been rewritten (not copied from official PyCaret examples) to ensure originality.
3.  **Dataset Selection:** Each task uses a unique dataset sourced from Kaggle or other public repositories, distinct from those used in official PyCaret tutorials.
4.  **AutoML Utilization:** Full use of PyCaret's **AutoML** features, including the `compare_models()` and `tune_model()` functions, is demonstrated.
5.  **GPU Acceleration:** Where supported for Classification and Regression tasks, GPU acceleration is enabled using `setup(use_gpu=True)` to leverage Google Colab's GPU runtime.

---

## 📁 Project Structure and Contents

The repository is organized to clearly present each task and its corresponding Colab notebook.

| Task | PyCaret Module | Notebook Filename | Dataset Focus | Execution Notes |
| :--- | :--- | :--- | :--- | :--- |
| **Binary Classification** | `pycaret.classification` | `1_Binary_Classification.ipynb` | Predict two target classes. | GPU enabled (`use_gpu=True`). |
| **Multiclass Classification** | `pycaret.classification` | `2_Multiclass_Classification.ipynb` | Predict three or more target classes. | GPU enabled (`use_gpu=True`). |
| **Regression** | `pycaret.regression` | `3_Regression.ipynb` | Predict a continuous numerical value. | GPU enabled (`use_gpu=True`). |
| **Clustering** | `pycaret.clustering` | `4_Clustering.ipynb` | Unsupervised grouping of data points. | Successfully executed. |
| **Anomaly Detection** | `pycaret.anomaly` | `5_Anomaly_Detection.ipynb` | Identify rare items/events/observations. | Successfully executed. |
| **Time Series Forecasting** | `pycaret.time_series` | `7a_TS_Univariate.ipynb` | Forecasting a single variable without external data. | Successfully executed. |

---

## 📹 Deliverables Checklist

### A. Colab Execution and Code Integrity

* **All notebooks** are designed to be cloned and **executed successfully** in the target environment (Google Colab).
* The output cells in each notebook show successful execution, demonstrating the use of `setup()`, `compare_models()`, and model deployment functions.
* GPU usage is confirmed in the output of the `setup()` function where applicable.

### B. Video Tutorial

A long-form video tutorial has been provided, which serves as a detailed walkthrough for every Colab notebook in this repository.

* **Walkthrough Requirement:** The video walks through each of the **6 Colab notebooks** sequentially.
* **Explanation:** Each notebook's purpose, dataset, key PyCaret functions (`setup`, `compare_models`, `create_model`, `tune_model`), and final output are explained in approximately **one minute**.
* **Proof of Execution:** The video explicitly shows the code running in the student's Google Colab environment, confirming successful execution and results for all tasks.

**Video Link:**
https://drive.google.com/file/d/1TbgP-W6n31U8YXIPhgfICuaT7g9Bq6Pk/view?usp=drive_link
https://drive.google.com/file/d/1Nt-iubejLP0utEmYTD0QvHTdl0AedaNq/view?usp=drive_link
https://drive.google.com/file/d/1oLqUYGuiiM2QQ3mWdLg5IOzgvJtNFJ3a/view?usp=drive_link
https://drive.google.com/file/d/1OaoWqpaYIzrGovBk1gcvB75lv_wBsrvO/view?usp=drive_link
https://drive.google.com/file/d/1Sgc-fYVjib57R1JKjUVXRL_NO97I5PaT/view?usp=drive_link
https://drive.google.com/file/d/1Ih1p2bqqGgH_9GXjlPlwIZNsb7uaigcS/view?usp=drive_link
