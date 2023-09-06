# GoogleBard-RTL-Style
A few lines of CSS to change font of Persian/Arabic Languages output!

### Code
```CSS
@import url('https://fonts.googleapis.com/css2?family=Rubik&display=swap');

.query-text,
.textarea[dir=rtl],
.model-response-text p,
.model-response-text ul li,
.model-response-text ol li,
.icon-and-prompt-container > span,
.conversation-title {
	font-family: 'Rubik', sans-serif !important;
	font-size:14px;
}
```

## Usage
Depend on your browser, You can use one of plugins/extensions to inject CSS code:
* Google Chrome: [User JavaScript and CSS](https://chrome.google.com/webstore/detail/user-javascript-and-css/nbhcbdghjpllgmfilhnhkllmkecfmpld)
* Microsoft Edge: [Code Injector](https://microsoftedge.microsoft.com/addons/detail/code-injector/kgmlfocfgenookigofalapefagndnlnc)
* Mozilla Firefox: [Custom Style Script](https://addons.mozilla.org/en-US/firefox/addon/custom-style-script/)
* ... and many other extensions! (Search your Browser name with this keywords: "add custom CSS", "inject CSS", ...)

## تغییر فونت چت‌بات Google Bard (راهنمای فارسی)
این، چند خط استایل CSS برای چت‌بات [Google Bard](https://bard.google.com) است برای کسانی که می‌خواهند ظاهر زیباتری را با تغییر فونت محیط گفتگوی آن تجربه کنند. 

### طریقه استفاده
کافی است بسته به نوع مرورگرتان، از یکی از افزونه‌های زیر جهت واردکردن کد CSS به صفحه Google Bard استفاده کنید و کد CSS بالا را با استفاده از افزونه به صفحه https://bard.google.com اضافه کنید:
* گوگل کروم: [User JavaScript and CSS](https://chrome.google.com/webstore/detail/user-javascript-and-css/nbhcbdghjpllgmfilhnhkllmkecfmpld)
* مایکروسافت اج: [Code Injector](https://microsoftedge.microsoft.com/addons/detail/code-injector/kgmlfocfgenookigofalapefagndnlnc)
* موزیلا فایرفاکس: [Custom Style Script](https://addons.mozilla.org/en-US/firefox/addon/custom-style-script/)
* ... و بسیاری افزونه‌های دیگر! (کافی‌است نام مرورگرتان را با کلمات کلیدی CSS injector یا custom CSS و مانند اینها جستجو کنید).

در این استایل از فونت [Rubik](https://fonts.google.com/specimen/Rubik?subset=arabic) استفاده شده است.
