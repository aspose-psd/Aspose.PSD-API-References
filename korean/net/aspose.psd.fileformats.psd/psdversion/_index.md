---
title: Enum PsdVersion
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.PsdVersion 열거형. 파일 형식 버전
type: docs
weight: 3600
url: /ko/net/aspose.psd.fileformats.psd/psdversion/
---
## PsdVersion enumeration

파일 형식 버전

```csharp
public enum PsdVersion : byte
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Psd | `1` | 기본 PSD 버전입니다. |
| Psb | `2` | PSB 버전입니다. |

### 예

다음 예는 PSD 파일을 PSB로 또는 그 반대로 변환하는 기능을 보여줍니다.

```csharp
[C#]

string sourceFilePathPsb = "2layers.psb";
string outputFilePathPsd = "ConvertFromPsb.psd";
using (Image img = Image.Load(sourceFilePathPsb))
{
    var options = new PsdOptions((PsdImage)img) { PsdVersion = PsdVersion.Psd };
    img.Save(outputFilePathPsd, options);
}

string sourceFilePathPsd = "2layers.psd";
string outputFilePathPsb = "ConvertFromPsd.psb";
using (Image img = Image.Load(sourceFilePathPsd))
{
    var options = new PsdOptions((PsdImage)img) { PsdVersion = PsdVersion.Psb };
    img.Save(outputFilePathPsb, options);
}
```

### 또한보십시오

* 네임스페이스 [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* 집회 [Aspose.PSD](../../)


