---
title: Enum PsdVersion
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.FileFormats.Psd.PsdVersion enumeración. Versión de formato de archivo
type: docs
weight: 3600
url: /es/net/aspose.psd.fileformats.psd/psdversion/
---
## PsdVersion enumeration

Versión de formato de archivo

```csharp
public enum PsdVersion : byte
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Psd | `1` | La versión PSD predeterminada. |
| Psb | `2` | La versión PSB. |

### Ejemplos

El siguiente ejemplo muestra la capacidad de convertir un archivo PSD a PSB y viceversa.

```csharp
[C#]

string sourceFilePathPsb = "2layers.psb";
string outputFilePathPsd = "ConvertFromPsb.psd";
using (Image img = Image.Load(sourceFilePathPsb))
{
    var options = new PsdOptions((PsdImage)img) { PsdVersion = PsdVersion.Psd };
    img.Save(outputFilePathPsd, options);
}

string sourceFilePathPsd = "2layers.psd";
string outputFilePathPsb = "ConvertFromPsd.psb";
using (Image img = Image.Load(sourceFilePathPsd))
{
    var options = new PsdOptions((PsdImage)img) { PsdVersion = PsdVersion.Psb };
    img.Save(outputFilePathPsb, options);
}
```

### Ver también

* espacio de nombres [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* asamblea [Aspose.PSD](../../)


