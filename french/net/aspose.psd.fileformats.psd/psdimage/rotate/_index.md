---
title: "PsdImage.Rotate"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode PsdImage. Faire pivoter l'image autour du centre"
type: docs
weight: 670
url: /fr/net/aspose.psd.fileformats.psd/psdimage/rotate/
---
{{< psd/tize >}}
## Rotate(float) {#rotate}

Fait pivoter l'image autour du centre.

```csharp
public override void Rotate(float angle)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| angle | Single | L'angle de rotation en degrés. Les valeurs positives font pivoter dans le sens horaire. |

## Exemples

Le code suivant démontre la capacité de faire pivoter l'image d'une valeur d'angle spécifique.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Rotation de l'image entière
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// Rotation du calque
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### Voir aussi

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)

---

## Rotate(float, bool, Color) {#rotate_1}

Fait pivoter l'image autour du centre.

```csharp
public override void Rotate(float angle, bool resizeProportionally, Color backgroundColor)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| angle | Single | L'angle de rotation en degrés. Les valeurs positives font pivoter dans le sens horaire. |
| resizeProportionally | Booléen | si défini sur `true`, la taille de votre image sera modifiée selon les projections du rectangle tourné (points d'angle) ; sinon, les dimensions restent inchangées et seul le contenu interne de l'image est tourné. |
| backgroundColor | Couleur | Couleur de l'arrière-plan. |

### Voir aussi

* struct [Color](../../../aspose.psd/color/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


