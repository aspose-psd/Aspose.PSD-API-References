---
title: "Класс Metered"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Класс Aspose.PSD.Metered. Предоставляет методы для установки измеряемого ключа"
type: docs
weight: 5610
url: /ru/net/aspose.psd/metered/
---
{{< psd/tize >}}
## Metered class

Предоставляет методы установки измеряемого ключа.

```csharp
public class Metered
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Metered](metered/)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Equals](../../aspose.psd/metered/equals/)(object) | Определяет, равен ли указанный объект этому экземпляру. |
| [GetProductName](../../aspose.psd/metered/getproductname/)() | Получает название продукта. |
| [SetMeteredKey](../../aspose.psd/metered/setmeteredkey/)(string, string) | Устанавливает публичный и приватный измеряемый ключ. Если вы приобрели измеряемую лицензию, при запуске приложения этот API должен быть вызван, обычно этого достаточно. Однако, если постоянно не удаётся загрузить данные о потреблении и проходит более 24 часов, лицензия будет переключена в статус оценки; чтобы избежать этого, следует регулярно проверять статус лицензии, и если он находится в статусе оценки, вызвать этот API снова. |
| static [GetConsumptionCredit](../../aspose.psd/metered/getconsumptioncredit/)() | Получает кредит потребления |
| static [GetConsumptionQuantity](../../aspose.psd/metered/getconsumptionquantity/)() | Получает размер файла потребления |
| static [IsMeteredLicensed](../../aspose.psd/metered/ismeteredlicensed/)() | Проверяет, лицензирована ли измеряемая лицензия |

## Примеры

В этом примере будет предпринята попытка установить публичный и приватный измеряемый ключ

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### См. также

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


