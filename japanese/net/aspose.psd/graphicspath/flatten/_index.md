---
title: "GraphicsPath.Flatten"
second_title: "Aspose.PSD for .NET API Reference"
description: "GraphicsPath メソッド。このパス内の各曲線を連続した線分のシーケンスに変換します"
type: docs
weight: 90
url: /ja/net/aspose.psd/graphicspath/flatten/
---
{{< psd/tize >}}
## Flatten() {#flatten}

このパス内の各曲線を連続した線分のシーケンスに変換します。

```csharp
public void Flatten()
```

### 関連項目

* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Flatten(Matrix) {#flatten_1}

指定された変換を適用し、次にこの [`GraphicsPath`](../) の各曲線を連続した線分のシーケンスに変換します。

```csharp
public void Flatten(Matrix matrix)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | Matrix | 平坦化する前にこの [`GraphicsPath`](../) を変換するための [`Matrix`](../../matrix/)。 |

### 関連項目

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Flatten(Matrix, float) {#flatten_2}

この [`GraphicsPath`](../) の各曲線を連続した線分のシーケンスに変換します。

```csharp
public void Flatten(Matrix matrix, float flatness)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | Matrix | 平坦化する前にこの [`GraphicsPath`](../) を変換するための [`Matrix`](../../matrix/)。 |
| 平滑度 | シングル | 曲線とその平坦化近似との間の許容最大誤差を指定します。デフォルト値は 0.25 です。フラットネス値を小さくすると、近似における線分の数が増加します。 |

### 関連項目

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


