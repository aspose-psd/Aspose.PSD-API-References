---
title: "GraphicsPath.Flatten"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод GraphicsPath. Преобразует каждую кривую в этом пути в последовательность соединённых отрезков"
type: docs
weight: 90
url: /ru/net/aspose.psd/graphicspath/flatten/
---
{{< psd/tize >}}
## Flatten() {#flatten}

Преобразует каждую кривую в этом пути в последовательность соединённых отрезков.

```csharp
public void Flatten()
```

### См. также

* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Flatten(Matrix) {#flatten_1}

Применяет указанное преобразование, а затем преобразует каждую кривую в этом [`GraphicsPath`](../) в последовательность соединённых отрезков.

```csharp
public void Flatten(Matrix matrix)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | Matrix | [`Matrix`](../../matrix/), которым следует преобразовать этот [`GraphicsPath`](../) перед выравниванием. |

### См. также

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Flatten(Matrix, float) {#flatten_2}

Преобразует каждую кривую в этом [`GraphicsPath`](../) в последовательность соединённых отрезков.

```csharp
public void Flatten(Matrix matrix, float flatness)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | Matrix | [`Matrix`](../../matrix/), которым следует преобразовать этот [`GraphicsPath`](../) перед выравниванием. |
| плоскость | Single | Указывает максимальную допустимую ошибку между кривой и её уплощённым приближением. Значение 0.25 является значением по умолчанию. Уменьшение значения плоскости увеличит количество отрезков в приближении. |

### См. также

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


