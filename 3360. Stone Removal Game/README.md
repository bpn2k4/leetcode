
<h3>Stone Removal Game</h3>
<div class="xg0bVG_html" data-qd-rendered-description="" data-track-load="description_content"><p>Alice and Bob are playing a game where they take turns removing stones from a pile, with <em>Alice going first</em>.</p>
<ul>
<li>Alice starts by removing <strong>exactly</strong> 10 stones on her first turn.</li>
<li>For each subsequent turn, each player removes <strong>exactly</strong> 1 fewer<strong> </strong>stone<strong> </strong>than the previous opponent.</li>
</ul>
<p>The player who cannot make a move loses the game.</p>
<p>Given a positive integer <code>n</code>, return <code>true</code> if Alice wins the game and <code>false</code> otherwise.</p>
<p> </p>
<p><span class="float-right -my-0.5 ml-2 inline-flex select-none items-center" data-example-lang-controls=""><span class="inline-flex h-6 items-center rounded-sd-md bg-sd-muted p-0.5" data-example-lang-toggle="" role="group"><button aria-pressed="true" class="h-5 max-w-[10rem] truncate whitespace-nowrap rounded-sd-sm border px-2 text-xs font-normal leading-none border-sd-border bg-sd-background text-sd-foreground" type="button">Original</button><button aria-pressed="false" class="h-5 max-w-[10rem] truncate whitespace-nowrap rounded-sd-sm border px-2 text-xs font-normal leading-none border-transparent text-sd-muted-foreground hover:text-sd-foreground" type="button">Python3</button></span></span><strong>Example 1:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">n = 12</span></p>
<p><strong>Output:</strong> <span class="example-io">true</span></p>
<p><strong>Explanation:</strong></p>
<ul>
<li>Alice removes 10 stones on her first turn, leaving 2 stones for Bob.</li>
<li>Bob cannot remove 9 stones, so Alice wins.</li>
</ul>
</div>
<p><strong>Example 2:</strong></p>
<div class="example-block">
<p><strong>Input:</strong> <span class="example-io">n = 1</span></p>
<p><strong>Output:</strong> <span class="example-io">false</span></p>
<p><strong>Explanation:</strong></p>
<ul>
<li>Alice cannot remove 10 stones, so Alice loses.</li>
</ul>
</div>
<p> </p>
<p><strong>Constraints:</strong></p>
<ul>
<li><code>1 &lt;= n &lt;= 50</code></li>
</ul>
</div>
