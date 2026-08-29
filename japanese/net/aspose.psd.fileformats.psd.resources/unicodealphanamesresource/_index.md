---
title: "クラス UnicodeAlphaNamesResource"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.FileFormats.Psd.Resources.UnicodeAlphaNamesResource クラス。Unicode アルファ名リソースです。"
type: docs
weight: 4400
url: /ja/net/aspose.psd.fileformats.psd.resources/unicodealphanamesresource/
---
{{< psd/tize >}}
## UnicodeAlphaNamesResource class

Unicode アルファ名リソース

```csharp
public sealed class UnicodeAlphaNamesResource : ResourceBlock
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [UnicodeAlphaNamesResource](unicodealphanamesresource/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlphaNames](../../aspose.psd.fileformats.psd.resources/unicodealphanamesresource/alphanames/) { get; set; } | アルファ名を取得または設定します。 |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/unicodealphanamesresource/datasize/) { get; } | リソースデータのサイズ（バイト）を取得します。 |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | リソースの一意識別子を取得または設定します。 |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/unicodealphanamesresource/minimalversion/) { get; } | 必要最低限の PSD バージョンを取得します。 |
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


