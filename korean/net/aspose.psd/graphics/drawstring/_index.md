---
title: Graphics.DrawString
second_title: .NET API 참조용 Aspose.PSD
description: Graphics 방법. 지정된 텍스트 문자열을 지정된 위치에 지정된Brush 그리고Font 객체.
type: docs
weight: 320
url: /ko/net/aspose.psd/graphics/drawstring/
---
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

지정된 텍스트 문자열을 지정된 위치에 지정된[`Brush`](../../brush/) 그리고[`Font`](../../font/) 객체.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| s | String | 그릴 문자열입니다. |
| font | Font | [`Font`](../../font/) 문자열의 텍스트 형식을 정의합니다. |
| brush | Brush | [`Brush`](../../brush/) 그려진 텍스트의 색상과 질감을 결정합니다. |
| x | Single | 그려진 텍스트의 왼쪽 위 모퉁이의 x 좌표입니다. |
| y | Single | 그려진 텍스트의 왼쪽 위 모퉁이의 y 좌표입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | *brush* null입니다. -또는- *s* null입니다. |

### 또한보십시오

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [Graphics](../)
* 네임스페이스 [Aspose.PSD](../../graphics/)
* 집회 [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

지정된 텍스트 문자열을 지정된 위치에 지정된[`Brush`](../../brush/) 그리고[`Font`](../../font/) 객체.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| s | String | 그릴 문자열입니다. |
| font | Font | [`Font`](../../font/) 문자열의 텍스트 형식을 정의합니다. |
| brush | Brush | [`Brush`](../../brush/) 그려진 텍스트의 색상과 질감을 결정합니다. |
| point | PointF | [`PointF`](../../pointf/) 그려진 텍스트의 왼쪽 위 모서리를 지정하는 구조입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | *brush* null입니다. -또는- *s* null입니다. |

### 예

이 예제는 Font 및 SolidBrush 클래스를 사용하여 이미지 표면에 문자열을 그리는 방법을 보여줍니다. 이 예에서는 Figures 및 GraphicsPath를 사용하여 새 이미지를 만들고 도형을 그립니다.

```csharp
[C#]

//이미지 인스턴스 생성
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    // Graphics 클래스의 인스턴스 생성 및 초기화
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //그래픽 표면을 지웁니다.
    graphics.Clear(Color.Wheat);

    //Font 인스턴스 생성
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //빨간색을 갖는 SolidBrush의 인스턴스 생성
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //문자열 그리기
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // 내보내기 옵션을 만듭니다.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // 모든 변경 사항 저장
    image.Save("C:\\temp\\output.gif", options);
}
```

### 또한보십시오

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* 네임스페이스 [Aspose.PSD](../../graphics/)
* 집회 [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

지정된 텍스트 문자열을 지정된 위치에 지정된[`Brush`](../../brush/) 그리고[`Font`](../../font/) 지정된 서식 속성을 사용하는 개체[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| s | String | 그릴 문자열입니다. |
| font | Font | [`Font`](../../font/) 문자열의 텍스트 형식을 정의합니다. |
| brush | Brush | [`Brush`](../../brush/) 그려진 텍스트의 색상과 질감을 결정합니다. |
| x | Single | 그려진 텍스트의 왼쪽 위 모퉁이의 x 좌표입니다. |
| y | Single | 그려진 텍스트의 왼쪽 위 모퉁이의 y 좌표입니다. |
| format | StringFormat | [`StringFormat`](../../stringformat/) 그려진 텍스트에 적용되는 줄 간격 및 정렬과 같은 서식 속성을 지정합니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | *brush* null입니다. -또는- *s* null입니다. |

### 또한보십시오

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* 네임스페이스 [Aspose.PSD](../../graphics/)
* 집회 [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

지정된 텍스트 문자열을 지정된 위치에 지정된[`Brush`](../../brush/) 그리고[`Font`](../../font/) 지정된 서식 속성을 사용하는 개체[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| s | String | 그릴 문자열입니다. |
| font | Font | [`Font`](../../font/) 문자열의 텍스트 형식을 정의합니다. |
| brush | Brush | [`Brush`](../../brush/) 그려진 텍스트의 색상과 질감을 결정합니다. |
| point | PointF | [`PointF`](../../pointf/) 그려진 텍스트의 왼쪽 위 모서리를 지정하는 구조입니다. |
| format | StringFormat | [`StringFormat`](../../stringformat/) 그려진 텍스트에 적용되는 줄 간격 및 정렬과 같은 서식 속성을 지정합니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | *brush* null입니다. -또는- *s* null입니다. |

### 또한보십시오

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* 네임스페이스 [Aspose.PSD](../../graphics/)
* 집회 [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

지정된 사각형에 지정된 텍스트 문자열을 지정된[`Brush`](../../brush/) 그리고[`Font`](../../font/) 객체.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| s | String | 그릴 문자열입니다. |
| font | Font | [`Font`](../../font/) 문자열의 텍스트 형식을 정의합니다. |
| brush | Brush | [`Brush`](../../brush/) 그려진 텍스트의 색상과 질감을 결정합니다. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) 그려진 텍스트의 위치를 지정하는 구조입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | *brush* null입니다. -또는- *s* null입니다. |

### 또한보십시오

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* 네임스페이스 [Aspose.PSD](../../graphics/)
* 집회 [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

지정된 사각형에 지정된 텍스트 문자열을 지정된[`Brush`](../../brush/) 그리고[`Font`](../../font/) 지정된 서식 속성을 사용하는 개체[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| s | String | 그릴 문자열입니다. |
| font | Font | [`Font`](../../font/) 문자열의 텍스트 형식을 정의합니다. |
| brush | Brush | [`Brush`](../../brush/) 그려진 텍스트의 색상과 질감을 결정합니다. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) 그려진 텍스트의 위치를 지정하는 구조입니다. |
| format | StringFormat | [`StringFormat`](../../stringformat/) 그려진 텍스트에 적용되는 줄 간격 및 정렬과 같은 서식 속성을 지정합니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | *brush* null입니다. -또는- *s* null입니다. -또는- *brush* null입니다. |

### 또한보십시오

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* 네임스페이스 [Aspose.PSD](../../graphics/)
* 집회 [Aspose.PSD](../../../)


