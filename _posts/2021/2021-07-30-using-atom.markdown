---
layout: "post"
title: "Using Atom"
date: "2021-07-30 21:23"
---

After fumbling with Jekyll for the last day, I figured out the problem.
By putting  "Hello World" into index.markdown, I was causing it to overwrite
the content on the default theme layout. There was also some general
rustiness with dealing Ruby / Gem / Bundle and getting dependencies specified
correctly so that things would run.
