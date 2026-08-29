---
title: "Blend クラス"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.Blend クラス。ブレンド パターンを定義します。このクラスは継承できません。"
type: docs
weight: 110
url: /ja/net/aspose.psd/blend/
---
{{< psd/tize >}}
## Blend class

ブレンドパターンを定義します。このクラスは継承できません。

```csharp
public sealed class Blend
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Blend](blend/#constructor)() | `Blend` クラスの新しいインスタンスを初期化します。factor と blend 配列の要素数は 1 になります。 |
| [Blend](blend/#constructor_1)(int) | `Blend` クラスの新しいインスタンスを、指定された factor と position の数で初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Factors](../../aspose.psd/blend/factors/) { get; set; } | グラデーションの blend factor 配列を取得または設定します。 |
| [Positions](../../aspose.psd/blend/positions/) { get; set; } | グラデーションの blend position 配列を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../aspose.psd/blend/equals/)(object) | 指定されたオブジェクトが `Blend` クラスであり、この `Blend` クラスと等価かどうかをテストします。 |
| override [GetHashCode](../../aspose.psd/blend/gethashcode/)() | このインスタンスのハッシュコードを返します。 |

## 備考

典型的な blend クラスの使用方法は、ブラシ用に blend パターンを定義することです。そのため、blend プロパティは慎重に初期化する必要があります。null 配列は許可されません。blend factor または position 配列が空であるか、長さが一致しない場合、ブラシは適切な例外をスローします。position 配列に要素が 2 つ以上ある場合、最初の要素は 0、最後の要素は 1 にする必要があります。

### 関連項目

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


