---
title: "TiffStreamReader.ReadUShortArray"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "TiffStreamReader 메서드. 스트림에서 부호 없는 정수 값 배열을 읽습니다."
type: docs
weight: 220
url: /ko/net/aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/readushortarray/
---
{{< psd/tize >}}
## TiffStreamReader.ReadUShortArray method

스트림에서 부호 없는 정수 값 배열을 읽습니다.

```csharp
public ushort[] ReadUShortArray(long position, long count)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 위치 | Int64 | 읽을 위치. |
| count | Int64 | 요소 개수. |

### 반환 값

부호 없는 정수 값 배열입니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentOutOfRangeException | count;전체 바이트 수가 음수입니다. + count + x2= + totalBytes |

### 또 보기

* class [TiffStreamReader](../)
* namespace [Aspose.PSD.FileFormats.Tiff.FileManagement](../../../aspose.psd.fileformats.tiff.filemanagement/)
* assembly [Aspose.PSD](../../../)


