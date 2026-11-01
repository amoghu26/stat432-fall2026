---
id: w10-amoghu2-forest-vs-knn
title: "Why Does a Forest Beat KNN in High Dimensions?"
author: "Amogh Upadhyaya (amoghu2)"
---

The forest-kernel reading reframes a random forest as adaptive nearest neighbors, where "near" is learned from the response instead of fixed by distance. If that's really what's happening, why does KNN fall apart in high dimensions but a forest on 784 pixels doesn't? Is the adaptiveness the whole difference, or is something else going on?
