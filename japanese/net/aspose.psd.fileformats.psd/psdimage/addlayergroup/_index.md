---
title: "PsdImage.AddLayerGroup"
second_title: "Aspose.PSD for .NET API Reference"
description: "PsdImage メソッド。レイヤー グループを追加します"
type: docs
weight: 400
url: /ja/net/aspose.psd.fileformats.psd/psdimage/addlayergroup/
---
{{< psd/tize >}}
## PsdImage.AddLayerGroup method

レイヤー グループを追加します。

```csharp
public LayerGroup AddLayerGroup(string groupName, int index, bool startBehaviour)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| groupName | 文字列 | グループの名前です。 |
| インデックス | Int32 | 挿入後のレイヤーのインデックスです。 |
| startBehaviour | Boolean | `true` に設定された場合、[start behaviour] は起動時にグループが開いた状態になります。設定されていない場合は最小化された状態になります。 |

### 戻り値

グループレイヤーを開く

### 例外

| 例外 | 条件 |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | インデックスはレイヤー数の範囲内である必要があります |

### 関連項目

* class [LayerGroup](../../../aspose.psd.fileformats.psd.layers/layergroup/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


