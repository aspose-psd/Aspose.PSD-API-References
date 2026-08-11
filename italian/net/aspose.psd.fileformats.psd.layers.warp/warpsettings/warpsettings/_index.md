---
title: "WarpSettings.WarpSettings"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Costruttore WarpSettings. Inizializza una nuova istanza della classe WarpSettings"
type: docs
weight: 10
url: /it/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/warpsettings/
---
{{< psd/tize >}}
## WarpSettings(PointF[], Rectangle) {#constructor_2}

Inizializza una nuova istanza della classe [`WarpSettings`](../).

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| meshPoints | PointF[] | I punti della mesh della deformazione |
| bounds | Rettangolo | I limiti dell'immagine di deformazione |

## Esempi

Il codice seguente dimostra il supporto della proprietà WarpSettings.GridSize.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Ottieni le impostazioni di deformazione
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Imposta nuova dimensione
    // Per Photoshop il valore può essere compreso tra 1 e 50 e non è possibile salvare correttamente il file PSD.
    warpSettings.GridSize = new Size(100, 100);

    // Imposta valore valido
    warpSettings.GridSize = new Size(3, 3);

    // Esegui il rendering del file di esempio con griglia x3
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### Vedi anche

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PointF[], Rectangle, WarpStyles) {#constructor_3}

Inizializza una nuova istanza della classe [`WarpSettings`](../).

```csharp
public WarpSettings(PointF[] meshPoints, Rectangle bounds, WarpStyles style)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| meshPoints | PointF[] | I punti della mesh della deformazione |
| bounds | Rettangolo | I limiti dell'immagine di deformazione |
| stile | WarpStyles | Lo stile della deformazione |

## Esempi

Il codice seguente dimostra il supporto della proprietà WarpSettings.GridSize.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // Ottieni le impostazioni di deformazione
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // Imposta nuova dimensione
    // Per Photoshop il valore può essere compreso tra 1 e 50 e non è possibile salvare correttamente il file PSD.
    warpSettings.GridSize = new Size(100, 100);

    // Imposta valore valido
    warpSettings.GridSize = new Size(3, 3);

    // Esegui il rendering del file di esempio con griglia x3
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### Vedi anche

* struct [PointF](../../../aspose.psd/pointf/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* enum [WarpStyles](../../warpstyles/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(OSTypeStructure[], Rectangle) {#constructor}

Inizializza una nuova istanza della classe [`WarpSettings`](../).

```csharp
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| warpItems | OSTypeStructure[] | Elementi PS con impostazioni di deformazione |
| bounds | Rettangolo | I limiti dell'immagine di deformazione |

### Vedi anche

* class [OSTypeStructure](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/)
* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)

---

## WarpSettings(PlacedResource) {#constructor_1}

Inizializza una nuova istanza della classe [`WarpSettings`](../).

```csharp
public WarpSettings(PlacedResource placedResource)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| placedResource | PlacedResource | La risorsa con impostazioni di deformazione |

### Vedi anche

* class [PlacedResource](../../../aspose.psd.fileformats.psd.layers.layerresources/placedresource/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


