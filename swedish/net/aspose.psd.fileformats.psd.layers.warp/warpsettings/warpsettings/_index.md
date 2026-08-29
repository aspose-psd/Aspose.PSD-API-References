---
title: "WarpSettings.WarpSettings"
second_title: "Aspose.PSD för .NET API‑referens"
description: "WarpSettings-konstruktor. Initierar en ny instans av WarpSettings‑klassen"
type: docs
weight: 10
url: /sv/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/warpsettings/
---
{{< psd/tize >}}
## WarpSettings(PointF[], Rectangle) {#constructor_2}

Initierar en ny instans av [`WarpSettings`](../)-klassen.

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meshPoints | PointF[] | Mesh‑punkterna för warp |
| gränser | Rectangle | Gränserna för warp‑bilden |

## Exempel

Följande kod demonstrerar stöd för WarpSettings.GridSize-egenskapen.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Hämta warp‑inställningar
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Ställ in ny storlek
    // För Photoshop kan värdet vara mellan 1 och 50 och du kan inte spara PSD‑filen korrekt.
    warpSettings.GridSize = new Size(100, 100);

    // Ställ in ett giltigt värde
    warpSettings.GridSize = new Size(3, 3);

    // Rendera exempelfil med x3‑rutnät
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### Se även

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PointF[], Rectangle, WarpStyles) {#constructor_3}

Initierar en ny instans av [`WarpSettings`](../)-klassen.

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds, WarpStyles style)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| meshPoints | PointF[] | Mesh‑punkterna för warp |
| gränser | Rectangle | Gränserna för warp‑bilden |
| stil | WarpStyles | Stilen för warp |

## Exempel

Följande kod demonstrerar stöd för WarpSettings.GridSize-egenskapen.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Hämta warp‑inställningar
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Ställ in ny storlek
    // För Photoshop kan värdet vara mellan 1 och 50 och du kan inte spara PSD‑filen korrekt.
    warpSettings.GridSize = new Size(100, 100);

    // Ställ in ett giltigt värde
    warpSettings.GridSize = new Size(3, 3);

    // Rendera exempelfil med x3‑rutnät
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### Se även

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* enum [WarpStyles](../../warpstyles/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(OSTypeStructure[], Rectangle) {#constructor}

Initierar en ny instans av [`WarpSettings`](../)-klassen.

```csharp
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| warpItems | OSTypeStructure[] | PS‑objekt med warp‑inställningar |
| gränser | Rectangle | Gränserna för warp‑bilden |

### Se även

* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PlacedResource) {#constructor_1}

Initierar en ny instans av [`WarpSettings`](../)-klassen.

```csharp
public WarpSettings(PlacedResource placedResource)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| placedResource | PlacedResource | Resursen med warp‑inställningar |

### Se även

* class [PlacedResource](../../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


