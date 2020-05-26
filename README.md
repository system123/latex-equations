# latex-equations

I get tired of rewriting the same equations in various publications, and tired of the thought that hundred of people do the same for their publications. So I am placing the code for common equations I use here so they can be easily copy and pasted for later use:

## Computer Vision

Normalized Cross Correlation (NCC)
```
\begin{equation}
	\text{NCC}(x,y) = \frac{\sum\limits_{(u,v)\in\mathbf{T}}{\left(\mathbf{R}(x+u,y+v)-\overline{\mathbf{R}}_{u,v}\right)\left(\mathbf{T}(u,v) - \overline{\mathbf{T}}\right)}}{\sqrt{\sum\limits_{(u,v)\in\mathbf{T}}{\left(\mathbf{R}(x+u,y+v)-\overline{\mathbf{R}}_{u,v}\right)}^2\sum\limits_{(u,v)\in\mathbf{T}}{\left(\mathbf{T}(u,v) - \overline{\mathbf{T}}\right)}^2}}
\end{equation}
```

## Deep Learning
