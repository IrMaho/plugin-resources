<div dir="rtl" align='center'>

# منابع متن‌باز برای توسعه پلاگین و ویجت فیگما

_مجموعه‌ای از پلاگین‌ها، ویجت‌ها و دیگر منابع متن‌باز برای فیگما + فیگ‌جم که در گیت‌هاب به اشتراک گذاشته شده‌اند._

</div>

> _از پول ریکوئست‌ها استقبال می‌شود. لطفاً قبل از باز کردن پول ریکوئست، [راهنمای مشارکت](CONTRIBUTING.md) را مطالعه کنید._

## سلب مسئولیت:

منابع ارائه‌شده با هدف کمک به توسعه پلاگین و ویجت فیگما گردآوری شده‌اند. این منابع به هیچ وجه توسط فیگما تأیید یا حمایت مالی نشده‌اند. **لطفاً قبل از استفاده از هر یک از منابع لیست‌شده، بررسی‌های لازم و امنیتی خود را انجام دهید.**

---

## فهرست مطالب

- [منابع](#resources) -- منابعی برای ساخت پلاگین‌ها و ویجت‌ها
  - [قالب‌های اولیه](#starter-templates)
  - [کامپوننت‌های سیستم طراحی](#design-system-components)
  - [توابع کمکی](#helper-functions)
  - [ابزارهای انتشار CI/CD](#cicd-release-tools)
- [پلاگین‌ها](#plugins) -- کد منبع پلاگین‌ها
  - [دسترسی‌پذیری](#accessibility)
  - [رنگ](#color)
  - [لینترهای طراحی](#design-linters)
  - [سیستم‌های طراحی](#design-systems)
  - [ابزارهای توسعه‌دهندگان](#developer-tools)
  - [خروجی گرفتن (Export)](#export)
  - [آیکون‌ها](#icons)
  - [نقشه‌ها](#maps)
  - [سازماندهی](#organization)
  - [ریسپانسیو (واکنش‌گرا)](#responsive)
  - [متن](#text)
  - [ابزارهای کاربردی](#utilities)
  - [متفرقه](#misc)
- [ویجت‌ها](#widgets) -- کد منبع ویجت‌ها

---

## منابع

مجموعه‌ای از منابع برای کمک به تسریع فرآیند توسعه پلاگین‌ها و ویجت‌های فیگما.

---

### قالب‌های اولیه

این قالب‌های اولیه، کدهای آماده (boilerplate) مورد نیاز برای توسعه پلاگین‌ها و ویجت‌ها را بسته‌بندی کرده‌اند.

#### Create Figma Plugin

[کد منبع](https://github.com/yuanqing/create-figma-plugin) · [MIT](https://github.com/yuanqing/create-figma-plugin/blob/main/LICENSE.md)

🔋 جعبه ابزار جامع برای توسعه پلاگین‌ها و ویجت‌ها برای فیگما و فیگ‌جم

---

#### FigPlug

[کد منبع](https://github.com/rsms/figplug) · [MIT](https://github.com/rsms/figplug/blob/master/LICENSE)

figplug یک برنامه کوچک برای ساخت پلاگین‌های فیگما است. این برنامه تمام چیزهایی که برای اکثر پروژه‌ها نیاز دارید را ارائه می‌دهد: تایپ‌اسکریپت، ری‌اکت/JSX، باندل کردن دارایی‌ها، تولید مانیفست پلاگین و غیره.

---

#### Figma Plugin React Template

[کد منبع](https://github.com/nirsky/figma-plugin-react-template) · بدون لایسنس

با استفاده از این قالب و ابزارها، پلاگین فیگمای خود را به سرعت شروع کنید.

---

#### Figsvelte

[کد منبع](https://github.com/thomas-lowry/figsvelte) · [MIT](https://github.com/thomas-lowry/figsvelte/blob/master/LICENSE)

یک قالب آماده برای ساخت پلاگین‌های فیگما با استفاده از Svelte.

---

#### Figma Plugin Template

[کد منبع](https://github.com/tomquinonero/figma-plugin-template) · بدون لایسنس

یک قالب پلاگین فیگما با استفاده از Svelte. با پشتیبانی از SCSS و Typescript.

---

#### fwidgets

[کد منبع](https://github.com/fwextensions/fwidgets) · [MIT](https://github.com/fwextensions/fwidgets/blob/main/LICENSE)

سریع‌ترین راه برای ساخت رابط کاربری پلاگین فیگما — بدون حتی یک خط کدنویسی برای UI.

---

**[⬆ بازگشت به فهرست مطالب](#table-of-contents)**

### کامپوننت‌های سیستم طراحی

#### Figma Kit

[کد منبع](https://github.com/tigranpetrossian/figma-kit) · [MIT](https://github.com/tigranpetrossian/figma-kit/blob/beta/LICENSE)

مجموعه‌ای گسترده از کامپوننت‌های ری‌اکت برای ساخت پلاگین‌های فیگما. آماده برای UI3، با پشتیبانی درجه یک از Tailwind.

#### Figma Plugin DS Svelte

[کد منبع](https://github.com/thomas-lowry/figma-plugin-ds-svelte) · [MIT](https://github.com/thomas-lowry/figma-plugin-ds-svelte/blob/master/LICENSE)

کامپوننت‌های سیستم طراحی پلاگین فیگما که با Svelte ساخته شده‌اند.

---

#### Figma Plugin DS

[کد منبع](https://github.com/thomas-lowry/figma-plugin-ds) · [MIT](https://github.com/thomas-lowry/figma-plugin-ds/blob/master/LICENSE)

یک سیستم طراحی کوچک و سبک برای استفاده در پلاگین‌های فیگما.

---

#### React Figma Plugin DS

[کد منبع](https://github.com/alexandrtovmach/react-figma-plugin-ds) · [MIT](https://github.com/alexandrtovmach/react-figma-plugin-ds/blob/master/LICENSE)

کامپوننت‌های ری‌اکت سیستم طراحی فیگما.

---

**[⬆ بازگشت به فهرست مطالب](#table-of-contents)**

### توابع کمکی

#### figma-await-ipc

[کد منبع](https://github.com/fwextensions/figma-await-ipc) · [MIT](https://github.com/fwextensions/figma-await-ipc/blob/main/LICENSE)

یک جایگزین ساده و قابل `await` برای `postMessage()` در پلاگین‌های فیگما.

---

#### Figma Plugin Helpers

[کد منبع](https://github.com/figma-plugin-helper-functions/figma-plugin-helpers) · بدون لایسنس

مجموعه‌ای از توابع کمکی مفید برای ایمپورت کردن به پروژه پلاگین فیگمای شما.

**[⬆ بازگشت به فهرست مطالب](#table-of-contents)**

---

### ابزارهای انتشار CI/CD

#### figcd

[کد منبع](https://github.com/parrot-global/figcd) · [MIT](https://github.com/parrot-global/figcd/blob/main/LICENSE)

یک ابزار CLI برای تحویل مستمر و یکپارچه پلاگین‌های فیگما. با الهام از Fastlane، figcd فرآیند دستی انتشار پلاگین‌های فیگما را ساده‌سازی می‌کند.

#### figma-plugin-deploy

[کد منبع](https://github.com/typper-io/figma-plugin-deploy) · [MIT](https://github.com/typper-io/figma-plugin-deploy/blob/main/LICENSE)

یک GitHub Action برای خودکارسازی فرآیند استقرار پلاگین‌های فیگما. این اکشن کل فرآیند استقرار، از احراز هویت تا انتشار را مدیریت می‌کند و تحویل مستمر پلاگین‌های فیگما را یکپارچه و کارآمد می‌سازد.

**[⬆ بازگشت به فهرست مطالب](#table-of-contents)**

---

## پلاگین‌ها

مجموعه‌ای از پلاگین‌هایی که به صورت متن‌باز منتشر شده‌اند. می‌توانید این پلاگین‌ها را نصب، بررسی یا برای میزبانی نسخه خود، فورک کنید.

---

### دسترسی‌پذیری

#### Include

[کد منبع](https://github.com/eBay/figma-include-accessibility-annotations) · [پلاگین](https://www.figma.com/community/plugin/1208180794570801545/includeaccessibility-annotations) · [APACHE LICENSE 2.0](https://github.com/eBay/figma-include-accessibility-annotations/blob/main/LICENSE)

Include یک پلاگین فیگما است که حاشیه‌نویسی برای دسترسی‌پذیری (a11y) را ساده می‌کند. این کار را برای طراحان جهت مشخص کردن و برای توسعه‌دهندگان جهت درک نیازمندی‌ها آسان‌تر می‌کند.

---

#### Polychrom

[کد منبع](https://github.com/evilmartians/figma-polychrom) · [پلاگین](https://www.figma.com/community/plugin/1281280685402026529/polychrom) · [MIT](https://github.com/evilmartians/figma-polychrom/blob/main/LICENSE)

Polychrom یک پلاگین فیگما است که به کاربران اجازه می‌دهد سطح کنتراست بین لایه‌های انتخاب‌شده را اندازه‌گیری کرده و بازخورد فوری دریافت کنند. این پلاگین از متد APCA برای تعیین کنتراست استفاده می‌کند، پیشنهاداتی برای اندازه متن ارائه می‌دهد و رنگ‌ها را به فرمت‌های مختلفی از جمله OKLCH، RGB و HEX برای کپی آسان کد CSS تبدیل می‌کند.

---

#### zebra

[کد منبع](https://github.com/danhollick/zebra) · [پلاگین](https://www.figma.com/c/plugin/806578669827234193/zebra) · بدون لایسنس

Zebra یک ابزار سریع و سبک برای بررسی کنتراست رنگ است.

---

**[⬆ بازگشت به فهرست مطالب](#table-of-contents)**

### رنگ

#### Chroma

[کد منبع](https://github.com/kaleidocode-app/chroma) · [پلاگین](https://www.figma.com/c/plugin/739237058450529919/Chroma-Colors) · [MIT](https://github.com/kaleidocode-app/chroma/blob/master/LICENSE)

یک پلاگین فیگما برای ساخت استایل‌های رنگی به صورت دسته‌ای از آیتم‌های انتخاب شده.

---

#### Dominant Color

[کد منبع](https://github.com/brianlovin/figma-dominant-color-toolkit) · [پلاگین](https://www.figma.com/community/plugin/744725347356614754/Dominant-Color-Toolkit-%F0%9F%8E%A8) · [MIT](https://github.com/brianlovin/figma-dominant-color-toolkit/blob/main/LICENSE)

یک پالت رنگی از یک تصویر تولید کنید تا به طور جادویی طرح‌های خود را پر کنید.

---

#### Easing Gradient

[کد منبع](https://github.com/alexwidua/figma-easing-gradients) · [پلاگین](https://www.figma.com/c/plugin/781591244449826498/Easing-Gradient) · [MIT](https://github.com/alexwidua/figma-easing-gradients/blob/master/LICENSE)

گرادینت‌های زیبا و نرم در فیگما بسازید. گرادینت‌های خطی اغلب در نقاط شروع و/یا پایان خود لبه‌های تیزی دارند. این پلاگین با افزودن نقاط توقف به گرادینت، توابع easing را شبیه‌سازی می‌کند.

---

#### Lucidi

[کد منبع](https://github.com/dimuuu/lucidi) · [پلاگین](https://www.figma.com/community/plugin/1235943434768675768) · [CC0](https://github.com/dimuuu/lucidi/blob/main/LICENSE)

استایل‌های شفافیت (opacity) را بر اساس استایل‌های رنگی اصلی و مات ایجاد و همگام‌سازی کنید.

---

#### Navigator

[کد منبع](https://github.com/kaleidocode-app/navigator) · [پلاگین](https://www.figma.com/c/plugin/739558587628004077/Navigator) · بدون لایسنس

روشی آسان برای پیدا کردن و اعمال استایل‌های رنگی از سند فعلی شما.

---

#### system.colors()

[کد منبع](https://github.com/thelittlewonder/system.colors) · [پلاگین](https://www.figma.com/community/plugin/832358256915224919) · بدون لایسنس

پالت‌های رنگی از سیستم‌های طراحی محبوب را مستقیماً به فایل خود وارد کنید.

---

#### Valor

[کد منبع](https://github.com/kolebayev/valor-figma-plugin) · [پلاگین](https://www.figma.com/community/plugin/798588768596541799/Valor) · بدون لایسنس

پالت‌های رنگی موجود یا جدید را در سیستم طراحی خود تجسم کنید یا لیستی از متغیرهای رنگی از پالت‌های رنگی تولید کنید.

---

**[⬆ بازگشت به فهرست مطالب](#table-of-contents)**

### لینترهای طراحی

#### Design Lint

[کد منبع](https://github.com/destefanis/design-lint) · [پلاگین](https://www.figma.com/c/plugin/801195587640428208/Design-Lint) · [MIT](https://github.com/destefanis/design-lint/blob/master/LICENSE)

خطاهای موجود در طرح‌های خود را به صورت رایگان پیدا و اصلاح کنید.

---

**[⬆ بازگشت به فهرست مطالب](#table-of-contents)**

### سیستم‌های طراحی

#### Design Tokens

[کد منبع](https://github.com/lukasoppermann/design-tokens) · [پلاگین](https://www.figma.com/community/plugin/888356646278934516/design-tokens) · [MIT](https://github.com/lukasoppermann/design-tokens/blob/main/LICENSE)

Design Tokens یک پلاگین فیگما است که به شما امکان می‌دهد توکن‌های طراحی را به فرمت JSON خروجی بگیرید و آن‌ها را برای وب، iOS و اندروید به زبان‌ها و پلتفرم‌های مختلف تبدیل کنید.

---

#### Styler

[کد منبع](https://github.com/andrei-inc/Styler) · [پلاگین](https://www.figma.com/community/plugin/820660579767995949/Styler) · [MIT](https://github.com/andreincu/Styler/blob/master/LICENSE)

Styler یک پلاگین فیگما است که روشی کارآمدتر برای ساخت و نگهداری سیستم‌های طراحی ارائه می‌دهد.

---

#### Themer

[کد منبع](https://github.com/thomas-lowry/themer) · [پلاگین](https://www.figma.com/c/plugin/731176732337510831/Themer) · [MIT](https://github.com/thomas-lowry/themer/blob/master/LICENSE)

پلاگینی برای فیگما که به شما امکان می‌دهد بین استایل‌هایی با نام یکسان از کتابخانه‌های منتشر شده مختلف جابجا شوید.

---

#### Tokens Studio for Figma

[کد منبع](https://github.com/six7/figma-tokens) · [پلاگین](https://www.figma.com/community/plugin/843461159747178978/Figma-Tokens) · [MIT](https://github.com/tokens-studio/figma-plugin/blob/main/LICENSE.md)

Tokens Studio for Figma یک پلاگین برای فیگما است که به شما امکان تعریف و استفاده از توکن‌های طراحی در فیگما را می‌دهد. شما می‌توانید توکن‌های طراحی خود را در فرمت JSON ذخیره کنید، آن‌ها را با یک ارائه‌دهنده همگام‌سازی مانند گیت‌هاب سینک کنید و حتی برای ویژگی‌هایی که هنوز در فیگما پشتیبانی بومی ندارند، مانند borderRadius یا spacing، توکن تعریف کنید.

---

**[⬆ بازگشت به فهرست مطالب](#table-of-contents)**

### ابزارهای توسعه‌دهندگان

#### Figma to Boostrap 5 Plugin

[کد منبع](https://github.com/gabrielrbarbosa/figma-to-bootstrap-plugin) · [پلاگین](https://www.figma.com/community/plugin/1287660587112027215/figma-to-bootstrap-5-plugin) · [GPLv3](https://github.com/gabrielrbarbosa/figma-to-bootstrap-plugin/blob/main/LICENSE)

طرح‌های فیگمای خود را به قطعه‌ کدهای بوت‌استرپ ۵ تبدیل کنید! این پلاگین گرید، borderها و ابزارهای کاربردی بوت‌استرپ ۵ را تولید می‌کند.

---

#### Figma Tailwindcss

[کد منبع](https://github.com/jan-dh/figma-tailwindcss) · [پلاگین](https://www.figma.com/c/plugin/785619431629077634/Figma-Tailwindcss) · بدون لایسنس

Figma Tailwindcss به شما امکان می‌دهد جنبه‌هایی از یک طرح ساخته‌شده در فیگما را به یک فایل تم جاوااسکریپت خروجی بگیرید که به راحتی با Tailwindcss قابل استفاده است.

---

#### Kaleidocode

[کد منبع](https://github.com/kaleidocode-app/kaleidocode) · [پلاگین](https://www.figma.com/c/plugin/736060893363678891/Kaleidocode) · بدون لایسنس

تم‌های VS Code را به کتابخانه‌های رنگی فیگما تبدیل کنید، تم‌های جدید از طریق JSON بسازید و تم‌ها را به طور خودکار جابجا کنید.

---

#### Tailwind CSS

[کد منبع](https://github.com/impulse/tailwindcss-figma-plugin) · [پلاگین](https://www.figma.com/community/plugin/738806869514947558/Tailwind-CSS) · [MIT](https://github.com/ecklf/tailwindcss-figma-plugin/blob/main/LICENSE)

استایل‌ها و چیزهای جالب دیگر را مستقیماً از فایل کانفیگ tailwind خود تولید کنید.

---

**[⬆ بازگشت به فهرست مطالب](#table-of-contents)**

### خروجی گرفتن (Export)

#### Android Resources Export

[کد منبع](https://github.com/Ashung/android-resources-export-figma) · [پلاگین](https://www.figma.com/c/plugin/735452896889481850/Android-Resources-Export) · [MIT](https://github.com/Ashung/android-resources-export-figma/blob/master/LICENSE.md)

خروجی PNG در اندازه‌های مختلف از slice یا لایه قابل خروجی گرفتن، با ساختار پوشه ثابت (drawable-xhdpi و غیره) و نام معتبر.

---

#### Figma Export

[کد منبع](https://github.com/brianlovin/figma-export-zip) · [پلاگین](https://www.figma.com/c/plugin/747228167548695118/Export-.zip) · بدون لایسنس

به راحتی دارایی‌ها (assets) را از فیگما مستقیماً به یک فایل .zip خروجی بگیرید.

---

#### Image Minifire

[کد منبع](https://github.com/zendyani/figma-image-compression) · [پلاگین](https://www.figma.com/community/plugin/1284557222547216612/image-minifire) · [MIT](https://github.com/zendyani/figma-image-compression/blob/main/LICENSE)

Image Minifire به کاربر اجازه می‌دهد تا تصاویر یک فریم انتخاب‌شده در فیگما را فشرده و خروجی بگیرد.

---

#### Lazy Export

[کد منبع](https://github.com/kocheck/Lazy-Export) · [پلاگین](https://www.figma.com/community/plugin/824059814042167296/Lazy-Export) · [MIT](https://github.com/kocheck/Lazy-Export/blob/production/LICENSE)

Lazy Export به کاربر اجازه می‌دهد تا به سرعت تنظیمات خروجی پیش‌فرض را به اشیاء انتخاب‌شده در فیگما اعمال کند.

---

#### Figma Sprite Generator

[کد منبع](https://github.com/omidnikrah/figma-sprite-generator) · [پلاگین](https://www.figma.com/community/plugin/1424139256012895014/goodway-sprite) · [MIT](https://github.com/omidnikrah/figma-sprite-generator/blob/main/LICENSE)

یک پلاگین فیگما برای تولید sprite sheet و فایل‌های JSON از آیکون‌های انتخاب شده.

---

**[⬆ بازگشت به فهرست مطالب](#table-of-contents)**

### آیکون‌ها

#### 3dicons

[کد منبع](https://github.com/realvjy/3dicons-figma) • [پلاگین](https://www.figma.com/community/plugin/1107546399747513238) • [MIT](https://github.com/realvjy/3dicons-figma/blob/main/LICENSE)

مجموعه‌ای با بیش از ۱۴۰۰ آیکون سه‌بعدی. می‌توانید به سرعت در فایل‌های فیگما یا فیگ‌جم از آن‌ها استفاده کنید. آیکون‌ها را می‌توان بر اساس رنگ و زاویه جستجو و فیلتر کرد.

---

#### Feather Icons

[کد منبع](https://github.com/feathericons/figma-feather) · [پلاگین](https://www.figma.com/c/plugin/744047966581015514/Feather-Icons) · بدون لایسنس

دسترسی سریع به آیکون‌های Feather در فیگما.

---

#### Figma Text to Icon

[کد منبع](https://github.com/lichin-lin/figma-text-to-icon) • بدون لایسنس

یک پلاگین فیگما که از متن، آیکون تولید می‌کند و با Next.js، Tailwind، Shadcn UI و Replicate API ساخته شده است.

---

#### Iconify

[کد منبع](https://github.com/iconify/iconify-figma) • [پلاگین](https://www.figma.com/community/plugin/735098390272716381/Iconify) • [APACHE LICENSE 2.0](https://github.com/iconify/iconify-figma/blob/main/license.txt)

آیکون‌های Material Design، FontAwesome، Jam Icons، EmojiOne، Twitter Emoji و بسیاری دیگر (بیش از ۱۰۰ مجموعه آیکون شامل بیش از ۱۰۰,۰۰۰ آیکون) را به عنوان اشکال وکتور به سند فیگما وارد کنید.

---

**[⬆ بازگشت به فهرست مطالب](#table-of-contents)**

### نقشه‌ها

#### Figma Map Maker

[کد منبع](https://github.com/kawamurakazushi/figma-map-maker) · [پلاگین](https://www.figma.com/c/plugin/731312569747199418/Map-Maker) · [MIT](https://github.com/kawamurakazushi/figma-sort-it/blob/master/LICENSE)

پلاگین فیگما برای تولید نقشه، با پشتیبانی از Google Maps و Mapbox.

---

#### Figmap

[کد منبع](https://github.com/ergum/figmap) · [پلاگین](https://www.figma.com/community/plugin/937760472566581732) · بدون لایسنس

نقشه‌ها و نشانگرهای کاملاً قابل سفارشی‌سازی برای فیگما.

---

#### Placemark Figma Plugin

[کد منبع](https://github.com/placemark/figma-plugin) · [پلاگین](https://www.figma.com/community/plugin/1189962635826293304/Placemark) · بدون لایسنس

با فیگما نقشه بسازید.

---

**[⬆ بازگشت به فهرست مطالب](#table-of-contents)**

### سازماندهی

#### Figma Format

[کد منبع](https://github.com/kawamurakazushi/figma-format) · [پلاگین](https://www.figma.com/c/plugin/732774680197470712/Figma-Format) · [MIT](https://github.com/kawamurakazushi/figma-format/blob/master/LICENSE)

Figma Format به شما اجازه می‌دهد تا با گروه‌بندی فریم‌ها بر اساس نامشان، بوم (canvas) خود را قالب‌بندی کنید.

---

#### GridGen · Automatic Table Generator

[کد منبع](https://github.com/gnawx/figma-plugins/tree/master/packages/figma-gridgen) · [پلاگین](https://www.figma.com/c/plugin/796759972238579874/GridGen) · [MIT](https://github.com/stevahnes/figma-plugins/blob/master/LICENSE)

با استفاده از مستطیل‌ها، خطوط و متون داخلی فیگما، جداولی با لایه‌های منظم تولید می‌کند.

---

#### Project Scaffold

[کد منبع](https://github.com/tushar7d/Project-Scaffold-Figma-Plugin) · [پلاگین](https://www.figma.com/c/plugin/747372158567878238/Project-Scaffold) · بدون لایسنس

این پلاگین تنها با یک کلیک یک ساختار کلی (Scaffold) برای پروژه طراحی محصول شما تولید می‌کند.

---

#### Super Tidy

[کد منبع](https://github.com/basiclines/figma-super-tidy) · [پلاگین](https://www.figma.com/c/plugin/731260060173130163/Super-Tidy) · [MIT](https://github.com/basiclines/figma-super-tidy/blob/master/LICENSE)

یک پلاگین فیگما برای تراز کردن، تغییر نام و ترتیب‌دهی آسان فریم‌های شما بر اساس موقعیت‌شان در بوم.

---

**[⬆ بازگشت به فهرست مطالب](#table-of-contents)**

### ریسپانسیو (واکنش‌گرا)

#### Responsify

[کد منبع](https://github.com/brianlovin/figma-responsify) · [پلاگین](https://www.figma.com/c/plugin/743654854885744527/Responsify-%E2%9A%A1%EF%B8%8F) · بدون لایسنس

یک پلاگین فیگما برای تست سریع طرح‌های شما در اندازه‌های مختلف دستگاه‌ها.

---

**[⬆ بازگشت به فهرست مطالب](#table-of-contents)**

### متن

#### Better Font Picker

[کد منبع](https://github.com/nitinrgupta/figma-better-font-picker) · [پلاگین](https://www.figma.com/c/plugin/739922281164562258/Better-Font-Picker) · [MIT](https://github.com/yenargy/figma-better-font-picker/blob/develop/LICENSE)

Better Font Picker به شما کمک می‌کند فونت‌ها را با پیش‌نمایشی از ظاهر آن‌ها انتخاب کنید.

---

#### Content Buddy

[کد منبع](https://github.com/basiclines/figma-content-buddy) · [پلاگین](https://www.figma.com/c/plugin/731260490045684148/Content-Buddy) · [MIT](https://github.com/basiclines/figma-content-buddy/blob/master/LICENSE)

یک پلاگین فیگما که جایگزینی محتوای متنی در چندین لایه را برای هر کسی بسیار آسان می‌کند.

---

#### Tolgee

[کد منبع](https://github.com/tolgee/figma-plugin) • [پلاگین](https://www.figma.com/community/plugin/1212381421658754793/Tolgee-localization) • [MIT](https://github.com/tolgee/figma-plugin/blob/main/LICENSE)

با اتصال فیگما به پلتفرم بومی‌سازی Tolgee، ترجمه‌ها را به راحتی در فایل‌های طراحی فیگمای خود مدیریت کنید.

---

#### Typograf

[کد منبع](https://github.com/golmakov/figma-typograf-plugin) · [پلاگین](https://www.figma.com/c/plugin/745519632050796775/Typograf) · بدون لایسنس

پلاگین فیگما برای ایجاد متن با تایپوگرافی خوب.

---

**[⬆ بازگشت به فهرست مطالب](#table-of-contents)**

### ابزارهای کاربردی

#### Batch Styler

[کد منبع](https://github.com/six7/figma-batch-styler) · [پلاگین](https://www.figma.com/community/plugin/818203235789864127/Batch-Styler) · [MIT](https://github.com/six7/figma-batch-styler/blob/master/LICENSE)

Batch Styler پلاگینی است که به شما امکان ویرایش چندین استایل متن یا رنگ را به طور همزمان می‌دهد.

---

#### Component to page

[کد منبع](https://github.com/thomas-lowry/component-to-page) · [پلاگین](https://www.figma.com/c/plugin/749583881837062159/Component-Page) · [MIT](https://github.com/thomas-lowry/component-to-page/blob/master/LICENSE)

این پلاگین به شما امکان می‌دهد یک کامپوننت بسازید (مانند Sketch) که در آن کامپوننت اصلی (master) به یک صفحه اختصاصی منتقل می‌شود و یک نمونه (instance) در جای خود باقی می‌ماند.

---

#### Edit in place

[کد منبع](https://github.com/thomas-lowry/edit-in-place) · [پلاگین](https://www.figma.com/c/plugin/754704266165393093/Edit-in-place) · بدون لایسنس

هر نمونه‌ای از یک کامپوننت محلی را انتخاب کنید و کامپوننت اصلی را در همان‌جا و در زمینه جایی که از نمونه استفاده می‌کنید، ویرایش کنید. این قابلیت زمانی مفید است که کامپوننت‌های اصلی شما در صفحه‌ای دیگر قرار دارند!

---

#### Emoji Pattern Generator

[کد منبع](https://github.com/niyamax/figma-emoji-pattern-generator) • [پلاگین](https://www.figma.com/community/plugin/1307592924492712453/emoji-pattern-generator) • [MIT](https://github.com/niyamax/figma-emoji-pattern-generator/blob/main/LICENSE)

یک پلاگین فیگما که با استفاده از ایموجی‌ها الگوهای زیبایی ایجاد می‌کند. با سبک‌های مختلف الگو و ترکیب ایموجی‌ها، طرح‌های منحصر به فرد بسازید.

---

#### Figma Measure

[کد منبع](https://github.com/ph1p/figma-measure) · [پلاگین](https://www.figma.com/c/plugin/739918456607459153/Figma-Measure) · [MIT](https://github.com/ph1p/figma-measure/blob/main/LICENSE)

پلاگینی برای اندازه‌گیری آسان ابعاد. یک رابط کاربری کوچک به شما امکان می‌دهد فلش‌هایی برای ارتفاع و عرض اضافه کنید.

---

#### Figma Remove.bg Plugin

[کد منبع](https://github.com/aaroniker/figma-remove-bg) · [پلاگین](https://www.figma.com/c/plugin/738992712906748191/Remove-BG) · بدون لایسنس

پس‌زمینه تصاویر را تنها با یک کلیک حذف کنید.

---

#### Figma Sort It

[کد منبع](https://github.com/kawamurakazushi/figma-sort-it) · [پلاگین](https://www.figma.com/c/plugin/731324768889901500/Sort-It) · [MIT](https://github.com/kawamurakazushi/figma-sort-it/blob/master/LICENSE)

فریم‌ها یا لایه‌های انتخاب‌شده را بر اساس نام یا موقعیت مرتب کنید.

---

#### Figma Walker

[کد منبع](https://github.com/kawamurakazushi/figma-walker) · [پلاگین](https://www.figma.com/c/plugin/732773762837487095/Figma-Walker) · [MIT](https://github.com/kawamurakazushi/figma-walker/blob/master/LICENSE)

بدون برداشتن دست از روی کیبورد، در پروژه خود پیمایش کنید.

---

#### Figmoji

[کد منبع](https://github.com/nitinrgupta/figmoji) · [پلاگین](https://www.figma.com/c/plugin/736612173445813953/Figmoji) · بدون لایسنس

ایموجی‌ها را به طور یکپارچه به طرح‌های خود اضافه کنید.

---

#### Nester

[کد منبع](https://github.com/thomas-lowry/nester) · [پلاگین](https://www.figma.com/c/plugin/787337376836787569/Nester) · [MIT](https://github.com/thomas-lowry/nester/blob/master/LICENSE)

Nester هر شیئی را که بالای یک فریم/آرت‌بورد سطح بالا (و نه داخل آن) قرار دارد، به داخل آن تودرتو می‌کند.

---

#### Pattern Hero

[کد منبع](https://github.com/nitinrgupta/figma-pattern-hero) · [پلاگین](https://www.figma.com/c/plugin/740556241021336678/Pattern-Hero) · بدون لایسنس

Pattern Hero به شما امکان می‌دهد عناصر یا فریم‌های انتخاب‌شده را در یک گرید قرار دهید تا الگو ایجاد کنید.

---

#### Randomiser

[کد منبع](https://github.com/niyamax/Figma-Randomiser) • [پلاگین](https://www.figma.com/community/plugin/1189284785668093844/randomiser) • [CC0-1.0](https://github.com/niyamax/Figma-Randomiser/blob/main/LICENSE)

یک پلاگین فیگما که به کاربران کمک می‌کند اندازه، موقعیت و رنگ عناصر داخل یک فریم را به صورت تصادفی تغییر دهند.

---

#### Reattach Instance

[کد منبع](https://github.com/renancamm/figma-reattache-instance) · [پلاگین](https://www.figma.com/c/plugin/741415678427267506/Reattach-Instance) · [MIT](https://github.com/renancamm/figma-reattache-instance/blob/master/LICENSE)

با جستجوی نمونه‌های مشابه، یک فریم را دوباره به یک کامپوننت متصل کنید.

---

#### Reverse layer order

[کد منبع](https://github.com/mikegowen/figma-reverse-layer-order) · [پلاگین](https://www.figma.com/c/plugin/738853407874474111/Reverse-Layer-Order) · بدون لایسنس

پلاگین فیگما برای معکوس کردن ترتیب لایه‌های انتخاب‌شده.

---

#### Send to top

[کد منبع](https://github.com/thomas-lowry/send-to-top) · [پلاگین](https://www.figma.com/community/plugin/740593880490123393) · [MIT](https://github.com/thomas-lowry/send-to-top/blob/master/LICENSE)

لایه‌های انتخاب‌شده را به بالاترین نقطه از پشته لایه‌ها، بالاتر از تمام فریم‌های دیگر روی بوم می‌فرستد.

---

#### Sorter

[کد منبع](https://github.com/thomas-lowry/sorter) · [پلاگین](https://www.figma.com/c/plugin/742038190980789811/Sorter) · [MIT](https://github.com/thomas-lowry/sorter/blob/master/LICENSE)

به کاربر امکان می‌دهد تا به سرعت ترتیب لایه‌ها را بر اساس موقعیت، نام (الفبایی)، ترتیب معکوس یا تصادفی مرتب کند.

---

#### Variables Import

[کد منبع](https://github.com/microsoft/figma-variables-import) • [پلاگین](https://www.figma.com/community/plugin/1253424530216967528/variables-import) • [MIT](https://github.com/microsoft/figma-variables-import/blob/main/LICENSE.txt)

این پلاگین امکان وارد کردن توکن‌های طراحی به عنوان متغیرهای فیگما را فراهم می‌کند. توجه داشته باشید که پارسر آن کاملاً سازگار نیست و از همه توکن‌های فرمت DTCG پشتیبانی نمی‌کند.

---

**[⬆ بازگشت به فهرست مطالب](#table-of-contents)**

### متفرقه

#### Retro Snake

[کد منبع](https://github.com/gnawx/figma-plugins/tree/master/packages/figma-retro-snake) · [پلاگین](https://www.figma.com/community/plugin/812994090875519300/Retro-Snake) · [MIT](https://github.com/stevahnes/figma-plugins/blob/master/LICENSE)

آوردن بازی قدیمی که همه ما دوستش داریم، Snake، به داخل فیگما!

---

## ویجت‌ها

مجموعه‌ای از ویجت‌هایی که به صورت متن‌باز منتشر شده‌اند. می‌توانید این ویجت‌ها را نصب، بررسی یا برای میزبانی نسخه خود، فورک کنید.

---

**[⬆ بازگشت به فهرست مطالب](#table-of-contents)**
