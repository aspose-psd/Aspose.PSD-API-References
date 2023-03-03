---
title: MlstResource.Items
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: MlstResource संपत्त. संरचनओं क प्रप्त य सेट करत है
type: docs
weight: 30
url: /hi/net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/items/
---
## MlstResource.Items property

संरचनाओं को प्राप्त या सेट करता है।

```csharp
public OSTypeStructure[] Items { get; }
```

### उदाहरण

निम्न कोड MlstResource संसाधन के समर्थन को प्रदर्शित करता है जो लेयर स्टेट्स में हेरफेर करने के लिए एक निम्न-स्तरीय तंत्र देता है।

```csharp
[C#]

string sourceFile = "image1219.psd";
string outputPsd = "output_image1219.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    Layer layer1 = image.Layers[1];
    ShmdResource shmdResource = (ShmdResource)layer1.Resources[8];
    MlstResource mlstResource = (MlstResource)shmdResource.SubResources[0];

    ListStructure layerStatesList = (ListStructure)mlstResource.Items[1];
    DescriptorStructure layersStateOnFrame1 = (DescriptorStructure)layerStatesList.Types[1];
    BooleanStructure layerEnabled = (BooleanStructure)layersStateOnFrame1.Structures[0];

    // फ़्रेम 1 पर परत 1 को अक्षम करें
    layerEnabled.Value = false;

    image.Save(outputPsd);
}
```

### यह सभी देखें

* class [OSTypeStructure](../../ostypestructure/)
* class [MlstResource](../)
* नाम स्थान [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../mlstresource/)
* सभा [Aspose.PSD](../../../)


