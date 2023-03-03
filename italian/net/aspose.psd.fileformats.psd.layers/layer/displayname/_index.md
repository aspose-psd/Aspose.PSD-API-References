---
title: Layer.DisplayName
second_title: Aspose.PSD per riferimento API .NET
description: Layer proprietà. Ottiene o imposta il nome visualizzato del layer.
type: docs
weight: 100
url: /it/net/aspose.psd.fileformats.psd.layers/layer/displayname/
---
## Layer.DisplayName property

Ottiene o imposta il nome visualizzato del layer.

```csharp
public string DisplayName { get; set; }
```

### Valore della proprietà

Il nome visualizzato del layer.

### Esempi

L'esempio seguente dimostra la possibilità di impostare il valore DisplayName, in cui il nome del livello viene visualizzato correttamente.

```csharp
[C#]

// apportare modifiche ai nomi dei livelli e salvarlo
string sourceFileName = "layers with names.psd";
string output = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];
        // imposta un nuovo valore nella proprietà DisplayName
        layer.DisplayName += "_changed";
    }

    image.Save(output);
}
```

### Guarda anche

* class [Layer](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* assemblea [Aspose.PSD](../../../)


