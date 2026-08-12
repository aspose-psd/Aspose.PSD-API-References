---
title: "Color.FromArgb"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод Color. Создаёт структуру Color из 32‑битного значения ARGB"
type: docs
weight: 1430
url: /ru/net/aspose.psd/color/fromargb/
---
{{< psd/tize >}}
## FromArgb(int) {#fromargb}

Создаёт структуру [`Color`](../) из 32‑битного значения ARGB.

```csharp
public static Color FromArgb(int argb)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| argb | Int32 | Значение, указывающее 32‑битное значение ARGB. |

### Возвращаемое значение

Структура [`Color`](../), создаваемая этим методом.

### См. также

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

Создаёт структуру [`Color`](../) из четырёх значений компонентов ARGB (alpha, red, green и blue). Хотя этот метод позволяет передавать 32‑битное значение для каждого компонента, значение каждого компонента ограничено 8 битами.

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| alpha | Int32 | Компонент alpha. Допустимые значения от 0 до 255. |
| красный | Int32 | Компонент red. Допустимые значения от 0 до 255. |
| зеленый | Int32 | Компонент green. Допустимые значения от 0 до 255. |
| синий | Int32 | Компонент blue. Допустимые значения от 0 до 255. |

### Возвращаемое значение

[`Color`](../), создаваемый этим методом.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | *alpha*, *red*, *green* или *blue* меньше 0 или больше 255. |

### См. также

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

Создает структуру [`Color`](../) из указанной структуры [`Color`](../), но с новым указанным альфа‑значением. Хотя этот метод позволяет передать 32‑битное значение для альфа‑значения, значение ограничено 8 битами.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| alpha | Int32 | Альфа‑значение для нового [`Color`](../). Допустимые значения от 0 до 255. |
| baseColor | Color | [`Color`](../), из которой создаётся новый [`Color`](../). |

### Возвращаемое значение

[`Color`](../), создаваемый этим методом.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* меньше 0 или больше 255. |

### См. также

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

Создает структуру [`Color`](../) из указанных 8‑битных значений цвета (red, green и blue). Значение альфа подразумевается как 255 (полностью непрозрачное). Хотя этот метод позволяет передать 32‑битное значение для каждого компонента цвета, значение каждого компонента ограничено 8 битами.

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| red | Int32 | Значение красного компонента для нового [`Color`](../). Допустимые значения от 0 до 255. |
| green | Int32 | Значение зелёного компонента для нового [`Color`](../). Допустимые значения от 0 до 255. |
| blue | Int32 | Значение синего компонента для нового [`Color`](../). Допустимые значения от 0 до 255. |

### Возвращаемое значение

[`Color`](../), создаваемый этим методом.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | *red*, *green* или *blue* меньше 0 или больше 255. |

### См. также

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


