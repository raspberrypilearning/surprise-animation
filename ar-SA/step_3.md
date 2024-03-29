## فضول

<div style="display: flex; flex-wrap: wrap">
<div style="flex-basis: 200px; flex-grow: 1; margin-right: 15px;">
هل سيفعل الكائن شيئًا لجذب الانتباه؟ كيف سيكون رد فعل الكائن؟

انت صاحب القرار!
</div>
<div>

![بوو!' مشروع يوضح أن الشخصية فضوليّة.](images/boo.png)

</div>
</div>

### الكائن

--- task ---

**اختر:** إذا كنت تريد أن يقوم الكائن بشيء ما ، فاختر ما سيفعله الكائن.

أضف كتلًا إلى نهاية الكائن `عند النقر على العلم الأخضر`{:class="block3events"} لضبط التعليمات البرمجية.

[[[scratch3-jiggle-a-sprite]]]

[[[scratch3-graphic-effects]]]

--- /task ---

### الشخصية

--- task ---

احصل على الشخصية الرئيسية لإظهار الاهتمام بالكائن. أضف الكتل إلى نهاية لضبط التعليمة البرمجية **الخاص بـ**.

إذا كنت في حاجة إلى أنتظار شخصية ما لعمل شيء لديه، إضف كتلة `الانتظار`{:class="block3control"}.

يمكنك استخدام كتلة `قول`{:class="block3looks"} أو كتلة `فكر`{:class="block3looks"} ، أو حتى استخدام `نص إلى كلام`{:class="block3extensions"} لجعل الشخصية تتحدث بصوت عال!

[[[scratch3-text-to-speech]]]

يمكن للشخصية أن ترمز ، كما هو الحال في مشروع [حديث الفضاء](https://projects.raspberrypi.org/ar-SA/projects/space-talk){:target="_blank"}.

[[[scratch3-change-costumes-to-show-mood]]]

يمكن أن تكون الشخصية شجاعة وتقترب أكثر للتحقق من الكائن.

[[[scratch3-animate-movement-costumes]]]

--- /task ---

--- task ---

**اختبار:** انقر فوق العلم الأخضر لاختبار مشروعك. يجب أن تظهر الشخصية فضولًا حول الكائن.

انقر على العلم الأخضر مرة أخرى. إذا قمت بتغيير موضع الكائن **** أو**الشخصية ** أو شكله ، فستحتاج إلى التأكد من أنه تم إعادته إلى موضع البداية أو المظهر عند تشغيل المشروع مرة أخرى.

--- collapse ---
---
title: اضبط موضع البداية والبحث عن كائن
---

اختر الكتل التي تحتاجها لتعيين الموضع وابحث عن الكائن في البداية.

```blocks3
when flag clicked // إضافة الكتل لإعداد البداية 
switch costume to [costume1 v]
set size to (100) % // حجم عند البداية
go to x: (-200) y: (50) // الموقع عند البداية
point in direction [90]
set [brightness v] effect to [80]
show
```

**نصيحة:** يتم مسح جميع تأثيرات الرسوم عند النقر فوق العلم الأخضر ، لذلك لا تحتاج إلى مسحها ، ولكن قد تحتاج إلى تعيين التأثيرات التي تريد أن يكون للكائن المتحرك.

--- /collapse ---

--- /task ---

--- task ---

**التصحيح:**

--- collapse ---
---
title: الصوت لا يعمل
---

تأكد من أن مستوى الصوت على الكمبيوتر أو الجهاز اللوحي مرتفع بدرجة كافية وأن مكبرات الصوت أو سماعات الرأس متصلة وتعمل بشكل صحيح.

--- /collapse ---

--- collapse ---
---
title: لا يتم إعادة تعيين الرسوم المتحركة الخاصة بي بشكل صحيح عند النقر فوق العلم الأخضر
---

تحقق من أن مشروعك يحتوي على `عند نقر على العلم الأخضر`{:class="block3events"} نصوص برمجية للكائنات التي تحتاجها ، وتحقق من أنها تعيد تعيين الموضع والحجم والبحث عن الكائنات. للمساعدة في هذا ، راجع **تعيين موضع البداية والبحث عن** أعلاه.

--- /collapse ---

--- /task ---

--- save ---
