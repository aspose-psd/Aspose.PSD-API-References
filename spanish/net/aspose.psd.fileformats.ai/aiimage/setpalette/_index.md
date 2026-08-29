---
title: "AiImage.SetPalette"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método AiImage. Establece la paleta de la imagen"
type: docs
weight: 200
url: /es/net/aspose.psd.fileformats.ai/aiimage/setpalette/
---
{{< psd/tize >}}
## AiImage.SetPalette method

Establece la paleta de la imagen.

```csharp
public override void SetPalette(IColorPalette palette, bool updateColors)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| paleta | IColorPalette | La paleta a establecer. |
| updateColors | Boolean | si se establece en `true` los colores se actualizarán según la nueva paleta; de lo contrario, los índices de color permanecerán sin cambios. Tenga en cuenta que los índices sin cambios pueden provocar que la imagen se bloquee al cargar si algunos índices no tienen entradas de paleta correspondientes. |

### Excepciones

| excepción | condición |
| --- | --- |
| NotImplementedException | No implementado |

### Ver también

* interface [IColorPalette](../../../aspose.psd/icolorpalette/)
* class [AiImage](../)
* namespace [Aspose.PSD.FileFormats.Ai](../../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../../)


