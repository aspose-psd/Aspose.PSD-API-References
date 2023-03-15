---
title: Font.Font
second_title: Aspose.PSD per riferimento API .NET
description: Font costruttore. Inizializza un nuovoFont che utilizza lesistente specificatoFont EFontStyle enumerazione.
type: docs
weight: 10
url: /it/net/aspose.psd/font/font/
---
## Font(Font, FontStyle) {#constructor}

Inizializza un nuovo[`Font`](../) che utilizza l'esistente specificato[`Font`](../) E[`FontStyle`](../../fontstyle/) enumerazione.

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prototype | Font | L'esistente[`Font`](../) da cui creare il nuovo[`Font`](../). |
| newStyle | FontStyle | IL[`FontStyle`](../../fontstyle/) applicare al nuovo[`Font`](../) . Valori multipli di[`FontStyle`](../../fontstyle/) l'enumerazione può essere combinata con l'operatore OR. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | *prototype* è zero. |

### Guarda anche

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* spazio dei nomi [Aspose.PSD](../../font/)
* assemblea [Aspose.PSD](../../../)

---

## Font(string, float) {#constructor_1}

Inizializza un nuovo[`Font`](../) utilizzando una dimensione specificata. Il set di caratteri è impostato suDefault , l'unità grafica aPoint , lo stile del carattere aRegular .

```csharp
public Font(string fontName, float emSize)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | String | Una rappresentazione di stringa del[`Font`](../) nome. |
| emSize | Single | La dimensione em, in punti, del nuovo font. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* è minore o uguale a 0, restituisce infinito o non è un numero valido. |
| ArgumentNullException | *fontName* è zero. |

### Guarda anche

* class [Font](../)
* spazio dei nomi [Aspose.PSD](../../font/)
* assemblea [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

Inizializza un nuovo[`Font`](../) utilizzando una dimensione e uno stile specificati. Il set di caratteri è impostato suDefault , l'unità grafica aPoint .

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | String | Una rappresentazione di stringa del[`Font`](../) nome. |
| emSize | Single | La dimensione em, in punti, del nuovo font. |
| style | FontStyle | IL[`FontStyle`](../../fontstyle/) del nuovo carattere. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* è minore o uguale a 0, restituisce infinito o non è un numero valido. |
| ArgumentNullException | *fontName* è zero. |

### Guarda anche

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* spazio dei nomi [Aspose.PSD](../../font/)
* assemblea [Aspose.PSD](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

Inizializza un nuovo[`Font`](../) utilizzando una dimensione e un'unità specificate. Il set di caratteri è impostato suDefault lo stile è impostato suRegular .

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | String | Una rappresentazione di stringa del[`Font`](../) nome. |
| emSize | Single | La dimensione em del nuovo carattere nelle unità specificate da*unit* parametro. |
| unit | GraphicsUnit | IL[`GraphicsUnit`](../../graphicsunit/) del nuovo carattere. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* è minore o uguale a 0, restituisce infinito o non è un numero valido. |
| ArgumentNullException | *fontName* è zero. |

### Guarda anche

* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* spazio dei nomi [Aspose.PSD](../../font/)
* assemblea [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

Inizializza un nuovo[`Font`](../) utilizzando una dimensione, uno stile, un'unità e un set di caratteri specificati.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | String | Una rappresentazione di stringa del[`Font`](../) nome. |
| emSize | Single | La dimensione em del nuovo carattere nelle unità specificate da*unit* parametro. |
| style | FontStyle | IL[`FontStyle`](../../fontstyle/) del nuovo carattere. |
| unit | GraphicsUnit | IL[`GraphicsUnit`](../../graphicsunit/) del nuovo carattere. |
| characterSet | CharacterSet | Un set di caratteri da utilizzare per questo tipo di carattere. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* è minore o uguale a 0, restituisce infinito o non è un numero valido. |
| ArgumentNullException | *fontName* è zero. |

### Guarda anche

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* enum [CharacterSet](../../characterset/)
* class [Font](../)
* spazio dei nomi [Aspose.PSD](../../font/)
* assemblea [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

Inizializza un nuovo[`Font`](../) utilizzando una dimensione, uno stile e un'unità specificati.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontName | String | Una rappresentazione di stringa del[`Font`](../) nome. |
| emSize | Single | La dimensione em del nuovo carattere nelle unità specificate da*unit* parametro. |
| style | FontStyle | IL[`FontStyle`](../../fontstyle/) del nuovo carattere. |
| unit | GraphicsUnit | IL[`GraphicsUnit`](../../graphicsunit/) del nuovo carattere. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* è minore o uguale a 0, restituisce infinito o non è un numero valido. |
| ArgumentNullException | *fontName* è zero. |

### Guarda anche

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* spazio dei nomi [Aspose.PSD](../../font/)
* assemblea [Aspose.PSD](../../../)


