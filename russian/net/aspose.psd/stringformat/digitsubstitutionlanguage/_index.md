---
title: "StringFormat.DigitSubstitutionLanguage"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Свойство StringFormat. Возвращает или задает язык, который используется, когда локальные цифры заменяются западными цифрами."
type: docs
weight: 60
url: /ru/net/aspose.psd/stringformat/digitsubstitutionlanguage/
---
{{< psd/tize >}}
## StringFormat.DigitSubstitutionLanguage property

Получает или задает язык, используемый при замене локальных цифр на западные.

```csharp
public int DigitSubstitutionLanguage { get; set; }
```

### Property Value

Идентификатор языка National Language Support (NLS), который определяет язык, используемый при замене локальных цифр на западные. Вы можете передать свойство LCID объекта CultureInfo в качестве идентификатора языка NLS. Например, предположим, что вы создаёте объект CultureInfo, передавая строку "ar-EG" конструктору CultureInfo. Если вы передадите свойство LCID этого объекта CultureInfo вместе с методом StringDigitSubstitute, то арабо‑индийские цифры будут заменяться на западные цифры во время отображения.

## Примечания

Сеттер введён для устаревшего метода SetDigitSubstitution.

### См. также

* class [StringFormat](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


