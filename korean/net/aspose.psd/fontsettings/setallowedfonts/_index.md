---
title: FontSettings.SetAllowedFonts
second_title: .NET API 참조용 Aspose.PSD
description: FontSettings 방법. 글꼴 목록으로 글꼴 사용을 제한합니다. restriction 전에 실제 글꼴 이름을 확인하세요. restriction 를 제거하려면 허용된 글꼴 목록을 Null로 설정하세요.
type: docs
weight: 100
url: /ko/net/aspose.psd/fontsettings/setallowedfonts/
---
## FontSettings.SetAllowedFonts method

글꼴 목록으로 글꼴 사용을 제한합니다. restriction 전에 실제 글꼴 이름을 확인하세요. restriction 를 제거하려면 허용된 글꼴 목록을 Null로 설정하세요.

```csharp
public static void SetAllowedFonts(string[] fontList)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| fontList | String[] | 글꼴 목록입니다. |

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


