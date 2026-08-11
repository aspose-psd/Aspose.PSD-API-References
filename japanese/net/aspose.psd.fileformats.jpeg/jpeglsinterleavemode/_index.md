---
title: "列挙型 JpegLsInterleaveMode"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Jpeg.JpegLsInterleaveMode 列挙型。マルチコンポーネントカラー画素データのインターリーブモードを定義します。"
type: docs
weight: 1520
url: /ja/net/aspose.psd.fileformats.jpeg/jpeglsinterleavemode/
---
{{< psd/tize >}}
## JpegLsInterleaveMode enumeration

マルチコンポーネント（カラー）ピクセルデータのインターリーブモードを定義します。

```csharp
public enum JpegLsInterleaveMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | `0` | データはコンポーネントごとにエンコードされ、RRRGGGBBB のように格納されます。 |
| Line | `1` | インタリーブモードは行単位です。各コンポーネントのフル行が次の行に移る前にエンコードされます。 |
| Sample | `2` | データはサンプル単位でエンコードされ、保存されます。カラー画像の場合、これは RGBRGBRGB のような形式です。 |

### 関連項目

* namespace [Aspose.PSD.FileFormats.Jpeg](../../aspose.psd.fileformats.jpeg/)
* assembly [Aspose.PSD](../../)


