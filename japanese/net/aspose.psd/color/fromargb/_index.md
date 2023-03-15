---
title: Color.FromArgb
second_title: Aspose.PSD for .NET API リファレンス
description: Color 方法. を作成しますColor 32 ビット ARGB 値からの構造体.
type: docs
weight: 1430
url: /ja/net/aspose.psd/color/fromargb/
---
## FromArgb(int) {#fromargb}

を作成します[`Color`](../) 32 ビット ARGB 値からの構造体.

```csharp
public static Color FromArgb(int argb)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| argb | Int32 | 32 ビット ARGB 値を指定する値。 |

### 戻り値

の[`Color`](../)このメソッドが作成する構造。

### 関連項目

* struct [Color](../)
* 名前空間 [Aspose.PSD](../../color/)
* 組み立て [Aspose.PSD](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

を作成します[`Color`](../) 4 つの ARGB コンポーネント (アルファ、赤、緑、青) 値からの構造。このメソッドでは各コンポーネントに 32 ビットの値を渡すことができますが、各コンポーネントの値は 8 ビットに制限されています。

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| alpha | Int32 | アルファ成分。有効な値は 0 ～ 255 です。 |
| red | Int32 | 赤のコンポーネント。有効な値は 0 ～ 255 です。 |
| green | Int32 | 緑のコンポーネント。有効な値は 0 ～ 255 です。 |
| blue | Int32 | 青の成分。有効な値は 0 ～ 255 です。 |

### 戻り値

の[`Color`](../)このメソッドが作成するもの。

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* 、*red* 、*green* 、 また*blue* 未満または 255 より大きい。 |

### 関連項目

* struct [Color](../)
* 名前空間 [Aspose.PSD](../../color/)
* 組み立て [Aspose.PSD](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

を作成します[`Color`](../)指定された構造[`Color`](../)構造ですが、新しく指定されたアルファ値があります。このメソッドでは、アルファ値として 32 ビット値を渡すことができますが、値は 8 ビットに制限されています。

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| alpha | Int32 | 新しいのアルファ値[`Color`](../).有効な値は 0 ～ 255 です。 |
| baseColor | Color | の[`Color`](../)そこから新しいものを作成する[`Color`](../). |

### 戻り値

の[`Color`](../)このメソッドが作成するもの。

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* 未満または 255 より大きい。 |

### 関連項目

* struct [Color](../)
* 名前空間 [Aspose.PSD](../../color/)
* 組み立て [Aspose.PSD](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

を作成します[`Color`](../)指定された 8 ビットのカラー値 (赤、緑、青) からの構造体。アルファ値は暗黙的に 255 (完全に不透明) です。このメソッドでは、各色コンポーネントに 32 ビット値を渡すことができますが、各コンポーネントの値は 8 ビットに制限されています。

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| red | Int32 | 新しいコンポーネントの赤のコンポーネント値[`Color`](../).有効な値は 0 ～ 255 です。 |
| green | Int32 | 新しいのグリーン コンポーネント値[`Color`](../).有効な値は 0 ～ 255 です。 |
| blue | Int32 | 新しいの青のコンポーネント値[`Color`](../).有効な値は 0 ～ 255 です。 |

### 戻り値

の[`Color`](../)このメソッドが作成するもの。

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentOutOfRangeException | *red* 、*green* 、 また*blue* 未満または 255 より大きい。 |

### 関連項目

* struct [Color](../)
* 名前空間 [Aspose.PSD](../../color/)
* 組み立て [Aspose.PSD](../../../)


