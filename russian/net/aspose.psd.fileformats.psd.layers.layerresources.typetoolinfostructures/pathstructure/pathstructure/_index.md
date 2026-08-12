---
title: "PathStructure.PathStructure"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Конструктор PathStructure. Инициализирует новый экземпляр класса PathStructure"
type: docs
weight: 10
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/pathstructure/
---
{{< psd/tize >}}
## PathStructure constructor

Инициализирует новый экземпляр класса [`PathStructure`](../).

```csharp
public PathStructure(ClassID keyName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| keyName | ClassID | Имя ключа. |

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

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../../aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/)
* assembly [Aspose.PSD](../../../)


