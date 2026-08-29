---
title: "XmpBasicPackage.SetValue"
second_title: "Aspose.PSD for .NET API Reference"
description: "XmpBasicPackage メソッド。値を設定します"
type: docs
weight: 120
url: /ja/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/setvalue/
---
{{< psd/tize >}}
## XmpBasicPackage.SetValue method

値を設定します。

```csharp
public override void SetValue(string key, IXmlValue value)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| key | 文字列 | 追加された値で識別されるキーの文字列表現です。 |
| 値 | IXmlValue | 追加する値。 |

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

* interface [IXmlValue](../../../aspose.psd.xmp/ixmlvalue/)
* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


