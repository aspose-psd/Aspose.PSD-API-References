---
title: Class ResolutionInfoResource
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Resources.ResolutionInfoResource 수업. 해상도 정보 resource
type: docs
weight: 3880
url: /ko/net/aspose.psd.fileformats.psd.resources/resolutioninforesource/
---
## ResolutionInfoResource class

해상도 정보 resource

```csharp
public sealed class ResolutionInfoResource : ResourceBlock
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ResolutionInfoResource](resolutioninforesource/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/datasize/) { get; } | 리소스 데이터 크기를 바이트 단위로 가져옵니다. |
| [HDpi](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/hdpi/) { get; set; } | 수평 DPI. |
| [HeightDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/heightdisplayunit/) { get; set; } | 높이 표시 단위를 가져오거나 설정합니다. |
| [HResDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/hresdisplayunit/) { get; set; } | 수평 해상도 단위를 표시합니다. 이는 the 사용자 인터페이스에만 영향을 미칩니다. 해상도는 여전히 PSD 파일 에 픽셀/인치로 저장됩니다. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | 리소스의 고유 식별자를 가져오거나 설정합니다. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/minimalversion/) { get; } | 필요한 최소 PSD 버전을 가져옵니다. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | 리소스 이름을 가져오거나 설정합니다. 파스칼 문자열, 크기를 균일하게 만들기 위해 패딩됨(널 이름은 2바이트의 0으로 구성됨). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | 리소스 서명을 가져옵니다. 항상 '8BIM'이어야 합니다. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | 데이터를 포함하여 리소스 블록 크기를 바이트 단위로 가져옵니다. |
| [VDpi](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/vdpi/) { get; set; } | 세로 DPI. |
| [VResDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/vresdisplayunit/) { get; set; } | 수직 해상도 표시 단위. |
| [WidthDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/widthdisplayunit/) { get; set; } | 너비 표시 단위를 가져오거나 설정합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | 리소스 블록을 지정된 스트림에 저장합니다. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | 리소스 값의 유효성을 검사합니다. |

### 또한보십시오

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* 집회 [Aspose.PSD](../../)


