---
title: AiLayerSection
second_title: Riferimento all'API di Aspose.PSD per .NET
description: La sezione del livello del formato Ai
type: docs
weight: 1270
url: /it/net/aspose.psd.fileformats.ai/ailayersection/
---
## AiLayerSection class

La sezione del livello del formato Ai

```csharp
public sealed class AiLayerSection : AiDataSection
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Blue](../../aspose.psd.fileformats.ai/ailayersection/blue) { get; set; } | Ottiene o imposta il componente di colore blu. |
| [ColorNumber](../../aspose.psd.fileformats.ai/ailayersection/colornumber) { get; set; } | Ottiene o imposta il numero del colore. -1 è il valore del colore personalizzato dalle proprietà Rosso, Verde, Blu. Specifica l'impostazione del colore del livello. |
| [DimValue](../../aspose.psd.fileformats.ai/ailayersection/dimvalue) { get; set; } | Ottiene o imposta il valore dim come percentuale. Riduce l'intensità delle immagini collegate e delle immagini bitmap contenute nel livello alla percentuale specificata. |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [Green](../../aspose.psd.fileformats.ai/ailayersection/green) { get; set; } | Ottiene o imposta il componente di colore verde. |
| [IsImagesDimmed](../../aspose.psd.fileformats.ai/ailayersection/isimagesdimmed) { get; set; } | Ottiene o imposta un valore che indica se questo livello è oscurato. Riduce l'intensità delle immagini collegate e delle immagini bitmap contenute nel livello. |
| [IsLocked](../../aspose.psd.fileformats.ai/ailayersection/islocked) { get; set; } | Ottiene o imposta un valore che indica se questo livello è bloccato. Impedisce modifiche all'elemento. |
| [IsPreview](../../aspose.psd.fileformats.ai/ailayersection/ispreview) { get; set; } | Ottiene o imposta un valore che indica se questo livello è in anteprima. Visualizza il disegno contenuto nel livello a colori anziché come contorni. |
| [IsPrinted](../../aspose.psd.fileformats.ai/ailayersection/isprinted) { get; set; } | Ottiene o imposta un valore che indica se questo livello è stampato. Rende stampabile la grafica contenuta nel livello se true. |
| [IsShown](../../aspose.psd.fileformats.ai/ailayersection/isshown) { get; set; } | Ottiene o imposta un valore che indica se questo livello è mostrato. Visualizza tutta la grafica contenuta nel livello sulla tavola da disegno se true. |
| [IsTemplate](../../aspose.psd.fileformats.ai/ailayersection/istemplate) { get; set; } | Ottiene o imposta un valore che indica se questo livello è un livello modello. |
| [Name](../../aspose.psd.fileformats.ai/ailayersection/name) { get; set; } | Ottiene o imposta il nome del livello. Specifica il nome dell'elemento come appare nel pannello Livelli. |
| [RasterImages](../../aspose.psd.fileformats.ai/ailayersection/rasterimages) { get; } | Ottiene le immagini raster. |
| [Red](../../aspose.psd.fileformats.ai/ailayersection/red) { get; set; } | Ottiene o imposta il componente di colore rosso. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddRasterImage](../../aspose.psd.fileformats.ai/ailayersection/addrasterimage)(AiRasterImageSection) | Aggiunge l'immagine raster. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Elimina l'istanza corrente. |
| [GetData](../../aspose.psd.fileformats.ai/aidatasection/getdata)() | Ottiene i dati della stringa. |

### Esempi

Il codice seguente mostra come caricare le impostazioni delle immagini raster nei file di formato AI.

```csharp
[C#]

const double DefaultTolerance = 1e-6;

void AssertIsTrue(bool condition, string message)
{
    if (!condition)
    {
        throw new FormatException(message);
    }
}

string sourceFile = "sample.ai";
using (AiImage image = (AiImage)Image.Load(sourceFile))
{
    AiLayerSection layer = image.Layers[0];

    AssertIsTrue(layer.RasterImages != null, "RasterImages property should be not null");
    AssertIsTrue(layer.RasterImages.Length == 1, "RasterImages property should contain exactly one item");

    AiRasterImageSection rasterImage = layer.RasterImages[0];
    AssertIsTrue(rasterImage.Pixels != null, "rasterImage.Pixels property should be not null");
    AssertIsTrue(rasterImage.Pixels.Length == 100, "rasterImage.Pixels property should contain exactly 100 items");
    AssertIsTrue((uint)rasterImage.Pixels[99] == 0xFFB21616, "rasterImage.Pixels[99] should be 0xFFB21616");
    AssertIsTrue((uint)rasterImage.Pixels[19] == 0xFF00FF00, "rasterImage.Pixels[19] should be 0xFF00FF00");
    AssertIsTrue((uint)rasterImage.Pixels[10] == 0xFF01FD00, "rasterImage.Pixels[10] should be 0xFF01FD00");
    AssertIsTrue((uint)rasterImage.Pixels[0] == 0xFF0000FF, "rasterImage.Pixels[0] should be 0xFF0000FF");
    AssertIsTrue(Math.Abs(0.999875 - rasterImage.Width) < DefaultTolerance, "rasterImage.Width should be 0.99987");
    AssertIsTrue(Math.Abs(0.999875 - rasterImage.Height) < DefaultTolerance, "rasterImage.Height should be 0.99987");
    AssertIsTrue(Math.Abs(387 - rasterImage.OffsetX) < DefaultTolerance, "rasterImage.OffsetX should be 387");
    AssertIsTrue(Math.Abs(379 - rasterImage.OffsetY) < DefaultTolerance, "rasterImage.OffsetY should be 379");
    AssertIsTrue(Math.Abs(0 - rasterImage.Angle) < DefaultTolerance, "rasterImage.Angle should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.LeftBottomShift) < DefaultTolerance, "rasterImage.LeftBottomShift should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.ImageRectangle.X) < DefaultTolerance, "rasterImage.ImageRectangle.X should be 0");
    AssertIsTrue(Math.Abs(0 - rasterImage.ImageRectangle.Y) < DefaultTolerance, "rasterImage.ImageRectangle.Y should be 0");
    AssertIsTrue(Math.Abs(10 - rasterImage.ImageRectangle.Width) < DefaultTolerance, "rasterImage.ImageRectangle.Width should be 10");
    AssertIsTrue(Math.Abs(10 - rasterImage.ImageRectangle.Height) < DefaultTolerance, "rasterImage.ImageRectangle.Height should be 10");
}
```

### Guarda anche

* class [AiDataSection](../aidatasection)
* spazio dei nomi [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai)
* assemblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
