---
title: "Region.IsVisible"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة Region. تختبر ما إذا كانت النقطة المحددة موجودة داخل هذا Region."
type: docs
weight: 100
url: /ar/net/aspose.psd/region/isvisible/
---
{{< psd/tize >}}
## IsVisible(float, float) {#isvisible_11}

تختبر ما إذا كانت النقطة المحددة موجودة داخل هذا [`Region`](../).

```csharp
public bool IsVisible(float x, float y)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Single | إحداثي x للنقطة التي سيتم اختبارها. |
| y | Single | إحداثي y للنقطة التي سيتم اختبارها. |

### قيمة الإرجاع

صحيح عندما تكون النقطة المحددة موجودة داخل هذا [`Region`](../)؛ وإلا، خطأ.

### انظر أيضًا

* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(PointF) {#isvisible_2}

تختبر ما إذا كانت بنية [`PointF`](../../pointf/) المحددة موجودة داخل هذا [`Region`](../).

```csharp
public bool IsVisible(PointF point)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| point | PointF | بنية [`PointF`](../../pointf/) للاختبار. |

### قيمة الإرجاع

صحيح عندما تكون *point* موجودة داخل هذا [`Region`](../)؛ وإلا، خطأ.

### انظر أيضًا

* struct [PointF](../../pointf/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(float, float, Graphics) {#isvisible_12}

تختبر ما إذا كانت النقطة المحددة موجودة داخل هذا [`Region`](../) عند رسمه باستخدام الـ[`Graphics`](../../graphics/).

```csharp
public bool IsVisible(float x, float y, Graphics g)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Single | إحداثي x للنقطة التي سيتم اختبارها. |
| y | Single | إحداثي y للنقطة التي سيتم اختبارها. |
| g | Graphics | الـ[`Graphics`](../../graphics/) الذي يمثل سياق رسومي. |

### قيمة الإرجاع

صحيح عندما تكون النقطة المحددة موجودة داخل هذا [`Region`](../)؛ وإلا، خطأ.

### انظر أيضًا

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(PointF, Graphics) {#isvisible_3}

تختبر ما إذا كانت بنية [`PointF`](../../pointf/) المحددة موجودة داخل هذا [`Region`](../) عند رسمه باستخدام الـ[`Graphics`](../../graphics/).

```csharp
public bool IsVisible(PointF point, Graphics g)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| point | PointF | بنية [`PointF`](../../pointf/) للاختبار. |
| g | Graphics | الـ[`Graphics`](../../graphics/) الذي يمثل سياق رسومي. |

### قيمة الإرجاع

صحيح عندما تكون *point* موجودة داخل هذا [`Region`](../)؛ وإلا، خطأ.

### انظر أيضًا

* struct [PointF](../../pointf/)
* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(float, float, float, float) {#isvisible_13}

تختبر ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا [`Region`](../).

```csharp
public bool IsVisible(float x, float y, float width, float height)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Single | إحداثي x للزاوية العلوية اليسرى للمستطيل المراد اختباره. |
| y | Single | إحداثي y للزاوية العلوية اليسرى للمستطيل المراد اختباره. |
| العرض | Single | عرض المستطيل المراد اختباره. |
| الارتفاع | Single | ارتفاع المستطيل المراد اختباره. |

### قيمة الإرجاع

صحيح عندما يكون أي جزء من المستطيل المحدد موجودًا داخل كائن [`Region`](../) هذا؛ وإلا، خطأ.

### انظر أيضًا

* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(RectangleF) {#isvisible_6}

تختبر ما إذا كان أي جزء من بنية [`RectangleF`](../../rectanglef/) المحددة موجودًا داخل هذا [`Region`](../).

```csharp
public bool IsVisible(RectangleF rect)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | RectangleF | بنية [`RectangleF`](../../rectanglef/) للاختبار. |

### قيمة الإرجاع

صحيح عندما يكون أي جزء من *rect* موجودًا داخل هذا [`Region`](../)؛ وإلا، خطأ.

### انظر أيضًا

* struct [RectangleF](../../rectanglef/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(float, float, float, float, Graphics) {#isvisible_14}

يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا [`Region`](../) عند رسمه باستخدام الـ[`Graphics`](../../graphics/).

```csharp
public bool IsVisible(float x, float y, float width, float height, Graphics g)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Single | إحداثي x للزاوية العلوية اليسرى للمستطيل المراد اختباره. |
| y | Single | إحداثي y للزاوية العلوية اليسرى للمستطيل المراد اختباره. |
| العرض | Single | عرض المستطيل المراد اختباره. |
| الارتفاع | Single | ارتفاع المستطيل المراد اختباره. |
| g | Graphics | الـ[`Graphics`](../../graphics/) الذي يمثل سياق رسومي. |

### قيمة الإرجاع

صحيح عندما يكون أي جزء من المستطيل المحدد موجودًا داخل هذا [`Region`](../)؛ وإلا، خطأ.

### انظر أيضًا

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(RectangleF, Graphics) {#isvisible_7}

يفحص ما إذا كان أي جزء من بنية [`RectangleF`](../../rectanglef/) المحددة موجودًا داخل هذا [`Region`](../) عند رسمه باستخدام الـ[`Graphics`](../../graphics/).

```csharp
public bool IsVisible(RectangleF rect, Graphics g)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | RectangleF | بنية [`RectangleF`](../../rectanglef/) للاختبار. |
| g | Graphics | الـ[`Graphics`](../../graphics/) الذي يمثل سياق رسومي. |

### قيمة الإرجاع

صحيح عندما يكون *rect* موجودًا داخل هذا [`Region`](../)؛ وإلا، خطأ.

### انظر أيضًا

* struct [RectangleF](../../rectanglef/)
* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(int, int, Graphics) {#isvisible_8}

يفحص ما إذا كانت النقطة المحددة موجودة داخل كائن هذا [`Region`](../) عند رسمه باستخدام كائن الـ[`Graphics`](../../graphics/).

```csharp
public bool IsVisible(int x, int y, Graphics g)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Int32 | إحداثي x للنقطة التي سيتم اختبارها. |
| y | Int32 | إحداثي y للنقطة التي سيتم اختبارها. |
| g | Graphics | الـ[`Graphics`](../../graphics/) الذي يمثل سياق رسومي. |

### قيمة الإرجاع

صحيح عندما تكون النقطة المحددة موجودة داخل هذا [`Region`](../)؛ وإلا، خطأ.

### انظر أيضًا

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(Point) {#isvisible}

يفحص ما إذا كانت بنية [`Point`](../../point/) المحددة موجودة داخل هذا [`Region`](../).

```csharp
public bool IsVisible(Point point)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| point | Point | بنية [`Point`](../../point/) للاختبار. |

### قيمة الإرجاع

صحيح عندما تكون *point* موجودة داخل هذا [`Region`](../)؛ وإلا، خطأ.

### انظر أيضًا

* struct [Point](../../point/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(Point, Graphics) {#isvisible_1}

يفحص ما إذا كانت بنية [`Point`](../../point/) المحددة موجودة داخل هذا [`Region`](../) عند رسمه باستخدام الـ[`Graphics`](../../graphics/).

```csharp
public bool IsVisible(Point point, Graphics g)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| point | Point | بنية [`Point`](../../point/) للاختبار. |
| g | Graphics | الـ[`Graphics`](../../graphics/) الذي يمثل سياق رسومي. |

### قيمة الإرجاع

صحيح عندما تكون *point* موجودة داخل هذا [`Region`](../)؛ وإلا، خطأ.

### انظر أيضًا

* struct [Point](../../point/)
* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(int, int, int, int) {#isvisible_9}

تختبر ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا [`Region`](../).

```csharp
public bool IsVisible(int x, int y, int width, int height)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Int32 | إحداثي x للزاوية العلوية اليسرى للمستطيل المراد اختباره. |
| y | Int32 | إحداثي y للزاوية العلوية اليسرى للمستطيل المراد اختباره. |
| العرض | Int32 | عرض المستطيل المراد اختباره. |
| الارتفاع | Int32 | ارتفاع المستطيل المراد اختباره. |

### قيمة الإرجاع

صحيح عندما يكون أي جزء من المستطيل المحدد موجودًا داخل هذا [`Region`](../)؛ وإلا، خطأ.

### انظر أيضًا

* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(Rectangle) {#isvisible_4}

يفحص ما إذا كان أي جزء من بنية [`Rectangle`](../../rectangle/) المحددة موجودًا داخل هذا [`Region`](../).

```csharp
public bool IsVisible(Rectangle rect)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | بنية [`Rectangle`](../../rectangle/) للاختبار. |

### قيمة الإرجاع

تُعيد هذه الطريقة صحيحًا عندما يكون أي جزء من *rect* موجودًا داخل هذا [`Region`](../)؛ وإلا، خطأ.

### انظر أيضًا

* struct [Rectangle](../../rectangle/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(int, int, int, int, Graphics) {#isvisible_10}

يفحص ما إذا كان أي جزء من المستطيل المحدد موجودًا داخل هذا [`Region`](../) عند رسمه باستخدام الـ[`Graphics`](../../graphics/).

```csharp
public bool IsVisible(int x, int y, int width, int height, Graphics g)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Int32 | إحداثي x للزاوية العلوية اليسرى للمستطيل المراد اختباره. |
| y | Int32 | إحداثي y للزاوية العلوية اليسرى للمستطيل المراد اختباره. |
| العرض | Int32 | عرض المستطيل المراد اختباره. |
| الارتفاع | Int32 | ارتفاع المستطيل المراد اختباره. |
| g | Graphics | الـ[`Graphics`](../../graphics/) الذي يمثل سياق رسومي. |

### قيمة الإرجاع

صحيح عندما يكون أي جزء من المستطيل المحدد موجودًا داخل هذا [`Region`](../)؛ وإلا، خطأ.

### انظر أيضًا

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## IsVisible(Rectangle, Graphics) {#isvisible_5}

يفحص ما إذا كان أي جزء من بنية [`Rectangle`](../../rectangle/) المحددة موجودًا داخل هذا [`Region`](../) عند رسمه باستخدام الـ[`Graphics`](../../graphics/).

```csharp
public bool IsVisible(Rectangle rect, Graphics g)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | Rectangle | بنية [`Rectangle`](../../rectangle/) للاختبار. |
| g | Graphics | الـ[`Graphics`](../../graphics/) الذي يمثل سياق رسومي. |

### قيمة الإرجاع

صحيح عندما يكون أي جزء من *rect* موجودًا داخل هذا [`Region`](../)؛ وإلا، خطأ.

### انظر أيضًا

* struct [Rectangle](../../rectangle/)
* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


