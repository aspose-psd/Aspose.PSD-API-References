---
title: FontSettings.IsFontAllowed
second_title: .NET API 참조용 Aspose.PSD
description: FontSettings 방법. 글꼴 허용 여부 지정된 글꼴 이름 여부를 결정합니다.
type: docs
weight: 80
url: /ko/net/aspose.psd/fontsettings/isfontallowed/
---
## FontSettings.IsFontAllowed method

[글꼴 허용 여부] [지정된 글꼴 이름] 여부를 결정합니다.

```csharp
public static bool IsFontAllowed(string fontName)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| fontName | String | 글꼴의 이름입니다. |

### 반환 값

`진실` if [허용된 글꼴] [지정된 글꼴 이름]; 그렇지 않으면,`거짓` .

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


