---
title: DataRecoveryMode Enumeration
type: docs
weight: 5310
url: /python-net/aspose.psd/datarecoverymode/
---

The data recovery mode.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.DataRecoveryMode

**Aspose.PSD Version:** 24.4.0

## **Members**
| **Member name** | **Description** |
| :- | :- |
| CONSISTENT_RECOVER | The consistent recovery mode tries to recover all data as long as corruption does not break the file format and allows correct further processing. |
| MAXIMAL_RECOVER | The maximal recovery mode recovers all data even if the file format has corrupted structure and further processing may yield unattended effects. |
| NONE | No data recovery is implied. Whenever the file format has some corrupted data the appropriate exception is thrown. |
