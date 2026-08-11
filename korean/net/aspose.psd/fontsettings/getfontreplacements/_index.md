---
title: "FontSettings.GetFontReplacements"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "FontSettings 메서드. 글꼴 이름으로 글꼴 교체 배열을 가져옵니다."
type: docs
weight: 60
url: /ko/net/aspose.psd/fontsettings/getfontreplacements/
---
{{< psd/tize >}}
## FontSettings.GetFontReplacements method

글꼴 이름으로 글꼴 교체 배열을 가져옵니다.

```csharp
public static string[] GetFontReplacements(string fontName)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontName | String | 글꼴 이름. |

### 반환 값

제공된 글꼴에 대한 교체 이름 배열

## 예제

다음 코드는 프로그래밍 방식으로 폰트를 제한하는 기능을 보여줍니다.

```csharp
[C#]

string srcFile = "fonts_com_updated.psd";
string output = "etalon_fonts_com_updated.psd.png";

try
{
    var fontList = new string[] { "Courier New", "Webdings", "Bookman Old Style" };
    FontSettings.SetAllowedFonts(fontList);

    var myriadReplacement = new string[] { "Courier New", "Webdings", "Bookman Old Style" };
    var calibriReplacement = new string[] { "Webdings", "Courier New", "Bookman Old Style" };
    var arialReplacement = new string[] { "Bookman Old Style", "Courier New", "Webdings" };
    var timesReplacement = new string[] { "Arial", "NotExistedFont", "Courier New" };

    FontSettings.SetFontReplacements("MyriadPro-Regular", myriadReplacement);
    FontSettings.SetFontReplacements("Calibri", calibriReplacement);
    FontSettings.SetFontReplacements("Arial", arialReplacement);
    FontSettings.SetFontReplacements("Times New Roman", timesReplacement);

    using (PsdImage image = (PsdImage)Image.Load(srcFile,
        new PsdLoadOptions() { AllowNonChangedLayerRepaint = true }))
    {
        image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
finally
{
    FontSettings.SetAllowedFonts(null);
    FontSettings.ClearFontReplacements();
}
```

### 또 보기

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


