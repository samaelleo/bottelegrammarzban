<h2>
معرفی
</h2>

این یک ربات تلگرامی است که با php  نوشته شده است

این ربات برای پنل مرزبان می باشد و قابلیت هایی شامل  ساخت اکانت تست ،مشاهده اطلاعات سرویس ، جوین اجباری و...  می باشد.




<h3>
آموزش نصب:
</h3>

برای اجرا سورس ابتدا باید یک هاست  تهیه کنید ( ترجیحا هاست ربات تلگرام هلند )  بجز هاست ایران هر هاستی میشه ربات را اجرا کرد. پس از تهیه  هاست مراحل زیر را به ترتیب انجام دهید.


1- ابتدا به ربات پدر رفته botfather@ و برای خود یک ربات بسازید و توکن ربات را کپی کنید چون در سورس باید جایگزاری کنید.

2- بعد از ساخت ربات و دریافت توکن سورس را که از لینک زیر آخرین نسخه میتوانید دانلود کنید را در هاست اپلود کرده.( ترجیحا داخل پوشه آپلود کنید )

https://github.com/mahdigholipour3/bottelegrammarzban/releases

3- پرونده ای که داخل هاست آپلود کرده اید را از حالت فشرده خارج کنید.

4- پس از خارج کردن پرونده فایل config.php را باز کرده و موارد زیر را تغییر دهید


$dbname = نام دیتابیس خود را وارد نمایید برای ساخت با رفتن به صفحه اصلی سی پنل و زدن گزینه MySQL® Database Wizard می توانید دیتابیس خود را بسازید

$username = نام کاربری دیتابیس خود را باید وارد نمایید

$password = رمز عبور دیتابیس ساخته شده را باید وارد نمایید

$token  = توکنی که از ربات بات فادر تهیه کردید را وارد کنید

$time = این متغییر برای بخش اکانت تست است که  تاریخ پایان  یوزر تست را باید وارد کنید زمان بر اساس ساعت باید وارد شود 

$val = این متغییر برای بخش اکانت تست است که حجم یوزر تستی که ایجاد می شود را باید وارد کنید که واحد بر اساس مگابایت باید وارد شود

$adminnumber  = آیدی عددی ادمین باید وارد شود  که از ربات زیر می توانید آیدی عددی خود را بگیرید  از پنل ادمین قابل تنظیم می باشد

@myidbot

$limit_usertest = محدودیت ساخت اکانت تست بطور پیشفرض را وارد نمایید از پنل ادمین قابل تنظیم می باشد


5 - پس از ذخیره  فایل را ذخیره کنید.  و در مرورگر خود یکبار ایل table.php را در مرورگر خود باز کنید تا جداول دیتابیس ایجاد شوند

6 - کارتان در هاست تمام شده است حالا باید وبهوک ربات را انجام بدهید تا ربات شما روشن شود برای وب هوک از دو طریق می توانید این کار را انجام دهید
 
روش اول از طریق  سایت لینک تلگرام :

برای وبهوک از طریق  لینک تلگرام  از لینک زیر میتوانید انجام دهید و باید در قسمت هایی که فارسی نوشته شده مقدار  ها را وارد کنید

 
https://api.telegram.org/botتوکن/setwebhook?url=https://site.com/مسیر پوشه /index.php


در صورتی که وبهوک موفقیت آمیز باشد خروجی زیر را نشان خواهد داد.

{“ok”:true,”result”:true,”description”:”Webhook was set”}

روش دوم از طریق ربات تلگرام : 
برای انجام وبهوک ربات تلگرام از طریق آیدی زیر میتوانید ربات را استارت کرده و ربات را وبهوک کنید

 
https://t.me/SwhBot


نکته های استفاده از سورس:

برای وارد به پنل ادمین از دستور "panel " استفاده کنید
 
در صورتی که می خواهید متن های ربات تغییر دهید می توانید از فایل index.php  استفاده نمایید.

برای قابلیت عضویت اجباری ربات حتما باید ادمین کانال باشد. در غیر اینصورت این قابلیت کار نخواهد کرد

پنل را باید از پنل ادمین ربات اضافه نمایید

برای اینکه تعیین کنید چه پروتکل هایی ساخته شود از فایل apipanel میتوانید

<h2>

کانال تلگرامی ما 
@botpanelmarzban


و در آخر در صورت وجود مشکل ، درخواست ویژگی جدید یا راهنمایی میتوانید یک درخواست باز کنید یا با آیدی تلگرام @gholipour3  در ارتباط باشید. و لطفا به این پروژه ستاره دهید

برای حمایت از ما از کیف پول های زیر می توانید استفاده کنید.

TRX(TRC20): 

TLYPZq8m7EXKyZuhJDQ2vmjH2fpoa9XuJT 

USDT(TRC20)

TMRaoveUu1pprEvaibk7w3DqVFhEpbfwjz    


</h2>
