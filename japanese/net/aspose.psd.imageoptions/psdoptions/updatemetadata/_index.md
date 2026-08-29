---
title: "PsdOptions.UpdateMetadata"
second_title: "Aspose.PSD for .NET API Reference"
description: "PsdOptions プロパティ。メタデータを更新するかどうかを示す値を取得または設定します。値が true の場合、画像を保存する際にメタデータが更新されます"
type: docs
weight: 110
url: /ja/net/aspose.psd.imageoptions/psdoptions/updatemetadata/
---
{{< psd/tize >}}
## PsdOptions.UpdateMetadata property

メタデータを [update metadata] するかどうかを示す値を取得または設定します。値が true の場合、画像を保存する際にメタデータが更新されます。

```csharp
public bool UpdateMetadata { get; set; }
```

### Property Value

`true` if [メタデータを更新]; otherwise, `false`.

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

* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


