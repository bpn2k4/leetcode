
<h3>Sudoku Solver</h3>
<div><p>Write a program to solve a Sudoku puzzle by filling the empty cells.</p>
<p>A sudoku solution must satisfy <strong>all of the following rules</strong>:</p>
<ol>
<li>Each of the digits <code>1-9</code> must occur exactly once in each row.</li>
<li>Each of the digits <code>1-9</code> must occur exactly once in each column.</li>
<li>Each of the digits <code>1-9</code> must occur exactly once in each of the 9 <code>3x3</code> sub-boxes of the grid.</li>
</ol>
<p>The <code>'.'</code> character indicates empty cells.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<img src="assets/718607b4611c426d959359cda9923f10.png" style="height: 250px; width: 250px;"/>
<pre><strong>Input:</strong> board = [["5","3",".",".","7",".",".",".","."],["6",".",".","1","9","5",".",".","."],[".","9","8",".",".",".",".","6","."],["8",".",".",".","6",".",".",".","3"],["4",".",".","8",".","3",".",".","1"],["7",".",".",".","2",".",".",".","6"],[".","6",".",".",".",".","2","8","."],[".",".",".","4","1","9",".",".","5"],[".",".",".",".","8",".",".","7","9"]]
<strong>Output:</strong> [["5","3","4","6","7","8","9","1","2"],["6","7","2","1","9","5","3","4","8"],["1","9","8","3","4","2","5","6","7"],["8","5","9","7","6","1","4","2","3"],["4","2","6","8","5","3","7","9","1"],["7","1","3","9","2","4","8","5","6"],["9","6","1","5","3","7","2","8","4"],["2","8","7","4","1","9","6","3","5"],["3","4","5","2","8","6","1","7","9"]]
<strong>Explanation:</strong> The input board is shown above and the only valid solution is shown below:

<img src="assets/11205d2cd9be439780d36e2991e0310b.png" style="height: 250px; width: 250px;"/>
</pre>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>board.length == 9</code></li>
<li><code>board[i].length == 9</code></li>
<li><code>board[i][j]</code> is a digit or <code>'.'</code>.</li>
<li>It is <strong>guaranteed</strong> that the input board has only one solution.</li>
</ul>
</div>