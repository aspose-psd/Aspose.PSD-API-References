---
title: FontSettings.SetFontReplacements
second_title: .NET API 참조용 Aspose.PSD
description: FontSettings 방법. 글꼴 대체 목록을 설정합니다. 글꼴이 허용되지 않으면 대체품을 찾습니다. 목록의 첫 번째 글꼴이 먼저 사용됩니다. 너무 제한되면 목록에서 다음 글꼴이 선택됩니다. 글꼴이 대체되지 않거나 모든 대체가 허용되지 않는 경우 허용된 글꼴 목록에서 첫 번째로 허용된 글꼴이 사용됩니다. 허용되고 사용 가능한 글꼴이 없으면 라이브러리는 허용되지 않는 경우에도 시스템 기본 글꼴을 사용해 보십시오.
type: docs
weight: 110
url: /ko/net/aspose.psd/fontsettings/setfontreplacements/
---
## FontSettings.SetFontReplacements method

글꼴 대체 목록을 설정합니다. 글꼴이 허용되지 않으면 대체품을 찾습니다. 목록의 첫 번째 글꼴이 먼저 사용됩니다. 너무 제한되면 목록에서 다음 글꼴이 선택됩니다. 글꼴이 대체되지 않거나 모든 대체가 허용되지 않는 경우 허용된 글꼴 목록에서 첫 번째로 허용된 글꼴이 사용됩니다. 허용되고 사용 가능한 글꼴이 없으면 라이브러리는 허용되지 않는 경우에도 시스템 기본 글꼴을 사용해 보십시오.

```csharp
public static void SetFontReplacements(string fontToReplace, string[] fontNames)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| fontToReplace | String | 바꿀 글꼴입니다. |
| fontNames | String[] | 유사성 순으로 대체 글꼴 이름입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentException | 글꼴 배열의 길이와 글꼴 차이 배열은 같아야 합니다. |

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


