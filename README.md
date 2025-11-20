# 🧪 KATA TDD con Pytest

Este repositorio contiene una **kata de programación usando Test-Driven
Development (TDD)** con **pytest**.\
El objetivo es practicar el flujo de trabajo TDD: **rojo → verde →
refactor**, escribiendo primero las pruebas y luego el código mínimo
necesario para hacerlas pasar.

## 📁 Estructura del proyecto

    pytest-kata-dam/
    │
    ├── src/               # Código fuente de la solución
    ├── test/              # Pruebas unitarias escritas con pytest
    │
    ├── .gitignore
    ├── pytest.ini         # Configuración para pytest
    ├── requirements.txt   # Dependencias del proyecto
    └── README.md          # Este archivo

## 🚀 Requisitos

-   Python 3.10 o superior\
-   pip\
-   virtualenv (opcional pero recomendado)

## ⚙️ Instalación y configuración del entorno

### 1. Clonar el repositorio

``` bash
git clone https://github.com/jrgeepd/pytest-kata-dam.git
cd pytest-kata-dam
```

### 2. Crear un entorno virtual

``` bash
python3 -m venv venv
```

### 3. Activar el entorno virtual

**Linux / macOS:**

``` bash
source venv/bin/activate
```

**Windows (PowerShell):**

``` bash
venv\Scripts\activate
```

### 4. Instalar dependencias

``` bash
pip install -r requirements.txt
```

## 🧪 Ejecutar las pruebas

``` bash
pytest
```

Ejecutar un archivo de pruebas:

``` bash
pytest test/test_nombre.py
```

Modo detallado:

``` bash
pytest -v
```

## 🎯 Objetivo de la kata

-   Practicar **TDD con pytest**.\
-   Escribir pruebas claras, pequeñas y específicas.\
-   Implementar soluciones simples que cumplan los tests.\
-   Refactorizar manteniendo la funcionalidad.

La lógica de la kata se encuentra dentro de la carpeta `test/`.\
Tu misión: **hacer pasar todas las pruebas implementando código en
`src/`**.

## 🛠️ Consejos

-   Escribe solo el código necesario para que el test actual pase.\
-   Refactoriza después de tener todos los tests en verde.\
-   Mantén funciones pequeñas y fáciles de leer.

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas!

## 📄 Licencia

Proyecto bajo licencia MIT.
