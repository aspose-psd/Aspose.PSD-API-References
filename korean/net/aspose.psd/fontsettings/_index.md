---
title: "클래스 FontSettings"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FontSettings 클래스. 일반 PSD 벡터 형식 렌더러의 글꼴 설정"
type: docs
weight: 4760
url: /ko/net/aspose.psd/fontsettings/
---
{{< psd/tize >}}
## FontSettings class

일반 PSD 벡터 형식 렌더러 글꼴 설정.

```csharp
public static class FontSettings
```

## 속성

| 이름 | 설명 |
| --- | --- |
| static [DefaultFontName](../../aspose.psd/fontsettings/defaultfontname/) { get; set; } | 글꼴의 기본 이름을 가져오거나 설정합니다. |
| static [GetSystemAlternativeFont](../../aspose.psd/fontsettings/getsystemalternativefont/) { get; set; } | [대체 글꼴 가져오기] 여부를 나타내는 값을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [ClearFontReplacements](../../aspose.psd/fontsettings/clearfontreplacements/)() | 모든 글꼴 교체를 지웁니다. |
| static [GetAdobeFontName](../../aspose.psd/fontsettings/getadobefontname/)(string) | 글꼴 패밀리 이름으로 Adobe 글꼴 이름을 가져옵니다. |
| static [GetDefaultFontsFolders](../../aspose.psd/fontsettings/getdefaultfontsfolders/)() | 기본 글꼴 폴더를 가져옵니다. |
| static [GetFontReplacements](../../aspose.psd/fontsettings/getfontreplacements/)(string) | 글꼴 이름으로 글꼴 교체 배열을 가져옵니다. |
| static [GetFontsFolders](../../aspose.psd/fontsettings/getfontsfolders/)() | Aspose.Words가 TrueType 글꼴을 찾는 폴더 목록을 포함하는 배열의 복사본을 가져옵니다. |
| static [GetReplacementFont](../../aspose.psd/fontsettings/getreplacementfont/)(string) | 가장 적합한 교체 글꼴을 가져옵니다. 모든 교체가 허용되지 않으면 첫 번째 허용되고 사용 가능한 글꼴이 반환됩니다. 사용 가능한 글꼴이 없으면 인수로 전달된 글꼴이 반환됩니다. |
| static [IsFontAllowed](../../aspose.psd/fontsettings/isfontallowed/)(string) | [지정된 글꼴 이름]이 허용되는지 여부를 결정합니다. |
| static [RemoveFontCacheFile](../../aspose.psd/fontsettings/removefontcachefile/)() | 글꼴 캐시 파일을 제거합니다. |
| static [Reset](../../aspose.psd/fontsettings/reset/)() | 글꼴 폴더와 기본 글꼴 이름을 시스템 기본값으로 재설정합니다. |
| static [SetAllowedFonts](../../aspose.psd/fontsettings/setallowedfonts/)(string[]) | 글꼴 목록을 사용하여 글꼴 사용을 제한합니다. 제한하기 전에 실제 글꼴 이름을 확인하십시오. 제한을 해제하려면 허용된 글꼴 목록을 Null로 설정하십시오. |
| static [SetFontReplacements](../../aspose.psd/fontsettings/setfontreplacements/)(string, string[]) | 글꼴 교체 목록을 설정합니다. 글꼴이 허용되지 않으면 교체 글꼴을 찾습니다. 목록의 첫 번째 글꼴이 먼저 사용됩니다. 그것도 제한된 경우 목록에서 다음 글꼴이 선택됩니다. 글꼴에 교체가 없거나 모든 교체가 허용되지 않으면 허용된 글꼴 목록에서 첫 번째 허용된 글꼴이 사용됩니다. 허용되고 사용 가능한 글꼴이 없으면 라이브러리는 허용되지 않더라도 시스템 기본 글꼴을 사용하려고 시도합니다. |
| static [SetFontsFolder](../../aspose.psd/fontsettings/setfontsfolder/)(string) | 이는 하나의 글꼴 디렉터리만 설정하기 위한 [`SetFontsFolders`](./setfontsfolders/)에 대한 바로 가기입니다. 글꼴 폴더에 대한 검사는 수행되지 않습니다. |
| static [SetFontsFolders](../../aspose.psd/fontsettings/setfontsfolders/)(string[], bool) | TrueType 글꼴이 로드되는 폴더를 설정하고 로드된 모든 글꼴을 지웁니다. 글꼴 폴더에 대한 검사는 수행되지 않습니다. |
| static [UpdateFonts](../../aspose.psd/fontsettings/updatefonts/)() | 텍스트 레이어가 포함된 PSD 파일에 대한 글꼴 캐시를 업데이트합니다. 이 메서드는 FontSettings.SetFontsFolder(fontsFolder) 메서드를 사용하여 폴더 fontsFolder에서 글꼴을 가져오거나 FontSettings.Reset()으로 글꼴을 재설정한 경우 PSD 파일을 처리할 때 해당 글꼴이 고려되도록 보장합니다. PSD 이미지에 대해 FontSettings.SetFontsFolder(fontsFolder) 또는 FontSettings.Reset()이 호출될 때마다 이 메서드를 사용하십시오. 이 메서드를 호출하지 않으면 글꼴이 업데이트된다는 보장이 없습니다. |

### 또 보기

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


