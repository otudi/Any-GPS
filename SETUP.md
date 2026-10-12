# AnyGPS — Setup · خطوات التفعيل

[English](#english) · [العربية](#العربية)

**iOS 18–26?** See [SETUP-iOS18-26.md](SETUP-iOS18-26.md) · **أجهزة iOS 18–26؟** راجع [SETUP-iOS18-26.md](SETUP-iOS18-26.md)

## English

First-time activation for **iOS 27**. You do this once; after that, daily use is just: LocalDevVPN on → pin → **Teleport**.

### Before you start

- Be on **Wi‑Fi** (not a phone hotspot).
- Have your signing app ready.

### Step 1 — Install LocalDevVPN

Install **[LocalDevVPN](https://apps.apple.com/us/app/localdevvpn/id6755608044)** from the App Store. It creates a small private tunnel on your iPhone that AnyGPS needs to reach Apple's developer location service. You don't need to change its settings.

### Step 2 — Install AnyGPS

1. Download the IPA from the [README](README.md).
2. Sign it and install it.
3. Open AnyGPS. Choose your language at the bottom of the welcome screen, then tap **Get started**.

### Step 3 — Pair AnyGPS with your iPhone

Pairing lets AnyGPS use the developer location service. It is done once and saved on the iPhone.

1. Tap **Start pairing**.
2. Allow the requests one by one: **Location**, then **Notifications**, then **Local Network**.
3. Keep AnyGPS open, then go to **Settings → Privacy & Security → Developer Mode**.
4. Under **Other Devices**, tap **Pair with AnyGPS**. In the **Pair with "AnyGPS"?** window, tap **Pair**.
5. Enter your iPhone passcode.
6. On the next prompt, type the **6‑digit code** shown in AnyGPS (it also appears as a notification at the top).
7. Go back to AnyGPS. You will see **Paired** → tap **Continue**.

In the app, each step number is **yellow** until it's done, then turns into a **green check**.

If AnyGPS doesn't appear in the Developer Mode list: go back to AnyGPS, tap **Try again**, and reopen Developer Mode. Don't force-quit AnyGPS while pairing.

Already have a pairing file? Tap **I have a pairing file** under the pairing card. **Skip for now** continues without pairing (pair later from Settings).

### Step 4 — Turn on the tunnel

1. Tap **Open LocalDevVPN** and turn the VPN **on**.
2. Return to AnyGPS and tap **I’ve connected it — continue**.

### Step 5 — Check the connection

1. On the main screen, tap the red **Check** button at the top.
2. Wait up to 30 seconds. When it turns **green (Ready)**, everything is set.

If something is wrong, a message tells you what to do (see Troubleshooting).

### Daily use

1. Turn on LocalDevVPN.
2. Open AnyGPS. If **Check** is red, tap it.
3. Tap the map or search for a place to drop a pin, then tap **Teleport**.
4. Tap **Stop** to return to your real location.

If you tap **Teleport** while **Check** is red, AnyGPS asks to check first — tap **OK** and it checks, then teleports.

### Other tools

- **Joystick:** tap **Joy** to move with the on-screen joystick. Pick walk / run / cycle / drive above it.
- **Routes:** route button (top) → set start and end → **Follow route**. It follows real roads from Apple Maps. If the start or end has no road, it hops to the nearest road first and hops from the road to the end.
- **Draw:** pencil button → tap points on the map → use the drawn path in Routes.
- **Favorites:** star a pin, then open the star button in the bottom bar.
- **Language:** Settings → Language.
- **See these steps again:** Settings → **Show setup steps again**.

### Troubleshooting

| Message / problem | What to do |
| --- | --- |
| LocalDevVPN is off | Open LocalDevVPN, turn the VPN on, tap **Check** again. |
| Not on Wi‑Fi | Connect to Wi‑Fi (not a phone hotspot), tap **Check** again. |
| Developer service not found | Turn LocalDevVPN off and on, tap **Check** again. If it continues, pair again (Settings → Pair on this iPhone). |
| No pairing file | Settings → **Pair on this iPhone**. |
| Location doesn't return after Stop | Turn LocalDevVPN off and on. |
| Big blue location bubble at the top while simulating | Settings → AnyGPS → Location → **Always**. Then iOS shows only a small arrow. |

## العربية

هذه خطوات التفعيل لأول مرة، وتسويها مرة واحدة فقط. بعدها الاستخدام اليومي بسيط: شغّل تطبيق النفق، ضع دبوسًا، ثم اضغط **انتقال**.

لأجهزة الآيفون بنظام 18 إلى 26 راجع [ملف الشرح الخاص بها](SETUP-iOS18-26.md#العربية).

### قبل البدء

- كن متصلًا بـ **واي فاي** (وليس نقطة اتصال من جوال).
- جهّز تطبيق التوقيع.

### الخطوة 1 — تطبيق النفق

ثبّت تطبيق **[LocalDevVPN](https://apps.apple.com/us/app/localdevvpn/id6755608044)** من متجر التطبيقات. هذا التطبيق ينشئ نفقًا خاصًا صغيرًا داخل الآيفون، ويحتاجه تطبيقنا للوصول إلى خدمة الموقع. لا تحتاج تغيّر إعداداته.

### الخطوة 2 — تثبيت التطبيق

1. نزّل ملف التطبيق من رابط التحميل في [الصفحة الرئيسية](README.md#العربية).
2. وقّعه وثبّته.
3. افتح التطبيق، واختر اللغة من أسفل شاشة الترحيب، ثم اضغط **ابدأ**.

### الخطوة 3 — إقران التطبيق مع الآيفون

الإقران يسمح للتطبيق باستخدام خدمة الموقع، ويتم مرة واحدة ويُحفظ على الجوال.

1. اضغط **بدء الإقران**.
2. وافق على الطلبات واحدًا بعد الآخر: **الموقع**، ثم **الإشعارات**، ثم **الشبكة المحلية**.
3. اترك التطبيق مفتوحًا، واذهب إلى **الإعدادات ← الخصوصية والأمن ← نمط المطور**.
4. تحت **الأجهزة الأخرى** اضغط زر الإقران باسم التطبيق، وفي النافذة التي تظهر اضغط **إقران**.
5. أدخل رمز قفل الآيفون.
6. في الطلب التالي اكتب **الرمز المكوّن من 6 أرقام** الظاهر في التطبيق (يظهر أيضًا كإشعار في الأعلى).
7. ارجع إلى التطبيق، ستظهر **تم الإقران**، ثم اضغط **متابعة**.

في التطبيق رقم كل خطوة يكون **أصفر** حتى تكتمل، ثم يتحول إلى **علامة صح خضراء**.

إذا ما ظهر زر الإقران في نمط المطور: ارجع إلى التطبيق واضغط **حاول مرة أخرى**، ثم افتح نمط المطور من جديد. لا تغلق التطبيق بالقوة أثناء الإقران.

عندك ملف إقران جاهز؟ اضغط **عندي ملف إقران** تحت بطاقة الإقران. وزر **تخطي الآن** يكمل بدون إقران، وتقدر تقترن لاحقًا من الإعدادات.

### الخطوة 4 — تشغيل النفق

1. اضغط زر فتح تطبيق النفق، ثم شغّل الاتصال فيه.
2. ارجع إلى التطبيق واضغط **شغّلته — متابعة**.

### الخطوة 5 — التأكد من الاتصال

1. في الشاشة الرئيسية اضغط الزر الأحمر **افحص الاتصال** في الأعلى.
2. انتظر حتى 30 ثانية. إذا صار **أخضر (جاهز)** فكل شيء مضبوط.

إذا فيه مشكلة تظهر لك رسالة توضّح الحل (راجع حل المشاكل).

### الاستخدام اليومي

1. شغّل تطبيق النفق.
2. افتح التطبيق. إذا كان زر **افحص الاتصال** أحمر، اضغطه.
3. اضغط على الخريطة أو ابحث عن مكان لوضع دبوس، ثم اضغط **انتقال**.
4. اضغط **إيقاف** للرجوع إلى موقعك الحقيقي.

إذا ضغطت **انتقال** والزر أحمر، يطلب منك التطبيق الفحص أولًا. اضغط **موافق** فيفحص ثم ينتقل.

### أدوات أخرى

- **عصا التحكم:** اضغط **تحكم** للتحرك بالعصا على الشاشة، واختر مشي أو جري أو دراجة أو قيادة من الأزرار فوقها.
- **المسارات:** اضغط زر المسار في الأعلى، حدد البداية والنهاية، ثم اضغط **اتبع المسار**. يمشي على الطرق الحقيقية من خرائط الآيفون، وإذا كانت البداية أو النهاية بعيدة عن الطريق يقفز إلى أقرب طريق أولًا، ومن الطريق يقفز إلى النهاية.
- **الرسم:** اضغط زر القلم، ثم اضغط نقاطًا على الخريطة، ثم استخدم المسار المرسوم من شاشة المسارات.
- **المفضلة:** اضغط النجمة على الدبوس، ثم افتح زر النجمة في الشريط السفلي.
- **اللغة:** من الإعدادات ثم اللغة.
- **عرض هذه الخطوات مرة ثانية:** من الإعدادات اضغط **عرض خطوات التفعيل من جديد**.

### حل المشاكل

| المشكلة | الحل |
| --- | --- |
| تطبيق النفق غير شغّال | افتحه وشغّل الاتصال، ثم اضغط **افحص الاتصال**. |
| لست على واي فاي | اتصل بواي فاي (وليس نقطة اتصال جوال)، ثم اضغط **افحص الاتصال**. |
| لم يتم العثور على خدمة المطوّر | أطفئ تطبيق النفق وشغّله من جديد، ثم اضغط **افحص الاتصال**. إذا استمرت المشكلة أعد الإقران من الإعدادات. |
| لا يوجد ملف إقران | من الإعدادات اضغط **الإقران على هذا الآيفون**. |
| الموقع ما رجع بعد الإيقاف | أطفئ تطبيق النفق وشغّله من جديد. |
| فقاعة الموقع الزرقاء الكبيرة فوق أثناء المحاكاة | الإعدادات ← التطبيق ← الموقع ← **دائمًا**. بعدها يظهر سهم صغير فقط. |
