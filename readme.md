# Discrete Fourier Transform
Used to extract frequency components from an input discrete function

$$ X_k = \sum_{n=0}^{N-1} x_n . e^{\dfrac{-j2 \pi kn}{N}}$$

for each k we get a corressponding complex equation $X_k = A_k + jB_k$<br>
These can be then laid on a spectrum plot to figure out the frequency components of the input signals.
[Refer this video](https://www.youtube.com/watch?v=mkGsMWi_j4Q) <br>

This method is too complex for computers to calculate. <br>
Complexity : $N^2$
# Fast Fourier Transform
Reduce the complexity of calculating DFT.<br>
Complexity : $N\log_2{N}$
<br>[Refer this video](https://www.youtube.com/watch?v=htCj9exbGo0)<br>
