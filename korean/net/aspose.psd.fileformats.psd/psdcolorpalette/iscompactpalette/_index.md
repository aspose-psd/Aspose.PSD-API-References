---
title: "PsdColorPalette.IsCompactPalette"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "PsdColorPalette 속성. 팔레트가 컴팩트인지 여부를 나타내는 값을 가져옵니다"
type: docs
weight: 70
url: /ko/net/aspose.psd.fileformats.psd/psdcolorpalette/iscompactpalette/
---
{{< psd/tize >}}
## PsdColorPalette.IsCompactPalette property

컴팩트된 팔레트인지 여부를 나타내는 값을 가져옵니다.

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true`이면 팔레트가 컴팩트이며, 그렇지 않으면 `false`.

## 비고

압축 팔레트는 이미지가 가능한 경우 지정된 팔레트 항목만 포함한다는 의미이며, 다시 말해 이미지가 더 압축되어 차지하는 공간이 적어집니다; 그렇지 않으면 2^BitsPerPixel 개의 항목이 존재하고 이미지가 모든 가능한 팔레트 항목을 위해 더 많은 공간을 예약합니다. 이 값을 `true` 로 설정하고 팔레트 항목을 변경하면 데이터 이동이 발생할 수 있어 성능 저하가 발생할 수 있으므로 주의해서 사용하십시오.

### 또 보기

* class [PsdColorPalette](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


