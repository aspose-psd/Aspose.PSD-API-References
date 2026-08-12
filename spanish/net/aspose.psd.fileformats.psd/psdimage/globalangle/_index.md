---
title: "PsdImage.GlobalAngle"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "PsdImage propiedad. Obtiene o establece el ángulo global"
type: docs
weight: 100
url: /es/net/aspose.psd.fileformats.psd/psdimage/globalangle/
---
{{< psd/tize >}}
## PsdImage.GlobalAngle property

Obtiene o establece el ángulo global.

```csharp
public int GlobalAngle { get; set; }
```

## Ejemplos

El siguiente código demuestra el soporte de la propiedad PsdImage.GlobalAngle para cambiar el valor del ángulo global.

```csharp
[C#]

// Cuando la propiedad DropShadowEffect.UseGlobalLight es 'true', el objeto DropShadowEffect utiliza el valor del ángulo de la propiedad PsdImage.GlobalAngle.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### Ver también

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


