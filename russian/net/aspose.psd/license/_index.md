---
title: "Класс License"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.License. Предоставляет методы для лицензирования компонента."
type: docs
weight: 5540
url: /ru/net/aspose.psd/license/
---
{{< psd/tize >}}
## License class

Предоставляет методы лицензирования компонента.

```csharp
public class License
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [License](license/)() | Инициализирует новый экземпляр этого класса. |

## Методы

| Имя | Описание |
| --- | --- |
| [SetLicense](../../aspose.psd/license/setlicense/#setlicense)(Stream) | Лицензирует компонент. |
| [SetLicense](../../aspose.psd/license/setlicense/#setlicense_1)(string) | Лицензирует компонент. |

## Примеры

В этом примере будет предпринята попытка найти файл лицензии с именем MyLicense.lic в папке, содержащей компонент, в папке, содержащей вызывающую сборку, в папке входной сборки, а затем во встроенных ресурсах вызывающей сборки.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

### См. также

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


