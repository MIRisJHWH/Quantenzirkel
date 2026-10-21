Als erstes möchte ich den Energie- bzw. den Impulsoperator aus der Kinematik herleiten.

Es gelte:

$$\frac{\mathrm{d}^2 s}{\mathrm{dt}^2}=\frac{\mathrm{d} v}{\mathrm{dt}}=a$$.

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

Jedoch der Clou ist, dass wir jene Kraft mit der Zentalkraft $$\vec{F_Z}=m\omega^2r $$ gleichsetzen.


Für $$W$$ setzen wir alle nicht-radialen Anteile gleich 0. In Kugelkoordianten:


$$
W=\int \vec{F} \vec{\mathrm{d}s} = \int \vec{F_Z}( \mathrm{d}r \vec{e}_r+r\mathrm{d}\theta\vec{e}_\theta + r \mathrm{sin} \theta \mathrm{d}\varphi \vec{e}_\varphi )     .
$$

wobei $$\theta$$ der Azimnnutalwinkel ist, $$r$$ die Komponente in radiale Richtung, $$\varphi $$ der Polarwinkel und  die $$\vec{e}_i$$ Einheitsvektoren in i- Richtung sind.

Für Kugelkoordianten gilt also für die Zentralkraft

$$
\begin{aligned}
    W &= \int F_{Z}\mathrm{d}r \\
      &= \int m \omega^2 r \mathrm{d}r \\
      &= \frac{1}{\mathrm{i}} \int m \omega v^2 \mathrm{d}t.
\end{aligned}
$$


In der obigen Gleichung wurde die Kettenregel $$\mathrm{d}r=v \mathrm{d}t$$ verwendet und unsere Startbedingung $$\mathrm{i} \omega r=v$$ eingesetzt, wobei gelten soll, dass die Geschwindigkeit radial entlang der Kugeloberfläche mit dem Weg radial entlang der Kugeloberfläche über die imaginäre Einheit 


$$ \mathrm{i}$$


und die Winkelfrequenz $$\omega $$ verknüpft ist.

Wie können wir uns diesen Aufbau bildlich vorstellen?

Man muss also beachten:

Wenn wir hier von einer Geschwindigkeit reden und davon, dass die Geschwindigkeit mit der Beschleunigung und dem Weg über die Ableitungen zusammenhängen, dann haben wir für unser oszillierendes System lediglich eine Symmetrie entlang der Kugeloberfläche mit variierendem Radius, um genau zu sein entlang des Polarwinkels und des Azimutalwinkels

Wenn hier also etwas schwingt, was ich hoffe, dann nur entlang der Kugeloberfläche.

Nun zum Impulsoperator:



Als nächstes soll es uns darum gehen, das Arbeitsintegral zu lösen. Wir werden sehen, dass es verschwindet. Über diese Tatsache kann man sich ja insgeheim schon einmal Gedanken machen. Was bedeutet es, dass ein Arbeitsintegral verschwindet? Ich glaube, das hat etwas mit einem konservativen Kraftfeld zu tun.
Vernutlch wird in unserem oszillierenden System der fundamentalen Kinematik keine Arbeit entlang der radialen Richtung verrichtet; es könnte sich um einen idealen harmonischen Oszillator handeln.
Ob wir hier dem Geheimnis der Materie auf der Spur sind, bleibt verborgen. Immerhin sind es rein klassische Überlegungen.

An die "Arbeit"!

$$\begin{aligned} W &= \frac{1}{\mathrm{i}} \int m \omega v^2  \mathrm{d}t \\ 
                    &= \frac{\mathrm{i}}{\mathrm{i}} \int m \omega v^2 \frac{1}{a}  \mathrm{d}v \end{aligned}$$
wobei gilt, dass $$\frac{\mathrm{dv}}{\mathrm{d}t}=a$$

oder umgestellt
$$\mathrm{d}t=\frac{\mathrm{d}v}{a}$$.

Es wird verwendet, dass $$\frac{1}{a}$$ die Umkehrfunktion der Zeit nach der Geschwindigkeit ist $$\frac{1}{a}=\frac{\mathrm{d} t}{\mathrm{d} v} \,
$$

Warum darf man das machen? Weil die Zeit abgeleitet nach der Geschwindigkeit die Umkehrfunktion von $$a$$ ist; ohne Beschränkung der Allgemeinheit!

$$\frac{1}{a} a = 1$$,
$$\frac{\mathrm{d} t}{\mathrm{d} v}\frac{\mathrm{d} v}{\mathrm{d}t{}}=\frac{\mathrm{d} t}{\mathrm{d} v}a .$$
Daraus folgt direkt, dass
$$\frac{\mathrm{d} t}{\mathrm{d} v} = \frac{1}{a}$$ 
sein muss.

Zurück an die Arbeit:


$$
\begin{aligned} 
W &= \frac{1}{\mathrm{i} } \int m \omega v^2 \frac{1}{a} \ \mathrm{d}v \\
&= \frac{1}{\mathrm{i}}m \omega \left( t v^2-2\int vt \mathrm{d}v \right) \\
&= \frac{m \omega}{\mathrm{i}} \left( t v^2-2 \left( t v^2 -\int t v \mathrm{d} v \right)  \right)\\ 
&= \frac{m \omega }{\mathrm{i}} \left(-tv^2 + 2\int t v \mathrm{d} v \right) 
\end{aligned}
$$

Gr0ße Foglerung!


Das Integral muss verschwinden!


$$
-\frac{m \omega }{i} ( t v^2 - 2 \int vt  dv ) = \frac{m \omega}{i} ( t v^2 - 2 \int vt  dv )
$$

Denn wenn das negative Element gleich dem positven Element ist

$$
\begin{aligned}
    x=-x
\end{aligned}
$$

gilt $$x=0$$ .

Daraus folgt also


$$
\frac{m \omega }{\mathrm{i}} \left( tv^2-2\int vt \mathrm{d}v \right) = 0 .
$$

Da $$W=\frac{1}{\mathrm{i}} \int m \omega v^2  \mathrm{d}t=   \frac{m \omega }{\mathrm{i}} \left( tv^2-2\int vt \mathrm{d}v \right)= 0 $$ ist, man kann es etwas weiter oben sehen, gilt

$$
\begin{aligned}
    m\omega v^2 = \mathrm{Const}(\backslash  t)
\end{aligned}
$$

Der gewonnene Ausdruck 


$$
m\omega v^2
$$


ist also eine Konstante. Das $$\backslash t$$ bedeutet, dass der Ausdruck explizit nicht von der Zeit abhängt.


$$ a= b + c $$





