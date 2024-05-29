<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>منع تآكل التربة</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #eaf4e8;
            color: #333;
            margin: 0;
            padding: 0;
            direction: rtl;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            text-align: right;
        }
        header {
            background: #6b8e23; /* Olive green */
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #8b4513 3px solid; /* Saddle brown */
        }
        header a {
            color: #fff;
            text-decoration: none;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            display: inline;
            padding: 0 20px 0 20px;
        }
        .main-section {
            padding: 20px;
            background: #fff;
            margin-top: 20px;
            border-radius: 5px;
            text-align: justify;
        }
        .button {
            display: inline-block;
            color: #fff;
            background: #6b8e23; /* Olive green */
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 10px;
        }
        .button:hover {
            background: #8b4513; /* Saddle brown */
        }
        footer {
            background: #6b8e23; /* Olive green */
            color: #fff;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
            border-top: #8b4513 3px solid; /* Saddle brown */
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>منع تآكل التربة</h1>
            <ul>
                <li><a href="#about">حول</a></li>
                <li><a href="#report">التقرير</a></li>
                <li><a href="#project">المشروع</a></li>
            </ul>
        </div>
    </header>

    <div class="container">
        <section id="about" class="main-section">
            <h2>حول</h2>
            <p>مرحبًا بك في مبادرتنا لمنع تآكل التربة. مهمتنا هي رفع الوعي واتخاذ إجراءات ضد تآكل التربة لحماية البيئة والحفاظ على النظم البيئية الصحية.</p>
        </section>

        <section id="about" class="main-section">
            <h2>العلامات التوضيحية لشكل التربة المتآكلة</h2>
            <p>فقدان الطبقة السطحية للتربة*: قد تلاحظ أن الطبقة السطحية الداكنة من التربة، الغنية بالمواد العضوية، قد تآكلت، مما يكشف عن الطبقات السفلية الفاتحة.</p>
        <p>يمكن معرفة منطقة تآكل التربة عند ايجاد رواسب وحفر عميقة في التربة. 
            عند رؤيتك لهذه المنطقة الرجاء اخذ لقطة واضحة للتربة المتآكله ، لكي نساهم في حل هذه المشكلة في اسرع وقت ممكن.</p>
        </section>

        <section id="report" class="main-section">
            <h2>التقرير عن تآكل التربة</h2>
            <p>إذا لاحظت أي حالات من تآكل التربة، يرجى الإبلاغ عن الموقع باستخدام الزر أدناه. يساعد تقريرك في اتخاذ إجراءات في الوقت المناسب لمنع حدوث مزيد من الأضرار.</p>
            <button class="button" onclick="openCamera()">التقرير مع الصورة</button>
            <form id="reportForm" style="display: none;" enctype="multipart/form-data">
                <input type="file" id="cameraInput" accept="image/*" capture="environment" style="display: none;" onchange="showSubmitButton()">
                <input type="submit" value="إرسال" class="button" style="display: none;" id="submitButton">
            </form>
        </section>

        <section id="project" class="main-section">
            <h2>المشروع المرتبط</h2>
            <p>تحقق من المشروع المرتبط لمزيد من المعلومات والموارد الإضافية.</p>
            <a href="https://alyah27.wuiltweb.com/" class="button">عرض المشروع</a>
        </section>
    </div>

    <footer>
        <p>منع تآكل التربة &copy; 2024-1445</p>
        <p>الثانوية الثالثة والعشرون</p>
    </footer>

    <script>
        function openCamera() {
            document.getElementById('cameraInput').click();
        }
