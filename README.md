# djelfa-ens-portal.-

<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="theme-color" content="#234d38">
  <meta name="description" content="البوابة الرقمية لملحقة المدرسة العليا للأساتذة بالجلفة">
  <title>ملحقة المدرسة العليا للأساتذة بالجلفة</title>

  <style>
    :root {
      --green: #234d38;
      --green-light: #397354;
      --sand: #d8c39a;
      --cream: #f7f5ee;
      --text: #26382d;
      --muted: #6d786f;
      --white: #fff;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: Tahoma, Arial, sans-serif;
      background: var(--cream);
      color: var(--text);
      line-height: 1.8;
    }

    a {
      text-decoration: none;
    }

    header {
      color: white;
      background: linear-gradient(135deg, var(--green), var(--green-light));
      padding: 20px 6% 55px;
      border-radius: 0 0 30px 30px;
    }

    nav {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 12px;
      flex-wrap: wrap;
      max-width: 1100px;
      margin: auto;
    }

    .brand {
      display: flex;
      align-items: center;
      gap: 12px;
      font-weight: bold;
    }

    .logo {
      display: grid;
      place-items: center;
      width: 48px;
      height: 48px;
      border-radius: 14px;
      background: var(--sand);
      color: var(--green);
      font-size: 26px;
    }

    nav a {
      color: white;
      padding: 7px 10px;
      font-size: 14px;
    }

    .hero {
      max-width: 1100px;
      margin: 45px auto 0;
    }

    .hero h1 {
      font-size: clamp(28px, 5vw, 46px);
      line-height: 1.5;
      margin: 0 0 12px;
    }

    .hero p {
      max-width: 650px;
      color: #e5eee7;
    }

    .button {
      display: inline-block;
      background: var(--sand);
      color: var(--green);
      padding: 11px 20px;
      margin-top: 12px;
      border: 0;
      border-radius: 12px;
      font-weight: bold;
      font-family: inherit;
      cursor: pointer;
    }

    main {
      max-width: 1100px;
      margin: -22px auto 0;
      padding: 0 16px 40px;
    }

    .stats {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 12px;
    }

    .stat, .card, .panel {
      background: white;
      border: 1px solid #e5e8df;
      border-radius: 17px;
      padding: 18px;
      box-shadow: 0 5px 20px #203d2b08;
    }

    .stat strong {
      display: block;
      color: var(--green);
      font-size: 25px;
    }

    .stat span {
      color: var(--muted);
      font-size: 13px;
    }

    section {
      margin-top: 35px;
    }

    h2 {
      color: var(--green);
      margin-bottom: 5px;
    }

    .subtitle {
      color: var(--muted);
      margin-top: 0;
      font-size: 14px;
    }

    .filters {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      margin: 18px 0;
    }

    .filter {
      border: 1px solid #dce3d9;
      border-radius: 25px;
      background: white;
      color: var(--green);
      padding: 9px 16px;
      font-family: inherit;
      cursor: pointer;
    }

    .filter.active {
      background: var(--green);
      color: white;
    }

    .grid {
      display: grid;
      grid-template-columns: repeat(3, minmax(0, 1fr));
      gap: 14px;
    }

    .card {
      border-top: 4px solid var(--sand);
    }

    .card-icon {
      font-size: 28px;
    }

    .card h3 {
      margin: 7px 0;
      font-size: 18px;
    }

    .card p {
      color: var(--muted);
      font-size: 13px;
      margin: 0;
    }

    .tag {
      display: inline-block;
      background: #edf4ed;
      color: #2c6545;
      padding: 4px 10px;
      border-radius: 20px;
      font-size: 11px;
      margin-top: 12px;
    }

    .resource-grid {
      display: grid;
      grid-template-columns: repeat(3, minmax(0, 1fr));
      gap: 14px;
    }

    .panel-grid {
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 14px;
    }

    .panel p {
      color: var(--muted);
      font-size: 14px;
    }

    .notice {
      border-right: 5px solid var(--sand);
    }

    footer {
      background: var(--green);
      color: white;
      text-align: center;
      padding: 25px 15px;
      font-size: 13px;
    }

    @media (max-width: 650px) {
      header {
        padding: 16px 18px 45px;
      }

      nav {
        align-items: flex-start;
      }

      nav .links {
        width: 100%;
      }

      .hero {
        margin-top: 28px;
      }

      .stats {
        gap: 8px;
      }

      .stat {
        padding: 12px 8px;
      }

      .stat strong {
        font-size: 20px;
      }

      .stat span {
        font-size: 11px;
      }

      .grid, .resource-grid {
        grid-template-columns: repeat(2, minmax(0, 1fr));
        gap: 10px;
      }

      .card, .panel {
        padding: 13px;
      }

      .panel-grid {
        grid-template-columns: 1fr;
      }
    }

    @media (max-width: 380px) {
      .grid, .resource-grid {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>

<body>
  <header>
    <nav>
      <div class="brand">
        <div class="logo">🎓</div>
        <div>
          ملحقة المدرسة العليا للأساتذة<br>
          القبة — الجلفة
        </div>
      </div>

      <div class="links">
        <a href="#home">الرئيسية</a>
        <a href="#specialties">التخصصات</a>
        <a href="#resources">الموارد</a>
        <a href="#student">فضاء الطالب</a>
      </div>
    </nav>

    <div class="hero" id="home">
      <h1>مرحبًا بكم في<br>البوابة الجامعية لملحقة الجلفة</h1>
      <p>
        فضاء رقمي يهدف إلى جمع التخصصات الدراسية والدروس والملخصات
        والإعلانات الجامعية في مكان واحد لخدمة الطلبة.
      </p>
      <a class="button" href="#specialties">اكتشف التخصصات ←</a>
    </div>
  </header>

  <main>
    <div class="stats">
      <div class="stat">
        <strong>3</strong>
        <span>أطوار تعليمية</span>
      </div>
      <div class="stat">
        <strong id="specialtyCount">10</strong>
        <span>تخصصات دراسية</span>
      </div>
      <div class="stat">
        <strong>2026–2027</strong>
        <span>السنة الجامعية</span>
      </div>
    </div>

    <section id="specialties">
      <h2>التخصصات الدراسية</h2>
      <p class="subtitle">اختر الطور التعليمي لعرض التخصصات المتاحة.</p>

      <div class="filters">
        <button class="filter active" data-level="الكل">جميع التخصصات</button>
        <button class="filter" data-level="ابتدائي">أستاذ التعليم الابتدائي</button>
        <button class="filter" data-level="متوسط">أستاذ التعليم المتوسط</button>
        <button class="filter" data-level="ثانوي">أستاذ التعليم الثانوي</button>
      </div>

      <div class="grid" id="specialtyGrid"></div>
    </section>

    <section id="resources">
      <h2>الدروس والملخصات</h2>
      <p class="subtitle">مساحة مخصصة للموارد التعليمية والمراجعة.</p>

      <div class="resource-grid">
        <article class="card">
          <div class="card-icon">🧬</div>
          <h3>علوم الطبيعة والحياة</h3>
          <p>ملخصات ومراجعات في العلوم الطبيعية.</p>
          <span class="tag">موارد تعليمية</span>
        </article>

        <article class="card">
          <div class="card-icon">📐</div>
          <h3>الرياضيات</h3>
          <p>دروس وتمارين للمراجعة والتطبيق.</p>
          <span class="tag">دروس وتمارين</span>
        </article>

        <article class="card">
          <div class="card-icon">💻</div>
          <h3>الإعلام الآلي</h3>
          <p>مبادئ الحاسوب والتقنيات الرقمية.</p>
          <span class="tag">موارد تعليمية</span>
        </article>
      </div>
    </section>

    <section class="panel-grid">
      <div class="panel notice">
        <h3>📢 الإعلانات الجامعية</h3>
        <p>
          ستظهر هنا إعلانات التسجيل والامتحانات ومواعيد الدراسة
          بعد ربط الموقع بنظام إدارة حقيقي.
        </p>
      </div>

      <div class="panel" id="student">
        <h3>🪪 فضاء الطالب</h3>
        <p>
          يمكن تخصيص هذا القسم لتسجيل الطلبة وعرض بياناتهم
          وبطاقة الطالب بعد إضافة خادم آمن وقاعدة بيانات.
        </p>
        <button class="button" id="studentInfo">معرفة المزيد</button>
      </div>
    </section>
  </main>

  <footer>
    <p>ملحقة المدرسة العليا للأساتذة — القبة، الجلفة</p>
    <p>بوابة جامعية نموذجية لخدمة الطلبة</p>
  </footer>

  <script>
    const specialties = [
      {
        level: "ابتدائي",
        name: "لغة عربية",
        icon: "📖",
        description: "تكوين في اللغة العربية وطرائق تدريسها."
      },
      {
        level: "ابتدائي",
        name: "لغة فرنسية",
        icon: "🇫🇷",
        description: "تكوين في اللغة الفرنسية وتعليمها."
      },
      {
        level: "متوسط",
        name: "لغة عربية",
        icon: "✍️",
        description: "اللغة والأدب وطرائق التدريس."
      },
      {
        level: "متوسط",
        name: "لغة فرنسية",
        icon: "🇫🇷",
        description: "اللغة الفرنسية وديداكتيك المادة."
      },
      {
        level: "متوسط",
        name: "لغة إنجليزية",
        icon: "🇬🇧",
        description: "اللغة الإنجليزية وطرق تعليمها."
      },
      {
        level: "متوسط",
        name: "تاريخ وجغرافيا",
        icon: "🌍",
        description: "دراسة التاريخ والجغرافيا والخرائط."
      },
      {
        level: "متوسط",
        name: "إعلام آلي",
        icon: "💻",
        description: "الحاسوب والمفاهيم الرقمية."
      },
      {
        level: "متوسط",
        name: "تربية بدنية",
        icon: "⚽",
        description: "التربية البدنية والنشاط الرياضي."
      },
      {
        level: "متوسط",
        name: "علوم طبيعية",
        icon: "🧬",
        description: "علوم الطبيعة والحياة."
      },
      {
        level: "ثانوي",
        name: "تربية بدنية",
        icon: "🏃",
        description: "التكوين في التربية البدنية للتعليم الثانوي."
      }
    ];

    const grid = document.getElementById("specialtyGrid");

    function showSpecialties(level = "الكل") {
      const filtered = specialties.filter(item =>
        level === "الكل" || item.level === level
      );

      grid.innerHTML = filtered.map(item => `
        <article class="card">
          <div class="card-icon">${item.icon}</div>
          <h3>${item.name}</h3>
          <p>${item.description}</p>
          <span class="tag">أستاذ التعليم ${item.level}</span>
        </article>
      `).join("");
    }

    document.querySelectorAll(".filter").forEach(button => {
      button.addEventListener("click", () => {
        document.querySelectorAll(".filter").forEach(item =>
          item.classList.remove("active")
        );

        button.classList.add("active");
        showSpecialties(button.dataset.level);
      });
    });

    document.getElementById("studentInfo").addEventListener("click", () => {
      alert(
        "هذا القسم تجريبي. تسجيل الطلبة وعرض بياناتهم يحتاج إلى خادم آمن."
      );
    });

    showSpecialties();
  </script>
</body>
</html>
