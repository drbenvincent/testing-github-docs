---
layout: default
title: Home
---

Hi

I am a [link](random_md_file.md) to a .md file/page

- [Info 1](info1.md)
- [Info 2](info2.md)
- [Info 3](info3.md)


Picture of a cat in root dir
![](../cats_in_root.png)

Picture of a cat in `docs/`
![](cats_in_docs.png)

Picture of a cat in `~/img/` ![](img/cats_in_docs.png)

Link to [page](sub/page_in_sub.md) in subfolder


Below is an attempt to embed a YouTube video in GitHub pages

<iframe width="560" height="315" src="https://www.youtube.com/embed/vSjL2Zc-gEQ" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

## Test of formatted code blocks

Below should be Python code with syntax highlighting: 
```python
def my_func(x):
    print(x*2)
```

Below should be Julia code with syntax highlighting: 
```julia
f(x) = println(x*2)
```

## Test of maths
Below should be a display equation:
$y ~ \text{Normal} (\beta_0 + \beta_1 x, \sigma)$

And what about inline, $e = mc^2$.
