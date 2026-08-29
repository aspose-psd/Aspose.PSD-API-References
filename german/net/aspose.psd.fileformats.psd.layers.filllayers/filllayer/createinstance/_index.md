---
title: "FillLayer.CreateInstance"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "FillLayer-Methode. Erstellt eine neue Instanz der FillLayer-Klasse basierend auf dem Fülltyp."
type: docs
weight: 10
url: /de/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/createinstance/
---
{{< psd/tize >}}
## FillLayer.CreateInstance method

Erstellt eine neue Instanz der [`FillLayer`](../)-Klasse basierend auf dem Fülltyp.

```csharp
public static FillLayer CreateInstance(FillType fillType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fillType | FillType | Der Typ der Füllschicht. |

### Rückgabewert

Gibt eine neue Instanz der [`FillLayer`](../)-Klasse zurück, basierend auf dem Fülltyp.

## Beispiele

Das folgende Beispiel demonstriert, wie man den FillLayer-Typ zur Laufzeit hinzufügt.

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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)


