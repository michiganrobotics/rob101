# Robotics 101: Computational Linear Algebra

Computational Linear Algebra is a pilot first-semester, first-year undergraduate course that shows how mathematics and computation are unified for reasoning about data and making discoveries about the world.

This course ran in Fall 2020 at the University of Michigan Robotics Institute.

Engineering math education is stuck in the Sputnik era: we force students to do four semesters of calculus before they can do anything interesting in engineering. ROB 101 seeks to break through with new ideas. Students will see how engineers are using mathematics and computing to solve large and important problems. Students will still do drill problems to firm up concepts with teeny tiny problems with two or three variables, but they will also solve problems in the Julia programming language with hundreds of variables.

Students will have a palpable understanding that computation and mathematics are friends, instead of hoops to be jumped through on the way to a degree.

## Lecture videos
All lecture videos are available on YouTube:  
[ROB 101 Lecture Videos](https://www.youtube.com/playlist?list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv)  

And [lecture notes](https://github.com/michiganrobotics/rob101/tree/main/Lecture%20Notes) here.

## Textbook
The textbook, [Notes for Computational Linear Algebra](https://github.com/michiganrobotics/rob101/blob/main/Textbook/ROB_101_ComputationalLinearAlgebra_Grizzle_2020_12_15.pdf), continues to be updated.

## Projects
Three main projects that accompany the course are [available here](https://github.com/michiganrobotics/rob101/tree/main/Projects).

## Course Plan
| Lecture | Topic                            | Youtube                                                                                               | Textbook Chapters | Assignments due                                                                          |
|---------|----------------------------------|-------------------------------------------------------------------------------------------------------|--------------------------|------------------------------------------------------------------------------------------|
| 1       | Introduction                     | [Video](https://www.youtube.com/watch?v=v1jneRWVrxY&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=1)  | 1.1 - 1.2                |                                                                                          |
| 2       | Linear Equations & Matrices      | [Video](https://www.youtube.com/watch?v=itP15hjoLcg&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=2)  | 1.3 - 2.5                |                                                                                          |
| 3       | Matrix Determinant               | [Video](https://www.youtube.com/watch?v=oXT0Q_imxMk&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=3)  | 2.5 - 2.6                |                                                                                          |
| 4       | Determinant & Triangular Systems | [Video](https://www.youtube.com/watch?v=gabzvtBTi6A&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=4)  | 2.6 - 3.4                |                                                                                          |
| 5       | Triangular Systems: Substitution | [Video](https://www.youtube.com/watch?v=6auyyEsAxwY&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=5)  | 3.5 - 4.1                | [Homework 1](https://github.com/michiganrobotics/rob101/tree/main/Homework/Homework%201) |
| 6       | Matrix Multiplication            | [Video](https://www.youtube.com/watch?v=XDhlitYcM9k&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=6)  | 4.2 - 4.4                |                                                                                          |
| 7       | Matrix Multiplication II         | [Video](https://www.youtube.com/watch?v=9c9xe75VTag&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=7)  | 4.4 - 5.2                |                                                                                          |
| 8       | LU Factorization                 | [Video](https://www.youtube.com/watch?v=Z8t4kCGmiwM&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=8)  | 5.3        | [Homework 2](https://github.com/michiganrobotics/rob101/tree/main/Homework/Homework%202) |
| 9       | LU Factorization II              | [Video](https://www.youtube.com/watch?v=HyI3NSQeIVs&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=9)  | 5.3 - 5.5                |                                                                                          |
| 10      | Matrix Transpose & Inverse       | [Video](https://www.youtube.com/watch?v=4itGSAbBWbo&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=10) | 6.1 - 6.3                |                                                                                          |
| 11      | Vector Space R^n                 | [Video](https://www.youtube.com/watch?v=6JRoWeMolbY&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=11) | 6.3, skip to 7.1         |                                                                                          |
| 12      | Linear Independence              | [Video](https://www.youtube.com/watch?v=IBknl4aBOwo&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=12) | 7.2, 7.4                 | [Homework 3](https://github.com/michiganrobotics/rob101/tree/main/Homework/Homework%203) |
| 13      | Linear Independence II           | [Video](https://www.youtube.com/watch?v=xSV9ctrwNfg&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=13) | 7.4.5, 7.3, 7.5          |                                                                                          |
| 14      | Linear Independence III          | [Video](https://www.youtube.com/watch?v=ITGJXfshACQ&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=14) | 7.6 - 7.7                | [Project 1](https://github.com/michiganrobotics/rob101/tree/main/Projects/Project-01)    |
| 15      | Linear Independence IV           | [Video](https://www.youtube.com/watch?v=T6HiylBZAkU&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=15) | 7.7, skip to 8.1 - 8.2   |                                                                                          |
| 16      | Norm of a Vector                 | [Video](https://www.youtube.com/watch?v=GUWIRey6G18&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=16) | 8.2 - 8.3                |                                                                                          |
| 17      | Least Squares                    | [Video](https://www.youtube.com/watch?v=OLABElNVZRU&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=17) | 9.1 - 9.2                | [Homework 4](https://github.com/michiganrobotics/rob101/tree/main/Homework/Homework%204) |
| 18      | Subspaces                        | [Video](https://www.youtube.com/watch?v=mesSJVafvQA&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=18) | 9.2, 9.4                 |                                                                                          |
| 19      | Subspaces II                     | [Video](https://www.youtube.com/watch?v=JVTWEtsiC5Q&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=19) | 9.3 - 9.4                |                                                                                          |
| 20      | Rank & Nullity of a Matrix       | [Video](https://www.youtube.com/watch?v=cyCBDSd5jM0&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=20) | 9.5 - 9.6                | [Homework 5](https://github.com/michiganrobotics/rob101/tree/main/Homework/Homework%205) |
| 21      | Dot Product & Orthogonal Vectors | [Video](https://www.youtube.com/watch?v=kFW1c9LbHSQ&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=21) | 9.6                      |                                                                                          |
| 22      | Orthonormal Vectors              | [Video](https://www.youtube.com/watch?v=ZF6qyIuk1jo&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=22) | 9.7         |                                                                                          |
| 23      | QR Factorization                 | [Video](https://www.youtube.com/watch?v=wWBqstOQyg8&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=23) | 9.9 - 10.1               | [Homework 6](https://github.com/michiganrobotics/rob101/tree/main/Homework/Homework%206) |
| 24      | Roots of Nonlinear Equations     | [Video](https://www.youtube.com/watch?v=fyI290RVtW4&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=24) | 10.1 - 10.2              |                                                                                          |
| 25      | Bisection Algorithm              | [Video](https://www.youtube.com/watch?v=1h40va8YeSQ&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=25) | 10.3 - 10.4              |                                                                                          |
| 26      | Newton's Method                  | [Video](https://www.youtube.com/watch?v=DKovRqflvJA&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=26) | 10.4 - 10.5              | [Homework 7](https://github.com/michiganrobotics/rob101/tree/main/Homework/Homework%207) |
| 27      | Partial Derivatives & Roots      | [Video](https://www.youtube.com/watch?v=dmJDDcu0DP8&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=27) | 10.5                     |                                                                                          |
| 28      | Gradient & the Jacobian          | [Video](https://www.youtube.com/watch?v=G3SGmHv0rAk&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=28) | 10.5 - 10.6              |                                                                                          |
| 29      | Newton-Raphson Algorithm         | [Video](https://www.youtube.com/watch?v=kPoSOHnqCYg&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=29) | 11.1 - 11.2              | [Homework 8](https://github.com/michiganrobotics/rob101/tree/main/Homework/Homework%208) |
| 30      | Optimization                     | [Video](https://www.youtube.com/watch?v=rs9LYvkl6xg&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=30) | 11.3 - 11.4              |                                                                                          |
| 31      | Gradient Descent                 | [Video](https://www.youtube.com/watch?v=JqNdHVkCmUA&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=31) | 11.5 - 11.6 |                                                                                          |
| 32      | Optimization II                  | [Video](https://www.youtube.com/watch?v=-trMQhRrA2o&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=32) | 11.6, skip to A.1        | [Project 2](https://github.com/michiganrobotics/rob101/tree/main/Projects/Project-02)    |
| 33      | Affine Spaces                    | [Video](https://www.youtube.com/watch?v=WAGGwvdK6Hs&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=33) | A.1, skip to 11.8 - 11.9 |                                                                                          |
| 34      | Hyperplanes                      | [Video](https://www.youtube.com/watch?v=B1pSHrvXXqE&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=34) | 11.9, A.4                |                                                                                          |
| 35      | Quadratic Program                | [Video](https://www.youtube.com/watch?v=0o41lZ49G2I&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=35) | A.4 extensions           | [Homework 9](https://github.com/michiganrobotics/rob101/tree/main/Homework/Homework%209) |
| 36      | Quadratic Program II             | [Video](https://www.youtube.com/watch?v=e4iufA9meAc&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=36) | B.1 - B.1.3              |                                                                                          |
| 37      | Complex Numbers                  | [Video](https://www.youtube.com/watch?v=SOUc7FB79-4&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=37) | B.1.4                    |                                                                                          |
| 38      | Eigenvalues & Eigenvectors       | [Video](https://www.youtube.com/watch?v=ojd4oklzEE8&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=38) | B.1.4 - B.1.5            |                                                                                          |
| 39      | Final class & convolution        | [Video](https://www.youtube.com/watch?v=jpMDhDFsrp4&list=PLdPQZLMHRjDK8ZbLIcq1Q2PQobIi68dpv&index=39) | Not yet in book.         | [Project 3](https://github.com/michiganrobotics/rob101/tree/main/Projects/Project-03)    |

## Credits
- Chad Jenkins, Associate Director of Undergraduate Programs, Michigan Robotics
- Jessy Grizzle, Director, Michigan Robotics
- Maani Ghaffari, Assistant Professor, Naval and Marine Architecture, U-M
- Kira Biener
- Tribhi Kathuria
- Madhav Achar
- Fangtong (Miley) Liu
- Shaoxiong Yao
- Eva Mungai
- Bruce JK Huang
- Grant A. Gibson
- Oluwami Dosunmu-Ogunbi
- Lu Gan
- Ray Zhang

## For more
- [ROB 101 Course Information for those at U-M](https://robotics.umich.edu/academic-program/course-offerings/rob101/)
- [University of Michigan Robotics Institute](https://robotics.umich.edu)
- [Michigan Robotics Twitter](http://twitter.com/umrobotics)
- [Michigan Robotics Instagram](http://instagram.com/umrobotics/)
