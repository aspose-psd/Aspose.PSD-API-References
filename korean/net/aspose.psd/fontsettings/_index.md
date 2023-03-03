---
title: Class FontSettings
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FontSettings 수업. 일반 PSD 벡터 형식 렌더러 글꼴 설정.
type: docs
weight: 4290
url: /ko/net/aspose.psd/fontsettings/
---
## FontSettings class

일반 PSD 벡터 형식 렌더러 글꼴 설정.

```csharp
public static class FontSettings
```

## 속성

| 이름 | 설명 |
| --- | --- |
| static [DefaultFontName](../../aspose.psd/fontsettings/defaultfontname/) { get; set; } | 글꼴의 기본 이름을 가져오거나 설정합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| static [ClearFontReplacements](../../aspose.psd/fontsettings/clearfontreplacements/)() | 모든 글꼴 교체 지우기 |
| static [GetAdobeFontName](../../aspose.psd/fontsettings/getadobefontname/)(string) | 글꼴 패밀리 이름으로 Adobe 글꼴 이름을 가져옵니다. |
| static [GetDefaultFontsFolders](../../aspose.psd/fontsettings/getdefaultfontsfolders/)() | 기본 글꼴 폴더를 가져옵니다. |
| static [GetFontReplacements](../../aspose.psd/fontsettings/getfontreplacements/)(string) | 글꼴 이름 로 글꼴 대체 배열을 가져옵니다. |
| static [GetFontsFolders](../../aspose.psd/fontsettings/getfontsfolders/)() | Aspose.Words가 트루타입 글꼴을 찾는 폴더 목록이 포함된 배열의 복사본을 가져옵니다. |
| static [GetReplacementFont](../../aspose.psd/fontsettings/getreplacementfont/)(string) | 가장 적합한 대체 글꼴을 가져옵니다. 모든 대체가 허용되지 않으면 먼저 허용되고 사용 가능한 글꼴이 반환됩니다. 사용 가능한 글꼴이 없으면 인수 에서 글꼴이 반환됩니다. |
| static [IsFontAllowed](../../aspose.psd/fontsettings/isfontallowed/)(string) | [글꼴 허용 여부] [지정된 글꼴 이름] 여부를 결정합니다. |
| static [Reset](../../aspose.psd/fontsettings/reset/)() | 글꼴 폴더와 기본 글꼴 이름을 시스템 기본값으로 재설정합니다. |
| static [SetAllowedFonts](../../aspose.psd/fontsettings/setallowedfonts/)(string[]) | 글꼴 목록으로 글꼴 사용을 제한합니다. restriction 전에 실제 글꼴 이름을 확인하세요. restriction 를 제거하려면 허용된 글꼴 목록을 Null로 설정하세요. |
| static [SetFontReplacements](../../aspose.psd/fontsettings/setfontreplacements/)(string, string[]) | 글꼴 대체 목록을 설정합니다. 글꼴이 허용되지 않으면 대체품을 찾습니다. 목록의 첫 번째 글꼴이 먼저 사용됩니다. 너무 제한되면 목록에서 다음 글꼴이 선택됩니다. 글꼴이 대체되지 않거나 모든 대체가 허용되지 않는 경우 허용된 글꼴 목록에서 첫 번째로 허용된 글꼴이 사용됩니다. 허용되고 사용 가능한 글꼴이 없으면 라이브러리는 허용되지 않는 경우에도 시스템 기본 글꼴을 사용해 보십시오. |
| static [SetFontsFolder](../../aspose.psd/fontsettings/setfontsfolder/)(string) | 이것은 바로 가기입니다.[`SetFontsFolders`](./setfontsfolders/) 하나의 글꼴 디렉토리만 설정하기 위해. 글꼴 폴더에서 수행된 검사가 없습니다. |
| static [SetFontsFolders](../../aspose.psd/fontsettings/setfontsfolders/)(string[], bool) | TrueType 글꼴이 로드되는 폴더를 설정하고 로드된 모든 글꼴을 지웁니다. 글꼴 폴더에서 수행된 검사가 없습니다. |
| static [UpdateFonts](../../aspose.psd/fontsettings/updatefonts/)() | 텍스트 레이어가 포함된 PSD 파일의 글꼴 캐시를 업데이트합니다. 이 메서드는 fontsFolder using 메서드 FontSettings.SetFontsFolder(fontsFolder) 또는 FontSettings.Reset()을 사용하여 글꼴을 재설정한 후 폴더의 글꼴이 PSD 파일을 처리할 때 고려되도록 보장합니다. PSD 이미지에 대해 FontSettings.SetFontsFolder(fontsFolder) 또는 FontSettings.Reset()이 호출될 때마다 이 방법을 사용하십시오. 이 메서드를 호출하지 않으면 글꼴이 업데이트된다는 보장이 없습니다. |

### 또한보십시오

* 네임스페이스 [Aspose.PSD](../../aspose.psd/)
* 집회 [Aspose.PSD](../../)


