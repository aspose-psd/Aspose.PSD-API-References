---
title: "XmpBasicPackage.Item"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство XmpBasicPackage. Получает или задает объект с указанным ключом"
type: docs
weight: 20
url: /ru/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/item/
---
{{< psd/tize >}}
## XmpBasicPackage indexer

Получает или задает объект с указанным ключом.

```csharp
public override object this[string key] { get; set; }
```

| Параметр | Описание |
| --- | --- |
| ключ | Ключ, который идентифицирует значение. |

### Возвращаемое значение

Возвращает объект с указанным ключом.

### Property Value

Объект.

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

* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


