---
title: "Énumération PsdVersion"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.PsdVersion enum. Version du format de fichier"
type: docs
weight: 4060
url: /fr/net/aspose.psd.fileformats.psd/psdversion/
---
{{< psd/tize >}}
## PsdVersion enumeration

Version du format de fichier

```csharp
public enum PsdVersion : byte
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Psd | `1` | La version PSD par défaut. |
| Psb | `2` | La version PSB. |

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

* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


