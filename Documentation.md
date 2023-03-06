
### مقدمة في Code Documentation 

هو شرح للكود الذي تم كتابته في البرنامج.
عندما نقوم بكتابة code فإننا نقوم باستخدام لغة برمجية لكتابة البرنامج . وعشان نلخص ماكتبناه في البرنامج راح نستخدم code documentation  ويعتبر الصورة الواضحة لما تم كتابته في البرنامج. ميزة code documentation يحسن readability - usability للكود الذي تم كتابته بحيث يمكًن المطورين من قراءة الكود وفهمه بشكل واضح ومعرفة تفاصيله.


ومن الأمثلة على Documentation مثل Software documentation وهو شرح لكيفية تشغيل وعمل البرنامج وكيفية استخدامه.
و من الأمثلة أيضاً API Documentation مثل شرح عمل service وكيفية استخدامها
و  End user documentation الهدف من end user documentation هو مساعدة المستخدم لفهم product وتقديم جميع الاجابات لمساعدته باستخدام product أو خدمة معينة.


### لماذا نحتاج الى code documentation
- عندما تقوم بكتابة كود برمجي ثم تمضي فترة زمنية من الوقت لم تقم بفتح البرنامج، ستواجه صعوبة بقراءة code عند فتحه مرة أخرى لذلك اذا كتبت code documentation فلن تواجه صعوبة بقراءته ولن تأخذ وقت طويل لفهم ماتم كتابته سابقاً.
- اذا طلب منك client بكتابة برنامج من الممكن أن يطلب منك source code الذي قمت بكتابته ، اذا قمت بتسليمه source code سيواجه مشكلة بعدم فهمه لذلك الحل الأنسب هو code documentation سيتم تلخيص ماتم كتابته في البرنامج وتستطيع تسليمه للعميل.


### مقدمة في documentation generator
- هو برنامج يقوم بمعالجة software documentation أو API documentation وذلك باستخراج  التعليقات special comments الموجودة داخل ملف المشروع source code ثم يتم عرضها في web page بصيغة html.
- ومن الأمثلة على documentation generators
-   Doxygen , Javadoc , JSDoc , Pydoc , phpDocumentor 

وغيرها الكثير من البرامج.


----------
### تحميل برنامج Doxygen

لتحميل برنامج Doxygen على نظام Mac يرجى زيارة الموقع https://www.doxygen.nl/download.html

لتحميل برنامج Doxygen على نظام Windows يرجى زيارة الموقع https://www.doxygen.nl/download.html 

لتحميل برنامج Doxygen على نظام Linux يرجى زيارة الموقع https://www.doxygen.nl/download.html 



----------
### خطوات كتابة comment block
1. كيفية انشاء ملف باستخدام command line 
- يوجد هناك عدة طرق لكتابة comment block :

2. باستخدام `Javadoc style`  وهو باستخدام  `C-style comment block`  باضافة علامة two  `**` في بداية كتابة comment block  كما في المثال التالي: 

  
```
    /**
    * ... text ...
    */
```

3. باستخدام `Qt style` وهو بإضافة علامة `!` exclamation mark بعد بداية كتابة `C-style comment block` كما في الشكل التالي: 

```
    /*!
    * ... text ...
    */
```

4. في الطريقتين السابقتين يمكننا فصل علامة asterisk التي تقع في منتصف comment block كما في الشكل التالي: 
```
    /*
     ... text ...
    */
```


5. كتابة comment block بطرق أخرى
- نستطيع كتابة comment block وذلك باضافة one slash بعد إضافة `C++ comment lines` كما في الشكل التالي: 
```
    ///
    /// ... text ...
    ///
```

- أو باستخدام الطريقة الثانية باضافة علامة exclamation mark `!` كما في الشكل التالي:

```    
    //!
    //!... text ...
    //!
```
ملاحظة: عند اضافة blank line بعد نهاية comment block ينتهي كتابة documentation.


