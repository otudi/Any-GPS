# AnyGPS — Setup for iOS 18–26 · خطوات التفعيل لـ iOS 18–26

[English](#english) · [العربية](#العربية)

On iOS 27 follow [SETUP.md](SETUP.md) · لأجهزة iOS 27 اتبع [SETUP.md](SETUP.md)

## English

Follow [SETUP.md](SETUP.md#english) Steps 1–2 (LocalDevVPN, install AnyGPS). For Step 3, use a pairing file:

On iOS 18–26 the iPhone can't pair by itself, so Step 3 uses a pairing file made once on a computer. Everything else (LocalDevVPN, Check, Teleport) is the same.

1. On a Mac or PC, download **[idevice_pair](https://github.com/jkcoxson/idevice_pair/releases)**.
2. Connect the iPhone with a cable, unlock it and tap **Trust**.
3. In idevice_pair, create an **RPPairing** file. A SideStore/lockdown `.mobiledevicepairing` file will **not** work.
4. Send the file to the iPhone (AirDrop, Files, or any share), then do **one** of these:
   - Tap the file → Share → **AnyGPS**. AnyGPS saves it and opens straight to the map.
   - In AnyGPS setup, tap **Import pairing file** and pick the file.
   - Copy the file's text, then in AnyGPS tap **Paste from clipboard**.
5. Continue from **Step 4 — Turn on the tunnel** in [SETUP.md](SETUP.md#english).

You can also import later: Settings → **Import RPPairing file…** or **Paste RPPairing from clipboard**.

### LiveContainer

File pickers often don't work inside LiveContainer. Use one of these:

1. Long-press **AnyGPS** in LiveContainer → **Settings** → enable **Fix File Picker**, then import again.
2. Share the pairing file **into LiveContainer → AnyGPS**.
3. Copy the pairing file's text → in AnyGPS use **Paste RPPairing from clipboard**.

## العربية

في أجهزة الآيفون بنظام ١٨ إلى ٢٦ لا يقدر الجوال يقترن بنفسه، لذلك تحتاج ملف إقران تسويه مرة واحدة من الكمبيوتر. باقي الخطوات نفسها.

### الخطوات

1. اتبع الخطوتين ١ و٢ في [ملف الشرح الرئيسي](SETUP.md#العربية): تطبيق النفق، وتثبيت التطبيق.
2. على جهاز ماك أو كمبيوتر ويندوز نزّل أداة **[idevice_pair](https://github.com/jkcoxson/idevice_pair/releases)**.
3. وصّل الآيفون بالكيبل، افتح القفل واضغط **وثوق**.
4. من الأداة أنشئ ملف إقران من نوع **RPPairing**. ملف الإقران الخاص بتطبيق سايد ستور **ما يشتغل**.
5. أرسل الملف للآيفون (عن طريق الإيردروب أو الملفات أو أي مشاركة)، ثم اختر **طريقة واحدة** من هذي:
   - اضغط على الملف، ثم مشاركة، ثم اختر التطبيق. يحفظه التطبيق ويفتح على الخريطة مباشرة.
   - في خطوات بداية التطبيق اضغط **استيراد ملف الإقران** واختر الملف.
   - انسخ محتوى الملف، ثم في التطبيق اضغط **لصق من الحافظة**.
6. كمّل من **الخطوة ٤ — تشغيل النفق** في [ملف الشرح الرئيسي](SETUP.md#العربية).

وتقدر تستورد الملف لاحقًا من الإعدادات: **استيراد ملف RPPairing…** أو **لصق RPPairing من الحافظة**.

### عند استخدام لايف كونتينر

منتقي الملفات غالبًا ما يشتغل داخل لايف كونتينر. استخدم طريقة من هذي:

1. اضغط مطولًا على التطبيق داخل لايف كونتينر، ثم الإعدادات، وفعّل خيار **Fix File Picker**، ثم استورد مرة ثانية.
2. شارك ملف الإقران إلى لايف كونتينر، ثم اختر التطبيق.
3. انسخ محتوى ملف الإقران، ثم في التطبيق اضغط **لصق RPPairing من الحافظة**.
