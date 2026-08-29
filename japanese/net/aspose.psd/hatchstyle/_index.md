---
title: "列挙型 HatchStyle"
second_title: "Aspose.PSD for .NET API Reference"
description: "Aspose.PSD.HatchStyle 列挙型。HatchBrush オブジェクトで利用できるさまざまなパターンを指定します"
type: docs
weight: 4810
url: /ja/net/aspose.psd/hatchstyle/
---
{{< psd/tize >}}
## HatchStyle enumeration

[`HatchBrush`](../../aspose.psd.brushes/hatchbrush/) オブジェクトで利用できるさまざまなパターンを指定します。

```csharp
public enum HatchStyle
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Horizontal | `0` | 水平線のパターンです。 |
| Min | `0` | ハッチスタイル Horizontal を指定します。 |
| Vertical | `1` | 垂直線のパターンです。 |
| ForwardDiagonal | `2` | 左上から右下への対角線のパターンです。 |
| BackwardDiagonal | `3` | 右上から左下への対角線のパターンです。 |
| Cross | `4` | 交差する水平線と垂直線を指定します。 |
| LargeGrid | `4` | ハッチスタイル Cross を指定します。 |
| Max | `4` | ハッチスタイル SolidDiamond を指定します。 |
| DiagonalCross | `5` | 交差する対角線のパターンです。 |
| Percent05 | `6` | 5% のハッチを指定します。前景色と背景色の比率は 5:95 です。 |
| Percent10 | `7` | 10% のハッチを指定します。前景色と背景色の比率は 10:90 です。 |
| Percent20 | `8` | 20% のハッチを指定します。前景色と背景色の比率は 20:80 です。 |
| Percent25 | `9` | 25% のハッチを指定します。前景色と背景色の比率は 25:75 です。 |
| Percent30 | `10` | 30% のハッチを指定します。前景色と背景色の比率は 30:70 です。 |
| Percent40 | `11` | 40% のハッチを指定します。前景色と背景色の比率は 40:60 です。 |
| Percent50 | `12` | 50% のハッチを指定します。前景色と背景色の比率は 50:50 です。 |
| Percent60 | `13` | 60% のハッチを指定します。前景色と背景色の比率は 60:40 です。 |
| Percent70 | `14` | 70% のハッチを指定します。前景色と背景色の比率は 70:30 です。 |
| Percent75 | `15` | 75% のハッチを指定します。前景色と背景色の比率は 75:25 です。 |
| Percent80 | `16` | 80% のハッチを指定します。前景色と背景色の比率は 80:100 です。 |
| Percent90 | `17` | 90パーセントのハッチを指定します。前景色と背景色の比率は90:10です。 |
| LightDownwardDiagonal | `18` | 右上から右下へ斜めに傾く対角線を指定し、ForwardDiagonal より 50 パーセント間隔が狭くなりますが、アンチエイリアスは適用されません。 |
| LightUpwardDiagonal | `19` | 左上から左下へ斜めに傾く対角線を指定し、BackwardDiagonal より 50 パーセント間隔が狭くなりますが、アンチエイリアスは適用されません。 |
| DarkDownwardDiagonal | `20` | 右上から右下へ斜めに傾く対角線を指定し、ForwardDiagonal より 50 パーセント間隔が狭く、幅が 2 倍です。このハッチ パターンはアンチエイリアスされません。 |
| DarkUpwardDiagonal | `21` | 左上から左下へ斜めに傾く対角線を指定し、BackwardDiagonal より 50 パーセント間隔が狭く、幅が 2 倍です。ただし、線はアンチエイリアスされません。 |
| WideDownwardDiagonal | `22` | 右上から右下へ斜めに傾く対角線を指定し、ハッチスタイル ForwardDiagonal と同じ間隔で、幅が 3 倍です。ただし、アンチエイリアスは適用されません。 |
| WideUpwardDiagonal | `23` | 左上から左下へ斜めに傾く対角線を指定し、ハッチスタイル BackwardDiagonal と同じ間隔で、幅が 3 倍です。ただし、アンチエイリアスは適用されません。 |
| LightVertical | `24` | Vertical より 50 パーセント間隔が狭い垂直線を指定します。 |
| LightHorizontal | `25` | Horizontal より 50 パーセント間隔が狭い水平線を指定します。 |
| NarrowVertical | `26` | ハッチスタイル Vertical より 75 パーセント間隔が狭い垂直線（または LightVertical より 25 パーセント間隔が狭い）を指定します。 |
| NarrowHorizontal | `27` | ハッチスタイル Horizontal より 75 パーセント間隔が狭い水平線（または LightHorizontal より 25 パーセント間隔が狭い）を指定します。 |
| DarkVertical | `28` | Vertical より 50 パーセント間隔が狭く、幅が 2 倍の垂直線を指定します。 |
| DarkHorizontal | `29` | Horizontal より 50 パーセント間隔が狭く、幅が 2 倍の水平線を指定します。 |
| DashedDownwardDiagonal | `30` | 右上から右下へ斜めに傾く破線の対角線を指定します。 |
| DashedUpwardDiagonal | `31` | 左上から左下へ斜めに傾く破線の対角線を指定します。 |
| DashedHorizontal | `32` | 破線の水平線を指定します。 |
| DashedVertical | `33` | 破線の垂直線を指定します。 |
| SmallConfetti | `34` | 紙吹雪のような外観のハッチを指定します。 |
| LargeConfetti | `35` | 紙吹雪のような外観のハッチを指定し、SmallConfetti より大きなピースで構成されます。 |
| ZigZag | `36` | ジグザグで構成された水平線を指定します。 |
| Wave | `37` | チルダで構成された水平線を指定します。 |
| DiagonalBrick | `38` | 左上から左下へ斜めに傾く層状のレンガの外観のハッチを指定します。 |
| HorizontalBrick | `39` | 横方向に層状のレンガの外観のハッチを指定します。 |
| Weave | `40` | 織物のような外観のハッチを指定します。 |
| Plaid | `41` | チェック柄のような外観のハッチを指定します。 |
| Divot | `42` | 凹みの外観を持つハッチを指定します。 |
| DottedGrid | `43` | 交差する水平線と垂直線を指定します。各線は点で構成されています。 |
| DottedDiamond | `44` | 交差する前方対角線と後方対角線を指定します。各線は点で構成されています。 |
| Shingle | `45` | 上部から下部へ右方向に傾斜した対角状に重ねられたシングルの外観を持つハッチを指定します。 |
| Trellis | `46` | 格子の外観を持つハッチを指定します。 |
| Sphere | `47` | 隣接して配置された球体の外観を持つハッチを指定します。 |
| SmallGrid | `48` | 交差し、ハッチスタイル「Cross」より50％近く間隔が狭い水平線と垂直線を指定します。 |
| SmallCheckerBoard | `49` | チェッカーボードの外観を持つハッチを指定します。 |
| LargeCheckerBoard | `50` | SmallCheckerBoard のサイズの2倍の正方形を持つチェッカーボードの外観を持つハッチを指定します。 |
| OutlinedDiamond | `51` | 交差する前方対角線と後方対角線を指定しますが、アンチエイリアスは適用されません。 |
| SolidDiamond | `52` | 対角に配置されたチェッカーボードの外観を持つハッチを指定します。 |

### 関連項目

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


