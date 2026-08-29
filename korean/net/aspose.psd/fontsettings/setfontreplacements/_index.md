---
title: "FontSettings.SetFontReplacements"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "FontSettings 메서드. 글꼴 교체 목록을 설정합니다. 글꼴이 허용되지 않은 경우 교체 글꼴을 찾습니다. 목록의 첫 번째 글꼴이 먼저 사용됩니다. 해당 글꼴도 제한된 경우 목록에서 다음 글꼴이 선택됩니다. 글꼴에 교체 항목이 없거나 모든 교체 글꼴이 허용되지 않으면 허용된 글꼴 목록에서 첫 번째 허용 글꼴이 사용됩니다. 허용되고 사용 가능한 글꼴이 없으면 라이브러리는 시스템 기본 글꼴을 사용하려 시도합니다(허용되지 않더라도)."
type: docs
weight: 130
url: /ko/net/aspose.psd/fontsettings/setfontreplacements/
---
{{< psd/tize >}}
## FontSettings.SetFontReplacements method

글꼴 교체 목록을 설정합니다. 글꼴이 허용되지 않으면 교체 글꼴을 찾습니다. 목록의 첫 번째 글꼴이 먼저 사용됩니다. 그것도 제한된 경우 목록에서 다음 글꼴이 선택됩니다. 글꼴에 교체가 없거나 모든 교체가 허용되지 않으면 허용된 글꼴 목록에서 첫 번째 허용된 글꼴이 사용됩니다. 허용되고 사용 가능한 글꼴이 없으면 라이브러리는 허용되지 않더라도 시스템 기본 글꼴을 사용하려고 시도합니다.

```csharp
public static void SetFontReplacements(string fontToReplace, string[] fontNames)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fontToReplace | String | 교체할 글꼴. |
| fontNames | String[] | 유사도 순서대로 나열된 교체 글꼴 이름. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | Font 배열과 Font Differences 배열의 길이는 동일해야 합니다. |

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


