#CUrlRequest
Khan.Lau 大神亲情力作，VC下对curl的封装
***
##Usage
<pre>
CUrlRequest urq;
urq.post(url, parameters, [hWnd](const char* body, size_t len)->void {
                        [hWnd](int code)->void {
</pre>

##Other
std破天荒的引入了新的字符编码工具
<pre>
std::wstring to_wchar_t(std::string str) {
</pre>