
<h3>Maximum Number of Events That Can Be Attended</h3>
<div><p>You are given an array of <code>events</code> where <code>events[i] = [startDay<sub>i</sub>, endDay<sub>i</sub>]</code>. Every event <code>i</code> starts at <code>startDay<sub>i</sub></code><sub> </sub>and ends at <code>endDay<sub>i</sub></code>.</p>
<p>You can attend an event <code>i</code> at any day <code>d</code> where <code>startTime<sub>i</sub> &lt;= d &lt;= endTime<sub>i</sub></code>. You can only attend one event at any time <code>d</code>.</p>
<p>Return <em>the maximum number of events you can attend</em>.</p>
<p> </p>
<p><strong>Example 1:</strong></p>
<img alt="" src="assets/b29156a0322f4ccdad771c13e4c9b364.png" style="width: 400px; height: 267px;"/>
<pre><strong>Input:</strong> events = [[1,2],[2,3],[3,4]]
<strong>Output:</strong> 3
<strong>Explanation:</strong> You can attend all the three events.
One way to attend them all is as shown.
Attend the first event on day 1.
Attend the second event on day 2.
Attend the third event on day 3.
</pre>
<p><strong>Example 2:</strong></p>
<pre><strong>Input:</strong> events= [[1,2],[2,3],[3,4],[1,2]]
<strong>Output:</strong> 4
</pre>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>1 &lt;= events.length &lt;= 10<sup>5</sup></code></li>
<li><code>events[i].length == 2</code></li>
<li><code>1 &lt;= startDay<sub>i</sub> &lt;= endDay<sub>i</sub> &lt;= 10<sup>5</sup></code></li>
</ul>
</div>
