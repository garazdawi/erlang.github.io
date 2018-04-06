---
layout: post
title: First Blog!
---

```erlang
-module(m).
-compile(export_all).

foo(A) when is_atom(A) ->
  L = atom_to_list(A),
  case L of 
    "veryverylonglist" -> [C + 47|| C <- L, C =/= 47]; _ -> true end.
```
Next you can update your site name, avatar and other options using the _config.yml file in the root of your repository (shown below).

