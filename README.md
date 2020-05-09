# Calculation of Normalized Distribution of Radius of Curvature in Prolate and Oblate Spheroids
Repository storing calculation of normalized distribution of radius of curvature in prolate and oblate spheroids in a Jupyter notebook.

The main result is summarized below.

### Radius of Curvature Distribution in Prolate Spheroid

Mass function:

<img src="https://render.githubusercontent.com/render/math?math=\huge\displaystyle f_C(\bar{R}) = \frac{\sqrt{\frac{C^{4/3}\cdot\bar{R}^{2/3}-1}{C^4-C}}}{\frac{3C^2}{4} - \frac{3}{8C} - \frac{3\cdot\log\left(C^{3/2}+\sqrt{C^3-1}\right)}{8C^2\sqrt{C^4-C}}}">

Cumulative function:

<img src="https://render.githubusercontent.com/render/math?math=\large F_C(\bar{R}) = \frac{\displaystyle\sqrt{\frac{C^{4/3}\bar{R}^{2/3}-1}{C^4-C}}\left(\frac{3\bar{R}}{4} - \frac{3\bar{R}^{1/3}}{8C^{4/3}}\right) - \frac{3\cdot\log\left(C^{2/3}\bar{R}^{1/3}%2B\sqrt{C^{4/3}\bar{R}^{2/3}-1}\right)}{8C^2\sqrt{C^4-C}}}{\displaystyle\frac{3C^2}{4} - \frac{3}{8C} - \frac{3\cdot\log\left(C^{3/2}%2B\sqrt{C^3-1}\right)}{8C^2\sqrt{C^4-C}}}">

### Radius of Curvature Distribution in Oblate Spheroid

Mass function:

<img src="https://render.githubusercontent.com/render/math?math=\huge\displaystyle f_C(\bar{R}) = \frac{\sqrt{\frac{1-{C'}^{4/3}\cdot\bar{R}^{2/3}}{{C'}-{C'}^4}}}{-\frac{3{C'}^2}{4} %2B \frac{3}{8{C'}} %2B \frac{\frac{3\pi}{2} - 3\cdot\arcsin\left({C'}^{3/2}\right)}{8{C'}^2\sqrt{{C'}-{C'}^4}}}, \qquad C' = \frac{1}{C^2}">

Cumulative function:

<img src="https://render.githubusercontent.com/render/math?math=\large F_C(\bar{R}) = \frac{\displaystyle\sqrt{\frac{1-{C'}^{4/3}\bar{R}^{2/3}}{{C'}-{C'}^4}}\left(\frac{3\bar{R}}{4} - \frac{3\bar{R}^{1/3}}{8{C'}^{4/3}}\right) %2B \frac{3\cdot\arcsin\left({C'}^{2/3}\bar{R}^{1/3}\right)}{8{C'}^2\sqrt{{C'}-{C'}^4}}-\frac{3{C'}^2}{4} %2B \frac{3}{8{C'}} -  \frac{3\cdot\arcsin\left({C'}^{3/2}\right)}{8{C'}^2\sqrt{{C'}-{C'}^4}}}{\displaystyle -\frac{3{C'}^2}{4} %2B \frac{3}{8{C'}} %2B \frac{\frac{3\pi}{2} - 3\cdot\arcsin\left({C'}^{3/2}\right)}{8{C'}^2\sqrt{{C'}-{C'}^4}}}, \text{with }\ C' = \frac{1}{C^2}">
