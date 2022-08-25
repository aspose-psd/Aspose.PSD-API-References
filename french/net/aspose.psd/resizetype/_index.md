---
title: ResizeType
second_title: Référence de l'API Aspose.PSD pour .NET
description: Spécifie le type de redimensionnement.
type: docs
weight: 5300
url: /fr/net/aspose.psd/resizetype/
---
## ResizeType enumeration

Spécifie le type de redimensionnement.

```csharp
public enum ResizeType
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| None | `0` | Les pixels ne sont pas conservés lors de l'opération de redimensionnement. |
| LeftTopToLeftTop | `1` | Le point supérieur gauche de la nouvelle image coïncidera avec le point supérieur gauche de l'image d'origine. Le recadrage aura lieu si nécessaire. |
| RightTopToRightTop | `2` | Le point supérieur droit de la nouvelle image coïncidera avec le point supérieur droit de l'image d'origine. Le recadrage aura lieu si nécessaire. |
| RightBottomToRightBottom | `3` | Le point inférieur droit de la nouvelle image coïncidera avec le point inférieur droit de l'image d'origine. Le recadrage aura lieu si nécessaire. |
| LeftBottomToLeftBottom | `4` | Le point inférieur gauche de la nouvelle image coïncidera avec le point inférieur gauche de l'image d'origine. Le recadrage aura lieu si nécessaire. |
| CenterToCenter | `5` | Le centre de la nouvelle image coïncidera avec le centre de l'image originale. Le recadrage aura lieu si nécessaire. |
| LanczosResample | `6` | Rééchantillonner en utilisant l'algorithme de lanczos avec a=3. |
| NearestNeighbourResample | `7` | Rééchantillonner en utilisant l'algorithme du plus proche voisin. |
| AdaptiveResample | `8` | Rééchantillonner à l'aide d'un algorithme adaptatif basé sur une fonction rationnelle pondérée et mixte et des algorithmes d'interpolation lanczos3. |
| BilinearResample | `9` | Rééchantillonnez en utilisant une interpolation bilinéaire. Le pré-filtrage d'image est autorisé pour supprimer le bruit avant le rééchantillonnage, si nécessaire |
| HighQualityResample | `10` | Le rééchantillonnage de haute qualité |
| CatmullRom | `11` | La méthode d'interpolation cubique Catmull-Rom. |
| CubicConvolution | `12` | La méthode d'interpolation par convolution cubique |
| CubicBSpline | `13` | La méthode d'interpolation cubique CubicBSpline |
| Mitchell | `14` | La méthode d'interpolation cubique de Mitchell |
| SinC | `15` | La méthode d'interpolation cubique Sinc (Lanczos3) |
| Bell | `16` | La méthode d'interpolation de Bell |

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

* espace de noms [Aspose.PSD](../../aspose.psd)
* Assemblée [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
