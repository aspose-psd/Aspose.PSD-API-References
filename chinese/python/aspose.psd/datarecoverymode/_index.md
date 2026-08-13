---
title: "DataRecoveryMode 枚举"
type: docs
weight: 5390
url: /zh/python-net/aspose.psd/datarecoverymode/
---

数据恢复模式。

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.DataRecoveryMode

**Aspose.PSD Version:** 24.12.0

## **Members**
| **成员名称** | **Description** |
| :- | :- |
| CONSISTENT_RECOVER | 一致恢复模式尝试在腐败未破坏文件格式的情况下恢复所有数据，并允许正确的后续处理。 |
| MAXIMAL_RECOVER | 最大恢复模式即使在文件格式结构已损坏的情况下也会恢复所有数据，但后续处理可能产生不可预料的影响。 |
| NONE | 不暗示任何数据恢复。只要文件格式中出现损坏数据，就会抛出相应的异常。 |
