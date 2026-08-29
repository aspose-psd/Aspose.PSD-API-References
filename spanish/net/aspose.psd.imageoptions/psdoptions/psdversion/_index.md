---
title: "PsdOptions.PsdVersion"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad PsdOptions. Obtiene o establece la versión del formato de archivo. Puede ser PSD o PSB."
type: docs
weight: 70
url: /es/net/aspose.psd.imageoptions/psdoptions/psdversion/
---
{{< psd/tize >}}
## PsdOptions.PsdVersion property

Obtiene o establece la versión del formato de archivo. Puede ser PSD o PSB.

```csharp
public PsdVersion PsdVersion { get; set; }
```

### Property Value

La versión del formato de archivo.

## Ejemplos

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

* enum [PsdVersion](../../../aspose.psd.fileformats.psd/psdversion/)
* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


