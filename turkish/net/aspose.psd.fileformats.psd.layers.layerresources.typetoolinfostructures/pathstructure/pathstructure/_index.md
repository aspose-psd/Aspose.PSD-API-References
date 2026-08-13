---
title: "PathStructure.PathStructure"
second_title: "Aspose.PSD for .NET API Referansı"
description: "PathStructure yapıcı. PathStructure sınıfının yeni bir örneğini başlatır."
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/pathstructure/
---
{{< psd/tize >}}
## PathStructure(ClassID) {#constructor}

[`PathStructure`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public PathStructure(ClassID keyName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| keyName | ClassID | Anahtar adı. |

## Örnekler

Aşağıdaki kod, PathStructure yapısıyla dosya yükleme yeteneğini gösterir.

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### Ayrıca Bakınız

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)

---

## PathStructure(ClassID, string) {#constructor_1}

Bir yol ile [`PathStructure`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public PathStructure(ClassID keyName, string path)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| keyName | ClassID | Anahtar adı. |
| yol | String | Yol dizesi. |

### Ayrıca Bakınız

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


