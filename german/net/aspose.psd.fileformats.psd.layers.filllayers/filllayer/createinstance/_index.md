---
title: FillLayer.CreateInstance
second_title: Aspose.PSD für .NET-API-Referenz
description: FillLayer methode. Erstellen Sie eine neue Instanz derFillLayer Klasse nach Art der Füllung.
type: docs
weight: 10
url: /de/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/createinstance/
---
## FillLayer.CreateInstance method

Erstellen Sie eine neue Instanz der[`FillLayer`](../) Klasse nach Art der Füllung.

```csharp
public static FillLayer CreateInstance(FillType fillType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fillType | FillType | Der Typ der Füllschicht. |

### Rückgabewert

Gibt eine neue Instanz von zurück[`FillLayer`](../) Klasse nach Art der Füllung.

### Beispiele

Das folgende Beispiel zeigt, wie Sie die Ebene vom Typ FillLayer zur Laufzeit hinzufügen.

```csharp
[C#]

string outputFilePath = "output.psd";

using (var image = new PsdImage(100, 100))
{
    FillLayer colorFillLayer = FillLayer.CreateInstance(FillType.Color);
    colorFillLayer.DisplayName = "Color Fill Layer";
    image.AddLayer(colorFillLayer);

    FillLayer gradientFillLayer = FillLayer.CreateInstance(FillType.Gradient);
    gradientFillLayer.DisplayName = "Gradient Fill Layer";
    image.AddLayer(gradientFillLayer);

    FillLayer patternFillLayer = FillLayer.CreateInstance(FillType.Pattern);
    patternFillLayer.DisplayName = "Pattern Fill Layer";
    patternFillLayer.Opacity = 50;
    image.AddLayer(patternFillLayer);

    image.Save(outputFilePath);
}
```

### Siehe auch

* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [FillLayer](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* Montage [Aspose.PSD](../../../)


