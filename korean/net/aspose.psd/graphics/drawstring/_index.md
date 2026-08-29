---
title: "Graphics.DrawString"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Graphics 메서드. 지정된 Brush와 Font 객체를 사용하여 지정된 위치에 지정된 텍스트 문자열을 그립니다."
type: docs
weight: 330
url: /ko/net/aspose.psd/graphics/drawstring/
---
{{< psd/tize >}}
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

지정된 위치에 지정된 [`Brush`](../../brush/)와 [`Font`](../../font/) 객체를 사용하여 지정된 텍스트 문자열을 그립니다.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | String | 그릴 문자열. |
| font | Font | 문자열의 텍스트 형식을 정의하는 [`Font`](../../font/). |
| brush | Brush | 그려진 텍스트의 색상 및 질감을 결정하는 [`Brush`](../../brush/). |
| x | 단일 | 그려진 텍스트의 왼쪽 위 모서리의 x좌표. |
| y | 단일 | 그려진 텍스트의 왼쪽 위 모서리의 y좌표. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *brush*가 null입니다. -or- *s*가 null입니다. |

### 또 보기

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

지정된 위치에 지정된 [`Brush`](../../brush/)와 [`Font`](../../font/) 객체를 사용하여 지정된 텍스트 문자열을 그립니다.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | String | 그릴 문자열. |
| font | Font | 문자열의 텍스트 형식을 정의하는 [`Font`](../../font/). |
| brush | Brush | 그려진 텍스트의 색상 및 질감을 결정하는 [`Brush`](../../brush/). |
| point | PointF | 그려진 텍스트의 왼쪽 위 모서리를 지정하는 [`PointF`](../../pointf/) 구조체. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *brush*가 null입니다. -or- *s*가 null입니다. |

## 예제

이 예제는 Font 및 SolidBrush 클래스를 사용하여 Image 표면에 문자열을 그리는 방법을 보여줍니다. 예제는 새 Image를 생성하고 Figures와 GraphicsPath를 사용하여 도형을 그립니다.

```csharp
[C#]

//Image의 인스턴스를 생성합니다.
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics 클래스를 생성하고 초기화합니다.
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics 표면을 지웁니다.
    graphics.Clear(Color.Wheat);

    //Font의 인스턴스를 생성합니다.
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Red 색상을 가진 SolidBrush의 인스턴스를 생성합니다.
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //문자열을 그립니다.
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // 내보내기 옵션을 생성합니다.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // 모든 변경 사항을 저장합니다.
    image.Save("C:\\temp\\output.gif", options);
}
```

### 또 보기

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

지정된 [`StringFormat`](../../stringformat/)의 서식 속성을 사용하여 지정된 위치에 지정된 [`Brush`](../../brush/)와 [`Font`](../../font/) 객체를 사용해 지정된 텍스트 문자열을 그립니다.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | String | 그릴 문자열. |
| font | Font | 문자열의 텍스트 형식을 정의하는 [`Font`](../../font/). |
| brush | Brush | 그려진 텍스트의 색상 및 질감을 결정하는 [`Brush`](../../brush/). |
| x | 단일 | 그려진 텍스트의 왼쪽 위 모서리의 x좌표. |
| y | 단일 | 그려진 텍스트의 왼쪽 위 모서리의 y좌표. |
| format | StringFormat | 그려진 텍스트에 적용되는 줄 간격 및 정렬과 같은 서식 속성을 지정하는 [`StringFormat`](../../stringformat/). |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *brush*가 null입니다. -or- *s*가 null입니다. |

### 또 보기

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

지정된 [`StringFormat`](../../stringformat/)의 서식 속성을 사용하여 지정된 위치에 지정된 [`Brush`](../../brush/)와 [`Font`](../../font/) 객체를 사용해 지정된 텍스트 문자열을 그립니다.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | String | 그릴 문자열. |
| font | Font | 문자열의 텍스트 형식을 정의하는 [`Font`](../../font/). |
| brush | Brush | 그려진 텍스트의 색상 및 질감을 결정하는 [`Brush`](../../brush/). |
| point | PointF | 그려진 텍스트의 왼쪽 위 모서리를 지정하는 [`PointF`](../../pointf/) 구조체. |
| format | StringFormat | 그려진 텍스트에 적용되는 줄 간격 및 정렬과 같은 서식 속성을 지정하는 [`StringFormat`](../../stringformat/). |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *brush*가 null입니다. -or- *s*가 null입니다. |

### 또 보기

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

지정된 사각형 안에 지정된 [`Brush`](../../brush/)와 [`Font`](../../font/) 객체를 사용하여 지정된 텍스트 문자열을 그립니다.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | String | 그릴 문자열. |
| font | Font | 문자열의 텍스트 형식을 정의하는 [`Font`](../../font/). |
| brush | Brush | 그려진 텍스트의 색상 및 질감을 결정하는 [`Brush`](../../brush/). |
| layoutRectangle | RectangleF | 그려진 텍스트의 위치를 지정하는 [`RectangleF`](../../rectanglef/) 구조체. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *brush*가 null입니다. -or- *s*가 null입니다. |

### 또 보기

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

지정된 [`StringFormat`](../../stringformat/)의 서식 속성을 사용하여 지정된 사각형 안에 지정된 [`Brush`](../../brush/)와 [`Font`](../../font/) 객체를 사용해 지정된 텍스트 문자열을 그립니다.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | String | 그릴 문자열. |
| font | Font | 문자열의 텍스트 형식을 정의하는 [`Font`](../../font/). |
| brush | Brush | 그려진 텍스트의 색상 및 질감을 결정하는 [`Brush`](../../brush/). |
| layoutRectangle | RectangleF | 그려진 텍스트의 위치를 지정하는 [`RectangleF`](../../rectanglef/) 구조체. |
| format | StringFormat | 그려진 텍스트에 적용되는 줄 간격 및 정렬과 같은 서식 속성을 지정하는 [`StringFormat`](../../stringformat/). |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *brush*가 null입니다. -or- *s*가 null입니다. -or- *brush*가 null입니다. |

### 또 보기

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


