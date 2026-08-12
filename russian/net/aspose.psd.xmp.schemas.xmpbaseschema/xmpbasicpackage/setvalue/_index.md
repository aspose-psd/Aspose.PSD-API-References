---
title: "XmpBasicPackage.SetValue"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод XmpBasicPackage. Устанавливает значение"
type: docs
weight: 120
url: /ru/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/setvalue/
---
{{< psd/tize >}}
## XmpBasicPackage.SetValue method

Устанавливает значение.

```csharp
public override void SetValue(string key, IXmlValue value)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| ключ | String | Строковое представление ключа, идентифицируемого добавленным значением. |
| значение | IXmlValue | Значение, которое нужно добавить. |

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

* interface [IXmlValue](../../../aspose.psd.xmp/ixmlvalue/)
* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


