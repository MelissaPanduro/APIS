# API de Traductor - Azure Cognitive Services
Esta API permite traducir texto entre varios idiomas utilizando el servicio Azure Translator, parte de los Azure Cognitive Services. 
Azure Translator es un servicio basado en la nube que proporciona traducción automática en tiempo real para múltiples idiomas.

Configuración

1. Primero debemos regístrarnos en [Azure Portal](https://portal.azure.com/?authuser=0#home).
2. Seleccionamos Crear un recurso 
3. Nos dirigimos en IA y Machine Learning
4. Selecciona Cognitive Services y luego Translator
5. Proporcionarmos los detalles necesarios
   (Nombre del recurso, Suscripción, Grupo de recursos, etc.).
   En este caso utilice lo siguiente:
   
   <img src="https://github.com/user-attachments/assets/77783e46-5730-4cd0-b323-8dca4cc90a04" alt="Descripción de la imagen" width="400"/>

6. Una vez creado, ve al recurso para obtener la clave API y el endpoint.
Resultados de Pruebas

    <img src="https://github.com/user-attachments/assets/4626fe33-6928-4064-8933-159b8f956393" alt="Descripción de la imagen" width="700"/>

Aqui muestra la solicitud y su respuesta

   - Solicitud: Contiene un campo text con el valor "Como estas ".
   - detectedLanguage: Indica que el idioma detectado es es (español) con una confianza del 95% (score: "0.95").
   - translations: Proporciona la traducción al inglés con el texto "How are you ".

     <img src="https://github.com/user-attachments/assets/a8766343-52be-4c8a-bbed-2f70d305d7ca" width="600"/>

Esta API permite una integración sencilla con otros sistemas para traducir textos de forma automática utilizando Azure Translator.
Es altamente escalable y puede manejar múltiples solicitudes simultáneamente, lo que la convierte en una solución ideal para aplicaciones multilingües.

Referencias
 - [Documentación del traductor de Azure](https://learn.microsoft.com/en-us/azure/ai-services/translator/)
 - [Referencia de la API del traductor de Azure (v3.0)](https://learn.microsoft.com/en-us/azure/ai-services/translator/reference/v3-0-translate?tabs=curl)











   




