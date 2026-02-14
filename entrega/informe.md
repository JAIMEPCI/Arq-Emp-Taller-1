# 📄 Informe – Modelado BPMN del Proceso de Generación del FUEC

## 🏢 Descripción del proceso seleccionado

El proceso seleccionado por el grupo corresponde a la generación del Formato Único de Extracto del Contrato (FUEC) en la empresa TRANS CAPITAL S.A.S. Este documento es obligatorio para la prestación del servicio de transporte especial, ya que certifica que el servicio es legal y cumple con la normativa de tránsito vigente. El FUEC contiene información relevante como los datos del conductor, del vehículo, del cliente y del servicio prestado, y es requerido por las autoridades como soporte durante controles operativos.


## 🔄 Modelado del proceso utilizando BPMN

El modelado BPMN permitió representar de forma clara el flujo de generación del FUEC, identificando las actividades y decisiones involucradas en el proceso.

### Actor del proceso

Tras analizar el proceso, se determinó que existe **un único actor principal**:

* **Personal administrativo**: responsable de diligenciar la información, verificar los datos, imprimir, escanear y enviar el documento.

Otros elementos fueron descartados como actores:

* **Conductor**: no participa en la generación del documento, solo lo recibe al final del proceso.
* **Excel**: es únicamente una herramienta de apoyo, no ejecuta acciones ni toma decisiones.

### Flujo general del proceso

El proceso sigue la siguiente secuencia:

**1. Solicitud o necesidad del FUEC:** Se identifica la necesidad de generar el documento para un servicio específico.

**2. Diligenciamiento en Excel:** El personal administrativo completa manualmente una plantilla en Excel con los datos del conductor, vehículo, cliente y servicio.

**3. Impresión en formato oficial:** El archivo se imprime en el formato físico preestablecido de la empresa.

**4. Verificación de la información:** Se revisa el documento para detectar errores de digitación o inconsistencias.

**5. Escaneo del documento:** El formato impreso es digitalizado.

**6. Envío al conductor:** El archivo final es enviado al conductor como soporte legal del servicio.

## ⚖️ Diferencias con el caso base (Clínica Salud Viva)

Aunque ambos procesos fueron modelados utilizando BPMN, presentan diferencias importantes:

**1. Nivel de automatización:**
El proceso de la clínica es automatizado y gestionado completamente por un sistema. En cambio, el proceso del FUEC es manual y depende de la intervención del personal administrativo.

**2. Actores involucrados:**
En la clínica, el actor principal es el paciente que interactúa con el sistema. En el proceso del FUEC, el único actor activo es el personal administrativo.

**3. Manejo de la información:**
La clínica gestiona la información de forma totalmente digital. Por el contrario, el proceso del FUEC combina Excel con documentos físicos, impresiones y escaneo.

**4. Eficiencia del proceso:**
El proceso automatizado de la clínica es más rápido y eficiente. El proceso del FUEC es más lento debido a las actividades manuales que requiere.

## ✅ Justificación del modelado

El modelado BPMN de este proceso es importante porque permite comprender de forma clara cómo se genera un documento crítico para la operación de la empresa. Además, facilita la identificación de actividades manuales que pueden representar riesgos, como errores en la digitación de información o pérdida de documentos.

El diagrama también permite identificar oportunidades de mejora, como la posible digitalización completa del proceso, la automatización de la generación del documento y la reducción del uso de papel. Estas mejoras podrían aumentar la eficiencia, reducir errores y optimizar el tiempo requerido para generar el FUEC.

Adicionalmente, el modelado proporciona una representación visual que facilita el análisis del proceso y su comprensión por parte de diferentes actores, lo que es fundamental para la mejora continua y la optimización de los procesos organizacionales.