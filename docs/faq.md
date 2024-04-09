<h1 align="center">⁉️ سوالات متداول</h1>

1- چرا کانفیگ Fragment وصل نمیشه؟
- اگر `Routing` فعال کردید و VPN متصل نشد تنها دلیلش آپدیت نبودن Geo asset هست. از منوی برنامه‌ی v2rayNG وارد قسمت `Geo asset files` بشید و اون علامت ابر یا دانلود رو بزنید تا آپدیت بشن، اگر آپدیت ناموفق باشه وصل نمیشید. اگر هر کاری کردید آپدیت نشد دو تا فایل از دو تا لینک زیر دانلود کنید و بجای آپدیت زدن، دکمه اضافه کردن رو بزنید و این دوتا فایل رو وارد کنید:
> 
>[geoip.dat](https://github.com/Loyalsoldier/v2ray-rules-dat/releases/latest/download/geoip.dat)
> 
>[geosite.dat](https://github.com/Loyalsoldier/v2ray-rules-dat/releases/latest/download/geosite.dat)
<br> 

2- چرا کانفیگ نرمال وصل نمیشه؟
- برای استفاده از این کانفیگ ها `Mux` رو از تنظیمات هر اپلیکیشنی که استفاده میکنید خاموش کنید.
<br>

3- چرا برنامه‌های Nekobox یا Hiddify Next هیچ سایتی رو باز نمیکنن؟
- باید داخل تنظیمات اپلیکیشن `remote DNS` رو اینجوری بذارید:
> `https://8.8.8.8/dns-query`
<br>

4- چرا کانفیگ فرگمنت روی اپراتور من سرعتش کمه؟
- هر اپراتوری تنظیمات فرگمنت مخصوص خودش رو داره. اکثرا با پیشفرض پنل اوکی هستن ولی ممکنه روی اپراتور شما این مقادیر بهتر باشه، باید تست کنید:
> `Length: 10-100`
> 
> `Length: 10-20`
<br>

5- چرا Ping من انقدر بالاست؟
- به هیچ عنوان از `https://1.1.1.1/dns-query` برای remote DNS استفاده نکنید چون پینگ رو بالا میبره.
<br>

6- من از اون دو تا لینک آموزش Proxy IP گذاشتم ولی سایتا رو باز نمیکنه!
- تعداد این IP ها زیاده و ممکنه تعداد زیادیشون از کار افتاده باشن. باید تست کنید تا یه خوبشو سوا کنید.
<br>

7- وقتی proxy IP گذاشتم کار میکرد ولی الان از کار افتاده!
- اگر از تک IP استفاده کنید احتمالا بعد یه مدت دوباره از کار میافته و خیلی سایتا باز نمیشن. باید از اول این مراحلو برید. ترجیحا اگر کار خاصی انجام نمیدید که نیاز به IP ثابت داشته باشه بذارید پیشفرض پنل بمونه، Proxy IP تکی نذارید.
<br>

8- چرا وقتی میرم به آدرس `panel/` ارور میده؟
- طبق آموزش راه‌اندازی کنید، KV درست تنظیم نشده.