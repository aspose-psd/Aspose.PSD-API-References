---
title: "PsdOptions.RemoveGlobalTextEngineResource"
second_title: "Aspose.PSD for .NET API Reference"
description: "PsdOptions プロパティ。グローバル テキスト エンジン リソースを削除するかどうかを示す値を取得または設定します。このオプションは、主にフォントが欠如しているテキストレイヤーが原因で、処理後に Adobe Photoshop で開けなくなるテキストレイヤー付き psd ファイルにのみ使用されます。このオプションを使用した後、ユーザーは Photoshop で開いたファイルのメニュー\\\"Menu Text\\\"→\\\"Process absent fonts\\\"を実行する必要があります。その操作が完了すると、すべてのテキストが再び表示されます。ただし、この操作により最終的なレイアウトが一部変更される可能性があることに注意してください。"
type: docs
weight: 90
url: /ja/net/aspose.psd.imageoptions/psdoptions/removeglobaltextengineresource/
---
{{< psd/tize >}}
## PsdOptions.RemoveGlobalTextEngineResource property

グローバル テキスト エンジン リソースを削除するかどうかを示す値を取得または設定します。このオプションは、処理後に Adobe Photoshop で開けなくなるテキストレイヤー付き PSD ファイル（主にフォントが欠如しているテキストレイヤーに関連）で使用されます。このオプションを使用した後、ユーザーは Photoshop で開いたファイルで次の操作を行う必要があります：メニュー「Text」→「Process absent fonts」。この操作により、すべてのテキストが再び表示されます。ただし、この操作により最終レイアウトが一部変更される可能性があることに注意してください。

```csharp
public bool RemoveGlobalTextEngineResource { get; set; }
```

### Property Value

`true` は [remove global text engine resource] の場合; それ以外は `false`。

### 関連項目

* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


