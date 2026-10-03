# تعريب NUKITASHI العربي

مثبّت Windows للنسخة **NUKITASHI 2.0.2** يضيف الواجهة العربية والنصوص العربية بخط **Noto Sans Arabic**، مع دعم المحاذاة من اليمين إلى اليسار وكشف النص العربي.

## التثبيت

1. أغلق اللعبة.
2. نزّل `NUKITASHI_Arabic_Translation_Setup.exe` وشغّله من أي مكان.
3. اختر مجلد اللعبة الذي يحتوي على `NUKITASHI.exe`.
4. اضغط **تثبيت الترجمة / Install**.

يتحقق المثبّت من إصدار اللعبة ومن كل مورد مصدر قبل التعديل. ينشئ نسخة رجوع موثقة بالهاش، ويتيح زر **استعادة / Restore** الرجوع إلى الرقعة السابقة.

## المحتوى والتحقق

- الإصدار المدعوم: **2.0.2** فقط.
- تغطية آلية: **48,344 / 48,344** حقلاً مصدرياً يحتوي على إنجليزية له نص عربي مستهدف.
- لا توجد كلمات لاتينية ظاهرة في النصوص المستهدفة بحسب الفحص الآلي.
- أزيلت جميع العبارات الاحتياطية العامة، واستُبدلت **1,644** حالة بترجمات مرتبطة مباشرة بمصدرها الإنجليزي.
- خضعت مجموعة المصطلحات الحساسة البالغة **5,916** سطراً لفحص صارم منفصل؛ لا تزال المراجعة الأدبية الشاملة عملاً مستمراً.
- خط الحوار: **Noto Sans Arabic**، بحجم 44 للنمطين الرئيسيين وحد أسود أوضح.
- اجتاز الأرشيف إعادة القراءة، وإعادة تحليل 133 ملف نص، واختبار التثبيت المتكرر والاستعادة المطابقة بالهاش.
- المراجعة الأدبية الكاملة والاختبارات البصرية لجميع المشاهد ما زالت مستمرة؛ نجاح الفحوص الآلية لا يعني اعتماد كل صياغة.

## الخصوصية والملكية

الحزمة لا تتضمن اللعبة، ولا الأرشيفات الأصلية الكاملة، ولا النصوص الأصلية غير المعدلة. يبني المثبّت رقعة اللغة من نسخة اللعبة الموجودة لدى المستخدم بعد التحقق منها. لا يتطلب Python أو نموذج ذكاء اصطناعي أو اتصالاً بالإنترنت.

خط Noto Sans Arabic موزّع وفق رخصة SIL Open Font License المرفقة في `OFL.txt`.

---

# NUKITASHI Arabic Localization

Windows installer for **NUKITASHI 2.0.2**. Close the game, run the installer from any folder, select the directory containing `NUKITASHI.exe`, then choose **Install**. The installer verifies the exact game version and source resources, creates a hash-verified rollback, and can restore the previous overlay.

This release provides automated Arabic target coverage for all 48,344 source subtitle fields containing visible English. Preview 2 replaces 1,644 generic fallbacks with source-linked Arabic and reports no remaining generic placeholders or visible Latin target strings. Full editorial and all-scene visual QA remain ongoing. The package does not contain the game or complete unchanged scenario text.
