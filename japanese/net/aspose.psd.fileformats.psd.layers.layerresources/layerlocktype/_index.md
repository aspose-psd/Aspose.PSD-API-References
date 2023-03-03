---
title: Enum LayerLockType
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LayerLockType 列挙. レイヤー ロック オプション
type: docs
weight: 2580
url: /ja/net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/
---
## LayerLockType enumeration

レイヤー ロック オプション

```csharp
[Flags]
public enum LayerLockType
```

### 値

| 名前 | 価値 | 説明 |
| --- | --- | --- |
| None | `0` | レイヤーロックなし |
| LockTransparentPixels | `1` | レイヤーを部分的にロック - 編集をレイヤーの不透明部分に限定します。 このオプションは、以前のバージョンの Photoshop の [透明度を保持] オプションと同等です。 |
| LockImagePixels | `2` | レイヤーを部分的にロック - ペイント ツールを使用してレイヤーのピクセルを変更できないようにします。 |
| LockPosition | `4` | レイヤーを部分的にロック - レイヤーのピクセルが動かないようにします. |
| LockAll | `7` | レイヤーのすべてのプロパティをロックします |

### 関連項目

* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* 組み立て [Aspose.PSD](../../)


