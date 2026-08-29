---
title: "WarpSettings.WarpSettings"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "WarpSettings constructor. Initialiseert een nieuw exemplaar van de WarpSettings-klasse"
type: docs
weight: 10
url: /nl/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/warpsettings/
---
{{< psd/tize >}}
## WarpSettings(PointF[], Rectangle) {#constructor_2}

Initialiseert een nieuw exemplaar van de [`WarpSettings`](../) klasse.

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| meshPoints | PointF[] | De mesh-punten van warp |
| bounds | Rechthoek | De grenzen van warp-afbeelding |

## Voorbeelden

De volgende code toont de ondersteuning van de WarpSettings.GridSize eigenschap.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Warp-instellingen ophalen
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Nieuwe grootte instellen
    // Voor Photoshop kan de waarde tussen 1 en 50 liggen en kun je een PSD-bestand niet correct opslaan.
    warpSettings.GridSize = new Size(100, 100);

    // Geldige waarde instellen
    warpSettings.GridSize = new Size(3, 3);

    // Voorbeeldbestand renderen met x3 raster
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### Zie ook

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PointF[], Rectangle, WarpStyles) {#constructor_3}

Initialiseert een nieuw exemplaar van de [`WarpSettings`](../) klasse.

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds, WarpStyles style)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| meshPoints | PointF[] | De mesh-punten van warp |
| bounds | Rechthoek | De grenzen van warp-afbeelding |
| stijl | WarpStyles | De stijl van warp |

## Voorbeelden

De volgende code toont de ondersteuning van de WarpSettings.GridSize eigenschap.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Warp-instellingen ophalen
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Nieuwe grootte instellen
    // Voor Photoshop kan de waarde tussen 1 en 50 liggen en kun je een PSD-bestand niet correct opslaan.
    warpSettings.GridSize = new Size(100, 100);

    // Geldige waarde instellen
    warpSettings.GridSize = new Size(3, 3);

    // Voorbeeldbestand renderen met x3 raster
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### Zie ook

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* enum [WarpStyles](../../warpstyles/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(OSTypeStructure[], Rectangle) {#constructor}

Initialiseert een nieuw exemplaar van de [`WarpSettings`](../) klasse.

```csharp
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| warpItems | OSTypeStructure[] | PS-items met warp-instellingen |
| bounds | Rechthoek | De grenzen van warp-afbeelding |

### Zie ook

* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PlacedResource) {#constructor_1}

Initialiseert een nieuw exemplaar van de [`WarpSettings`](../) klasse.

```csharp
public WarpSettings(PlacedResource placedResource)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| placedResource | PlacedResource | De bron met warp-instellingen |

### Zie ook

* class [PlacedResource](../../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


