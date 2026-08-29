---
title: "Layer.ApplyLayerMask"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Metodo Layer. Applica la maschera del livello al livello e poi elimina la maschera"
type: docs
weight: 350
url: /it/net/aspose.psd.fileformats.psd.layers/layer/applylayermask/
---
{{< psd/tize >}}
## Layer.ApplyLayerMask method

Applica la maschera di livello al livello, quindi elimina la maschera.

```csharp
public void ApplyLayerMask()
```

## Esempi

Il codice seguente dimostra la funzionalità di applicare la maschera al livello.

```csharp
[C#]

var sourceFile = "example.psd";
var outFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions()))
{
    psdImage.Layers[1].ApplyLayerMask();

    psdImage.Save(outFile, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Vedi anche

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


