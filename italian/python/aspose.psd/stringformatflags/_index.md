---
title: "Enumerazione StringFormatFlags"
type: docs
weight: 6300
url: /it/python-net/aspose.psd/stringformatflags/
---

Specifica le informazioni di visualizzazione e layout per le stringhe di testo.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.StringFormatFlags

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Nome membro** | **Description** |
| :- | :- |
| DIRECTION_RIGHT_TO_LEFT | Il testo è visualizzato da destra a sinistra. |
| DIRECTION_VERTICAL | Il testo è allineato verticalmente. |
| DISPLAY_FORMAT_CONTROL | I caratteri di controllo, come il segno da sinistra a destra, sono mostrati nell'output con un glifo rappresentativo. |
| EXACT_ALIGNMENT | L'allineamento esatto, riempimento corretto GDI+ |
| FIT_BLACK_BOX | Le parti dei caratteri possono sporgere dal rettangolo di layout della stringa. Per impostazione predefinita, i caratteri vengono riposizionati per evitare qualsiasi sporgenza. |
| LINE_LIMIT | Solo le linee intere vengono disposte nel rettangolo di formattazione. Per impostazione predefinita il layout continua fino alla fine del testo, o fino a quando non sono più visibili linee a causa del ritaglio, a seconda di quale evento si verifichi per primo.<br/>            Nota che le impostazioni predefinite consentono all'ultima linea di essere parzialmente oscurata da un rettangolo di formattazione che non è un multiplo intero dell'altezza della linea. Per garantire che vengano visualizzate solo linee intere,<br/>            specificare questo valore e fare attenzione a fornire un rettangolo di formattazione alto almeno quanto l'altezza di una linea. |
| MEASURE_TRAILING_SPACES | Include lo spazio finale alla fine di ogni riga. Per impostazione predefinita il rettangolo di confine restituito dal metodo MeasureString esclude lo spazio alla fine di ogni riga. Impostare questa opzione per includere quello spazio nella misurazione. |
| NO_CLIP | Le parti sporgenti dei glifi e il testo non avvolto che si estende al di fuori del rettangolo di formattazione possono essere visualizzati. Per impostazione predefinita tutte le parti di testo e glifi che si estendono al di fuori del rettangolo di formattazione vengono ritagliate. |
| NO_FONT_FALLBACK | Il ricorso a caratteri alternativi per i caratteri non supportati nel font richiesto è disabilitato. Eventuali caratteri mancanti vengono visualizzati con il glifo mancante del font, solitamente un quadrato vuoto. |
| NO_WRAP | L'andare a capo del testo tra le linee durante la formattazione all'interno di un rettangolo è disabilitato. Questa opzione è implicita quando viene passato un punto anziché un rettangolo, o quando il rettangolo specificato ha una lunghezza di linea pari a zero. |
