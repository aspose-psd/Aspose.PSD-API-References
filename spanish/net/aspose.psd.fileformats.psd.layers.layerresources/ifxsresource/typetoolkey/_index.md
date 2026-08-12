---
title: "IfxsResource.TypeToolKey"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Campo IfxsResource. La clave de información de la herramienta de tipo"
type: docs
weight: 20
url: /es/net/aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/typetoolkey/
---
{{< psd/tize >}}
## IfxsResource.TypeToolKey field

La clave de información de la herramienta de tipo.

```csharp
public const int TypeToolKey;
```

## Ejemplos

El siguiente código demuestra el soporte de IfxsResource.

```csharp
[C#]

string sourceFile = "example.psd";
string outputFile = "export.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true,
};

using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
{
    // El ejemplo tiene 2 capas de grupo con efectos
    // Capa de grupo con un efecto
    LayerGroup layerGroupOne = (LayerGroup)psdImage.Layers[2];

    // Capa de grupo con muchos efectos
    LayerGroup layerGroupMany = (LayerGroup)psdImage.Layers[5];

    // Obtén el número de efectos y verifica su cantidad
    int effectCountOne = layerGroupOne.BlendingOptions.Effects.Length;
    int effectCountMany = layerGroupMany.BlendingOptions.Effects.Length;

    // Un efecto en la capa de grupo está en el recurso 'IfxsResource'
    IfxsResource ifxsResource = (IfxsResource)layerGroupOne.Resources[0];

    // Dos o más efectos en una capa de grupo están en el recurso 'ImfxResource'
    ImfxResource imfxResource = (ImfxResource)layerGroupMany.Resources[0];

    // Agrega una tercera sombra a una capa de grupo con múltiples efectos
    layerGroupMany.BlendingOptions.AddDropShadow();

    psdImage.Save(outputFile);
}
```

### Ver también

* class [IfxsResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


