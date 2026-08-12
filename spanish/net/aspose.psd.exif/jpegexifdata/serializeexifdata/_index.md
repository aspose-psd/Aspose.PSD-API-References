---
title: "JpegExifData.SerializeExifData"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método JpegExifData. Serializa los datos EXIF. Escribe los valores y contenidos de las etiquetas. La etiqueta de tamaño más influyente es el contenido de la etiqueta Miniatura"
type: docs
weight: 270
url: /es/net/aspose.psd.exif/jpegexifdata/serializeexifdata/
---
{{< psd/tize >}}
## JpegExifData.SerializeExifData method

Serializa los datos EXIF. Escribe los valores y contenidos de las etiquetas. La etiqueta de tamaño que más influye es el contenido de la etiqueta Miniatura.

```csharp
public byte[] SerializeExifData()
```

### Valor devuelto

Los datos EXIF serializados.

## Observaciones

El tamaño total del segmento debe ser menor o igual a MaxExifSegmentSize bytes para producir una imagen jpeg correcta. Sugerencia: intente reducir el tamaño de la miniatura o cambiar su compresión en caso de que tenga una sección EXIF demasiado grande.

### Ver también

* class [JpegExifData](../)
* namespace [Aspose.PSD.Exif](../../../aspose.psd.exif/)
* assembly [Aspose.PSD](../../../)


