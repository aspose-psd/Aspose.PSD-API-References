---
title: FontSettings.GetReplacementFont
second_title: .NET API 참조용 Aspose.PSD
description: FontSettings 방법. 가장 적합한 대체 글꼴을 가져옵니다. 모든 대체가 허용되지 않으면 먼저 허용되고 사용 가능한 글꼴이 반환됩니다. 사용 가능한 글꼴이 없으면 인수 에서 글꼴이 반환됩니다.
type: docs
weight: 70
url: /ko/net/aspose.psd/fontsettings/getreplacementfont/
---
## FontSettings.GetReplacementFont method

가장 적합한 대체 글꼴을 가져옵니다. 모든 대체가 허용되지 않으면 먼저 허용되고 사용 가능한 글꼴이 반환됩니다. 사용 가능한 글꼴이 없으면 인수 에서 글꼴이 반환됩니다.

```csharp
public static string GetReplacementFont(string fontName)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| fontName | String | 글꼴의 이름입니다. |

### 반환 값

교체된 글꼴의 이름

### 예

다음 코드는 다음을 사용하여 프로그래밍 방식으로 글꼴을 제한하는 기능을 보여줍니다.

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

    using (PsdImage image = (PsdImage)Image.Load(srcFile))
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

### 또한보십시오

* class [FontSettings](../)
* 네임스페이스 [Aspose.PSD](../../fontsettings/)
* 집회 [Aspose.PSD](../../../)


