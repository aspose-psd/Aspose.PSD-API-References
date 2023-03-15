---
title: Class TiffDataType
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Tiff.TiffDataType クラス. tiff データ型.
type: docs
weight: 4210
url: /ja/net/aspose.psd.fileformats.tiff/tiffdatatype/
---
## TiffDataType class

tiff データ型.

```csharp
public abstract class TiffDataType : IComparable
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlignedDataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/aligneddatasize/) { get; } | 追加のデータ サイズをバイト単位で取得します (12 バイトではタグ データに収まらない場合)。 |
| abstract [Count](../../aspose.psd.fileformats.tiff/tiffdatatype/count/) { get; } | 要素数を取得します。 |
| abstract [DataSize](../../aspose.psd.fileformats.tiff/tiffdatatype/datasize/) { get; } | 追加のデータ サイズをバイト単位で取得します (12 バイトではタグ データに収まらない場合)。 |
| [Id](../../aspose.psd.fileformats.tiff/tiffdatatype/id/) { get; } | タグ ID 整数表現を取得します。 |
| [IsValid](../../aspose.psd.fileformats.tiff/tiffdatatype/isvalid/) { get; } | タグデータが有効かどうかを示す値を取得します。有効なタグには、保存できるデータが含まれています。無効なタグは保存できません. |
| [TagId](../../aspose.psd.fileformats.tiff/tiffdatatype/tagid/) { get; } | タグ ID を取得します。 |
| abstract [TagType](../../aspose.psd.fileformats.tiff/tiffdatatype/tagtype/) { get; } | タグの種類を取得します。 |
| abstract [Value](../../aspose.psd.fileformats.tiff/tiffdatatype/value/) { get; set; } | このデータ型に含まれる値を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [ReadTag](../../aspose.psd.fileformats.tiff/tiffdatatype/readtag/)(TiffStreamReader, long) | タグデータを読み込みます。 |
| [CompareTo](../../aspose.psd.fileformats.tiff/tiffdatatype/compareto/)(object) | 現在のインスタンスを同じ型の別のオブジェクトと比較し、現在のインスタンスが他のオブジェクトと並べ替え順序で前、後、または同じ位置にあるかどうかを示す整数を返します。 |
| virtual [DeepClone](../../aspose.psd.fileformats.tiff/tiffdatatype/deepclone/)() | このインスタンスのディープ クローンを実行します。 |
| override [ToString](../../aspose.psd.fileformats.tiff/tiffdatatype/tostring/)() | を返しますStringこのインスタンスを表す. |
| abstract [WriteAdditionalData](../../aspose.psd.fileformats.tiff/tiffdatatype/writeadditionaldata/)(TiffStreamWriter) | 追加タグデータを書き込みます。 |
| [WriteTag](../../aspose.psd.fileformats.tiff/tiffdatatype/writetag/)(TiffStreamWriter, long) | タグデータを書き込みます。 |

### 関連項目

* 名前空間 [Aspose.PSD.FileFormats.Tiff](../../aspose.psd.fileformats.tiff/)
* 組み立て [Aspose.PSD](../../)


