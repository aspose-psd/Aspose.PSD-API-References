---
title: Layer.IsVisible
second_title: Aspose.PSD per riferimento API .NET
description: Layer proprietà. Ottiene o imposta un valore che indica se il livello è visibile
type: docs
weight: 170
url: /it/net/aspose.psd.fileformats.psd.layers/layer/isvisible/
---
## Layer.IsVisible property

Ottiene o imposta un valore che indica se il livello è visibile

```csharp
public bool IsVisible { get; set; }
```

### Valore della proprietà

`VERO` se questa istanza è visibile; Altrimenti,`falso` .

### Esempi

L'esempio seguente mostra come modificare la visibilità di LayerGroup in Aspose.PSD

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// apportare modifiche ai nomi dei livelli e salvarlo
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // Disattiva tutto all'interno di un gruppo
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

### Guarda anche

* class [Layer](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* assemblea [Aspose.PSD](../../../)


