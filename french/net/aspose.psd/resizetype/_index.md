---
title: "Enum ResizeType"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Enum Aspose.PSD.ResizeType. Spécifie le type de redimensionnement."
type: docs
weight: 5870
url: /fr/net/aspose.psd/resizetype/
---
{{< psd/tize >}}
## ResizeType enumeration

Spécifie le type de redimensionnement.

```csharp
public enum ResizeType
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| None | `0` | Les pixels ne sont pas conservés pendant l'opération de redimensionnement. |
| LeftTopToLeftTop | `1` | Le point supérieur gauche de la nouvelle image coïncidera avec le point supérieur gauche de l'image originale. Un recadrage sera effectué si nécessaire. |
| RightTopToRightTop | `2` | Le point supérieur droit de la nouvelle image coïncidera avec le point supérieur droit de l'image originale. Un recadrage sera effectué si nécessaire. |
| RightBottomToRightBottom | `3` | Le point inférieur droit de la nouvelle image coïncidera avec le point inférieur droit de l'image originale. Un recadrage sera effectué si nécessaire. |
| LeftBottomToLeftBottom | `4` | Le point inférieur gauche de la nouvelle image coïncidera avec le point inférieur gauche de l'image originale. Le recadrage sera effectué si nécessaire. |
| CenterToCenter | `5` | Le centre de la nouvelle image coïncidera avec le centre de l'image originale. Le recadrage sera effectué si nécessaire. |
| LanczosResample | `6` | Rééchantillonner en utilisant l'algorithme Lanczos avec a=3. |
| NearestNeighbourResample | `7` | Rééchantillonner en utilisant l'algorithme du plus proche voisin. |
| AdaptiveResample | `8` | Rééchantillonner en utilisant un algorithme adaptatif basé sur une fonction rationnelle pondérée et mélangée ainsi que les algorithmes d'interpolation Lanczos3. |
| BilinearResample | `9` | Rééchantillonner en utilisant l'interpolation bilinéaire. Le préfiltrage de l'image est autorisé pour supprimer le bruit avant le rééchantillonnage, si nécessaire. |
| HighQualityResample | `10` | Le rééchantillonnage de haute qualité |
| CatmullRom | `11` | La méthode d'interpolation cubique Catmull-Rom. |
| CubicConvolution | `12` | La méthode d'interpolation Cubic Convolution |
| CubicBSpline | `13` | La méthode d'interpolation cubique CubicBSpline |
| Mitchell | `14` | La méthode d'interpolation cubique Mitchell |
| SinC | `15` | La méthode d'interpolation cubique Sinc (Lanczos3) |
| Bell | `16` | La méthode d'interpolation Bell |

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

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


