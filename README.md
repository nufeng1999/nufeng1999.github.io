#

![1](http://latex.codecogs.com/svg.latex?\int_a^bf(x)\%20dx)

![2](http://latex.codecogs.com/svg.latex?\begin{cases}a_1=a_{2}\\\\b_{1}=b_{2}\\\\\end{cases})

![3](http://latex.codecogs.com/svg.latex?\begin{bmatrix}{a_{1}}&{a_{2}}&{a_{3}}\\\\{b_{1}}&{b_{2}}&{b_{3}}\\\\{c_{1}}&{c_{2}}&{c_{3}}\\\\\end{bmatrix})

![4](http://latex.codecogs.com/svg.latex?\sum_{n=1}^\infty\frac{1}{n^2}=\frac{\pi^2}{6})

$$


$$

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

$$
f(x) = \int_{-\infty}^\infty \hat f(\xi)\,e^{2 \pi \xi x} \,d\xi
$$

```graphviz
digraph finite_state_machine {
    rankdir=LR;
    size="8,5"

    node [shape = doublecircle]; S;
    node [shape = point ]; qi

    node [shape = circle];
    qi -> S;
    S  -> q1 [ label = "a" ];
    S  -> S  [ label = "a" ];
    q1 -> S  [ label = "a" ];
    q1 -> q2 [ label = "ddb" ];
    q2 -> q1 [ label = "b" ];
    q2 -> q2 [ label = "b" ];
}
```