<div style="line-height: normal; overflow: hidden">
                    <h1><strong>Graph visualization</strong></h1>

<h3 dir="rtl"><span style="font-size:18px">لایبرری های زیادی برای نمایش گراف وجود دارد، شما میتوانید برای مطالعه بیشتر به این <a href="https://medium.com/@Elise_Deux/the-list-of-graph-visualization-libraries-7a7b89aab6a6">صفحه</a> بروید.&nbsp;<br>
طبق تحقیقی که تیم فرانت ما داشته بهترین لایبرری موجود برای پیاده سازی اهداف تیم ستاره لایبرری <strong>ogma </strong>است. برای آشنایی بیشتر با&nbsp;این محصول میتوانید به این <a href="https://doc.linkurio.us/ogma/latest/quickstart.html">سایت</a> مراجعه کنید.</span></h3>

<h3 dir="rtl"><img alt="Features" src="https://i0.wp.com/linkurio.us/wp-content/uploads/2020/04/image4.gif?fit=1155%2C678&ssl=1&resize=350%2C200"></h3>

<h3 dir="rtl"><span style="font-size:18px">تصویر بالا یک گراف کوچک است که به کمک اگما نمایش داده شده است. شاید برای شما سوال پیش بیاید که نمایش گراف چه اهمیتی دارد، و چرا نرم افزار هایی نظیر <strong>Gephi </strong>برای زیبا کشیدن گراف بوجود آمده است؟(توصیه میشود این نرم افزار را نصب کنید و چیدمان های مختلف آن را امتحا کنید از جمله چیدمان های circular آن را که پیچیدگی زیادی دارند.)</span></h3>

<h3 dir="rtl"><img alt="Features" src="https://gephi.org/images/screenshots/preview1.png"></h3>

<h3 dir="rtl"><span style="font-size:18px">چیدمانی خوب است که بتواند راس های مرتبط را کنار هم و راس های نامرتبط از هم را با فاصله از هم قرار دهد، تا بتوان با یک نگاه اطلاعات زیادی بدست آورد. به طور مثال وقتی شما دو راس خاص را در نظر دارید و میخواهید ببینید این دو راس چه میزان به هم مرتبط اند کافی است یک چیدمان مناسب استفاده کنید، محصول ستاره هم از چند چیدمان مهم استفاده میکند.</span></h3>

<h3 dir="rtl"><span style="font-size:18px">در ابتدا <strong>ogma </strong>را داخل انگولار امتحان کنید و برای پیاده سازی آن به providing-ogma مراجعه کنید.</span></h3>

<h3 dir="rtl"><span style="font-size:18px">سپس یک گراف دلخواه را در آن نمایش دهید و توصیه میکنم برای اطمینان از صحت پیاده سازی خود یک <strong>Button </strong>بگذارید که با فشرده شدن آن یک گراف رندوم جدید در صفحه گراف بوجود بیاید.</span></h3>

<h3 dir="rtl"><span style="font-size:18px"><strong>پیشنهاد</strong>: برای زیبا تر شدن المنت های <strong>html </strong>خود و زیبایی <strong>template </strong>خود از لایبرری های css مانند <strong>semantic ui</strong> , <strong>bootstrapt </strong>استفاده کنید و با توجه به سادگی که <strong>semantic </strong>دارد، آن را بیشتر توصیه میکنیم.</span></h3>

<h3 dir="rtl"><span style="font-size:18px">برای اضافه شدن این لایبرری ها به پروژه انگولار خود <strong>cdn </strong>آن را از اینترنت بگیرید و در <strong>head </strong>فایل index.html پروژه انگولار خود قرار دهید.</span></h3>

<h3 dir="rtl"><span style="font-size:18px">به طور مثال <strong>cdn </strong>سمنتیک این است:</span></h3>

<h3>&nbsp;</h3>

<h3><code>&lt;script src="https://code.jquery.com/jquery-3.1.1.min.js" crossorigin="anonymous"&gt;&lt;/script&gt;<br>
&lt;link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/semantic-ui@2.4.2/dist/semantic.min.css"&gt;<br>
&lt;script src="https://cdn.jsdelivr.net/npm/semantic-ui@2.4.2/dist/semantic.min.js"&gt;&lt;/script&gt;</code></h3>

<h3 dir="rtl"><span style="font-size:18px">شما باید بعد از پیاده سازی اگما بتوانید کارهای زیر را انجام دهید:</span></h3>

<h3 dir="rtl"><span style="font-size:18px">1- روی یک راس&nbsp;کلیک کرده و حالت <strong>selected </strong>آن را سویچ کنید.</span></h3>

<h3 dir="rtl"><span style="font-size:18px">2- با موس بتوانید تمامی رئوس <strong>selected </strong>را جا به جا کنید.</span></h3>

<h3 dir="rtl">&nbsp;</h3>

<h3 dir="rtl"><span style="font-size:18px">در فاز های بعدی شما باید بتوانید کار های انیمیشنی بیشتری در <strong>ogma </strong>انجام دهید مثلا رنگ یال هارا تغییر دهید و در آن ها <strong>flow </strong>ایجاد کنید و یا در راس ها <strong>pulse </strong>ایجاد کنید و بهتر است برای یادگیری آن ها در این فاز با <strong>api&nbsp;</strong>های اگما آشنا شوید، به طور مثال توابع <strong>setAttributes </strong>میتوانید نقش مهمی در این انیمیشن ها داشته باشد که شما میتوانید جزئیات آن را در این <a href="https://doc.linkurio.us/ogma/latest/api.html"><strong>صفحه </strong></a>دنبال کنید.</span></h3>

<h3 dir="rtl"><span style="font-size:18px"><strong>پیشنهاد:&nbsp;</strong>زمان هایی که میخواهید به کاربر پیامی نشان بدهید و یا مقداری را از او بگیرید میتوانید از&nbsp;لایبرری Sweet alert 2 استفاده کنید، این لایبرری قدرتمند با فیچر های زیادی که در اختیار شما قرار میدهد کار را بسیار ساده میکند.</span></h3>

<h3 dir="rtl"><span style="font-size:18px">در نهایت شما باید بتوانید اطلاعات گراف را به کمک <strong>HttpClient </strong>از سرور <strong>backend </strong>بگییرید و با اگما نمایش بدهید، پس حواستان به نحوه پیاده سازی باشد تا بعدا&nbsp;به مشکل نخورید. در فاز های بعدی هم سعی میکنم لایبرری های دیگرری را که به نظرم مفید هستند معرفی کنم.</span></h3>
                </div>
