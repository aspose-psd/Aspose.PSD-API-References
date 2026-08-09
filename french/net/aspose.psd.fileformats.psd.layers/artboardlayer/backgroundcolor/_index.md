---
title: "ArtboardLayer.BackgroundColor"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété ArtboardLayer. Obtient ou définit la couleur d'arrière-plan du plan de travail"
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd.layers/artboardlayer/backgroundcolor/
---
{{< psd/tize >}}
## ArtboardLayer.BackgroundColor property

Obtient ou définit la couleur d'arrière-plan de l'artboard.

```csharp
public override Color BackgroundColor { get; set; }
```

## Exemples

Le code suivant montre la prise en charge de l'exportation d'ArtboardLayer en images séparées et toutes dans une seule image.

```csharp
[C#]

string srcFile = "artboard2.psd";

string outFilePng0 = "art0.png";
string outFilePng1 = "art1.png";
string outFilePng2 = "art2.png";
string outFilePng3 = "art3.png";

using (var psdImage = (PsdImage)Image.Load(srcFile))
{
    ArtboardLayer art1 = (ArtboardLayer)psdImage.Layers[4];
    ArtboardLayer art2 = (ArtboardLayer)psdImage.Layers[9];
    ArtboardLayer art3 = (ArtboardLayer)psdImage.Layers[14];

    var pngSaveOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
    art1.Save(outFilePng1, pngSaveOptions);
    art2.Save(outFilePng2, pngSaveOptions);
    art3.Save(outFilePng3, pngSaveOptions);

    psdImage.Save(outFilePng0, pngSaveOptions);
}
```

### Voir aussi

* struct [Color](../../../aspose.psd/color/)
* class [ArtboardLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


