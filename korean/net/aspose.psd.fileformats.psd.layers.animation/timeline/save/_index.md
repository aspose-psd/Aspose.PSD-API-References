---
title: "Timeline.Save"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Timeline 메서드. 저장 옵션에 따라 지정된 파일 위치와 지정된 형식으로 PsdImages와 Timeline 데이터를 저장합니다."
type: docs
weight: 70
url: /ko/net/aspose.psd.fileformats.psd.layers.animation/timeline/save/
---
{{< psd/tize >}}
## Save(string, ImageOptionsBase) {#save_1}

저장 옵션에 따라 지정된 형식으로 지정된 파일 위치에 PsdImage와 Timeline 데이터를 저장합니다.

```csharp
public void Save(string filePath, ImageOptionsBase options)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | String | 파일 경로. |
| 옵션 | ImageOptionsBase | 옵션. |

## 예제

다음 코드는 Timeline을 GIF 이미지로 내보내는 지원을 보여줍니다.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### 또 보기

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save}

저장 옵션에 따라 지정된 형식으로 지정된 스트림에 PsdImage와 Timeline 데이터를 저장합니다.

```csharp
public void Save(Stream outputStream, ImageOptionsBase options)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| outputStream | 스트림 | 출력 스트림입니다. |
| 옵션 | ImageOptionsBase | 옵션. |

## 예제

다음 코드는 Timeline을 GIF 이미지로 내보내는 지원을 보여줍니다.

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### 또 보기

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


