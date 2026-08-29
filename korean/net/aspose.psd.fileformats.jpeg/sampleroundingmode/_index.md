---
title: "열거형 SampleRoundingMode"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Jpeg.SampleRoundingMode 열거형. n비트 값을 8비트 값으로 변환하는 방식을 정의합니다."
type: docs
weight: 1540
url: /ko/net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---
{{< psd/tize >}}
## SampleRoundingMode enumeration

n비트 값을 8비트 값으로 변환하는 방법을 정의합니다.

```csharp
public enum SampleRoundingMode
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Extrapolate | `0` | 1 < n < 8인 경우 8비트 값을 n비트에 맞게 외삽합니다. 가능한 모든 8비트 값의 수는 1 << 8 = 256이며, 0부터 255까지입니다. 가능한 모든 n비트 값의 수는 1 << n이며, 0부터 (1 << n) - 1까지입니다. 일부 8비트 값 V8에 해당하는 가장 합리적인 n비트 값 Vn은 Vn = V8 >> (8 - n)와 같습니다. |
| Truncate | `1` | 1 < n < 8인 경우 8비트 값을 n비트에 맞게 잘라냅니다. 가능한 모든 n비트 값의 수는 1 << n이며, 0부터 (1 << n) - 1까지입니다. 일부 8비트 값 V8에 해당하는 가장 합리적인 n비트 값 Vn은 Vn = V8 & ((1 << n) - 1)와 같습니다. |

### 또 보기

* namespace [Aspose.PSD.FileFormats.Jpeg](../../aspose.psd.fileformats.jpeg/)
* assembly [Aspose.PSD](../../)


