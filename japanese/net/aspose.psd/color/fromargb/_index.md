---
title: "Color.FromArgb"
second_title: "Aspose.PSD for .NET API Reference"
description: "Color メソッド。32 ビット ARGB 値から Color 構造体を作成します"
type: docs
weight: 1430
url: /ja/net/aspose.psd/color/fromargb/
---
{{< psd/tize >}}
## FromArgb(int) {#fromargb}

32 ビット ARGB 値から [`Color`](../) 構造体を作成します。

```csharp
public static Color FromArgb(int argb)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| argb | Int32 | 32 ビット ARGB 値を指定する値です。 |

### 戻り値

このメソッドが作成する [`Color`](../) 構造体です。

### 関連項目

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

アルファ、赤、緑、青の 4 つの ARGB コンポーネント値から [`Color`](../) 構造体を作成します。このメソッドは各コンポーネントに 32 ビットの値を渡すことを許可しますが、各コンポーネントの値は 8 ビットに制限されます。

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| alpha | Int32 | アルファ コンポーネント。有効な値は 0 から 255 です。 |
| 赤 | Int32 | 赤成分。 有効な値は0から255です。 |
| 緑 | Int32 | 緑成分。 有効な値は0から255です。 |
| 青 | Int32 | 青成分。 有効な値は0から255です。 |

### 戻り値

このメソッドが作成する [`Color`](../) です。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | *alpha*、*red*、*green*、または*blue*が0未満または255より大きいです。 |

### 関連項目

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

指定された[`Color`](../)構造体から新しい[`Color`](../)構造体を作成しますが、アルファ値は新しく指定されたものです。このメソッドはアルファ値に32ビットの値を渡すことを許可しますが、値は8ビットに制限されます。

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| alpha | Int32 | 新しい[`Color`](../)のアルファ値です。 有効な値は0から255です。 |
| baseColor | Color | 新しい[`Color`](../)を作成する元となる[`Color`](../)です。 |

### 戻り値

このメソッドが作成する [`Color`](../) です。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | *alpha*が0未満または255より大きいです。 |

### 関連項目

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

指定された8ビットカラー値（赤、緑、青）から[`Color`](../)構造体を作成します。アルファ値は暗黙的に255（完全に不透明）です。このメソッドは各カラーコンポーネントに32ビットの値を渡すことを許可しますが、各コンポーネントの値は8ビットに制限されます。

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| red | Int32 | 新しい[`Color`](../)の赤成分値です。 有効な値は0から255です。 |
| green | Int32 | 新しい[`Color`](../)の緑成分値です。 有効な値は0から255です。 |
| blue | Int32 | 新しい[`Color`](../)の青成分値です。 有効な値は0から255です。 |

### 戻り値

このメソッドが作成する [`Color`](../) です。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | *red*、*green*、または*blue*が0未満または255より大きいです。 |

### 関連項目

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


