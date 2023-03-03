---
title: Class XmpPackage
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.Xmp.XmpPackage クラス. XMP パッケージの基本抽象化を表す XmpPackage クラスを定義します
type: docs
weight: 6270
url: /ja/net/aspose.psd.xmp/xmppackage/
---
## XmpPackage class

XMP パッケージの基本抽象化を表す XmpPackage クラスを定義します。

```csharp
public class XmpPackage : IEnumerable<KeyValuePair<string, object>>, IXmlValue
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [Item](../../aspose.psd.xmp/xmppackage/item/) { get; set; } | を取得または設定しますObject指定されたキーで. |
| virtual [Keys](../../aspose.psd.xmp/xmppackage/keys/) { get; } | XMP パッケージ内のキーを取得します。 |
| [NamespaceUri](../../aspose.psd.xmp/xmppackage/namespaceuri/) { get; } | 名前空間 URI を取得します。 |
| [Prefix](../../aspose.psd.xmp/xmppackage/prefix/) { get; } | プレフィックスを取得します。 |
| [XmlNamespace](../../aspose.psd.xmp/xmppackage/xmlnamespace/) { get; } | XML 名前空間を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| virtual [AddValue](../../aspose.psd.xmp/xmppackage/addvalue/)(string, string) | 値を追加します。 |
| virtual [Clear](../../aspose.psd.xmp/xmppackage/clear/)() | このインスタンスをクリアします。 |
| virtual [ContainsKey](../../aspose.psd.xmp/xmppackage/containskey/)(string) | 指定されたキーにキーが含まれているかどうかを判断します. |
| [GetEnumerator](../../aspose.psd.xmp/xmppackage/getenumerator/)() | コレクションを反復処理する列挙子を返します。 |
| virtual [GetXmlValue](../../aspose.psd.xmp/xmppackage/getxmlvalue/)() | XMP 値を XML 表現に変換します。 |
| virtual [Remove](../../aspose.psd.xmp/xmppackage/remove/)(string) | 指定されたキーの値を削除します。 |
| virtual [SetValue](../../aspose.psd.xmp/xmppackage/setvalue/)(string, IXmlValue) | 値を設定します。 |
| virtual [SetXmpTypeValue](../../aspose.psd.xmp/xmppackage/setxmptypevalue/)(string, XmpTypeBase) | XMP タイプの値を設定します。 |

### 関連項目

* interface [IXmlValue](../ixmlvalue/)
* 名前空間 [Aspose.PSD.Xmp](../../aspose.psd.xmp/)
* 組み立て [Aspose.PSD](../../)


