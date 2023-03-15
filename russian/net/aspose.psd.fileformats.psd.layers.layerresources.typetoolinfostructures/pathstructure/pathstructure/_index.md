---
title: PathStructure.PathStructure
second_title: Справочник по Aspose.PSD для .NET API
description: PathStructure строитель. Инициализирует новый экземплярPathStructure класс.
type: docs
weight: 10
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/pathstructure/
---
## PathStructure constructor

Инициализирует новый экземпляр[`PathStructure`](../) класс.

```csharp
public PathStructure(ClassID keyName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| keyName | ClassID | Ключевое имя. |

### Примеры

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

### Смотрите также

* class [ClassID](../../../aspose.psd.fileformats.psd.layers.layerresources/classid/)
* class [PathStructure](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* сборка [Aspose.PSD](../../../)


