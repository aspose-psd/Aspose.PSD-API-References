---
title: "Layer.BlendClippedElements"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété Layer. Obtient ou définit la fusion de l'élément découpé"
type: docs
weight: 30
url: /fr/net/aspose.psd.fileformats.psd.layers/layer/blendclippedelements/
---
{{< psd/tize >}}
## Layer.BlendClippedElements property

Obtient ou définit la fusion de l'élément découpé.

```csharp
public bool BlendClippedElements { get; set; }
```

### Property Value

La fusion de l'élément découpé.

## Exemples

Le code suivant montre la prise en charge de la propriété BlendClippedElements.

```csharp
[C#]

string sourceFile = "example_source.psd";
string outputPsd = "example_output.psd";
string outputPng = "example_output.png";

using (var image = (PsdImage)Image.Load(sourceFile))
{
    image.Layers[1].BlendClippedElements = false;
    image.Save(outputPsd);
    image.Save(outputPng, new PngOptions());
}
```

### Voir aussi

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


