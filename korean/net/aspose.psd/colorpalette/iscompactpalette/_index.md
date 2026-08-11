---
title: "ColorPalette.IsCompactPalette"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "ColorPalette 속성. 압축 팔레트를 사용하는지 여부를 나타내는 값을 가져오거나 설정합니다"
type: docs
weight: 60
url: /ko/net/aspose.psd/colorpalette/iscompactpalette/
---
{{< psd/tize >}}
## ColorPalette.IsCompactPalette property

컴팩트 팔레트 사용 여부를 나타내는 값을 가져오거나 설정합니다.

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true` 압축 팔레트를 사용하는 경우; 그렇지 않으면 `false`.

## 비고

압축 팔레트는 이미지가 가능한 경우 지정된 팔레트 항목만 포함한다는 의미이며, 다시 말해 이미지가 더 압축되어 차지하는 공간이 적어집니다; 그렇지 않으면 2^BitsPerPixel 개의 항목이 존재하고 이미지가 모든 가능한 팔레트 항목을 위해 더 많은 공간을 예약합니다. 이 값을 `true` 로 설정하고 팔레트 항목을 변경하면 데이터 이동이 발생할 수 있어 성능 저하가 발생할 수 있으므로 주의해서 사용하십시오.

### 또 보기

* class [ColorPalette](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


