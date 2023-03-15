---
title: PathStructure.Path
second_title: Справочник по Aspose.PSD для .NET API
description: PathStructure свойство. Получает или задает путь.
type: docs
weight: 40
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/path/
---
## PathStructure.Path property

Получает или задает путь.

```csharp
public string Path { get; set; }
```

### Стоимость имущества

Полный путь.

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

* class [PathStructure](../)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.TypeToolInfoStructures](../../pathstructure/)
* сборка [Aspose.PSD](../../../)


