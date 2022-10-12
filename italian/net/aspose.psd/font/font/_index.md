---
title: Font
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Inizializza un nuovoFontaspose.psd/font che utilizza lesistente specificatoFontaspose.psd/font eFontStyleaspose.psd/fontstyle enumerazione.
type: docs
weight: 10
url: /it/net/aspose.psd/font/font/
---
## Font(Font, FontStyle) {#constructor}

Inizializza un nuovo[`Font`](../../font) che utilizza l'esistente specificato[`Font`](../../font) e[`FontStyle`](../../fontstyle) enumerazione.

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prototype | Font | L'esistente[`Font`](../../font) da cui creare il nuovo[`Font`](../../font). |
| newStyle | FontStyle | Il[`FontStyle`](../../fontstyle) da applicare al nuovo[`Font`](../../font) . Valori multipli di[`FontStyle`](../../fontstyle) l'enumerazione può essere combinata con l'operatore OR. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *prototype* è zero. |

### Guarda anche

* enum [FontStyle](../../fontstyle)
* class [Font](../../font)
* spazio dei nomi [Aspose.PSD](../../font)
* assemblea [Aspose.PSD](../../../)

---

## Font(string, float) {#constructor_1}

Inizializza un nuovo[`Font`](../../font) utilizzando una dimensione specificata. Il set di caratteri è impostato suDefault , l'unità grafica suPoint , lo stile del carattere aRegular .

```csharp
public Font(string fontName, float emSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | String | Una rappresentazione in stringa di[`Font`](../../font) nome. |
| emSize | Single | La dimensione em, in punti, del nuovo font. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* è minore o uguale a 0, restituisce infinito o non è un numero valido. |
| ArgumentNullException | *fontName* è zero. |

### Guarda anche

* class [Font](../../font)
* spazio dei nomi [Aspose.PSD](../../font)
* assemblea [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

Inizializza un nuovo[`Font`](../../font) utilizzando una dimensione e uno stile specificati. Il set di caratteri è impostato suDefault , l'unità grafica suPoint .

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | String | Una rappresentazione in stringa di[`Font`](../../font) nome. |
| emSize | Single | La dimensione em, in punti, del nuovo font. |
| style | FontStyle | Il[`FontStyle`](../../fontstyle) del nuovo carattere. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* è minore o uguale a 0, restituisce infinito o non è un numero valido. |
| ArgumentNullException | *fontName* è zero. |

### Guarda anche

* enum [FontStyle](../../fontstyle)
* class [Font](../../font)
* spazio dei nomi [Aspose.PSD](../../font)
* assemblea [Aspose.PSD](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

Inizializza un nuovo[`Font`](../../font) utilizzando una dimensione e un'unità specificate. Il set di caratteri è impostato suDefault lo stile è impostato suRegular .

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | String | Una rappresentazione in stringa di[`Font`](../../font) nome. |
| emSize | Single | La dimensione em del nuovo font nelle unità specificate da*unit* parametro. |
| unit | GraphicsUnit | Il[`GraphicsUnit`](../../graphicsunit) del nuovo carattere. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* è minore o uguale a 0, restituisce infinito o non è un numero valido. |
| ArgumentNullException | *fontName* è zero. |

### Guarda anche

* enum [GraphicsUnit](../../graphicsunit)
* class [Font](../../font)
* spazio dei nomi [Aspose.PSD](../../font)
* assemblea [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

Inizializza un nuovo[`Font`](../../font) utilizzando una dimensione, uno stile, un'unità e un set di caratteri specificati.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | String | Una rappresentazione in stringa di[`Font`](../../font) nome. |
| emSize | Single | La dimensione em del nuovo font nelle unità specificate da*unit* parametro. |
| style | FontStyle | Il[`FontStyle`](../../fontstyle) del nuovo carattere. |
| unit | GraphicsUnit | Il[`GraphicsUnit`](../../graphicsunit) del nuovo carattere. |
| characterSet | CharacterSet | Un set di caratteri da utilizzare per questo font. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* è minore o uguale a 0, restituisce infinito o non è un numero valido. |
| ArgumentNullException | *fontName* è zero. |

### Guarda anche

* enum [FontStyle](../../fontstyle)
* enum [GraphicsUnit](../../graphicsunit)
* enum [CharacterSet](../../characterset)
* class [Font](../../font)
* spazio dei nomi [Aspose.PSD](../../font)
* assemblea [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

Inizializza un nuovo[`Font`](../../font) utilizzando una dimensione, uno stile e un'unità specificati.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | String | Una rappresentazione in stringa di[`Font`](../../font) nome. |
| emSize | Single | La dimensione em del nuovo font nelle unità specificate da*unit* parametro. |
| style | FontStyle | Il[`FontStyle`](../../fontstyle) del nuovo carattere. |
| unit | GraphicsUnit | Il[`GraphicsUnit`](../../graphicsunit) del nuovo carattere. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* è minore o uguale a 0, restituisce infinito o non è un numero valido. |
| ArgumentNullException | *fontName* è zero. |

### Guarda anche

* enum [FontStyle](../../fontstyle)
* enum [GraphicsUnit](../../graphicsunit)
* class [Font](../../font)
* spazio dei nomi [Aspose.PSD](../../font)
* assemblea [Aspose.PSD](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
