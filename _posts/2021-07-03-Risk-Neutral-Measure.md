---
layout: post
title: "Risk Neutral Measure"
subtitle: "An important measure to price financial derivatives"
background: '/img/posts/01.jpg'
---

{% include katex_import.html %}

<!-- <div class="equation" data-expr="\displaystyle P(x)=\frac{1}{\sigma\sqrt{2\pi}}e^{-\frac{(x-\mu)^2}{2\sigma ^2}}"></div> -->

Different assets have different risk profiles. An investor could hold a riskier stock while simultaneously holding a less risky bond. While pricing these securities the usual method of discounting future cashflows would cause immense pain as the discount rates would vary depending on the riskiness of the asset. How do we then simplify the pricing of various securities? This is where risk neutral pricing, one of the most important concepts in the area of derivative pricing comes into play. 

To get an intuition of risk neutral pricing we consider the one period binomial tree model. Let $S_{0}$ be today's stock price that either moves up to $S_{0} * u$ or down to $S_{0} * d$ in the next period. Let $r$ be the risk-free rate. By imposing the condition $d<$ $r<$ $u$ we insure that there is no arbitrage in the model. 

By making the following manipulations, we can write $S_{0}$ as,

<!--\[S_{0}=S_{0}*\frac{(u-d)}{(u-d)}\]
\[=S_{0}*\frac{e^{r}*(u-d)}{e^{r}*(u-d)}\]
\[=S_{0}*\frac{e^{r}*(u-d)+(S_{0}ud-S_{0}ud)}{e^{r}*(u-d)}\]
\[=S_{0}*\frac{e^{r}*(u-d)+(S_{0}ud-S_{0}ud)}{e^{r}*(u-d)}\]-->
<!--<div class="equation" data-expr="\displaystyle \begin{eqnarray*}
		S_{0} &=& S_{0}*\frac{(u-d)}{(u-d)}\\
		&=& S_{0}*\frac{e^{r}*(u-d)}{e^{r}*(u-d)}\\
		&=&S_{0}*\frac{e^{r}*(u-d)+(S_{0}ud-S_{0}ud)}{e^{r}*(u-d)}\\
		&=&S_{0}*\frac{e^{r}*(u-d)+(S_{0}ud-S_{0}ud)}{e^{r}*(u-d)}\\
	\end{eqnarray*}"></div>-->

   
    <div class="equation" data-expr="\displaystyle S_{0}=S_{0}*\frac{(u-d)}{(u-d)}"></div>

<!-- &= S_{0}*\frac{e^{r}*(u-d)}{e^{r}*(u-d)}\\
		&= S_{0}*\frac{e^{r}*(u-d)+(S_{0}ud-S_{0}ud)}{e^{r}*(u-d)}\\
		&= S_{0}*\frac{e^{r}*(u-d)+(S_{0}ud-S_{0}ud)}{e^{r}*(u-d)} -->
{% include katex_render.html %}