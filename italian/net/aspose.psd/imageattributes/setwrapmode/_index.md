---
title: ImageAttributes.SetWrapMode
second_title: Aspose.PSD per riferimento API .NET
description: ImageAttributes metodo. Imposta la modalità di avvolgimento utilizzata per decidere come affiancare una trama attraverso una forma o ai limiti della forma. Una trama viene affiancata a una forma per riempirla quando la trama è più piccola della forma che sta riempiendo.
type: docs
weight: 210
url: /it/net/aspose.psd/imageattributes/setwrapmode/
---
## SetWrapMode(WrapMode) {#setwrapmode}

Imposta la modalità di avvolgimento utilizzata per decidere come affiancare una trama attraverso una forma o ai limiti della forma. Una trama viene affiancata a una forma per riempirla quando la trama è più piccola della forma che sta riempiendo.

```csharp
public void SetWrapMode(WrapMode mode)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mode | WrapMode | Un elemento di[`WrapMode`](../../wrapmode/) che specifica come vengono utilizzate copie ripetute di un'immagine per affiancare un'area. |

### Guarda anche

* enum [WrapMode](../../wrapmode/)
* class [ImageAttributes](../)
* spazio dei nomi [Aspose.PSD](../../imageattributes/)
* assemblea [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color) {#setwrapmode_1}

Imposta la modalità di avvolgimento e il colore utilizzati per decidere come affiancare una trama attraverso una forma o ai limiti della forma. Una trama viene affiancata a una forma per riempirla quando la trama è più piccola della forma che sta riempiendo.

```csharp
public void SetWrapMode(WrapMode mode, Color color)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mode | WrapMode | Un elemento di[`WrapMode`](../../wrapmode/) che specifica come vengono utilizzate copie ripetute di un'immagine per affiancare un'area. |
| color | Color | UN[`ImageAttributes`](../) oggetto che specifica il colore dei pixel all'esterno di un'immagine renderizzata. Questo colore è visibile se il parametro mode è impostato suClamp e il rettangolo di origine passato a DrawImage è più grande dell'immagine stessa. |

### Guarda anche

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* spazio dei nomi [Aspose.PSD](../../imageattributes/)
* assemblea [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color, bool) {#setwrapmode_2}

Imposta la modalità di avvolgimento e il colore utilizzati per decidere come affiancare una trama attraverso una forma o ai limiti della forma. Una trama viene affiancata a una forma per riempirla quando la trama è più piccola della forma che sta riempiendo.

```csharp
public void SetWrapMode(WrapMode mode, Color color, bool clamp)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mode | WrapMode | Un elemento di[`WrapMode`](../../wrapmode/) che specifica come vengono utilizzate copie ripetute di un'immagine per affiancare un'area. |
| color | Color | Un oggetto color che specifica il colore dei pixel all'esterno di un'immagine di rendering. Questo colore è visibile se il parametro mode è impostato suClamp e il rettangolo di origine passato a DrawImage è più grande dell'immagine stessa. |
| clamp | Boolean | Questo parametro non ha effetto. Impostalo su falso. |

### Guarda anche

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* spazio dei nomi [Aspose.PSD](../../imageattributes/)
* assemblea [Aspose.PSD](../../../)


