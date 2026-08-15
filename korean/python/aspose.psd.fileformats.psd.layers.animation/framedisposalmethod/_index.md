---
title: "FrameDisposalMethod 열거형"
type: docs
weight: 50
url: /ko/python-net/aspose.psd.fileformats.psd.layers.animation/framedisposalmethod/
---

프레임 폐기 방법은 다음 프레임을 표시하기 전에 현재 프레임을 폐기할지 여부를 지정합니다.<br/>            배경 투명성을 포함하는 애니메이션에 대해 폐기 방법을 선택하여 현재<br/>            프레임이 다음 프레임의 투명 영역을 통해 보일지 여부를 지정합니다.

**Module:** [aspose.psd.fileformats.psd.layers.animation](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/)

**Full Name:** aspose.psd.fileformats.psd.layers.animation.FrameDisposalMethod

**Aspose.PSD Version:** 24.12.0

## **Members**
| **멤버 이름** | **설명** |
| :- | :- |
| AUTOMATIC | 현재 프레임에 대한 폐기 방법을 자동으로 결정하며, 다음 프레임에 레이어 투명도가 포함된 경우 현재 프레임을 폐기합니다.<br/>            대부분의 애니메이션에서 자동 옵션(기본값)이 원하는 결과를 제공합니다. |
| DISPOSE | 다음 프레임이 표시되기 전에 현재 프레임을 디스플레이에서 폐기합니다.<br/>            언제나 단일 프레임만 표시되며(현재 프레임은 다음 프레임의 투명 영역을 통해 나타나지 않습니다). |
| DO_NOT_DISPOSE | 다음 프레임이 디스플레이에 추가되는 동안 현재 프레임을 유지합니다.<br/>            현재 프레임(및 이전 프레임)은 다음 프레임의 투명 영역을 통해 표시될 수 있습니다. |
