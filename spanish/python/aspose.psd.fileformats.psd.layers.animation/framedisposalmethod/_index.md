---
title: "Enumeración FrameDisposalMethod"
type: docs
weight: 50
url: /es/python-net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---

El método de eliminación de fotogramas especifica si se debe descartar el fotograma actual antes de mostrar el siguiente fotograma.<br/>            Selecciona un método de eliminación para animaciones que incluyen transparencia de fondo para especificar si el fotograma actual<br/>            será visible a través de las áreas transparentes del siguiente fotograma.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.FrameDisposalMethod

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Member name** | **Descripción** |
| :- | :- |
| AUTOMÁTICO | Determina un método de eliminación para el fotograma actual automáticamente, descartando el fotograma actual si el siguiente fotograma contiene transparencia de capa.<br/>            Para la mayoría de las animaciones, la opción Automático (predeterminada) produce los resultados deseados. |
| ELIMINAR | Descarta el fotograma actual de la pantalla antes de que se muestre el siguiente fotograma.<br/>            Sólo se muestra un fotograma a la vez (y el fotograma actual no aparece a través de las áreas transparentes del siguiente fotograma). |
| NO_ELIMINAR | Preserva el fotograma actual mientras se agrega el siguiente fotograma a la pantalla.<br/>            El fotograma actual (y los fotogramas anteriores) pueden mostrarse a través de áreas transparentes del siguiente fotograma. |
