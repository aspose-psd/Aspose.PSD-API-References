---
title: RasterImage.Crop
second_title: Référence de l'API Aspose.PSD pour .NET
description: RasterImage méthode. Rogne le rectangle spécifié.
type: docs
weight: 240
url: /fr/net/aspose.psd/rasterimage/crop/
---
## Crop(Rectangle) {#crop}

Rogne le rectangle spécifié.

```csharp
public virtual void Crop(Rectangle rectangle)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| rectangle | Rectangle | Le rectangle. |

### Exemples

L'exemple de code suivant montre comment recadrer une image et l'enregistrer.

```csharp
[C#]

// Implémenter la méthode Crop correcte pour les fichiers PSD.
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

### Voir également

* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* espace de noms [Aspose.PSD](../../rasterimage/)
* Assemblée [Aspose.PSD](../../../)

---

## Crop(int, int, int, int) {#crop_1}

Recadrer l'image avec des décalages.

```csharp
public virtual void Crop(int leftShift, int rightShift, int topShift, int bottomShift)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| leftShift | Int32 | Le décalage à gauche. |
| rightShift | Int32 | Le virage à droite. |
| topShift | Int32 | Le changement supérieur. |
| bottomShift | Int32 | Le décalage du bas. |

### Voir également

* class [RasterImage](../)
* espace de noms [Aspose.PSD](../../rasterimage/)
* Assemblée [Aspose.PSD](../../../)


