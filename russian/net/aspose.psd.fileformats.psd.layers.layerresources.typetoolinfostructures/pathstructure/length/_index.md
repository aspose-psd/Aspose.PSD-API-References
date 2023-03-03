---
title: PathStructure.Length
second_title: Справочник по Aspose.PSD для .NET API
description: PathStructure свойство. ПолучаетOSTypeStructure длина в байтах.
type: docs
weight: 30
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/pathstructure/length/
---
## PathStructure.Length property

Получает[`OSTypeStructure`](../../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) длина в байтах.

```csharp
public override int Length { get; }
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


