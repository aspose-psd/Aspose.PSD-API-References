---
title: ImageOptionsBase.DefaultReplacementFont
second_title: .NET API 참조용 Aspose.PSD
description: ImageOptionsBase 재산. 기본 대체 글꼴PSD 파일의 기존 레이어 글꼴이 시스템에 표시되지 않는 경우 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 글꼴을 가져오거나 설정합니다. 기본 글꼴의 적절한 이름을 사용하려면 다음 코드 스니펫을 사용할 수 있습니다.  System.Drawing.Text.InstalledFontCollection col  new System.Drawing.Text.InstalledFontCollection System.Drawing.FontFamily families  col.Families string defaultFontName  families0.Name PsdLoadOptions psdLoadOptions  new PsdLoadOptions  DefaultReplacementFont  defaultFontName 
type: docs
weight: 20
url: /ko/net/aspose.psd/imageoptionsbase/defaultreplacementfont/
---
## ImageOptionsBase.DefaultReplacementFont property

기본 대체 글꼴(PSD 파일의 기존 레이어 글꼴이 시스템에 표시되지 않는 경우 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 글꼴)을 가져오거나 설정합니다. 기본 글꼴의 적절한 이름을 사용하려면 다음 코드 스니펫을 사용할 수 있습니다. : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName });

```csharp
public virtual string DefaultReplacementFont { get; set; }
```

### 자산 가치

기본 대체 글꼴입니다.

### 예

다음 예제에서는 DefaultReplacementFont 속성을 사용하여 기본 대체 글꼴을 변경하는 방법을 보여줍니다.

```csharp
[C#]

// 이 테스트는 설치되지 않은 글꼴을 대체해야 하므로 Konstanting 글꼴을 설치하지 마십시오.
string sourceFileName = "sample_konstanting.psd";

string[] outputs = new string[]
{
    "replacedfont0.tiff",
    "replacedfont1.png",
    "replacedfont2.jpg"
};

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions()))
{
    // 이렇게 하면 다른 출력에 다른 글꼴을 사용할 수 있습니다. 
    image.Save(outputs[0], new TiffOptions(TiffExpectedFormat.TiffJpegRgb) { DefaultReplacementFont = "Arial" });
    image.Save(outputs[1], new PngOptions { DefaultReplacementFont = "Verdana" });
    image.Save(outputs[2], new JpegOptions { DefaultReplacementFont = "Times New Roman" });
}
```

### 또한보십시오

* class [ImageOptionsBase](../)
* 네임스페이스 [Aspose.PSD](../../imageoptionsbase/)
* 집회 [Aspose.PSD](../../../)


