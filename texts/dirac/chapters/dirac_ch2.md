#II DYNAMICAL VARIABLES AND OBSERVABLES

#7. Linear operators

IN the preceding section we considered a number which is a linear function of a ket vector, and this led to the concept of a bra vector. We shall now consider a ket vector which is a linear function of a ket vector, and this will lead to the concept of a linear operator.

Suppose we have a ket $\ket{F}$ which is a function of a ket $\ket{A}$, i.e. to each ket $\ket{A}$ there corresponds one ket $\ket{F}$, and suppose further that the function is a linear one, which means that the $\ket{F}$ corresponding to $\ket{A}+\ket{A'}$ is the sum of the $\ket{F}$’s corresponding to $\ket{A}$ and to $\ket{A’}$, and the $\ket{F}$ corresponding to $c\ket{A}$ is c times the $\ket{F}$ corresponding to $\ket{A}$, c being any numerical factor. Under these conditions, we may look upon the passage from $\ket{A}$ to $\ket{F}$ as the application of a linear operator to $\ket{A}$. Introducing the symbol a: for the linear operator, we may write

$$\ket{F} = \alpha\ket{A},$$
in which the result of on operating on $\ket{A}$ is written like a product of a with $\ket{A}$. We make the rule that in such products the ket vector
must always be put on the right of the linear operator. The above conditions of linearity may now be expressed by the equations
\begin{align}
\alpha\\{\ket{A}+\ket{A'}\\} &= \alpha\ket{A} + \alpha\ket{A'},\\
\alpha\\{c\ket{A}\\} = c\alpha\ket{A}.
\end{align}

A linear operator is considered to be completely defined when the result of its application to every ket vector is given. Thus a linear operator is to be considered zero if the result of its application to every ket vanishes, and two linear operators are to be considered equal if they produce the same result when applied to every ket.

Linear operators can he added together, the sum of two linear operators being defined to be that linear operator which, operating on any ket, produces the sum of what the two linear operators separately would produce. Thus $\alpha+\beta$ is defined by
\begin{equation}
    \\{\alpha + \beta \\} \ket{A} = \alpha\ket{A} + \beta\ket{A}
\end{equation}
for any $\ket{A}$. Equation (2) and the first of equations (1) show that products of linear operators with ket vectors satisfy the distributive axiom of multiplication.

Linear operators can also be multiplied together, the product of two linear operators being defined as that linear operator, the application of which to any ket produces the same result as the application of the two linear operators successively.. Thus the product $\alpha\beta$ is defined as the linear operator which, operating on any ket $\ket{A}$, changes it into that ket which one would get by operating first on $\ket{A}$ with B, and then on the result of the first operation with $\alpha$. In symbols
$$\\{\alpha\beta\\}\ket{A} = \alpha\\{\beta\ket{A}\\}$$

This definition appears as the associative axiom of multiplication for the triple product of $\alpha$, $\beta$, and $\ket{A}$, and allows us to write this triple product as $\alpha\beta\ket{A}$ without brackets. However, this triple product is in general not the same as what we should get if we operated on $\ket{A}$ first with $\alpha$ and then with $\beta$, i.e. in general $\alpha\beta\ket{A}$ differs from $\beta\alpha\ket{A}$, so that in general $\alpha\beta$ must differ from $\beta\alpha$. The commutative axiom of multiplication does not hold for linear operators. It may happen as a special case that two linear operators if $\xi$ and $\eta$ are such that $\xi\eta$ and $\eta\xi$ are equal. In this case we say that $\xi$ commutes with $\eta$, or that $\xi$ and $\eta$ commute.

By repeated applications of the above processes of adding and multiplying linear operators, one can form sums and products of more than two of them, and one can proceed to build up an algebra with them. In this algebra the commutative axiom of multiplication does not hold, and also the product of two linear operators may vanish without either factor vanishing. But all the other axioms of ordinary algebra, including the associative and distributive axioms of multiplication, are valid, as may easily be verified.

If we take a number k and multiply it into ket vectors, it appears as a linear operator operating on ket vectors, the conditions (1) being fulﬁlled with k substituted for $\alpha$. A number is, thus a special case of a linear operator. It has the property that it commutes with all linear operators and this property distinguishes it from a general linear operator.

So far we have considered linear operators operating only on ket
vectors. We can give a meaning to their operating also on bra vectors,
in the following way. Take the scalar product of any bra $\bra{B}$ with
the ket $\alpha\ket{A}$. This scalar product is a number which depends
linearly on $\ket{A}$ and therefore, from the definition of bras, it may be
considered as the scalar product of $\ket{A}$ with some bra. The bra thus defined depends linearly on $\bra{B}$, so we may look upon it as the result of some linear operator applied to $\bra{B}$. This linear operator is uniquely
determined by the original linear operator a and may reasonably be called the same linear operator operating on a bra. In this way our linear operators are made capable of operating on bra vectors.

A suitable notation to use for the resulting bra when a operates on the bra $\bra{B}$ is $\bra{B}\alpha$, as in this notation the equation which defines $\bra{B}\alpha$ is
\begin{equation}
\\{\bra{B}\alpha\\}\ket{A} = \bra{B}\\{\alpha\ket{A}\\}
\end{equation}

for any $\ket{A}$, which simply expresses the associative axiom of multi-
plication for the triple product of $\bra{B}$, \alpha, and $\ket{A}$. We therefore make the general rule that in a product of a bra and a linear operator, the bra must always be put on the left. We can now write the triple product of $\bra{B}$, $\alpha$, and $\ket{A}$ simply as $\bra{B}\alpha\ket{A}$ without brackets. It may easily be verified that the distributive axiom of multiplication holds for products of bras and linear operators just as well as for products of linear operators and kets.

There is one further kind of product which has a meaning in our scheme, namely the product of a ket vector and a bra vector with the ket on the left, such as $\ket{A}\bra{B}$. To examine this product, let us multiply it into an arbitrary ket $\ket{P}$, putting the ket on the right, and assume the associative axiom of multiplication. The product is then $\ket{A}\braket{B}{P}$, which is another ket, namely $\ket{A}$ multiplied by the
number $\braket{B}{P}$, and this ket depends linearly on the ket $\ket{P}$. Thus $\ket{A}\bra{B}$ appears as a linear operator that can operate on kets. It can also operate on bras, its product with a bra $\bra{Q}$ on the left being
$\braket{Q}{A}\bra{B}$, which is the number $\braket{Q}{A}$ times the bra $\bra{B}$. The product $\ket{A}\bra{B}$ is to be sharply distinguished from the product $\braket{B}{A}$ of the same factors in the reverse order, the latter product being, of course, a number.

We now have a complete algebraic scheme involving three kinds of quantities, bra vectors, ket vectors, and linear operators. They can be multiplied together in the various ways discussed above, and the associative and distributive axioms of multiplication always hold, but the commutative axiom of multiplication does not hold. In this general scheme we still have the rules of notation of the preceding section, that any complete bracket expression, containing $\langle$ on the left and $\rangle$ on the right, denotes a number, while any incomplete bracket expression, containing only $\langle$ or $\rangle$, denotes a vector.

With regard to the physical significance of the scheme, We have already assumed that the bra vectors and ket vectors, or rather the directions of these vectors, correspond to the states of a dynamical system at a particular time. We now make the further assumption that the linear operators correspond to theklynamical variables at that time. By dynamical variables are meant quantities such as the coordinates and the components of velocity, momentum and angular momentum of particles, and functions of these quantities--in fact the variables in terms of which classical mechanics is built up. The new assumption requires that these quantities shall occur also in quantum mechanics, but with the striking difference that they are now subject to an algebra in which the commutative axionz of multiplication does not hold.

This different algebra for the dynamical variables is one of the most important ways in which quantum mechanics differs from classical mechanics. We shall see later on that, in spite of this fundamental difference, the dynamical variables of quantum mechanics still. have many properties in common with their classical counterparts and it will be possible to build up a theory of them closely analogous to the classical theory and forming a beautiful generalization of it.

It is convenient to use the same letter to denote a dynamical variable and the corresponding linear operator. In fact, We may consider a dynamical variable and the corresponding linear operator to be both the same thing, Without getting into confusion.

#8. Conjugate relations

Our linear operators are complex quantities, since one can multiply
them by complex numbers and get other quantities of the same nature.
Hence they must correspond in general to complex dynamical variables, i.e. to complex functions of the coordinates, velocities, etc. We
need some further development of the theory to see What kind of
Linear operator corresponds to a real dynamical variable.

Consider the Bet which is the conjugate imaginary of $\bra{P}\alpha$. This
ket depends antilinearly on $\bra{P}$ and thus depends linearly on $\ket{P}$.
It may therefore be considered as the result of some linear operator
operating on $\ket{P}$. This linear operator is called the *adjoint* of $\alpha$ and we shall denote it by $\bar{\alpha}$. With this notation, the conjugate imaginary of $\bra{P}\alpha$ is $\bar{\alpha}\ket{P}$.

In formula (7) of Chapter I put $\bra{P}\alpha$ for $\bra{A}$ and its conjugate imaginary $\bar{\alpha}\ket{P}$ for $\ket{A}$. The result is
\begin{equation}
\bra{B}\bar{\alpha}\ket{P} = \overline{\bra{P}\alpha\ket{B}}.
\end{equation}

This is a general formula holding for any ket vectors $\ket{B}$, $\ket{P}$ and
any linear operator $\alpha$, and it expresses one of the most frequently
used properties of the adjoint.

Putting $\bar{\alpha}$ for $\alpha$ in (4), we get

$$\bra{B}\bar{\bar{\alpha}}\ket{P} = \overline{\bra{P}\bar{\alpha}\ket{B}} = \bra{B}\alpha\ket{P},$$

by using (4) again With $\ket{P}$ and $\ket{B}$ interchanged. This holds for
any ket $\ket{P}$, so We can infer from (4) of Chapter I,
$$\bra{B}\bar{\bar{\alpha}} = \bra{B}\alpha,$$
and since this holds for any bra vector $\bra{B}$, we can infer
$$\bar{\bar{\alpha}} = \alpha$$

Thus *the adjoint of the adjoint of a linear operator is the original linear operator*. This property of the adjoint makes it like the conjugate complex of a number, and it is easily verified that in the special case When the linear operator is a number, the adjoint linear operator is the conjugate complex number. Thus it is reasonable to assume that *the adjoint of a linear operator corresponds to the conjugate complex of a dynamical variable*. With this physical significance for the adjoint of a linear operator, We may call the adjoint alternatively the conjugate complex linear operator, Which conforms With onr notation $\bar{\alpha}$.

A linear operator may equal its adjoint, and is then called *self-adjoint*. It corresponds to a real dynamical variable, so it may be called alternatively a *real linear operator*. Any linear operator may be split up into a real part and a pure imaginary part. For this reason the Words 'conjugate complex' are applicable to linear operators and not the words 'conjugate imaginary'.

The conjugate complex of the sum of two linear operators is obviously the sum of their conjugate complexes. To get the conjugate complex of the product of two linear operators $\alpha$ and $\beta$, We apply formula (7) of Chapter I With
$$\bra{A} = \bra{P}\alpha, \bra{B} = \bra{Q}\bar{\beta}$$
$$\mathrm{so that} \ket{A} = \bar{\alpha}\ket{P}, \ket{B} = \beta\ket{Q}.$$
The result is
$$\bra{Q}\bar{\beta}\bar{\alpha}\ket{P} = \overline{\bra{P}\alpha\beta\ket{Q}} = \bra{Q}\overline{\alpha\beta}\ket{P}$$
from (4). Since this holds for any $\ket{P}$ and $\bra{Q}$, we can infer that
\begin{equation}
\bar{\beta}\bar{\alpha} = \overline{\alpha\beta}
\end{equation}
Thus *the conjugate complex of the product of two linear operators equals the product of the conjugate complexes of the factors in the reverse order*.
As simple examples of this result, it should be noted that, if $\xi$ and
$\eta$ are real, in general $\xi\eta$ is not real. This is an important difference from classical mechanics. However, $\xi\eta + \eta\xi$ is real, and so is $i\left(\xi\eta-\eta\xi\right)$. Only when $\xi$ and $\eta$ commute is $\xi\eta$ itself also real. Further, if $\xi$ is real, then so is $\xi^2$ and, more generally, $\xi^n$ with $n$ any positive integer.
We may get the conjugate complex of the product of three linear operators by successive applications of the rule (5) for the conjugate complex of the product of two of them. We have
\begin{equation}
\alpha\beta\gamma = \alpha\left(\beta\gamma\right) = \beta\gamma\bar{\alpha} =\bar{\gamma}\bar{\beta}\bar{\alpha},
\end{equation}
so the conjugate complex of the product of three linear operators equals the product of the conjugate complexes of the factors in the reverse order. The rule may easily be extended to the product of any number of linear operators.

In the preceding section we saw that the product $\ket{A}\bra{B}$ is a linear operator. We may get its conjugate complex by referring directly to the definition of the adjoint. Multiplying $\ket{A}\bra{B}$ into a general bra $\bra{P}$ we get $\braket{P}{A}\bra{B}$, whose conjugate imaginary ket is
$$\overline{\braket{A}{A}}\ket{B} = \braket{A}{P}\ket{B} = \ket{B}\braket{A}{P} $$
Hence
\begin{equation}\overline{\ket{A}\bra{A}} = \ket{B}\bra{A}.\end{equation}

We now have several rules concerning conjugate complexes and conjugate imaginaries of products, namely equation (7 ) of Chapter I, equations (4), (5), (6), (7) of this chapter, and the rule that the conjugate imaginary of $\bra{P}\alpha$ is $\bar{\alpha}\ket{P}$. These rules can all be summed up in a single comprehensive rule, *the conjugate complex or conjugate imaginary of any product of hra vectors, ket vectors, and linear operators is obtained by taking the conjugate complex or conjugate imaginary of each factor and reversing the order of all the factors*. The rule is easily verified to hold quite generally, also for the cases not explicitly given, above.

THEOREM. *If $\xi$ is a real linear operator and*
\begin{equation}\xi^m\ket{P}\end{equation}
*for a particular ket $\ket{P}$, m heing a positive integer, then*
$$\xi\ket{P} = 0$$

To prove the theorem, take first the case when m = 2. Equation
(8) then gives
$$\bra{P}\xi^2\ket{P} = 0$$
showing that the ket $\xi\ket{P}$ multiplied by the conjugate imaginary bra $\bra{P}\xi$ is zero. From the assumption (8) of Chapter I with $\xi\ket{P}$ for $\ket{A}$,

we see that $\xi\ket{P}$ must be zero. Thus the theorem is proved for $m = 2$.
Now take $m > 2$ and put
$$\xi^{m-2}\ket{P} = \ket{Q}$$
Equation (8) now gives
$$\xi^2\ket{Q} = 0$$
Applying the theorem for m = 2, we get
$$\xi\ket{Q} = 0$$
\begin{equation}
\mathrm{or} \xi^{m-1}\ket{P} = 0.
\end{equation}

By repeating the process by which equation (9) is obtained from
(8), we obtain successively
$$\xi^{m-2}\ket{P} = 0, \xi^{m-3}\ket{P} = 0, \ldots, \xi^2\ket{P} = 0, \xi\ket{P} = 0,$$

and so the theorem is proved generally.

#9. Eigenvalues and eigenvectors

We must make a further development of the theory of linear operators, consisting in studying the equation
\begin{equation}
\alpha\ket{P} = a\ket{P},
\end{equation}
where $\alpha$ is a linear operator and $a$ is a number. This equation usually presents itself in the form that $\alpha$ is a known linear operator and the number $a$ and the ket $\ket{P}$ are unknowns, which we have to try to choose so as to satisfy (10), ignoring the trivial solution $\ket{P} = 0$.

Equation (10) means that the linear operator a applied to the ket $\ket{P}$ just multiplies this ket by a numerical factor without changing its direction, or else multiplies it by the factor zero, so that it ceases to have a direction. This same $\alpha$ applied to other kets will, of course, in general change both their lengths and their directions. It should be noticed that only the direction of $\ket{P}$ is of importance in equation (10). If one multiplies $\ket{P}$ by any number not zero, it will not affect the question of whether ( 10) is satisfied or not.

Together with equation (10), we should consider also the conjugate imaginary form of equation
\begin{equation}
\bra{Q}\alpha = b\bra{Q},
\end{equation}
where $b$ is a number. Here the unknowns are the number $b$ and the non-zero bra $\bra{Q}$. Equations (10) and (11) are of such fundamental importance in the theory that it is desirable to have some special words to describe the relationships between the quantities involved.
If (10) is satisfied, We shall call $a$ an *eigenvalue* $\dagger$ of the linear operator $\alpha$, or of the corresponding dynamical variable, and We shall call $\ket{P}$ an *eigenket* of the linear operator or dynamical variable. Further, we shall say that the eigenket $\ket{P}$ belongs to the eigenvalue $a$. Similarly, if (11) is satisfied, We shall call $b$ an eigenvalue of $\alpha$ and $\bra{Q}$ an eigenbra belonging to this eigenvalue. The words eigenvalue, eigenket, eigenbra have a meaning, of course, *only with reference to a linear operator or dynamical variable.*

Using this terminology, We can assert that, if an eigenket of $\alpha$ is multiplied by any number not zero, the resulting ket is also an eigenket and belongs to the same eigenvalue as the original one. It is possible to have two or more independent eigenkets of a linear operator belonging to the same eigenvalue of that linear operator, e.g. equation (10) may have several solutions, $\ket{P_1}, \ket{P_2}, \ket{P_3}, \ldots$ say, all holding for the same value of a, with the various eigenkets $\ket{P_1}, \ket{P_2}, \ket{P_3}, \ldots$ independent. In this case it is evident that any linear combination of the eigenltets is another eigenket belonging to the same eigenvalue of the linear operator, e.g.
$$c_1\ket{P_1} + c_2\ket{P_2} + c_3\ket{P_3} + \ldots$$
is another solution of (10), where $c_1, c_2, c_3, \ldots$ are any numbers.

In the special case when the Linear operator a of equations (10) and
(11) is a number, $k$ say, it is obvious that any ket $\ket{P}$ and bra $\bra{Q}$ will satisfy these equations provided $a$ and $b$ equal $k$. Thus a number considered as a linear operator has just one eigenvalue, and any ket is an eigenliet and any bra is an eigenbra, belonging to this eigenvalue.

The theory of eigenvalues and eigenvectors of a linear operator $\alpha$ which is not real is not of much use for quantum mechanics. We shall therefore confine ourselves to real linear operators for the further development of the theory. Putting for $\alpha$ the real linear operator $\xi$,
We have instead of equations (10) and (11)
\begin{equation}
\xi\ket{P} = a \ket{P},
\end{equation}
\begin{equation}
\bra{Q}\xi = b\bra{Q}.
\end{equation}
$\dagger$ The word 'proper' is sometimes used instead of 'eigein', but this is not satisfactory as the words 'proper' and 'improper' are often used with other meanings. For example, in §§ 15 and 46 the words 'improper function' and 'proper-energy' are used.

Three important results can now be readily deduced.
*(i) The eigenvalues are all real numbers*. To prove that a satisfying
(12) is real, we multiply (12) by the bra $\bra{Q}$ on the left, obtaining
$\bra{P}\xi\ket{P} = a\braket{P}{P}$
Now from equation (4) with $\bra{B}$ replaced by $\bra{P}$ and $\alpha$ replaced by the real linear operator $\xi$, we see that the number $\bra{P}\xi\ket{P}$ must be real, and from (8) of § 6, $\braket{P}{P}$ must be real and not zero. Hence $a$ is real. Similarly, by multiplying (13) by $\ket{Q}$ on the right, we can prove that $b$ is real.

Suppose we have a solution of (12) and we form the conjugate
imaginary equation, which will read
$$\bra{P}\xi = a\bra{P}$$
in view of the reality of $\xi$ and $a$. This conjugate imaginary equation
now provides a solution of (13), with $\bra{Q} = \bra{P}$ and $b = a$. Thus we can infer

(ii) *The eigenvalues associated with eigenkets are the same as the eigenvalues associated with eigenbras*.

(iii) *The conjugate imaginary of any eigenket is a n eigenbra belonging to the same eigenvalue, and conversely*. This last result makes it reasonable to call the state correspondingto any eigenket or to the conjugate imaginary eigenbra an eigenstate of the real dynamical variable $\xi$.

Eigenvalues and eigenvectors of various real dynamical variables are used very extensively in quantum mechanics, so it is desirable to have some systematic notation for labelling them. The following is suitable for most purposes. If $\xi$ is a real dynamical variable, we call its eigenvalues $\xi'.\xi'',\xi^r$, etc. Thus we have a letter by itself denoting a *real dynamical variable* or a *real linear operator*, and the same letter with primes or an index attached denoting a *number*, namely an eigenvalue of what the letter by itself denotes. An eigenvector may now be labelled by the'eigenvalue to which it belongs.
Thus $\ket{\xi'}$ denotes an eigenket belonging to the eigenvalue $\xi'$ of the dynamical variable $\xi$. If in a piece of work we deal with more than one eigenket belonging to the same eigenvalue of a dynamical variable, we may distinguish them one from another by means of a further label, or possibly of more than one further labels. Thus, if we are dealing with two eigenkets belonging to the same eigenvalue of $\xi'$, we may call them $\ket{\xi_1'}$ and $\ket{\xi_2'}$.

THEOREM. *Two eigenvectors of a real dynamical variable belonging to different eigenvalues are orthogonal.*

To prove the theorem, let $\ket{\xi'}$ and $\ket{\xi''}$ be two eigenkets of the real dynamical variable $\xi$, belonging to the eigenvalues $\xi'$ and $\xi''$ respectively. THen we ahve the equations

\begin{equation}
\xi\ket{\xi'} = \xi'\ket{\xi'}
\end{equation}

\begin{equation}
\xi\ket{\xi''} = \xi''\ket{\xi''}
\end{equation}
Taking the conjugate imaginary of (14), we get
$$\bra{\xi'}\xi = \xi'\bra{\xi'}.$$
Multiplying this by $\ket{\xi''}$ on the right gives
$$\bra{\xi'}\xi\ket{\xi''} = \xi'\braket{\xi'}{\xi''}$$
and multiplying (15) by $\bra{\xi'}$ on the left gives
$$\bra{\xi'}\xi\ket{\xi''} = \xi''\braket{\xi'}{\xi''}.$$
\begin{equation}
\mathrm{Hence, subtracting,} \left(\xi'-\xi''\right)\braket{\xi'}{\xi''} = 0,
\end{equation}
showing that, if $\xi'\ne\xi'', \braket{\xi'}{\xi''} = 0$ and the two eigenvectors $\ket{\xi'}$ and $\ket{\xi''}$ are orthogonal. This theorem will be referred to as the *orthogonality theorem*.

We have been discussing properties of the eigenvalues and eigenvectors of a real linear operator, but have not yet considered the question of whether, for a given real linear operator, any eigenvalues and eigenvectors exist, and if so, how to find them. This question is in general very difficult to answer. There is one useful special case, however, which is quite tractable, namely when the real linear operator, $\xi$ say, satisfies an algebraic equation
\begin{equation}
\phi\left(\xi\right) \equiv \xi^n + a_1\xi^{n-1} + a_2\xi^{n-2} + \ldots + a_n =0,
\end{equation}
the coefficients $a$ being numbers. This equation means, of course, that the linear operator $\phi\left(\xi\right)$ produces the result zero when applied to any ket vector or to any bra vector.

Let (17) be the simplest algebraic equation that $\xi$ satisfies. Then it will be shown that

($\alpha$) The number of eigenvalues of $\xi$ is n.

($\beta$) There are so many eigenkets of$\xi$ that any ket whatever can be expressed as a sum of such eigenkets.

The algebraic form $\phi\left(\xi\right)$ can be factorized into $n$ linear factors, the result being
\begin{equation}
\phi\left(\xi\right) \equiv \left(\xi - c_1\right) \left(\xi - c_2\right) \left(\xi - c_3\right) \ldots \left(\xi - c_n\right)
\end{equation}
say, the c's being numbers, not assumed to be all different. This factorization can be performed with $\xi$ a linear operator just as well as with $\xi$ an ordinary algebraic varaible, since there is nothing occurring in (18) that does not commute with $\xi$. Let the quotient when $\phi\left(\xi\right)$ is divided by $\left(\xi-c_r\right)$ be $\chi_r\left(\xi\right)$, so that
$$\phi\left(\xi\right) \equiv \left(\xi-c_r\right)\chi_r\left(\xi\right) \left(r = 1,2,3,\ldots,n\right).$$
Then, for any ket $\ket{P}$,
\begin{equation}
\left(\xi-c_r\right)\chi_r\left(\xi\right)\ket{P} = \phi\left(\xi\right)\ket{P} = 0
\end{equation}

Now $\chi_r\left(\xi\right)\ket{P}$ cannot vanish for every ket $\ket{P}$, as otherwise $\chi_r\left(\xi\right)$ itself would vanish and we should have $\xi$ satisfying an algebraic equation of degree $n-1$, which would contradict the assumption that (17) is the simplest equation that $\xi$ satisfies. If we choose $\ket{P}$ so that $\chi_r\left(\xi\right)\ket{P}$ does not vanish, then equation (19) shows that $\chi_r\left(\xi\right)\ket{P}$ is an eigenket of $|xi$, belonging to the eigenvalue $c_r$. The arguments holds for each value of $r$ from 1 to n, and hence each of the c's is an eigenvalue of $\xi$. No other number can be an eigenvalue of $\xi$, since if $\xi'$ is any eigenvalue, belonging to an eigenket $\ket{\xi'}$,
$$\xi\ket{\xi'} = \xi'\ket{\xi'}$$
and we can deduce $\phi\left(\xi\right)\ket{\xi'} = \phi\left(\xi'\right)\ket{\xi'},$

and since the left-hand side vanishes we must have $\phi\left(\xi'\right) = 0$.

To complete the proof of ($\alpha$) we must verify that the c's are all different. Suppose the c's are not all different and $c_s$ occurs m times say with $m>1$. Then $\phi\left(\xi\right)$ is of the form
$$\phi\left(\xi\right) \equiv \left(\xi - c_s\right)^m\theta\left(\xi\right),$$
with $\theta\left(\xi\right)$ a rational integral function of $\xi$. Equation (17) now gives us
\begin{equation}
\left(\xi - c_s\right)^m\theta\left(\xi\right)\ket{a} = 0
\end{equation}
for any ket $\ket{A}$. Since $c_s$ is an eigenvalue of $\xi$ it must be real, so that $\xi-c_s$ is a real linear operator. Equation (20) is now of the same form as equation (8) with $\xi-c_s$ for $\xi$ and $\theta\left(\xi\right)\ket{A}$ for $\ket{P}$. From the theorem connected with equation (8) we can infer that
$$\left(\xi-c_s\right)\theta\left(\xi\right)\ket{A} = 0.$$
Since the ket $\ket{A}$ is arbitrary,
$$\left(\xi - c_s\right)^m\theta\left(\xi\right) = 0,$$
which contradicts the assumption that (17) is the simplest equaiton that $\xi$ satisfies. Henc ethe c's are all different and ($\alpha$) is proved.

Let $\chi_r\left(c_r\right)$ be the number obtained when $c_r$ is substituted for $\xi$ in the algebraic expression $\chi_r\left(\xi\right)$. Since the c's are all diﬁereilt, $\chi_r\left(c_r\right)$ cannot vanish. Consider now the expression
\begin{equation}
\sum_r \frac{\chi_r\left(\xi\right)}{\chi_r\left(c_r\right)} - 1
\end{equation}

If $c_s$, is substituted for $\xi$ here, every term in the sum vanishes except
the one for which $r = s$, since $\chi_r\left(\xi\right)$ contains $\left(\xi-c_s\right)$ as a factor when $r \ne s$, and the term for which $r = s$ is unity, so the whole expression vanishes. Thus the expression (21) vanishes when $\xi$ is put equal to any of the $n$ numbers $c_1,c_2,\ldots,c_n$. Since, however, the expression is only of degree $n-1$ in $\xi$, it must vanish identically. If we now apply the linear operator (21) to an arbitrary ket $\ket{P}$ and equate the result to zero, me get
\begin{equation}
\ket{P} = \sum_r \frac{1}{\chi_r\left(c_r\right)}\chi_r\left(\xi\right)\ket{P}.
\end{equation}
Each term in the sum on the right here is, according to (19), an eigenket of $\xi$, if it does not vanish. Equation (22) thus expresses the arbitrary ket $\ket{P}$ as a sum of eigenkets of $\xi$, and thus ($\beta$) is proved.

As a simple example we may consider a real linear operator $\sigma$ that
satisfies the equation
\begin{equation}
\sigma^2 = 1.
\end{equation}

Then $\sigma$ has the two eigenvalues 1 and -1. Any ket $\ket{P}$ can be
expressed as
$$\ket{P} = \frac12\left(1 + \sigma\right)\ket{P} + \frac12\left(1-\sigma\right)\ket{P}.$$

It is easily verified that the two terms on the right here are eigenkets of $\sigma$, belonging to the eigenvalues 1 and -1 respectively, when they do not vanish.

#10. Observables

We have made a number of assumptions about the way in which states and dynamical variables are to be represented mathematically in the theory. These assumptions are not, by themselves, laws of nature, but become laws of nature when we make some further assumptions that provide a physical interpretation of the theory. Such further assumptions must take the form of establishing connexions between the results of observations, on one hand, and the equations of the mathematical formalism on the other.

When we make an observation we measure some dynamical variable. It is obvious physically that the result of such a measurement must always be a real number, so we should expect that any dynamical variable that we can measure must be a real dynamical variable. One might think one could measure a complex dynamical variable by measuring separately its real and pure imaginary parts. But this would involve two measurements or two observations, which would be all right in classical mechanics, but would not do in quantum mechanics, where two observations in general interfere with one another--it is not in general permissible to consider that two observations can be made exactly simultaneously, and if they are made in quick succession the first will usually disturb the state of the system and introduce an indeterminacy that will affect the second. We therefore have to restrict the dynamical variables that we can measure to be real, the condition for this in quantum mechanics being as given in §8. Not every real dynamical variable can be measured, however. A further restriction is needed, as we shall see later.

We now make some assumptions for the physical interpretation of the theory. *If the dynamical system is in an eigenstate of a real dynamical variable $\xi$, belonging to the eigenvalue $\xi'$, then a measurement of $\xi$ will certainly give as result the number $\xi'$*. Conversely, *if the system
is in a state such that a measurement of a real dynamical variable $\xi$ is
certain to give one particular result* (instead of giving one or other of
several possible results according to a probability law, as is in general
the case), *then the state is an eigenstate of $\xi$ and the result of the measurement is the eigenvalue of $\xi$ to which this eigenstate belongs*. These assumptions are reasonable on account of the eigenvalues of real linear operators being always real numbers.

Some of the immediate consequences of the assumptions will be noted. If we have two or more eigenstates of a real dynamical variable $\xi$ belonging to the same eigenvalue $\xi'$, then any state formed by superposition of them will also be an eigenstate of $\xi$ belonging to the eigenvalue $\xi'$. We can infer that if we have two or more states for which a measurement of $\xi$ is certain to give the result $\xi'$, then for any state formed by superposition of them a measurement of $\xi$ will still be certain to give the result $\xi'$. This gives us some insight into the physical significance of superposition of states. Again, two eigenstates of $\xi$ belonging to djﬁerent eigenvalues are orthogonal. We can infer that two states for which a measurement of $\xi$ is certain to give two different results are orthogonal. This gives us some insight into the physical significance of orthogonal states.

When we measure a real dynamical variable $\xi$, the disturbance involved in the act of measurement causes a jump in the state of the dynamical system. ‘From physical continuity, if we make a second measurement of the same dynamical variable $\xi$ immediately after the first, the result of the second measurement must be the same as that of the first. Thus after the first measurement has been made, there is no indeterminacy in the result of the second. Hence, after the first measurement has been made, the system is in an eigenstate of the dynamical variable $\xi$, the eigenvalue it belongs to being equal to the result of the first measurement. This conclusion must still hold if the second measurement is not actually made. In this way we see that a measurement always causes the system to jump into an eigenstate of the dynamical variable that is being measured, the eigenvalue this eigenstate belongs to being equal to the result of the measurement.

We can infer that, with the dynamical system in any state, *any result of a measurement of a real dynamical variable is one of its eigenvalues*. Conversely, *every eigenvalue is a possible result of a measure ment of the dynamical variable for some state of the system*, since it is certainly the result if the state is an eigenstate belonging to this eigenvalue. This gives us the physical significance of eigenvalues. The set of eigenvalues of a real dynamical variable are just the possible results of measurements of that dynamical variable and the calculation of eigenvalues is for this reason an important problem.

Another assumption we make connected with the physical interpretation of the theory is that, *if a certain real dynamical variable $\xi$ is measured with the system in a particular state, the states 'into which the system may jump 0n account of the measurement are such that the original state is dependent on them*. Now these states into which the system may jump are all eigenstates of $\xi$, and hence the original state is dependent on eigenstates of $\xi$. But the original state may be any state, so we can conclude that any state is dependent on eigenstates of $\xi$. If we define a complete set of states to be a set such that any state is dependent on them, then our conclusion can be formulated--the eigenstates of $\xi$ form a complete set.

Not every real dynamical variable has sufﬁcient eigenstates to form a complete set. Those Whose eigenstates do not form complete sets are not quantities that can be measured. We obtain in this way a further condition that a dynamical variable has to satisfy in order that it shall be susceptible t0 measurement, in addition t0 the condition that it shall be real. We call a real dynamical variable whose eigenstates form a complete set an observable. Thus any quantity that can be measured is an observable.

The question now presents itself--Can every observable be measured? The answer theoretically is yes. In practice it may he very awkward, or perhaps even beyond the ingenuity of the experimenter, to devise an apparatus which could measure some particular observable, but the theory always allows one to imagine that the measurement can be made.

Let us examine mathematically the condition for a real dynamical variable $\xi$ to be an observable. Its eigenvalues may consist of a (finite or infinite) discrete set of numbers, or alternatively, they may consist of all numbers in a certain range, such as all numbers lying between $a$ and $b$. In the former case, the condition that any state is dependent on eigenstates of $\xi$ is that any ket can be expressed as a sum of eigenkets of $\xi$. In the latter case the condition needs modiﬁcation, since one may have an integral instead
of a sum, i.e. a ket $\ket{P}$ may be expressible as an integral of eigenkets of $\xi$,
\begin{equation}
\ket{P} = \int \ket{\xi'} \operatorname{d}\xi',
\end{equation}
$\ket{\xi'}$ being an eigenket of $\xi$ belonging to the eigenvalue $\xi'$ and the
range of integration being the range of eigenvalues, as such a ket is
dependent on eigenkets of $\xi$. Not every ket dependent on eigenkets
of $\xi$ can be expressed in the form of the right-hand side of (24), since
one of the eigenkets itself cannot, and more generally any sum of
eigenkets cannot. The condition for the eigenstates of $\xi$ to form a
complete set must thus be formulated, that any ket $\ket{P}$ can be
expressed as an integral plus a sum of eigenkets of $\xi$, i.e.
\begin{equation}
\ket{P} = \int \ket{\xi'c}\operatorname{d}\xi' + \sum_r\ket{\xi^rd},
\end{equation}
where the $\ket{\xi'c}$, $\ket{\xi^rd}$ are all eigenkets of $\xi$, the labels $c$ and $d$ being inserted to distinguish them when the eigenvalues $\xi'$ and $\xi^r$ are equal, and where the integral is taken over the whole range of eigenvalues and the sum is taken over any selection of them. If this condition is satisfied in the case when the eigenvalues of $\xi$ consist of a range of numbers, then $\xi$ is an observable.

There is a more general case that sometimes occurs, namely the eigenvalues of $\xi$ may consist of a range of numbers together with a discrete set of numbers lying outside the range. In this case the condition that $\xi$ shall be an observable is still that any ket shall be expressible in the form of the right-hand side of (25), but the sum over $r$ is now a sum over the discrete set of eigenvalues as well as a selection of those in the range.

It is often very diffﬁcult to decide mathematically whether a particular real dynamical variable satisfies the condition for being an observable or not, because the whole problem of ﬁnding eigenvalues and eigenvectors is in general very difﬁcult. However, we may have good reason on experimental grounds for believingth at the dynamical variable can be measured and then we may reasonably assume that it is an observable even though the mathematical proof is missing. This is a thing we shall frequently do during the course of development of the theory, eg. we shall assume the energy of any dynamical system to be always an observable, even though it is beyond the power of presenti-day mathematical analysis to prove it so except in simple cases.

In the special case when the real dynamical variable is a number, every state is an eigenstate and the dynamical variable is obviously an observable. Any measurement of it always gives the same result, so it is just a physical constant, like the charge on an electron. A physical constant in quantum mechanics may thus be looked upon either as an observable with a single eigenvalue or as a mere number appearing in the equations, the two points of view being equivalent.

If the real dynamical variable satisfies an algebraic equation, then the result ($\beta$) of the preceding section shows that the dynamical variable is an observable. Such an observable has a ﬁnite number of eigenvalues. Conversely, any observable with a ﬁnite number of eigenvalues satisfies an algebraic equation, since if the observable $\xi$ has as its eigenvalues $\xi',\xi'',\ldots,\xi^n$, then
$$\left(\xi-\xi'\right) \left(\xi-\xi''\right) \ldots \left(\xi-\xi^n\right) \ket{P} = 0$$
holds for $\ket{P}$ any eigenkets of $\xi$, and thus it holds for any $ket{P}$ whatever, because any ket can be expressed as a sum of eigenkets of $\xi$ on account of $\xi$ being an observable. Hence
\begin{equation}
\left(\xi-\xi'\right) \left(\xi-\xi''\right) \ldots \left(\xi-\xi^n\right) = 0
\end{equation}

As an example we may consider the linear operator $\ket{A}\bra{A}$, where $\ket{A}$ is a normalized ket. This linear operator is real according to (7), and its square is
\begin{equation}
\\{\ket{A}\bra{A}\\}^2 = \ket{A}\braket{A}{A}\bra{A} = \ket{A}\bra{A}
\end{equation}
since $\braket{A}{A} = 1$. Thus its square equals itself and so it satisfies an algebraic equation and is an observable. Its eigenvalues are 1 and 0, with $\ket{A}$ as the eigenket belonging to the eigenvalue 1 and all kets orthogonal to $\ket{A}$ as eigenkets belonging to the eigenvalue 0. A measurement of the observable thus certainly gives the result 1 if the dynamical system is in the state corresponding to $\ket{A}$ and the result 0 if the system is in any orthogonal state, so the observable may be described as the quantity which determines whether the system is in the state $\ket{A}$ or not.

Before concluding this section we should examine the conditions for an integral such as occurs in (24) to be significant. Suppose $\ket{X}$ and $\ket{Y}$ are two kets which can be expressed as integrals of eigenkets of the observable $\xi$,
$$\ket{X} = \int\ket{\xi'x}\operatorname{d}\xi', \ket{Y} = \int \ket{\xi''y}\operatorname{d}\xi''$$
$x$ and $y$ being used as labels to distinguish the two integrands. Then we have, taking the conjugate imaginary of the first equation and multiplying by the second
\begin{equation}
\braket{X}{Y} = \int\int \braket{\xi'x}{\xi''y}\operatorname{d}\xi'\operatorname{d}\xi''.
\end{equation}

Consider now the single integral
\begin{equation}
\int\braket{\xi'x}{\xi''y}\operatorname{d}\xi''.
\end{equation}

From the orthogonality theorem, the integrand here must vanish over the whole range of integration except the one point $\xi'' = \xi'$. If the integrand is finite at this point, the integral (29) vanishes, and if this holds for all $\xi'$, we get from (28) that $\braket{X}{Y}$ vanishes. Now
in general $\braket{X}{Y}$ does not vanish, so in general $\braket{\xi'x}{\xi'y}$ must be infinitely great in such a way as to make (29) non-vanishing and finite. The form of infinity required for this will be discussed in § 15.

In our work up to the present it has been implied that our bra and ket vectors are of finite length and their scalar products are finite. We see now the need for relaxing this condition when we are dealing with eigenvectors of an observable whose eigenvalues form a range. If we did not relax it, the phenomenon of ranges of eigenvalues could not occur and our theory would be too weak for most practical problems.

Taking $\ket{Y} = \ket{X}$ above, we get the result that in general $\braket{\xi'x}{\xi'x}$ is infinitely great. We shall assume that if $\ket{\xi'x} \ne 0$
\begin{equation}
\int \braket{\xi'x}{\xi''x}\operatorname{d}\xi'' \gt 0,
\end{equation}
as the axiom corresponding to (8) of §6 for vectors of infinite length.

The space of bra or ket vectors when the vectors are restricted to be of finite length and to have finite scalar products is called by mathematicians a *Hilbert space*. The bra and ket vectors that we now use form a more general space than a Hilbert space.

We can now see that the expansion of a ket $ket{P}$ in the form of the right-hand side of (25) is unique, provided there are not two or more terms in the sum referring to the same eigenvalue. To prove this result, let us suppose that two different expansions of $ket{P}$ are possible. Then by subtracting one from the other, we get an equation of the form
\begin{equation}
0 = \int\ket{\xi'a}\operatorname{d}\xi' + \sum_s \ket{\xi^sb},
\end{equation}
$a$ and $b$ being used as new labels for the eigenvectors, and the sum over $s$ including all terms left after the subtraction of one sum from the other. If there is a term in the sum in (31) referring to an eigenvalue $\xi'$ not in the range, we get, by multiplying (31) on the left by $\bra{\xi'b}$ and using the orthogonality theorem,
$$0 = \braket{\xi'b}{\xi'b},$$

which contradicts (8) of § 6. Again, if the integrand in (31) does not
vanish for some eigenvalue $\xi''$ not equal to any $\xi^s$ occurring in the
sum, we get, by multiplying (31) on the left by $\bra{\xi''a}$ and using the
orthogonality theorem,
$$0 = \int \braket{\xi''a}{\xi'a}\operatorname{d}\xi',$$
which contradicts (30). Finally, if there is a term in the sum in (31)
referring to an eigenvalue $\xi'$ in the range, we get, multiplying (31) on
the left by $\bra{\xi'b}$,
\begin{equation}
0 = \int \braket{\xi'b}{\xi'a}\operatorname{d}\xi' + \braket{\xi'b}{\xi'b}
\end{equation}
and multiplying (31) on the left by $\bra{\xi'a}$
\begin{equation}
0 = \int \braket{\xi'a}{\xi'a}\operatorname{d}\xi' + \braket{\xi'a}{\xi'b}.
\end{equation}

Now the integral in (33) is finite, so $\braket{\xi'a}{\xi'b}$ is finite and $\braket{\xi'b}{\xi'a}$ is ﬁnite. The integral in (32) must then be zero, so $\braket{\xi'b}{\xi'b}$ is zero and we again have a contradiction. Thus every term in (31) must vanish and the expansion of a ket $\ket{P}$ in the form of the right-hand side of (25) must be unique.

#11. Functions of observables

Let $\xi$ be an observable. We can multiply it by any real number $k$ and get another observable $k\xi$. In order that our theory may be self-consistent it is necessary that, when the system is in a state such that a measurement of the observable $\xi$ certainly gives the result $\xi$, a measurement of the observable k5 shall certainly give the result $k\xi'$. It is easily verified that this condition is fulfilled. The ket corresponding to a state for which a measurement of E certainly gives the result $\xi'$ is an eigenket of $\xi$, $\ket{\xi'}$ say, satisfying
$$\xi\ket{\xi'} = \xi'\ket{\xi'}$$
This equation leads to
$$k\xi\ket{\xi'} = k\xi'\ket{\xi'}$$
showing that $\ket{\xi'}$ is an eigenket of $k\xi$ belonging to the eigenvalue $k\xi'$, and thus that a measurement of $k\xi$ will certainly give the result $k\xi'$.

More generally, we may take any real function of $\xi$, $f\left(\xi\right)$ say, and consider it as a new observable wzvhich is automatically measured
whenever $\xi$ is measured, since an experimental determination of the value of $\xi$ also provides the value of $f\left(\xi\right)$. We need not restrict $f\left(\xi\right)$ to be real, and then its real and pure imaginary parts are two observables which are automatically measured when $\xi$ is measured. For the theory to be consistent it is necessary that, when the system is in a state such that a measurement of $\xi$ certainly gives the result $\xi'$, a measurement of the real and pure imaginary parts of $f\left(\xi\right)$ shall certainly give for results the real and pure imaginary parts of $f\left(\xi'\right)$. In the case when $f\left(\xi\right)$ is expressible as a power series
$$f\left(\xi\right) = c_0 + c_1\xi + c_2\xi^2 + c_3\xi^3 + \ldots,$$
the c's being numbers, this condition can again be verified by elementary algebra. In the case of more general functions $f$ it may not be possible to verify the condition. The condition may then be used to define $f\left(\xi\right)$, which we have not yet defined mathematically. In this way me can get a more general definition of a function of an observable than is provided by power series.

We define $f\left(\xi\right)$ in general to be that linear operator which satisfies
\begin{equation}
f\left(\xi\right)\ket{\xi'} = f\left(\xi'\right)\ket{\xi'}
\end{equation}
for every eigenket $\ket{\xi'}$ of $\xi$, $f\left(\xi'\right)$ being a number for each eigenvalue $\xi'$. It is easily seen that this deﬁnition is self-consistent when applied to eigenkets $\ket{\xi'}$ that are not independent. If we have an eigenket $\ket{\xi'A}$ dependent on other eigenkets of $\xi$, these other eigenkets must all belong to the same eigenvalue $\xi'$, otherwise we should have an equation of the type (31), which we have seen is impossible. On multiplying the equation which expresses $\ket{\xi'A}$ linearly in terms of the other eigenkets of $\xi$ by $f\left(\xi\right)$ on the left, me merely multiply each term in it by the number $f\left(\xi'\right)$, so we obviously get a consistent equation. Further, equation (34) is sufficient to define the linear operator $f\left(\xi'\right)$ completely, since to get the result of $f\left(\xi\right)$ multiplied into an arbitrary ket $ket{P}$, we have only to expand $\ket{P}$ in the form of the right-hand side of (25) and take
\begin{equation}
f(\xi)\ket{P} = \int f(\xi')\ket{\xi'c}\operatorname{d}\xi' + \sum_r f(\xi^4)\ket{\xi^rd}.
\end{equation}
The conjugate complex $\overline{f(\xi)}$ of $f(\xi)$ is defined by the conjugate imaginary equation to (34), namely
$$\bra{\xi'}\overline{f(\xi)} = \bar{f}(\xi')\bra{\xi'},$$
holding for any eigenbra $\bra{\xi'}$, $\bar{f}(\xi')$ being the conjugate complex function to $f(\xi')$. Let us replace $\xi'$ here by $\xi''$ and multiply the equation on the right by the arbitrary ket $\ket{P}$. Then we get, using
the expansion (25) for $\ket{P}$,
\begin{equation}
\begin{aligned}
\bra{\xi''}\overline{f(\xi)}\ket{P} & = \bar{f}(\xi'')\braket{\xi''}{P} \\\\
                                    & = \int \bar{f}(\xi'')\braket{\xi''}{\xi'c}\operatorname{d}\xi' + \sum_r \bar{f}(\xi'')\braket{\xi''}{\xi^r d} \\\\
                                    & = \int \bar{f}(\xi'')\braket{\xi''}{\xi'c}\operatorname{d}\xi' + \bar{f}(\xi'')\braket{\xi''}{\xi'' d} \\\\
\end{aligned}
\end{equation}
with the help of the orthogonality theorem, $\braket{\xi''}{\xi''d}$ being understood to be zero if $\xi''$ is not one of the eigenvalues to which the terms
in the sum in (25) refer. Again, putting the conjugate complex function $\bar{f}(\xi')$ for $f(\xi')$ in (35) and multiplying on the left by $\bra{\xi''}$, we get
$$\bra{\xi''}\bar{f}(\xi)\ket{P} = \int \bar{f}(\xi')\braket{\xi'}{\xi'c}\operatorname{d}\xi' + \bar{f}(\xi'')\braket{\xi''}{\xi''d}.$$
The right-hand side here equals that of (36), since the integrands
vanish for $\xi' \ne \xi''$, and hence
$$\bra{\xi''}\overline{f(\xi)}\ket{P} = \bra{\xi''}\bar{f}(\xi)\ket{P}.$$
This holds for $\bra{\xi''}$ any eigenbra and $\ket{P}$ any ket, so
\begin{equation}
\overline{f(\xi)} = \bar{f}(\xi).
\end{equation}

Thus the conjugate complex of the linear operator $f(\xi)$ is the conjugate complex function $\bar{f}$ of $\xi$.

It follows as a corollary that if $f(\xi')$ is a real function of $\xi'$, $f(\xi)$ is a real linear operator. $f(\xi)$ is then also an observable, since its eigenstates form a complete set, every eigenstate of $\xi$ being also an eigenstate of $f(\xi)$.

With the above definition we are able to give a meaning to any function $f$ of an observable, provided only that the domain of existence of the function of a real variable $f(x)$ includes all the eigenvalues of the observable. If the domain of existence contains other points besides these eigenvalues, then the values of $f(x)$ for these other points will not affect the function of the observable. The function need not be analytic or continuous. The eigenvalues of a function f of an observable are just the function f of the eigenvalues of the observable.

It is important to observe that the possibility of defining a function $f$ of an observable requires the existence of a unique number $f(x)$ for each value of X which is an eigenvalue of the observable. Thus the function $f(x)$ must be single-valued. This may be illustrated by considering the question: When we have an observable $f(A)$ which is a real function of the observable $A$, is the observable $A$ a function of the observable $f(A)$)? The answer to this is yes, if different eigenvalues $A'$ of $A$ always lead to different values of $f(A')$. If, however, there exist two different eigenvalues of $A$, $A'$ and $A'$' say, such that $f(A') = f(A'')$, then, corresponding to the eigenvalue $f(A')$ of the observable $f(A)$, there will not be a unique eigenvalue of the observable A and the latter will not be a function of the observable $f(A)$.

It may easily be verified mathematically, from the definition, that the sum or product of two functions of an observable is a function of that observable and that a function of a function of an observable is a function of that observable. Also it is easily seen that the whole theory of functions of an observable is symmetrical between bras and kets and that we could equally well work from the equation
\begin{equation}
\bra{\xi'}f(\xi) = f(\xi')\bra{\xi'}
\end{equation}
instead of from (34).

We shall conclude this section with a discussion of two examples which are of great practical importance, namely the reciprocal and the square root. The reciprocal of an observable exists if the observable does not have the eigenvalue zero. If the observable $\alpha$ does not have the eigenvalue zero, the reciprocal observable, which we call $\alpha^{-1}$ or $1/\alpha$, will satisfy
\begin{equation}
\alpha^{-1}\ket{\alpha'} = \alpha'^{-1}\ket{\alpha'}
\end{equation}

where $\ket{\alpha'}$ is an eigenket of $\alpha$ belonging to the eigenvalue $\alpha'$. Hence
$$\alpha\alpha^{-1}\ket{\alpha'} = \alpha\alpha'^{-1}\ket{\alpha'} = \ket{\alpha'}$$
Since this holds for any eigenket $\ket{\alpha'}$, we must have
\begin{equation}
\alpha\alpha^{-1} = 1
\end{equation}
Similarly,
\begin{equation}
\alpha^{-1}\alpha = 1
\end{equation}

Either of these equations is sufficient to determine $\alpha^{-1}$ completely, provided $\alpha$ does not have the eigenvalue zero. To prove this in the case of (40), let $x$ be any linear operator satisfying the equation
$$\alpha x = 1$$
and multiply both sides on the left by the $\alpha^{-1}$ defined by (39). The result is
$$\alpha^{-1}\alpha x = \alpha^{-1}$$
and hence from (41)
$$ x = \alpha^{-1}$$

Equations (40) and (41) can be used to define the reciprocal, when it exists, of a general linear operator $\alpha$, which need not even be real. One of these equations by itself is then not necessarily sufficient. If any two linear operators $\alpha$ and $\beta$ have reciprocals, their product $\alpha\beta$ has the reciprocal
\begin{equation}
\left(\alpha\beta\right)^{-1} = \beta^{-1}\alpha^{-1}
\end{equation}
obtained by taking the reciprocal of each factor and reversing their order. We verify (42) by noting that its right-hand side gives unity when multiplied by a5, either on the right or on the left. This reciprocal law for products can be immediately extended to more than two factors, i.e.,
$$\left(\alpha\beta\gamma\ldots\right)^{-1} = \ldots\gamma^{-1}\beta^{-1}\alpha^{-1}.$$

The square root of an observable on always exists, and is real if $\alpha$ has no negative eigenvnlues. We write it $\sqrt{\alpha}$ or $\alpha^{\frac12}$. It satisfies
\begin{equation}
\sqrt{\alpha}\ket{\alpha'} = \pm \sqrt{\alpha'}\ket{\alpha'},
\end{equation}

$\ket{\alpha'}$ being an eigenket of $\alpha$ belonging to the eigenvalue $\alpha$. Hence
$$\sqrt{\alpha}\sqrt{\alpha}\ket{\alpha'} = \sqrt{\alpha'}\sqrt{\alpha'}\ket{\alpha'} = \alpha'\ket{\alpha'} = \alpha\ket{\alpha'},$$
and since this holds for any eigenket $\ket{\alpha'}$ we must have
\begin{equation}
\sqrt{\alpha}\sqrt{\alpha} = \alpha
\end{equation}

On account of the ambiguity of sign in (43) there will be several square roots. To fix one of them me must specify a particular sign in (43) for each eigenvalue. This sign may vary irregularly from one eigenvalue to the next and equation (43) will always define a linear operator $\sqrt{\alpha}$ satisfying (44) and forming a square-root function of $\alpha$. If there is an eigenvalue of o: with two or more independent eigenkets belonging to it, then we must, according to our definition of a function, have the same sign in (43) for each of these eigenkets. If we took different signs,however, equation (44)would still hold, and hence equation (44) by itself is not sufficient to define $\sqrt{\alpha}$, except in the special case when there is only one independent eigenket of $\alpha$. belonging to any eigenvalue.

The number of different square roots of an observable is $2^n$, where $n$ is the total number of eigenvalues not zero. In practice the square-root function is used only for observables without negative eigenvalues and the particular square root that is useful is the one for which the positive sign is always taken in (43). This one will be called the *positive square root*.

#12. The general physical interpretation

The assumptions that me made at the beginning of § 10 to get a physical interpretation of the mathematical theory are of a rather special kind, since they can be used only in connexion with eigenstates. We need some more general assumption which will enable us to extract physical information from the mathematics even when me are not dealing with eigenstates.

In classical mechanics an observable always, as we say, 'has a value' for any particular state of the system. What is there in quantum mechanics corresponding to this? If we take any observable $\xi$ and any two states $x$ and $y$, corresponding to the vectors $\bra{x}\xi\ket{y}$, then we can form the number $\bra{x}\xi\ket{y}$. This number is not very closely analogous to the value which an observable can 'have' in the classical theory, for three reasons, namely, (i) it refers to two states of the system, while the classical value always refers to one, (ii) it is in general not a real number, and (iii) it is not uniquely determined by the observable and the states, since the vectors $\bra{x}$ and $\ket{y}$ contain arbitrary numerical factors. Even if we impose on $\bra{x}$ and $\ket{y}$ the condition that they shall be normalized, there will still be an undetermined factor of modulus unity in $\bra{x}\xi\ket{y}$. These three reasons cease to apply, however, if we take the two states to be identical and $\ket{y}$to be the conjugate imaginary vector to $\bra{x}$. The number that we then get, namely $\bra{x}\xi\ket{x}$, is necessarily real, and also it is uniquely determined when $\bra{x}$ is normalized, since if we multiply $\bra{x}$ by the numerical factor $e^{ic}$, $c$ being some real number, we must multiply $\ket{x}$ by $e^{-ic}$ and $\bra{x}\xi\ket{x}$ will be unaltered.

One might thus be inclined to make the tentative assumption that the observable $\xi'$ has the value $\bra{x}\xi\ket{x}$ for the state $x$, in a sense analogous to the classical sense. This would not be satisfactory, though, for the following reason. Let us take a second observable $\eta$, which would have by the above assumption the value $\bra{x}\eta\ket{x}$ for this same state. We should then expect, from classical analogy, that for this state the sum of the two observables would have a value equal to the sum of the values of the two observables separately and the product of the two observables would have a value equal to the product of the values of the two observables separately. Actually, the tentative assumption would give for the sum of the two observables the value $\bra{x}\xi + \eta \ket{x}$, which is, in fact, equal to the sum of $\bra{x}\xi\ket{x}$ and $\bra{x}\eta\ket{x}$, but for the product it would give the value $\bra{x}\xi\eta\ket{x}$ or $\bra{x}\eta\xi\ket{x}$, neither of which is connected in any simple way with $\bra{x}\xi\ket{x}$ and $\bra{x}\eta\ket{x}$.

However, since things go wrong only with the product and not with the sum, it would be reasonable to call $\bra{x}\xi\ket{x}$ the *average* value of the observable $\xi$ for the state $x$. This is because the average of the sum of two quantities must equal the sum of their averages, but the average of their product need not equal the product of their averages. We therefore make the general assumption that *if the measurement of the observable $\xi$ for the system in the state corresponding to $\ket{x}$ is made a large number of times, the average of all the results obtained will be $\bra{x}\xi\ket{x}$, provided $\ket{x}$ is normalized*. If $\ket{x}$ is not normalized, as is necessarily the case if the state $x$ is an eigenstate of some observable belonging to an eigenvalue in a range, the assumption becomes that the average result of a measurement of $\xi$ is proportional to $\bra{x}\xi\ket{x}$. This general assumption provides a basis for a general physical interpretation of the theory.

The expression that an observable 'has a particular value' for a particular state is permissible in quantum mechanics in the special case when a measurement of the observable is certain to lead to the particular value, so that the state is an eigenstate of the observable.

It may easily be verified from the algebra that, with this restricted meaning for an observable 'having a value', if two observables have values for a particular state, then for this state the sum of the two observables (if this sum is an observable?) has a value equal to the sum of the values of the two observables separately and the product of the two bbservables (if this product is an observable) has a value equal to the product of the values of the two observables separately.

In the general case we cannot speak of an observable having a value for a particular state, but we can speak of its having an average value for the state.\*We can go further and speak of the probability of its having any speciﬁed value for the state, meaning the probability of this speciﬁed value being obtained when one makes a measurement of the observable. This probability can be obtained from the general assumption in the following way.

Let the observable be $\xi$ and let the state correspond to the normalized ket $\ket{x}$. Then the general assumption tells us, not only that the average value of $\xi$ is $\bra{x}\xi\ket{x}$, but also that the average value of any function of $\xi$, $f(\xi)$ say, is $\bra{x}f(\xi)\ket{x}$. Take $f(\xi)$ to be that function of $\xi$ which is equal to unity when $\xi = a$, $a$ being some real number, and zero otherwise. This function of $\xi$ has a meaning according to our general theory of functions of an observable, and it may be denoted by $\delta\_{\xi a}$ in conformity with the general notation of the symbol $\xi$ with two suﬁxes given on p. 62 (equation (17)). The average value of this function of $\xi$ is just the probability, $P_a$ say, of $\xi$ having the value $a$. Thus
\begin{equation}
P_a = \bra{x} \delta\_{\xi a} \ket{x}.
\end{equation}

If $a$ is not an eigenvalue of $\xi$, $\delta\_{\xi a}$ multiplied into any eigenket of $\xi$ is zero, and hence $\delta\_{\xi a} = 0$ and $P_a = 0$. This agrees with a conclusion of § 10, that any result of a measurement of an observable must be one of its eigenvalues.

If the possible results of a measurement of $\xi$ form a range of numbers, the probability of $\xi$ having exactly a particular value will be zero in most physical problems. The quantity of physical importance is then the probability of $\xi$ having a value within a small range, say from $a$ to $a+da$. This probability, which we may call $P(a) da$, is

$\dagger$ This is not obviously so, since the sum may not have sufficient eigenstates to form a complete set, in which case the sum, considered as a single quantity, would not be measurable.
$\ddagger$ Here the reality condition may fail, as well as the condition for the eigenstates to form a complete set.

equal to the average value of that function of $\xi$ which is equal to
unity for $\xi$ lying within the range $a$ to $a+da$ and zero otherwise.
This function of $\xi$ has a meaning according to our general theory of
functions of an observable. Denoting it by $\chi(\xi)$, we have
\begin{equation}
P(a)da = \bra{x}\chi(\xi)\ket{x}
\end{equation}

If the range $a$ to $a+da$ does not include any eigenvalues of $\xi$, we have as above $\chi(\xi) = 0$ and $P(a) = 0$. If $\ket{x}$ is not normalized, the right-hand sides of (45) and (46) will still be proportional to the probability of $\xi$ having the value $a$ and lying within the range $a$ to $a+da$ respectively.

The assumption of § 10, that a measurement of $\xi$ is certain to give
the result $\xi'$ if the system is in an eigenstate of $\xi$ belonging to the
eigenvalue $\xi'$, is consistent with the general assumption for physical
interpretation and can in fact be deduced from it. Working from the
general assumption we see that, if $\ket{\xi'}$ is an eigenket of $\xi$ belonging to the eigenvalue $\xi'$, then, in the case of discrete eigenvalues of $\xi$,
$$\delta\_{\xi a} \ket{\xi'} = 0 \,\, \mathrm{unless} \,\, a = \xi', $$
and in the case of a range of eigenvalues of $\xi$
$$\chi(\xi)\ket{\xi'} = 0 \,\, unless\,the\,range\,a\,to\,a+da\,includes\,\xi'.$$
In either case, for the state corresponding to $\ket{F}$, the probability of $\xi$ having any value other than $\xi'$ is zero.

An eigenstate of $\xi$ belonging to an eigenvalue $\xi'$ lying in a range is a state which cannot strictly be realized in practice, since it would need an inﬁnite amount of precision to get $\xi$ to equal exactly $\xi'$. The most that could be attained in practice would be to get $\xi$ to lie within a narrow range about the value $\xi'$. The systam would then be in a state approximating to an eigenstate of $\xi$. Thus an eigenstate belonging to an eigenvalue in a range is a mathematical idealization of what can be attained in practice. All the same such eigenstates play a very useful role in the theory and one could not very well do without them. Science contains many examples of theoretical concepts which are limits of things met with in practice and are useful for the precise formulation of laws of nature, although they are not realizable experimentally, and this is just one more of them. It may be that the infinite length of the ket vectors corresponding to these eigenstates is connected with their unrealizability, and that all realizable states correspond to ket vectors that can be normalized and that form a Hilbert space.

#13. Commutability and compatibility

A state may be simultaneously an eigenstate of two observables.
If the state corresponds to the ket vector $\ket{A}$ and the observables are
$\xi$ and $\eta$, we should then have the equations
$$\xi\ket{A} = \xi'\ket{A}$$
$$\eta\ket{A} = \eta'\ket{A}$$

Where $\xi'$ and $\eta'$ are eigenvalues of $\xi$ and $\eta$ respectively. We can now deduce
$$\xi\eta\ket{A} = \xi\eta'\ket{A} = \xi'\eta'\ket{A} = \eta\xi'\ket{A} = \eta\xi\ket{A},$$
or
$$\left(\xi\eta - \eta\xi\right)\ket{A} = 0.$$

This suggests that the chances for the existence of a simultaneous eigenstate are most favourable if $\xi\eta - \eta\xi = 0$ and the two observables commute. If they do not commute a simultaneous eigenstate is not impossible, but is rather exceptional. On the other hand, *if they do commute there exist so many simultaneous eigenstates that they form a complete set*, as will now be proved.

Let $\xi$ and $\eta$ be two commuting observables. Take an eigenket of $\eta$, $\ket{\eta'}$ say, belonging to the eigenvalue $\eta'$, and expand it in terms of eigenkets of f in the form of the right-hand side of (25), thus
\begin{equation}
\ket{\eta'} = \int \ket{\xi' \eta' c} \operatorname{d}\xi' + \sum_r \ket{\xi^r \eta' d}.
\end{equation}

The eigenkets of $\xi$ on the right-hand side here have $\eta'$ inserted in them as an extra label, in order to remind us that they come ﬁom the expansion of a special ket vector, namely $\eta'$, and not a general one as in equation (25). We can now show that each of these eigenkets of $\xi$ is also an eigenket of $\eta$ belonging to the eigenvalue $\eta'$. We have
\begin{align}
0 = \left(\eta -\eta'\right)\ket{\eta'} = \int \left(\eta -\eta'\right)\ket{\xi'\eta'c}\operatorname{d}\xi' + \sum_r \left(\eta - \eta'\right)\ket{\xi^r\eta'd}.
\end{align}

Now the ket $\left(\eta-\eta'\right)\ket{\xi^r\eta'd}$ satisfies
\begin{aligned}
\xi\left(\eta-\eta'\right)\ket{\xi^r\eta'd} = \left(\eta-\eta'\right)\xi\ket{\xi^r\eta'd} &= \left(\eta -\eta'\right) \xi^r\ket{\xi^r\eta'd} \\\\
            &= \xi^r\left(\eta - \eta'\right)\ket{\xi^r\eta'd},
\end{aligned}
showing that it is an eigenket of $\xi$ belonging to the eigenvalue $\xi^r$, and similarly the ket $\left(\eta - \eta'\right)\ket{\xi'\eta'c}$ is an eigenket of $\xi$ belonging to the eigenvalue $\xi'$. Equation (48) thus gives an integral plus a sum of eigenkets of $\xi$ equal to zero, which, as we have seen with equation (31), is impossible unless the integrand and every term in the sum
vanishes. Hence
$$\left(\eta -\eta'\right)\ket{\xi'\eta'c} = 0, \, \left(\eta - \eta'\right)\ket{\xi^r\eta'd} = 0,$$
so that all the kets appearing on the right-hand side of (47) are
eigenkets of $\eta$ as well as of $\xi$. Equation (47) now gives $\ket{\eta'}$ expanded in terms of simultaneous eigenkets of $\xi$ and $\eta$. Since any ket can be expanded in terms of eigenkets $\ket{\eta'}$ of $\eta$, it .follows that any ket can be expanded in terms of simultaneous eigenkets of $\xi$ and $\eta$, and thus the simultaneous eigenstates form a complete set.

The above simultaneous eigenkets of $\xi$ and $\eta$, $\ket{\xi'\eta'c}$ and $\ket{\xi^r\eta'd}$, are labelled by the eigenvalues $\xi'$ and $\eta'$, or $\xi^r$ and $\eta'$, to which they belong, together with the labels $c$ and $d$ which may also be necessary. The procedure of using eigenvalues as labels for simultaneous eigenvectors will be generally followed in the future, just as it has been followed in the past for eigenvectors of single observables.

The converse to the above theorem says that, *if $\xi$ and $\eta$ are two observables such that their simultaneous eigenstates form a complete set, then $\xi$ and $\eta$ commute*. To prove this, we note that, if $\ket{\xi'\eta'}$ is a simultaneous eigenket belonging to the eigenvalues $\xi'$ and $\eta'$,
\begin{equation}
\left(\xi\eta-\eta\xi\right)\ket{\xi'\eta'} = \left(\xi'\eta'-\eta'\xi'\right)\ket{\xi'\eta'} = 0.
\end{equation}
Since the simultaneous eigenstates form a complete set, an arbitrary ket $\ket{P}$ can be expanded in terms of simultaneous eigenkets $\ket{\xi'\eta'}$, for each of which (49) holds, and hence
$$\left(\xi\eta-\eta\xi\right)\ket{P} = 0$$
and so
$$\xi\eta-\eta\xi = 0$$

The idea of simultaneous eigenstates may be extended to more than two observables and the above theorem and its converse still hold, i.e. if any set of observables commute, each with all the others, their simultaneous eigenstates form a complete set, and conversely. The same arguments used for the proof with two observables are adequate for the general case; e.g., if we have three commuting observables $\xi$, $\eta$, $\zeta$, we can expand any simultaneous eigenket of $\xi$ and $\eta$ in terms of eigenkets of $\zeta$ and then show that each of these eigenkets of $\zeta$ is also an eigenket of $\xi$ and of $\eta$. Thus the simultaneous eigenket of $\xi$ and $\eta$ is expanded in terms of simultaneous eigenkets of $\xi$, $\eta$, and $\zeta$, and since any ket can be expanded in terms of simultaneous eigenkets of $\xi$ and $\eta$, it can also be expanded in terms of simultaneous eigenkets of $\xi$, $\eta$, and $\zeta$.

The orthogonality theorem applied to simultaneous eigenkets tells us that two simultaneous eigenvectors of a set of commuting observables are orthogonal if the sets of eigenvalues to which they belong differ in any way.

Owing to the simultaneous eigenstates of two or more commuting observables forming a complete set, we can set up a theory of functions of two or more commuting observables on the same lines as the theory of functions of a single observable given in § 11. If $\xi$, $\eta$, $\zeta$, $\ldots$ are commuting observables, we define a general function $f$ of them to be that linear operator $f(\xi,\eta,\zeta,\ldots)$ which satisfies
\begin{equation}
f(\xi,\eta,\zeta,\ldots)\ket{\xi'\eta'\zeta'\ldots} = f(\xi',\eta',\zeta',\ldots)\ket{\xi'\eta'\zeta'\ldots},
\end{equation}
where $\ket{\xi'\eta'\zeta'\ldots}$ is any simultaneous eigenket of $\xi$, $\eta$, $\zeta$, $\ldots$ belonging to the eigenvalues $\xi'$, $\eta'$, $\zeta'$, $\ldots$. Here $f$ is any function such that $f(a,b,c,\ldots)$ is deﬁned for all values of $a,b,c,\ldots$ which are eigenvalues of $\xi, \eta, \zeta, \ldots$ respectively. As with a function of a single observable defined by (34), we can show that $f(\xi,\eta,\zeta,\ldots)$ is completely determined by (50), that
$$\overline{f(\xi,\eta,\zeta,\ldots)} = \bar{f}(\xi,\eta,\zeta,\ldots),$$
corresponding to (37), and that if $f(a, b, c,\ldots)$ is a real function, $f(\xi,\eta,\zeta,\ldots)$ is real and is an observable.

We can now proceed to generalize the results (45) and (46). Given a set of commuting observables $\xi,\eta,\zeta,\ldots$ we may form that function of them which is equal to unity when $\xi=a,\eta=b\zeta=c,\ldots, a,b,c,\ldots$ being real numbers, and is equal to zero when any of these conditions is not fulfilled. This function may be written $\delta\_{\xi a}\delta\_{\eta b}\delta\_{\zeta c}$ and is in fact just the product in any order of the factors $\delta\_{\xi a},\delta\_{\eta b},\delta\_{\zeta c}$ defined as functions of single observables, as may be seen by substituting this product for $f(\xi,\eta,\zeta,\ldots)$ in the left-hand side of (50). The average value of this function for any state is the probability, $P\_{abc\ldots}$ say, of $\xi,\eta,\zeta,\ldots$ having the values $a, b, c,\ldots$ respectively for that state. Thus if the state corresponds to the normalized ket vector $\ket{x}$, we get from our general assumption for physical interpretation
\begin{equation}
P\_{abc\ldots} = \bra{x}\delta\_{\xi a}\delta\_{\eta b}\delta\_{\zeta c}\ldots\ket{x}.
\end{equation}

$P\_{abc\ldots}$ is zero unless each of the numbers $a,b,c,\ldots$ is an eigenvalue of the corresponding observable. If any of the numbers $a,b,c,\ldots$ is an eigenvalue in a range of eigenvalues of the corresponding observable, $P\_{abc\ldots}$ will usually again be zero, but in this case we ought to replace the requirement that this observable shall have exactly one value by the requirement that it shall have a value lying within a small range, which involves replacing one of the $\delta$ factors in (51) by a factor like the $\chi(\xi)$ of equation (46). On carrying out such a replacement for each of the observables $\xi,\eta,\zeta,\ldots$ whose corresponding numerical value $a, b, c,\ldots$ lies in a range of eigenvalues, we shall get a probability which does not in general vanish.

If certain observables commute, there exist states for which they all have particular values, in the sense explained at the bottom of p. 46, namely the simultaneous eigenstates. Thus *one can give a meaning to several commuting observables having values at the same time*. Further, we see from (51) that for any state *one can give a meaning to the probability of particular results being obtained for simultaneous measurements of several commuting observables*. This conclusion is an important new development. In general one cannot make an observation on a system in a deﬁnite state without disturbing that state and spoiling it for the purposes of a second observation. One cannot then give any meaning to the two observations being made simultaneously. The above conclusion tells us, though, that in the special case when the two observables commute, the observations are to be considered as non-interfering or *compatible*, in such a xvay that one can give a meaning to the two observations being made simultaneously and can discuss the probability of any particular results being obtained. The two observations may, in fact, be considered as a single observation of a more complicated type, the result of which is expressible by two numbers instead of a single number. *Front the point of view of general theory, any two or more commuting observables may be counted as a single observable, the result of a measurement of which consists of two or more numbers*. The states for which this measurement is certain to lead to one particular result arefthe simultaneous eigenstates.
