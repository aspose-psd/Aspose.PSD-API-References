---
title: PathStructure.Key
second_title: Справочник по Aspose.PSD для .NET API
description: PathStructure свойство. Получает ключ структуры.
type: docs
weight: 20
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/key/
---
## PathStructure.Key property

Получает ключ структуры.

```csharp
public override int Key { get; }
```

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


