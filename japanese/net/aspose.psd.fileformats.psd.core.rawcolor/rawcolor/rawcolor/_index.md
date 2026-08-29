---
title: "RawColor.RawColor"
second_title: "Aspose.PSD for .NET API Reference"
description: "RawColor コンストラクタ。RawColor クラスの新しいインスタンスを初期化します"
type: docs
weight: 10
url: /ja/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/rawcolor/
---
{{< psd/tize >}}
## RawColor(ColorComponent[]) {#constructor}

[`RawColor`](../) クラスの新しいインスタンスを初期化します。

```csharp
public RawColor(ColorComponent[] components)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| コンポーネント | ColorComponent[] | カスタム カラー コンポーネント。 |

### 関連項目

* class [ColorComponent](../../colorcomponent/)
* class [RawColor](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)

---

## RawColor(PixelDataFormat, short) {#constructor_1}

[`RawColor`](../) クラスの新しいインスタンスを、事前定義されたカラーモードを使用してピクセル データ フォーマットから初期化します。

```csharp
public RawColor(PixelDataFormat pixelDataFormat, short colorMode = 0)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pixelDataFormat | PixelDataFormat | ピクセル データ フォーマット。 |
| カラーモード | Int16 | 従うべきカラーのモードです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | チャンネル数が PixelFormat と異なり、チャンネルのインデックスを取得できません。Components の配列引数で RawColor を作成してください。 |

### 関連項目

* class [PixelDataFormat](../../../aspose.psd/pixeldataformat/)
* class [RawColor](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


