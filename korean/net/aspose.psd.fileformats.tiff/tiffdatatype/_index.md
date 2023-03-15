---
title: Class TiffDataType
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Tiff.TiffDataType 수업. tiff 데이터 유형입니다.
type: docs
weight: 4210
url: /ko/net/aspose.psd.fileformats.tiff/tiffdatatype/
---
## TiffDataType class

tiff 데이터 유형입니다.

```csharp
public abstract class TiffDataType : IComparable
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AlignedDataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/aligneddatasize/) { get; } | 추가 데이터 크기를 바이트 단위로 가져옵니다(12바이트가 태그 데이터에 맞지 않는 경우). |
| abstract [Count](../../aspose.psd.fileformats.tiff/tiffdatatype/count/) { get; } | 요소 수를 가져옵니다. |
| abstract [DataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/datasize/) { get; } | 추가 데이터 크기를 바이트 단위로 가져옵니다(12바이트가 태그 데이터에 맞지 않는 경우). |
| [Id](../../aspose.psd.fileformats.tiff/tiffdatatype/id/) { get; } | 태그 ID 정수 표현을 가져옵니다. |
| [IsValid](../../aspose.psd.fileformats.tiff/tiffdatatype/isvalid/) { get; } | 태그 데이터가 유효한지 여부를 나타내는 값을 가져옵니다. 유효한 태그에는 보존할 수 있는 데이터가 포함되어 있습니다. 잘못된 태그는 저장할 수 없습니다. |
| [TagId](../../aspose.psd.fileformats.tiff/tiffdatatype/tagid/) { get; } | 태그 ID를 가져옵니다. |
| abstract [TagType](../../aspose.psd.fileformats.tiff/tiffdatatype/tagtype/) { get; } | 태그 유형을 가져옵니다. |
| abstract [Value](../../aspose.psd.fileformats.tiff/tiffdatatype/value/) { get; set; } | 이 데이터 유형에 포함된 값을 가져오거나 설정합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [ReadTag](../../aspose.psd.fileformats.tiff/tiffdatatype/readtag/)(TiffStreamReader, long) | 태그 데이터를 읽습니다. |
| [CompareTo](../../aspose.psd.fileformats.tiff/tiffdatatype/compareto/)(object) | 현재 인스턴스를 같은 유형의 다른 개체와 비교하고 현재 인스턴스가 정렬 순서에서 다른 개체보다 앞인지, 뒤인지 또는 같은 위치에 있는지를 나타내는 정수를 반환합니다. |
| virtual [DeepClone](../../aspose.psd.fileformats.tiff/tiffdatatype/deepclone/)() | 이 인스턴스의 전체 복제를 수행합니다. |
| override [ToString](../../aspose.psd.fileformats.tiff/tiffdatatype/tostring/)() | 반환String 이 instance. 를 나타냅니다. |
| abstract [WriteAdditionalData](../../aspose.psd.fileformats.tiff/tiffdatatype/writeadditionaldata/)(TiffStreamWriter) | 추가 태그 데이터를 씁니다. |
| [WriteTag](../../aspose.psd.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | 태그 데이터를 씁니다. |

### 또한보십시오

* 네임스페이스 [Aspose.PSD.FileFormats.Tiff](../../aspose.psd.fileformats.tiff/)
* 집회 [Aspose.PSD](../../)


