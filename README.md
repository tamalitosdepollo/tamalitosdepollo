- 👋 Hi, I’m @tamalitosdepollo
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
tamalitosdepollo/tamalitosdepollo is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
# Demostración de la continuidad en \( x = 0 \) para la función dada

## Función dada
La función \( f: \mathbb{R} \to \mathbb{R} \) está definida por:

\[ 
f(x) = 
\begin{cases} 
x \sin\left(\frac{1}{x}\right) & \text{si } x \neq 0 \\ 
0 & \text{si } x = 0 
\end{cases} 
\]

## Objetivo
Queremos demostrar que la función \( f \) es continua en \( x = 0 \) usando la definición \(\epsilon-\delta\).

## Definición de continuidad
La función \( f \) es continua en \( x = 0 \) si, para todo \(\epsilon > 0\), existe un \(\delta > 0\) tal que, si \(|x| < \delta\), entonces \(|f(x) - f(0)| < \epsilon\).

## Paso 1: Definición del límite
Para demostrar que \( \lim_{x \to 0} f(x) = 0 \):

Para todo \(\epsilon > 0\), existe un \(\delta > 0\) tal que, si \(|x| < \delta\), entonces \(|f(x) - 0| < \epsilon\).

## Paso 2: Expresión de \(|f(x) - f(0)|\)
Consideremos \(|f(x) - f(0)| = |f(x)|\) porque \(f(0) = 0\):

\[ 
|f(x)| = \left| x \sin\left(\frac{1}{x}\right) \right|.
\]

## Paso 3: Acotación de \(\left| x \sin\left(\frac{1}{x}\right) \right|\)
Sabemos que, para todos los \( x \neq 0 \):

\[ 
|\sin\left(\frac{1}{x}\right)| \leq 1.
\]

Por lo tanto:

\[ 
\left| x \sin\left(\frac{1}{x}\right) \right| \leq |x|.
\]

## Paso 4: Elección de \(\delta\)
Queremos que \(\left| x \sin\left(\frac{1}{x}\right) \right| < \epsilon\). Dado que \(\left| x \sin\left(\frac{1}{x}\right) \right| \leq |x|\), podemos garantizar que \(\left| x \sin\left(\frac{1}{x}\right) \right| < \epsilon\) si simplemente hacemos \(|x| < \epsilon\).

## Paso 5: Formalización de \(\delta\)
Podemos elegir \(\delta = \epsilon\). Entonces, si \(|x| < \delta\), tenemos que \(|x| < \epsilon\), lo que implica:

\[ 
\left| x \sin\left(\frac{1}{x}\right) \right| < \epsilon.
\]

## Paso 6: Conclusión
Por lo tanto, hemos demostrado que, para cualquier \(\epsilon > 0\), podemos encontrar \(\delta = \epsilon\) tal que si \(|x| < \delta\), entonces \(\left| x \sin\left(\frac{1}{x}\right) \right| < \epsilon\). Esto demuestra que:

\[ 
\lim_{x \to 0} f(x) = 0 = f(0).
\]

En conclusión, la función \( f(x) \) es continua en \( x = 0 \) según la definición \(\epsilon-\delta\).
