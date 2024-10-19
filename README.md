<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>صفحة بسيطة</title>
    <style>
        body {
            display: flex;
            flex-direction: column; /* ترتيب العناصر عموديًا */
            justify-content: flex-start; /* جعل المحتوى يبدأ من الأعلى */
            align-items: flex-start; /* محاذاة العناصر لليسار */
            height: 100vh; /* يجعل المحتوى في منتصف الشاشة عموديًا */
            background-color: black; /* خلفية الصفحة باللون الأسود */
            font-family: Arial, sans-serif;
            color: white; /* لون النص الافتراضي أبيض */
            padding: 20px; /* مسافة داخلية */
            overflow-y: auto; /* تمكين التمرير العمودي */
        }
        .header {
            font-size: 66px; /* حجم الخط */
            color: green; /* اللون الأخضر */
            margin-bottom: 20px; /* مسافة أسفل العنوان */
        }
        .content {
            font-size: 30px; /* حجم الخط */
            color: gray; /* لون النص الرمادي */
            margin-top: 20px; /* مسافة من الأعلى */
        }
        .list {
            list-style-type: none; /* إزالة نقاط القائمة */
            padding: 0; /* إزالة المساحة الداخلية للقائمة */
            text-align: left; /* محاذاة النص لليسار */
        }
        .list li {
            margin: 5px 0; /* مسافة بين العناصر */
            font-size: 15px; /* حجم خط العناصر في القائمة */
            display: flex; /* يسمح بمحاذاة الصورة والنص */
            align-items: center; /* محاذاة العناصر في المنتصف عموديًا */
        }
        .list img {
            width: 75px; /* عرض الصورة بحجم 5 أضعاف الخط */
            height: auto; /* الحفاظ على نسبة الطول إلى العرض */
            margin-right: 10px; /* مسافة بين النص والصورة */
        }
    </style>
</head>
<body>

    <div class="header">جوني سينس للاختراق</div>
    <div class="content">
        <h2>أنواع الاختراقات:</h2>
        <ul class="list">
            <li><img src="https://img.icons8.com/ios-filled/75/FFFFFF/network.png" alt="Network Hacking">اختراق الشبكات (Network Hacking)</li>
            <li><img src="https://img.icons8.com/ios-filled/75/FFFFFF/user-lock.png" alt="Account Hacking">اختراق الحسابات (Account Hacking)</li>
            <li><img src="https://img.icons8.com/ios-filled/75/FFFFFF/target.png" alt="Targeted Attacks">الهجمات المستهدفة (Targeted Attacks)</li>
            <li><img src="https://img.icons8.com/ios-filled/75/FFFFFF/application.png" alt="Application Hacking">اختراق التطبيقات (Application Hacking)</li>
            <li><img src="https://img.icons8.com/ios-filled/75/FFFFFF/computer.png" alt="Device Hacking">اختراق الأجهزة (Device Hacking)</li>
            <li><img src="https://img.icons8.com/ios-filled/75/FFFFFF/cyber-security.png" alt="Cyber Attacks">الهجمات الإلكترونية (Cyber Attacks)</li>
            <li><img src="https://img.icons8.com/ios-filled/75/FFFFFF/phishing.png" alt="Phishing">اختراقات الـ Phishing</li>
            <li><img src="https://img.icons8.com/ios-filled/75/FFFFFF/malware.png" alt="Malware">اختراقات الـ Malware</li>
            <li><img src="https://img.icons8.com/ios-filled/75/FFFFFF/ddos.png" alt="DDoS">اختراقات الـ DDoS</li>
            <li><img src="https://img.icons8.com/ios-filled/75/FFFFFF/ransomware.png" alt="Ransomware">اختراقات الـ Ransomware</li>
        </ul>
    </div>

</body>
</html>
