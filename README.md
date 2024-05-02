
> # ABOUT ME
>Hey there iam hyper and this is my github profile. And the two things i love the most are coding and VFX.
>VFX grew as a hobby for me.i started messing around with softwares like blender and unreal engine.
>the other part of me just loves coding iam still in the making but i hope that one day i will be one of best AI + software Engineer.

```tikz
\begin{tikzpicture}
    % Draw a circle
    \draw (0,0) circle (1cm);

    % Fill a rectangle within the circle
    \begin{scope}
        \clip (0,0) circle (1cm);
        \fill[black] (0cm,1cm) rectangle (-1cm, -1cm);
    \end{scope}

    % Draw two filled circles
    \fill[black] (0,0.5) circle (0.5cm);
    \fill[white] (0,-0.5) circle (0.5cm);

    % Draw smaller circles within the filled circles
    \fill[white] (0,0.5) circle (0.1cm);
    \fill[black] (0,-0.5) circle (0.1cm);
\end{tikzpicture}

```
