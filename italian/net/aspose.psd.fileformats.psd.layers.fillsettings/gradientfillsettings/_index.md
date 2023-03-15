---
title: Class GradientFillSettings
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.FillSettings.GradientFillSettings classe. Impostazioni delleffetto di riempimento sfumato.
type: docs
weight: 1960
url: /it/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---
## GradientFillSettings class

Impostazioni dell'effetto di riempimento sfumato.

```csharp
public class GradientFillSettings : BaseFillSettings, IGradientFillSettings
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [GradientFillSettings](gradientfillsettings/)() | Inizializza una nuova istanza di`GradientFillSettings` classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/alignwithlayer/) { get; set; } | Ottiene o imposta un valore che indica se [allinea al livello]. |
| [Angle](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/angle/) { get; set; } | Ottiene o imposta l'angolo. |
| [Color](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/color/) { get; set; } | Ottiene o imposta il colore. |
| [ColorPoints](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/colorpoints/) { get; set; } | Ottiene o imposta i punti di colore. |
| [Dither](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/dither/) { get; set; } | Ottiene o imposta un valore che indica se this`GradientFillSettings` è dither. |
| override [FillType](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/filltype/) { get; } | Il tipo di riempimento |
| [GradientName](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/gradientname/) { get; set; } | Ottiene o imposta il nome del gradiente. |
| [GradientType](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/gradienttype/) { get; set; } | Ottiene o imposta il tipo di gradiente. |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/horizontaloffset/) { get; set; } | Ottiene o imposta l'offset orizzontale in percentuale. |
| [Reverse](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/reverse/) { get; set; } | Ottiene o imposta un valore che indica se this`GradientFillSettings` è inverso. |
| [Scale](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/scale/) { get; set; } | Ottiene o imposta la scala. |
| [TransparencyPoints](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/transparencypoints/) { get; set; } | Ottiene o imposta i punti di trasparenza. |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/verticaloffset/) { get; set; } | Ottiene o imposta l'offset verticale in percentuale. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddColorPoint](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/addcolorpoint/)() | Aggiunge il punto di colore. |
| [AddTransparencyPoint](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/addtransparencypoint/)() | Aggiunge il punto di colore. |
| [RemoveColorPoint](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/removecolorpoint/)(IGradientColorPoint) | Rimuove il punto di colore. |
| [RemoveTransparencyPoint](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/removetransparencypoint/)(IGradientTransparencyPoint) | Rimuove il punto di trasparenza. |
| static [GenerateLfx2ResourceNodes](../../aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/generatelfx2resourcenodes/)() | Genera i nodi di risorse LFX2. |

### Esempi

Il codice seguente dimostra il supporto del livello dell'effetto tratto con il tipo di riempimento Gradiente.

```csharp
[C#]

void AssertIsTrue(bool condition, string message)
{
    if (!condition)
    {
        throw new FormatException(message);
    }
}
void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

string sourceFileName = "Stroke.psd";
string exportPath = "StrokeGradientChanged.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true
};

using (var im = (PsdImage)Image.Load(sourceFileName, loadOptions))
{
    var gradientStroke = (StrokeEffect)im.Layers[2].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Normal, gradientStroke.BlendMode);
    AssertAreEqual((byte)255, gradientStroke.Opacity);
    AssertAreEqual(true, gradientStroke.IsVisible);

    var fillSettings = (GradientFillSettings)gradientStroke.FillSettings;
    AssertAreEqual(Color.Black, fillSettings.Color);
    AssertAreEqual(FillType.Gradient, fillSettings.FillType);
    AssertAreEqual(true, fillSettings.AlignWithLayer);
    AssertAreEqual(GradientType.Linear, fillSettings.GradientType);
    AssertIsTrue(Math.Abs(90 - fillSettings.Angle) < 0.001, "Angle is incorrect");
    AssertAreEqual(false, fillSettings.Dither);
    AssertIsTrue(Math.Abs(0 - fillSettings.HorizontalOffset) < 0.001, "Horizontal offset is incorrect");
    AssertIsTrue(Math.Abs(0 - fillSettings.VerticalOffset) < 0.001, "Vertical offset is incorrect");
    AssertAreEqual(false, fillSettings.Reverse);

    // Punti colore
    var colorPoints = fillSettings.ColorPoints;
    AssertAreEqual(2, colorPoints.Length);

    AssertAreEqual(Color.Black, colorPoints[0].Color);
    AssertAreEqual(0, colorPoints[0].Location);
    AssertAreEqual(50, colorPoints[0].MedianPointLocation);

    AssertAreEqual(Color.White, colorPoints[1].Color);
    AssertAreEqual(4096, colorPoints[1].Location);
    AssertAreEqual(50, colorPoints[1].MedianPointLocation);

    // Punti di trasparenza
    var transparencyPoints = fillSettings.TransparencyPoints;
    AssertAreEqual(2, transparencyPoints.Length);

    AssertAreEqual(0, transparencyPoints[0].Location);
    AssertAreEqual(50, transparencyPoints[0].MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoints[0].Opacity);

    AssertAreEqual(4096, transparencyPoints[1].Location);
    AssertAreEqual(50, transparencyPoints[1].MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoints[1].Opacity);

    // Modifica di prova
    fillSettings.Color = Color.Green;

    gradientStroke.Opacity = 127;
    gradientStroke.BlendMode = BlendMode.Color;

    fillSettings.AlignWithLayer = false;
    fillSettings.GradientType = GradientType.Radial;
    fillSettings.Angle = 45;
    fillSettings.Dither = true;
    fillSettings.HorizontalOffset = 15;
    fillSettings.VerticalOffset = 11;
    fillSettings.Reverse = true;

    // Aggiungi un nuovo punto di colore
    var colorPoint = fillSettings.AddColorPoint();
    colorPoint.Color = Color.Green;
    colorPoint.Location = 4096;
    colorPoint.MedianPointLocation = 75;

    // Cambia la posizione del punto precedente
    fillSettings.ColorPoints[1].Location = 1899;

    // Aggiungi un nuovo punto di trasparenza
    var transparencyPoint = fillSettings.AddTransparencyPoint();
    transparencyPoint.Opacity = 25;
    transparencyPoint.MedianPointLocation = 25;
    transparencyPoint.Location = 4096;

    // Modifica la posizione del punto di trasparenza precedente
    fillSettings.TransparencyPoints[1].Location = 2411;

    im.Save(exportPath);
}

// Prova il file dopo la modifica
using (var im = (PsdImage)Image.Load(exportPath, loadOptions))
{
    var gradientStroke = (StrokeEffect)im.Layers[2].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Color, gradientStroke.BlendMode);
    AssertAreEqual((byte)127, gradientStroke.Opacity);
    AssertAreEqual(true, gradientStroke.IsVisible);

    var fillSettings = (GradientFillSettings)gradientStroke.FillSettings;
    AssertAreEqual(Color.Green, fillSettings.Color);
    AssertAreEqual(FillType.Gradient, fillSettings.FillType);

    // Controlla i punti di colore
    AssertAreEqual(3, fillSettings.ColorPoints.Length);

    var point = fillSettings.ColorPoints[0];
    AssertAreEqual(50, point.MedianPointLocation);
    AssertAreEqual(Color.Black, point.Color);
    AssertAreEqual(0, point.Location);

    point = fillSettings.ColorPoints[1];
    AssertAreEqual(50, point.MedianPointLocation);
    AssertAreEqual(Color.White, point.Color);
    AssertAreEqual(1899, point.Location);

    point = fillSettings.ColorPoints[2];
    AssertAreEqual(75, point.MedianPointLocation);
    AssertAreEqual(Color.Green, point.Color);
    AssertAreEqual(4096, point.Location);

    // Controlla i punti trasparenti
    AssertAreEqual(3, fillSettings.TransparencyPoints.Length);

    var transparencyPoint = fillSettings.TransparencyPoints[0];
    AssertAreEqual(50, transparencyPoint.MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoint.Opacity);
    AssertAreEqual(0, transparencyPoint.Location);

    transparencyPoint = fillSettings.TransparencyPoints[1];
    AssertAreEqual(50, transparencyPoint.MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoint.Opacity);
    AssertAreEqual(2411, transparencyPoint.Location);

    transparencyPoint = fillSettings.TransparencyPoints[2];
    AssertAreEqual(25, transparencyPoint.MedianPointLocation);
    AssertAreEqual(25.00, transparencyPoint.Opacity);
    AssertAreEqual(4096, transparencyPoint.Location);
}
```

### Guarda anche

* class [BaseFillSettings](../basefillsettings/)
* interface [IGradientFillSettings](../igradientfillsettings/)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assemblea [Aspose.PSD](../../)


