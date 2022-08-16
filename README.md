# Chess Pieces Optimization

An optimization project for positioning the maximum number of chess pieces on an $(N*N)$ chessboard such that no two pieces attack each other.

In this project, our primary goal is to optimize the maximum number of chess pieces that can be put on a  $(N*N)$ chess board along with their location on the chess board so that no chess piece threatens any other chess piece. To accomplish this task, we will be using Mixed Integer Programming <b>(MIP)</b>. 

In this project, instead of just placing queens on a chess board, we will be placing the maximum number of knights (N), bishop(B), rook(R), queen(Q), and king(K). We will also find the locations of these chess pieces so that no chess piece threatens any other chess piece. All the chess piece movements follow their movements as per the chess rules.<br/>
This is interesting because building such an optimization model could solve N-Queens and many other more straightforward chess-piece-positioning problems (as discussed in our derived problem statement).

#### A) Main 
In our Main problem statement, we try to build a generalized optimization model that finds the maximum number of chess pieces one can place on an NxN chessboard so that no piece attacks any other, and the total number of pieces of each type lies in a particular range.

#### B) Derived
In our Derived problem statement, we try to find the maximum number of pieces of a particular type (one among N, B, R, Q, K) that one can place on an NxN chessboard so that no piece attacks any other. This essentially means solving N-Queens for piece type Q, N-Rooks for piece type R, and so on.


One can find structured information about the project, including the Introduction, Mathematical Model, Code, Results, Discussion, Conclusion, etc., in the `main.ipynb` file.




