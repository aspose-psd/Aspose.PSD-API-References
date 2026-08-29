---
title: "PsdOptions.PsdVersion"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété PsdOptions. Obtient ou définit la version du format de fichier. Elle peut être PSD ou PSB"
type: docs
weight: 70
url: /fr/net/aspose.psd.imageoptions/psdoptions/psdversion/
---
{{< psd/tize >}}
## PsdOptions.PsdVersion property

Obtient ou définit la version du format de fichier. Il peut s'agir de PSD ou PSB.

```csharp
public PsdVersion PsdVersion { get; set; }
```

### Property Value

La version du format de fichier.

## Exemples

L'exemple suivant montre la capacité de convertir un fichier PSD en PSB et vice‑versa.

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

### Voir aussi

* enum [PsdVersion](../../../aspose.psd.fileformats.psd/psdversion/)
* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


