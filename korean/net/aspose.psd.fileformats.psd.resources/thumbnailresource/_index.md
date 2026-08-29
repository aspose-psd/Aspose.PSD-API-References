---
title: "클래스 ThumbnailResource"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Resources.ThumbnailResource 클래스. 썸네일 리소스 블록"
type: docs
weight: 4380
url: /ko/net/aspose.psd.fileformats.psd.resources/thumbnailresource/
---
{{< psd/tize >}}
## ThumbnailResource class

썸네일 리소스 블록.

```csharp
public class ThumbnailResource : ResourceBlock
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ThumbnailResource](thumbnailresource/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BitsPixel](../../aspose.psd.fileformats.psd.resources/thumbnailresource/bitspixel/) { get; set; } | 비트 픽셀을 가져오거나 설정합니다. |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/thumbnailresource/datasize/) { get; } | 리소스 데이터 크기를 바이트 단위로 가져옵니다. |
| [Format](../../aspose.psd.fileformats.psd.resources/thumbnailresource/format/) { get; set; } | 썸네일 데이터 형식을 가져오거나 설정합니다. |
| [Height](../../aspose.psd.fileformats.psd.resources/thumbnailresource/height/) { get; set; } | 썸네일의 높이를 픽셀 단위로 가져오거나 설정합니다. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | 리소스의 고유 식별자를 가져오거나 설정합니다. |
| [JpegOptions](../../aspose.psd.fileformats.psd.resources/thumbnailresource/jpegoptions/) { get; set; } | JPEG 옵션을 가져오거나 설정합니다. 썸네일 리소스를 JPEG 파일 형식으로만 저장할 때 적합합니다. RAW 형식이 정의된 경우 이 옵션은 영향을 주지 않습니다. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/thumbnailresource/minimalversion/) { get; } | 필요한 최소 PSD 버전을 가져옵니다. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | 리소스 이름을 가져오거나 설정합니다. Pascal 문자열이며, 크기를 짝수로 맞추기 위해 패딩됩니다(널 이름은 0 두 바이트로 구성됩니다). |
| [PlanesCount](../../aspose.psd.fileformats.psd.resources/thumbnailresource/planescount/) { get; set; } | 플레인 수를 가져오거나 설정합니다. |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | 리소스 서명을 가져옵니다. 항상 '8BIM'이어야 합니다. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | 데이터를 포함한 리소스 블록 크기를 바이트 단위로 가져옵니다. |
| [SizeAfterCompression](../../aspose.psd.fileformats.psd.resources/thumbnailresource/sizeaftercompression/) { get; } | 압축 후 크기를 가져오거나 설정합니다. 일관성 검증에 사용됩니다. |
| [ThumbnailArgb32Data](../../aspose.psd.fileformats.psd.resources/thumbnailresource/thumbnailargb32data/) { get; set; } | 32비트 ARGB 썸네일 데이터를 가져오거나 설정합니다. |
| [ThumbnailData](../../aspose.psd.fileformats.psd.resources/thumbnailresource/thumbnaildata/) { get; set; } | 썸네일 데이터를 가져오거나 설정합니다. |
| [TotalSize](../../aspose.psd.fileformats.psd.resources/thumbnailresource/totalsize/) { get; } | 전체 데이터 크기를 가져옵니다. |
| [Width](../../aspose.psd.fileformats.psd.resources/thumbnailresource/width/) { get; set; } | 썸네일의 너비를 픽셀 단위로 가져오거나 설정합니다. |
| [WidthBytes](../../aspose.psd.fileformats.psd.resources/thumbnailresource/widthbytes/) { get; } | 행 너비를 바이트 단위로 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | 지정된 스트림에 리소스 블록을 저장합니다. |
| override [ValidateValues](../../aspose.psd.fileformats.psd.resources/thumbnailresource/validatevalues/)() | 리소스 값을 검증합니다. |

### 또 보기

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


