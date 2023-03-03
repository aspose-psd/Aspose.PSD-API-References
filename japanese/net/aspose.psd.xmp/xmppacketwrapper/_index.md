---
title: Class XmpPacketWrapper
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.Xmp.XmpPacketWrapper クラス. ヘッダーとトレーラーを含むシリアル化された xmp パッケージが含まれています
type: docs
weight: 6290
url: /ja/net/aspose.psd.xmp/xmppacketwrapper/
---
## XmpPacketWrapper class

ヘッダーとトレーラーを含むシリアル化された xmp パッケージが含まれています。

```csharp
public class XmpPacketWrapper
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | の新しいインスタンスを初期化します`XmpPacketWrapper`class. |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | の新しいインスタンスを初期化します`XmpPacketWrapper`class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [HeaderPi](../../aspose.psd.xmp/xmppacketwrapper/headerpi/) { get; } | ヘッダー処理命令を取得します。 |
| [Meta](../../aspose.psd.xmp/xmppacketwrapper/meta/) { get; set; } | XMP メタを取得します。オプション. |
| [Packages](../../aspose.psd.xmp/xmppacketwrapper/packages/) { get; } | の配列を取得します[`XmpPackage`](../xmppackage/)XMP. 内 |
| [PackagesCount](../../aspose.psd.xmp/xmppacketwrapper/packagescount/) { get; } | XMP 構造内のパッケージの量を取得します。 |
| [TrailerPi](../../aspose.psd.xmp/xmppacketwrapper/trailerpi/) { get; } | トレーラ処理命令を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddPackage](../../aspose.psd.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | パッケージを追加します。 |
| [ClearPackages](../../aspose.psd.xmp/xmppacketwrapper/clearpackages/)() | すべて削除[`XmpPackage`](../xmppackage/)XMP. 内 |
| [ContainsPackage](../../aspose.psd.xmp/xmppacketwrapper/containspackage/)(string) | パッケージが xmp ラッパーに存在するかどうかを判断します。 |
| [GetPackage](../../aspose.psd.xmp/xmppacketwrapper/getpackage/)(string) | 名前空間 URI でパッケージを取得します。 |
| [RemovePackage](../../aspose.psd.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | XMP パッケージを削除します。 |

### 備考

XML 処理命令 (PI) のペアで構成されるラッパーを rdf:RDF 要素の周りに配置できます。

### 関連項目

* 名前空間 [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* 組み立て [Aspose.PSD](../../)


