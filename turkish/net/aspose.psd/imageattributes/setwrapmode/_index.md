---
title: "ImageAttributes.SetWrapMode"
second_title: "Aspose.PSD for .NET API Referansı"
description: "ImageAttributes yöntemi. Bir doku şekil boyunca veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan sarma modunu ayarlar. Doku, doldurduğu şekilden daha küçük olduğunda şekil boyunca döşenerek doldurulur."
type: docs
weight: 210
url: /tr/net/aspose.psd/imageattributes/setwrapmode/
---
{{< psd/tize >}}
## SetWrapMode(WrapMode) {#setwrapmode}

Bir dokunun bir şekil üzerinde veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan sarma modunu ayarlar. Doku, dolduracağı şekilden daha küçük olduğunda, şekli doldurmak için şekil üzerine döşenir.

```csharp
public void SetWrapMode(WrapMode mode)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mode | WrapMode | Bir alanın döşenmesinde bir görüntünün tekrar eden kopyalarının nasıl kullanılacağını belirten bir [`WrapMode`](../../wrapmode/) öğesi. |

### Ayrıca Bakınız

* enum [WrapMode](../../wrapmode/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color) {#setwrapmode_1}

Bir dokunun bir şekil üzerinde veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan sarma modunu ve rengi ayarlar. Doku, dolduracağı şekilden daha küçük olduğunda, şekli doldurmak için şekil üzerine döşenir.

```csharp
public void SetWrapMode(WrapMode mode, Color color)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mode | WrapMode | Bir alanın döşenmesinde bir görüntünün tekrar eden kopyalarının nasıl kullanılacağını belirten bir [`WrapMode`](../../wrapmode/) öğesi. |
| color | Color | Bir [`ImageAttributes`](../) nesnesi, işlenmiş bir görüntünün dışındaki piksellerin rengini belirler. Bu renk, mod parametresi Clamp olarak ayarlandığında ve DrawImage'e geçirilen kaynak dikdörtgeni görüntünün kendisinden daha büyük olduğunda görünür. |

### Ayrıca Bakınız

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color, bool) {#setwrapmode_2}

Bir dokunun bir şekil üzerinde veya şekil sınırlarında nasıl döşeneceğine karar vermek için kullanılan sarma modunu ve rengi ayarlar. Doku, dolduracağı şekilden daha küçük olduğunda, şekli doldurmak için şekil üzerine döşenir.

```csharp
public void SetWrapMode(WrapMode mode, Color color, bool clamp)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mode | WrapMode | Bir alanın döşenmesinde bir görüntünün tekrar eden kopyalarının nasıl kullanılacağını belirten bir [`WrapMode`](../../wrapmode/) öğesi. |
| renk | Renk | İşlenmiş bir görüntünün dışındaki piksellerin rengini belirten bir renk nesnesi. Bu renk, mod parametresi Clamp olarak ayarlandığında ve DrawImage'e geçirilen kaynak dikdörtgeni görüntünün kendisinden daha büyük olduğunda görünür. |
| clamp | Boolean | Bu parametrenin bir etkisi yoktur. False olarak ayarlayın. |

### Ayrıca Bakınız

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


