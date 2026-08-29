---
title: "クラス Metered"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.Metered クラス。メータキーを設定するメソッドを提供します。"
type: docs
weight: 5610
url: /ja/net/aspose.psd/metered/
---
{{< psd/tize >}}
## Metered class

メーターキーを設定するメソッドを提供します。

```csharp
public class Metered
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Metered](metered/)() | デフォルトコンストラクタです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../aspose.psd/metered/equals/)(object) | 指定されたオブジェクトがこのインスタンスと等しいかどうかを判断します。 |
| [GetProductName](../../aspose.psd/metered/getproductname/)() | 製品名を取得します。 |
| [SetMeteredKey](../../aspose.psd/metered/setmeteredkey/)(string, string) | メーターパブリックキーとプライベートキーを設定します。メータライセンスを購入した場合、アプリケーション起動時にこの API を呼び出す必要があります。通常、これだけで十分です。ただし、使用量データのアップロードが常に失敗し、24 時間を超えると、ライセンスが評価版ステータスに設定されます。そのような事態を防ぐため、ライセンスステータスを定期的に確認し、評価版ステータスであれば再度この API を呼び出す必要があります。 |
| static [GetConsumptionCredit](../../aspose.psd/metered/getconsumptioncredit/)() | 消費クレジットを取得します |
| static [GetConsumptionQuantity](../../aspose.psd/metered/getconsumptionquantity/)() | 消費ファイルサイズを取得します |
| static [IsMeteredLicensed](../../aspose.psd/metered/ismeteredlicensed/)() | メーターがライセンスされているかどうかを確認します |

## 例

この例では、メーターの公開鍵と秘密鍵を設定しようとします

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### 関連項目

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


