---
title: PsdOptions.PsdVersion
second_title: .NET API 참조용 Aspose.PSD
description: PsdOptions 재산. 파일 형식 버전을 가져오거나 설정합니다. PSD 또는 PSB일 수 있습니다.
type: docs
weight: 60
url: /ko/net/aspose.psd.imageoptions/psdoptions/psdversion/
---
## PsdOptions.PsdVersion property

파일 형식 버전을 가져오거나 설정합니다. PSD 또는 PSB일 수 있습니다.

```csharp
public PsdVersion PsdVersion { get; set; }
```

### 자산 가치

파일 형식 버전입니다.

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

* enum [PsdVersion](../../../aspose.psd.fileformats.psd/psdversion/)
* class [PsdOptions](../)
* 네임스페이스 [Aspose.PSD.ImageOptions](../../psdoptions/)
* 집회 [Aspose.PSD](../../../)


