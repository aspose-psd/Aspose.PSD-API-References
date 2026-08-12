---
title: "LmskResource.ColorSpace"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство LmskResource. Возвращает цветовое пространство"
type: docs
weight: 60
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/colorspace/
---
{{< psd/tize >}}
## LmskResource.ColorSpace property

Получает цветовое пространство.

```csharp
public ColorSpace ColorSpace { get; set; }
```

### Property Value

Цветовое пространство.

## Примеры

Следующий код демонстрирует, как изменить параметры отображения маски слоя на 16‑битных изображениях, изменяя свойства LmskResource.

```csharp
[C#]

string sourceFile = "sourceFile.psd";
string outputPsd = "sourceFile_output.psd";

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects are not equal.");
    }
}

// Загрузить 16‑битное изображение.
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    // Найти LmskResource.
    LmskResource lmskResource = new LmskResource();
    foreach (var res in image.GlobalLayerResources)
    {
        if (res is LmskResource)
        {
            lmskResource = (LmskResource)res;
            break;
        }
    }

    // Проверить свойства LmskResource.
    AssertAreEqual(lmskResource.ColorSpace, ColorSpace.RGB);
    AssertAreEqual(lmskResource.ColorComponent1, (ushort)65535);
    AssertAreEqual(lmskResource.ColorComponent2, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent3, (ushort)0);
    AssertAreEqual(lmskResource.ColorComponent4, (ushort)0);
    AssertAreEqual(lmskResource.Opacity, (short)45);
    AssertAreEqual(lmskResource.Flag, (byte)128);

    // Изменить свойства LmskResource.
    lmskResource.ColorSpace = ColorSpace.HSB;
    lmskResource.ColorComponent1 = 7854;
    lmskResource.ColorComponent2 = 10;
    lmskResource.ColorComponent3 = 15484;
    lmskResource.Opacity = 85;

    // Сохранить изображение.
    image.Save(outputPsd);
}
```

### См. также

* enum [ColorSpace](../../../aspose.psd.fileformats.psd.resources.enums/colorspace/)
* class [LmskResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


