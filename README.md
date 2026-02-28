README BASICO LUEGO CAMBIARA. 

CONTADOR DE PALABRAS – Analizador de Texto en Python
📌 Descripción
Este proyecto es un analizador de texto interactivo en terminal que permite obtener estadísticas completas de un texto introducido manualmente o cargado desde un archivo .txt. El programa muestra información como:

Número de palabras
Número de caracteres (con y sin espacios)
Número de oraciones
Número de párrafos
Palabras más frecuentes
Palabras únicas y porcentaje
Longitud media de las palabras
Palabra más larga y más corta
Posibilidad de guardar un informe en un archivo

El desarrollo se realizó siguiendo un flujo de commits incrementales y utilizando asistencia de IA para generar y mejorar partes del código.

📁 Estructura del Proyecto
Código


Copiar
contador-palabras/
│
├── src/
│   └── contador.py
│
├── textos/
│   └── ejemplo.txt
│
├── docs/
│   └── asistencia_ia.md
│
├── README.md
├── requirements.txt
└── .gitignore

▶️ Cómo ejecutar el programa

1. Clonar el repositorio
git clone https://github.com/tuusuario/contador-palabras.git
cd contador-palabras

2. Crear entorno virtual (opcional pero recomendado)
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

3. Instalar dependencias Código
pip install -r requirements.txt

4. Ejecutar el programa
python src/contador.py

🧪 Ejemplo de uso
El programa muestra un menú como este:
CONTADOR DE PALABRAS DE UN TEXTO

1. Introducir texto manualmente
2. Cargar desde archivo .txt
3. Salir

📄 Funcionalidades principales
Captura de texto multilinea desde terminal
Lectura de archivos .txt
Conteo de palabras, caracteres, oraciones y párrafos
TOP 5 de palabras más frecuentes
Estadísticas avanzadas
Guardado de informe en archivo
Menú interactivo

🧠 Tecnologías utilizadas
Python 3
Módulos estándar: re, collections, os, datetime
Git para control de versiones
Asistencia de IA documentada en docs/asistencia_ia.md

📝 Autor
Proyecto desarrollado por Ángel como parte del módulo Estrategias de Generación de Código con IA.