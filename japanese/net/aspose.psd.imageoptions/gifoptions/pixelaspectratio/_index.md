---
title: GifOptions.PixelAspectRatio
second_title: Aspose.PSD for .NET API リファレンス
description: GifOptions 財産. GIF ピクセルの縦横比を取得または設定します
type: docs
weight: 90
url: /ja/net/aspose.psd.imageoptions/gifoptions/pixelaspectratio/
---
## GifOptions.PixelAspectRatio property

GIF ピクセルの縦横比を取得または設定します。

```csharp
public byte PixelAspectRatio { get; set; }
```

### プロパティ値

GIF ピクセルのアスペクト比。

### 備考

ピクセル アスペクト比 - 元の画像のピクセルのアスペクト比の近似 を計算するために使用される係数。フィールドの 値が0でない場合、アスペクト比 のこの近似値は、次の式に基づいて計算されます: アスペクト比=(ピクセルアスペクト比+15)/64 ピクセルアスペクト比は、ピクセルの商として定義されます。 s 幅がその高さを超えています。このフィールドの値の範囲では、 の最大幅のピクセルから 4:1 の最大ピクセルまでを 1:4 の最大ピクセルまで、1/64 単位で指定できます。計算で使用される値。

### 関連項目

* class [GifOptions](../)
* 名前空間 [Aspose.PSD.ImageOptions](../../gifoptions/)
* 組み立て [Aspose.PSD](../../../)


