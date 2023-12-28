<div dir='rtl' align="center">
به نام پروردگار هدایت کننده به راه راست

  دانشگاه اصفهان

  ساختمان داده – دکتر رمضانی 

  پاییز ۰۳-۰۲

  پروژه چهارم –  موتور جستجو 


<img src="https://s24.picofile.com/file/8456084100/Picture44.png"  width="500"/>
  
  طراحان پروژه : امیرعلی گلی ، الهام گرفته شده از کداستار
</div>

<div dir='rtl' align="justify">
  
### مبحث : مپ 
اهداف پروژه :
+ کار با ساختمان داده مپ
+ آشنایی با موتورهای جستجو و نحوه کار آن‌ها



در این پروژه قرار است با استفاده از ساختمان‌داده مپ یک موتور جستجو را شبیه‌سازی کنید.

## گام های پروژه
### گام اول:

قبل از شروع مطالعه روی دو سوال زیر فکر کنید تا ذهن شما آماده شود.

+ به روز‌های اول تشکیل شرکت گوگل فکر کنید، فرض کنید متن‌های چند صد هزار صفحه‌ی وب را جمع آوری کرده‌اید و می‌خواهید بین آن صفحات جستجو کنید. چه راه حلی برای اجرای کوئری چند کلمه‌ای کاربران بین هزاران صفحه متن که از قبل آماده شده است به ذهنتان می‌رسد؟
    چطور می‌شود این جستجو را از مرتبه‌ی یک یا همان (O(1 انجام داد؟

+ یکی از داده‌ساختارهایی که برای پیاده‌سازی موتور جستجو قابل‌استفاده است، Inverted Index می‌باشد. برای آشنایی با این داده ساختار (https://www.geeksforgeeks.org/inverted-index/)[Inverted Index - GeeksforGeeks] را مطالعه کنید؛ سپس برای فهم بهتر ویدئوی (https://www.youtube.com/watch?v=bnP6TsqyF30)[The Inverted Index]  را مشاهده نمایید.

### گام دوم:

در گام اول، از ریپازیتوری پروژه Clone بگیرید تا در سیستم خود داشته باشید.



### گام سوم :

ما فایل‌های اسنادی داریم که حاوی کلمات انگلیسی هستند. 

  (https://star-academy.github.io/codestar-documents/assets/files/the-20-newsgroups-b28960092a8cf8e833bba736d4f3d433.zip  
)[دانلود اسناد]

اسناد داده شده را بخوانید و به نحوی ویرایش کنید که فاقد هرگونه علائم نگارشی بوده و کلمات آن با اسپیس از هم جدا شده باشد. (کاراکتر اسپیس جداکننده تمامی کلمات است.)


### گام چهارم : 

برنامه خود را به گونه‌ای طراحی کنید که تعدادی Document را بخواند و از روی آن‌ها یک Inverted Index بسازد؛ سپس از کاربر یک کلمه به عنوان ورودی بگیرد و نام Documentهایی که شامل آن کلمه هستند را در خروجی نمایش دهد.

دقت کنید که موتور جستجوی شما می‌تواند سه نوع ورودی از کاربر بگیرد:

+ کلماتی که حتما باید در نتیجه وجود داشته باشند. این کلمات پیشوندی ندارند.
+ کلماتی که حداقل یکی از آن‌ها باید در نتیجه وجود داشته باشند. این کلمات با پیشوند + مشخص می‌شوند.
+ کلماتی که نباید در نتیجه وجود داشته باشند. این کلمات با پیشوند - مشخص می‌شوند.

ورودی نوع اول مانند And، نوع دوم مانند Or و نوع سوم مانند Not می‌باشد.

<details class="red"> 
<summary>مثال</summary>

> get help +illness +disease -cough

با استفاده از Query بالا می‌توانیم Documentهایی را پیدا کنیم که حتماً شامل عبارات get و help و همچنین حداقل یکی از عبارات illness و disease باشند و شامل عبارت cough نباشند.
  
</details>

### بخش امتیازی:
+	در صورت نبود یک کلمه در تمام متون، کلمات مشابه با یک اختلاف( تغییر در حروف، کم و زیاد شدن تعداد حروف)  را نشان داده و سپس سرچ کند. ( امتیاز بالا )
+	استفاده از الستیک سرچ () برای ذخیره سازی اسناد و بازیابی آن‌ها با استفاده از queryهای آن (امتیازی متوسط)
+	رابط کاربری گرافیکی ( امتیازی متوسط )



## نکات تکمیلی :
+ این پروژه بصورت تک نفری باید پیاده سازی شود.
+ بستر پیاده سازی پروژه روی گیت‌هاب می‌باشد.
+ سعی کنید هریک از بخش‌ها را در یک کامیت جداگانه انجام دهید.
+ رعایت اصول کدنویسی تمیز بخش بسیار زیادی از نمره را به خود اختصاص می‌دهد و درصورتی که کد کاملا به شکل غیراصولی پیاده سازی شده باشد. تحویل گرفته نمی‌شود.
+ استفاده از هر زبان، فریمورک و رابط‌های گرافیکی کاملا آزاد است.
+ به افرادی که از تکلنولوژی‌های جدید استفاده کنند، توکن تمدید اضافه‌تر داده خواهد شد.




</div>
