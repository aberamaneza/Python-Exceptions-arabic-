# Python-Exceptions-arabic-
"A project for translating and defining standard exceptions in the Python language into Arabic."

BaseException (الاستثناء الأساسي)
 ├── BaseExceptionGroup (مجموعة الاستثناء الأساسية)
 ├── GeneratorExit (استثناء خروج المولد)
 ├── KeyboardInterrupt (استثناء انقطاع التحكم)
 ├── SystemExit (استثناء الخروج من النظام)
 └── Exception (الاستثناء العام)
      ├── ArithmeticError (استثناء الحساب)
      │    ├── FloatingPointError (استثناء نقطة العائمة)
      │    ├── OverflowError (استثناء التجاوز)
      │    └── ZeroDivisionError (استثناء قسمة على الصفر)
      ├── AssertionError (استثناء التأكيد)
      ├── AttributeError (استثناء عدم وجود السمة)
      ├── BufferError (استثناء الخطأ في المخزن المؤقت)
      ├── EOFError (استثناء نهاية الملف)
      ├── ExceptionGroup [BaseExceptionGroup] (مجموعة الاستثناءات [مجموعة الاستثناء الأساسية])
      ├── ImportError (استثناء الاستيراد)
      │    └── ModuleNotFoundError (استثناء عدم العثور على الوحدة)
      ├── LookupError (استثناء البحث)
      │    ├── IndexError (استثناء فهرس القائمة غير صالح)
      │    └── KeyError (استثناء مفتاح القاموس غير موجود)
      ├── MemoryError (استثناء نفاد الذاكرة)
      ├── NameError (استثناء عدم وجود الاسم)
      │    └── UnboundLocalError (استثناء عدم وجود المتغير المحلي المرتبط)
      ├── OSError (استثناء خطأ نظام التشغيل)
      │    ├── BlockingIOError (استثناء الإدخال/الإخراج التالف)
      │    ├── ChildProcessError (استثناء خطأ في عملية الطفل)
      │    ├── ConnectionError (استثناء خطأ في الاتصال)
      │    │    ├── BrokenPipeError (استثناء خطأ في الأنابيب المنقطعة)
      │    │    ├── ConnectionAbortedError (استثناء خطأ في الاتصال الملغي)
      │    │    ├── ConnectionRefusedError (استثناء خطأ في رفض الاتصال)
      │    │    └── ConnectionResetError (استثناء خطأ في إعادة تعيين الاتصال)
      │    ├── FileExistsError (استثناء خطأ في وجود الملف)
      │    ├── FileNotFoundError (استثناء خطأ في عدم وجود الملف)
      │    ├── InterruptedError (استثناء مقاطعة التشغيل)
      │    ├── IsADirectoryError (استثناء خطأ في دليل)
      │    ├── NotADirectoryError (استثناء خطأ في غير الدليل)
      │    ├── PermissionError (استثناء خطأ في الإذن)
      │    ├── ProcessLookupError (استثناء خطأ في البحث عن العملية)
      │    └── TimeoutError (استثناء خطأ في المهلة الزمنية)
      ├── ReferenceError (استثناء الإشارة)
      ├── RuntimeError (استثناء الوقت التشغيلي)
      │    ├── NotImplementedError (استثناء عدم تنفيذه بعد)
      │    └── RecursionError (استثناء التكرار)
      ├── StopAsyncIteration (استثناء إيقاف التكرار الغير متزامن)
      ├── StopIteration (استثناء إيقاف التكرار)
      ├── SyntaxError (استثناء الصيغة)
      │    └── IndentationError (استثناء خطأ التظليل)
      │         └── TabError (استثناء خطأ التبويب)
      ├── SystemError (استثناء النظام)
      ├── TypeError (استثناء النوع)
      ├── ValueError (استثناء القيمة)
      │    └── UnicodeError (استثناء اليونيكود)
      │         ├── UnicodeDecodeError (استثناء فك تشفير اليونيكود)
      │         ├── UnicodeEncodeError (استثناء ترميز اليونيكود)
      │         └── UnicodeTranslateError (استثناء ترجمة اليونيكود)
      └── Warning (تحذير)
           ├── BytesWarning (تحذير البايتات)
           ├── DeprecationWarning (تحذير الإهمال)
           ├── EncodingWarning (تحذير الترميز)
           ├── FutureWarning (تحذير المستقبل)
           ├── ImportWarning (تحذير الاستيراد)
           ├── PendingDeprecationWarning (تحذير الإهمال المؤجل)
           ├── ResourceWarning (تحذير الموارد)
           ├── RuntimeWarning (تحذير التشغيل)
           ├── SyntaxWarning (تحذير الصيغة)
           ├── UnicodeWarning (تحذير اليونيكود)
           └── UserWarning (تحذير المستخدم)
