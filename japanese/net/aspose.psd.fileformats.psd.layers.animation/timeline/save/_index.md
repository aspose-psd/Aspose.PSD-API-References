---
title: "Timeline.Save"
second_title: "Aspose.PSD for .NET API Reference"
description: "Timeline メソッド。保存オプションに従って、指定された形式で PsdImages と Timeline データを指定されたファイル位置に保存します。"
type: docs
weight: 70
url: /ja/net/aspose.psd.fileformats.psd.layers.animation/timeline/save/
---
{{< psd/tize >}}
## Save(string, ImageOptionsBase) {#save_1}

保存オプションに従って、指定された形式で指定されたファイル場所に PsdImage と Timeline のデータを保存します。

```csharp
public void Save(string filePath, ImageOptionsBase options)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | 文字列 | ファイルパス。 |
| オプション | ImageOptionsBase | オプションです。 |

## 例

以下のコードは Timeline を GIF 画像にエクスポートするサポートを示しています。

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### 関連項目

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save}

保存オプションに従って、指定された形式で指定されたストリームに PsdImage と Timeline のデータを保存します。

```csharp
public void Save(Stream outputStream, ImageOptionsBase options)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputStream | ストリーム | 出力ストリームです。 |
| オプション | ImageOptionsBase | オプションです。 |

## 例

以下のコードは Timeline を GIF 画像にエクスポートするサポートを示しています。

```csharp
[C#]

string sourceFile = "4_animated.psd";
string outputGif = "out_4_animated.psd.gif";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    psdImage.Timeline.Save(outputGif, new GifOptions());
}
```

### 関連項目

* class [ImageOptionsBase](../../../aspose.psd/imageoptionsbase/)
* class [Timeline](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Animation](../../../aspose.psd.fileformats.psd.layers.animation/)
* assembly [Aspose.PSD](../../../)


