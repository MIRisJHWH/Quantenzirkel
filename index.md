Als erstes möchte ich den Energie- bzw. den Impulsoperator aus der Kinematik herleiten.

Es gelte:

$$ \frac{\mathrm{d}^2 s}{\mathrm{dt}^2}=\frac{\mathrm{d} v}{\mathrm{dt}}=a $$.

Es gelte weiterhin

$$(\mathrm{i}\omega)^2 s=\mathrm{i}\omega v = a$$.

Es muss sich also gemäß Startbedingung bzw. Annahme um eine harmonische Schwingung handeln.

Wenn wir die Gleichungen miteinander identifizieren, erhalten wir

$$\mathrm{i}\omega = \frac{\mathrm{d}}{\mathrm{d}t}$$

Mit der Planck-Einstein-Relation $$E=\hbar  \omega$$ erhalten wir also

$$\mathrm{i}\frac{E}{\hbar} = \frac{\mathrm{d}}{\mathrm{d}t}$$

woraus direkt folgt

$$E=-\mathrm{i\hbar}\frac{\mathrm{d}}{\mathrm{d}t}$$.

Da in der Quantenmechanik lediglich Betragsquadrate einer physikalischen Realität entsprechen, kann das Minus für die Energie vernachlässigt werden. Es wird durch das quadrieren einfach neutralisiert.

Im nächsten Schritt soll es uns um den Impulsoperator gehen.

Dafür wenden wir eine weltbewegende Relation an:

$$
W=\int \vec{F} \vec{\mathrm{d}s}.
$$

Es ist das herkömmliche Wegintegral aus der klassischen Mechanik.

Jedoch der Clou ist, dass wir jene Kraft mit der Zentrifugalkraft $$\vec{F_Z}=m\omega^2r $$ gleichsetzen.


Für $$W$$ setzen wir alle nicht-radialen Anteile gleich 0. In Zylinderkoordianten:


$$
W=\int \vec{F} \vec{\mathrm{d}s} = \int \vec{F_Z}(\mathrm{d}r \vec{e}_r+r\mathrm{d}\theta\vec{e}_\theta+\mathrm{d}z\vec{e}_z)     .
$$

wobei $$\theta$$ der Polarwinkel ist, $$r$$ die Komponente in radiale Richtung, $$z$$ die Komponente in z-Richtung und  die $$\vec{e}_i$$ Einheitsvektoren in i- Richtung sind.

Für Zylinderkoordianten gilt also

$$
\begin{align}
    W &=\int F_{Z}\mathrm{d}r \\ 
      &= \int m \omega^2 r \mathrm{d}r \\
      &=\frac{1}{\mathrm{i}} \int m \omega v^2 \mathrm{d}t.
\end{align}
$$

In der obigen Gleichung wurde die Kettenregel $$\mathrm{d}r=v \mathrm{d}t$$ verwendet und unsere Startbedingung $$\mathrm{i}\omega r=v$$ eingesetzt, wobei gelten soll, dass die Geschwindigkeit radial entlang des Zylinders mit dem Weg radial entlang des Zylinders über die imaginäre Einheit $$ \mathrm{i}$$ und die Winkelfrequenz $$\omega$$ verknüpft ist.

Wie können wir uns diesen Aufbau bildlich vorstellen?

Man muss also beachten:

Wenn wir hier von einer Geschwindigkeit reden und davon, dass die Geschwindigkeit mit der Beschleunigung und dem Weg über die Ableitungen zusammenhängen, dann haben wir für unser oszillierendes System lediglich eine Symmetrie entlang des Zylinders, um genau zu sein entlang der z-Achse und dem Polarwinkel $$\theta$$.

Wenn hier also etwas schwingt, was ich hoffe, dann nur entlang des Zylindermantels.









