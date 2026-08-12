---
title: "Clase TiffDataType"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.FileFormats.Tiff.TiffDataType. El tipo de datos tiff"
type: docs
weight: 4680
url: /es/net/aspose.psd.fileformats.tiff/tiffdatatype/
---
{{< psd/tize >}}
## TiffDataType class

El tipo de datos tiff.

```csharp
public abstract class TiffDataType : IComparable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AlignedDataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/aligneddatasize/) { get; } | Obtiene el tamaño adicional de datos en bytes (en caso de que los 12 bytes no sean suficientes para contener los datos de la etiqueta). |
| abstract [Count](../../aspose.psd.fileformats.tiff/tiffdatatype/count/) { get; } | Obtiene la cantidad de elementos. |
| abstract [DataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/datasize/) { get; } | Obtiene el tamaño adicional de datos en bytes (en caso de que los 12 bytes no sean suficientes para contener los datos de la etiqueta). |
| [Id](../../aspose.psd.fileformats.tiff/tiffdatatype/id/) { get; } | Obtiene la representación entera del id de la etiqueta. |
| [IsValid](../../aspose.psd.fileformats.tiff/tiffdatatype/isvalid/) { get; } | Obtiene un valor que indica si los datos de la etiqueta son válidos. La etiqueta válida contiene datos que pueden preservarse. La etiqueta inválida no puede almacenarse. |
| [TagId](../../aspose.psd.fileformats.tiff/tiffdatatype/tagid/) { get; } | Obtiene el id de la etiqueta. |
| abstract [TagType](../../aspose.psd.fileformats.tiff/tiffdatatype/tagtype/) { get; } | Obtiene el tipo de etiqueta. |
| abstract [Value](../../aspose.psd.fileformats.tiff/tiffdatatype/value/) { get; set; } | Obtiene o establece el valor que contiene este tipo de datos. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [ReadTag](../../aspose.psd.fileformats.tiff/tiffdatatype/readtag/)(TiffStreamReader, long) | Lee los datos de la etiqueta. |
| [CompareTo](../../aspose.psd.fileformats.tiff/tiffdatatype/compareto/)(object) | Compara la instancia actual con otro objeto del mismo tipo y devuelve un entero que indica si la instancia actual precede, sigue o se encuentra en la misma posición en el orden de clasificación que el otro objeto. |
| virtual [DeepClone](../../aspose.psd.fileformats.tiff/tiffdatatype/deepclone/)() | Realiza una clonación profunda de esta instancia. |
| override [ToString](../../aspose.psd.fileformats.tiff/tiffdatatype/tostring/)() | Devuelve una String que representa esta instancia. |
| abstract [WriteAdditionalData](../../aspose.psd.fileformats.tiff/tiffdatatype/writeadditionaldata/)(TiffStreamWriter) | Escribe los datos de etiqueta adicionales. |
| [WriteTag](../../aspose.psd.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | Escribe los datos de la etiqueta. |

### Ver también

* namespace [Aspose.PSD.FileFormats.Tiff](../../aspose.psd.fileformats.tiff/)
* assembly [Aspose.PSD](../../)


