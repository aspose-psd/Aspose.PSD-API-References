---
title: Enum SampleRoundingMode
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Jpeg.SampleRoundingMode 열거형. n비트 값이 8비트 값으로 변환되는 방식을 정의합니다.
type: docs
weight: 1530
url: /ko/net/aspose.psd.fileformats.jpeg/sampleroundingmode/
---
## SampleRoundingMode enumeration

n비트 값이 8비트 값으로 변환되는 방식을 정의합니다.

```csharp
public enum SampleRoundingMode
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Extrapolate | `0` | 8비트 값을 외삽하여 n비트에 맞춥니다. 여기서 1 &lt; n &lt; 8. 가능한 모든 8비트 값의 수는 1 &lt;&lt; 8 = 256, 0에서 255까지입니다. n비트 값은 1 &lt;&lt; n, 0에서 (1 &lt;&lt; n) - 1. 일부 8비트 값 V8에 해당하는 가장 합리적인 n비트 값 Vn은 Vn = V8 &gt;&gt; (8 - N). |
| Truncate | `1` | 8비트 값을 잘라 n비트에 맞춥니다. 여기서 1 &lt; n &lt; 8. 가능한 모든 n비트 값의 수는 0에서 (1 &lt;&lt; n) - 1. 까지 1 &lt;&lt; n입니다. 일부 8비트 값 V8에 해당하는 가장 합리적인 n비트 값 Vn은 Vn = V8 &amp; ((1 &lt;&lt; n) - 1). |

### 또한보십시오

* 네임스페이스 [Aspose.PSD.FileFormats.Jpeg](../../aspose.psd.fileformats.jpeg/)
* 집회 [Aspose.PSD](../../)


