---
title: "クラス XmpPacketWrapper"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.Xmp.XmpPacketWrapper クラス。ヘッダーとトレーラーを含むシリアライズされた XMP パッケージを保持します。"
type: docs
weight: 6790
url: /ja/net/aspose.psd.xmp/xmppacketwrapper/
---
{{< psd/tize >}}
## XmpPacketWrapper class

ヘッダーとトレーラを含むシリアライズされた xmp パッケージを含みます。

```csharp
public class XmpPacketWrapper
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | `XmpPacketWrapper` クラスの新しいインスタンスを初期化します。 |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | `XmpPacketWrapper` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [HeaderPi](../../aspose.psd.xmp/xmppacketwrapper/headerpi/) { get; } | ヘッダー処理指示を取得します。 |
| [Meta](../../aspose.psd.xmp/xmppacketwrapper/meta/) { get; set; } | XMP メタを取得します。オプションです。 |
| [Packages](../../aspose.psd.xmp/xmppacketwrapper/packages/) { get; } | XMP 内の [`XmpPackage`](../xmppackage/) 配列を取得します。 |
| [PackagesCount](../../aspose.psd.xmp/xmppacketwrapper/packagescount/) { get; } | XMP 構造内のパッケージ数を取得します。 |
| [TrailerPi](../../aspose.psd.xmp/xmppacketwrapper/trailerpi/) { get; } | トレーラー処理指示を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddPackage](../../aspose.psd.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | パッケージを追加します。 |
| [ClearPackages](../../aspose.psd.xmp/xmppacketwrapper/clearpackages/)() | XMP 内のすべての [`XmpPackage`](../xmppackage/) を削除します。 |
| [ContainsPackage](../../aspose.psd.xmp/xmppacketwrapper/containspackage/)(string) | パッケージが XMP ラッパーに存在するかどうかを判断します。 |
| [GetPackage](../../aspose.psd.xmp/xmppacketwrapper/getpackage/)(string) | 名前空間 URI によるパッケージを取得します。 |
| [RemovePackage](../../aspose.psd.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | XMP パッケージを削除します。 |

## 備考

XML 処理指示 (PI) のペアで構成されるラッパーは、rdf:RDF 要素の周囲に配置できる場合があります。

### 関連項目

* namespace [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* assembly [Aspose.PSD](../../)


