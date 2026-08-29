---
title: "Класс XmpPackage"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Aspose.PSD.Xmp.XmpPackage class. Определяет класс XmpPackage, который представляет базовую абстракцию для пакета XMP"
type: docs
weight: 6770
url: /ru/net/aspose.psd.xmp/xmppackage/
---
{{< psd/tize >}}
## XmpPackage class

Определяет класс XmpPackage, который представляет базовую абстракцию для пакета XMP.

```csharp
public class XmpPackage : IEnumerable<KeyValuePair<string, object>>, IXmlValue
```

## Свойства

| Имя | Описание |
| --- | --- |
| virtual [Item](../../aspose.psd.xmp/xmppackage/item/) { get; set; } | Получает или задает объект с указанным ключом. |
| virtual [Keys](../../aspose.psd.xmp/xmppackage/keys/) { get; } | Получает ключи в пакете XMP. |
| [NamespaceUri](../../aspose.psd.xmp/xmppackage/namespaceuri/) { get; } | Получает URI пространства имен. |
| [Prefix](../../aspose.psd.xmp/xmppackage/prefix/) { get; } | Получает префикс. |
| [XmlNamespace](../../aspose.psd.xmp/xmppackage/xmlnamespace/) { get; } | Получает пространство имен XML. |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [AddValue](../../aspose.psd.xmp/xmppackage/addvalue/)(string, string) | Добавляет значение. |
| virtual [Clear](../../aspose.psd.xmp/xmppackage/clear/)() | Очищает этот экземпляр. |
| virtual [ContainsKey](../../aspose.psd.xmp/xmppackage/containskey/)(string) | Определяет, содержит ли указанный ключ ключ. |
| [GetEnumerator](../../aspose.psd.xmp/xmppackage/getenumerator/)() | Возвращает перечислитель, который перебирает элементы коллекции. |
| virtual [GetXmlValue](../../aspose.psd.xmp/xmppackage/getxmlvalue/)() | Преобразует значение XMP в представление XML. |
| virtual [Remove](../../aspose.psd.xmp/xmppackage/remove/)(string) | Удаляет значение с указанным ключом. |
| virtual [SetValue](../../aspose.psd.xmp/xmppackage/setvalue/)(string, IXmlValue) | Устанавливает значение. |
| virtual [SetXmpTypeValue](../../aspose.psd.xmp/xmppackage/setxmptypevalue/)(string, XmpTypeBase) | Устанавливает значение типа XMP. |

### См. также

* interface [IXmlValue](../ixmlvalue/)
* namespace [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* assembly [Aspose.PSD](../../)


