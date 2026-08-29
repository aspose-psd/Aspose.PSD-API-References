---
title: "클래스 TiffDataType"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Tiff.TiffDataType 클래스. TIFF 데이터 유형"
type: docs
weight: 4680
url: /ko/net/aspose.psd.fileformats.tiff/tiffdatatype/
---
{{< psd/tize >}}
## TiffDataType class

tiff 데이터 유형.

```csharp
public abstract class TiffDataType : IComparable
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AlignedDataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/aligneddatasize/) { get; } | 태그 데이터를 저장하기에 12바이트가 부족한 경우를 대비해 추가 데이터 크기(바이트)를 가져옵니다. |
| abstract [Count](../../aspose.psd.fileformats.tiff/tiffdatatype/count/) { get; } | 요소 개수를 가져옵니다. |
| abstract [DataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/datasize/) { get; } | 태그 데이터를 저장하기에 12바이트가 부족한 경우를 대비해 추가 데이터 크기(바이트)를 가져옵니다. |
| [Id](../../aspose.psd.fileformats.tiff/tiffdatatype/id/) { get; } | 태그 ID의 정수 표현을 가져옵니다. |
| [IsValid](../../aspose.psd.fileformats.tiff/tiffdatatype/isvalid/) { get; } | 태그 데이터가 유효한지 여부를 나타내는 값을 가져옵니다. 유효한 태그는 보존될 수 있는 데이터를 포함합니다. 유효하지 않은 태그는 저장될 수 없습니다. |
| [TagId](../../aspose.psd.fileformats.tiff/tiffdatatype/tagid/) { get; } | 태그 ID를 가져옵니다. |
| abstract [TagType](../../aspose.psd.fileformats.tiff/tiffdatatype/tagtype/) { get; } | 태그 유형을 가져옵니다. |
| abstract [Value](../../aspose.psd.fileformats.tiff/tiffdatatype/value/) { get; set; } | 이 데이터 유형이 포함하는 값을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [ReadTag](../../aspose.psd.fileformats.tiff/tiffdatatype/readtag/)(TiffStreamReader, long) | 태그 데이터를 읽습니다. |
| [CompareTo](../../aspose.psd.fileformats.tiff/tiffdatatype/compareto/)(object) | 현재 인스턴스를 동일한 유형의 다른 객체와 비교하고, 현재 인스턴스가 정렬 순서에서 앞에 있는지, 뒤에 있는지, 혹은 같은 위치에 있는지를 나타내는 정수를 반환합니다. |
| virtual [DeepClone](../../aspose.psd.fileformats.tiff/tiffdatatype/deepclone/)() | 이 인스턴스의 깊은 복제본을 수행합니다. |
| override [ToString](../../aspose.psd.fileformats.tiff/tiffdatatype/tostring/)() | 이 인스턴스를 나타내는 문자열을 반환합니다. |
| abstract [WriteAdditionalData](../../aspose.psd.fileformats.tiff/tiffdatatype/writeadditionaldata/)(TiffStreamWriter) | 추가 태그 데이터를 씁니다. |
| [WriteTag](../../aspose.psd.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | 태그 데이터를 씁니다. |

### 또 보기

* namespace [Aspose.PSD.FileFormats.Tiff](../../aspose.psd.fileformats.tiff/)
* assembly [Aspose.PSD](../../)


