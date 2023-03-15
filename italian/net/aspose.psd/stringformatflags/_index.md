---
title: Enum StringFormatFlags
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.StringFormatFlags enum. Specifica le informazioni di visualizzazione e layout per le stringhe di testo.
type: docs
weight: 5680
url: /it/net/aspose.psd/stringformatflags/
---
## StringFormatFlags enumeration

Specifica le informazioni di visualizzazione e layout per le stringhe di testo.

```csharp
[Flags]
public enum StringFormatFlags
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| DirectionRightToLeft | `1` | Il testo viene visualizzato da destra a sinistra. |
| DirectionVertical | `2` | Il testo è allineato verticalmente. |
| FitBlackBox | `4` | Parti di caratteri possono sporgere dal rettangolo di layout della stringa. Per impostazione predefinita, i caratteri vengono riposizionati per evitare sporgenze. |
| DisplayFormatControl | `20` | I caratteri di controllo come il segno da sinistra a destra sono mostrati nell'output con un glifo rappresentativo. |
| NoFontFallback | `400` | Il fallback ai caratteri alternativi per i caratteri non supportati nel carattere richiesto è disabilitato. Tutti i caratteri mancanti vengono visualizzati con i caratteri mancanti del glifo, di solito un quadrato aperto. |
| MeasureTrailingSpaces | `800` | Include lo spazio finale alla fine di ogni riga. Per impostazione predefinita, il rettangolo di delimitazione restituito dal metodo MeasureString esclude lo spazio alla fine di ogni riga. Imposta questo flag per includere quello spazio nella misurazione. |
| NoWrap | `1000` | Testo che va a capo tra le righe quando la formattazione all'interno di un rettangolo è disabilitata. Questo flag è implicito quando viene passato un punto invece di un rettangolo o quando il rettangolo specificato ha una lunghezza della linea pari a zero. |
| LineLimit | `2000` | Nel rettangolo di formattazione sono disposte solo righe intere. Per impostazione predefinita, il layout continua fino alla fine del testo o fino a quando non sono più visibili righe a seguito del ritaglio, a seconda di quale situazione si verifica per prima. Nota che le impostazioni predefinite consentono all'ultima riga di essere parzialmente oscurata da un rettangolo di formattazione che non è un multiplo intero dell'altezza della linea. Per garantire che vengano visualizzate solo righe intere, specifica questo valore e fai attenzione a fornire un rettangolo di formattazione alto almeno quanto l'altezza di una riga. |
| NoClip | `4000` | Le parti sporgenti dei glifi e il testo non racchiuso all'esterno del rettangolo di formattazione possono essere visualizzati. Per impostazione predefinita, tutte le parti di testo e glifi che escono dal rettangolo di formattazione vengono ritagliate. |

### Guarda anche

* spazio dei nomi [Aspose.PSD](../../aspose.psd/)
* assemblea [Aspose.PSD](../../)


