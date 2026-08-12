---
title: "FillLayer.CreateInstance"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método FillLayer. Crea una nueva instancia de la clase FillLayer según el tipo de relleno."
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/createinstance/
---
{{< psd/tize >}}
## FillLayer.CreateInstance method

Crea una nueva instancia de la clase [`FillLayer`](../) según el tipo de relleno.

```csharp
public static FillLayer CreateInstance(FillType fillType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fillType | FillType | El tipo de capa de relleno. |

### Valor devuelto

Devuelve una nueva instancia de la clase [`FillLayer`](../) según el tipo de relleno.

## Ejemplos

El siguiente ejemplo demuestra cómo agregar la capa de tipo FillLayer en tiempo de ejecución.

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

### Ver también

* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [FillLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)


