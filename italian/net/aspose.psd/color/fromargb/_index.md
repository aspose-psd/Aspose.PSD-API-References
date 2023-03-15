---
title: Color.FromArgb
second_title: Aspose.PSD per riferimento API .NET
description: Color metodo. Crea unColor struttura da un valore ARGB a 32 bit.
type: docs
weight: 1430
url: /it/net/aspose.psd/color/fromargb/
---
## FromArgb(int) {#fromargb}

Crea un[`Color`](../) struttura da un valore ARGB a 32 bit.

```csharp
public static Color FromArgb(int argb)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argb | Int32 | Un valore che specifica il valore ARGB a 32 bit. |

### Valore di ritorno

IL[`Color`](../) struttura creata da questo metodo.

### Guarda anche

* struct [Color](../)
* spazio dei nomi [Aspose.PSD](../../color/)
* assemblea [Aspose.PSD](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

Crea un[`Color`](../) struttura dai valori dei quattro componenti ARGB (alfa, rosso, verde e blu). Sebbene questo metodo consenta di passare un valore a 32 bit per ciascun componente, il valore di ciascun componente è limitato a 8 bit.

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| alpha | Int32 | La componente alfa. I valori validi sono da 0 a 255. |
| red | Int32 | La componente rossa. I valori validi sono da 0 a 255. |
| green | Int32 | La componente verde. I valori validi sono da 0 a 255. |
| blue | Int32 | La componente blu. I valori validi sono da 0 a 255. |

### Valore di ritorno

IL[`Color`](../) che questo metodo crea.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* ,*red* ,*green* , O*blue* è minore di 0 o maggiore di 255. |

### Guarda anche

* struct [Color](../)
* spazio dei nomi [Aspose.PSD](../../color/)
* assemblea [Aspose.PSD](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

Crea un[`Color`](../) struttura dal specificato[`Color`](../) struttura, ma con il nuovo valore alfa specificato. Sebbene questo metodo consenta di passare un valore a 32 bit per il valore alfa, il valore è limitato a 8 bit.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| alpha | Int32 | Il valore alfa per il nuovo[`Color`](../). I valori validi sono da 0 a 255. |
| baseColor | Color | IL[`Color`](../) da cui creare il nuovo[`Color`](../). |

### Valore di ritorno

IL[`Color`](../) che questo metodo crea.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* è minore di 0 o maggiore di 255. |

### Guarda anche

* struct [Color](../)
* spazio dei nomi [Aspose.PSD](../../color/)
* assemblea [Aspose.PSD](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

Crea un[`Color`](../) struttura dai valori di colore a 8 bit specificati (rosso, verde e blu). Il valore alfa è implicitamente 255 (completamente opaco). Sebbene questo metodo consenta di passare un valore a 32 bit per ciascun componente di colore, il valore di ciascun componente è limitato a 8 bit.

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| red | Int32 | Il valore del componente rosso per il nuovo[`Color`](../). I valori validi sono da 0 a 255. |
| green | Int32 | Il valore della componente verde per il nuovo[`Color`](../). I valori validi sono da 0 a 255. |
| blue | Int32 | Il valore del componente blu per il nuovo[`Color`](../). I valori validi sono da 0 a 255. |

### Valore di ritorno

IL[`Color`](../) che questo metodo crea.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | *red* ,*green* , O*blue* è minore di 0 o maggiore di 255. |

### Guarda anche

* struct [Color](../)
* spazio dei nomi [Aspose.PSD](../../color/)
* assemblea [Aspose.PSD](../../../)


