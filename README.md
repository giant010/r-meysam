<!DOCTYPE html><html lang="tr"><head>
    <meta charset="utf-8"/>
    <meta content="width=device-width, initial-scale=1.0" name="viewport"/>
    <title>Rümeysa İçin Bir Şiir: Umut ve Aşkın İzinde</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Crimson+Text:ital,wght@0,400;0,600;1,400&amp;family=Inter:wght@300;400;500;600&amp;display=swap" rel="stylesheet"/>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet"/>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'cream': '#F5F5DC',
                        'sable': '#8B4513',
                        'rust': '#B7410E',
                        'sage': '#9CAF88',
                        'stone': '#8B8680'
                    },
                    fontFamily: {
                        'serif': ['Crimson Text', 'serif'],
                        'sans': ['Inter', 'sans-serif']
                    }
                }
            }
        }
    </script>
    <style>
        .hero-overlay {
            background: linear-gradient(135deg, rgba(139, 69, 19, 0.8) 0%, rgba(183, 65, 14, 0.6) 100%);
        }
        .toc-fixed {
            position: fixed;
            top: 0;
            left: 0;
            width: 280px;
            height: 100vh;
            background: rgba(245, 245, 220, 0.95);
            backdrop-filter: blur(10px);
            z-index: 1000;
            overflow-y: auto;
            border-right: 1px solid rgba(139, 69, 19, 0.2);
        }
        .main-content {
            margin-left: 280px;
            min-height: 100vh;
        }
        .poem-stanza {
            font-family: 'Crimson Text', serif;
            line-height: 1.8;
            letter-spacing: 0.02em;
        }
        .section-divider {
            background: linear-gradient(90deg, transparent, rgba(139, 69, 19, 0.3), transparent);
            height: 1px;
            margin: 3rem 0;
        }
        @media (max-width: 1024px) {
            .toc-fixed {
                transform: translateX(-100%);
                transition: transform 0.3s ease;
            }
            .toc-fixed.open {
                transform: translateX(0);
            }
            .main-content {
                margin-left: 0;
            }
        }
    </style>
  </head>

  <body class="bg-cream text-sable font-sans">

    <!-- Mobile TOC Toggle Button -->
    <button id="toc-toggle" class="fixed top-4 left-4 z-50 p-2 bg-sable text-cream rounded-full shadow-lg">
      <i class="fas fa-bars"></i>
    </button>

    <!-- Fixed Table of Contents -->
    <nav id="toc" class="toc-fixed p-6">
      <div class="mb-8">
        <h2 class="text-xl font-semibold text-sable mb-4">İçindekiler</h2>
        <ul class="space-y-3 text-sm">
          <li>
            <a class="text-sable hover:text-rust transition-colors" href="#hero">Başlangıç</a>
          </li>
          <li>
            <a class="text-sable hover:text-rust transition-colors" href="#portrait">Rümeysa&#39;nın Portresi</a>
          </li>
          <li>
            <a class="text-sable hover:text-rust transition-colors" href="#youth">Gençlik ve Eğitim</a>
          </li>
          <li>
            <a class="text-sable hover:text-rust transition-colors" href="#personality">Kişisel Özellikler</a>
          </li>
          <li>
            <a class="text-sable hover:text-rust transition-colors" href="#appearance">Görünüm ve İnancı</a>
          </li>
          <li>
            <a class="text-sable hover:text-rust transition-colors" href="#relationship">İlişkinin Temelleri</a>
          </li>
          <li>
            <a class="text-sable hover:text-rust transition-colors" href="#mutual-love">Karşılıklı Aşk</a>
          </li>
          <li>
            <a class="text-sable hover:text-rust transition-colors" href="#inner-beauty">İç Dünyanın Güzelliği</a>
          </li>
          <li>
            <a class="text-sable hover:text-rust transition-colors" href="#poet-perspective">Şairin Bakış Açısı</a>
          </li>
          <li>
            <a class="text-sable hover:text-rust transition-colors" href="#workaholic">İşkolik Zihin</a>
          </li>
          <li>
            <a class="text-sable hover:text-rust transition-colors" href="#importance">Sevgilinin Değeri</a>
          </li>
          <li>
            <a class="text-sable hover:text-rust transition-colors" href="#hope-future">Umut ve Gelecek</a>
          </li>
          <li>
            <a class="text-sable hover:text-rust transition-colors" href="#future-vision">Geleceğe Bakış</a>
          </li>
          <li>
            <a class="text-sable hover:text-rust transition-colors" href="#romantic-hope">Romantik Umut</a>
          </li>
          <li>
            <a class="text-sable hover:text-rust transition-colors" href="#poem">Şiir</a>
          </li>
        </ul>
      </div>
    </nav>

    <!-- Main Content -->
    <main class="main-content">

      <!-- Hero Section -->
      <section class="relative min-h-screen flex items-center" id="hero">
        <div class="absolute inset-0">
          <img alt="Üniversite kütüphanesinde kitap okuyan genç kadın" class="w-full h-full object-cover" src="https://kimi-web-img.moonshot.cn/img/images.pexels.com/e1da4aacbf07be42365a9a52b0969253369ef4af.jpeg" size="wallpaper" aspect="wide" style="photo" query="genç kadın üniversite kütüphanesinde kitap okurken" referrerpolicy="no-referrer" data-modified="1" data-score="11588.00"/>
          <div class="hero-overlay absolute inset-0"></div>
        </div>

        <div class="relative z-10 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16">
          <div class="grid grid-cols-1 lg:grid-cols-2 gap-8 lg:gap-12 items-center">
            <!-- Title Section -->
            <div class="text-cream">
              <h1 class="font-serif text-4xl md:text-5xl lg:text-7xl font-semibold leading-tight mb-6">
                <em>Rümeysa İçin</em>
                <br/>
                <span class="text-2xl md:text-3xl lg:text-4xl font-light">Bir Şiir</span>
              </h1>
              <p class="text-lg md:text-xl lg:text-2xl font-light opacity-90 italic">
                Umut ve Aşkın İzinde
              </p>
            </div>

            <!-- Key Highlights -->
            <div class="bg-cream/95 backdrop-blur-sm p-4 sm:p-6 md:p-8 rounded-lg shadow-xl">
              <h3 class="font-serif text-xl md:text-2xl font-semibold text-sable mb-4 md:mb-6">Şiirin Temaları</h3>
              <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 md:gap-6">
                <div class="text-center">
                  <i class="fas fa-heart text-2xl md:text-3xl text-rust mb-2 md:mb-3"></i>
                  <h4 class="font-semibold text-sable mb-1 md:mb-2">Karşılıklı Aşk</h4>
                  <p class="text-xs md:text-sm text-stone">İki gencin birbirine duyduğu derin sevgi ve bağlılık</p>
                </div>
                <div class="text-center">
                  <i class="fas fa-book text-2xl md:text-3xl text-sage mb-2 md:mb-3"></i>
                  <h4 class="font-semibold text-sable mb-1 md:mb-2">İç Dünya Zenginliği</h4>
                  <p class="text-xs md:text-sm text-stone">Kitap ve kahve sevgisiyle beslenen entelektüel derinlik</p>
                </div>
                <div class="text-center">
                  <i class="fas fa-university text-2xl md:text-3xl text-rust mb-2 md:mb-3"></i>
                  <h4 class="font-semibold text-sable mb-1 md:mb-2">Gençlik ve Eğitim</h4>
                  <p class="text-xs md:text-sm text-stone">18 yaşında üniversite öğrencisi olmanın dinamizmi</p>
                </div>
                <div class="text-center">
                  <i class="fas fa-star text-2xl md:text-3xl text-sage mb-2 md:mb-3"></i>
                  <h4 class="font-semibold text-sable mb-1 md:mb-2">Umutlu Gelecek</h4>
                  <p class="text-xs md:text-sm text-stone">Birlikte inşa edilecek güzel yarınlar</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- Portrait Section -->
      <section class="py-20 bg-white" id="portrait">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
          <div class="text-center mb-16">
            <h2 class="font-serif text-3xl md:text-4xl lg:text-5xl font-semibold text-sable mb-6">Rümeysa&#39;nın Portresi</h2>
            <p class="text-lg text-stone max-w-3xl mx-auto leading-relaxed">
              On sekiz yaşında bir üniversite öğrencisi, kitap ve kahve tutkunu, iç dünyasının zenginliğiyle parlayan genç bir kadın
            </p>
          </div>

          <!-- Youth and Education -->
          <div class="mb-20" id="youth">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
              <div>
                <h3 class="font-serif text-3xl font-semibold text-sable mb-6">Gençlik ve Eğitim Hayatı</h3>
                <div class="prose prose-lg text-stone leading-relaxed">
                  <p class="mb-4">
                    Rümeysa, 18 yaşında genç bir üniversite öğrencisidir. Bu bilgi, onun hem gençlik döneminin dinamizmini hem de eğitim hayatının getirdiği sorumluluk ve hedefleri yansıtmaktadır.
                  </p>
                  <p class="mb-4">
                    Üniversite ortamı yeni fikirlerle, insanlarla ve deneyimlerle dolu bir çevreyi temsil eder. Rümeysa&#39;nın bu ortamda bulunması, onun entelektüel gelişimine ve dünyaya bakış açısına katkı sağlayan bir unsurdur.
                  </p>
                  <blockquote class="border-l-4 border-rust pl-6 italic text-sable">
                    &#34;On sekiz yaş, genç bir kadının kendini keşfettiği ve geleceğini şekillendirmeye başladığı bir dönemdir.&#34;
                  </blockquote>
                </div>
              </div>
              <div>
                <img alt="Rümeysa'nın gerçek portresi" class="w-full h-80 object-cover rounded-lg shadow-lg" src="rumeysa.jpg" />
              </div>
            </div>
          </div>

          <!-- Personality Traits -->
          <div class="mb-20" id="personality">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
              <div class="order-2 lg:order-1">
                <img alt="Kitap okuyan ve kahve içen genç kadın" class="w-full h-80 object-cover rounded-lg shadow-lg" src="https://kimi-web-img.moonshot.cn/img/png.pngtree.com/c44ea731bc82d7eac28d29b781bd7f32bc076b03.jpg" size="medium" aspect="wide" style="photo" query="kitap okuyan kahve içen genç kadın" referrerpolicy="no-referrer" data-modified="1" data-score="11586.00"/>
              </div>
              <div class="order-1 lg:order-2">
                <h3 class="font-serif text-3xl font-semibold text-sable mb-6">Kişisel Özellikleri ve İlgi Alanları</h3>
                <div class="space-y-6">
                  <div class="bg-sage/10 p-6 rounded-lg">
                    <h4 class="font-semibold text-sable mb-3 flex items-center">
                      <i class="fas fa-book text-sage mr-3"></i>
                      Kitap Okuma Sevgisi
                    </h4>
                    <p class="text-stone">
                      Kitap okuma sevgisi, onun entelektüel birikimini, hayal gücünün genişliğini ve iç dünyasının zenginliğini gösterir. Kitaplar, Rümeysa için sadece bilgi kaynağı değil, aynı zamanda farklı dünyalara açılan kapılar, farklı bakış açıları kazandıran araçlardır.
                    </p>
                  </div>
                  <div class="bg-rust/10 p-6 rounded-lg">
                    <h4 class="font-semibold text-sable mb-3 flex items-center">
                      <i class="fas fa-coffee text-rust mr-3"></i>
                      Kahve Keyfi
                    </h4>
                    <p class="text-stone">
                      Kahve sevgisi genellikle dinginlik, keyif ve bazen de sosyal bir ritüel ile ilişkilendirilir. Rümeysa&#39;nın kahve içmeyi sevmesi, belki de kitaplarını okurken eşlikçisi olan bir keyif, ya da dost sohbetlerinin vazgeçilmez bir parçasıdır.
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!-- Appearance -->
          <div class="" id="appearance">
            <div class="bg-sage/5 p-8 rounded-lg">
              <h3 class="font-serif text-3xl font-semibold text-sable mb-6 text-center">İmanı ve Değerleri</h3>
              <div class="max-w-4xl mx-auto">
                <p class="text-stone text-lg leading-relaxed mb-6">
                  Rümeysa'nın güçlü imanı ve manevi değerleri, onun karakterinin temelini oluşturur. İnancı, hayatına yön veren en önemli rehberdir.
                </p>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                  <div class="text-center">
                    <i class="fas fa-heart text-2xl text-rust mb-3"></i>
                    <h4 class="font-semibold text-sable mb-2">Kimlik İfadesi</h4>
                    <p class="text-sm text-stone">İnancının ve değerlerinin bir yansıması</p>
                  </div>
                  <div class="text-center">
                    <i class="fas fa-peace text-2xl text-sage mb-3"></i>
                    <h4 class="font-semibold text-sable mb-2">İç Huzur</h4>
                    <p class="text-sm text-stone">İmanı sayesinde ruhsal dinginlik ve huzur</p>
                  </div>
                  <div class="text-center">
                    <i class="fas fa-gem text-2xl text-rust mb-3"></i>
                    <h4 class="font-semibold text-sable mb-2">Güzellik</h4>
                    <p class="text-sm text-stone">İç ve dış güzelliğin kaynağı olan manevi zenginlik</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <div class="section-divider"></div>

      <!-- Relationship Foundations -->
      <section class="py-20 bg-cream" id="relationship">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
          <div class="text-center mb-16">
            <h2 class="font-serif text-3xl md:text-4xl lg:text-5xl font-semibold text-sable mb-6">İlişkinin Temelleri ve Duygusal Boyutu</h2>
          </div>

          <!-- Mutual Love -->
          <div class="mb-20" id="mutual-love">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
              <div>
                <h3 class="font-serif text-3xl font-semibold text-sable mb-6">Karşılıklı Aşk</h3>
                <div class="prose prose-lg text-stone leading-relaxed">
                  <p class="mb-4">
                    Şiirin temelinde, şair ile Rümeysa arasındaki karşılıklı aşk duygusu yatmaktadır. İki tarafın da birbirine duyduğu derin sevgi ve bağlılık hisleri ön plana çıkarılmalıdır.
                  </p>
                  <p class="mb-4">
                    Aşkın iki tarafı da etkilediği, her ikisinin de bu duyguyla dolup taştığı hissettirilmelidir. Bu karşılıklı aşk, şiirin romantik ve umut dolu tonunun da temelini oluşturacaktır.
                  </p>
                  <blockquote class="border-l-4 border-sage pl-6 italic text-sable font-serif text-xl">
                    &#34;İkimiz de birbirimize tutkun,
                    <br/>
                    Bu aşkın içinde kaybolmuş iki ruhun&#34;
                  </blockquote>
                </div>
              </div>
              <div>
                <img alt="El ele tutuşan çift silueti" class="w-full h-80 object-cover rounded-lg shadow-lg" src="https://kimi-web-img.moonshot.cn/img/e7.pngegg.com/dc13d503735392067265e505031aa23bfbe8b3af.png" size="medium" aspect="wide" style="photo" query="romantik çift el ele tutuşuyor" referrerpolicy="no-referrer" data-modified="1" data-score="11591.00"/>
              </div>
            </div>
          </div>

          <!-- Inner Beauty -->
          <div class="" id="inner-beauty">
            <div class="bg-white p-8 rounded-lg shadow-lg">
              <h3 class="font-serif text-3xl font-semibold text-sable mb-6 text-center">Rümeysa&#39;nın İç Dünyasının Güzelliği</h3>
              <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div>
                  <p class="text-stone text-lg leading-relaxed mb-6">
                    Rümeysa&#39;nın iç dünyasının güzelliği, şiirde önemle vurgulanması gereken bir konudur. Kitap okuma sevgisi, onun iç zenginliğinin bir göstergesidir.
                  </p>
                  <div class="space-y-4">
                    <div class="flex items-start">
                      <i class="fas fa-star text-sage mt-1 mr-3"></i>
                      <div>
                        <h4 class="font-semibold text-sable">Entelektüel Derinlik</h4>
                        <p class="text-sm text-stone">Kitaplarla beslenen geniş hayal gücü</p>
                      </div>
                    </div>
                    <div class="flex items-start">
                      <i class="fas fa-heart text-rust mt-1 mr-3"></i>
                      <div>
                        <h4 class="font-semibold text-sable">Duygusal Hassasiyet</h4>
                        <p class="text-sm text-stone">Merhamet ve sevgi dolu bir kalp</p>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="flex items-center justify-center">
                  <blockquote class="border-l-4 border-rust pl-6 italic text-sable font-serif text-xl">
                    &#34;İç dünyanda galaksiler var,
                    <br/>
                    O kadar güzel ki, kelimeler kifayetsiz&#34;
                  </blockquote>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <div class="section-divider"></div>

      <!-- Poet's Perspective -->
      <section class="py-20 bg-white" id="poet-perspective">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
          <div class="text-center mb-16">
            <h2 class="font-serif text-3xl md:text-4xl lg:text-5xl font-semibold text-sable mb-6">Şairin Bakış Açısı ve Duyguları</h2>
          </div>

          <!-- Workaholic Mind -->
          <div class="mb-20" id="workaholic">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
              <div class="order-2 lg:order-1">
                <img alt="Yoğun çalışan bir ofis ortamı" class="w-full h-80 object-cover rounded-lg shadow-lg" src="https://kimi-web-img.moonshot.cn/img/blog.burotime.com/a5105828b101512d0024a8d910a0855c15a20149.jpg" size="medium" aspect="wide" style="photo" query="yoğun çalışma ortamı" referrerpolicy="no-referrer" data-modified="1" data-score="11594.00"/>
              </div>
              <div class="order-1 lg:order-2">
                <h3 class="font-serif text-3xl font-semibold text-sable mb-6">İşkolik Zihin Yapısı ve Sevgiliye Odaklanma</h3>
                <div class="prose prose-lg text-stone leading-relaxed">
                  <p class="mb-4">
                    Şair, kendisini &#34;işkolik kafa&#34; olarak tanımlamaktadır. Bu, onun zihinsel olarak genellikle işleriyle veya sorumluluklarıyla meşgul olduğu anlamına gelir.
                  </p>
                  <p class="mb-4">
                    Ancak, Rümeysa&#39;nın bu yoğun zihinsel aktivitenin önüne geçtiği ve onu önemsediği belirtilmelidir. Rümeysa&#39;nın varlığı, bu yoğun tempo içinde ona bir nefes aldırır, zihnini dinlendirir.
                  </p>
                  <blockquote class="border-l-4 border-sage pl-6 italic text-sable font-serif text-xl">
                    &#34;Pek çok sorunum var, işkolik kafam hep meşgul,
                    <br/>
                    Ama sen her şeyden önemli, bu belli olsun&#34;
                  </blockquote>
                </div>
              </div>
            </div>
          </div>

          <!-- Importance and Value -->
          <div class="" id="importance">
            <div class="bg-rust/5 p-8 rounded-lg">
              <h3 class="font-serif text-3xl font-semibold text-sable mb-6 text-center">Sevgilinin Önemi ve Değeri</h3>
              <div class="max-w-4xl mx-auto">
                <p class="text-stone text-lg leading-relaxed mb-8 text-center">
                  Rümeysa&#39;nın şairin hayatındaki önemi ve değeri, şiirin en temel vurgularından biri olmalıdır. Onun varlığı, şairin hayatına anlam katar ve ona güç verir.
                </p>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                  <div class="text-center bg-white p-6 rounded-lg shadow-md">
                    <i class="fas fa-anchor text-3xl text-sage mb-4"></i>
                    <h4 class="font-semibold text-sable mb-3">Denge ve Huzur</h4>
                    <p class="text-sm text-stone">İşkolik kafanın karmaşasından sıyrılıp huzur bulduğu liman</p>
                  </div>
                  <div class="text-center bg-white p-6 rounded-lg shadow-md">
                    <i class="fas fa-lightbulb text-3xl text-rust mb-4"></i>
                    <h4 class="font-semibold text-sable mb-3">İlham Kaynağı</h4>
                    <p class="text-sm text-stone">Yaratıcılığını ve motivasyonunu besleyen bir musa</p>
                  </div>
                  <div class="text-center bg-white p-6 rounded-lg shadow-md">
                    <i class="fas fa-infinity text-3xl text-sage mb-4"></i>
                    <h4 class="font-semibold text-sable mb-3">Eşsiz Değer</h4>
                    <p class="text-sm text-stone">Maddi değerlerle ölçülemeyecek kadar derin bir bağ</p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <div class="section-divider"></div>

      <!-- Hope and Future -->
      <section class="py-20 bg-cream" id="hope-future">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
          <div class="text-center mb-16">
            <h2 class="font-serif text-3xl md:text-4xl lg:text-5xl font-semibold text-sable mb-6">Umut ve Gelecek Vizyonu</h2>
          </div>

          <!-- Future Vision -->
          <div class="mb-20" id="future-vision">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
              <div>
                <h3 class="font-serif text-3xl font-semibold text-sable mb-6">Birlikte Geleceğe Bakış</h3>
                <div class="prose prose-lg text-stone leading-relaxed">
                  <p class="mb-4">
                    Şiir, Rümeysa ve şairin birlikte geleceğe umutla baktıklarını yansıtmalıdır. Karşılıklı aşk ve birbirlerine verdikleri değer, onlara geleceğe dair güven ve mutluluk vaat eder.
                  </p>
                  <p class="mb-4">
                    Rümeysa&#39;nın gençliği ve üniversite öğrencisi olması, geleceğin onlar için birçok fırsat ve güzellik barındırdığını düşündürür. Birlikte kurdukları hayaller, onlar için umut kaynağıdır.
                  </p>
                  <blockquote class="border-l-4 border-rust pl-6 italic text-sable font-serif text-xl">
                    &#34;El ele, yarınlara doğru yürüyoruz biz,
                    <br/>
                    Umutlarımız gökyüzünde birer yıldız&#34;
                  </blockquote>
                </div>
              </div>
              <div>
                <img alt="Gün batımında el ele yürüyen genç çift silueti" class="w-full h-80 object-cover rounded-lg shadow-lg" src="https://kimi-web-img.moonshot.cn/img/media.istockphoto.com/31ddb17d2fbb2e15e4bdc4e4133ab2ebb760b732.jpg" size="medium" aspect="wide" color="orange" style="photo" query="çift el ele günbatımı siluet" referrerpolicy="no-referrer" data-modified="1" data-score="11593.00"/>
              </div>
            </div>
          </div>

          <!-- Romantic Hope -->
          <div class="" id="romantic-hope">
            <div class="bg-white p-8 rounded-lg shadow-lg">
              <h3 class="font-serif text-3xl font-semibold text-sable mb-6 text-center">Romantik ve Umut Dolu Bir İlişki Tasviri</h3>
              <div class="max-w-4xl mx-auto">
                <p class="text-stone text-lg leading-relaxed mb-8 text-center">
                  Şiirin genel havası romantik ve umut dolu olmalıdır. Romantizm, aşkın güzelliğini, tutkuyu, duygusal bağlılığı ifade eder. Umut ise, bu romantik ilişkinin geleceğe dair olumlu beklentilerle devam edeceği inancını yansıtır.
                </p>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                  <div class="space-y-6">
                    <div class="flex items-start">
                      <i class="fas fa-heart text-rust text-xl mt-1 mr-4"></i>
                      <div>
                        <h4 class="font-semibold text-sable mb-2">Romantik Anlar</h4>
                        <p class="text-sm text-stone">Birlikte kitap okudukları, kahve içtikleri özel zamanlar</p>
                      </div>
                    </div>
                    <div class="flex items-start">
                      <i class="fas fa-star text-sage text-xl mt-1 mr-4"></i>
                      <div>
                        <h4 class="font-semibold text-sable mb-2">Gelecek Hayalleri</h4>
                        <p class="text-sm text-stone">Birlikte inşa edecekleri mutlu yarınlar</p>
                      </div>
                    </div>
                  </div>
                  <div class="flex items-center justify-center">
                    <blockquote class="border-l-4 border-sage pl-6 italic text-sable font-serif text-xl">
                      &#34;En güzel hayalimsin sen tek isteğim
                      <br/>
                      Yanında nefes almak benim tek dileğim&#34;
                    </blockquote>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <div class="section-divider"></div>

      <!-- The Poem -->
      <section class="py-20 bg-white" id="poem">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
          <div class="text-center mb-16">
            <h2 class="font-serif text-3xl md:text-4xl lg:text-5xl font-semibold text-sable mb-6">Rümeysa İçin Şiir</h2>
            <p class="text-lg text-stone italic">Umut ve Aşkın İzinde</p>
          </div>

          <div class="bg-cream/50 p-8 md:p-12 rounded-lg shadow-lg">
            <div class="poem-stanza text-lg md:text-xl lg:text-2xl text-sable leading-relaxed space-y-6 md:space-y-8">
              <div class="text-center">
                <p class="font-semibold">On sekiz yaşında, üniversite öğrencisi sen,</p>
                <p class="italic">Geleceğin referans kitapları sana küçük</p>
              </div>

              <div class="text-center">
                <p>Kitap okuyan gözlerinde bilgi dağları,</p>
                <p>Kahve kıvamında, olmuş ömrümün tadı</p>
              </div>

              <div class="text-center">
                <p class="font-semibold">Kapalı türbanın altında saklı,</p>
                <p class="italic">İnancın güzelliği, ruhunun paklığı</p>
              </div>

              <div class="text-center">
                <p>Seninle başladı, hayatımda en güzel sayfalar bir bir,</p>
                <p>İkimiz de birbirimize tutkun, bu aşkın içinde iki ruhun</p>
              </div>

              <div class="text-center">
                <p class="font-semibold">İç dünyanda galaksiler var,</p>
                <p class="italic">O kadar güzel ki, kelimeler kifayetsiz</p>
              </div>

              <div class="text-center">
                <p>Senin iç güzelliğin, benim için bir pusula,</p>
                <p>Karanlıkta yolumu aydınlatan bir yıldız</p>
              </div>

              <div class="text-center">
                <p class="font-semibold">Pek çok sorunum var, işkolik kafam hep meşgul,</p>
                <p class="italic">Ama sen her şeyden önemli, bu belli olsun</p>
              </div>

              <div class="text-center">
                <p>İşlerin karmaşasında kaybolmuşken,</p>
                <p>Senin sesin beni gerçeğe çağırır</p>
              </div>

              <div class="text-center">
                <p class="font-semibold">Seninle anladım ne demekmiş &#39;aşk&#39;,</p>
                <p class="italic">Sensiz hayatım, tatsız tuzsuz bir yemek</p>
              </div>

              <div class="text-center">
                <p>Mutlu nice uzun yıllara doğru filizleniyoruz,</p>
                <p>El ele, yarınlara doğru yürüyoruz biz</p>
              </div>

              <div class="text-center">
                <p class="font-semibold">Umutlarımız gökyüzünde birer yıldız,</p>
                <p class="italic">En güzel hayalimsin sen tek isteğim</p>
              </div>

              <div class="text-center">
                <p>Yanında nefes almak benim tek dileğim,</p>
                <p>Rümeysa&#39;m, aşkım, umudum, geleceğim</p>
              </div>
            </div>
          </div>

          <!-- Sources -->
          <div class="mt-16 text-center">
            <h3 class="font-serif text-2xl font-semibold text-sable mb-6">Kaynaklar ve İlham</h3>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-4 text-sm">
              <div class="bg-sage/10 p-4 rounded-lg">
                <span class="text-rust">Kahve ve Kitap İkilisinin Dostluğu</span>
              </div>
              <div class="bg-rust/10 p-4 rounded-lg">
                <span class="text-sage">Kitap ve Kahve Sevenlere</span>
              </div>
              <div class="bg-sage/10 p-4 rounded-lg">
                <span class="text-rust">Rümeysa İsmine Özel Akrostiş Şiir</span>
              </div>
              <div class="bg-rust/10 p-4 rounded-lg">
                <span class="text-sage">Geleceğe Dair Umut Sözleri</span>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- Footer -->
      <footer class="py-12 bg-sable text-cream">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
          <p class="text-lg font-serif italic mb-4">
            &#34;Aşk, iki kalbin birbirini bulmasıdır; umut ise bu buluşmanın sonsuza kadar süreceğine olan inançtır.&#34;
          </p>
          <p class="text-sm opacity-75">
            2025 Rümeysa İçin Şiir - Tüm hakları saklıdır.
          </p>
        </div>
      </footer>
    </main>

    <script>
        // Mobile TOC Toggle
        const tocToggle = document.getElementById('toc-toggle');
        const toc = document.getElementById('toc');
        
        tocToggle.addEventListener('click', () => {
            toc.classList.toggle('open');
        });
        
        // Close TOC when clicking outside on mobile
        document.addEventListener('click', (e) => {
            if (window.innerWidth <= 1024 && !toc.contains(e.target) && !tocToggle.contains(e.target)) {
                toc.classList.remove('open');
            }
        });
        
        // Reset TOC state on desktop
        window.addEventListener('resize', () => {
            if (window.innerWidth > 1024) {
                toc.classList.remove('open');
            }
        });
        
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                    
                    // Close mobile TOC after clicking
                    if (window.innerWidth <= 1024) {
                        toc.classList.remove('open');
                    }
                }
            });
        });
        
        // Highlight active section in TOC
        const sections = document.querySelectorAll('section[id]');
        const tocLinks = document.querySelectorAll('#toc a[href^="#"]');
        
        function highlightActiveSection() {
            let current = '';
            sections.forEach(section => {
                const sectionTop = section.offsetTop - 100;
                const sectionHeight = section.offsetHeight;
                if (window.scrollY >= sectionTop && window.scrollY < sectionTop + sectionHeight) {
                    current = section.getAttribute('id');
                }
            });
            
            tocLinks.forEach(link => {
                link.classList.remove('text-rust', 'font-semibold');
                link.classList.add('text-sable');
                if (link.getAttribute('href') === `#${current}`) {
                    link.classList.remove('text-sable');
                    link.classList.add('text-rust', 'font-semibold');
                }
            });
        }
        
        window.addEventListener('scroll', highlightActiveSection);
        highlightActiveSection(); // Initial call
    </script>

  

</body></html>
