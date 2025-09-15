The average squared distance of the observation from the mean in an infinite number of trials.


## Properties
When pulling a constant c out of a variance formula, the constant must be squared.
$V(cY)=c^2V(Y)$

Adding a constant to a random variable Y does not change the value of its variance.
$V(Y+b)=V(Y)$

# Discrete

$V(Y)=E[(Y-\mu)^2]=\displaystyle\sum_{y}(y-\mu)^2*p(y) = \sigma^2$

$V(Y)=E(Y^2)-\mu^2 = E(Y^2)-E(Y)^2$

$E(Y^2)=\displaystyle\sum_yy^2p(y)$

Ex.

$$
\begin{array}{|c|c|c|c|c|c|c|c|c|c|c|}
\hline
y & 2 & 3 & 4 & 5 & 6 & 7 & 8 & 9 & 10 & 11 & 12 \\
\hline
p(y) & \tfrac{1}{36} & \tfrac{2}{36} & \tfrac{3}{36} & \tfrac{4}{36} & \tfrac{5}{36} & \tfrac{6}{36} & \tfrac{5}{36} & \tfrac{4}{36} & \tfrac{3}{36} & \tfrac{2}{36} & \tfrac{1}{36} \\
\hline
\end{array}
$$

$$
E[Y^2] = \sum_{y=2}^{12} y^2 \, p(y) =
2^2 \cdot \tfrac{1}{36} +
3^2 \cdot \tfrac{2}{36} +
4^2 \cdot \tfrac{3}{36} +
5^2 \cdot \tfrac{4}{36} +
6^2 \cdot \tfrac{5}{36} +
7^2 \cdot \tfrac{6}{36} +
8^2 \cdot \tfrac{5}{36} +
9^2 \cdot \tfrac{4}{36} +
10^2 \cdot \tfrac{3}{36} +
11^2 \cdot \tfrac{2}{36} +
12^2 \cdot \tfrac{1}{36}.
$$
$$
E[Y] = \sum_{y=2}^{12} y \, p(y) =
2 \cdot \tfrac{1}{36} +
3 \cdot \tfrac{2}{36} +
4 \cdot \tfrac{3}{36} +
5 \cdot \tfrac{4}{36} +
6 \cdot \tfrac{5}{36} +
7 \cdot \tfrac{6}{36} +
8 \cdot \tfrac{5}{36} +
9 \cdot \tfrac{4}{36} +
10 \cdot \tfrac{3}{36} +
11 \cdot \tfrac{2}{36} +
12 \cdot \tfrac{1}{36}.
$$
$V(Y)=E(Y^2)-\mu^2=54.8\bar{3}-7^2=5.8\bar{3}$ 