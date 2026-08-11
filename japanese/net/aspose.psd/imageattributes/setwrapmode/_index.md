---
title: "ImageAttributes.SetWrapMode"
second_title: "Aspose.PSD for .NET API Reference"
description: "ImageAttributes メソッド。テクスチャを形状全体または形状境界にタイル配置する方法を決定するラップモードを設定します。テクスチャが対象の形状より小さい場合、テクスチャは形状全体にタイル配置されて埋められます。"
type: docs
weight: 210
url: /ja/net/aspose.psd/imageattributes/setwrapmode/
---
{{< psd/tize >}}
## SetWrapMode(WrapMode) {#setwrapmode}

テクスチャをシェイプ全体またはシェイプの境界でタイル状に配置する方法を決定するために使用されるラップモードを設定します。テクスチャがシェイプより小さい場合、テクスチャはシェイプ全体を埋めるようにタイル状に配置されます。

```csharp
public void SetWrapMode(WrapMode mode)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mode | WrapMode | [`WrapMode`](../../wrapmode/) の要素で、画像の繰り返しコピーがエリアにタイル配置される方法を指定します。 |

### 関連項目

* enum [WrapMode](../../wrapmode/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color) {#setwrapmode_1}

テクスチャをシェイプ全体またはシェイプの境界でタイル状に配置する方法を決定するために使用されるラップモードとカラーを設定します。テクスチャがシェイプより小さい場合、テクスチャはシェイプ全体を埋めるようにタイル状に配置されます。

```csharp
public void SetWrapMode(WrapMode mode, Color color)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mode | WrapMode | [`WrapMode`](../../wrapmode/) の要素で、画像の繰り返しコピーがエリアにタイル配置される方法を指定します。 |
| color | Color | [`ImageAttributes`](../) オブジェクトで、レンダリングされた画像の外側のピクセルの色を指定します。モードパラメータが Clamp に設定され、DrawImage に渡されるソース矩形が画像自体より大きい場合にこの色が表示されます。 |

### 関連項目

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color, bool) {#setwrapmode_2}

テクスチャをシェイプ全体またはシェイプの境界でタイル状に配置する方法を決定するために使用されるラップモードとカラーを設定します。テクスチャがシェイプより小さい場合、テクスチャはシェイプ全体を埋めるようにタイル状に配置されます。

```csharp
public void SetWrapMode(WrapMode mode, Color color, bool clamp)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mode | WrapMode | [`WrapMode`](../../wrapmode/) の要素で、画像の繰り返しコピーがエリアにタイル配置される方法を指定します。 |
| 色 | 色 | レンダリングされた画像の外側のピクセルの色を指定するカラーオブジェクトです。モードパラメータが Clamp に設定され、DrawImage に渡されるソース矩形が画像自体より大きい場合にこの色が表示されます。 |
| クランプ | Boolean | このパラメーターは効果がありません。false に設定してください。 |

### 関連項目

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


