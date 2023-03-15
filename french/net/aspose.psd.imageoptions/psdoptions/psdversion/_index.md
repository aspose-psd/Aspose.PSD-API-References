---
title: PsdOptions.PsdVersion
second_title: Référence de l'API Aspose.PSD pour .NET
description: PsdOptions propriété. Obtient ou définit la version du format de fichier. Il peut sagir de PSD ou de PSB.
type: docs
weight: 60
url: /fr/net/aspose.psd.imageoptions/psdoptions/psdversion/
---
## PsdOptions.PsdVersion property

Obtient ou définit la version du format de fichier. Il peut s'agir de PSD ou de PSB.

```csharp
public PsdVersion PsdVersion { get; set; }
```

### Valeur de la propriété

La version du format de fichier.

### Exemples

L'exemple suivant montre la possibilité de convertir un fichier PSD en PSB et vice versa.

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

### Voir également

* enum [PsdVersion](../../../aspose.psd.fileformats.psd/psdversion/)
* class [PsdOptions](../)
* espace de noms [Aspose.PSD.ImageOptions](../../psdoptions/)
* Assemblée [Aspose.PSD](../../../)


