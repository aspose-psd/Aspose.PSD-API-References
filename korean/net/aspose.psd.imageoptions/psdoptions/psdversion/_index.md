---
title: "PsdOptions.PsdVersion"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "PsdOptions 속성. 파일 형식 버전을 가져오거나 설정합니다. PSD 또는 PSB일 수 있습니다."
type: docs
weight: 70
url: /ko/net/aspose.psd.imageoptions/psdoptions/psdversion/
---
{{< psd/tize >}}
## PsdOptions.PsdVersion property

파일 형식 버전을 가져오거나 설정합니다. PSD 또는 PSB일 수 있습니다.

```csharp
public PsdVersion PsdVersion { get; set; }
```

### Property Value

파일 형식 버전.

## 예제

다음 예제는 PSD 파일을 PSB로, 그리고 그 반대로 변환하는 기능을 보여줍니다.

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

### 또 보기

* enum [PsdVersion](../../../aspose.psd.fileformats.psd/psdversion/)
* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


