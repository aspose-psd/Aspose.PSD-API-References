---
title: "PsdLoadOptions.AllowWarpRepaint"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété PsdLoadOptions. Obtient ou définit s'il faut enregistrer l'image rendue avec ou sans transformation de distorsion"
type: docs
weight: 30
url: /fr/net/aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowWarpRepaint property

Obtient ou définit s'il faut enregistrer avec l'image rendue, avec ou sans transformation de distorsion.

```csharp
public bool AllowWarpRepaint { get; set; }
```

### Property Value

`true` rend l'image avec transformation de distorsion `false`.

## Exemples

Le code suivant démontre le rendu de l'effet de déformation.

```csharp
[C#]

string sourceFile = "source.psd";
string pngWarpedExport = "warped.png";
string psdWarpedExport = "warpFile.psd";

var warpLoadOptions = new PsdLoadOptions() { AllowWarpRepaint = true };

using (var image = (PsdImage)Image.Load(sourceFile, warpLoadOptions))
{
    image.Save(pngWarpedExport, new PngOptions());
    image.Save(psdWarpedExport, new PsdOptions());
}
```

### Voir aussi

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


