---
title: "PsdOptions.UpdateMetadata"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство PsdOptions. Получает или задает значение, указывающее, следует ли обновлять метаданные. Если значение истинно, метаданные будут обновлены при сохранении изображения"
type: docs
weight: 110
url: /ru/net/aspose.psd.imageoptions/psdoptions/updatemetadata/
---
{{< psd/tize >}}
## PsdOptions.UpdateMetadata property

Получает или задает значение, указывающее, следует ли [update metadata]. Если значение истинно, метаданные будут обновлены при сохранении изображения.

```csharp
public bool UpdateMetadata { get; set; }
```

### Property Value

`true` если [update metadata]; иначе, `false`.

## Примеры

Следующий код демонстрирует использование опции UpdateMetadata для обновления значения CreatorTool в данных xmp.

```csharp
[C#]

string path = "output.psd";

using (var image = new PsdImage(100, 100))
{
    // Если вы хотите изменить инструмент создания, убедитесь, что свойство "UpdateMetadata" установлено в true. По умолчанию оно установлено в true.
    var psdOptions = new PsdOptions();
    psdOptions.UpdateMetadata = true;

    // Сохранение изображения. 
    image.Save(path, psdOptions);

    // Проверка инструмента создания в коде.
    var xmpData = image.XmpData;
    var basicPackage = image.XmpData.GetPackage(Namespaces.XmpBasic);

    // Здесь будет обновлена информация об инструменте создания.
    var currentCreatorTool = (string)basicPackage[":CreatorTool"];
}
```

### См. также

* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


