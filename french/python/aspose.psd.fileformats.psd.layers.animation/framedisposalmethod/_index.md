---
title: "Énumération FrameDisposalMethod"
type: docs
weight: 50
url: /fr/python-net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---

La méthode de disposition de la trame spécifie s'il faut supprimer la trame actuelle avant d'afficher la trame suivante.<br/>            Vous choisissez une méthode de disposition pour les animations incluant la transparence de l'arrière-plan afin de spécifier si la trame actuelle<br/>            sera visible à travers les zones transparentes de la trame suivante.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.FrameDisposalMethod

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Member name** | **Description** |
| :- | :- |
| AUTOMATIQUE | Détermine automatiquement une méthode de disposition pour la trame actuelle, en supprimant la trame actuelle si la trame suivante contient de la transparence de couche.<br/>            Pour la plupart des animations, l'option Automatique (par défaut) donne les résultats souhaités. |
| SUPPRIMER | Supprime la trame actuelle de l'affichage avant que la trame suivante ne soit affichée.<br/>            Une seule trame est affichée à la fois (et la trame actuelle n'apparaît pas à travers les zones transparentes de la trame suivante). |
| NE_PAS_SUPPRIMER | Conserve la trame actuelle lorsque la trame suivante est ajoutée à l'affichage.<br/>            La trame actuelle (et les trames précédentes) peut apparaître à travers les zones transparentes de la trame suivante. |
