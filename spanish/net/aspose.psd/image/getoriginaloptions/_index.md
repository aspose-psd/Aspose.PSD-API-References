---
title: "Image.GetOriginalOptions"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método Image. Obtiene las opciones basadas en la configuración del archivo original. Esto puede ser útil para mantener la profundidad de bits y otros parámetros de la imagen original sin cambios. Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el método Save, se producirá una imagen PNG de salida con 8 bits por píxel. Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas al método Save como segundo parámetro."
type: docs
weight: 190
url: /es/net/aspose.psd/image/getoriginaloptions/
---
{{< psd/tize >}}
## Image.GetOriginalOptions method

Obtiene las opciones basadas en la configuración del archivo original. Esto puede ser útil para mantener la profundidad de bits y otros parámetros de la imagen original sin cambios. Por ejemplo, si cargamos una imagen PNG en blanco y negro con 1 bit por píxel y luego la guardamos usando el método [`Save`](../../datastreamsupporter/save/), se producirá una imagen PNG de salida con 8 bits por píxel. Para evitarlo y guardar la imagen PNG con 1 bit por píxel, use este método para obtener las opciones de guardado correspondientes y páselas al método [`Save`](../save/) como segundo parámetro.

```csharp
public virtual ImageOptionsBase GetOriginalOptions()
```

### Valor devuelto

Las opciones basadas en la configuración del archivo original.

### Ver también

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


