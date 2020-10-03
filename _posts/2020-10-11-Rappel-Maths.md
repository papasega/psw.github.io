---
layout: post
title: Rappel Mathématique -- Algébre lineaire 
subtitle: Algébre Linéaire  
bigimg: img/posts/Websites_Redesign_Backgrounds_DT_Robotics1_2018.jpg
share-img: img/ML_intro.png
tags: [IA, maths, algébre, PSW]
comments: true
---



## Notations générales

### Définitions 


#### Vecteur 
On note  <img src="https://latex.codecogs.com/svg.latex?\Large&space; x\in\mathbb{R}^{n} " title=" x\in\mathbb{R}^{n} " /> un vecteur à n entrées, où <img src="https://latex.codecogs.com/svg.latex?\Large&space; x_i " title=" x_i "/> est la <img src="https://latex.codecogs.com/svg.latex?\Large&space; i^{eme} " title=" i^{ieme} " /> :  

<img src="https://latex.codecogs.com/svg.latex?\Large&space; X " title=" X " /> = 
<img src="https://latex.codecogs.com/svg.latex?\Large&space; \left (
   \begin{array}{ccc}
      x_1 \\
      x_2 \\
      ... \\
      x_n \\
   \end{array}
   \right ) " title=" \left (
   \begin{array}{ccc}
      x_1 \\
      x_2 \\
       \vdots \\
      x_n \\
   \end{array}
   \right ) " /> <img src="https://latex.codecogs.com/svg.latex?\Large&space; \in \mathbb{R}^{n}" title=" \in \mathbb{R}^{n}" />
   
#### Matrice
On note  <img src="https://latex.codecogs.com/svg.latex?\Large&space; M \in\mathbb{R}^{m} \times \mathbb{R}^{n}" title=" M \in\mathbb{R}^{m} \times \mathbb{R}^{n}" /> une matrice à  <img src="https://latex.codecogs.com/svg.latex?\Large&space;m" title="m" /> lignes et  <img src="https://latex.codecogs.com/svg.latex?\Large&space; n" title="n" /> colonnes, où  <img src="https://latex.codecogs.com/svg.latex?\Large&space; M_{i,j} \in \mathbb{R}" title="M_{i,j} \in \mathbb{R}" /> est l'entrée située à la <img src="https://latex.codecogs.com/svg.latex?\Large&space; i^{ieme}" title="i^{ieme}" /> ligne et <img src="https://latex.codecogs.com/svg.latex?\Large&space; j^{ieme}" title="j^{ieme}" /> colonne :

<img src="https://latex.codecogs.com/svg.latex?\Large&space; M = \left (
      \begin{array}{cccc}
      M_{1,1}  & \cdots & M_{1,n} \\
      \vdots & & \vdots \\
      M_{m,1} & \cdots  & M_{m,n} \\
      \end{array}
    \right )  " title="M = \left (
     \begin{array}{cccc}
      M_{1,1}  & \cdots & M_{1,n} \\
      \vdots & & \vdots \\
      M_{m,1} & \cdots  & M_{m,n} \\
        \end{array}
         \right )  " /> <img src="https://latex.codecogs.com/svg.latex?\Large&space; \in \mathbb{R}^{m \times n} " title="\in \mathbb{R}^{m \times n} " />
       
 Remarque: le vecteur <img src="https://latex.codecogs.com/svg.latex?\Large&space; X " title=" X " /> défini ci-dessus peut être vu comme une matrice de taille <img src="https://latex.codecogs.com/svg.latex?\Large&space; n \times 1 " title=" n \times 1 " />, aussi appelé vecteur colonne. 
 
## Matrices particulières
#### Matrice identité 
 La matrice <img src="https://latex.codecogs.com/svg.latex?\Large&space; I \in \mathbb{R}^{n \times n}" title=" I \in \mathbb{R}^{n \times n} " /> est une matrice carrée n lignes et n colonnes. Tous les éléments de sa diagonale sont égaux à 1 et tous les autres éléments sont égaux à 0. 
 
 <img src="https://latex.codecogs.com/svg.latex?\Large&space;  I = \begin{pmatrix}
    1    & \cdots & 0 \\ 
    \vdots & \ddots & \vdots \\ 
    0      & \cdots & 1 
\end{pmatrix}" title="  I = \begin{pmatrix}
    1    & \cdots & 0 \\ 
    \vdots & \ddots & \vdots \\ 
    0      & \cdots & 1 
\end{pmatrix} " />

Remarquons pour toute matrice <img src="https://latex.codecogs.com/svg.latex?\Large&space; A \in \mathbb{R}^{n \times n}" title=" I \in \mathbb{R}^{n \times n} " />,  on a <img src="https://latex.codecogs.com/svg.latex?\Large&space; A \times I" title=" A \times I " /> = <img src="https://latex.codecogs.com/svg.latex?\Large&space; I \times A" title=" I \times A " /> = <img src="https://latex.codecogs.com/svg.latex?\Large&space; A " title=" A " />. On peut le consider comme l'élément neutre de la multiplication. 

#### Matrice diagonale
Une matrice diagonale <img src="https://latex.codecogs.com/svg.latex?\Large&space; D \in \mathbb{R}^{n \times n}" title=" D \in \mathbb{R}^{n \times n} " /> est une matrice carrée dont les coefficients en dehors de la **diagonale** principale sont nuls. 

<img src="https://latex.codecogs.com/svg.latex?\Large&space; D = \begin{pmatrix}
    a & 0 & \dots & 0 \\
    0 & 1 & \dots & 0 \\
    \vdots & \vdots & \ddots & \vdots \\
    0 & 0 & \dots & 1
  \end{matrix}" title=" D= \begin{matrix}
    a & 0 & \dots & 0 \\
    0 & 1 & \dots & 0 \\
    \vdots & \vdots & \ddots & \vdots \\
    0 & 0 & \dots & 1
  \end{matrix} " />


## Opérations matricielles 

     coming soooo