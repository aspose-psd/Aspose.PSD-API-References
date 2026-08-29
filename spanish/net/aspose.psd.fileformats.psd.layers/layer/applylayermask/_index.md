---
title: "Layer.ApplyLayerMask"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método Layer. Aplica la máscara de capa a la capa y luego elimina la máscara"
type: docs
weight: 350
url: /es/net/aspose.psd.fileformats.psd.layers/layer/applylayermask/
---
{{< psd/tize >}}
## Layer.ApplyLayerMask method

Aplica la máscara de capa a la capa, luego elimina la máscara.

```csharp
public void ApplyLayerMask()
```

## Ejemplos

El siguiente código demuestra la funcionalidad de aplicar la máscara a la capa.

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

### Ver también

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


