---
title: "クラス GlobalAltitudeResource"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Resources.GlobalAltitudeResource クラス。グローバル高度リソース"
type: docs
weight: 4180
url: /ja/net/aspose.psd.fileformats.psd.resources/globalaltituderesource/
---
{{< psd/tize >}}
## GlobalAltitudeResource class

グローバル高度リソース

```csharp
public sealed class GlobalAltitudeResource : ResourceBlock
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [GlobalAltitudeResource](globalaltituderesource/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Altitude](../../aspose.psd.fileformats.psd.resources/globalaltituderesource/altitude/) { get; set; } | 高度を取得または設定します。 |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/globalaltituderesource/datasize/) { get; } | リソースデータのサイズ（バイト）を取得します。 |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | リソースの一意識別子を取得または設定します。 |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/globalaltituderesource/minimalversion/) { get; } | 必要最低限の PSD バージョンを取得します。 |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | リソース名を取得または設定します。パスカル文字列で、サイズを偶数にするためにパディングされます（null 名は 0 のバイト2つで構成されます）。 |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | リソースシグネチャを取得します。常に '8BIM' である必要があります。 |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | データを含むリソースブロックのサイズ（バイト）を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | リソースブロックを指定されたストリームに保存します。 |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | リソースの値を検証します。 |

### 関連項目

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* namespace [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assembly [Aspose.PSD](../../)


