Welcome Email for Skill Academy
This project contains HTML and CSS files designed for sending a welcome email to customers of the Skill Academy. The email includes a welcome message, details of a new course, a special discount code, and links to follow the academy on social media.

Files
index.html: The HTML structure of the email.

style.css: The CSS styles applied to the HTML structure.

HTML Structure
The HTML file includes various sections such as the welcome message, course information, discount details, and social media links. Below is a brief overview of the HTML code:
<!DOCTYPE html>
<html lang="fa">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width,initial-scale=1" />
    <title>خوشآمدگویی به مدرسه عالی مهارتی!</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="container">
      <div class="content-wrapper">
        <p><strong>مهارتی عزیز</strong> سلام</p>
        <p>
          «
          <strong>آموزش <span class="highlight">CCNA Wireless</span></strong>» در
          <strong><span class="highlight">Citupskill</span></strong>
          منتشر شده است.
        </p>
        <div class="highlight-wrapper">
          <a href="https://citupskill.ir" class="highlight-box">آموزش
          <span class="highlight">CCNA Wireless</span> – کلیک کنید</a>
        </div>
        <p>از آنجایی که شما، آموزش مشابهی را در این زمینه ثبت سفارش کرده بودید، 
          <span class="gift-code">کد هدیه ۷۵ درصدی</span> جهت تهیه این آموزش برای شما ارسال شده است.
        </p>
        <p><strong>مبلغ اصلی آموزش:</strong> <strike>۷۹۰,۰۰۰ تومان</strike></p>
        <p><strong>مبلغ آموزش با کد هدیه:</strong> ۱۹۷,۵۰۰ تومان</p>
        <p><strong>کد هدیه:</strong> <span class="highlight">NWSR89</span></p>
        <p><strong>مهلت استفاده از کد هدیه:</strong> سه‌شنبه، ۱۷ مهر ۱۴۰۳</p>
        <hr />
        <p class="offer-highlight">+۶۵ درصد تخفیف ویژه مدرسه عالی مهارتی برای شما:</p>
        <p class="discount-info">
          <span>علاوه بر هدیه ۷۵ درصدی آموزش فوق، شما میتوانید با کد تخفیف 
          <span class="discount-code"><strong>FDPUB65</strong></span></span> 
          آموزش‌های زیر را با 
          <span><strong>۶۵ درصد تخفیف ویژه</strong> دریافت کنید. </span>
        </p>
        <div class="courses">
          <a href="https://citupskill.ir" class="course blue">آموزش اکسل Excel</a>
          <a href="https://citupskill.ir" class="course pink">آموزش برنامه نویسی</a>
          <a href="https://citupskill.ir" class="course yellow">آموزش شبکه و امنیت</a>
          <a href="https://citupskill.ir" class="course blue">آموزش ارزهای دیجیتال</a>
          <a href="https://citupskill.ir" class="course pink">آموزش طراحی سایت</a>
          <a href="https://citupskill.ir" class="course yellow">آموزش ساخت انیمیشن</a>
          <a href="https://citupskill.ir" class="course blue">آموزش فتوشاپ و کورل</a>
          <a href="https://citupskill.ir" class="course pink">آموزش پایتون Python</a>
          <a href="https://citupskill.ir" class="course yellow">آموزش بازاریابی و تبلیغات</a>
          <a href="https://citupskill.ir" class="course blue">بورس و تحلیل تکنیکال</a>
          <a href="https://citupskill.ir" class="course pink">آموزش زبان های خارجی</a>
          <a href="https://citupskill.ir" class="course yellow">آموزش‌های رایگان</a>
          <a href="https://citupskill.ir" class="course blue">آموزش هوش مصنوعی</a>
          <a href="https://citupskill.ir" class="course pink">آموزش PowerPoint</a>
          <a href="https://citupskill.ir" class="course yellow">آموزش توسعه دهنده نرم افزار</a>
        </div>
        <hr />
        <div class="social-icons">
          <p>برای دنبال کردن ما در شبکه‌های اجتماعی:</p>
          <a href="https://www.instagram.com/cit.upskill?igsh=MXh5NjhtanN0c2k1bw==" target="_blank" rel="noopener">Instagram</a> |
          <a href="https://youtube.com/@citupskill?si=pw0Qhn7mu4TjZQ1y" target="_blank" rel="noopener">YouTube</a> |
          <a href="https://t.me/CITupskillschool" target="_blank" rel="noopener">Telegram</a>
        </div>
        <hr />
        <p class="unsubscribe">اگر نمیخواهید این ایمیل‌ها را دریافت کنید، میتوانید از طریق ارسال ایمیل به
          <a href="mailto:unsubscribe@citupskill.ir">unsubscribe@citupskill.ir</a>
        </p>
        <center>
          <a href="mailto:unsubscribe@citupskill.ir" class="unsubscribe-box">لغو اشتراک</a>
        </center>
      </div>
    </div>
  </body>
</html>

CSS Styles
The CSS file style.css is used to style the HTML structure and ensure a consistent and attractive appearance. Below is the content of the CSS file:
/* تنظیمات عمومی استایل‌ها */
/* تنظیمات عمومی استایل‌ها */
.content-wrapper {
  background-color: #ecf0f18a;
  padding: 15px;
  max-width: 680px;
  margin: auto;
  direction: rtl;
  font-family: "B Nazanin", IranNastaliq, Tahoma;
  font-size: 14pt;
  border-radius: 10px;
  color: #333;
}

/* استایل‌های مرتبط با ایکون‌های شبکه‌های اجتماعی */
.social-icons {
  text-align: center;
  margin-top: 10px; /* فاصله کمتر */
  padding: 15px;
}

.social-icons p {
  margin-bottom: 10px;
  font-size: 16px;
  font-weight: 700;
}

.social-icons a {
  font-family: "Arial", sans-serif;
  font-size: 14pt;
  color: red;
  text-decoration: none;
}

.social-icons a:hover {
  color: #89058e;
  font-weight: bold;
}

/* استایل‌های مرتبط با قسمت لغو اشتراک */
.unsubscribe {
  font-size: 11pt;
  text-align: center;
  color: #888;
  padding-top: 20px;
}

.unsubscribe a {
  color: #888;
  text-decoration: none;
  font-family: "Arial", sans-serif;
  font-size: 10pt;
}

.unsubscribe-box {
  display: inline-block;
  padding: 10px 20px;
  background-color: #888;
  color: #fff;
  font-size: 12pt;
  border-radius: 10px;
  text-decoration: none;
  font-family: "Arial", sans-serif;
}

/* تنظیمات کلی استایل‌های عمومی */
.container {
  background-color: #ecf0f18a;
  padding: 20px;
  border-radius: 10px;
}

body {
  background-color: #fff;
  text-align: right;
  direction: rtl;
}

.highlight-box {
  display: inline-block;
  padding: 10px 20px;
  background-color: #89058e;
  color: white;
  font-size: 12pt; /* اندازه فونت کوچک‌تر */
  font-family: "Arial", sans-serif;
  border-radius: 10px;
  text-decoration: none;
  font-weight: bold;
}

/* استایل‌های مرتبط با عناصر برجسته */
p strong {
  font-weight: bold;
  font-family: "Arial", sans-serif;
  color: #89058e;
}

.offer-highlight {
  font-size: 16pt;
  font-family: "Arial", sans-serif;
  color: red;
  font-weight: bold;
}

.gift-code {
  font-size: 18pt;
  color: red;
  font-weight: bold;
}

strike {
  color: #888;
}

/* استایل‌های مربوط به دوره‌های آموزشی */
.courses {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  margin-top: 10px; /* کاهش فاصله */
}

.course {
  width: 150px; /* عرض مربعات */
  margin: 5px; /* فاصله بین مربعات */
  padding: 8px; /* اندازه مربعات */
  border-radius: 5px;
  color: black;
  font-weight: bold;
  text-align: center;
  text-decoration: none;
  font-family: "Arial", sans-serif;
}

.yellow {
  background-color: #ffeb3b; /* رنگ زرد */
  line-height: 50px;
}

.pink {
  background-color: #d5006d; /* French pink */
  line-height: 60px;
}

.blue {
  background-color: #87ceeb; /* آبی روشن */
  line-height: 100px;
}
/* تنظیمات عمومی استایل‌ها */
.content-wrapper {
  background-color: #ecf0f18a;
  padding: 15px;
  max-width: 680px;
  margin: auto;
  direction: rtl;
  font-family: "B Nazanin", IranNastaliq, Tahoma;
  font-size: 14pt;
  border-radius: 10px;
  color: #333;
}

/* استایل‌های مرتبط با ایکون‌های شبکه‌های اجتماعی */
.social-icons {
  text-align: center;
  margin-top: 10px; /* فاصله کمتر */
  padding: 15px;
}

.social-icons p {
  margin-bottom: 10px;
  font-size: 16px;
  font-weight: 700;
}

.social-icons a {
  font-family: "Arial", sans-serif;
  font-size: 14pt;
  color: red;
  text-decoration: none;
}

.social-icons a:hover {
  color: #89058e;
  font-weight: bold;
}

/* استایل‌های مرتبط با قسمت لغو اشتراک */
.unsubscribe {
  font-size: 11pt;
  text-align: center;
  color: #888;
  padding-top: 20px;
}

.unsubscribe a {
  color: #888;
  text-decoration: none;
  font-family: "Arial", sans-serif;
  font-size: 10pt;
}

.unsubscribe-box {
  display: inline-block;
  padding: 10px 20px;
  background-color: #888;
  color: #fff;
  font-size: 12pt;
  border-radius: 10px;
  text-decoration: none;
  font-family: "Arial", sans-serif;
}

/* تنظیمات کلی استایل‌های عمومی */
.container {
  background-color: #ecf0f18a;
  padding: 20px;
  border-radius: 10px;
}

body {
  background-color: #fff;
  text-align: right;
  direction: rtl;
}

.highlight-box {
  display: inline-block;
  padding: 10px 20px;
  background-color: #89058e;
  color: white;
  font-size: 12pt; /* اندازه فونت کوچک‌تر */
  font-family: "Arial", sans-serif;
  border-radius: 10px;
  text-decoration: none;
  font-weight: bold;
}

/* استایل‌های مرتبط با عناصر برجسته */
p strong {
  font-weight: bold;
  font-family: "Arial", sans-serif;
  color: #89058e;
}

.offer-highlight {
  font-size: 16pt;
  font-family: "Arial", sans-serif;
  color: red;
  font-weight: bold;
}

.gift-code {
  font-size: 18pt;
  color: red;
  font-weight: bold;
}

strike {
  color: #888;
}

/* استایل‌های مربوط به دوره‌های آموزشی */
.courses {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  margin-top: 10px; /* کاهش فاصله */
}

.course {
  width: 150px; /* عرض مربعات */
  margin: 5px; /* فاصله بین مربعات */
  padding: 8px; /* اندازه مربعات */
  border-radius: 5px;
  color: black;
  font-weight: bold;
  text-align: center;
  text-decoration: none;
  font-family: "Arial", sans-serif;
}

.yellow {
  background-color: #ffeb3b; /* رنگ زرد */
  line-height: 50px;
}

.pink {
  background-color: #d5006d; /* French pink */
  line-height: 60px;
}

.blue {
  background-color: #87ceeb; /* آبی روشن */
  line-height: 100px;
}

Usage
Include the index.html file in your email template.

Link the style.css file in the <head> section of your HTML.

Customize the content as needed to fit your specific needs.

Purpose
This code is designed for sending professional and visually appealing welcome emails to customers. It includes all necessary elements such as the welcome message, course details, special discount offers, and social media links.
