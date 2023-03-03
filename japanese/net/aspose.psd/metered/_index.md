---
title: Class Metered
second_title: Aspose.PSD for .NET API リファレンス
description: Aspose.PSD.Metered クラス. メータリング キーを設定するメソッドを提供します
type: docs
weight: 5120
url: /ja/net/aspose.psd/metered/
---
## Metered class

メータリング キーを設定するメソッドを提供します。

統合のための従量制メソッドを提供します

```csharp
public class Metered
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Metered](metered/)() | デフォルトのコンストラクター。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../aspose.psd/metered/equals/)(object) | 指定されたObject、このインスタンスと等しい. |
| [SetMeteredKey](../../aspose.psd/metered/setmeteredkey/)(string, string) | 従量制の公開鍵と秘密鍵を設定します |
| static [GetConsumptionCredit](../../aspose.psd/metered/getconsumptioncredit/)() | 消費クレジットを取得 |
| static [GetConsumptionQuantity](../../aspose.psd/metered/getconsumptionquantity/)() | 消費ファイルサイズを取得 |

### 例

この例では、従量制の公開鍵と秘密鍵を設定しようとします

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### 関連項目

* 名前空間 [Aspose.PSD](../../aspose.psd/)
* 組み立て [Aspose.PSD](../../)


