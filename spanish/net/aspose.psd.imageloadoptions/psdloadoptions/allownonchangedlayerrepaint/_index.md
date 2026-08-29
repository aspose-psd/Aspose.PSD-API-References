---
title: "PsdLoadOptions.AllowNonChangedLayerRepaint"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad PsdLoadOptions. Obtiene o establece si se deben preservar los píxeles originales de la capa durante el renderizado cuando la capa no ha sido modificada"
type: docs
weight: 20
url: /es/net/aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowNonChangedLayerRepaint property

Obtiene o establece si se deben conservar los píxeles originales de la capa durante el renderizado cuando la capa no ha sido modificada.

```csharp
public bool AllowNonChangedLayerRepaint { get; set; }
```

### Property Value

`true` para mantener los píxeles originales de las capas sin cambios; de lo contrario, `false`.

## Ejemplos

El siguiente código demuestra el nuevo comportamiento que evita el repintado automático de capas antes de los cambios.

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

### Ver también

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


