---
title: "PathStructure.Prefix"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство PathStructure. Получает или задает префикс пути"
type: docs
weight: 50
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/prefix/
---
{{< psd/tize >}}
## PathStructure.Prefix property

Получает или задает префикс пути.

```csharp
public string Prefix { get; set; }
```

### Property Value

Полный путь.

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


