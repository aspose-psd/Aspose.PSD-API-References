---
title: License.SetLicense
second_title: Aspose.PSD per riferimento API .NET
description: License metodo. Concede in licenza il componente.
type: docs
weight: 20
url: /it/net/aspose.psd/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Concede in licenza il componente.

```csharp
public void SetLicense(string licenseName)
```

### Osservazioni

Tenta di trovare la licenza nelle seguenti posizioni:

1. Percorso esplicito.

2. La cartella che contiene l'assieme del componente Aspose.

3. La cartella che contiene l'assembly chiamante del client.

4. La cartella che contiene l'assembly della voce (avvio).

5. Una risorsa incorporata nell'assembly chiamante del client.

**Nota:**In .NET Compact Framework, tenta di trovare la licenza solo in questi percorsi:

1. Percorso esplicito.

2. Una risorsa incorporata nell'assembly chiamante del client.

### Esempi

In questo esempio si cercherà di trovare un file di licenza denominato MyLicense.lic nella cartella che contiene il componente, nella cartella che contiene l'assembly chiamante, nella cartella dell'assembly di entrata e quindi in le risorse incorporate dell'assembly chiamante. Può essere un nome file completo o breve o il nome di una risorsa incorporata. Usa una stringa vuota per passare alla modalità di valutazione.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

### Guarda anche

* class [License](../)
* spazio dei nomi [Aspose.PSD](../../license/)
* assemblea [Aspose.PSD](../../../)

---

## SetLicense(Stream) {#setlicense}

Concede in licenza il componente.

```csharp
public void SetLicense(Stream stream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | Stream | Un flusso che contiene la licenza. |

### Osservazioni

Utilizzare questo metodo per caricare una licenza da un flusso.

### Esempi

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

### Guarda anche

* class [License](../)
* spazio dei nomi [Aspose.PSD](../../license/)
* assemblea [Aspose.PSD](../../../)


