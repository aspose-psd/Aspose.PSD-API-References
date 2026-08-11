---
title: "Font.Font"
second_title: "Aspose.PSD for .NET API Reference"
description: "Font コンストラクター。指定された既存の Font と FontStyle 列挙体を使用する新しい Font を初期化します。"
type: docs
weight: 10
url: /ja/net/aspose.psd/font/font/
---
{{< psd/tize >}}
## Font(Font, FontStyle) {#constructor}

指定された既存の[`Font`](../)と[`FontStyle`](../../fontstyle/)列挙体を使用する新しい[`Font`](../)を初期化します。

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| prototype | Font | 新しい[`Font`](../)を作成する元となる既存の[`Font`](../)です。 |
| newStyle | FontStyle | 新しい[`Font`](../)に適用する[`FontStyle`](../../fontstyle/)です。[`FontStyle`](../../fontstyle/)列挙体の複数の値は OR 演算子で組み合わせることができます。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *prototype* は null です。 |

### 関連項目

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float) {#constructor_1}

指定されたサイズを使用して新しい[`Font`](../)を初期化します。文字セットは Default に、グラフィック単位は Point に、フォントスタイルは Regular に設定されます。

```csharp
public Font(string fontName, float emSize)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontName | String | [`Font`](../) 名の文字列表現です。 |
| emSize | シングル | 新しいフォントの em サイズ（ポイント単位）です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* が 0 以下、無限大になる、または有効な数値でない場合です。 |
| ArgumentNullException | *fontName* は null です。 |

### 関連項目

* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

指定されたサイズとスタイルを使用して新しい[`Font`](../)を初期化します。文字セットは Default に、グラフィック単位は Point に設定されます。

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontName | String | [`Font`](../) 名の文字列表現です。 |
| emSize | シングル | 新しいフォントの em サイズ（ポイント単位）です。 |
| style | FontStyle | 新しいフォントの[`FontStyle`](../../fontstyle/)です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* が 0 以下、無限大になる、または有効な数値でない場合です。 |
| ArgumentNullException | *fontName* は null です。 |

### 関連項目

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

指定されたサイズと単位を使用して新しい[`Font`](../)を初期化します。文字セットは Default に、スタイルは Regular に設定されます。

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontName | String | [`Font`](../) 名の文字列表現です。 |
| emSize | シングル | *unit* パラメーターで指定された単位での新しいフォントの em サイズです。 |
| unit | GraphicsUnit | 新しいフォントの[`GraphicsUnit`](../../graphicsunit/)です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* が 0 以下、無限大になる、または有効な数値でない場合です。 |
| ArgumentNullException | *fontName* は null です。 |

### 関連項目

* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

指定されたサイズ、スタイル、単位、文字セットを使用して新しい[`Font`](../)を初期化します。

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontName | String | [`Font`](../) 名の文字列表現です。 |
| emSize | シングル | *unit* パラメーターで指定された単位での新しいフォントの em サイズです。 |
| style | FontStyle | 新しいフォントの[`FontStyle`](../../fontstyle/)です。 |
| unit | GraphicsUnit | 新しいフォントの[`GraphicsUnit`](../../graphicsunit/)です。 |
| characterSet | CharacterSet | このフォントで使用する文字セットです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* が 0 以下、無限大になる、または有効な数値でない場合です。 |
| ArgumentNullException | *fontName* は null です。 |

### 関連項目

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* enum [CharacterSet](../../characterset/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

指定されたサイズ、スタイル、単位を使用して新しい[`Font`](../)を初期化します。

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontName | String | [`Font`](../) 名の文字列表現です。 |
| emSize | シングル | *unit* パラメーターで指定された単位での新しいフォントの em サイズです。 |
| style | FontStyle | 新しいフォントの[`FontStyle`](../../fontstyle/)です。 |
| unit | GraphicsUnit | 新しいフォントの[`GraphicsUnit`](../../graphicsunit/)です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* が 0 以下、無限大になる、または有効な数値でない場合です。 |
| ArgumentNullException | *fontName* は null です。 |

### 関連項目

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


