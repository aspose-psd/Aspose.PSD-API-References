---
title: Class PrintScaleResource
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.FileFormats.Psd.Resources.PrintScaleResource クラス. 印刷縮尺 resource
type: docs
weight: 3840
url: /ja/net/aspose.psd.fileformats.psd.resources/printscaleresource/
---
## PrintScaleResource class

印刷縮尺 resource

```csharp
public sealed class PrintScaleResource : ResourceBlock
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PrintScaleResource](printscaleresource/)() | デフォルトのコンストラクター。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/printscaleresource/datasize/) { get; } | リソース データ サイズをバイト単位で取得します。 |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | リソースの一意の識別子を取得または設定します。 |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/printscaleresource/minimalversion/) { get; } | 必要最小限の PSD バージョンを取得します。 |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | リソース名を取得または設定します。サイズを均等にするためにパディングされた Pascal 文字列 (null 名は 2 バイトの 0 で構成されます). |
| [Scale](../../aspose.psd.fileformats.psd.resources/printscaleresource/scale/) { get; set; } | スケールを取得または設定します。 |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | リソース署名を取得します。常に '8BIM'. である必要があります |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | データを含むリソース ブロック サイズをバイト単位で取得します。 |
| [Style](../../aspose.psd.fileformats.psd.resources/printscaleresource/style/) { get; set; } | スタイルを取得または設定します。 |
| [XLocation](../../aspose.psd.fileformats.psd.resources/printscaleresource/xlocation/) { get; set; } | x 位置を取得または設定します。 |
| [YLocation](../../aspose.psd.fileformats.psd.resources/printscaleresource/ylocation/) { get; set; } | y 位置を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | 指定したストリームにリソース ブロックを保存します。 |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | リソース値を検証します。 |

### 関連項目

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* 組み立て [Aspose.PSD](../../)


