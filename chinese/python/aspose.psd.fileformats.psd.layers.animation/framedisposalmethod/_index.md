---
title: "FrameDisposalMethod 枚举"
type: docs
weight: 50
url: /zh/python-net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---

帧处理方式指定是否在显示下一帧之前丢弃当前帧。<br/>            对于包含背景透明度的动画，您可以选择处理方式，以指定当前帧是否会通过下一帧的透明区域可见。

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.FrameDisposalMethod

**Aspose.PSD Version:** 24.12.0

## **Members**
| **成员名称** | **Description** |
| :- | :- |
| AUTOMATIC | 自动确定当前帧的处置方法，如果下一帧包含图层透明度，则丢弃当前帧。<br/>            对于大多数动画，Automatic 选项（默认）可产生期望的结果。 |
| DISPOSE | 在显示下一帧之前，从显示中丢弃当前帧。<br/>            任意时刻仅显示单帧（且当前帧不会通过下一帧的透明区域显示）。 |
| DO_NOT_DISPOSE | 在将下一帧添加到显示时保留当前帧。<br/>            当前帧（以及之前的帧）可能会透过下一帧的透明区域显示。 |
