---
title: "Перечисление ReadOnlyMode"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.ImageLoadOptions.ReadOnlyMode перечисление. Указывает режимы только для чтения, доступные при загрузке PSD‑изображения"
type: docs
weight: 5260
url: /ru/net/aspose.psd.imageloadoptions/readonlymode/
---
{{< psd/tize >}}
## ReadOnlyMode enumeration

Указывает режимы только для чтения, доступные при загрузке изображения PSD.

```csharp
public enum ReadOnlyMode
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| None | `0` | Ограничения только для чтения не применяются. Изображение может быть полностью изменено. |
| Default | `1` | Режим по умолчанию. Изображение полностью только для чтения и не может быть изменено. |
| MetadataEdit | `2` | Позволяет редактировать метаданные изображения, при этом содержимое изображения остаётся только для чтения. |

## Примеры

Продемонстрировано редактирование и сохранение PSD‑метаданных с использованием ReadOnlyMode.MetadataEdit.

```csharp
[C#]

string sourceFile = "psdnet2382.psd";
string outputFile = "output.psd";

string testMetadata = "Updated metadata text";

using (PsdImage psdImage = (PsdImage)Aspose.PSD.Image.Load(sourceFile,
    new PsdLoadOptions() { ReadOnlyType = ReadOnlyMode.MetadataEdit })) // Sets the of ReadOnlyMode to true
{
    AssertAreNotEqual(testMetadata, psdImage.XmpData.Meta.AdobeXmpToolkit);

    // Изменить метаданные в ReadOnlyMode
    psdImage.XmpData.Meta.AdobeXmpToolkit = testMetadata;

    // Сохранить изменённые метаданные в ReadOnlyMode
    psdImage.Save(outputFile);
}

using (PsdImage psdImage = (PsdImage)Aspose.PSD.Image.Load(outputFile)) // Sets the of ReadOnlyMode to true
{
    AssertAreEqual(testMetadata, psdImage.XmpData.Meta.AdobeXmpToolkit);
}

void AssertAreEqual(object expected, object actual)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception("Objects should be equal, but they don't.");
    }
}

void AssertAreNotEqual(object obj1, object obj2)
{
    if (object.Equals(obj1, obj2))
    {
        throw new Exception("Objects should not be equal, but they are equal.");
    }
}
```

### См. также

* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)


