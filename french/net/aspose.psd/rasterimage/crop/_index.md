---
title: "RasterImage.Crop"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode RasterImage. Rogne le rectangle spécifié"
type: docs
weight: 240
url: /fr/net/aspose.psd/rasterimage/crop/
---
{{< psd/tize >}}
## Crop(Rectangle) {#crop}

Recadre le rectangle spécifié.

```csharp
public virtual void Crop(Rectangle rectangle)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | Rectangle | Le rectangle. |

## Exemples

L'exemple de code suivant montre comment rogner une image et l'enregistrer.

```csharp
[C#]

// Implémentez la méthode Crop correcte pour les fichiers PSD.
string sourceFileName = "1.psd";
string exportPathPsd = "CropTest.psd";
string exportPathPng = "CropTest.png";
using (RasterImage image = Image.Load(sourceFileName) as RasterImage)
{
    image.Crop(new Rectangle(10, 30, 100, 100));
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Voir aussi

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Crop(int, int, int, int) {#crop_1}

Recadrer l'image avec des décalages.

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| leftShift | Int32 | Le décalage à gauche. |
| rightShift | Int32 | Le décalage à droite. |
| topShift | Int32 | Le décalage supérieur. |
| bottomShift | Int32 | Le décalage inférieur. |

### Voir aussi

* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


