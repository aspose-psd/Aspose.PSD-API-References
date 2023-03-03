---
title: Class Metered
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.Metered сорт. Предоставляет методы для установки измеренного ключа.
type: docs
weight: 5120
url: /ru/net/aspose.psd/metered/
---
## Metered class

Предоставляет методы для установки измеренного ключа.

Предоставляет измеряемые методы для интеграции

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
| override [Equals](../../aspose.psd/metered/equals/)(object) | Определяет, является ли указанныйObject , равно этому экземпляру. |
| [SetMeteredKey](../../aspose.psd/metered/setmeteredkey/)(string, string) | Устанавливает лимитированный открытый и закрытый ключ |
| static [GetConsumptionCredit](../../aspose.psd/metered/getconsumptioncredit/)() | Получает потребительский кредит |
| static [GetConsumptionQuantity](../../aspose.psd/metered/getconsumptionquantity/)() | Получает размер файла потребления |

### Примеры

В этом примере будет предпринята попытка установить лимитированный открытый и закрытый ключ

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Смотрите также

* пространство имен [Aspose.PSD](../../aspose.psd/)
* сборка [Aspose.PSD](../../)


