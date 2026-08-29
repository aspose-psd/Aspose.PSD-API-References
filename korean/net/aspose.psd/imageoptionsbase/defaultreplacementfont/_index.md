---
title: "ImageOptionsBase.DefaultReplacementFont"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "ImageOptionsBase 속성. 시스템에 존재하지 않는 PSD 파일의 레이어 폰트가 없을 경우 래스터로 내보낼 때 텍스트를 그리기 위해 사용되는 기본 대체 폰트를 가져오거나 설정합니다. 기본 폰트 이름을 얻으려면 다음 코드 스니펫을 사용할 수 있습니다 System.Drawing.Text.InstalledFontCollection col  new System.Drawing.Text.InstalledFontCollection System.Drawing.FontFamily families  col.Families string defaultFontName  families0.Name PsdLoadOptions psdLoadOptions  new PsdLoadOptions  DefaultReplacementFont  defaultFontName"
type: docs
weight: 20
url: /ko/net/aspose.psd/imageoptionsbase/defaultreplacementfont/
---
{{< psd/tize >}}
## ImageOptionsBase.DefaultReplacementFont property

기본 대체 폰트를 가져오거나 설정합니다 (PSD 파일의 기존 레이어 폰트가 시스템에 없을 경우 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 폰트). 기본 폰트의 올바른 이름을 가져오려면 다음 코드 스니펫을 사용할 수 있습니다: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName });

```csharp
public virtual string DefaultReplacementFont { get; set; }
```

### Property Value

기본 대체 폰트.

## 예제

다음 예제는 DefaultReplacementFont 속성을 사용하여 기본 대체 폰트를 변경하는 방법을 보여줍니다.

```csharp
[C#]

// Konstanting 폰트를 설치하지 마세요, 이 테스트는 설치되지 않은 폰트를 교체해야 하기 때문입니다.
string sourceFileName = "sample_konstanting.psd";

string[] outputs = new string[]
{
    "replacedfont0.tiff",
    "replacedfont1.png",
    "replacedfont2.jpg"
};

using (PsdImage image = (PsdImage)Image.Load(sourceFileName, new PsdLoadOptions() { AllowNonChangedLayerRepaint = true }))
{
    // 이렇게 하면 다양한 출력에 대해 서로 다른 폰트를 사용할 수 있습니다.
    image.Save(outputs[0], new TiffOptions(TiffExpectedFormat.TiffJpegRgb) { DefaultReplacementFont = "Arial" });
    image.Save(outputs[1], new PngOptions { DefaultReplacementFont = "Verdana" });
    image.Save(outputs[2], new JpegOptions { DefaultReplacementFont = "Times New Roman" });
}
```

### 또 보기

* class [ImageOptionsBase](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


