---
title: GraphicsPath.Flatten
second_title: Справочник по Aspose.PSD для .NET API
description: GraphicsPath метод. Преобразует каждую кривую на этом пути в последовательность соединенных сегментов линии.
type: docs
weight: 90
url: /ru/net/aspose.psd/graphicspath/flatten/
---
## Flatten() {#flatten}

Преобразует каждую кривую на этом пути в последовательность соединенных сегментов линии.

```csharp
public void Flatten()
```

### Смотрите также

* class [GraphicsPath](../)
* пространство имен [Aspose.PSD](../../graphicspath/)
* сборка [Aspose.PSD](../../../)

---

## Flatten(Matrix) {#flatten_1}

Применяет указанное преобразование, а затем преобразует каждую кривую в этот[`GraphicsPath`](../) в последовательность соединенных отрезков линии.

```csharp
public void Flatten(Matrix matrix)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | Matrix | А[`Matrix`](../../matrix/) с помощью которого можно преобразовать это[`GraphicsPath`](../) перед уплощением. |

### Смотрите также

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* пространство имен [Aspose.PSD](../../graphicspath/)
* сборка [Aspose.PSD](../../../)

---

## Flatten(Matrix, float) {#flatten_2}

Преобразует каждую кривую в этот[`GraphicsPath`](../) в последовательность соединенных отрезков линии.

```csharp
public void Flatten(Matrix matrix, float flatness)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | Matrix | А[`Matrix`](../../matrix/) с помощью которого можно преобразовать это[`GraphicsPath`](../) перед уплощением. |
| flatness | Single | Определяет максимально допустимую ошибку между кривой и ее уплощенной аппроксимацией. По умолчанию используется значение 0,25. Уменьшение значения плоскостности увеличит количество отрезков линии в аппроксимации. |

### Смотрите также

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* пространство имен [Aspose.PSD](../../graphicspath/)
* сборка [Aspose.PSD](../../../)


