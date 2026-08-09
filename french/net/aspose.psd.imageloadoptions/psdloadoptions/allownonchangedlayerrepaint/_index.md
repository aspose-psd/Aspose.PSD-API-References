---
title: "PsdLoadOptions.AllowNonChangedLayerRepaint"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété PsdLoadOptions. Obtient ou définit s'il faut préserver les pixels des calques originaux lors du rendu si le calque n'a pas été modifié."
type: docs
weight: 20
url: /fr/net/aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowNonChangedLayerRepaint property

Obtient ou définit s'il faut conserver les pixels de calque originaux lors du rendu si le calque n'a pas été modifié.

```csharp
public bool AllowNonChangedLayerRepaint { get; set; }
```

### Property Value

`true` pour conserver les pixels originaux des calques non modifiés ; sinon, `false`.

## Exemples

Le code suivant démontre le nouveau comportement qui empêche le rafraîchissement automatique des calques avant les modifications.

```csharp
[C#]

string srcFile = "psdnet2400.psd";
string output1 = "unchanged-2400.png";
string output2 = "updated-2400.png";

using (var psdImage = (PsdImage)Image.Load(srcFile,
new PsdLoadOptions() { AllowNonChangedLayerRepaint = false /* The new default behaviour */ }))
{
    psdImage.Save(output1, new PngOptions());

    ((TextLayer)psdImage.Layers[1]).TextData.UpdateLayerData();

    psdImage.Save(output2, new PngOptions());
}
```

### Voir aussi

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


