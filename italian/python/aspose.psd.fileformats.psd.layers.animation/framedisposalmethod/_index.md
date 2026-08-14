---
title: "Enumerazione FrameDisposalMethod"
type: docs
weight: 50
url: /it/python-net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---

Il metodo di smaltimento del fotogramma specifica se scartare il fotogramma corrente prima di visualizzare il fotogramma successivo.<br/>            Si seleziona un metodo di smaltimento per le animazioni che includono trasparenza di sfondo per specificare se il fotogramma corrente<br/>            sarà visibile attraverso le aree trasparenti del fotogramma successivo.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.FrameDisposalMethod

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Nome membro** | **Description** |
| :- | :- |
| AUTOMATIC | Determina automaticamente un metodo di smaltimento per il frame corrente, scartando il frame corrente se il frame successivo contiene trasparenza di layer.<br/>            Per la maggior parte delle animazioni, l'opzione Automatic (predefinita) produce i risultati desiderati. |
| DISPOSE | Scarta il frame corrente dal display prima che il frame successivo venga visualizzato.<br/>            Viene visualizzato un solo frame alla volta (e il frame corrente non appare attraverso le aree trasparenti del frame successivo). |
| DO_NOT_DISPOSE | Preserva il frame corrente mentre il frame successivo viene aggiunto al display.<br/>            Il frame corrente (e i frame precedenti) può apparire attraverso le aree trasparenti del frame successivo. |
