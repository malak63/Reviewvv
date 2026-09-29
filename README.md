Here are the answers for the questions shown in your photos, in an exam-ready format.

3.4.1 Question 1: Parallel RC Circuit

a) Capacitive reactance

\boxed{X_C=\frac{1}{2\pi fC}}

Where:

* X_C = capacitive reactance in Ω
* f = frequency in Hz
* C = capacitance in F

b) Impedance in a parallel RC circuit

\boxed{Z=\frac{R X_C}{\sqrt{R^2+X_C^2}}}

⸻

3.4.2 Question 2

Given:

* R=1\,k\Omega=1000\,\Omega
* C=500\,\mu F=500\times10^{-6}F
* f=2\,Hz

a) Calculate the reactance of the capacitor

Formula:

X_C=\frac{1}{2\pi fC}

Substitute:

X_C=\frac{1}{2\pi(2)(500\times10^{-6})}

X_C=\frac{1}{0.006283}

\boxed{X_C\approx159.15\,\Omega}

b) Calculate the impedance

For the series RC circuit shown:

Z=\sqrt{R^2+X_C^2}

Z=\sqrt{1000^2+159.15^2}

Z=\sqrt{1\,000\,000+25\,329}

Z=\sqrt{1\,025\,329}

\boxed{Z\approx1012.6\,\Omega}

or

\boxed{Z\approx1.013\,k\Omega}

c) Name two factors that would lower the impedance

Any two:

1. Increase the frequency f — this decreases X_C.
2. Increase the capacitance C — this decreases X_C.
3. Decrease the resistance R.

⸻

3.4.3 Question 3: Kirchhoff’s Law

a) Kirchhoff’s Current Law (KCL)

\boxed{\sum I_{\text{in}}=\sum I_{\text{out}}}

In words:

The total current entering a junction is equal to the total current leaving the junction.

b) Circuit calculation

Using the indicated current directions:

The right-hand branch has:

I_3=\frac{5V}{5\Omega}

\boxed{I_3=1A}

Using KCL:

I_1+I_2=I_3

Therefore:

I_1+I_2=1

Applying Kirchhoff’s Voltage Law to the left loop gives:

2I_1+4I_2=10

So:

I_1+2I_2=5

Subtract:

(I_1+2I_2)-(I_1+I_2)=5-1

I_2=4A

Then:

I_1+4=1

\boxed{I_1=-3A}

The negative sign means I_1 actually flows opposite to the arrow shown.

Thus:

\boxed{I_1=-3A}

\boxed{I_2=4A}

\boxed{I_3=1A}

Important: The battery polarities in the photograph are somewhat difficult to distinguish. If your lecturer’s intended battery polarities are different from the interpretation above, the numerical current directions can change.

⸻

3.4.4 Question 4: Boolean Algebra

a) Simplify

The expression shown is:

AB+A\overline{B}+\overline{A}B

First group the first two terms:

AB+A\overline{B}

Factor out A:

=A(B+\overline B)

Using the complement law:

B+\overline B=1

Therefore:

=A

So:

A+\overline AB

Using the absorption law:

A+\overline AB=A+B

Therefore:

\boxed{F=A+B}

⸻

Question 4(b): Gate System

Step 1 — Find X

The first gate is an AND gate:

\boxed{X=AB}

Step 2 — Find Y

The next gate is an OR gate with X and C:

Y=X+C

Substitute X=AB:

\boxed{Y=AB+C}

Step 3 — Find F

The final gate is a NAND gate:

F=\overline{YC}

Substitute Y=AB+C:

F=\overline{(AB+C)C}

Using the distributive law:

F=\overline{ABC+C}

Using the absorption law:

ABC+C=C

Therefore:

F=\overline C

Final answer:

\boxed{F=\overline C}

So the complete sequence is:

\boxed{X=AB}

\boxed{Y=AB+C}

\boxed{F=\overline{(AB+C)C}}

\boxed{F=\overline C}

Final simplified result:

\boxed{F=C'}
