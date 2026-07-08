<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<title>واجهة شحن تجريبية</title>
<style>
body{
    font-family: Arial;
    background:#111827;
    color:white;
    text-align:center;
}
.box{
    margin:60px auto;
    width:300px;
    background:#1f2937;
    padding:20px;
    border-radius:10px;
}
input,button{
    width:90%;
    padding:10px;
    margin:10px;
    border:none;
    border-radius:6px;
}
button{
    background:#10b981;
    color:white;
    cursor:pointer;
}
</style>
</head>
<body>

<div class="box">
<h2>واجهة شحن تجريبية</h2>
<p style="color:yellow;">هذه الصفحة للتجربة فقط ولا تقوم بأي شحن فعلي.</p>

<input type="text" placeholder="أدخل معرف اللاعب">

<select style="width:90%;padding:10px;border-radius:6px;">
<option>100 جوهرة</option>
<option>310 جوهرة</option>
<option>520 جوهرة</option>
</select>

<button onclick="demo()">شحن (تجريبي)</button>

<p id="msg"></p>
</div>

<script>
function demo(){
document.getElementById("msg").innerHTML =
"✅ تم الضغط على الزر. هذه مجرد محاكاة وليست عملية شحن حقيقية.";
}
</script>

</body>
</html># -
قيس 
