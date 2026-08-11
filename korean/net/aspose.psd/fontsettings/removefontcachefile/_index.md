---
title: "FontSettings.RemoveFontCacheFile"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "FontSettings 메서드. 글꼴 캐시 파일을 제거합니다."
type: docs
weight: 100
url: /ko/net/aspose.psd/fontsettings/removefontcachefile/
---
{{< psd/tize >}}
## FontSettings.RemoveFontCacheFile method

글꼴 캐시 파일을 제거합니다.

```csharp
public static void RemoveFontCacheFile()
```

## 예제

다음 코드는 로드된 글꼴 캐시 파일을 제거하는 방법을 보여줍니다.

```csharp
[C#]

string src = "SimpleText.psd";

FontSettings.RemoveFontCacheFile();

using (var psdImage = (PsdImage)Image.Load(src))
{
    foreach (var layer in psdImage.Layers)
    {
        if (layer is TextLayer textLayer)
        {
            textLayer.GetFonts();
        }
    }
}
```

### 또 보기

* class [FontSettings](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


