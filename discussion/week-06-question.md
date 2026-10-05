---
id: w06-amoghu2-auc-vs-threshold
title: "Why Lean on AUC If You Pick One Cutoff?"
author: "Amogh Upadhyaya (amoghu2)"
---

A model can have a great AUC and still make bad calls at the cutoff you actually use, since AUC only scores ranking. If you only ever predict at one threshold, why do we lean on AUC so much instead of judging the model at that threshold directly?
