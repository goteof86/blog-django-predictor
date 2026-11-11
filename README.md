# Blog Django con predictor de Machine Learning

Aplicación web hecha con Django: blog con usuarios y un modelo de
Machine Learning integrado que se puede probar desde el navegador.

🔗 **Demo en vivo:** https://goteof86.pythonanywhere.com

## Qué hace
- Registro e inicio de sesión de usuarios
- Crear, editar y eliminar artículos (solo su autor)
- Formulario de contacto
- Modo oscuro / claro
- Predictor de clientes con ML: *(describe aquí qué predice)*

## Tecnologías
Python · Django · scikit-learn · joblib · SQLite · HTML/CSS/JS

## Estructura
- `core/`: configuración del proyecto
- `hola/`: app principal (modelos, vistas, plantillas, ML)
- `redes_neuronales/`: ejercicios con TensorFlow (regresión Celsius→Fahrenheit y XOR)

## Cómo ejecutarlo
    git clone https://github.com/goteof86/blog-django-predictor.git
    cd blog-django-predictor
    pip install -r requirements.txt
    echo SECRET_KEY=tu-clave-aqui > .env
    python manage.py migrate
    python manage.py runserver

## Autor
Leo · goteof86@gmail.com
