# Modern Robotics وPhysical AI

نسخة منظمة بالمجلدات من كورس **Modern Robotics и Physical AI** المجاني (من الكلاسيكيات إلى التعلم من العروض ونماذج VLA والروبوتات البشرية)، مع الشرح والأكواد والمختبرات التفاعلية والصور. كل درس صفحة HTML مستقلة تعمل في المتصفح، والشبكات العصبية الصغيرة تتدرب أمامك بدون سيرفر.

> المؤلف الأصلي: Oleg Shipitko، https://modernrobotics.ru. هذا الريبو عمل مشتق وفق CC BY-NC 4.0 (نص ورسوم) وMIT (كود). التفاصيل في [NOTICE.md](NOTICE.md). نصوص الدروس بالروسية.

## ابدأ
1. افتح `part_0_intro/lesson_0.1_two_paradigms/index.html` في المتصفح.
2. تابع بالترتيب: [خريطة الكورس](docs/syllabus.md).
3. المصطلحات: [docs/glossary.md](docs/glossary.md).

## الأجزاء
| الجزء | الحالة |
|---|---|
| [الجزء 0: المقدمة، المنظومة الكلاسيكية وحدودها](part_0_intro/README.md) | متاح |
| [الجزء 1: التعلم من العروض التوضيحية](part_1_imitation_learning/README.md) | متاح |
| [الجزء 2: التمثيل المكاني واللغة والتخطيط](part_2_spatial_language/README.md) | قريبًا |
| [الجزء 3: نماذج الأساس للروبوتات](part_3_foundation_models/README.md) | قريبًا |
| [الجزء 4: بيانات تدريب الروبوتات](part_4_data_for_training/README.md) | قريبًا |
| [الجزء 5: التعلم المعزز](part_5_reinforcement_learning/README.md) | قريبًا |
| [الجزء 6: الروبوتات البشرية](part_6_humanoid_robots/README.md) | قريبًا |
| [الجزء 7: نماذج العالم](part_7_world_models/README.md) | قريبًا |
| [الجزء 8: من النموذج الأولي إلى المنتج](part_8_prototype_to_product/README.md) | قريبًا |

## ما في الريبو
- `part_*/lesson_*/index.html` الدروس، و`README.md` ملخص عربي لكل درس.
- `labs/` المختبرات المستقلة والنماذج الأولية.
- `assets/` الصور والخطوط وKaTeX.
- `docs/` التوثيق.
- `upstream/` نسخة كاملة من الريبو الأصلي (كل الأكواد وسكربتات البناء والاختبارات).

## إعادة البناء من المصدر
```bash
cd upstream
python3 site/build.py
python3 lessons/build.py all   # الناتج في upstream/site/lessons/
```
