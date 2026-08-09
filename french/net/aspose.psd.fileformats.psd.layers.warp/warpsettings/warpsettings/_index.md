---
title: "WarpSettings.WarpSettings"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Constructeur WarpSettings. Initialise une nouvelle instance de la classe WarpSettings"
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/warpsettings/
---
{{< psd/tize >}}
## WarpSettings(PointF[], Rectangle) {#constructor_2}

Initialise une nouvelle instance de la classe [`WarpSettings`](../).

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| meshPoints | PointF[] | Les points de maillage de la déformation |
| limites | Rectangle | Les limites de l'image déformée |

## Exemples

Le code suivant montre la prise en charge de la propriété WarpSettings.GridSize.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Obtenir les paramètres de déformation
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Définir une nouvelle taille
    // Pour Photoshop, la valeur peut être comprise entre 1 et 50 et vous ne pouvez pas enregistrer correctement le fichier PSD.
    warpSettings.GridSize = new Size(100, 100);

    // Définir une valeur valide
    warpSettings.GridSize = new Size(3, 3);

    // Rendre le fichier d'exemple avec une grille x3
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### Voir aussi

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PointF[], Rectangle, WarpStyles) {#constructor_3}

Initialise une nouvelle instance de la classe [`WarpSettings`](../).

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds, WarpStyles style)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| meshPoints | PointF[] | Les points de maillage de la déformation |
| limites | Rectangle | Les limites de l'image déformée |
| style | WarpStyles | Le style de la déformation |

## Exemples

Le code suivant montre la prise en charge de la propriété WarpSettings.GridSize.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Obtenir les paramètres de déformation
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Définir une nouvelle taille
    // Pour Photoshop, la valeur peut être comprise entre 1 et 50 et vous ne pouvez pas enregistrer correctement le fichier PSD.
    warpSettings.GridSize = new Size(100, 100);

    // Définir une valeur valide
    warpSettings.GridSize = new Size(3, 3);

    // Rendre le fichier d'exemple avec une grille x3
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### Voir aussi

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* enum [WarpStyles](../../warpstyles/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(OSTypeStructure[], Rectangle) {#constructor}

Initialise une nouvelle instance de la classe [`WarpSettings`](../).

```csharp
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| warpItems | OSTypeStructure[] | Éléments PS avec paramètres de déformation |
| limites | Rectangle | Les limites de l'image déformée |

### Voir aussi

* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PlacedResource) {#constructor_1}

Initialise une nouvelle instance de la classe [`WarpSettings`](../).

```csharp
public WarpSettings(PlacedResource placedResource)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| placedResource | PlacedResource | La ressource avec paramètres de déformation |

### Voir aussi

* class [PlacedResource](../../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


