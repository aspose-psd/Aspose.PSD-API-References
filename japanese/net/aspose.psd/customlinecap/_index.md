---
title: "クラス CustomLineCap"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.CustomLineCap クラス。カスタムのユーザー定義ラインキャップをカプセル化します。"
type: docs
weight: 710
url: /ja/net/aspose.psd/customlinecap/
---
{{< psd/tize >}}
## CustomLineCap class

カスタムのユーザー定義ラインキャップをカプセル化します。

```csharp
public class CustomLineCap
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [CustomLineCap](customlinecap/#constructor)(GraphicsPath, GraphicsPath) | 指定されたアウトラインと塗りつぶしで `CustomLineCap` クラスの新しいインスタンスを初期化します。 |
| [CustomLineCap](customlinecap/#constructor_1)(GraphicsPath, GraphicsPath, LineCap) | 指定された既存の [`LineCap`](../linecap/) 列挙体と指定されたアウトラインと塗りつぶしから、`CustomLineCap` クラスの新しいインスタンスを初期化します。 |
| [CustomLineCap](customlinecap/#constructor_2)(GraphicsPath, GraphicsPath, LineCap, float) | 指定された既存の[`LineCap`](../linecap/) 列挙体から、指定されたアウトライン、塗り、インセットを使用して `CustomLineCap` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BaseCap](../../aspose.psd/customlinecap/basecap/) { get; set; } | `CustomLineCap` が基づく [`LineCap`](../linecap/) 列挙体を取得または設定します。 |
| [BaseInset](../../aspose.psd/customlinecap/baseinset/) { get; set; } | キャップとライン間の距離を取得または設定します。 |
| [FillPath](../../aspose.psd/customlinecap/fillpath/) { get; set; } | カスタムキャップの塗りを定義するオブジェクトを取得または設定します。 |
| [StrokeJoin](../../aspose.psd/customlinecap/strokejoin/) { get; set; } | この `CustomLineCap` オブジェクトを構成するラインがどのように結合されるかを決定する [`LineJoin`](../linejoin/) 列挙体を取得または設定します。 |
| [StrokePath](../../aspose.psd/customlinecap/strokepath/) { get; set; } | カスタムキャップのアウトラインを定義するオブジェクトを取得または設定します。 |
| [WidthScale](../../aspose.psd/customlinecap/widthscale/) { get; set; } | Pen オブジェクトの幅に対するこの `CustomLineCap` クラスオブジェクトのスケール量を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GetStrokeCaps](../../aspose.psd/customlinecap/getstrokecaps/)(out LineCap, out LineCap) | このカスタムキャップを構成するラインの開始と終了に使用されるキャップを取得します。 |
| [SetStrokeCaps](../../aspose.psd/customlinecap/setstrokecaps/)(LineCap, LineCap) | このカスタムキャップを構成するラインの開始と終了に使用されるキャップを設定します。 |

### 関連項目

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


