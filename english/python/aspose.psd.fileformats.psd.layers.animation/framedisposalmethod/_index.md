---
title: FrameDisposalMethod Enumeration
type: docs
weight: 50
url: /python-net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---

The frame disposal method specifies whether to discard the current frame before displaying the next frame.<br/>            You select a disposal method for animations that include background transparency to specify whether the current<br/>            frame will be visible through the transparent areas of the next frame.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.FrameDisposalMethod

**Aspose.PSD Version:** 24.6.0

## **Members**
| **Member name** | **Description** |
| :- | :- |
| AUTOMATIC | Determines a disposal method for the current frame automatically, discarding the current frame if the next frame contains layer transparency.<br/>            For most animations, the Automatic option (default) yields the desired results. |
| DISPOSE | Discards the current frame from the display before the next frame is displayed.<br/>            Only a single frame is displayed at any time (and the current frame does not appear through the transparent areas of the next frame). |
| DO_NOT_DISPOSE | Preserves the current frame as the next frame is added to the display.<br/>            The current frame (and preceding frames) may show through transparent areas of the next frame. |
