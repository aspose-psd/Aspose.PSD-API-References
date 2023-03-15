---
title: Font.Font
second_title: Aspose.PSD for .NET API リファレンス
description: Font コンストラクタ. 新しいFont指定された既存のFontとFontStyle列挙.
type: docs
weight: 10
url: /ja/net/aspose.psd/font/font/
---
## Font(Font, FontStyle) {#constructor}

新しい[`Font`](../)指定された既存の[`Font`](../)と[`FontStyle`](../../fontstyle/)列挙.

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| prototype | Font | 既存の[`Font`](../)そこから新しいものを作成する[`Font`](../). |
| newStyle | FontStyle | の[`FontStyle`](../../fontstyle/)新規に申し込む[`Font`](../).の複数の値[`FontStyle`](../../fontstyle/)列挙は OR 演算子と組み合わせることができます。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentNullException | *prototype*無効である。 |

### 関連項目

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* 名前空間 [Aspose.PSD](../../font/)
* 組み立て [Aspose.PSD](../../../)

---

## Font(string, float) {#constructor_1}

新しい[`Font`](../)指定サイズを使用。文字セットはDefault、グラフィックスユニットをPoint、フォント スタイルRegular .

```csharp
public Font(string fontName, float emSize)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fontName | String | の文字列表現[`Font`](../)名前。 |
| emSize | Single | 新しいフォントの em サイズ (ポイント単位)。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentOutOfRangeException | *emSize*が 0 以下であるか、無限に評価されるか、有効な数値ではありません。 |
| ArgumentNullException | *fontName*無効である。 |

### 関連項目

* class [Font](../)
* 名前空間 [Aspose.PSD](../../font/)
* 組み立て [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

新しい[`Font`](../)指定されたサイズとスタイルを使用します。文字セットはDefault、グラフィックスユニットをPoint .

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fontName | String | の文字列表現[`Font`](../)名前。 |
| emSize | Single | 新しいフォントの em サイズ (ポイント単位)。 |
| style | FontStyle | の[`FontStyle`](../../fontstyle/)新しいフォントの。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentOutOfRangeException | *emSize*が 0 以下であるか、無限に評価されるか、有効な数値ではありません。 |
| ArgumentNullException | *fontName*無効である。 |

### 関連項目

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* 名前空間 [Aspose.PSD](../../font/)
* 組み立て [Aspose.PSD](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

新しい[`Font`](../)指定されたサイズと単位を使用します。文字セットはDefault、スタイルはに設定されていますRegular .

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fontName | String | の文字列表現[`Font`](../)名前。 |
| emSize | Single | によって指定された単位での新しいフォントの全角サイズ。*unit*パラメータ。 |
| unit | GraphicsUnit | の[`GraphicsUnit`](../../graphicsunit/)新しいフォントの。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentOutOfRangeException | *emSize*が 0 以下であるか、無限に評価されるか、有効な数値ではありません。 |
| ArgumentNullException | *fontName*無効である。 |

### 関連項目

* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* 名前空間 [Aspose.PSD](../../font/)
* 組み立て [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

新しい[`Font`](../)指定されたサイズ、スタイル、単位、および文字セットを使用します。

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fontName | String | の文字列表現[`Font`](../)名前。 |
| emSize | Single | によって指定された単位での新しいフォントの全角サイズ。*unit*パラメータ。 |
| style | FontStyle | の[`FontStyle`](../../fontstyle/)新しいフォントの。 |
| unit | GraphicsUnit | の[`GraphicsUnit`](../../graphicsunit/)新しいフォントの。 |
| characterSet | CharacterSet | このフォントに使用する文字セット。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentOutOfRangeException | *emSize*が 0 以下であるか、無限に評価されるか、有効な数値ではありません。 |
| ArgumentNullException | *fontName*無効である。 |

### 関連項目

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* enum [CharacterSet](../../characterset/)
* class [Font](../)
* 名前空間 [Aspose.PSD](../../font/)
* 組み立て [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

新しい[`Font`](../)指定されたサイズ、スタイル、および単位を使用します。

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| fontName | String | の文字列表現[`Font`](../)名前。 |
| emSize | Single | によって指定された単位での新しいフォントの全角サイズ。*unit*パラメータ。 |
| style | FontStyle | の[`FontStyle`](../../fontstyle/)新しいフォントの。 |
| unit | GraphicsUnit | の[`GraphicsUnit`](../../graphicsunit/)新しいフォントの。 |

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentOutOfRangeException | *emSize*が 0 以下であるか、無限に評価されるか、有効な数値ではありません。 |
| ArgumentNullException | *fontName*無効である。 |

### 関連項目

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* 名前空間 [Aspose.PSD](../../font/)
* 組み立て [Aspose.PSD](../../../)


