---
title: PsdImage.AddLayerGroup
second_title: Aspose.PSD for .NET API リファレンス
description: PsdImage 方法. 画層グループを追加します
type: docs
weight: 380
url: /ja/net/aspose.psd.fileformats.psd/psdimage/addlayergroup/
---
## PsdImage.AddLayerGroup method

画層グループを追加します。

```csharp
public LayerGroup AddLayerGroup(string groupName, int index, bool startBehaviour)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| groupName | String | グループの名前。 |
| index | Int32 | 後に挿入するレイヤーのインデックス。 |
| startBehaviour | Boolean | に設定した場合`真実` [開始動作] グループは起動時に開いた状態になり、それ以外の場合は最小化された状態になります。 |

### 戻り値

オープニンググループ layer

### 例外

| 例外 | 調子 |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | インデックスはレイヤー数の境界内にある必要があります |

### 関連項目

* class [LayerGroup](../../../aspose.psd.fileformats.psd.layers/layergroup/)
* class [PsdImage](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* 組み立て [Aspose.PSD](../../../)


