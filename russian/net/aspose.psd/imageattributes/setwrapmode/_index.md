---
title: "ImageAttributes.SetWrapMode"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Метод ImageAttributes. Устанавливает режим обтекания, используемый для решения, как заполнять текстуру по фигуре или на её границах. Текстура заполняет фигуру, когда её размер меньше фигуры, которую она заполняет."
type: docs
weight: 210
url: /ru/net/aspose.psd/imageattributes/setwrapmode/
---
{{< psd/tize >}}
## SetWrapMode(WrapMode) {#setwrapmode}

Устанавливает режим обтекания, который используется для определения того, как размещать текстуру по фигуре или на границах фигуры. Текстура размещается по фигуре, заполняя её, когда текстура меньше фигуры, которую она заполняет.

```csharp
public void SetWrapMode(WrapMode mode)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| mode | WrapMode | Элемент [`WrapMode`](../../wrapmode/), который указывает, как повторяющиеся копии изображения используются для заполнения области. |

### См. также

* enum [WrapMode](../../wrapmode/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color) {#setwrapmode_1}

Устанавливает режим обтекания и цвет, используемые для определения того, как размещать текстуру по фигуре или на границах фигуры. Текстура размещается по фигуре, заполняя её, когда текстура меньше фигуры, которую она заполняет.

```csharp
public void SetWrapMode(WrapMode mode, Color color)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| mode | WrapMode | Элемент [`WrapMode`](../../wrapmode/), который указывает, как повторяющиеся копии изображения используются для заполнения области. |
| color | Color | Объект [`ImageAttributes`](../), который задаёт цвет пикселей за пределами отрисованного изображения. Этот цвет виден, если параметр mode установлен в Clamp и исходный прямоугольник, переданный в DrawImage, больше самого изображения. |

### См. также

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color, bool) {#setwrapmode_2}

Устанавливает режим обтекания и цвет, используемые для определения того, как размещать текстуру по фигуре или на границах фигуры. Текстура размещается по фигуре, заполняя её, когда текстура меньше фигуры, которую она заполняет.

```csharp
public void SetWrapMode(WrapMode mode, Color color, bool clamp)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| mode | WrapMode | Элемент [`WrapMode`](../../wrapmode/), который указывает, как повторяющиеся копии изображения используются для заполнения области. |
| color | Color | Объект цвета, который задаёт цвет пикселей за пределами отрисованного изображения. Этот цвет виден, если параметр mode установлен в Clamp и исходный прямоугольник, переданный в DrawImage, больше самого изображения. |
| Clamp | Boolean | Этот параметр не оказывает влияния. Установите его в false. |

### См. также

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


