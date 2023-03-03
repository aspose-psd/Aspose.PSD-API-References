---
title: RasterCachedImage.Resize
second_title: Référence de l'API Aspose.PSD pour .NET
description: RasterCachedImage méthode. Redimensionne limage.
type: docs
weight: 120
url: /fr/net/aspose.psd/rastercachedimage/resize/
---
## Resize(int, int, ResizeType) {#resize_2}

Redimensionne l'image.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| newWidth | Int32 | La nouvelle largeur. |
| newHeight | Int32 | La nouvelle hauteur. |
| resizeType | ResizeType | Le type de redimensionnement. |

### Exemples

Le code suivant montre comment redimensionner une image avec un nouveau type de redimensionnement SinC.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// Charger une image existante dans une instance de la classe PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

Le code suivant montre comment redimensionner une image avec un nouveau type de redimensionnement Bell.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// Charger une image existante dans une instance de la classe PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

Le code suivant montre comment redimensionner une image avec un nouveau type de redimensionnement Mitchell.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// Charger une image existante dans une instance de la classe PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

Le code suivant montre comment redimensionner une image avec un nouveau type de redimensionnement CatmullRom.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// Charger une image existante dans une instance de la classe PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

Le code suivant montre comment redimensionner une image avec un nouveau type de redimensionnement CubicBSpline.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// Charger une image existante dans une instance de la classe PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

Le code suivant montre comment redimensionner une image avec un nouveau type de redimensionnement CubicConvolution.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// Charger une image existante dans une instance de la classe PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### Voir également

* enum [ResizeType](../../resizetype/)
* class [RasterCachedImage](../)
* espace de noms [Aspose.PSD](../../rastercachedimage/)
* Assemblée [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Redimensionne l'image.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| newWidth | Int32 | La nouvelle largeur. |
| newHeight | Int32 | La nouvelle hauteur. |
| settings | ImageResizeSettings | Les paramètres de redimensionnement. |

### Voir également

* class [ImageResizeSettings](../../imageresizesettings/)
* class [RasterCachedImage](../)
* espace de noms [Aspose.PSD](../../rastercachedimage/)
* Assemblée [Aspose.PSD](../../../)


