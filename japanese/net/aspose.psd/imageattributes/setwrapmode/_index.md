---
title: ImageAttributes.SetWrapMode
second_title: Aspose.PSD for .NET API リファレンス
description: ImageAttributes 方法. シェイプ全体またはシェイプ境界でテクスチャをタイリングする方法を決定するために使用されるラップ モードを設定しますテクスチャが塗りつぶしている形状よりも小さい場合テクスチャは形状全体にタイル張りされて塗りつぶされます.
type: docs
weight: 210
url: /ja/net/aspose.psd/imageattributes/setwrapmode/
---
## SetWrapMode(WrapMode) {#setwrapmode}

シェイプ全体またはシェイプ境界でテクスチャをタイリングする方法を決定するために使用されるラップ モードを設定します。テクスチャが塗りつぶしている形状よりも小さい場合、テクスチャは形状全体にタイル張りされて塗りつぶされます.

```csharp
public void SetWrapMode(WrapMode mode)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| mode | WrapMode | の要素[`WrapMode`](../../wrapmode/)これは、画像の繰り返しコピーを使用して領域をタイル化する方法を指定します。 |

### 関連項目

* enum [WrapMode](../../wrapmode/)
* class [ImageAttributes](../)
* 名前空間 [Aspose.PSD](../../imageattributes/)
* 組み立て [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color) {#setwrapmode_1}

シェイプ全体またはシェイプ境界でテクスチャをタイル化する方法を決定するために使用されるラップ モードと色を設定します。テクスチャが塗りつぶしている形状よりも小さい場合、テクスチャは形状全体にタイル張りされて塗りつぶされます.

```csharp
public void SetWrapMode(WrapMode mode, Color color)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| mode | WrapMode | の要素[`WrapMode`](../../wrapmode/)これは、画像の繰り返しコピーを使用して領域をタイル化する方法を指定します。 |
| color | Color | アン[`ImageAttributes`](../)レンダリングされたイメージの外側のピクセルの色を指定するオブジェクト。この色は、モード パラメータが に設定されている場合に表示されます。Clamp DrawImage に渡されたソースの四角形は、画像自体よりも大きいです。 |

### 関連項目

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* 名前空間 [Aspose.PSD](../../imageattributes/)
* 組み立て [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color, bool) {#setwrapmode_2}

シェイプ全体またはシェイプ境界でテクスチャをタイル化する方法を決定するために使用されるラップ モードと色を設定します。テクスチャが塗りつぶしている形状よりも小さい場合、テクスチャは形状全体にタイル張りされて塗りつぶされます.

```csharp
public void SetWrapMode(WrapMode mode, Color color, bool clamp)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| mode | WrapMode | の要素[`WrapMode`](../../wrapmode/)これは、画像の繰り返しコピーを使用して領域をタイル化する方法を指定します。 |
| color | Color | レンダリングされたイメージの外側のピクセルの色を指定する色オブジェクト。この色は、モード パラメータが に設定されている場合に表示されます。Clamp DrawImage に渡されたソースの四角形は、画像自体よりも大きいです。 |
| clamp | Boolean | このパラメータは無効です。 false に設定します。 |

### 関連項目

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* 名前空間 [Aspose.PSD](../../imageattributes/)
* 組み立て [Aspose.PSD](../../../)


