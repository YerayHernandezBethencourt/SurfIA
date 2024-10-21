# 🌊 SurfIA: Clasificador de Trucos de Surf con IA 🏄‍♂️

¡Bienvenido a **SurfIA**! Este proyecto combina mi pasión por el surf con mis habilidades en inteligencia artificial para crear un modelo que clasifica trucos de surf a partir de vídeos. 🎥🏄‍♀️

## 🚀 Descripción del Proyecto

SurfIA utiliza redes neuronales profundas para identificar y clasificar diferentes trucos de surf. A través de la extracción de fotogramas de los vídeos, el modelo aprende a reconocer los movimientos y técnicas de los surfistas. Este proyecto está diseñado para ayudar a surfistas de todos los niveles a mejorar su técnica mediante la retroalimentación visual.

## 🎬 Demostración en Vídeo

A continuación se muestra un vídeo del funcionamiento del programa, donde se analiza el movimiento del surfista y se visualizan los resultados:

![Vídeo Original](https://github.com/user-attachments/assets/6f1566d4-fd05-44de-ad7a-0ce4faca224f)

![Demostración de SurfIA](https://github.com/user-attachments/assets/d5fac092-c5ae-4ffe-92ea-40ba1edbabf4)

<video width="640" height="480" controls loop>
    <source src="ruta_al_video.mp4" type="video/mp4">
    Tu navegador no soporta la reproducción de vídeos.
</video>

## ⚙️ Funcionalidades

- **Extracción de Fotogramas:** Convierte vídeos de surf en imágenes para su procesamiento.
- **Clasificación de Trucos:** Utiliza un modelo preentrenado de ResNet50 para identificar hasta 11 trucos diferentes.
- **Aumento de Datos:** Mejora la precisión del modelo mediante técnicas de aumento de datos.

## 📦 Requisitos

- Python 3.x
- TensorFlow
- OpenCV
- Keras
- NumPy
- Matplotlib

## 💻 Instalación

```bash
git clone https://github.com/tu-usuario/SurfIA.git
cd SurfIA
pip install -r requirements.txt

```
## 📊 Uso
Preparar los Vídeos: Asegúrate de tener tus vídeos de surf organizados en carpetas.
Ejecutar el Script: Usa el script de entrenamiento para comenzar el proceso de clasificación.
python
Copiar código
python train.py
Evaluar el Modelo: Después del entrenamiento, evalúa el modelo con tus propios vídeos.

## 🛠️ Contribuciones
¡Las contribuciones son bienvenidas! Si tienes ideas para mejorar SurfIA o encuentras un error, no dudes en abrir un issue o enviar un pull request.

## 📫 Contacto
Para más información, puedes contactarme en [LinkedIn](https://www.linkedin.com/in/yeray-hernandez-bethencourt/) o al [Mail](mailto:yera_hb@hotmail.es).

## 🌟 Agradecimientos
Gracias por visitar el proyecto SurfIA. ¡Espero que disfrutes explorándolo tanto como yo disfruto del surf!

