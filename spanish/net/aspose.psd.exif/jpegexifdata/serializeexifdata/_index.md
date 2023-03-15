---
title: JpegExifData.SerializeExifData
second_title: Referencia de API de Aspose.PSD para .NET
description: JpegExifData método. Serializa los datos EXIF. Escribe los valores y contenidos de las etiquetas. La etiqueta de tamaño que más influye es el contenido de la etiqueta de miniatura.
type: docs
weight: 270
url: /es/net/aspose.psd.exif/jpegexifdata/serializeexifdata/
---
## JpegExifData.SerializeExifData method

Serializa los datos EXIF. Escribe los valores y contenidos de las etiquetas. La etiqueta de tamaño que más influye es el contenido de la etiqueta de miniatura.

```csharp
public byte[] SerializeExifData()
```

### Valor_devuelto

Los datos EXIF serializados.

### Observaciones

El tamaño total del segmento debe ser menor o igual a los bytes MaxExifSegmentSize para producir la imagen jpeg correcta. Sugerencia: intente reducir el tamaño de la miniatura o cambie su compresión en caso de que tenga un tamaño de sección EXIF demasiado grande.

### Ver también

* class [JpegExifData](../)
* espacio de nombres [Aspose.PSD.Exif](../../jpegexifdata/)
* asamblea [Aspose.PSD](../../../)


