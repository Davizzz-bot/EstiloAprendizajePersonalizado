# **Detector de Estilos de Aprendizaje**

Este proyecto es un sistema basado en **Django** que permite evaluar los estilos de aprendizaje (visual, auditivo, kinestésico) a través de un test interactivo. La aplicación ofrece una interfaz sencilla y funcional que valida las respuestas del usuario, procesa los datos y genera un análisis gráfico de los resultados.

---

## **Características**
- **Test de Estilo de Aprendizaje**: Evalúa las preferencias de aprendizaje del usuario mediante preguntas sencillas.
- **Validación de Respuestas**: Verifica que todas las preguntas estén contestadas antes de procesar los datos.
- **Generación de Gráficos**: Muestra resultados visuales utilizando la biblioteca **Chart.js**.
- **Interfaz Amigable**: Diseñada con HTML, CSS y JavaScript para una experiencia de usuario óptima.

---

## **Requisitos**
- Python 3.9 o superior
- Django 4.x
- Navegador web compatible (Google Chrome, Mozilla Firefox, etc.)
- Librerías adicionales:
  - **Chart.js**: Para la generación de gráficos interactivos.

---

## **Instalación**
Sigue estos pasos para instalar y ejecutar el proyecto en tu entorno local:

### 1. Clonar el repositorio:
```bash
git clone https://github.com/Davizzz-bot/EstiloAprendizajePersonalizado.git
cd detector-estilos-aprendizaje
```

### 2. Crear un entorno virtual:
```bash
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
```

### 3. Instalar dependencias:
```bash
pip install -r requirements.txt
```

### 4. Aplicar migraciones:
```bash
python manage.py migrate
```

### 5. Ejecutar el servidor:
```bash
python manage.py runserver
```

### 6. Acceder a la aplicación:
Despues de correr el servidor copia la ruta similar a `http://127.0.0.1:8000`, abre tu navegador y pega la ruta.

---

## **Estructura del Proyecto**

```plaintext
detector-estilos-aprendizaje/
├── detector/
│   ├── migrations/
│   ├── static/
│   │   ├── css/
|   |   |   ├── index.css
|   |   |   ├── login.css
|   |   |   ├── sudent.css
|   |   |   ├── teacher.css
│   │   │   └── test.css
│   │   ├── images/
│   │   |   └── fondo.jpg
│   │   └── js/
|   |       ├── student.js
|   |       ├── teacher.js
│   │       └── test.js
│   ├── templates/
│   │   ├── detector/
│   │   │   ├── index.html
│   │   │   ├── login.html
│   │   │   ├── student.html
│   │   │   ├── teacher.html
│   │   │   └── test.html
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── manage.py
├── requirements.txt
└── README.md
```

---

## **Uso**

### Página Principal
- Navega a la página principal (`/`) para acceder a la interfaz inicial.
- Desde allí, puedes iniciar secion y hacer click para realiar el test.

### Test de Aprendizaje
- Completa el test respondiendo todas las preguntas.
- Al enviar el formulario, se generará un análisis gráfico de tus preferencias de aprendizaje.

---

## **Tecnologías Utilizadas**
- **Backend**: Django
- **Frontend**: HTML, CSS, JavaScript
- **Gráficos**: Chart.js
- **Control de Versiones**: Git y GitHub

---

## **Contribuciones**
Si deseas contribuir al proyecto:
1. Haz un fork del repositorio.
2. Crea una rama para tus cambios:
   ```bash
   git checkout -b feature/nueva-funcionalidad
   ```
3. Realiza un pull request.


---

## **Autores**
- Moisés David González Bermúdez
- Carlos Andrés Jiménez Sarmiento

