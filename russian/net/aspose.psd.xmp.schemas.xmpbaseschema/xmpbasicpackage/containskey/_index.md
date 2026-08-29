---
title: "XmpBasicPackage.ContainsKey"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод XmpBasicPackage. Определяет, содержит ли указанный ключ"
type: docs
weight: 40
url: /ru/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/containskey/
---
{{< psd/tize >}}
## XmpBasicPackage.ContainsKey method

Определяет, содержит ли указанный ключ ключ.

```csharp
public override bool ContainsKey(string key)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | String | Ключ, который нужно проверить. |

### Возвращаемое значение

Возвращает true, если указанный ключ содержит ключ.

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


