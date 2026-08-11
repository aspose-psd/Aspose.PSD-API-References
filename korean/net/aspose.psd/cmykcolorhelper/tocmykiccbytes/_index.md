---
title: "CmykColorHelper.ToCmykIccBytes"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "CmykColorHelper 메서드. 사용자 지정 ICC 프로파일을 사용하여 RGB를 CMYK로 변환합니다"
type: docs
weight: 120
url: /ko/net/aspose.psd/cmykcolorhelper/tocmykiccbytes/
---
{{< psd/tize >}}
## CmykColorHelper.ToCmykIccBytes method

사용자 정의 ICC 프로파일을 사용하여 RGB를 CMYK로 변환합니다.

```csharp
public static byte[] ToCmykIccBytes(int[] pixels, int startIndex, int length, Stream rgbIccStream, 
    Stream cmykIccStream)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 픽셀 | Int32[] | RGB 색상이 32비트 정수 값으로 표시됩니다. |
| startIndex | Int32 | RGB 색상의 시작 인덱스입니다. |
| 길이 | Int32 | 변환할 RGB 픽셀 수입니다. |
| rgbIccStream | 스트림 | RGB 프로파일 스트림입니다. |
| cmykIccStream | 스트림 | CMYK 프로파일 스트림입니다. |

### 반환 값

CMYK 색상이 바이트 배열로 표시됩니다.

### 또 보기

* class [CmykColorHelper](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


