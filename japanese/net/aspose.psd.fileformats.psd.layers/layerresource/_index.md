---
title: "クラス LayerResource"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResource クラス。レイヤー情報を表します。"
type: docs
weight: 2480
url: /ja/net/aspose.psd.fileformats.psd.layers/layerresource/
---
{{< psd/tize >}}
## LayerResource class

レイヤー情報を表します。

```csharp
public abstract class LayerResource
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | レイヤーリソースキーを取得します。 |
| abstract [Length](../../aspose.psd.fileformats.psd.layers/layerresource/length/) { get; } | レイヤーリソースの長さ（バイト単位）を取得します。 |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | レイヤーリソースに必要な最小 PSD バージョンを取得します。0 は制限なしを示します。 |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | 署名を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [Save](../../aspose.psd.fileformats.psd.layers/layerresource/save/)(StreamContainer, int) | リソースを指定されたストリームコンテナに保存します。 |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | このインスタンスを表すStringを返します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| const [PsbResourceSignature](../../aspose.psd.fileformats.psd.layers/layerresource/psbresourcesignature/) | PSB 固有のリソース署名です。 |
| const [ResourceSignature](../../aspose.psd.fileformats.psd.layers/layerresource/resourcesignature/) | 共通のリソース署名です。 |

### 関連項目

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


