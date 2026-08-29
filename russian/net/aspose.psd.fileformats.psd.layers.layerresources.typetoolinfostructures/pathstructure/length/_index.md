---
title: "PathStructure.Length"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство PathStructure. Возвращает длину OSTypeStructure в байтах"
type: docs
weight: 30
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/
---
{{< psd/tize >}}
## PathStructure.Length property

Получает длину [`OSTypeStructure`](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) в байтах.

```csharp
public override int Length { get; }
```

## Примеры

Следующий код демонстрирует возможность загрузки файла со структурой PathStructure.

```csharp
[C#]

string srcFile = "shirt-color.psd";
string output = "output.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    image.Save(output);
}
```

### См. также

* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


