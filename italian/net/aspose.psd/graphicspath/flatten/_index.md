---
title: GraphicsPath.Flatten
second_title: Aspose.PSD per riferimento API .NET
description: GraphicsPath metodo. Converte ogni curva in questo percorso in una sequenza di segmenti di linea collegati.
type: docs
weight: 90
url: /it/net/aspose.psd/graphicspath/flatten/
---
## Flatten() {#flatten}

Converte ogni curva in questo percorso in una sequenza di segmenti di linea collegati.

```csharp
public void Flatten()
```

### Guarda anche

* class [GraphicsPath](../)
* spazio dei nomi [Aspose.PSD](../../graphicspath/)
* assemblea [Aspose.PSD](../../../)

---

## Flatten(Matrix) {#flatten_1}

Applica la trasformazione specificata e quindi converte ciascuna curva in questa[`GraphicsPath`](../) in una sequenza di segmenti di linea collegati.

```csharp
public void Flatten(Matrix matrix)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | Matrix | UN[`Matrix`](../../matrix/) con cui trasformare questo[`GraphicsPath`](../) prima dell'appiattimento. |

### Guarda anche

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* spazio dei nomi [Aspose.PSD](../../graphicspath/)
* assemblea [Aspose.PSD](../../../)

---

## Flatten(Matrix, float) {#flatten_2}

Converte ogni curva in questo[`GraphicsPath`](../) in una sequenza di segmenti di linea collegati.

```csharp
public void Flatten(Matrix matrix, float flatness)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| matrix | Matrix | UN[`Matrix`](../../matrix/) con cui trasformare questo[`GraphicsPath`](../) prima dell'appiattimento. |
| flatness | Single | Specifica l'errore massimo consentito tra la curva e la sua approssimazione appiattita. Il valore predefinito è 0,25. Riducendo il valore di planarità aumenterà il numero di segmenti di linea nell'approssimazione. |

### Guarda anche

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* spazio dei nomi [Aspose.PSD](../../graphicspath/)
* assemblea [Aspose.PSD](../../../)


