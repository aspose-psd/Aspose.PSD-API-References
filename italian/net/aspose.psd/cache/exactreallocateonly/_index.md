---
title: Cache.ExactReallocateOnly
second_title: Aspose.PSD per riferimento API .NET
description: Cache proprietà. Ottiene o imposta un valore che indica se la riallocazione deve essere esatta o meno. Se la riallocazione non è esatta le prestazioni dovrebbero essere superiori.
type: docs
weight: 50
url: /it/net/aspose.psd/cache/exactreallocateonly/
---
## Cache.ExactReallocateOnly property

Ottiene o imposta un valore che indica se la riallocazione deve essere esatta o meno. Se la riallocazione non è esatta, le prestazioni dovrebbero essere superiori.

```csharp
public static bool ExactReallocateOnly { get; set; }
```

### Valore della proprietà

`VERO` se la riallocazione è esatta; Altrimenti,`falso` .

### Osservazioni

La riallocazione esatta eseguirà la riallocazione della memoria aggiuntiva solo fino al limite superiore specificato. Quando si supera il limite superiore per la memoria in memoria durante la riallocazione, i dati memorizzati nella cache verranno copiati su disco, se possibile. Quando si supera il limite superiore per la memoria del disco durante la riallocazione il viene generata un'eccezione appropriata. Le prestazioni dovrebbero essere superiori se questa opzione è disattivata poiché non verrà eseguita alcuna copia aggiuntiva, se possibile, tuttavia ciò potrebbe anche portare a superare i limiti superiori specificati per la memoria o il disco.

### Guarda anche

* class [Cache](../)
* spazio dei nomi [Aspose.PSD](../../cache/)
* assemblea [Aspose.PSD](../../../)


