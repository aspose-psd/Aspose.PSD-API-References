---
title: FillLayer.CreateInstance
second_title: Aspose.PSD per riferimento API .NET
description: FillLayer metodo. Crea una nuova istanza diFillLayer classe per tipo di riempimento.
type: docs
weight: 10
url: /it/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/createinstance/
---
## FillLayer.CreateInstance method

Crea una nuova istanza di[`FillLayer`](../) classe per tipo di riempimento.

```csharp
public static FillLayer CreateInstance(FillType fillType)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fillType | FillType | Il tipo di livello di riempimento. |

### Valore di ritorno

Restituisce una nuova istanza di[`FillLayer`](../) classe per tipo di riempimento.

### Esempi

L'esempio seguente mostra come aggiungere il livello di tipo FillLayer in fase di esecuzione.

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

### Guarda anche

* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [FillLayer](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../filllayer/)
* assemblea [Aspose.PSD](../../../)


