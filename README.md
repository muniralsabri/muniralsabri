<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>
أبراج الشمس
<p> - منير الصبري</p>
</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <img  src="mn.jpg" alt="
  " />
    <style>
        :root {
            --main-color: #6a1b9a; /* بنفسجي أكثر احترافية */
            --accent-color: #9c27b0;
        }
img {
    width: 100%; /* عرض كامل */
    max-width: 100%; /* أقصى عرض */
    height: auto; /* ارتفاع تلقائي */
    border-radius: 10px; /* زوايا مدورة */
}

        body {
            background: linear-gradient(45deg, var(--main-color), #4a148c);
            color: white;
            font-family: 'Tajawal', sans-serif;
        }

        .animated-header {
            background: linear-gradient(90deg, var(--main-color), var(--accent-color));
            padding: 1.5rem;
            animation: headerGlow 3s infinite alternate;
            box-shadow: 0 4px 15px rgba(0,0,0,0.3);
        }

        @keyframes headerGlow {
            from { background-position: 0% 50%; }
            to { background-position: 100% 50%; }
        }

        .company-carousel {
            display: flex;
            overflow: hidden;
            margin: 2rem 0;
            background: rgba(255,255,255,0.1);
            border-radius: 15px;
            padding: 1rem;
        }

        .company-name {
            flex-shrink: 0;
            padding: 0 2rem;
            animation: scroll 20s linear infinite;
            font-size: 1.2rem;
            color: #ffd700;
        }

        @keyframes scroll {
            0% { transform: translateX(100%); }
            100% { transform: translateX(-100%); }
        }

        .service-card {
            background: rgba(255,255,255,0.15);
            border-radius: 15px;
            padding: 1.5rem;
            margin: 1rem;
            transition: transform 0.3s;
            cursor: pointer;
        }

        .service-card:hover {
            transform: translateY(-10px);
            background: rgba(255,255,255,0.25);
        }

        .featured-section {
            border: 2px solid gold;
            border-radius: 20px;
            margin: 2rem auto;
            padding: 2rem;
            max-width: 1200px;
        }
    </style>
</head>
<body>
    <header class="animated-header">
        <h1 class="text-center display-4 fw-bold">⛅ أبراج الشمس ⛅</h1>
<marquee> <h1> منير الصبري  </h1>  </marquee>
        <p class="text-center fs-5">شركة النقل المتصدر البركة - أبو سرهد صقر الحجاز</p>
    </header>

    <div class="company-carousel">
        <div class="company-name"> نقل الجزيرة

<img     class="f"
 src="jz.jpg" alt="صور باص الجزيرة "></div>
        <div class="company-name"> الراشد للنقل
<img     class="f"
 src="sd.jpg" alt=" باص الراشد "></div>
        <div class="company-name"> <img     class="f"
 src="  " alt="  ">السعودية للنقل الجماعي</div>
        <div class="company-name"> <img     class="f"
 src=" " alt=" "> ناقل</div>
        <div class="company-name"> <img     class="f"
 src=" " alt=" "> سابتكو</div>
    </div>

    <div class="container featured-section">
        <h2 class="text-center mb-4">🌟 خدماتنا المميزة</h2>
        
        <div class="row justify-content-center">
            <div class="col-md-4 service-card">
                <h3>✈️ حجوزات طيران فاخرة</h3>
                <p>أفضل العروض من شركات الطيران العالمية</p>
            </div>
            
            <div class="col-md-4 service-card">
                <h3>🏰 رحلات سياحية مميزة</h3>
                <p>برامج سياحية مبتكرة بأسعار تنافسية</p>
            </div>
            
            <div class="col-md-4 service-card">
                <h3> 🚌🚌🚊 نقل بري آمن</h3>
                <p>شبكة نقل بري تغطي  جميع أنحاء المملكة العربيةالسعودية </p>
<p>  اليمن  </p>

<p> جميع دول الخليج </p>
            </div>
        </div>
    </div>

    <div class="register-form container">
        <div class="row justify-content-center">
            <div class="col-lg-6">
                <div class="card bg-transparent border-light">
                    <div class="card-body">
                        <h3 class="card-title text-center mb-4">🎉 انضم إلينا الآن</h3>
                        <form class="needs-validation" novalidate>
                            <div class="mb-3">
                                <input type="email" class="form-control bg-transparent text-white" 
                                       placeholder="البريد الإلكتروني (Gmail)" required>
                            </div>
                            
                            <div class="mb-3">
                                <input type="text" class="form-control bg-transparent text-white" 
                                       placeholder="الاسم الكامل" required>
                            </div>
                            
                            <div class="mb-3 position-relative">
                                <input type="password" id="password" 
                                       class="form-control bg-transparent text-white" 
                                       placeholder="كلمة السر" required>
                                <span class="position-absolute end-0 top-50 translate-middle-y me-2 cursor-pointer"
                                      onclick="togglePassword()">
                                    👁️
                                </span>
                            </div>
                            
                            <div class="mb-4">
                                <input type="password" id="confirm-password" 
                                       class="form-control bg-transparent text-white" 
                                       placeholder="تأكيد كلمة السر" required>
                            </div>
                            
                            <button type="submit" class="btn btn-light w-100 fw-bold">
                                ✅ إنشاء حساب
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <footer class="text-center py-4 mt-5 border-top border-light">
        <div class="d-flex justify-content-center gap-3 mb-3">
            <a href="#" class="text-white">الشروط والأحكام</a>
            <a href="#" class="text-white">سياسة الخصوصية</a>
            <a href="#" class="text-white">اتصل بنا</a>
        </div>
        <p class="mb-0">© 2024 أبراج الشمس - جميع الحقوق محفوظة</p>
    </footer>

    <script>
        function togglePassword() {
            const password = document.getElementById('password');
            const confirm = document.getElementById('confirm-password');
            const type = password.type === 'password' ? 'text' : 'password';
            password.type = type;
            confirm.type = type;
        }

        // التحقق من صحة النموذج
        (() => {
          'use strict'

          const forms = document.querySelectorAll('.needs-validation')

          Array.from(forms).forEach(form => {
            form.addEventListener('submit', event => {
              if (!form.checkValidity()) {
                event.preventDefault()
                event.stopPropagation()
              }

              // التحقق من تطابق كلمة السر
              const pass = document.getElementById('password').value;
              const confirmPass = document.getElementById('confirm-password').value;
              if (pass !== confirmPass) {
                alert("⚠️ كلمة السر غير متطابقة!");
                event.preventDefault()
              }

              form.classList.add('was-validated')
            }, false)
          })
        })()
    </script>
    <script>
  // عند تحميل الصفحة نتحقق من حالة المستخدم
  document.addEventListener('DOMContentLoaded', function() {
    if (localStorage.getItem('gmailUser')) {
      document.querySelector('.register-form').style.display = 'none';
    }
  });

  // تعديل دورة التحقق من النموذج
  (() => {
    'use strict'

    const forms = document.querySelectorAll('.needs-validation')

    Array.from(forms).forEach(form => {
      form.addEventListener('submit', event => {
        event.preventDefault()
        event.stopPropagation()

        // التحقق من صحة الحقول
        if (!form.checkValidity()) {
          form.classList.add('was-validated')
          return
        }

        // التحقق من تطابق كلمة السر
        const pass = document.getElementById('password').value
        const confirmPass = document.getElementById('confirm-password').value
        if (pass !== confirmPass) {
          alert("⚠️ كلمة السر غير متطابقة!")
          return
        }

        // التحقق من نوع البريد الإلكتروني
        const email = document.querySelector('input[type="email"]').value
        if (email.includes('@gmail.com')) {
          // إخفاء النموذج وحفظ الحالة
          document.querySelector('.register-form').style.display = 'none'
          localStorage.setItem('gmailUser', 'true')
          alert('مرحبا! تم تسجيل الدخول بنجاح ✅')
        }

        form.classList.add('was-validated')
      }, false)
    })
  })()
</script>

    <script>
        // عند تحميل الصفحة نتحقق من حالة المستخدم
        document.addEventListener('DOMContentLoaded', function() {
            if (localStorage.getItem('gmailUser')) {
                document.querySelector('.register-form').style.display = 'none';
                window.open('https://www.facebook.com/profile.php?id=61559639265458'); // استبدل الرابط بصفحتك
            }
        });

        (() => {
          'use strict'

          const forms = document.querySelectorAll('.needs-validation')

          Array.from(forms).forEach(form => {
            form.addEventListener('submit', event => {
              event.preventDefault()
              event.stopPropagation()

              if (!form.checkValidity()) {
                form.classList.add('was-validated')
                return
              }

              const pass = document.getElementById('password').value
              const confirmPass = document.getElementById('confirm-password').value
              if (pass !== confirmPass) {
                alert("⚠️ كلمة السر غير متطابقة!")
                return
              }

              const email = document.querySelector('input[type="email"]').value
              if (email.includes('@gmail.com')) {
                document.querySelector('.register-form').style.display = 'none'
                localStorage.setItem('gmailUser', 'true')
                alert('مرحبا! تم تسجيل الدخول بنجاح ✅')
                
                // فتح صفحة الفيسبوك في نافذة جديدة
                window.open('https://www.facebook.com/profile.php?id=61559639265458') // استبدل الرابط هنا
              }

              form.classList.add('was-validated')
            }, false)
          })
        })()
    </script>

    <!-- إضافة رابط الفيسبوك في الفوتر -->
    <footer class="text-center py-4 mt-5 border-top border-light">
        <div class="d-flex justify-content-center gap-3 mb-3">
            <!-- الروابط الأخرى -->
            <a href="https://www.facebook.com/YourFacebookPage" 
               class="text-white"
               target="_blank"
               id="facebook-link">صفحتنا على الفيسبوك</a>
            <a href="#" class="text-white">الشروط والأحكام</a>
            <a href="#" class="text-white">سياسة الخصوصية</a>
            <a href="#" class="text-white">اتصل بنا</a>
        </div>
        <p class="mb-0">© 2024 أبراج الشمس - جميع الحقوق محفوظة</p>
    </footer>

</body>
</html>
