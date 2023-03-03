---
title: Class IccProfileResource
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Resources.IccProfileResource クラス. ICC プロファイル リソースを表します
type: docs
weight: 3760
url: /ja/net/aspose.psd.fileformats.psd.resources/iccprofileresource/
---
## IccProfileResource class

ICC プロファイル リソースを表します。

```csharp
public sealed class IccProfileResource : ResourceBlock
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [IccProfileResource](iccprofileresource/)() | デフォルトのコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/iccprofileresource/datasize/) { get; } | リソース データ サイズをバイト単位で取得します。 |
| [IccProfile](../../aspose.psd.fileformats.psd.resources/iccprofileresource/iccprofile/) { get; set; } | ICC プロファイルを取得または設定します。 |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | リソースの一意の識別子を取得または設定します。 |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/iccprofileresource/minimalversion/) { get; } | 必要最小限の PSD バージョンを取得します。 |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | リソース名を取得または設定します。サイズを均等にするためにパディングされた Pascal 文字列 (null 名は 2 バイトの 0 で構成されます). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | リソース署名を取得します。常に '8BIM'. である必要があります |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | データを含むリソース ブロック サイズをバイト単位で取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | 指定したストリームにリソース ブロックを保存します。 |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | リソース値を検証します。 |

### 関連項目

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* 組み立て [Aspose.PSD](../../)


