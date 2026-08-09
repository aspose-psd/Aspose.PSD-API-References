---
title: "RasterCachedImage.Resize"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "RasterCachedImage method. Redimensionne l'image"
type: docs
weight: 120
url: /fr/net/aspose.psd/rastercachedimage/resize/
---
{{< psd/tize >}}
## Resize(int, int, ResizeType) {#resize_2}

Redimensionne l'image.

```csharp
public override void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | Int32 | La nouvelle largeur. |
| newHeight | Int32 | La nouvelle hauteur. |
| resizeType | ResizeType | Le type de redimensionnement. |

## Exemples

Le code suivant montre comment redimensionner une image avec un nouveau type de redimensionnement SinC.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// Chargez une image existante dans une instance de la classe PsdImage
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

// Chargez une image existante dans une instance de la classe PsdImage
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

// Chargez une image existante dans une instance de la classe PsdImage
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

// Chargez une image existante dans une instance de la classe PsdImage
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

// Chargez une image existante dans une instance de la classe PsdImage
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

// Chargez une image existante dans une instance de la classe PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### Voir aussi

* enum [ResizeType](../../resizetype/)
* class [RasterCachedImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

Redimensionne l'image.

```csharp
public override void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | Int32 | La nouvelle largeur. |
| newHeight | Int32 | La nouvelle hauteur. |
| paramètres | ImageResizeSettings | Les paramètres de redimensionnement. |

### Voir aussi

* class [ImageResizeSettings](../../imageresizesettings/)
* class [RasterCachedImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


