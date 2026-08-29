---
title: "Region.Equals"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод Region. Проверяет, идентичен ли указанный Region этому Region на указанной поверхности рисования"
type: docs
weight: 40
url: /ru/net/aspose.psd/region/equals/
---
{{< psd/tize >}}
## Equals(Region, Graphics) {#equals}

Проверяет, идентичен ли указанный [`Region`](../) данному [`Region`](../) на указанной поверхности рисования.

```csharp
public bool Equals(Region region, Graphics g)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| region | Region | [`Region`](../) для тестирования. |
| g | Graphics | Объект [`Graphics`](../../graphics/) представляет поверхность рисования. |

### Возвращаемое значение

True, если внутреннее пространство region идентично внутреннему пространству данного region при применении преобразования, связанного с параметром *g*; иначе — false.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | *g *or* region* равен null. |

### См. также

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Equals(object) {#equals_1}

Проверьте, равны ли объекты.

```csharp
public override bool Equals(object obj)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | Object | Другой объект. |

### Возвращаемое значение

Результат сравнения на равенство.

### См. также

* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


