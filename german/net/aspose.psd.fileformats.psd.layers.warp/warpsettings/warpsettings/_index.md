---
title: "WarpSettings.WarpSettings"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "WarpSettings-Konstruktor. Initialisiert eine neue Instanz der WarpSettings-Klasse"
type: docs
weight: 10
url: /de/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/warpsettings/
---
{{< psd/tize >}}
## WarpSettings(PointF[], Rectangle) {#constructor_2}

Initialisiert eine neue Instanz der [`WarpSettings`](../)-Klasse.

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| meshPoints | PointF[] | Die Netzpunkte der Verzerrung |
| bounds | Rectangle | Die Begrenzungen des verzerrten Bildes |

## Beispiele

Der folgende Code demonstriert die Unterstützung der WarpSettings.GridSize-Eigenschaft.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Warp-Einstellungen abrufen
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Neue Größe festlegen
    // Für Photoshop kann der Wert zwischen 1 und 50 liegen und Sie können die PSD-Datei nicht korrekt speichern.
    warpSettings.GridSize = new Size(100, 100);

    // Gültigen Wert festlegen
    warpSettings.GridSize = new Size(3, 3);

    // Beispieldatei mit x3-Raster rendern
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### Siehe auch

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PointF[], Rectangle, WarpStyles) {#constructor_3}

Initialisiert eine neue Instanz der [`WarpSettings`](../)-Klasse.

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds, WarpStyles style)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| meshPoints | PointF[] | Die Netzpunkte der Verzerrung |
| bounds | Rectangle | Die Begrenzungen des verzerrten Bildes |
| Stil | WarpStyles | Der Stil der Verzerrung |

## Beispiele

Der folgende Code demonstriert die Unterstützung der WarpSettings.GridSize-Eigenschaft.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Warp-Einstellungen abrufen
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Neue Größe festlegen
    // Für Photoshop kann der Wert zwischen 1 und 50 liegen und Sie können die PSD-Datei nicht korrekt speichern.
    warpSettings.GridSize = new Size(100, 100);

    // Gültigen Wert festlegen
    warpSettings.GridSize = new Size(3, 3);

    // Beispieldatei mit x3-Raster rendern
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### Siehe auch

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* enum [WarpStyles](../../warpstyles/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(OSTypeStructure[], Rectangle) {#constructor}

Initialisiert eine neue Instanz der [`WarpSettings`](../)-Klasse.

```csharp
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| warpItems | OSTypeStructure[] | PS-Elemente mit Warp-Einstellungen |
| bounds | Rectangle | Die Begrenzungen des verzerrten Bildes |

### Siehe auch

* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PlacedResource) {#constructor_1}

Initialisiert eine neue Instanz der [`WarpSettings`](../)-Klasse.

```csharp
public WarpSettings(PlacedResource placedResource)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| placedResource | PlacedResource | Die Ressource mit Warp-Einstellungen |

### Siehe auch

* class [PlacedResource](../../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


