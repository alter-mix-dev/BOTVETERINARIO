* RETO 2. BOT DE CITAS PARA UNA CLINICA VETERINARIA CON MEMORIA DE CONVERSACION.
* **Infraestructura e Inferencia:** Configura Ollama, descarga Meta Llama 3.1 (8B) y despliega Llama Stack en Colab.
* **Gestión de Memoria:** Crea un historial conversacional indexado por número telefónico para mantener el contexto del cliente.
* **Reglas y Escalamiento:** Filtra palabras clave para desviar automáticamente la consulta hacia un agente humano.
* **API y Mensajería:** Configura un webhook con FastAPI para recibir y procesar de forma asíncrona los mensajes de WhatsApp.
* **Conectividad Externa:** Expone el servidor local a internet mediante un túnel de Pyngrok para enlazarse con Meta.
