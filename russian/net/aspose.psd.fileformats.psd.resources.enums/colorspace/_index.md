---
title: "Перечисление ColorSpace"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.FileFormats.Psd.Resources.Enums.ColorSpace enum. Типы цветовых пространств"
type: docs
weight: 4160
url: /ru/net/aspose.psd.fileformats.psd.resources.enums/colorspace/
---
{{< psd/tize >}}
## ColorSpace enumeration

Типы цветовых пространств.

```csharp
public enum ColorSpace : ushort
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| RGB | `0` | Цветовое пространство RGB. |
| HSB | `1` | Цветовое пространство HSB. |
| CMYK | `2` | Цветовое пространство CMYK. |
| Lab | `7` | Цветовое пространство Lab. |
| GrayScale | `8` | Цветовое пространство GrayScale. |

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

* namespace [Aspose.PSD.FileFormats.Psd.Resources.Enums](../../aspose.psd.fileformats.psd.resources.enums/)
* assembly [Aspose.PSD](../../)


