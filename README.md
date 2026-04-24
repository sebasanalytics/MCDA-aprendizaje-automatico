# SI7009 – Aprendizaje Automático - 2025 2

Repositorio del curso de **Maestría en Ciencias de los Datos y Analítica (EAFIT)**. Aquí encontrarás el material de apoyo, notebooks, guías de laboratorio y ejemplos computacionales para trabajar los temas del curso:

- Fundamentos del Aprendizaje Automático
- Aprendizaje Supervisado (regresión, clasificación, ensamble, regularización, tuning de hiperparámetros)
- Aprendizaje No Supervisado (clustering, reducción de dimensionalidad)
- Casos de uso y aplicaciones prácticas

---

## 📂 Estructura del Repositorio

```
├── notebooks/        # Jupyter notebooks por unidad temática
├── data/             # Datasets de práctica
├── labs/             # Talleres y guías de laboratorio
└── README.md         # Este archivo
```

---

## ⚙️ Requisitos

- Python 3.10+
- [uv](https://github.com/astral-sh/uv) – gestor de entornos y dependencias
- Git

---

## 🚀 Instalación del Entorno con uv

1. Clona este repositorio:
   ```bash
   git clone https://github.com/<org>/<repo>.git
   cd <repo>
   ```

2. Crea un entorno con `uv`:
   ```bash
   curl -LsSf https://astral.sh/uv/install.sh | sh # en Linux / MacOS
   powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex" # en Windows (PowerShell)
   uv venv --python 3.10
   ```

3. Activa el entorno virtual:
   ```bash
   source .venv/bin/activate   # Linux / Mac
   .venv\Scripts\activate      # Windows
   ```

4. Instala dependencias:
   ```bash
   uv pip install -r requirements.txt
   ```

5. Instala paquetes adicionales:
   ```bash
   uv pip install nombre_del_paquete
   ```

---

## 📘 Dependencias principales

- numpy, pandas, scikit-learn
- matplotlib, seaborn
- jupyter, notebook
- umap-learn, xgboost

---

## 📚 Bibliografía

- Bishop, C. (2006). *Pattern Recognition and Machine Learning*. Springer.
- Murphy, K. (2012). *Machine Learning: A Probabilistic Perspective*. MIT Press.
- Géron, A. (2022). *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow*. O’Reilly.
- James, G. et al. (2023). *An Introduction to Statistical Learning with Python*. Springer.