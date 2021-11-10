# Apache Kafka

## ¿Qué es Apache Kafka?

Es una plataforma distribuida de transmisión de datos. Permite publicar, almacenar y procesar flujos de datos en tiempo real.

Problema Planteado

Primer Imagen

* Desarrollar, mantener y evolucionar las integraciones es complicado y costoso.
* Debemos definir formatos de datos y protocolos de intercambio en cada conexión.
* Demanda de datos creciente en el futuro.

Solución con Kafka

Segunda imagen

En apache Kafka se pueden depositar mensajes de cualquier fuente de datos en forma de eventos.

Los consumidores también pueden ser cualquiera sistema, como bases de datos o herramientas analíticas.

Recomendaciones de Uso

Tercera imagen

**Lenguajes utilizados en su Desarrollado**
* Java
* Scala

**¿Por qué utilizarlos?**

* Es Open Source bajo licencia Software Foundation (Licencia Apache 2.0).
* Es escalable, persistente y tolerante a fallos.
* Tiene una baja latencia (menos de 10ms).
* Integración sencilla con tecnologías Big Data.

**¿Por qué aprenderlo?**

1. Permite construir flujos de datos en tiempo real entre aplicaciones.
2. Permite construit aplicaciones que reaccionan a eventos en tiempo real.

**Casos de Uso**

* Procesamiento en Streaming. (Kafka Streams)
* Gestión de Logs.
* Sistema de recomendaciones en Tiempo Real.
* Recolección de datos e interacciones.


## Modelo Editor-Subscriptor

* Sistema de eventos distribuidos.
* Sucscriptor tiene interés por eventos.
    * Filtro - Topic.
* Editor genera eventos.
* Paradigma asíncrono.
* Desacoplado en el espacio.

### Ejemplo

* **Push**. Subscriptor recibe evento.
* **Pull**. Subscriptos pregunta si hay eventos.
* **Híbrido**. Subscriptor recibe notificación pero debe solicitar el evento.

Mecanismos Pull e Híbridos:

* Requieren almacenar eventos.
* Permiten desacoplar sistemas.
* Permiten implementar aplicaciones asíncronas.

# kafka-fundamentals
