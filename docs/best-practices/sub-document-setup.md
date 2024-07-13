---
title: Best Practices
description: The best practices to follow with organizing your mechanism documents in Onshape.
---

# Sub-Document Setup

Within each document, you should have a part studio and assembly attached to it. The part studio should contain **all parts that need to be manufactured by your team**. This could include fully custom plates, shafts cut to length, modified COTs parts, etc. However, unmodified COTs parts should be imported directly into the corresponding assembly - no modification inside the part studio is required.

!!! Important note
    Never pattern or mirror parts in part studios that don't explicitly need to be patterned. Creating one of each part in the studio means you can simply duplicate it when assembling, and your part studio regeneration time will be greatly improved at no cost.

Often, you only need to have one part studio and one top-level subsystem assembly, although depending on the complexity of the subsystem you may want to split into multiple. For example, you could split an elevator document into one part studio and corresponding assembly for each stage. The top-level elevator assembly would thus include each of the stage subassemblies within it.


Note how there's only 1 part studio and 1 assembly for this subsystem, as the part count is relatively low.

<center><img src="/img/best-practices/part-studio.webp"></center>

Note how a subassembly is used to assemble several parts that can then be imported as a single item in the top-level subsystem assembly.

<center><img src="/img/best-practices/subassembly.png"></center>

<br>