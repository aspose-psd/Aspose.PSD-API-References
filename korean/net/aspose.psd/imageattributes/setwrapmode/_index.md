---
title: "ImageAttributes.SetWrapMode"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "ImageAttributes 메서드. 텍스처를 도형 전체 또는 도형 경계에 타일링하는 방식을 결정하는 랩 모드를 설정합니다. 텍스처가 채우려는 도형보다 작을 경우 텍스처가 도형 전체에 타일링되어 채워집니다."
type: docs
weight: 210
url: /ko/net/aspose.psd/imageattributes/setwrapmode/
---
{{< psd/tize >}}
## SetWrapMode(WrapMode) {#setwrapmode}

텍스처를 도형 전체 또는 도형 경계에 타일링하는 방식을 결정하는 랩 모드를 설정합니다. 텍스처가 도형보다 작을 경우, 텍스처가 도형을 채우도록 타일링됩니다.

```csharp
public void SetWrapMode(WrapMode mode)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mode | WrapMode | 이미지의 반복 복사본을 사용하여 영역을 타일링하는 방식을 지정하는 [`WrapMode`](../../wrapmode/) 요소입니다. |

### 또 보기

* enum [WrapMode](../../wrapmode/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color) {#setwrapmode_1}

텍스처를 도형 전체 또는 도형 경계에 타일링하는 방식을 결정하는 랩 모드와 색상을 설정합니다. 텍스처가 도형보다 작을 경우, 텍스처가 도형을 채우도록 타일링됩니다.

```csharp
public void SetWrapMode(WrapMode mode, Color color)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mode | WrapMode | 이미지의 반복 복사본을 사용하여 영역을 타일링하는 방식을 지정하는 [`WrapMode`](../../wrapmode/) 요소입니다. |
| color | Color | `[`ImageAttributes`](../)` 객체는 렌더링된 이미지 외부의 픽셀 색상을 지정합니다. 모드 매개변수가 Clamp로 설정되고 DrawImage에 전달된 소스 사각형이 이미지 자체보다 클 경우 이 색상이 표시됩니다. |

### 또 보기

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color, bool) {#setwrapmode_2}

텍스처를 도형 전체 또는 도형 경계에 타일링하는 방식을 결정하는 랩 모드와 색상을 설정합니다. 텍스처가 도형보다 작을 경우, 텍스처가 도형을 채우도록 타일링됩니다.

```csharp
public void SetWrapMode(WrapMode mode, Color color, bool clamp)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mode | WrapMode | 이미지의 반복 복사본을 사용하여 영역을 타일링하는 방식을 지정하는 [`WrapMode`](../../wrapmode/) 요소입니다. |
| 색상 | 색상 | 렌더링된 이미지 외부의 픽셀 색상을 지정하는 색상 객체입니다. 모드 매개변수가 Clamp로 설정되고 DrawImage에 전달된 소스 사각형이 이미지 자체보다 클 경우 이 색상이 표시됩니다. |
| 클램프 | Boolean | 이 매개변수는 영향을 주지 않습니다. false 로 설정하십시오. |

### 또 보기

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


