---
title: GradientFillSettings.GradientType
second_title: Aspose.PSD per riferimento API .NET
description: GradientFillSettings proprietà. Ottiene o imposta il tipo di gradiente.
type: docs
weight: 90
url: /it/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/gradienttype/
---
## GradientFillSettings.GradientType property

Ottiene o imposta il tipo di gradiente.

```csharp
public GradientType GradientType { get; set; }
```

### Valore della proprietà

Il tipo di gradiente.

### Esempi

Il codice seguente salva le immagini con diversi tipi di gradiente e mostra come Aspose.PSD disegna il gradiente.

```csharp
[C#]

string fileName = "FillLayerGradient.psd";
string sourceFile = fileName;
GradientType[] gradientTypes = new[]
{
    GradientType.Linear, GradientType.Radial, GradientType.Angle, GradientType.Reflected, GradientType.Diamond
};
using (var image = Image.Load(sourceFile))
{
    PsdImage psdImage = (PsdImage)image;
    FillLayer fillLayer = (FillLayer)psdImage.Layers[0];
    GradientFillSettings fillSettings = (GradientFillSettings)fillLayer.FillSettings;
    foreach (var gradientType in gradientTypes)
    {
        fillSettings.GradientType = gradientType;
        fillLayer.Update();

        string resultFile = fileName + "_" + gradientType.ToString() + ".png";
        resultFile = resultFile;
        psdImage.Save(resultFile, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### Guarda anche

* enum [GradientType](../../gradienttype/)
* class [GradientFillSettings](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientfillsettings/)
* assemblea [Aspose.PSD](../../../)


