---
title: Class TiffDataType
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.FileFormats.Tiff.TiffDataType clase. El tipo de datos tiff.
type: docs
weight: 4210
url: /es/net/aspose.psd.fileformats.tiff/tiffdatatype/
---
## TiffDataType class

El tipo de datos tiff.

```csharp
public abstract class TiffDataType : IComparable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlignedDataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/aligneddatasize/) { get; } | Obtiene el tamaño de datos adicional en bytes (en caso de que los 12 bytes no sean suficientes para los datos de la etiqueta). |
| abstract [Count](../../aspose.psd.fileformats.tiff/tiffdatatype/count/) { get; } | Obtiene el conteo de elementos. |
| abstract [DataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/datasize/) { get; } | Obtiene el tamaño de datos adicional en bytes (en caso de que los 12 bytes no sean suficientes para los datos de la etiqueta). |
| [Id](../../aspose.psd.fileformats.tiff/tiffdatatype/id/) { get; } | Obtiene la representación de números enteros de ID de etiqueta. |
| [IsValid](../../aspose.psd.fileformats.tiff/tiffdatatype/isvalid/) { get; } | Obtiene un valor que indica si los datos de la etiqueta son válidos. La etiqueta válida contiene datos que pueden conservarse. No se puede almacenar la etiqueta no válida. |
| [TagId](../../aspose.psd.fileformats.tiff/tiffdatatype/tagid/) { get; } | Obtiene la etiqueta id. |
| abstract [TagType](../../aspose.psd.fileformats.tiff/tiffdatatype/tagtype/) { get; } | Obtiene el tipo de etiqueta. |
| abstract [Value](../../aspose.psd.fileformats.tiff/tiffdatatype/value/) { get; set; } | Obtiene o establece el valor que contiene este tipo de datos. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [ReadTag](../../aspose.psd.fileformats.tiff/tiffdatatype/readtag/)(TiffStreamReader, long) | Lee los datos de la etiqueta. |
| [CompareTo](../../aspose.psd.fileformats.tiff/tiffdatatype/compareto/)(object) | Compara la instancia actual con otro objeto del mismo tipo y devuelve un número entero que indica si la instancia actual precede, sigue u ocurre en la misma posición en el orden de clasificación que el otro objeto. |
| virtual [DeepClone](../../aspose.psd.fileformats.tiff/tiffdatatype/deepclone/)() | Realiza una clonación profunda de esta instancia. |
| override [ToString](../../aspose.psd.fileformats.tiff/tiffdatatype/tostring/)() | Devuelve unString que representa esta instancia. |
| abstract [WriteAdditionalData](../../aspose.psd.fileformats.tiff/tiffdatatype/writeadditionaldata/)(TiffStreamWriter) | Escribe los datos adicionales de la etiqueta. |
| [WriteTag](../../aspose.psd.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | Escribe los datos de la etiqueta. |

### Ver también

* espacio de nombres [Aspose.PSD.FileFormats.Tiff](../../aspose.psd.fileformats.tiff/)
* asamblea [Aspose.PSD](../../)


