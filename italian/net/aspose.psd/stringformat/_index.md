---
title: Class StringFormat
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.StringFormat classe. Incapsula le informazioni sul layout del testo come lallineamento lorientamento e le tabulazioni le manipolazioni del display come linserimento di puntini di sospensione e la sostituzione delle cifre nazionali e le funzionalità OpenType. Questa classe non può essere ereditata.
type: docs
weight: 5670
url: /it/net/aspose.psd/stringformat/
---
## StringFormat class

Incapsula le informazioni sul layout del testo (come l'allineamento, l'orientamento e le tabulazioni), le manipolazioni del display (come l'inserimento di puntini di sospensione e la sostituzione delle cifre nazionali) e le funzionalità OpenType. Questa classe non può essere ereditata.

```csharp
public sealed class StringFormat : DisposableObject
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [StringFormat](stringformat/#constructor)() | Inizializza un nuovo`StringFormat` oggetto. |
| [StringFormat](stringformat/#constructor_1)(StringFormat) | Inizializza un nuovo`StringFormat` oggetto dall'esistente specificato`StringFormat` oggetto. |
| [StringFormat](stringformat/#constructor_2)(StringFormatFlags) | Inizializza un nuovo`StringFormat` oggetto con l'oggetto specificato[`StringFormatFlags`](../stringformatflags/) enumerazione e lingua. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [GenericDefault](../../aspose.psd/stringformat/genericdefault/) { get; } | Ottiene un valore predefinito generico`StringFormat` oggetto. |
| static [GenericTypographic](../../aspose.psd/stringformat/generictypographic/) { get; } | Ottiene un tipografico generico`StringFormat` oggetto. |
| [Alignment](../../aspose.psd/stringformat/alignment/) { get; set; } | Ottiene o imposta le informazioni sull'allineamento del testo sul piano verticale. |
| [DigitSubstitutionLanguage](../../aspose.psd/stringformat/digitsubstitutionlanguage/) { get; set; } | Ottiene o imposta la lingua utilizzata quando le cifre locali vengono sostituite con le cifre occidentali. |
| [DigitSubstitutionMethod](../../aspose.psd/stringformat/digitsubstitutionmethod/) { get; set; } | Ottiene o imposta il metodo da utilizzare per la sostituzione delle cifre. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| [FirstTabOffset](../../aspose.psd/stringformat/firsttaboffset/) { get; } | Ottiene il numero di spazi tra l'inizio di una riga di testo e la prima tabulazione. |
| [FormatFlags](../../aspose.psd/stringformat/formatflags/) { get; set; } | Ottiene o imposta a[`StringFormatFlags`](../stringformatflags/) enumerazione che contiene informazioni sulla formattazione. |
| [HotkeyPrefix](../../aspose.psd/stringformat/hotkeyprefix/) { get; set; } | Ottiene o imposta il[`HotkeyPrefix`](../hotkeyprefix/) oggetto per questo`StringFormat` oggetto. |
| [LineAlignment](../../aspose.psd/stringformat/linealignment/) { get; set; } | Ottiene o imposta l'allineamento della linea sul piano orizzontale. |
| [TabStops](../../aspose.psd/stringformat/tabstops/) { get; } | Ottiene una matrice di distanze tra le tabulazioni nelle unità specificate da[`PageUnit`](../graphics/pageunit/) proprietà. |
| [Trimming](../../aspose.psd/stringformat/trimming/) { get; set; } | Ottiene o imposta il[`StringTrimming`](../stringtrimming/) enumerazione per questo`StringFormat` oggetto. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [DeepClone](../../aspose.psd/stringformat/deepclone/)() | Crea un clone profondo di questo`StringFormat` oggetto. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Elimina l'istanza corrente. |
| [SetTabStops](../../aspose.psd/stringformat/settabstops/)(float, float[]) | Imposta le tabulazioni per questo`StringFormat` oggetto. |
| override [ToString](../../aspose.psd/stringformat/tostring/)() | Converte questo`StringFormat` oggetto a una stringa leggibile dall'uomo. |

### Guarda anche

* class [DisposableObject](../disposableobject/)
* spazio dei nomi [Aspose.PSD](../../aspose.psd/)
* assemblea [Aspose.PSD](../../)


