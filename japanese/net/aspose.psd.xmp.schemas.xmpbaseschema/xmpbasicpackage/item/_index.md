---
title: "XmpBasicPackage.Item"
second_title: "Aspose.PSD for .NET API Reference"
description: "XmpBasicPackage プロパティ。指定されたキーで Object を取得または設定します"
type: docs
weight: 20
url: /ja/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/item/
---
{{< psd/tize >}}
## XmpBasicPackage indexer

指定されたキーに対応するオブジェクトを取得または設定します。

```csharp
public override object this[string key] { get; set; }
```

| パラメーター | 説明 |
| --- | --- |
| key | 値を識別するキーです。 |

### 戻り値

指定されたキーの Object を返します。

### Property Value

Object。

## 例

以下のコードは UpdateMetadata オプションを使用して XMP データの CreatorTool 値を更新する方法を示しています。

```csharp
[C#]

string path = "output.psd";

using (var image = new PsdImage(100, 100))
{
    // If you want the creator tool to change, make sure that the "UpdateMetadata" property is set to true. It's set to true by default.
    var psdOptions = new PsdOptions();
    psdOptions.UpdateMetadata = true;

    // 画像を保存しています。
    image.Save(path, psdOptions);

    // コード内で CreatorTool を確認しています。
    var xmpData = image.XmpData;
    var basicPackage = image.XmpData.GetPackage(Namespaces.XmpBasic);

    // ここに更新された CreatorTool の情報が表示されます。
    var currentCreatorTool = (string)basicPackage[":CreatorTool"];
}
```

### 関連項目

* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


