---
title: "Region.Equals"
second_title: "Aspose.PSD for .NET API Reference"
description: "Region メソッド。指定された描画面上で、指定された Region がこの Region と同一かどうかテストします。"
type: docs
weight: 40
url: /ja/net/aspose.psd/region/equals/
---
{{< psd/tize >}}
## Equals(Region, Graphics) {#equals}

指定された描画面上で、指定された [`Region`](../) がこの [`Region`](../) と同一かどうかテストします。

```csharp
public bool Equals(Region region, Graphics g)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| region | Region | テスト対象の [`Region`](../)。 |
| g | Graphics | 描画サーフェスを表す [`Graphics`](../../graphics/) です。 |

### 戻り値

*g* パラメータに関連付けられた変換が適用されたとき、領域の内部がこの領域の内部と同一である場合は true、そうでない場合は false。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *g* または *region* が null です。 |

### 関連項目

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Equals(object) {#equals_1}

オブジェクトが等しいかどうかを確認します。

```csharp
public override bool Equals(object obj)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | Object | 他のオブジェクトです。 |

### 戻り値

等価比較の結果です。

### 関連項目

* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


