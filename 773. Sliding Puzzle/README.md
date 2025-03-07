
<h3>Sliding Puzzle</h3>
<div><p>On an <code>2 x 3</code> board, there are five tiles labeled from <code>1</code> to <code>5</code>, and an empty square represented by <code>0</code>. A <strong>move</strong> consists of choosing <code>0</code> and a 4-directionally adjacent number and swapping it.</p>
<p>The state of the board is solved if and only if the board is <code>[[1,2,3],[4,5,0]]</code>.</p>
<p>Given the puzzle board <code>board</code>, return <em>the least number of moves required so that the state of the board is solved</em>. If it is impossible for the state of the board to be solved, return <code>-1</code>.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<img alt="" src="assets/87bdb41f089c4ad89c942a1f40e7431d.jpg" style="width: 244px; height: 165px;"/>
<pre><strong>Input:</strong> board = [[1,2,3],[4,0,5]]
<strong>Output:</strong> 1
<strong>Explanation:</strong> Swap the 0 and the 5 in one move.
</pre>
<p><strong>Example 2:</strong></p>
<img alt="" src="assets/50e4d0d1a7b44914b7376b46cebfe4aa.jpg" style="width: 244px; height: 165px;"/>
<pre><strong>Input:</strong> board = [[1,2,3],[5,4,0]]
<strong>Output:</strong> -1
<strong>Explanation:</strong> No number of moves will make the board solved.
</pre>
<p><strong>Example 3:</strong></p>
<img alt="" src="assets/7efa0399b12149c3912ce9d9e07b473e.jpg" style="width: 244px; height: 165px;"/>
<pre><strong>Input:</strong> board = [[4,1,2],[5,0,3]]
<strong>Output:</strong> 5
<strong>Explanation:</strong> 5 is the smallest number of moves that solves the board.
An example path:
After move 0: [[4,1,2],[5,0,3]]
After move 1: [[4,1,2],[0,5,3]]
After move 2: [[0,1,2],[4,5,3]]
After move 3: [[1,0,2],[4,5,3]]
After move 4: [[1,2,0],[4,5,3]]
After move 5: [[1,2,3],[4,5,0]]
</pre>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>board.length == 2</code></li>
<li><code>board[i].length == 3</code></li>
<li><code>0 &lt;= board[i][j] &lt;= 5</code></li>
<li>Each value <code>board[i][j]</code> is <strong>unique</strong>.</li>
</ul>
</div>
