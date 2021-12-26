# AdvSoftEng_AliRazavi_4001
Advance Software Engineering Assignments for 1400-1401-1 semester by Ali Razavi
<div dir="rtl">
  
## نیمه اول

### ۱. معنی و مفهوم Function Point و معادل فارسی آن

 
واژه Function Point برای اولین بار در سال ۱۹۷۹ میلادی توسط الن آلبرخت در مقاله‌ای تحت عنوان اندازه‌گیری بهره‌وری توسعه برنامه استفاده شد. او در این مقاله با اشاره به ضرورت ساخت سنگ محکی جامع که بتوان با آن بهره وری افراد را در طی فرآیند طراحی، تولید و تست برنامه، ضمن حفظ استقلال نسبت به انواع تکنولوژی و زبان‌های برنامه‌نویسی اندازه گرفت، روشی مبتنی بر Function Point ارائه کرد که حدوداً به طول پنج سال قبل از ارائه مقاله در شرکت IBM برای مقایسه ۲۲ پروژه کامل شده، استفاده شد. نتیجه بکارگیری این روش باعث افزایش بهره‌وری ۳ به ۱ در طی پنج سال شد.روش مذکور با ارائه فرمولی به شرح زیر برای اندازه گیری Function Point پروژه معرفی شد:
 
تعداد ورودی ضرب در ۴ + تعداد خروجی ضرب در ۵ + تعداد پرس‌وجو (inquiry) ضرب در ۴ + تعداد Master File ضرب در ۱۰
با ظهور پایگاه‌های داده مختلف چه تجاری و چه متن‌باز، فراگیری اینترنت و رشد کتابخانه‌ها و همچنین روی کار آمدن زبان‌های مختلف برنامه نویسی و ایجاد فاصله‌ای بزرگتر نسبت به زبان‌های سطح پائین و سطح بالا، نیاز به بازنویسی روش فوق احساس شد. به همین جهت این اصطلاح توسط گروه بین‌المللی Function Point اصلاح شد.

نسخه اصلی و اصلاح شده، با هدف ارائه متراژی برای اندازه‌گیری پروژه توسعه نرم‌افزار به‌همراه نگه‌داری آن، بدون وابستگی به ابزار یا تکنولوژی خاصی به مشتریان و ذی‌نفعان برای تخمین هزینه و منابع یا مقایسه دو پروژه طراحی شده است.

در روش امروزی، ۵ نوع برای محاسبه Function Point وجود دارد:
- ورودی خارجی: مسئول پردازش و کنترل داده خارج از محدوده برنامه است.
-	خروجی خارجی: مسئول تولید یا کنترل داده‌های ارسال شده به خارج از محدوده برنامه است.
-	پرس‌وجو خارجی: ترکیبی برای دریافت داده متناسب با ورودی ارائه شده می‌باشد.
-	فایل منطقی داخلی: مجموعه‌ای از داده‌های نگه‌داری شده در محدوده برنامه است.
-	فایل رابط خارجی: مجموعه‌ای از داده‌هایی که توسط برنامه استفاده ولی خارج از محدوده برنامه نگه‌داری می‌شود.

ضریب‌ها نیز با توجه با درجه پیچیدگی، می‌تواند ۳ عدد مختلف باشند که در نهایت با مقدار پیچیدگی که از ۱۴ سوال بدست آمده، جمع شده و عدد نهایی را بوجود
می‌آورد. در نهایت می‌توان با اندازه‌گیری‌های مختلف مثل تعداد خطوط کد در زبانی خاص، ساعات مصرف شده، خطاها، اندازه مستندات و موارد دیگر به ازای هر Function Point، به نتیجه‌گیری‌های مختلفی رسید.
  
برای ترجمه این واژه، اصطلاح امتیاز کارکرد پیشنهاد می‌شود.


### ۲. رابطه تضمین کیفیت نرم افزار و کیفیت نرم افزار

برخلاف تصور غالب، تضمین کیفیت قبل از شروع توسعه نرم‌افزار آغاز می‌شود. در ابتدای تعریف تضمین کیفیت نرم‌افزار، باید معنی کیفیت نرم‌افزار، فعالیت‌های لازم برای تضمین آن را بدانیم. تضمین کیفیت، الگویی از اعمال برنامه‌ریزی‌شده برای اطمینان از کیفیت بالای نرم‌افزار تعریف می‌شود که از عناصر زیر تشکیل می‌شود:
-	استانداردها: اطمینان از پیروی استاندارد مفروض
-	مرور و بازرسی: اطمینان از پیروی مفاد استاندارد در محصول
-	تست: اطمینان از انجام تست جامع و مؤثر با هدف یافتن خطا
-	جمع‌آوری و تحلیل خطا: برای شناسایی بهتر خطا و یافتن فعالیت مناسب برای حذف آن
-	مدیریت تغییر: اطمینان از وجود انعطاف‌پذیری لازم هنگام تغییر
-	آموزش: بهبود آموزش ذی‌نفعان
-	مدیریت فروشنده: اطمینان از پیروی شیوه‌های تضمین کیفیت
-	مدیریت امنیت: اطمینان از بکارگیری فرآیند و تکنولوژی مناسب
-	امنیت: ارزیابی اثر از کار افتادگی نرم‌افزار و قدم‌های ضروری برای کاهش آن
-	پشتیبانی: اطمینان از کیفیت مستندات، راهنما‌ها و موارد دیگر
این گروه با مشخص کردن استانداردها، مرور و مشارکت در فرآیند توسعه برای اطمینان از تطبیق با استاندارد مفروض، ضبط، رفع و گزارش انحرافات، وظایف مربوط به تضمین کیفیت را انجام می‌دهند.
تیم بطور مستقیم بر کیفیت‌های زیر تاثیر گذار است:
-	کیفیت نیازمندی‌ها: تیم تضمین کیفیت باید اطمینان حاصل کند، تیم توسعه، نیازمندی‌های لازم برای رسیدن به محصول با کیفیت را مرور کرده‌اند.
-	کیفیت طراحی: تیم باید با ارزیابی هر جز طراحی، از تطابق آن با استاندارد کیفیت اطمینان حاصل کند.
-	کیفیت کد: تیم باید کد منبع و موارد مرتبط را برای اطمینان از پیروی از استاندارد کد نویسی مثل قابلیت نگهداری تحلیل کند.
-	اثربخشی کنترل کیفیت: تیم باید با بررسی تخصیص منابع برای مرور و تست، از کارآمدی بالای آنها، مطمئن شود.
  
در ادامه با بکارگیری آمار در تضمین کیفیت، می‌توان به قسمت‌های حیاتی (۲۰ درصد اصلی) که عامل بخش بزرگی از خطاها در نرم‌افزار هستند را پی برد و با صرف کمترین منابع، بیشترین بهره را برد. در حقیقت، تضمین کیفیت، سپری است که به هر روند نرم‌افزار اعمال شده و با بکارگیری متودها و ابزار، تست و مرور فنی و موارد دیگر، از تطبیق آنها با استاندارد مشخص شده، اطمینان حاصل می‌کند تا در نهایت محصولی با کیفیت تولید شود.

  
## نیمه دوم

### ۱. نحوه تشکیل تیم دانشجویی برای تولید موثر نرم‌افزار

  استعداد یابی افراد در ابتدا مراحل و مشاوره با افراد مطلع برای اتصال علاقه آنها به روز بازار کار در ابتدای فعالیت دانشگاهی، تا با روشن شدن مسیر یا در مواردی تغییر مسیر، افراد با آگاهی و علاقه وارد رشته خود شوند.
معرفی پتانسیل بالقوه دانشجویان و پروژه‌های پژوهشی برای شرکت‌ها فعال، تا با دعوت از آنها پروژه‌های متنوعی در طیف گسترده‌ای برای دانشجویان، حمایت و پشتیبانی شود.
  
افزایش تعامل بین دانشجویان با برگزاری رویدادهای متنوع (تخصصی و غیر تخصصی) برای آشنایی با مهارت‌ها و استعداد یکدیگر که حتی می‌تواند با برگزاری رویدادهای کلی، از دانشجویان رشته‌ها مختلف دعوت شود تا افراد نه تنها با فرصت‌های رشته خود بلکه با فرصت‌های بین-رشته‌ای در همکاری با سایر دانشجویان آشنا شوند.
  
برگزاری تجربه‌محور کلاس‌ها در عصری که متون و پاورپوینت دروس در دسترس همه افراد است حتی افراد خارج از دانشگاه اما گوهر نایاب، تجربه افراد در بازار کار (چه استاد – چه دانشجو) است که کمتر جایی نوشته شده‌اند و به آسانی قابل دسترسی نیستند.

  

### ۲. نقش مهندسی نرم‌افزار پیشرفته در تحقق شعار سال (تولید، پشتیبانی‌ها و مانع‌زدایی‌ها)

در نظر داشتن نرخ خرابی برای محصولات تا محصولاتی با قابلیت نگهداری بالا یا توانایی بروز رسانی با صرف منابع کمتر تولید شود. در عین حال، نظارت و کنترل بر محصولات تولید شده قبلی تا بتواند پاسخگو نیاز روز باشد و از کاربران در مقابل آسیب‌های جدید مراقبت کند.
استفاده از چارچوب روند مهندسی نرم‌افزار برای سایر حوزه‌ها جهت تولید محصول با کیفیت:
-	ارتباط و همکاری با مشتریان و ذی‌نفعان محصول برای درک نیازمندی‌ها
    -	شنوا بودن
    -	آمادگی قبل از ارتباط
    -	ارتباط چهره به چهره
    -	یادداشت برداری و مستند سازی تصمیمات
    -	بدنبال سود رساندن به دو طرف (برد-برد)
-	برنامه‌ریزی: شکستن پروژه به بخش‌های کوچکتر، شناسایی منابع و ریسک‌های احتمالی به همراه راهکار تخفیف یا برون‌رفت از آنها
    -	درک محدوده پروژه
    -	مشارکت ذی‌نفعان
    -	درک iterative بودن برنامه‌ریزی
    -	واقع‌گرا بودن
    -	نقشه‌ریزی برای نحوه تضمین کیفیت و پذیرش تغییر
-	مدلسازی: شبیه‌سازی پروژه برای شناسایی نقاط حساس و خطرات که اصلاح نقشه را با صرف منابع کمتری ممکن می‌سازد
    -	به یاد داشتن هدف اصلی تیم (ارائه محصول نه مدلسازی)
    -	دنبال کردن ساده‌ترین مدلی که بیانگر نیازمندی‌هاست و اجتناب از مدلسازی بیش از اندازه
    -	به دنبال ساخت مدل مفید بودن نه ایده‌آل
    -	گوش دادن به غریزه خود (البته اگر با تجربه هستید)
    -	دریافت بازخورد در سریعترین زمان ممکن
•	ساخت و تولید: طبق نقشه و تست بخش‌های مختلف برای اطمینان از کیفیت
    -	تمام تست‌ها، به نیازمندی مشتری مرجوع می‌شوند
    -	پیروی از اصل 80/۲۰
•	تحویل: دریافت بازخورد از کاربران نهایی
    -	مدیریت توقعات مشتری (توقع بیش از اندازه منجر به ناامیدی می‌شود)
    -	تشکیل بخش پشتیبانی قبل از تحویل محصول
    -	اولویت داده اصلاح محصول ناقص بجای تحویل به موقع (مشتریان تجربه تلخ مشتریان بهتر از تجربیات خوش، در حافظه به یاد سپرده می‌شود)
اهمیت اصول کلی:
-	در طراحی محصول، روند باید تا جای ممکن ساده باشد
-	آینده‌نگری: محصول طوری طراحی شود که در آینده قابلیت بهبود و تطبیق با استاندار روز را داشته باشد
-	تفکر: تفکر شفاف و جامع تقریباً همیشه منجر به خلق نتیجه بهتر می‌شود.
بکارگیری اصول Agile:
-	بالاترین اولویت، رضایت مشتری است
-	در هر مرحله از توسعه، پذیرای تغییر باشید
-	بین تیم بخش تولید و بخش تجاری ارتباط مؤثر ایجاد کنید
-	محصول را با استفاده از افراد مشتاق تولید کنید
-	بهترین روش انتقال پیام، شکل حضوری است
-	به بهبود طراحی و مسائل فنی دائماً توجه کنید
-	بصورت دوره‌ای، کارایی را بسنجید و بدنبال بهبود باشید

### ۳. تجزیه و تحلیل مشکلات نظام آموزشی در پرورش دانشجویان توانمند برای تولید نرم‌افزار

مسلماً در یک جامعه، اجزا به شکلی درهم پیچیده شده‌اند که تفکیک و بهبود یک بخش، تولید نتیجه بهتر را تضمین نمی‌کند. آن هم در جامعی که مشکلات مختلف اقتصادی، اجتماعی، این گره را پیچیده‌تر کرده است. در شرایطی که بسیاری از کسب‌وکارها برای بقا دست‌وپنجه می‌زنند، طبیعی است دانشگاهی پیدا شود که با ثبت‌نام آزاد دانشجویان در رشته‌های مختلف، حتی در مقاطع تحقیقی مثل ارشد، بدون انجام مصاحبه و شناسایی استعداد و علایق افراد، قواعد بازی را درهم زند.
  
بی‌توجهی به نرخ خرابی یا فرسودگی در سامانه‌های نرم‌افزاری که از زمان شکل‌گیری آنها مدت‌ها گذشته و تعداد کاربرانشان چند ده برابر شده، نتیجه جز داشتن نمونه‌هایی مثل سامانه گلستان یا سامانه LMS که قبل از انتهای ترم آموزشی، فایل‌های آموزشی اساتید را حذف می‌کند یا سامانه‌ای که نمی‌تواند بار تماس تصویری دانشجویان و اساتید در کلاس را تحمل کند نیست که گویا این پدیده منحصر به دانشگاه پیام نور نمی‌باشد.
  
عدم ارتباط مؤثر و شفاف بین مسئولین و تصمیم گیران با دانشجویان و اساتید برای بهبود روند آموزشی – چه در سطح آموزشی از وجود کنکور – تمرکز منابع و فرصت‌ها به دانشگاه‌ها و موسسات مطرح تا سطح کلان کشوری در ارائه طرحی که منجر به تغییر طرح بازنشستگی شده اما بازخورد جامعی از شاغلان دریافت نکرده، منجر به ناامیدی و کاهش کیفیت نظام آموزشی خواهد شد.
  
بی‌برنامگی و واقع‌گرا نبودن مثل تغییر 180 درجه در روند انجام آزمون دانشگاه یا برگزاری نامنظم کلاس‌های آموزشی در سطوح مختلف در شرایط کنونی یا ارائه طرحی غیرواقعی در حوزه اینترنت که علاوه بر فشار روانی بر جامعه، تمام افراد از جمله اساتید و دانشجویان را تحت تاثیر قرار خواهد داد.
  
عدم پذیرش تغییر و بروز رسانی منابع آموزشی متناسب با نیاز روز بازار: آموزش زبان اسمبلی یا سی در مقطع کارشناسی، برای افرادی که احتمالاً برای اولین بار برنامه‌نویسی را تجربه خواهند کرد، آن هم در فضایی که گزینه‌های مناسب‌تری وجود دارد. تعدادی از معروف‌ترین مؤسسات آموزشی دنیا، زبان آموزشی خود را در سال‌های اخیر تغییر داده‌اند. اگر اساتید دلسوز آشنا به بازار کار نباشند، نباید انتظار عرض اندام از دانشجویان این حوزه داشته باشیم. (پذیرش تغییر در کنار مدیریت انتظارات)
  
آموزش زبان‌های مشکل در کنار نبود بستری فعال بعنوان آزمایشگاهی برای دانشجویان تا با زبان‌های مختلف کار کرده و سنجیده شوند. بستر فعلی، بستری است که بر اساس تجربه نگارنده، برنامه‌نویسی روی کاغذ آموزش داده شده و آزمون گرفته می‌شود، بدون حتی یکبار کامپایل کردن یا اجرا کد در کلاس آموزشی دانشگاه توسط دانشجو، نتیجه‌ای جز تولید دانشجویان حافظ کد ندارد.
  
بروز رسانی در سطح بالاتر به شکل ثبت رقم ۲ مگابیت در پروانه اپراتورهای اینترنتی است آن هم در عصری که بسیاری سرعت گیگابیت را نیز رد کرده‌اند که از بسیاری جهات، مانعی در جهت افزایش کیفیت نظام آموزشی است.
  
وجود چنین نظام آموزشی باعث می‌شود تا صرفا افراد توانا و علاقمند با خود-آموزشی، بتوانند خروجی مطلوب تولید کنند. برعکس نظام فعلی، برنامه‌ها و سایت‌های مختلفی در اینترنت با همین هدف ساخته شده که به مراتب دانشجویان توانمندتری در عرصه‌های مختلف از عکاسی تا برنامه‌نویسی را پرورش داده‌اند. در دنیایی که شرکت‌های مطرح وجود گواهینامه یا مدرک دانشگاهی را از نیازمندی‌های مشاغل خود حذف کرده و بدنبال مهارت حل مسئله هستند، نگاه به دانشگاه‌های مجازی که به نحوی آینده دانشگاه‌های فعلی در مقاطع ابتدایی و طیفی از رشته‌هاست، می‌تواند الگوی مناسبی برای بروز بودن، توجه به بازار کار، آموزش پروژه محور و موارد دیگر باشد.







</div>
