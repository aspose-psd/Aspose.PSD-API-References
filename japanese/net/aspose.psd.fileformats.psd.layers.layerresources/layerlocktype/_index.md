---
title: "列挙型 LayerLockType"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LayerLockType 列挙型。レイヤーロックオプションです。"
type: docs
weight: 2890
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/
---
{{< psd/tize >}}
## LayerLockType enumeration

レイヤーロックオプション

```csharp
[Flags]
public enum LayerLockType
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| None | `0` | レイヤーロックなし |
| LockTransparentPixels | `1` | レイヤーを部分的にロックします - 編集をレイヤーの不透明部分に限定します。このオプションは、以前のバージョンの Photoshop の「透明度を保持」オプションと同等です。 |
| LockImagePixels | `2` | レイヤーを部分的にロックします - ペイントツールによるレイヤーのピクセルの変更を防止します。 |
| LockPosition | `4` | レイヤーを部分的にロックします - レイヤーのピクセルが移動するのを防止します。 |
| LockAll | `7` | レイヤーのすべてのプロパティをロックします |

### 関連項目

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


