---
title: "FillLayer.ReplaceNonTransparentColors"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode FillLayer. Remplace toutes les couleurs non transparentes par une nouvelle couleur et préserve la valeur alpha originale pour conserver des bords lisses. Notez que si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule."
type: docs
weight: 40
url: /fr/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/
---
{{< psd/tize >}}
## FillLayer.ReplaceNonTransparentColors method

Remplace toutes les couleurs non transparentes par une nouvelle couleur et préserve la valeur alpha originale pour conserver des bords lisses. Remarque : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule.

```csharp
public override void ReplaceNonTransparentColors(int newColorArgb)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| newColorArgb | Int32 | Nouvelle valeur ARGB de couleur pour remplacer les couleurs non transparentes. |

## Exemples

Le code suivant montre la prise en charge du mode couleur CMYK 16 bits et la capacité de dessiner en utilisant la classe Aspose.PSD.Graphics.

```csharp
[C#]

string srcFile = "cub16bit_cmyk.psd";
string outputPsd = "output.psd";
string outputPng = "output.png";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### Voir aussi

* class [FillLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)


