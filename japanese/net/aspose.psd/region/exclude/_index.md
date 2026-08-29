---
title: "Region.Exclude"
second_title: "Aspose.PSD for .NET API Reference"
description: "Region メソッド。この Region の内部で、指定された RectangleF 構造体と交差しない部分だけを保持するように更新します。"
type: docs
weight: 50
url: /ja/net/aspose.psd/region/exclude/
---
{{< psd/tize >}}
## Exclude(RectangleF) {#exclude_2}

この [`Region`](../) を、指定された [`RectangleF`](../../rectanglef/) 構造体と交差しない内部の部分だけを保持するように更新します。

```csharp
public void Exclude(RectangleF rect)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | RectangleF | この [`Region`](../) から除外するための [`RectangleF`](../../rectanglef/) 構造体です。 |

### 関連項目

* struct [RectangleF](../../rectanglef/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Exclude(Rectangle) {#exclude_1}

この [`Region`](../) を更新し、指定された [`Rectangle`](../../rectangle/) 構造体と交差しない内部の部分だけを含むようにします。

```csharp
public void Exclude(Rectangle rect)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | Rectangle | この [`Region`](../) から除外する [`Rectangle`](../../rectangle/) 構造体。 |

### 関連項目

* struct [Rectangle](../../rectangle/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Exclude(GraphicsPath) {#exclude}

この [`Region`](../) を更新し、指定された [`GraphicsPath`](../../graphicspath/) と交差しない内部の部分だけを含むようにします。

```csharp
public void Exclude(GraphicsPath path)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| path | GraphicsPath | この [`Region`](../) から除外する [`GraphicsPath`](../../graphicspath/)。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *path* は null です。 |

### 関連項目

* class [GraphicsPath](../../graphicspath/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Exclude(Region) {#exclude_3}

この [`Region`](../) を更新し、指定された [`Region`](../) と交差しない内部の部分だけを含むようにします。

```csharp
public void Exclude(Region region)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| region | Region | この [`Region`](../) から除外する [`Region`](../)。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *region* は null です。 |

### 関連項目

* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


