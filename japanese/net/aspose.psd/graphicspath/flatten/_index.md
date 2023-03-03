---
title: GraphicsPath.Flatten
second_title: Aspose.PSD for .NET API リファレンス
description: GraphicsPath 方法. このパスの各曲線を一連の接続された線分に変換します
type: docs
weight: 90
url: /ja/net/aspose.psd/graphicspath/flatten/
---
## Flatten() {#flatten}

このパスの各曲線を一連の接続された線分に変換します。

```csharp
public void Flatten()
```

### 関連項目

* class [GraphicsPath](../)
* 名前空間 [Aspose.PSD](../../graphicspath/)
* 組み立て [Aspose.PSD](../../../)

---

## Flatten(Matrix) {#flatten_1}

指定された変換を適用してから、この中の各曲線を変換します[`GraphicsPath`](../)一連の接続された線分に変換します。

```csharp
public void Flatten(Matrix matrix)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| matrix | Matrix | あ[`Matrix`](../../matrix/)これを変換する方法[`GraphicsPath`](../)平らにする前。 |

### 関連項目

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* 名前空間 [Aspose.PSD](../../graphicspath/)
* 組み立て [Aspose.PSD](../../../)

---

## Flatten(Matrix, float) {#flatten_2}

この中の各曲線を変換します[`GraphicsPath`](../)一連の接続された線分に変換します。

```csharp
public void Flatten(Matrix matrix, float flatness)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| matrix | Matrix | あ[`Matrix`](../../matrix/)これを変換する方法[`GraphicsPath`](../)平らにする前。 |
| flatness | Single | 曲線とその平坦化された近似値との間の最大許容誤差を指定します。デフォルト値は 0.25 です。平坦度の値を下げると、近似の線分の数が増えます。 |

### 関連項目

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* 名前空間 [Aspose.PSD](../../graphicspath/)
* 組み立て [Aspose.PSD](../../../)


