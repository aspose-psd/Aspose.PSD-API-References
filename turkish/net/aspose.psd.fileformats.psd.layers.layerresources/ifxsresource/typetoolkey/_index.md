---
title: "IfxsResource.TypeToolKey"
second_title: "Aspose.PSD for .NET API Referansı"
description: "IfxsResource alanı. Tip aracı bilgi anahtarı"
type: docs
weight: 20
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/ifxsresource/typetoolkey/
---
{{< psd/tize >}}
## IfxsResource.TypeToolKey field

Tip aracı bilgi anahtarı.

```csharp
public const int TypeToolKey;
```

## Örnekler

Aşağıdaki kod, IfxsResource desteğini gösterir.

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
    // Örnek, efektli 2 grup katmana sahiptir
    // Bir etkili grup katmanı
    LayerGroup layerGroupOne = (LayerGroup)psdImage.Layers[2];

    // Birden fazla etkili grup katmanı
    LayerGroup layerGroupMany = (LayerGroup)psdImage.Layers[5];

    // Etkilerin sayısını alın ve miktarını doğrulayın
    int effectCountOne = layerGroupOne.BlendingOptions.Effects.Length;
    int effectCountMany = layerGroupMany.BlendingOptions.Effects.Length;

    // Grup katmanındaki bir etki 'IfxsResource' kaynağında bulunur
    IfxsResource ifxsResource = (IfxsResource)layerGroupOne.Resources[0];

    // Grup katmanındaki iki veya daha fazla etki 'ImfxResource' kaynağında bulunur
    ImfxResource imfxResource = (ImfxResource)layerGroupMany.Resources[0];

    // Birden fazla etkisi olan grup katmanına üçüncü bir gölge ekleyin
    layerGroupMany.BlendingOptions.AddDropShadow();

    psdImage.Save(outputFile);
}
```

### Ayrıca Bakınız

* class [IfxsResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


