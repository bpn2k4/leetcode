
<h3>Tìm chuỗi ký tự gốc được gõ I</h3>
<div><p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Alice đang cố gắng nhập một chuỗi ký tự cụ thể trên máy tính của mình. Tuy nhiên, cô ấy có xu hướng vụng về và </font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">có thể</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> nhấn một phím quá lâu, dẫn đến việc một ký tự được nhập </font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">nhiều</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> lần.</font></font></p>
<p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mặc dù Alice cố gắng tập trung vào việc gõ phím, cô nhận thức rằng có lẽ cô vẫn chỉ làm điều này </font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">nhiều nhất </font></font></strong> <em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">một lần</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> .</font></font></p>
<p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Bạn được cung cấp một chuỗi ký </font></font><code>word</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">tự biểu thị kết quả </font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">cuối cùng</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> được hiển thị trên màn hình của Alice.</font></font></p>
<p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Trả về tổng số </font><font style="vertical-align: inherit;">chuỗi gốc có thể có mà Alice </font><em><font style="vertical-align: inherit;">có </font></em></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ý</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> định nhập.</font></font><em><font style="vertical-align: inherit;"></font></em><font style="vertical-align: inherit;"></font></p>
<p> </p>
<p><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ví dụ 1:</font></font></strong></p>
<div class="example-block">
<p><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Đầu vào: </font></font></strong> <span class="example-io"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">word = "abbbcccc"</font></font></span></p>
<p><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Đầu ra: </font></font></strong> <span class="example-io"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">5</font></font></span></p>
<p><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Giải thích:</font></font></strong></p>
<p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Các chuỗi có thể là: </font></font><code>"abbcccc"</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">, </font></font><code>"abbccc"</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">, </font></font><code>"abbcc"</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">, </font></font><code>"abbc"</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">, và </font></font><code>"abcccc"</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></p>
</div>
<p><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ví dụ 2:</font></font></strong></p>
<div class="example-block">
<p><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Đầu vào: </font></font></strong> <span class="example-io"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">word = "abcd"</font></font></span></p>
<p><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Đầu ra: </font></font></strong> <span class="example-io"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1</font></font></span></p>
<p><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Giải thích:</font></font></strong></p>
<p><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Chuỗi duy nhất có thể là </font></font><code>"abcd"</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">.</font></font></p>
</div>
<p><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Ví dụ 3:</font></font></strong></p>
<div class="example-block">
<p><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Đầu vào: </font></font></strong> <span class="example-io"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">word = "aaaa"</font></font></span></p>
<p><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Đầu ra: </font></font></strong> <span class="example-io"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">4</font></font></span></p>
</div>
<p> </p>
<p><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Hạn chế:</font></font></strong></p>
<ul>
<li><code>1 &lt;= word.length &lt;= 100</code></li>
<li><code>word</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">chỉ bao gồm các chữ cái tiếng Anh viết thường.</font></font></li>
</ul>
</div>
