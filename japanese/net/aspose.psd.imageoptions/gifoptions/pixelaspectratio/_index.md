---
title: "GifOptions.PixelAspectRatio"
second_title: "Aspose.PSD for .NET API Reference"
description: "GifOptions プロパティ。GIF のピクセルアスペクト比を取得または設定します"
type: docs
weight: 90
url: /ja/net/aspose.psd.imageoptions/gifoptions/pixelaspectratio/
---
{{< psd/tize >}}
## GifOptions.PixelAspectRatio property

GIF のピクセルアスペクト比を取得または設定します。

```csharp
public byte PixelAspectRatio { get; set; }
```

### Property Value

GIF のピクセルアスペクト比です。

## 備考

ピクセルアスペクト比 - 元画像のピクセルのアスペクト比の近似を計算するために使用される係数です。フィールドの値が 0 でない場合、このアスペクト比の近似は次の式に基づいて計算されます: アスペクト比 = (Pixel Aspect Ratio + 15) / 64 ピクセルアスペクト比はピクセルの幅を高さで割った商として定義されます。このフィールドの値範囲は、最も幅の広いピクセル 4:1 から最も高さの高いピクセル 1:4 までを 1/64 刻みで指定できます。値: 0 - アスペクト比情報が提供されていません。1..255 - 計算に使用される値。

### 関連項目

* class [GifOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


