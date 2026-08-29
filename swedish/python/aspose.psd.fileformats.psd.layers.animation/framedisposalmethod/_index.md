---
title: "FrameDisposalMethod‑enumeration"
type: docs
weight: 50
url: /sv/python-net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---

Raderingsmetoden för bildrutan anger om den aktuella bildrutan ska kastas bort innan nästa bildruta visas.<br/>            Du väljer en raderingsmetod för animationer som inkluderar bakgrundstransparens för att ange om den aktuella<br/>            bildrutan kommer att vara synlig genom de transparenta områdena i nästa bildruta.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.FrameDisposalMethod

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Medlemsnamn** | **Beskrivning** |
| :- | :- |
| AUTOMATISK | Bestämmer en kassationsmetod för den aktuella ramen automatiskt, och kastar den aktuella ramen om nästa ram innehåller lagertransparens.<br/>            För de flesta animationer ger det automatiska alternativet (standard) önskat resultat. |
| DISPOSE | Kastar den aktuella ramen från displayen innan nästa ram visas.<br/>            Endast en ram visas åt gången (och den aktuella ramen visas inte genom de transparenta områdena i nästa ram). |
| DO_NOT_DISPOSE | Bevarar den aktuella ramen när nästa ram läggs till på displayen.<br/>            Den aktuella ramen (och föregående ramar) kan visas genom transparenta områden i nästa ram. |
