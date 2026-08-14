---
title: "FrameDisposalMethod 列挙体"
type: docs
weight: 50
url: /ja/python-net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---

フレーム破棄方法は、次のフレームを表示する前に現在のフレームを破棄するかどうかを指定します。<br/>            背景の透過を含むアニメーションでは、現在のフレームが次のフレームの透過領域を通して表示されるかどうかを指定するために破棄方法を選択します。

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.FrameDisposalMethod

**Aspose.PSD Version:** 24.12.0

## **Members**
| **メンバー名** | **説明** |
| :- | :- |
| AUTOMATIC | 現在のフレームに対して破棄方法を自動的に決定し、次のフレームにレイヤーの透過が含まれる場合は現在のフレームを破棄します。<br/>            ほとんどのアニメーションでは、Automatic オプション（デフォルト）が期待通りの結果をもたらします。 |
| DISPOSE | 次のフレームが表示される前に、現在のフレームをディスプレイから破棄します。<br/>            常に単一のフレームのみが表示され、現在のフレームは次のフレームの透過領域を通して表示されません。 |
| DO_NOT_DISPOSE | 次のフレームがディスプレイに追加される際に、現在のフレームを保持します。<br/>            現在のフレーム（および前のフレーム）は、次のフレームの透過領域を通して表示される場合があります。 |
