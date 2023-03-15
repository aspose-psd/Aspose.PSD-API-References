---
title: FillLayer.ReplaceNonTransparentColors
second_title: Référence de l'API Aspose.PSD pour .NET
description: FillLayer méthode. Remplace toutes les couleurs non transparentes par une nouvelle couleur et conserve la valeur alpha dorigine pour économiser des bords lisses. Remarque  si vous lutilisez sur des images sans transparence toutes les couleurs seront remplacées par une seule.
type: docs
weight: 40
url: /fr/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/replacenontransparentcolors/
---
## FillLayer.ReplaceNonTransparentColors method

Remplace toutes les couleurs non transparentes par une nouvelle couleur et conserve la valeur alpha d'origine pour économiser des bords lisses. Remarque : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule.

```csharp
public override void ReplaceNonTransparentColors(int newColorArgb)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| newColorArgb | Int32 | Nouvelle valeur ARGB de couleur pour remplacer les couleurs non transparentes. |

### Exemples

Le code suivant illustre la prise en charge du CMJN ColorMode 16 bits et la possibilité de dessiner à l'aide de la classe Aspose.PSD.Graphics.

```csharp
[C#]

using (PsdImage image = (PsdImage)Image.Load("cub16bit_cmyk.psd"))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save("output.psd");
    image.Save("output.png", new PngOptions());
}
```

### Voir également

* class [FillLayer](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* Assemblée [Aspose.PSD](../../../)


