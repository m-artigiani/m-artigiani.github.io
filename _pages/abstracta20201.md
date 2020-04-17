---
layout: page
title: "Álgebra abstracta y codificación"
date: 2020-01-31
modified:
permalink: /teaching/abstracta20201/
image:
  feature:
  teaser:
  thumb:
---

<figure style="float: right; width:35%; margin-left:2%; margin-bottom:2%; margin-top:2%;">
<img src="../../images/Euclidean_Algorithm.svg" />
<figcaption>Image courtesy of Wikimedia.</figcaption>
</figure>

### Horario:
  Martes: 9.00-11.00, Aula: CASUR 506.\\
  Viernes: 13.00-15.00, Aula: CASUR 308.

**Horario de atención**:
  Lunes: 11.00-13.00, virtual, salón 234-Claustro.

[Guía de clase](../../files/abstracta20201.doc)

### Libro de texto:
+ Cameron, Peter J., _Introduction to Algebra_, Second Edition, Oxford Mathematics, Oxford, 2008.

### Referencias adicionales
+ Zimmermann, Paul _et al._, [Computational Mathematics with SageMath](http://dl.lateralis.org/public/sagebook/sagebook-ba6596d.pdf)

### Talleres y Parciales
+ [Primer Taller](../../files/Taller1Abstracta.pdf) **Entrega Viernes 21/02 a comienzo de clase**
+ [Primer Parcial](../../files/Parcial1Abstracta.pdf) y [Solución](../../files/SolParcial1Abstracta.pdf)
+ [Segundo Taller](../../files/Taller2Abstracta.pdf) y [Solución](../../files/SolTaller2Abstracta.pdf) **Entrega Jueves 16/04 a comienzo de la monitoría**
+ [Segundo Parcial](../../files/Parcial2Abstracta.pdf) y [Solución](../../files/SolParcial2Abstracta.pdf)

### Diario de las lecciones
+ 21/01: Repaso: Notación para conjuntos de números. Técnicas demonstrativas, Existen infinitos primos, raíz de 2 es irraciónal. División euclidiana en los enteros. Inducción y inducción fuerte.
+ 24/01: Repaso: Números complejos, arítmetica en los complejos, forma polar de los números complejos. Polinomios y división entre ellos. Relaciones.
<figure style="float: left; width:20%; margin-right:2%; margin-bottom:2%; margin-top:2%;">
<img src="../../images/Rubikcube.svg" />
<figcaption>Image courtesy of Wikimedia.</figcaption>
</figure>
+ 28/01: Relaciones, relaciones de equivalencia. Ejemplos. Relaciones y particiones de un conjunto. Congruencia módulo m. Máximo comun divisor y algoritmo de Euclides. Teorema de Bezout (_enunciado_).
+ 30/01: Arítmetica en \\( \mathbb{Z}_m \\) . Invertibilidad multiplicativa en \\( \mathbb{Z}_m \\) y máximo comun divisor. Definición de anillo. Ejemplos: enteros, campos númericos, polinomios, matrices, anillos finitos, anillo 0, un anillo finito que no es \\( \mathbb{Z}_m \\). Asociadividad de la suma entre cualquier número de terminos en un anillo.
+ 04/02: Anillos booleanos. Arítmetica en anillos. Subanillos: definición y test para decidir si un subconjunto es un subanillo. Todos los subanillos de \\( \mathbb{Z} \\) son de la forma \\( m \mathbb{Z} \\).
+ 07/02: Definiciones de coset a través de la relación de equivalencia. Rapresentación de la clases de equivalencia. Ejemplo: \\( R=\mathbb{Z} \\) y \\( S=m\mathbb{Z} \\). Homorfísmos e isomorfísmo entre anillos. Clasificación de los homomorfísmos de \\( \mathbb{Z} \\) en si mismo. Nucleo e imagen de un homomorfísmo son subanillos.
+ 11/02: Definición de ideal. El nucleo es un ideal. Todos los ideales de \\( \mathbb{Z} \\) son de la forma \\( m \mathbb{Z} \\). En un anillo con identidad los ideales que contienen la identidad son todo el anillo. Un anillo conmutativo con unidad es un campo si y solo si tiene solamente ideales triviales. Dado un anillo \\( R \\) existe un anillo \\(R^* \\) con unidad que contiene un subanillo isomorfo a \\(R\\).
+ 14/02: Anillo cociente. Homorfísmo canónico, primer teorema de isomorfísmo. Ejemplo: \\( \mathbb{Z}\[i\]/(1+3i) \\) es isomorfo a \\( \mathbb{Z}_{10} \\).
+ 18/02: Ejemplos: \\(\mathbb{Z}\_9 \\) no es isomorfo a \\( \mathbb{Z}\_3 \times \mathbb{Z}\_3 \\). \\( \mathbb{Z}_{15} \\) es isomorfo a \\( \mathbb{Z}_3 \times \mathbb{Z}_5 \\).
+ 21/02: Solución del taller. Ejemplo: \\( \mathbb{R}\[x\]/(x^2+1) \\) es isomorfo a los complejos.
+ 25/02: Anillo de los polinomios con coeficientes en un anillo. Zeros de un polinomio con coeficientes en un campo y su grado. Factorización en \\( \mathbb{Z} \\): elementos irreducibles y primos; irreducible implica primo. Teorema fundamental del aritmética. Factorización en anillos: divisores del 0, unidades, ejemplo en \\(\mathbb{Z}_m \\).
+ 28/02: Primer Parcial.
+ 03/03: Solución primer parcial. Divisores del cero, unidades, irreducibles, primos. Un elemento en \\(\mathbb{Z}\_m\\) es una unidad si y solo si es primo con \\(m\\), de otra manera es un divisor del cero. Dominios a factorización unica (UFD), Lema de Gauss (_enunciado_).
+ 06/03: Un ejemplo de anillo que no sea un UFD: \\( R=\lbrace a+b\sqrt{-5}, a,b\in\mathbb{Z} \rbrace\\). Dominios a factorización única y máximo común divisor. Ideal generado por elementos \\(a\_1,\dots,a\_n\\), dominio a idealeas principales (PID).
+ 10/03: PID implica UFD. Un ejemplo de UFD que no es PID: \\(\mathbb{Z}[x]\\). Dominios euclidianos (ED).
+ 13/03: ED implica PID. Factorización en ED. Como obtener un campo de un anillo: campo de fracciones. Ideales maximales y campos.
+ ~~17/03:~~ Clase cancelada. Las clases abajo son **virtuales**.
+ 20/03: Campo obtenidos agregando elementos. Definición de grupo. Ejemplos.
+ 24/03: Grupo simétrico. Notación en ciclos para las permutaciones. El grupo \\(D\_4\\) diedral del cuadrado como grupo de permutaciones. Subgrupos. Cosets izquierdos y derechos de un subgrupo.
+ 27/03: Orden de un grupo. Indice de un subgrupo. Teorema de Lagrange: \\(\|G\|=\|H\|\|G:H\|\\). Orden de un elemento.
+ 31/03: Grupos cíclicos y sus subgrupos. Homomorísmos y isomorfísmos de grupos. Los grupos cíclicos del mismo orden son isomorfos. Subgrupos normales y grupos cocientes. Primer teorema de isomorfísmo para grupos.
+ 03/04: Conjugación. Centralizador de un elemento y ecuación de las clases. Centro de un grupo. Automorfísmos internos de un grupo.
+ 14/04: Ejercicios.
+ 17/04: Segundo parcial.
