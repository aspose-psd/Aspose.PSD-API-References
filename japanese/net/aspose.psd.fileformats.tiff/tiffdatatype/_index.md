---
title: "クラス TiffDataType"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Tiff.TiffDataType クラス。tiff データ型"
type: docs
weight: 4680
url: /ja/net/aspose.psd.fileformats.tiff/tiffdatatype/
---
{{< psd/tize >}}
## TiffDataType class

TIFF データ型。

```csharp
public abstract class TiffDataType : IComparable
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlignedDataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/aligneddatasize/) { get; } | タグデータを格納するのに 12 バイトでは足りない場合に備えて、追加データサイズ（バイト単位）を取得します。 |
| abstract [Count](../../aspose.psd.fileformats.tiff/tiffdatatype/count/) { get; } | 要素数を取得します。 |
| abstract [DataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/datasize/) { get; } | タグデータを格納するのに 12 バイトでは足りない場合に備えて、追加データサイズ（バイト単位）を取得します。 |
| [Id](../../aspose.psd.fileformats.tiff/tiffdatatype/id/) { get; } | タグ ID の整数表現を取得します。 |
| [IsValid](../../aspose.psd.fileformats.tiff/tiffdatatype/isvalid/) { get; } | タグデータが有効かどうかを示す値を取得します。有効なタグは保持できるデータを含みます。無効なタグは保存できません。 |
| [TagId](../../aspose.psd.fileformats.tiff/tiffdatatype/tagid/) { get; } | タグ ID を取得します。 |
| abstract [TagType](../../aspose.psd.fileformats.tiff/tiffdatatype/tagtype/) { get; } | タグタイプを取得します。 |
| abstract [Value](../../aspose.psd.fileformats.tiff/tiffdatatype/value/) { get; set; } | このデータ型が保持する値を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [ReadTag](../../aspose.psd.fileformats.tiff/tiffdatatype/readtag/)(TiffStreamReader, long) | タグデータを読み取ります。 |
| [CompareTo](../../aspose.psd.fileformats.tiff/tiffdatatype/compareto/)(object) | 現在のインスタンスを同じ型の別のオブジェクトと比較し、現在のインスタンスがソート順で前、後、または同じ位置にあるかを示す整数を返します。 |
| virtual [DeepClone](../../aspose.psd.fileformats.tiff/tiffdatatype/deepclone/)() | このインスタンスのディープクローンを実行します。 |
| override [ToString](../../aspose.psd.fileformats.tiff/tiffdatatype/tostring/)() | このインスタンスを表すStringを返します。 |
| abstract [WriteAdditionalData](../../aspose.psd.fileformats.tiff/tiffdatatype/writeadditionaldata/)(TiffStreamWriter) | 追加のタグデータを書き込みます。 |
| [WriteTag](../../aspose.psd.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | タグデータを書き込みます。 |

### 関連項目

* namespace [Aspose.PSD.FileFormats.Tiff](../../aspose.psd.fileformats.tiff/)
* assembly [Aspose.PSD](../../)


