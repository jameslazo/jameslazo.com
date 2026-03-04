---
title: "fzf bug fix"
link: "https://github.com/junegunn/fzf/pull/4635"
image: "/img/fzf-bug-fix.png"
description: "Fixed bug in Bash integration of fzf overriding readline defaults"
featured: true
tags: ["Git","Bash","CLI development"]
fact: "Identified, fixed and tested solution for Bash implementation of fzf cli utility"
weight: 100
sitemap: 
    priority : 0.8
---

Previous Bash implementations of fzf overrode default readline key bindings, producing unexpected results when attempting to manually update readline binding.
