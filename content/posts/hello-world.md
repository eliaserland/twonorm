---
title: "Hello World"
date: 2021-10-18T08:21:24+02:00
draft: false
math: true
---

Hi there! 

Welcome to my blog. An attempt at formulating thoughts, dreams and problems that's swirling around in my head. Hopefully it will be somewhat interesting.

Stick around to see what I'm up to.

```c
#include <stdio.h>

int main(int argc, char **argv)
{
	printf("Hello World!\n");
	return 0;	
}
```

$$
\begin{aligned}
f(x) &= \int_{-\infty}^\infty \hat{f}(\xi) \\, e^{2 \pi i x \xi} \\,d\xi \cr
\hat{f}(\xi) &= \int_{-\infty}^\infty f(x) \\, e^{-2 \pi i x \xi} \\,dx
\end{aligned}
$$

$$
\operatorname{ELBO}=\mathbb{E}\_{z \sim q(z \mid x)} \log \left(p(x \mid z)-D_{\mathrm{KL}}(q(z \mid x) \| p(z))\right.
$$

