```
\documentclass[12pt]{article}
\usepackage[a4paper,margin=2.5cm]{geometry}
\usepackage{amsmath,amssymb,physics}
\usepackage{bm}
\usepackage{setspace}
\usepackage{enumitem}

\setstretch{1.3}

\begin{document}

\begin{center}
{\Large \textbf{Advanced Quantum Mechanics}}[0.3em]
{\Large \textbf{Final Mock Examination (Latest Version)}}[0.5em]
\textbf{Time: 2 Hours \quad Total: 100 Points}
\end{center}

\vspace{1em}

\noindent\textbf{Instructions:}
\begin{itemize}
\item Unless otherwise stated, set $\hbar = 1$.
\item All operators act on appropriate Hilbert spaces.
\item Show clear logical steps for derivation-type questions.
\end{itemize}

\vspace{1.5em}

%====================
\section*{Problem 3 (25 points) --- Angular Momentum, Lie Algebra and Representations}

Let the quantum angular momentum operators
[
\bm{J} = (J_x, J_y, J_z)
]

satisfy the standard commutation relations
[
[J_i, J_j] = i,\varepsilon_{ijk} J_k.
]

\subsection*{(a) Lie algebra structure \hfill (8 points)}

Show that the operator set ${J_x, J_y, J_z}$ forms a three-dimensional real Lie algebra under the commutator. Write down its structure constants explicitly, and explain the relation between this Lie algebra and $\mathfrak{su}(2)$.

\subsection*{(b) Representation and irreducibility \hfill (8 points)}

Let $V$ be a finite-dimensional representation space of $\mathfrak{su}(2)$, and define
[
J^2 = J_x^2 + J_y^2 + J_z^2.
]

\begin{enumerate}[label=(\roman*)]
\item Explain why $J^2$ must act as a scalar operator on an irreducible representation.
\item Prove that there exists a state $\ket{j,m_{\max}}$ such that
[
J_+\ket{j,m_{\max}} = 0.
]
\end{enumerate}

\subsection*{(c) Group-theoretic origin of spin (Conceptual) \hfill (9 points)}

From the perspective of Lie groups and Lie algebras, answer the following:

\begin{enumerate}[label=(\roman*)]
\item Why must spin degrees of freedom in quantum mechanics be described by $SU(2)$ rather than $SO(3)$?
\item How does half-integer spin (e.g. $j = \tfrac12$) arise at the level of group representations?
\item Explain the physical meaning of the statement that $SU(2)$ is a double cover of $SO(3)$.
\end{enumerate}

%====================
\section*{Problem 4 (20 points) --- Generators, Exponential Map and Rotations}

Define the quantum rotation operator
[
U(\bm{n},\theta) = \exp\big(-i\theta, \bm{n}\cdot \bm{J}\big),
]

where $\bm{n}$ is a unit vector.

\subsection*{(a) Rotation of vector operators \hfill (10 points)}

Using the Baker--Campbell--Hausdorff formula, show that for any vector operator $\bm{A}$ satisfying the same rotational commutation relations as $\bm{J}$,
[
U^{\dagger}(\bm{n},\theta),(\bm{A}\cdot \bm{a}),U(\bm{n},\theta)
= \bm{A}\cdot \big(R(\bm{n},\theta)\bm{a}\big),
]

where $R(\bm{n},\theta)$ is the classical $3\times 3$ rotation matrix.

\subsection*{(b) Conceptual question \hfill (10 points)}

Explain why quantum rotations are implemented through the exponential map
[
\exp(-i\theta J_i)
]
rather than finite matrices directly. Discuss the connection with the Lie group--Lie algebra correspondence.

%====================
\section*{Problem 5 (15 points) --- Angular Momentum Coupling}

Consider two systems with angular momenta $j_1$ and $j_2$, represented on $V_{j_1}$ and $V_{j_2}$.

\subsection*{(a) Total angular momentum \hfill (8 points)}

Explain why the total angular momentum operator on the tensor product space
[
V_{j_1} \otimes V_{j_2}
]
is given by
[
\bm{J} = \bm{J}^{(1)} \otimes I + I \otimes \bm{J}^{(2)}.
]

\subsection*{(b) Clebsch--Gordan decomposition \hfill (7 points)}

From the viewpoint of representation theory, explain the physical and mathematical meaning of the decomposition
[
V_{j_1} \otimes V_{j_2} = \bigoplus_{j = |j_1 - j_2|}^{j_1 + j_2} V_j.
]

Explicit computation of Clebsch--Gordan coefficients is \emph{not} required.

%====================
\section*{Problem 6 (15 points) --- Conceptual Synthesis}

Answer briefly (about equal length for each part):

\begin{enumerate}[label=(\roman*)]
\item Why can the angular momentum commutation relations be regarded as defining a Lie algebra rather than merely operator identities?
\item What is the relation between eigenvalues of observables and weights in representation theory?
\item Why can the same Lie algebra (e.g. $\mathfrak{su}(2)$) describe different physical systems?
\end{enumerate}

\end{document}
```
