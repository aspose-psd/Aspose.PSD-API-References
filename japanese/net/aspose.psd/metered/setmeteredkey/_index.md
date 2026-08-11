---
title: "Metered.SetMeteredKey"
second_title: "Aspose.PSD for .NET API Reference"
description: "Metered メソッド。メーター制の公開キーと秘密キーを設定します。アプリケーション起動時にメーター制ライセンスを購入した場合、この API を通常通り呼び出すだけで十分です。ただし、消費データのアップロードが常に失敗し、24 時間を超えるとライセンスは評価版ステータスに設定されます。そのような事態を防ぐため、ライセンスステータスを定期的に確認し、評価版ステータスの場合は再度この API を呼び出してください。"
type: docs
weight: 40
url: /ja/net/aspose.psd/metered/setmeteredkey/
---
{{< psd/tize >}}
## Metered.SetMeteredKey method

メーターパブリックキーとプライベートキーを設定します。メータライセンスを購入した場合、アプリケーション起動時にこの API を呼び出す必要があります。通常、これだけで十分です。ただし、使用量データのアップロードが常に失敗し、24 時間を超えると、ライセンスが評価版ステータスに設定されます。そのような事態を防ぐため、ライセンスステータスを定期的に確認し、評価版ステータスであれば再度この API を呼び出す必要があります。

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| publicKey | 文字列 | 公開キー |
| privateKey | 文字列 | 秘密キー |

### 関連項目

* class [Metered](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


