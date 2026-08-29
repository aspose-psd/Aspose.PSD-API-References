---
title: "Énumération TextRenderingHint"
type: docs
weight: 6340
url: /fr/python-net/aspose.psd/textrenderinghint/
---

Spécifie la qualité du rendu du texte.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.TextRenderingHint

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Member name** | **Description** |
| :- | :- |
| ANTI_ALIAS | Chaque caractère est dessiné en utilisant son bitmap de glyphe antialiasé sans hinting. Meilleure qualité grâce à l'antialiasing. Les différences de largeur des tiges peuvent être perceptibles car le hinting est désactivé. |
| ANTI_ALIAS_GRID_FIT | Chaque caractère est dessiné en utilisant son bitmap de glyphe antialiasé avec hinting. Qualité bien meilleure grâce à l'antialiasing, mais à un coût de performance plus élevé. |
| CLEAR_TYPE_GRID_FIT | Chaque caractère est dessiné en utilisant son bitmap de glyphe ClearType avec hinting. Le réglage de la plus haute qualité. Utilisé pour tirer parti des fonctionnalités de police ClearType. |
| SINGLE_BIT_PER_PIXEL | Chaque caractère est dessiné en utilisant son bitmap de glyphe. Le hinting n'est pas utilisé. |
| SINGLE_BIT_PER_PIXEL_GRID_FIT | Chaque caractère est dessiné en utilisant son bitmap de glyphe. Le hinting est utilisé pour améliorer l'apparence des caractères sur les tiges et les courbures. |
| SYSTEM_DEFAULT | Chaque caractère est dessiné en utilisant son bitmap de glyphe, avec le hint de rendu par défaut du système. Le texte sera dessiné en fonction des paramètres de lissage des polices que l'utilisateur a sélectionnés pour le système. |
