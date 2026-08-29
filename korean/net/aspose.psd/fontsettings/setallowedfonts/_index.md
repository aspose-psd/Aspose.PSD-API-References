---
title: "FontSettings.SetAllowedFonts"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "FontSettings 메서드. 글꼴 목록을 사용하여 글꼴 사용을 제한합니다. 제한하기 전에 실제 글꼴 이름을 확인하십시오. 제한을 해제하려면 허용된 글꼴 목록을 Null로 설정하십시오."
type: docs
weight: 120
url: /ko/net/aspose.psd/fontsettings/setallowedfonts/
---
{{< psd/tize >}}
## FontSettings.SetAllowedFonts method

글꼴 목록을 사용하여 글꼴 사용을 제한합니다. 제한하기 전에 실제 글꼴 이름을 확인하십시오. 제한을 해제하려면 허용된 글꼴 목록을 Null로 설정하십시오.

```csharp
public static void SetAllowedFonts(string[] fontList)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontList | String[] | 글꼴 목록. |

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


