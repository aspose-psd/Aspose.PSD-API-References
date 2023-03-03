---
title: Class QuickMaskInformationResource
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Resources.QuickMaskInformationResource クラス. クイックマスク情報 resource
type: docs
weight: 3850
url: /ja/net/aspose.psd.fileformats.psd.resources/quickmaskinformationresource/
---
## QuickMaskInformationResource class

クイックマスク情報 resource

```csharp
public sealed class QuickMaskInformationResource : ResourceBlock
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [QuickMaskInformationResource](quickmaskinformationresource/)() | デフォルトのコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ChannelId](../../aspose.psd.fileformats.psd.resources/quickmaskinformationresource/channelid/) { get; set; } | チャネル識別子を取得または設定します。 |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/quickmaskinformationresource/datasize/) { get; } | リソース データ サイズをバイト単位で取得します。 |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | リソースの一意の識別子を取得または設定します。 |
| [IsMaskEmpty](../../aspose.psd.fileformats.psd.resources/quickmaskinformationresource/ismaskempty/) { get; set; } | このインスタンスがマスク空であるかどうかを示す値を取得または設定します。 |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/quickmaskinformationresource/minimalversion/) { get; } | 必要最小限の PSD バージョンを取得します。 |
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


