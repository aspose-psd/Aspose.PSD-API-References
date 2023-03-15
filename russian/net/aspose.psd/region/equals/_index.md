---
title: Region.Equals
second_title: Справочник по Aspose.PSD для .NET API
description: Region метод. Проверяет указанныйRegion идентичен этомуRegion на указанной поверхности рисования.
type: docs
weight: 40
url: /ru/net/aspose.psd/region/equals/
---
## Region.Equals method

Проверяет, указанный[`Region`](../) идентичен этому[`Region`](../) на указанной поверхности рисования.

```csharp
public bool Equals(Region region, Graphics g)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| region | Region | [`Region`](../) тестировать. |
| g | Graphics | А[`Graphics`](../../graphics/) который представляет собой поверхность для рисования. |

### Возвращаемое значение

Истинно, если внутренняя часть области идентична внутренней части этой области, когда преобразование, связанное с*g*применяется параметр; в противном случае false.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *g *или* region* нулевой. |

### Смотрите также

* class [Graphics](../../graphics/)
* class [Region](../)
* пространство имен [Aspose.PSD](../../region/)
* сборка [Aspose.PSD](../../../)


