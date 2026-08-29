---
title: "PsdLoadOptions.AllowNonChangedLayerRepaint"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Proprietà PsdLoadOptions. Ottiene o imposta se conservare i pixel originali del livello durante il rendering se il livello non è stato modificato"
type: docs
weight: 20
url: /it/net/aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowNonChangedLayerRepaint property

Ottiene o imposta se conservare i pixel originali del livello durante il rendering se il livello non è stato modificato.

```csharp
public bool AllowNonChangedLayerRepaint { get; set; }
```

### Property Value

`true` per mantenere i pixel originali dei livelli non modificati; altrimenti, `false`.

## Esempi

Il codice seguente dimostra il nuovo comportamento che impedisce il ridisegno automatico dei livelli prima delle modifiche.

```csharp
[C#]

string srcFile = "psdnet2400.psd";
string output1 = "unchanged-2400.png";
string output2 = "updated-2400.png";

using (var psdImage = (PsdImage)Image.Load(srcFile,
new PsdLoadOptions() { AllowNonChangedLayerRepaint = false /* The new default behaviour */ }))
{
    psdImage.Save(output1, new PngOptions());

    ((TextLayer)psdImage.Layers[1]).TextData.UpdateLayerData();

    psdImage.Save(output2, new PngOptions());
}
```

### Vedi anche

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


