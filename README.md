<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
  <title>Đào Tạo Pha Chế F&amp;B Base | Trung Tâm Đào Tạo Pha Chế &amp; Setup Quán Đà Nẵng - fbbase.com</title>
  <meta name="description" content="F&B Base (fbbase.com) - Học viện đào tạo pha chế chuyên sâu Barista, Bartender, Trà sữa, Mở quán, Barista Du học sinh và cung cấp Nguyên liệu, Máy móc thiết bị, Dụng cụ, Ly tách pha chế, Setup quán trọn gói tại 134/5 Yên Bái, Hải Châu, Đà Nẵng. Hotline: 0777.434.358.">

  <!-- THUMBNAIL CHIA SẺ LINK WEBSITE LÀ ẢNH LOGO TRANG WEB (OPEN GRAPH & TWITTER META) -->
  <meta property="og:type" content="website">
  <meta property="og:site_name" content="fbbase.com - Đào tạo pha chế F&B Base">
  <meta property="og:url" content="https://fbbase.com/">
  <meta property="og:title" content="Đào Tạo Pha Chế F&B Base - Học Viện Pha Chế & Setup Quán Cà Phê Đà Nẵng">
  <meta property="og:description" content="Đào tạo Barista, Bartender, Mở quán, Du học sinh. Cung cấp nguyên liệu, máy móc thiết bị, dụng cụ pha chế & Setup quán trọn gói. Đ/c: 134/5 Yên Bái - Hải Châu - Đà Nẵng. SĐT: 0777.434.358">
  <meta property="og:image" content="https://drive.google.com/thumbnail?id=1_Lmxu5-AwVn0MLzPvd0daTshr1HvShPm&sz=w1200">
  <meta property="og:image:alt" content="Logo Đào Tạo Pha Chế F&B Base - fbbase.com">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:title" content="Đào Tạo Pha Chế F&B Base - fbbase.com">
  <meta name="twitter:description" content="Trung tâm đào tạo pha chế chuyên sâu & Setup quán cà phê trọn gói tại 134/5 Yên Bái, Hải Châu, Đà Nẵng.">
  <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1_Lmxu5-AwVn0MLzPvd0daTshr1HvShPm&sz=w1200">
  <link rel="icon" type="image/png" href="https://drive.google.com/thumbnail?id=1_Lmxu5-AwVn0MLzPvd0daTshr1HvShPm&sz=w200">

  <!-- Google Fonts: Inter -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

  <!-- Font Awesome 6 Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
          },
          colors: {
            brand: {
              dark: '#2A1810',     /* Màu nâu Espresso đậm theo tông Logo F&B */
              primary: '#4A2C1D',  /* Màu nâu cà phê chủ đạo */
              accent: '#C6862E',   /* Màu vàng đồng / Amber ấm của F&B */
              light: '#FBF8F3',    /* Màu kem sáng nền Flatsome */
              soft: '#F3ECE1',     /* Màu kem nhạt phân tách section */
              border: '#E5DAC9'    /* Màu viền khung nhẹ nhàng */
            }
          }
        }
      }
    }
  </script>

  <style>
    /* ==========================================================================
       CHUẨN HÓA BỐ CỤC FLATSOME & CHỐNG TRÀN VIỀN / LỆCH PHẢI TUYỆT ĐỐI
       ========================================================================== */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      font-family: 'Inter', sans-serif;
      background-color: #FFFFFF;
      color: #2A1810;
      scroll-behavior: smooth;
    }

    /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính */
    .ux-container {
      width: 94%;
      max-width: 94%;
      margin-left: auto;
      margin-right: auto;
    }
    @media (min-width: 1024px) {
      .ux-container {
        width: 95%;
        max-width: 95%;
        margin-left: auto;
        margin-right: auto;
      }
    }

    /* Tối ưu tên danh mục trên máy tính & trang chủ:
       Viết liền trên 1 hàng, chữ nhỏ gọn, không bao giờ tự ngắt chữ xuống dòng trong 1 tên danh mục */
    .cat-nowrap {
      white-space: nowrap !important;
      display: inline-flex;
      align-items: center;
      line-height: 1.25;
    }

    /* Tiêu chuẩn Section Title giống Flatsome UX Builder (Title kiểu Center Divider) */
    .flatsome-section-title {
      display: flex;
      align-items: center;
      justify-content: center;
      width: 100%;
      margin-bottom: 1.5rem;
      text-align: center;
    }
    .flatsome-section-title b {
      display: block;
      flex: 1;
      height: 2px;
      background-color: #E5DAC9;
    }
    .flatsome-section-title span {
      padding: 0 1rem;
      font-weight: 800;
      text-transform: uppercase;
      color: #2A1810;
      letter-spacing: 0.02em;
    }

    /* 2 Ảnh Banner Tự Trượt Kích Thước Bằng Nhau Tuyệt Đối */
    .banner-slider-viewport {
      position: relative;
      width: 100%;
      height: 310px;
      overflow: hidden;
      border-radius: 0.75rem;
      background-color: #2A1810;
    }
    @media (min-width: 640px) {
      .banner-slider-viewport {
        height: 360px;
      }
    }
    @media (min-width: 1024px) {
      .banner-slider-viewport {
        height: 430px;
      }
    }
    .banner-slide {
      position: absolute;
      inset: 0;
      width: 100%;
      height: 100%;
      opacity: 0;
      visibility: hidden;
      transition: opacity 0.7s ease-in-out, visibility 0.7s ease-in-out;
    }
    .banner-slide.active {
      opacity: 1;
      visibility: visible;
      z-index: 10;
    }

    /* Tên sản phẩm đầy đủ không bị tràn ra ngoài và không bị cắt thiếu chữ (...) */
    .product-title-full {
      white-space: normal;
      word-wrap: break-word;
      overflow-wrap: break-word;
      word-break: break-word;
      line-height: 1.38;
    }

    /* Hiệu ứng nút liên hệ nổi bật */
    @keyframes pulseRing {
      0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(198, 134, 46, 0.7); }
      70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(198, 134, 46, 0); }
      100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(198, 134, 46, 0); }
    }
    .floating-pulse {
      animation: pulseRing 2s infinite;
    }
  </style>
</head>
<body class="bg-white text-brand-dark antialiased selection:bg-brand-accent selection:text-white">

  <!-- ==========================================================================
       [UX BUILDER: TOP BAR] - DÒNG ĐỊA CHỈ & THÔNG TIN CƠ BẢN (KHÔNG HIỂN THỊ TÙY CHỌN UX BUILDER)
       ========================================================================== -->
  <div class="w-full bg-brand-dark text-brand-light text-xs py-2 border-b border-brand-primary">
    <div class="ux-container flex flex-wrap items-center justify-between gap-2">
      <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
        <span class="inline-flex items-center gap-1.5 font-medium">
          <i class="fa-solid fa-globe text-brand-accent"></i>
          <strong>fbbase.com</strong> – Đào tạo pha chế F&amp;B Base
        </span>
        <span class="hidden sm:inline-flex items-center gap-1.5">
          <i class="fa-solid fa-location-dot text-brand-accent"></i>
          134/5 Yên Bái - Hải Châu - Đà Nẵng
        </span>
      </div>
      <div class="flex items-center gap-x-4">
        <span class="inline-flex items-center gap-1.5">
          <i class="fa-regular fa-clock text-brand-accent"></i>
          Làm việc: 08:00 - 21:00 (T2 - CN)
        </span>
        <a href="https://www.facebook.com/DaotaophacheFnBBase" target="_blank" rel="noopener" class="hover:text-brand-accent transition-colors inline-flex items-center gap-1">
          <i class="fa-brands fa-facebook"></i> Fanpage F&amp;B Base
        </a>
      </div>
    </div>
  </div>

  <!-- ==========================================================================
       [UX BUILDER: HEADER] - LOGO NHỎ GỌN + DANH MỤC TRÊN 1 HÀNG (KHÔNG ĐỂ NÚT GỌI NGAY)
       ========================================================================== -->
  <header class="sticky top-0 z-40 w-full bg-white/95 backdrop-blur border-b border-brand-border shadow-sm">
    <div class="ux-container py-2.5 flex items-center justify-between gap-3">
      
      <!-- LOGO CHỈNH GỌN NHỎ LẠI -->
      <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group focus:outline-none">
        <div class="w-10 h-10 sm:w-11 sm:h-11 rounded-lg border border-brand-border bg-brand-light p-1 flex items-center justify-center overflow-hidden shrink-0">
          <img 
            src="https://drive.google.com/thumbnail?id=1_Lmxu5-AwVn0MLzPvd0daTshr1HvShPm&sz=w300" 
            data-drive-id="1_Lmxu5-AwVn0MLzPvd0daTshr1HvShPm"
            alt="Logo Đào tạo pha chế F&B Base" 
            class="w-full h-full object-contain"
            onerror="handleDriveImgError(this, 'F&B')"
          >
        </div>
        <div class="leading-tight">
          <span class="block text-sm sm:text-base font-extrabold text-brand-dark tracking-tight group-hover:text-brand-accent transition-colors">F&amp;B BASE</span>
          <span class="block text-[10px] sm:text-[11px] font-medium text-stone-500">fbbase.com • Đà Nẵng</span>
        </div>
      </a>

      <!-- DANH MỤC MENU TRÊN MÁY TÍNH: CHỮ NHỎ GỌN, VIẾT LIỀN TRÊN 1 HÀNG (HOẶC XUỐNG HÀNG 2 NẾU HẸP, KHÔNG BẺ DÒNG TÊN DANH MỤC) -->
      <nav aria-label="Danh mục chính" class="hidden lg:flex flex-wrap items-center justify-end gap-x-1.5 xl:gap-x-2.5 gap-y-1 flex-1">
        <a href="#trang-chu" class="cat-nowrap px-2 py-1.5 rounded text-[12px] xl:text-[12.5px] font-semibold text-brand-dark hover:text-brand-accent hover:bg-brand-light transition-colors">Trang Chủ</a>
        <a href="#gioi-thieu" class="cat-nowrap px-2 py-1.5 rounded text-[12px] xl:text-[12.5px] font-semibold text-brand-dark hover:text-brand-accent hover:bg-brand-light transition-colors">Giới Thiệu</a>
        <a href="#khoa-hoc-pha-che" class="cat-nowrap px-2 py-1.5 rounded text-[12px] xl:text-[12.5px] font-semibold text-brand-dark hover:text-brand-accent hover:bg-brand-light transition-colors">Khóa Học Pha Chế</a>
        <a href="#dich-vu-setup" class="cat-nowrap px-2 py-1.5 rounded text-[12px] xl:text-[12.5px] font-semibold text-brand-dark hover:text-brand-accent hover:bg-brand-light transition-colors">Dịch Vụ Setup</a>
        <a href="#may-moc-thiet-bi" class="cat-nowrap px-2 py-1.5 rounded text-[12px] xl:text-[12.5px] font-semibold text-brand-dark hover:text-brand-accent hover:bg-brand-light transition-colors">Máy Móc Thiết Bị</a>
        <a href="#dung-cu-pha-che" class="cat-nowrap px-2 py-1.5 rounded text-[12px] xl:text-[12.5px] font-semibold text-brand-dark hover:text-brand-accent hover:bg-brand-light transition-colors">Dụng Cụ Pha Chế</a>
        <a href="#nguyen-lieu-pha-che" class="cat-nowrap px-2 py-1.5 rounded text-[12px] xl:text-[12.5px] font-semibold text-brand-dark hover:text-brand-accent hover:bg-brand-light transition-colors">Nguyên Liệu Pha Chế</a>
        <a href="#ly-tach-pha-che" class="cat-nowrap px-2 py-1.5 rounded text-[12px] xl:text-[12.5px] font-semibold text-brand-dark hover:text-brand-accent hover:bg-brand-light transition-colors">Ly Tách Pha Chế</a>
        <a href="#doi-tac" class="cat-nowrap px-2 py-1.5 rounded text-[12px] xl:text-[12.5px] font-semibold text-brand-dark hover:text-brand-accent hover:bg-brand-light transition-colors">Đối Tác</a>
        <a href="#tin-tuc" class="cat-nowrap px-2 py-1.5 rounded text-[12px] xl:text-[12.5px] font-semibold text-brand-dark hover:text-brand-accent hover:bg-brand-light transition-colors">Bài Viết</a>
        <a href="#bao-gia" class="cat-nowrap px-2 py-1.5 rounded text-[12px] xl:text-[12.5px] font-semibold text-brand-dark hover:text-brand-accent hover:bg-brand-light transition-colors">Báo Giá</a>
        <a href="#lien-he" class="cat-nowrap px-2 py-1.5 rounded text-[12px] xl:text-[12.5px] font-semibold text-brand-dark hover:text-brand-accent hover:bg-brand-light transition-colors">Liên Hệ</a>
      </nav>

      <!-- NÚT MỞ MENU TRÊN ĐIỆN THOẠI (KHÔNG ĐỂ NÚT GỌI NGAY TRÊN HEADER ĐỂ TRÁNH TRÀN VIỀN) -->
      <button 
        id="mobileMenuBtn" 
        type="button" 
        aria-label="Mở danh mục menu"
        class="lg:hidden inline-flex items-center gap-1.5 px-3 py-2 rounded-lg border border-brand-border bg-brand-light text-brand-dark text-xs font-bold hover:bg-brand-soft transition-colors shrink-0"
      >
        <i class="fa-solid fa-bars text-sm"></i>
        <span>Danh Mục</span>
      </button>
    </div>

    <!-- MENU DANH MỤC TRÊN ĐIỆN THOẠI (CHIA CỘT GỌN ĐẸP, KHÔNG BẺ DÒNG TÊN DANH MỤC) -->
    <div id="mobileMenuPanel" class="hidden lg:hidden border-t border-brand-border bg-brand-light">
      <div class="ux-container py-3 grid grid-cols-2 sm:grid-cols-3 gap-2">
        <a href="#trang-chu" class="mobile-nav-link cat-nowrap px-3 py-2 rounded-lg bg-white border border-brand-border text-xs font-semibold text-brand-dark hover:border-brand-accent"><i class="fa-solid fa-house text-brand-accent mr-1.5"></i>Trang Chủ</a>
        <a href="#gioi-thieu" class="mobile-nav-link cat-nowrap px-3 py-2 rounded-lg bg-white border border-brand-border text-xs font-semibold text-brand-dark hover:border-brand-accent"><i class="fa-solid fa-award text-brand-accent mr-1.5"></i>Giới Thiệu</a>
        <a href="#khoa-hoc-pha-che" class="mobile-nav-link cat-nowrap px-3 py-2 rounded-lg bg-white border border-brand-border text-xs font-semibold text-brand-dark hover:border-brand-accent"><i class="fa-solid fa-graduation-cap text-brand-accent mr-1.5"></i>Khóa Học Pha Chế</a>
        <a href="#dich-vu-setup" class="mobile-nav-link cat-nowrap px-3 py-2 rounded-lg bg-white border border-brand-border text-xs font-semibold text-brand-dark hover:border-brand-accent"><i class="fa-solid fa-store text-brand-accent mr-1.5"></i>Dịch Vụ Setup</a>
        <a href="#may-moc-thiet-bi" class="mobile-nav-link cat-nowrap px-3 py-2 rounded-lg bg-white border border-brand-border text-xs font-semibold text-brand-dark hover:border-brand-accent"><i class="fa-solid fa-gears text-brand-accent mr-1.5"></i>Máy Móc Thiết Bị</a>
        <a href="#dung-cu-pha-che" class="mobile-nav-link cat-nowrap px-3 py-2 rounded-lg bg-white border border-brand-border text-xs font-semibold text-brand-dark hover:border-brand-accent"><i class="fa-solid fa-blender text-brand-accent mr-1.5"></i>Dụng Cụ Pha Chế</a>
        <a href="#nguyen-lieu-pha-che" class="mobile-nav-link cat-nowrap px-3 py-2 rounded-lg bg-white border border-brand-border text-xs font-semibold text-brand-dark hover:border-brand-accent"><i class="fa-solid fa-jar text-brand-accent mr-1.5"></i>Nguyên Liệu Pha Chế</a>
        <a href="#ly-tach-pha-che" class="mobile-nav-link cat-nowrap px-3 py-2 rounded-lg bg-white border border-brand-border text-xs font-semibold text-brand-dark hover:border-brand-accent"><i class="fa-solid fa-martini-glass-citrus text-brand-accent mr-1.5"></i>Ly Tách Pha Chế</a>
        <a href="#doi-tac" class="mobile-nav-link cat-nowrap px-3 py-2 rounded-lg bg-white border border-brand-border text-xs font-semibold text-brand-dark hover:border-brand-accent"><i class="fa-solid fa-handshake text-brand-accent mr-1.5"></i>Đối Tác</a>
        <a href="#tin-tuc" class="mobile-nav-link cat-nowrap px-3 py-2 rounded-lg bg-white border border-brand-border text-xs font-semibold text-brand-dark hover:border-brand-accent"><i class="fa-regular fa-newspaper text-brand-accent mr-1.5"></i>Bài Viết</a>
        <a href="#bao-gia" class="mobile-nav-link cat-nowrap px-3 py-2 rounded-lg bg-white border border-brand-border text-xs font-semibold text-brand-dark hover:border-brand-accent"><i class="fa-solid fa-file-invoice-dollar text-brand-accent mr-1.5"></i>Yêu Cầu Báo Giá</a>
        <a href="#lien-he" class="mobile-nav-link cat-nowrap px-3 py-2 rounded-lg bg-white border border-brand-border text-xs font-semibold text-brand-dark hover:border-brand-accent"><i class="fa-solid fa-map-location-dot text-brand-accent mr-1.5"></i>Bản Đồ &amp; Liên Hệ</a>
      </div>
    </div>
  </header>

  <!-- ==========================================================================
       [UX BUILDER: THANH DANH MỤC NHANH TRANG CHỦ] - CHỮ NHỎ GỌN, ĐẸP TRÊN PC & MOBILE
       ========================================================================== -->
  <section class="w-full bg-brand-light border-b border-brand-border py-2.5">
    <div class="ux-container">
      <!-- Trên máy tính nằm gọn trên 1 hàng (hoặc xuống hàng 2), trên điện thoại chia lưới 2 cột đều đẹp -->
      <div class="grid grid-cols-2 sm:grid-cols-4 lg:flex lg:flex-wrap lg:items-center lg:justify-center gap-1.5 lg:gap-2">
        <a href="#khoa-hoc-pha-che" class="cat-nowrap justify-center px-2.5 py-1.5 rounded-md bg-white border border-brand-border text-[11.5px] xl:text-[12px] font-semibold text-brand-dark hover:bg-brand-dark hover:text-white transition-colors">
          <i class="fa-solid fa-mug-hot text-brand-accent mr-1.5"></i>Đào Tạo Barista
        </a>
        <a href="#khoa-hoc-pha-che" class="cat-nowrap justify-center px-2.5 py-1.5 rounded-md bg-white border border-brand-border text-[11.5px] xl:text-[12px] font-semibold text-brand-dark hover:bg-brand-dark hover:text-white transition-colors">
          <i class="fa-solid fa-plane-departure text-brand-accent mr-1.5"></i>Barista Du Học Sinh
        </a>
        <a href="#khoa-hoc-pha-che" class="cat-nowrap justify-center px-2.5 py-1.5 rounded-md bg-white border border-brand-border text-[11.5px] xl:text-[12px] font-semibold text-brand-dark hover:bg-brand-dark hover:text-white transition-colors">
          <i class="fa-solid fa-champagne-glasses text-brand-accent mr-1.5"></i>Đào Tạo Bartender
        </a>
        <a href="#dich-vu-setup" class="cat-nowrap justify-center px-2.5 py-1.5 rounded-md bg-white border border-brand-border text-[11.5px] xl:text-[12px] font-semibold text-brand-dark hover:bg-brand-dark hover:text-white transition-colors">
          <i class="fa-solid fa-compass-drafting text-brand-accent mr-1.5"></i>Setup Quán Trọn Gói
        </a>
        <a href="#may-moc-thiet-bi" class="cat-nowrap justify-center px-2.5 py-1.5 rounded-md bg-white border border-brand-border text-[11.5px] xl:text-[12px] font-semibold text-brand-dark hover:bg-brand-dark hover:text-white transition-colors">
          <i class="fa-solid fa-gears text-brand-accent mr-1.5"></i>Máy Móc Thiết Bị
        </a>
        <a href="#dung-cu-pha-che" class="cat-nowrap justify-center px-2.5 py-1.5 rounded-md bg-white border border-brand-border text-[11.5px] xl:text-[12px] font-semibold text-brand-dark hover:bg-brand-dark hover:text-white transition-colors">
          <i class="fa-solid fa-kitchen-set text-brand-accent mr-1.5"></i>Dụng Cụ Pha Chế
        </a>
        <a href="#nguyen-lieu-pha-che" class="cat-nowrap justify-center px-2.5 py-1.5 rounded-md bg-white border border-brand-border text-[11.5px] xl:text-[12px] font-semibold text-brand-dark hover:bg-brand-dark hover:text-white transition-colors">
          <i class="fa-solid fa-cubes-stacked text-brand-accent mr-1.5"></i>Nguyên Liệu Pha Chế
        </a>
        <a href="#ly-tach-pha-che" class="cat-nowrap justify-center px-2.5 py-1.5 rounded-md bg-white border border-brand-border text-[11.5px] xl:text-[12px] font-semibold text-brand-dark hover:bg-brand-dark hover:text-white transition-colors">
          <i class="fa-solid fa-wine-glass text-brand-accent mr-1.5"></i>Ly Tách Pha Chế
        </a>
      </div>
    </div>
  </section>

  <!-- ==========================================================================
       [UX BUILDER: SLIDER 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU]
       - Hình ảnh và chữ nằm gọn hoàn toàn bên trong banner
       - Chữ cách xa viền ảnh banner (padding an toàn lớn)
       - Không bị thiếu chữ trên cả điện thoại và máy tính
       ========================================================================== -->
  <section id="trang-chu" class="w-full py-4 sm:py-6 bg-white">
    <div class="ux-container">
      <div class="banner-slider-viewport shadow-md border border-brand-border" id="heroSlider">
        
        <!-- BANNER SLIDE 1 -->
        <div class="banner-slide active" data-slide="0">
          <div class="w-full h-full bg-gradient-to-r from-[#23130C] via-[#3A2115] to-[#4E2E1E] flex items-center">
            <!-- Khoảng đệm cách xa viền banner (px-8 sm:px-14 lg:px-20 py-6 sm:py-10) -->
            <div class="w-full h-full px-8 sm:px-14 lg:px-20 py-6 sm:py-10 grid grid-cols-1 md:grid-cols-12 items-center gap-4 lg:gap-8">
              <div class="md:col-span-7 text-left space-y-2 sm:space-y-3.5">
                <p class="text-brand-accent text-xs sm:text-sm font-bold uppercase tracking-wider">
                  HỌC VIỆN ĐÀO TẠO PHA CHẾ &amp; SETUP QUÁN F&amp;B BASE
                </p>
                <h1 class="text-white text-lg sm:text-2xl lg:text-3xl xl:text-4xl font-extrabold leading-snug">
                  Nền Tảng Vững Chắc Cho Sự Nghiệp Pha Chế Chuyên Nghiệp
                </h1>
                <p class="text-stone-200 text-xs sm:text-sm lg:text-base leading-relaxed">
                  Đào tạo thực chiến 80% thực hành: Barista, Bartender, Pha chế tổng hợp, Mở quán cấp tốc &amp; Barista Du học sinh. Cam kết chất lượng đầu ra 10/10 tại 134/5 Yên Bái, Hải Châu, Đà Nẵng.
                </p>
                <div class="pt-1 sm:pt-2 flex flex-wrap items-center gap-2.5">
                  <a href="#khoa-hoc-pha-che" class="px-4 py-2 sm:px-5 sm:py-2.5 rounded-lg bg-brand-accent text-white text-xs sm:text-sm font-bold hover:bg-amber-600 transition-colors">
                    Xem Các Khóa Học
                  </a>
                  <a href="#bao-gia" class="px-4 py-2 sm:px-5 sm:py-2.5 rounded-lg bg-white/10 text-white border border-white/30 text-xs sm:text-sm font-semibold hover:bg-white/20 transition-colors">
                    Nhận Tư Vấn &amp; Báo Giá
                  </a>
                </div>
              </div>
              <div class="hidden md:flex md:col-span-5 items-center justify-center h-full">
                <div class="w-full max-w-[340px] h-[230px] lg:h-[290px] rounded-xl overflow-hidden border-2 border-brand-accent/60 shadow-lg bg-brand-primary">
                  <img 
                    src="https://drive.google.com/thumbnail?id=1rGho5fg969qDLR_0HwjCLl07fvvXFcnD&sz=w1000" 
                    data-drive-id="1rGho5fg969qDLR_0HwjCLl07fvvXFcnD"
                    alt="Đào tạo pha chế thực chiến F&B Base Đà Nẵng" 
                    class="w-full h-full object-cover"
                    onerror="handleDriveImgError(this, 'Đào Tạo Pha Chế F&B Base')"
                  >
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- BANNER SLIDE 2 (KÍCH THƯỚC BẰNG NHAU 100%) -->
        <div class="banner-slide" data-slide="1">
          <div class="w-full h-full bg-gradient-to-r from-[#2D1A10] via-[#452819] to-[#23130C] flex items-center">
            <!-- Khoảng đệm cách xa viền banner (px-8 sm:px-14 lg:px-20 py-6 sm:py-10) -->
            <div class="w-full h-full px-8 sm:px-14 lg:px-20 py-6 sm:py-10 grid grid-cols-1 md:grid-cols-12 items-center gap-4 lg:gap-8">
              <div class="md:col-span-7 text-left space-y-2 sm:space-y-3.5">
                <p class="text-brand-accent text-xs sm:text-sm font-bold uppercase tracking-wider">
                  GIẢI PHÁP F&amp;B TOÀN DIỆN – FBBASE.COM
                </p>
                <h2 class="text-white text-lg sm:text-2xl lg:text-3xl xl:text-4xl font-extrabold leading-snug">
                  Tư Vấn Setup Quán Cà Phê, Trà Sữa &amp; Cung Ứng Thiết Bị, Nguyên Liệu
                </h2>
                <p class="text-stone-200 text-xs sm:text-sm lg:text-base leading-relaxed">
                  Cung cấp trọn gói Máy móc thiết bị pha chế, Dụng cụ quầy Bar, Nguyên liệu pha chế chính hãng, Ly tách thủy tinh &amp; Setup vận hành quán tối ưu chi phí tại Đà Nẵng và miền Trung.
                </p>
                <div class="pt-1 sm:pt-2 flex flex-wrap items-center gap-2.5">
                  <a href="#may-moc-thiet-bi" class="px-4 py-2 sm:px-5 sm:py-2.5 rounded-lg bg-brand-accent text-white text-xs sm:text-sm font-bold hover:bg-amber-600 transition-colors">
                    Xem Sản Phẩm &amp; Thiết Bị
                  </a>
                  <a href="#dich-vu-setup" class="px-4 py-2 sm:px-5 sm:py-2.5 rounded-lg bg-white/10 text-white border border-white/30 text-xs sm:text-sm font-semibold hover:bg-white/20 transition-colors">
                    Dịch Vụ Setup Quán
                  </a>
                </div>
              </div>
              <div class="hidden md:flex md:col-span-5 items-center justify-center h-full">
                <div class="w-full max-w-[340px] h-[230px] lg:h-[290px] rounded-xl overflow-hidden border-2 border-brand-accent/60 shadow-lg bg-brand-primary">
                  <img 
                    src="https://drive.google.com/thumbnail?id=1oEbPHQbnw-_fN12EN1L9-db6ScbpLutN&sz=w1000" 
                    data-drive-id="1oEbPHQbnw-_fN12EN1L9-db6ScbpLutN"
                    alt="Setup quán cà phê và cung ứng máy móc nguyên liệu F&B Base" 
                    class="w-full h-full object-cover"
                    onerror="handleDriveImgError(this, 'Setup Quán & Thiết Bị F&B Base')"
                  >
                </div>
              </div>
            </div>
          </div>
        </div>

        <!-- Nút điều hướng qua lại nằm sát mép ngoài cùng, không đè lên chữ -->
        <button type="button" id="prevBannerBtn" aria-label="Banner trước" class="absolute left-2 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/40 text-white hover:bg-brand-accent transition-colors flex items-center justify-center">
          <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
        </button>
        <button type="button" id="nextBannerBtn" aria-label="Banner tiếp theo" class="absolute right-2 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/40 text-white hover:bg-brand-accent transition-colors flex items-center justify-center">
          <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
        </button>

        <!-- Chấm chỉ báo Slide -->
        <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
          <button type="button" data-goto="0" aria-label="Slide 1" class="banner-dot w-6 h-2 rounded-full bg-brand-accent transition-all"></button>
          <button type="button" data-goto="1" aria-label="Slide 2" class="banner-dot w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all"></button>
        </div>
      </div>
    </div>
  </section>

  <!-- ==========================================================================
       [UX BUILDER: SECTION GIỚI THIỆU & 4 LĨNH VỰC TRỌNG TÂM GIỐNG WEB MẪU VINCENTDANANG.VN]
       ========================================================================== -->
  <section id="gioi-thieu" class="w-full py-8 sm:py-10 bg-brand-light border-y border-brand-border">
    <div class="ux-container">
      <!-- Phần giới thiệu mở đầu giống Vincent – We Provide F&B Solutions -->
      <div class="max-w-4xl mx-auto text-center mb-8">
        <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-brand-dark uppercase tracking-tight">
          F&amp;B Base – We Provide F&amp;B Solutions
        </h2>
        <div class="w-20 h-1 bg-brand-accent mx-auto my-3 rounded-full"></div>
        <p class="text-xs sm:text-sm lg:text-base text-stone-700 leading-relaxed">
          <strong>Đào tạo pha chế F&amp;B Base (fbbase.com)</strong> tự hào là học viện đào tạo nghề pha chế chuyên sâu (Barista, Bartender, Bar trưởng, Mở quán cấp tốc, Barista dành cho Du học sinh &amp; Working Holiday) và nhà cung ứng giải pháp F&amp;B toàn diện tại Đà Nẵng. Chúng tôi mang đến nguyên liệu pha chế chọn lọc, máy móc thiết bị thẩm định kỹ càng về chất lượng cùng dịch vụ tư vấn – setup – vận hành quán cà phê, trà sữa, cocktail bar tối ưu chi phí nhất. Đặc biệt, F&amp;B Base có chương trình đào tạo nghề miễn phí dành cho thanh niên có hoàn cảnh khó khăn hoặc mồ côi.
        </p>
      </div>

      <!-- 4 Cột Giải Pháp Cốt Lõi (Giống bố cục 4 khối Nguyên Liệu - Máy Móc - Đào Tạo - Setup của web mẫu) -->
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-5">
        
        <!-- Khối 1: Nguyên liệu pha chế -->
        <div class="bg-white rounded-xl border border-brand-border overflow-hidden shadow-sm flex flex-col">
          <div class="h-44 w-full bg-stone-100 overflow-hidden">
            <img 
              src="https://drive.google.com/thumbnail?id=1Zm8xvocINo_Gco_CWfjlO8Xjw2uA47NN&sz=w800" 
              data-drive-id="1Zm8xvocINo_Gco_CWfjlO8Xjw2uA47NN"
              alt="Nguyên liệu pha chế F&B Base" 
              class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
              onerror="handleDriveImgError(this, 'Nguyên Liệu Pha Chế')"
            >
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between">
            <div>
              <h3 class="text-sm sm:text-base font-extrabold text-brand-dark uppercase mb-2">NGUYÊN LIỆU PHA CHẾ</h3>
              <p class="text-xs sm:text-sm text-stone-600 leading-relaxed">
                Hương vị khác biệt và độc đáo chính là yếu tố giữ chân khách hàng. F&amp;B Base chọn lọc nguyên liệu pha chế có nguồn gốc xuất xứ rõ ràng, an toàn sức khỏe và tạo phong cách riêng cho đồ uống của quán.
              </p>
            </div>
            <a href="#nguyen-lieu-pha-che" class="mt-3 inline-flex items-center text-xs font-bold text-brand-accent hover:underline">
              Xem danh mục nguyên liệu <i class="fa-solid fa-arrow-right ml-1.5"></i>
            </a>
          </div>
        </div>

        <!-- Khối 2: Máy móc và thiết bị -->
        <div class="bg-white rounded-xl border border-brand-border overflow-hidden shadow-sm flex flex-col">
          <div class="h-44 w-full bg-stone-100 overflow-hidden">
            <img 
              src="https://drive.google.com/thumbnail?id=1o0wBE5h1O8gI551OPfCPLYJLQzQQCD3-&sz=w800" 
              data-drive-id="1o0wBE5h1O8gI551OPfCPLYJLQzQQCD3-"
              alt="Máy móc và thiết bị pha chế F&B Base" 
              class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
              onerror="handleDriveImgError(this, 'Máy Móc Thiết Bị')"
            >
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between">
            <div>
              <h3 class="text-sm sm:text-base font-extrabold text-brand-dark uppercase mb-2">MÁY MÓC VÀ THIẾT BỊ</h3>
              <p class="text-xs sm:text-sm text-stone-600 leading-relaxed">
                Tất cả thiết bị máy móc trong kinh doanh cà phê &amp; trà sữa được F&amp;B Base tuyển chọn đáp ứng tính năng kỹ thuật, độ bền và phân khúc giá phù hợp với từng mô hình quán, mang lại hiệu quả đầu tư cao nhất.
              </p>
            </div>
            <a href="#may-moc-thiet-bi" class="mt-3 inline-flex items-center text-xs font-bold text-brand-accent hover:underline">
              Xem máy móc thiết bị <i class="fa-solid fa-arrow-right ml-1.5"></i>
            </a>
          </div>
        </div>

        <!-- Khối 3: Đào tạo Barista & Bartender -->
        <div class="bg-white rounded-xl border border-brand-border overflow-hidden shadow-sm flex flex-col">
          <div class="h-44 w-full bg-stone-100 overflow-hidden">
            <img 
              src="https://drive.google.com/thumbnail?id=1ET0rUw8l3P5eMHkFFbxfloOQ7IwdHndj&sz=w800" 
              data-drive-id="1ET0rUw8l3P5eMHkFFbxfloOQ7IwdHndj"
              alt="Đào tạo Barista chuyên nghiệp F&B Base" 
              class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
              onerror="handleDriveImgError(this, 'Đào Tạo Barista')"
            >
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between">
            <div>
              <h3 class="text-sm sm:text-base font-extrabold text-brand-dark uppercase mb-2">ĐÀO TẠO BARISTA &amp; PHA CHẾ</h3>
              <p class="text-xs sm:text-sm text-stone-600 leading-relaxed">
                Giáo trình chuyên sâu thực chiến với 80% thời lượng thực hành cùng giảng viên kỳ cựu. Đáp ứng tiêu chuẩn đi làm quốc tế (Du học sinh Úc, Working Holiday), Bar trưởng hoặc tự tin khởi nghiệp mở quán.
              </p>
            </div>
            <a href="#khoa-hoc-pha-che" class="mt-3 inline-flex items-center text-xs font-bold text-brand-accent hover:underline">
              Xem các khóa đào tạo <i class="fa-solid fa-arrow-right ml-1.5"></i>
            </a>
          </div>
        </div>

        <!-- Khối 4: Tư vấn, Setup mô hình Cafe & Trà sữa -->
        <div class="bg-white rounded-xl border border-brand-border overflow-hidden shadow-sm flex flex-col">
          <div class="h-44 w-full bg-stone-100 overflow-hidden">
            <img 
              src="https://drive.google.com/thumbnail?id=1wU8q1SH4yjgsfkgiY2mOZIhNXUL-H57m&sz=w800" 
              data-drive-id="1wU8q1SH4yjgsfkgiY2mOZIhNXUL-H57m"
              alt="Tư vấn Setup mô hình Cafe và Trà sữa F&B Base" 
              class="w-full h-full object-cover hover:scale-105 transition-transform duration-300"
              onerror="handleDriveImgError(this, 'Tư Vấn & Setup Quán')"
            >
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between">
            <div>
              <h3 class="text-sm sm:text-base font-extrabold text-brand-dark uppercase mb-2">TƯ VẤN, SETUP CAFE &amp; TRÀ SỮA</h3>
              <p class="text-xs sm:text-sm text-stone-600 leading-relaxed">
                Giải pháp toàn diện giúp tiết kiệm chi phí: Khảo sát mặt bằng, thiết kế công năng quầy bar, xây dựng menu tính cost định lượng, quản lý nguyên liệu, đào tạo nhân sự và vận hành thực tế.
              </p>
            </div>
            <a href="#dich-vu-setup" class="mt-3 inline-flex items-center text-xs font-bold text-brand-accent hover:underline">
              Xem gói dịch vụ setup <i class="fa-solid fa-arrow-right ml-1.5"></i>
            </a>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- ==========================================================================
       [UX BUILDER: CÁC KHOÁ HỌC PHA CHẾ TIÊU BIỂU TẠI F&B BASE]
       - Chia 2 cột trên điện thoại, 3-6 cột trên máy tính
       - Không để nhãn dán ở trang chủ
       - Tên khóa học/sản phẩm đầy đủ không bị tràn hay thiếu chữ
       ========================================================================== -->
  <section id="khoa-hoc-pha-che" class="w-full py-8 sm:py-10 bg-white">
    <div class="ux-container">
      <div class="flatsome-section-title">
        <b></b>
        <span class="text-base sm:text-xl lg:text-2xl">CÁC KHOÁ HỌC PHA CHẾ TIÊU BIỂU TẠI F&amp;B BASE</span>
        <b></b>
      </div>

      <!-- Lưới 2 cột trên điện thoại (grid-cols-2), 3 cột trên máy tính (lg:grid-cols-3) -->
      <div class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-5">
        
        <!-- Khóa học 1 -->
        <div class="bg-brand-light rounded-xl border border-brand-border overflow-hidden flex flex-col justify-between hover:shadow-md transition-shadow">
          <div>
            <div class="aspect-[4/3] w-full bg-stone-200 overflow-hidden">
              <img 
                src="https://drive.google.com/thumbnail?id=1rGho5fg969qDLR_0HwjCLl07fvvXFcnD&sz=w800" 
                data-drive-id="1rGho5fg969qDLR_0HwjCLl07fvvXFcnD"
                alt="Khoá Học Pha Chế Tổng Hợp" 
                class="w-full h-full object-cover"
                onerror="handleDriveImgError(this, 'Khoá Học Pha Chế Tổng Hợp')"
              >
            </div>
            <div class="p-3 sm:p-4">
              <h3 class="product-title-full text-xs sm:text-base font-bold text-brand-dark mb-1.5">
                Khoá Học Pha Chế Tổng Hợp Chuyên Nghiệp
              </h3>
              <p class="text-[11px] sm:text-xs text-stone-600 leading-relaxed">
                Nắm vững nền tảng và thực hành 80% các dòng đồ uống cà phê truyền thống, cà phê máy, trà trái cây nhiệt đới, đá xay, sinh tố, soda &amp; kem cheese.
              </p>
            </div>
          </div>
          <div class="px-3 pb-3 sm:px-4 sm:pb-4 pt-1 flex items-center justify-between border-t border-brand-border/60 mt-2">
            <span class="text-xs sm:text-sm font-extrabold text-brand-accent">Thực hành 80%</span>
            <button type="button" onclick="prefillQuote('Khoá Học Pha Chế Tổng Hợp Chuyên Nghiệp')" class="px-2.5 py-1.5 rounded bg-brand-dark text-white text-[11px] sm:text-xs font-semibold hover:bg-brand-accent transition-colors">
              Đăng ký tư vấn
            </button>
          </div>
        </div>

        <!-- Khóa học 2 -->
        <div class="bg-brand-light rounded-xl border border-brand-border overflow-hidden flex flex-col justify-between hover:shadow-md transition-shadow">
          <div>
            <div class="aspect-[4/3] w-full bg-stone-200 overflow-hidden">
              <img 
                src="https://drive.google.com/thumbnail?id=1oEbPHQbnw-_fN12EN1L9-db6ScbpLutN&sz=w800" 
                data-drive-id="1oEbPHQbnw-_fN12EN1L9-db6ScbpLutN"
                alt="Khoá Học Pha Chế Trà Sữa & Trà Trái Cây" 
                class="w-full h-full object-cover"
                onerror="handleDriveImgError(this, 'Khoá Học Pha Chế Trà Sữa')"
              >
            </div>
            <div class="p-3 sm:p-4">
              <h3 class="product-title-full text-xs sm:text-base font-bold text-brand-dark mb-1.5">
                Khoá Học Pha Chế Trà Sữa &amp; Topping Hiện Đại
              </h3>
              <p class="text-[11px] sm:text-xs text-stone-600 leading-relaxed">
                Bí quyết ủ cốt trà đậm vị, pha chế trà sữa chuẩn thương hiệu lớn, nấu trân châu, pudding, thạch củ năng và cập nhật menu đồ uống xu hướng mới nhất.
              </p>
            </div>
          </div>
          <div class="px-3 pb-3 sm:px-4 sm:pb-4 pt-1 flex items-center justify-between border-t border-brand-border/60 mt-2">
            <span class="text-xs sm:text-sm font-extrabold text-brand-accent">Chuẩn vị mở quán</span>
            <button type="button" onclick="prefillQuote('Khoá Học Pha Chế Trà Sữa & Topping Hiện Đại')" class="px-2.5 py-1.5 rounded bg-brand-dark text-white text-[11px] sm:text-xs font-semibold hover:bg-brand-accent transition-colors">
              Đăng ký tư vấn
            </button>
          </div>
        </div>

        <!-- Khóa học 3 -->
        <div class="bg-brand-light rounded-xl border border-brand-border overflow-hidden flex flex-col justify-between hover:shadow-md transition-shadow">
          <div>
            <div class="aspect-[4/3] w-full bg-stone-200 overflow-hidden">
              <img 
                src="https://drive.google.com/thumbnail?id=1ET0rUw8l3P5eMHkFFbxfloOQ7IwdHndj&sz=w800" 
                data-drive-id="1ET0rUw8l3P5eMHkFFbxfloOQ7IwdHndj"
                alt="Khoá Học Pha Chế Barista & Latte Art" 
                class="w-full h-full object-cover"
                onerror="handleDriveImgError(this, 'Khoá Học Pha Chế Barista')"
              >
            </div>
            <div class="p-3 sm:p-4">
              <h3 class="product-title-full text-xs sm:text-base font-bold text-brand-dark mb-1.5">
                Khoá Học Pha Chế Barista &amp; Latte Art Chuyên Sâu
              </h3>
              <p class="text-[11px] sm:text-xs text-stone-600 leading-relaxed">
                Làm chủ chiết xuất Espresso, kiểm soát nhiệt độ và độ mịn bọt sữa, tạo hình Latte Art từ cơ bản đến nâng cao và quy trình vận hành máy pha cà phê Ý.
              </p>
            </div>
          </div>
          <div class="px-3 pb-3 sm:px-4 sm:pb-4 pt-1 flex items-center justify-between border-t border-brand-border/60 mt-2">
            <span class="text-xs sm:text-sm font-extrabold text-brand-accent">Kèm sát 1-1</span>
            <button type="button" onclick="prefillQuote('Khoá Học Pha Chế Barista & Latte Art Chuyên Sâu')" class="px-2.5 py-1.5 rounded bg-brand-dark text-white text-[11px] sm:text-xs font-semibold hover:bg-brand-accent transition-colors">
              Đăng ký tư vấn
            </button>
          </div>
        </div>

        <!-- Khóa học 4 -->
        <div class="bg-brand-light rounded-xl border border-brand-border overflow-hidden flex flex-col justify-between hover:shadow-md transition-shadow">
          <div>
            <div class="aspect-[4/3] w-full bg-stone-200 overflow-hidden">
              <img 
                src="https://drive.google.com/thumbnail?id=1ZF3YcSyo7r56g1n6dSe8G8c9VQZ29GBk&sz=w800" 
                data-drive-id="1ZF3YcSyo7r56g1n6dSe8G8c9VQZ29GBk"
                alt="Khóa Học Pha Chế Rượu Cocktail Bartender" 
                class="w-full h-full object-cover"
                onerror="handleDriveImgError(this, 'Khóa Học Pha Chế Rượu Cocktail')"
              >
            </div>
            <div class="p-3 sm:p-4">
              <h3 class="product-title-full text-xs sm:text-base font-bold text-brand-dark mb-1.5">
                Khóa Học Pha Chế Rượu Cocktail &amp; Nghiệp Vụ Bartender
              </h3>
              <p class="text-[11px] sm:text-xs text-stone-600 leading-relaxed">
                Đào tạo kiến thức rượu nền, kỹ thuật Shake, Stir, Build, Garnish, công thức Classic &amp; Signature Cocktail chuẩn quầy Bar – Pub – Khách sạn 4-5 sao.
              </p>
            </div>
          </div>
          <div class="px-3 pb-3 sm:px-4 sm:pb-4 pt-1 flex items-center justify-between border-t border-brand-border/60 mt-2">
            <span class="text-xs sm:text-sm font-extrabold text-brand-accent">Chuẩn Quầy Bar</span>
            <button type="button" onclick="prefillQuote('Khóa Học Pha Chế Rượu Cocktail & Nghiệp Vụ Bartender')" class="px-2.5 py-1.5 rounded bg-brand-dark text-white text-[11px] sm:text-xs font-semibold hover:bg-brand-accent transition-colors">
              Đăng ký tư vấn
            </button>
          </div>
        </div>

        <!-- Khóa học 5 -->
        <div class="bg-brand-light rounded-xl border border-brand-border overflow-hidden flex flex-col justify-between hover:shadow-md transition-shadow">
          <div>
            <div class="aspect-[4/3] w-full bg-stone-200 overflow-hidden">
              <img 
                src="https://drive.google.com/thumbnail?id=1w-Z77OHU-cAzdUyvLZpE6V7KMuajJ9-4&sz=w800" 
                data-drive-id="1w-Z77OHU-cAzdUyvLZpE6V7KMuajJ9-4"
                alt="Khoá Học Pha Chế Mở Quán Cấp Tốc" 
                class="w-full h-full object-cover"
                onerror="handleDriveImgError(this, 'Khoá Học Pha Chế Mở Quán')"
              >
            </div>
            <div class="p-3 sm:p-4">
              <h3 class="product-title-full text-xs sm:text-base font-bold text-brand-dark mb-1.5">
                Khoá Học Pha Chế Mở Quán &amp; Quản Lý Vận Hành Quán
              </h3>
              <p class="text-[11px] sm:text-xs text-stone-600 leading-relaxed">
                Dành riêng cho chủ quán: Xây dựng menu theo mô hình kinh doanh, tính cost nguyên liệu, kiểm soát chi phí, quản lý nhân sự và thực hành pha chế toàn diện.
              </p>
            </div>
          </div>
          <div class="px-3 pb-3 sm:px-4 sm:pb-4 pt-1 flex items-center justify-between border-t border-brand-border/60 mt-2">
            <span class="text-xs sm:text-sm font-extrabold text-brand-accent">Hỗ trợ trọn đời</span>
            <button type="button" onclick="prefillQuote('Khoá Học Pha Chế Mở Quán & Quản Lý Vận Hành Quán')" class="px-2.5 py-1.5 rounded bg-brand-dark text-white text-[11px] sm:text-xs font-semibold hover:bg-brand-accent transition-colors">
              Đăng ký tư vấn
            </button>
          </div>
        </div>

        <!-- Khóa học 6 (Đặc trưng Fanpage F&B Base) -->
        <div class="bg-brand-light rounded-xl border border-brand-border overflow-hidden flex flex-col justify-between hover:shadow-md transition-shadow">
          <div>
            <div class="aspect-[4/3] w-full bg-stone-200 overflow-hidden">
              <img 
                src="https://drive.google.com/thumbnail?id=1MrWhPGxC_ZL_3Il-KwIS7J3GD0LNemZK&sz=w800" 
                data-drive-id="1MrWhPGxC_ZL_3Il-KwIS7J3GD0LNemZK"
                alt="Khóa Học Barista Du Học Sinh & Working Holiday" 
                class="w-full h-full object-cover"
                onerror="handleDriveImgError(this, 'Barista Du Học Sinh')"
              >
            </div>
            <div class="p-3 sm:p-4">
              <h3 class="product-title-full text-xs sm:text-base font-bold text-brand-dark mb-1.5">
                Khóa Học Barista Dành Cho Du Học Sinh &amp; Working Holiday
              </h3>
              <p class="text-[11px] sm:text-xs text-stone-600 leading-relaxed">
                Lộ trình thực hành cấp tốc chuẩn quốc tế (Úc, Canada, Châu Âu): Thực hành Espresso, Flat White, Cappuccino, Latte Art &amp; tác phong đứng quầy chuyên nghiệp.
              </p>
            </div>
          </div>
          <div class="px-3 pb-3 sm:px-4 sm:pb-4 pt-1 flex items-center justify-between border-t border-brand-border/60 mt-2">
            <span class="text-xs sm:text-sm font-extrabold text-brand-accent">Chuẩn Quốc Tế</span>
            <button type="button" onclick="prefillQuote('Khóa Học Barista Dành Cho Du Học Sinh & Working Holiday')" class="px-2.5 py-1.5 rounded bg-brand-dark text-white text-[11px] sm:text-xs font-semibold hover:bg-brand-accent transition-colors">
              Đăng ký tư vấn
            </button>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- ==========================================================================
       [UX BUILDER: SECTION SỨ MỆNH & THỐNG KÊ NHƯ WEB MẪU VINCENTDANANG.VN]
       ========================================================================== -->
  <section class="w-full py-8 sm:py-10 bg-brand-dark text-white">
    <div class="ux-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 items-center gap-6">
        <div class="lg:col-span-7 space-y-2 text-center lg:text-left">
          <p class="text-brand-accent text-xs sm:text-sm font-bold uppercase tracking-widest">SỨ MỆNH CỦA CHÚNG TÔI</p>
          <h2 class="text-base sm:text-xl lg:text-2xl font-extrabold leading-snug uppercase">
            HỌC VIỆN ĐÀO TẠO PHA CHẾ F&amp;B BASE ĐƯỢC THÀNH LẬP VỚI SỨ MỆNH VÌ SỰ THÀNH CÔNG CỦA CỘNG ĐỒNG KINH DOANH ĐỒ UỐNG &amp; BARISTA VIỆT NAM
          </h2>
          <p class="text-stone-300 text-xs sm:text-sm leading-relaxed">
            Cam kết chất lượng đầu ra 10/10, hỗ trợ học viên trọn đời và đồng hành cùng cộng đồng cựu học viên F&amp;B Base tại Đà Nẵng.
          </p>
        </div>
        <div class="lg:col-span-5 grid grid-cols-3 gap-3 text-center">
          <div class="p-3 sm:p-4 rounded-xl bg-white/10 border border-white/15">
            <div class="text-lg sm:text-2xl lg:text-3xl font-extrabold text-brand-accent">5000+</div>
            <div class="text-[11px] sm:text-xs text-stone-200 mt-1">Lượt quan tâm</div>
          </div>
          <div class="p-3 sm:p-4 rounded-xl bg-white/10 border border-white/15">
            <div class="text-lg sm:text-2xl lg:text-3xl font-extrabold text-brand-accent">120+</div>
            <div class="text-[11px] sm:text-xs text-stone-200 mt-1">Khóa học &amp; Dự án</div>
          </div>
          <div class="p-3 sm:p-4 rounded-xl bg-white/10 border border-white/15">
            <div class="text-lg sm:text-2xl lg:text-3xl font-extrabold text-brand-accent">2500+</div>
            <div class="text-[11px] sm:text-xs text-stone-200 mt-1">Học viên</div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ==========================================================================
       [UX BUILDER: DỊCH VỤ SETUP QUÁN & BỘ 9 HÌNH ẢNH THỰC TẾ F&B BASE TỪ GOOGLE DRIVE]
       ========================================================================== -->
  <section id="dich-vu-setup" class="w-full py-8 sm:py-10 bg-brand-soft border-b border-brand-border">
    <div class="ux-container">
      <div class="flatsome-section-title">
        <b></b>
        <span class="text-base sm:text-xl lg:text-2xl">DỊCH VỤ SETUP QUÁN TRỌN GÓI &amp; HÌNH ẢNH THỰC TẾ TẠI F&amp;B BASE</span>
        <b></b>
      </div>

      <!-- 3 Gói Dịch Vụ Setup giống cấu trúc menu Dịch Vụ Setup của web mẫu -->
      <div class="grid grid-cols-1 md:grid-cols-3 gap-4 mb-8">
        <div class="bg-white p-5 rounded-xl border border-brand-border shadow-sm flex flex-col justify-between">
          <div>
            <h3 class="text-sm sm:text-base font-extrabold text-brand-dark uppercase mb-2">1. GÓI DỊCH VỤ SETUP MENU &amp; ĐÀO TẠO</h3>
            <p class="text-xs sm:text-sm text-stone-600 leading-relaxed">
              Nghiên cứu &amp; xây dựng menu đồ uống đặc trưng theo mô hình quán, tính giá cost định lượng chi tiết từng ly, chuyển giao công thức và đào tạo nhân viên pha chế thành thạo.
            </p>
          </div>
          <button type="button" onclick="prefillQuote('Gói Dịch Vụ Setup Menu & Đào Tạo')" class="mt-4 w-full py-2 rounded-lg bg-brand-primary text-white text-xs font-bold hover:bg-brand-accent transition-colors">
            Nhận báo giá gói Setup Menu
          </button>
        </div>

        <div class="bg-white p-5 rounded-xl border border-brand-border shadow-sm flex flex-col justify-between">
          <div>
            <h3 class="text-sm sm:text-base font-extrabold text-brand-dark uppercase mb-2">2. GÓI DỊCH VỤ SETUP QUÁN CƠ BẢN</h3>
            <p class="text-xs sm:text-sm text-stone-600 leading-relaxed">
              Tư vấn bố trí công năng quầy bar chuẩn quy trình 1 chiều, lên danh mục máy móc thiết bị – dụng cụ – nguyên liệu tối ưu ngân sách, đào tạo đội ngũ nhân sự và hỗ trợ khai trương.
            </p>
          </div>
          <button type="button" onclick="prefillQuote('Gói Dịch Vụ Setup Quán Cơ Bản')" class="mt-4 w-full py-2 rounded-lg bg-brand-primary text-white text-xs font-bold hover:bg-brand-accent transition-colors">
            Nhận báo giá gói Setup Cơ Bản
          </button>
        </div>

        <div class="bg-white p-5 rounded-xl border border-brand-border shadow-sm flex flex-col justify-between">
          <div>
            <h3 class="text-sm sm:text-base font-extrabold text-brand-dark uppercase mb-2">3. GÓI DỊCH VỤ SETUP TRỌN GÓI NÂNG CAO</h3>
            <p class="text-xs sm:text-sm text-stone-600 leading-relaxed">
              Đồng hành từ A-Z như dự án Zen Coffee: Khảo sát mặt bằng, định hình concept, thiết kế thi công quầy bar, lắp đặt thiết bị, xây dựng quy trình vận hành – quản lý và chuyển giao toàn diện.
            </p>
          </div>
          <button type="button" onclick="prefillQuote('Gói Dịch Vụ Setup Trọn Gói Nâng Cao')" class="mt-4 w-full py-2 rounded-lg bg-brand-primary text-white text-xs font-bold hover:bg-brand-accent transition-colors">
            Nhận báo giá gói Setup Nâng Cao
          </button>
        </div>
      </div>

      <!-- BỘ 9 ẢNH THỰC TẾ TỪ GOOGLE DRIVE (CHIA 2 CỘT TRÊN ĐIỆN THOẠI, 3 CỘT TRÊN MÁY TÍNH) -->
      <div class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-4">
        <div class="bg-white rounded-xl border border-brand-border overflow-hidden">
          <div class="aspect-[4/3] w-full bg-stone-100 overflow-hidden">
            <img src="https://drive.google.com/thumbnail?id=1rGho5fg969qDLR_0HwjCLl07fvvXFcnD&sz=w800" data-drive-id="1rGho5fg969qDLR_0HwjCLl07fvvXFcnD" alt="Thực hành pha chế Espresso & Latte Art tại F&B Base" class="w-full h-full object-cover" onerror="handleDriveImgError(this, 'Ảnh Thực Tế 1')">
          </div>
          <div class="p-2.5 sm:p-3">
            <h4 class="product-title-full text-xs sm:text-sm font-bold text-brand-dark">Thực Hành Chiết Xuất Espresso &amp; Máy Pha Chuyên Nghiệp</h4>
          </div>
        </div>

        <div class="bg-white rounded-xl border border-brand-border overflow-hidden">
          <div class="aspect-[4/3] w-full bg-stone-100 overflow-hidden">
            <img src="https://drive.google.com/thumbnail?id=1oEbPHQbnw-_fN12EN1L9-db6ScbpLutN&sz=w800" data-drive-id="1oEbPHQbnw-_fN12EN1L9-db6ScbpLutN" alt="Đào tạo học viên Barista thực chiến tại quầy Bar" class="w-full h-full object-cover" onerror="handleDriveImgError(this, 'Ảnh Thực Tế 2')">
          </div>
          <div class="p-2.5 sm:p-3">
            <h4 class="product-title-full text-xs sm:text-sm font-bold text-brand-dark">Không Gian Quầy Bar Thực Hành Hiện Đại Tại 134/5 Yên Bái</h4>
          </div>
        </div>

        <div class="bg-white rounded-xl border border-brand-border overflow-hidden">
          <div class="aspect-[4/3] w-full bg-stone-100 overflow-hidden">
            <img src="https://drive.google.com/thumbnail?id=1Zm8xvocINo_Gco_CWfjlO8Xjw2uA47NN&sz=w800" data-drive-id="1Zm8xvocINo_Gco_CWfjlO8Xjw2uA47NN" alt="Nghiên cứu công thức đồ uống và nguyên liệu pha chế" class="w-full h-full object-cover" onerror="handleDriveImgError(this, 'Ảnh Thực Tế 3')">
          </div>
          <div class="p-2.5 sm:p-3">
            <h4 class="product-title-full text-xs sm:text-sm font-bold text-brand-dark">Thực Hành Pha Chế Đồ Uống &amp; Thử Nghiệm Menu Mới</h4>
          </div>
        </div>

        <div class="bg-white rounded-xl border border-brand-border overflow-hidden">
          <div class="aspect-[4/3] w-full bg-stone-100 overflow-hidden">
            <img src="https://drive.google.com/thumbnail?id=1o0wBE5h1O8gI551OPfCPLYJLQzQQCD3-&sz=w800" data-drive-id="1o0wBE5h1O8gI551OPfCPLYJLQzQQCD3-" alt="Trang thiết bị máy pha cà phê và máy xay tại F&B Base" class="w-full h-full object-cover" onerror="handleDriveImgError(this, 'Ảnh Thực Tế 4')">
          </div>
          <div class="p-2.5 sm:p-3">
            <h4 class="product-title-full text-xs sm:text-sm font-bold text-brand-dark">Hệ Thống Máy Pha Cà Phê &amp; Thiết Bị Quầy Bar Tiêu Chuẩn</h4>
          </div>
        </div>

        <div class="bg-white rounded-xl border border-brand-border overflow-hidden">
          <div class="aspect-[4/3] w-full bg-stone-100 overflow-hidden">
            <img src="https://drive.google.com/thumbnail?id=1ET0rUw8l3P5eMHkFFbxfloOQ7IwdHndj&sz=w800" data-drive-id="1ET0rUw8l3P5eMHkFFbxfloOQ7IwdHndj" alt="Kỹ thuật tạo hình Latte Art chuyên sâu" class="w-full h-full object-cover" onerror="handleDriveImgError(this, 'Ảnh Thực Tế 5')">
          </div>
          <div class="p-2.5 sm:p-3">
            <h4 class="product-title-full text-xs sm:text-sm font-bold text-brand-dark">Lớp Học Kỹ Thuật Đánh Sữa &amp; Tạo Hình Latte Art 1 Kèm 1</h4>
          </div>
        </div>

        <div class="bg-white rounded-xl border border-brand-border overflow-hidden">
          <div class="aspect-[4/3] w-full bg-stone-100 overflow-hidden">
            <img src="https://drive.google.com/thumbnail?id=1wU8q1SH4yjgsfkgiY2mOZIhNXUL-H57m&sz=w800" data-drive-id="1wU8q1SH4yjgsfkgiY2mOZIhNXUL-H57m" alt="Dự án Setup quán cà phê trọn gói F&B Base" class="w-full h-full object-cover" onerror="handleDriveImgError(this, 'Ảnh Thực Tế 6')">
          </div>
          <div class="p-2.5 sm:p-3">
            <h4 class="product-title-full text-xs sm:text-sm font-bold text-brand-dark">Tư Vấn Setup Quán Cà Phê &amp; Vận Hành Thực Tế Cho Chủ Quán</h4>
          </div>
        </div>

        <div class="bg-white rounded-xl border border-brand-border overflow-hidden">
          <div class="aspect-[4/3] w-full bg-stone-100 overflow-hidden">
            <img src="https://drive.google.com/thumbnail?id=1ZF3YcSyo7r56g1n6dSe8G8c9VQZ29GBk&sz=w800" data-drive-id="1ZF3YcSyo7r56g1n6dSe8G8c9VQZ29GBk" alt="Đào tạo Bartender & Cocktail chuyên nghiệp" class="w-full h-full object-cover" onerror="handleDriveImgError(this, 'Ảnh Thực Tế 7')">
          </div>
          <div class="p-2.5 sm:p-3">
            <h4 class="product-title-full text-xs sm:text-sm font-bold text-brand-dark">Đào Tạo Nghiệp Vụ Bartender, Cocktail &amp; Kỹ Năng Quầy Bar</h4>
          </div>
        </div>

        <div class="bg-white rounded-xl border border-brand-border overflow-hidden">
          <div class="aspect-[4/3] w-full bg-stone-100 overflow-hidden">
            <img src="https://drive.google.com/thumbnail?id=1w-Z77OHU-cAzdUyvLZpE6V7KMuajJ9-4&sz=w800" data-drive-id="1w-Z77OHU-cAzdUyvLZpE6V7KMuajJ9-4" alt="Buổi học giao lưu cộng đồng Barista F&B Base" class="w-full h-full object-cover" onerror="handleDriveImgError(this, 'Ảnh Thực Tế 8')">
          </div>
          <div class="p-2.5 sm:p-3">
            <h4 class="product-title-full text-xs sm:text-sm font-bold text-brand-dark">Workshop &amp; Giao Lưu Chia Sẻ Kinh Nghiệm Cộng Đồng Barista</h4>
          </div>
        </div>

        <div class="bg-white rounded-xl border border-brand-border overflow-hidden col-span-2 md:col-span-1">
          <div class="aspect-[4/3] w-full bg-stone-100 overflow-hidden">
            <img src="https://drive.google.com/thumbnail?id=1MrWhPGxC_ZL_3Il-KwIS7J3GD0LNemZK&sz=w800" data-drive-id="1MrWhPGxC_ZL_3Il-KwIS7J3GD0LNemZK" alt="Lớp Barista cho du học sinh tại F&B Base Đà Nẵng" class="w-full h-full object-cover" onerror="handleDriveImgError(this, 'Ảnh Thực Tế 9')">
          </div>
          <div class="p-2.5 sm:p-3">
            <h4 class="product-title-full text-xs sm:text-sm font-bold text-brand-dark">Học Viên Hoàn Thành Khóa Barista Du Học Sinh &amp; Mở Quán</h4>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ==========================================================================
       [UX BUILDER: DANH MỤC SẢN PHẨM 1 - MÁY MÓC THIẾT BỊ PHA CHẾ (LẤY TỪ WEB MẪU)]
       - Chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4)
       - Không để nhãn dán ở trang chủ
       - Tên sản phẩm hiển thị đầy đủ không tràn viền, không thiếu chữ
       ========================================================================== -->
  <section id="may-moc-thiet-bi" class="w-full py-8 sm:py-10 bg-white">
    <div class="ux-container">
      <div class="flatsome-section-title">
        <b></b>
        <span class="text-base sm:text-xl lg:text-2xl">MÁY MÓC THIẾT BỊ PHA CHẾ</span>
        <b></b>
      </div>

      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5" id="grid-may-moc">
        <!-- Sản phẩm được render từ dữ liệu chuẩn của web mẫu kết hợp ảnh thực tế -->
      </div>
    </div>
  </section>

  <!-- ==========================================================================
       [UX BUILDER: DANH MỤC SẢN PHẨM 2 - DỤNG CỤ PHA CHẾ (LẤY TỪ WEB MẪU)]
       ========================================================================== -->
  <section id="dung-cu-pha-che" class="w-full py-8 sm:py-10 bg-brand-light border-t border-brand-border">
    <div class="ux-container">
      <div class="flatsome-section-title">
        <b></b>
        <span class="text-base sm:text-xl lg:text-2xl">DỤNG CỤ PHA CHẾ</span>
        <b></b>
      </div>

      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5" id="grid-dung-cu">
        <!-- Sản phẩm được render từ dữ liệu chuẩn của web mẫu -->
      </div>
    </div>
  </section>

  <!-- ==========================================================================
       [UX BUILDER: DANH MỤC SẢN PHẨM 3 - NGUYÊN LIỆU PHA CHẾ (LẤY TỪ WEB MẪU)]
       ========================================================================== -->
  <section id="nguyen-lieu-pha-che" class="w-full py-8 sm:py-10 bg-white border-t border-brand-border">
    <div class="ux-container">
      <div class="flatsome-section-title">
        <b></b>
        <span class="text-base sm:text-xl lg:text-2xl">NGUYÊN LIỆU PHA CHẾ</span>
        <b></b>
      </div>

      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5" id="grid-nguyen-lieu">
        <!-- Sản phẩm được render từ dữ liệu chuẩn của web mẫu -->
      </div>
    </div>
  </section>

  <!-- ==========================================================================
       [UX BUILDER: DANH MỤC SẢN PHẨM 4 - LY TÁCH PHA CHẾ (LẤY TỪ WEB MẪU)]
       ========================================================================== -->
  <section id="ly-tach-pha-che" class="w-full py-8 sm:py-10 bg-brand-light border-t border-brand-border">
    <div class="ux-container">
      <div class="flatsome-section-title">
        <b></b>
        <span class="text-base sm:text-xl lg:text-2xl">LY TÁCH PHA CHẾ</span>
        <b></b>
      </div>

      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5" id="grid-ly-tach">
        <!-- Sản phẩm được render từ dữ liệu chuẩn của web mẫu -->
      </div>
    </div>
  </section>

  <!-- ==========================================================================
       [UX BUILDER: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TỪ NỘI DUNG FANPAGE F&B BASE & WEB MẪU)]
       ========================================================================== -->
  <section id="tin-tuc" class="w-full py-8 sm:py-10 bg-white border-t border-brand-border">
    <div class="ux-container">
      <div class="flatsome-section-title">
        <b></b>
        <span class="text-base sm:text-xl lg:text-2xl">DANH MỤC BÀI VIẾT &amp; TIN TỨC NỔI BẬT</span>
        <b></b>
      </div>

      <!-- Thanh lọc danh mục bài viết nhỏ gọn trên 1 hàng -->
      <div class="flex flex-wrap items-center justify-center gap-2 mb-6">
        <button type="button" onclick="filterPosts('all')" class="post-cat-btn cat-nowrap px-3 py-1.5 rounded-md bg-brand-dark text-white text-xs font-semibold transition-colors" data-cat="all">
          Tất cả bài viết
        </button>
        <button type="button" onclick="filterPosts('dao-tao')" class="post-cat-btn cat-nowrap px-3 py-1.5 rounded-md bg-brand-light text-brand-dark border border-brand-border text-xs font-semibold hover:bg-brand-soft transition-colors" data-cat="dao-tao">
          Đào tạo Barista &amp; Du học
        </button>
        <button type="button" onclick="filterPosts('setup-quan')" class="post-cat-btn cat-nowrap px-3 py-1.5 rounded-md bg-brand-light text-brand-dark border border-brand-border text-xs font-semibold hover:bg-brand-soft transition-colors" data-cat="setup-quan">
          Dự án Setup Quán
        </button>
        <button type="button" onclick="filterPosts('kien-thuc')" class="post-cat-btn cat-nowrap px-3 py-1.5 rounded-md bg-brand-light text-brand-dark border border-brand-border text-xs font-semibold hover:bg-brand-soft transition-colors" data-cat="kien-thuc">
          Kiến thức &amp; Vận hành F&amp;B
        </button>
      </div>

      <!-- Lưới bài viết: 2 cột trên điện thoại, 3 cột trên máy tính -->
      <div class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-5" id="blogGrid">
        
        <!-- Bài viết 1 -->
        <article class="blog-card bg-brand-light rounded-xl border border-brand-border overflow-hidden flex flex-col justify-between" data-category="setup-quan">
          <div>
            <div class="aspect-[16/10] w-full bg-stone-200 overflow-hidden">
              <img src="https://drive.google.com/thumbnail?id=1wU8q1SH4yjgsfkgiY2mOZIhNXUL-H57m&sz=w800" data-drive-id="1wU8q1SH4yjgsfkgiY2mOZIhNXUL-H57m" alt="Dự án setup Zen Coffee 134 Yên Bái Đà Nẵng" class="w-full h-full object-cover" onerror="handleDriveImgError(this, 'Dự Án Setup Zen Coffee')">
            </div>
            <div class="p-3 sm:p-4">
              <p class="text-[11px] text-brand-accent font-semibold mb-1">Dự án Setup Quán</p>
              <h3 class="product-title-full text-xs sm:text-base font-bold text-brand-dark mb-1.5">
                Dự Án Setup Zen Coffee Tại 134 Yên Bái, Hải Châu, Đà Nẵng – Hòa Quyện Cổ Kính Và Tối Giản
              </h3>
              <p class="text-[11px] sm:text-xs text-stone-600 leading-relaxed hidden sm:block">
                Dự án được đội ngũ F&amp;B Base setup trọn gói từ định hướng không gian, ánh sáng, khu vực workshop đến quy trình vận hành quầy bar và menu đồ uống chất lượng.
              </p>
            </div>
          </div>
          <div class="px-3 pb-3 sm:px-4 sm:pb-4">
            <a href="https://www.facebook.com/DaotaophacheFnBBase" target="_blank" rel="noopener" class="text-[11px] sm:text-xs font-bold text-brand-dark hover:text-brand-accent inline-flex items-center">
              Đọc chi tiết trên Fanpage <i class="fa-solid fa-angle-right ml-1"></i>
            </a>
          </div>
        </article>

        <!-- Bài viết 2 -->
        <article class="blog-card bg-brand-light rounded-xl border border-brand-border overflow-hidden flex flex-col justify-between" data-category="dao-tao">
          <div>
            <div class="aspect-[16/10] w-full bg-stone-200 overflow-hidden">
              <img src="https://drive.google.com/thumbnail?id=1ET0rUw8l3P5eMHkFFbxfloOQ7IwdHndj&sz=w800" data-drive-id="1ET0rUw8l3P5eMHkFFbxfloOQ7IwdHndj" alt="Khởi đầu hành trình du học Úc từ một ly cà phê" class="w-full h-full object-cover" onerror="handleDriveImgError(this, 'Barista Du Học Úc')">
            </div>
            <div class="p-3 sm:p-4">
              <p class="text-[11px] text-brand-accent font-semibold mb-1">Đào tạo Barista &amp; Du học</p>
              <h3 class="product-title-full text-xs sm:text-base font-bold text-brand-dark mb-1.5">
                Khởi Đầu Hành Trình Du Học Úc Từ Một Ly Cà Phê – Lộ Trình Học Barista Kèm 1-1 Thực Chiến
              </h3>
              <p class="text-[11px] sm:text-xs text-stone-600 leading-relaxed hidden sm:block">
                Chỉ sau khóa học kèm sát 1-1 tại F&amp;B Base, học viên nắm vững chiết xuất Espresso, kiểm soát bọt sữa và tạo hình Latte Art để tự tin ứng tuyển tại Úc.
              </p>
            </div>
          </div>
          <div class="px-3 pb-3 sm:px-4 sm:pb-4">
            <a href="https://www.facebook.com/DaotaophacheFnBBase" target="_blank" rel="noopener" class="text-[11px] sm:text-xs font-bold text-brand-dark hover:text-brand-accent inline-flex items-center">
              Đọc chi tiết trên Fanpage <i class="fa-solid fa-angle-right ml-1"></i>
            </a>
          </div>
        </article>

        <!-- Bài viết 3 -->
        <article class="blog-card bg-brand-light rounded-xl border border-brand-border overflow-hidden flex flex-col justify-between" data-category="dao-tao">
          <div>
            <div class="aspect-[16/10] w-full bg-stone-200 overflow-hidden">
              <img src="https://drive.google.com/thumbnail?id=1rGho5fg969qDLR_0HwjCLl07fvvXFcnD&sz=w800" data-drive-id="1rGho5fg969qDLR_0HwjCLl07fvvXFcnD" alt="Giải Á Quân cuộc thi pha chế Espresso Latte Art Signature" class="w-full h-full object-cover" onerror="handleDriveImgError(this, 'Á Quân Pha Chế')">
            </div>
            <div class="p-3 sm:p-4">
              <p class="text-[11px] text-brand-accent font-semibold mb-1">Hoạt động Học viện</p>
              <h3 class="product-title-full text-xs sm:text-base font-bold text-brand-dark mb-1.5">
                Chúc Mừng Thầy Minh Cùng Cộng Sự Đạt Giải Á Quân Cuộc Thi Pha Chế 3 Hạng Mục: Espresso, Latte Art, Signature
              </h3>
              <p class="text-[11px] sm:text-xs text-stone-600 leading-relaxed hidden sm:block">
                Tiếp lửa đam mê cho thế hệ Barista trẻ chất lượng tiếp theo trên hành trình xây dựng cộng đồng Barista chuyên nghiệp tại Đà Nẵng.
              </p>
            </div>
          </div>
          <div class="px-3 pb-3 sm:px-4 sm:pb-4">
            <a href="https://www.facebook.com/DaotaophacheFnBBase" target="_blank" rel="noopener" class="text-[11px] sm:text-xs font-bold text-brand-dark hover:text-brand-accent inline-flex items-center">
              Đọc chi tiết trên Fanpage <i class="fa-solid fa-angle-right ml-1"></i>
            </a>
          </div>
        </article>

        <!-- Bài viết 4 -->
        <article class="blog-card bg-brand-light rounded-xl border border-brand-border overflow-hidden flex flex-col justify-between" data-category="kien-thuc">
          <div>
            <div class="aspect-[16/10] w-full bg-stone-200 overflow-hidden">
              <img src="https://drive.google.com/thumbnail?id=1Zm8xvocINo_Gco_CWfjlO8Xjw2uA47NN&sz=w800" data-drive-id="1Zm8xvocINo_Gco_CWfjlO8Xjw2uA47NN" alt="Một lớp học hàng chục ý tưởng mới cho quán của bạn" class="w-full h-full object-cover" onerror="handleDriveImgError(this, 'Ý Tưởng Menu Quán')">
            </div>
            <div class="p-3 sm:p-4">
              <p class="text-[11px] text-brand-accent font-semibold mb-1">Kiến thức &amp; Vận hành F&amp;B</p>
              <h3 class="product-title-full text-xs sm:text-base font-bold text-brand-dark mb-1.5">
                Một Lớp Học – Hàng Chục Ý Tưởng Mới Cho Quán Cà Phê Của Bạn: Vừa Học Vừa Nghiên Cứu Thực Chiến
              </h3>
              <p class="text-[11px] sm:text-xs text-stone-600 leading-relaxed hidden sm:block">
                Không gian kết nối các chủ quán F&amp;B để cùng thử nghiệm công thức đồ uống mới, tối ưu giá cost nguyên liệu và nâng cao trải nghiệm khách hàng.
              </p>
            </div>
          </div>
          <div class="px-3 pb-3 sm:px-4 sm:pb-4">
            <a href="https://www.facebook.com/DaotaophacheFnBBase" target="_blank" rel="noopener" class="text-[11px] sm:text-xs font-bold text-brand-dark hover:text-brand-accent inline-flex items-center">
              Đọc chi tiết trên Fanpage <i class="fa-solid fa-angle-right ml-1"></i>
            </a>
          </div>
        </article>

        <!-- Bài viết 5 -->
        <article class="blog-card bg-brand-light rounded-xl border border-brand-border overflow-hidden flex flex-col justify-between" data-category="kien-thuc">
          <div>
            <div class="aspect-[16/10] w-full bg-stone-200 overflow-hidden">
              <img src="https://drive.google.com/thumbnail?id=1o0wBE5h1O8gI551OPfCPLYJLQzQQCD3-&sz=w800" data-drive-id="1o0wBE5h1O8gI551OPfCPLYJLQzQQCD3-" alt="Tổng hợp kỹ thuật pha chế cơ bản cho Barista mới bắt đầu" class="w-full h-full object-cover" onerror="handleDriveImgError(this, 'Kỹ Thuật Barista')">
            </div>
            <div class="p-3 sm:p-4">
              <p class="text-[11px] text-brand-accent font-semibold mb-1">Kiến thức &amp; Vận hành F&amp;B</p>
              <h3 class="product-title-full text-xs sm:text-base font-bold text-brand-dark mb-1.5">
                Tổng Hợp Các Kỹ Thuật Pha Chế Cơ Bản Cho Barista Mới Bắt Đầu &amp; Cách Lựa Chọn Máy Pha Phù Hợp
              </h3>
              <p class="text-[11px] sm:text-xs text-stone-600 leading-relaxed hidden sm:block">
                Hướng dẫn chi tiết cách chỉnh độ mịn máy xay, định lượng cà phê, lực nén Tamper và vệ sinh máy pha cà phê bền bỉ trong giờ cao điểm.
              </p>
            </div>
          </div>
          <div class="px-3 pb-3 sm:px-4 sm:pb-4">
            <a href="https://www.facebook.com/DaotaophacheFnBBase" target="_blank" rel="noopener" class="text-[11px] sm:text-xs font-bold text-brand-dark hover:text-brand-accent inline-flex items-center">
              Đọc chi tiết trên Fanpage <i class="fa-solid fa-angle-right ml-1"></i>
            </a>
          </div>
        </article>

        <!-- Bài viết 6 -->
        <article class="blog-card bg-brand-light rounded-xl border border-brand-border overflow-hidden flex flex-col justify-between" data-category="dao-tao">
          <div>
            <div class="aspect-[16/10] w-full bg-stone-200 overflow-hidden">
              <img src="https://drive.google.com/thumbnail?id=1w-Z77OHU-cAzdUyvLZpE6V7KMuajJ9-4&sz=w800" data-drive-id="1w-Z77OHU-cAzdUyvLZpE6V7KMuajJ9-4" alt="Chương trình đào tạo nghề miễn phí cho thanh niên khó khăn" class="w-full h-full object-cover" onerror="handleDriveImgError(this, 'Đào Tạo Nghề Nhân Văn')">
            </div>
            <div class="p-3 sm:p-4">
              <p class="text-[11px] text-brand-accent font-semibold mb-1">Đào tạo Barista &amp; Du học</p>
              <h3 class="product-title-full text-xs sm:text-base font-bold text-brand-dark mb-1.5">
                F&amp;B Base Đồng Hành Cùng Thanh Niên Có Hoàn Cảnh Khó Khăn Với Chương Trình Đào Tạo Nghề Miễn Phí
              </h3>
              <p class="text-[11px] sm:text-xs text-stone-600 leading-relaxed hidden sm:block">
                Trao cần câu nghề nghiệp vững chắc với cam kết đầu ra 10/10 giúp các bạn trẻ tự tin lập nghiệp và làm việc tại các chuỗi F&amp;B lớn.
              </p>
            </div>
          </div>
          <div class="px-3 pb-3 sm:px-4 sm:pb-4">
            <a href="https://www.facebook.com/DaotaophacheFnBBase" target="_blank" rel="noopener" class="text-[11px] sm:text-xs font-bold text-brand-dark hover:text-brand-accent inline-flex items-center">
              Đọc chi tiết trên Fanpage <i class="fa-solid fa-angle-right ml-1"></i>
            </a>
          </div>
        </article>

      </div>
    </div>
  </section>

  <!-- ==========================================================================
       [UX BUILDER: DANH MỤC ĐỐI TÁC ĐỒNG HÀNH CÙNG F&B BASE]
       ========================================================================== -->
  <section id="doi-tac" class="w-full py-8 sm:py-10 bg-brand-light border-t border-brand-border">
    <div class="ux-container">
      <div class="flatsome-section-title">
        <b></b>
        <span class="text-base sm:text-xl lg:text-2xl">ĐỐI TÁC ĐỒNG HÀNH &amp; THƯƠNG HIỆU LIÊN KẾT</span>
        <b></b>
      </div>

      <p class="text-center text-xs sm:text-sm text-stone-600 max-w-2xl mx-auto mb-6">
        F&amp;B Base tự hào hợp tác cùng các thương hiệu thiết bị, nguyên liệu pha chế uy tín hàng đầu và đồng hành setup cho nhiều dự án quán cà phê, doanh nghiệp tại Đà Nẵng.
      </p>

      <!-- Chia 2 cột trên điện thoại, 6 cột trên máy tính -->
      <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4">
        <div class="bg-white p-4 rounded-xl border border-brand-border text-center flex flex-col items-center justify-center min-h-[96px]">
          <i class="fa-solid fa-industry text-xl text-brand-accent mb-1.5"></i>
          <span class="text-xs sm:text-sm font-extrabold text-brand-dark">UNIBAR</span>
          <span class="text-[11px] text-stone-500">Thiết bị pha chế</span>
        </div>
        <div class="bg-white p-4 rounded-xl border border-brand-border text-center flex flex-col items-center justify-center min-h-[96px]">
          <i class="fa-solid fa-gears text-xl text-brand-accent mb-1.5"></i>
          <span class="text-xs sm:text-sm font-extrabold text-brand-dark">UNITECH</span>
          <span class="text-[11px] text-stone-500">Máy móc quầy Bar</span>
        </div>
        <div class="bg-white p-4 rounded-xl border border-brand-border text-center flex flex-col items-center justify-center min-h-[96px]">
          <i class="fa-solid fa-jar-wheat text-xl text-brand-accent mb-1.5"></i>
          <span class="text-xs sm:text-sm font-extrabold text-brand-dark">DEDU &amp; TRENDY</span>
          <span class="text-[11px] text-stone-500">Nguyên liệu &amp; Mứt</span>
        </div>
        <div class="bg-white p-4 rounded-xl border border-brand-border text-center flex flex-col items-center justify-center min-h-[96px]">
          <i class="fa-solid fa-mug-saucer text-xl text-brand-accent mb-1.5"></i>
          <span class="text-xs sm:text-sm font-extrabold text-brand-dark">ZEN COFFEE</span>
          <span class="text-[11px] text-stone-500">Dự án Setup 134 Yên Bái</span>
        </div>
        <div class="bg-white p-4 rounded-xl border border-brand-border text-center flex flex-col items-center justify-center min-h-[96px]">
          <i class="fa-solid fa-laptop-code text-xl text-brand-accent mb-1.5"></i>
          <span class="text-xs sm:text-sm font-extrabold text-brand-dark">FPT WORKSHOP</span>
          <span class="text-[11px] text-stone-500">Đối tác sự kiện đào tạo</span>
        </div>
        <div class="bg-white p-4 rounded-xl border border-brand-border text-center flex flex-col items-center justify-center min-h-[96px]">
          <i class="fa-solid fa-wine-bottle text-xl text-brand-accent mb-1.5"></i>
          <span class="text-xs sm:text-sm font-extrabold text-brand-dark">MONIN &amp; TORANI</span>
          <span class="text-[11px] text-stone-500">Syrup chuẩn quốc tế</span>
        </div>
      </div>
    </div>
  </section>

  <!-- ==========================================================================
       [UX BUILDER: FORM YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ TRANG CHỦ]
       ========================================================================== -->
  <section id="bao-gia" class="w-full py-8 sm:py-10 bg-white border-t border-brand-border">
    <div class="ux-container">
      <div class="flatsome-section-title">
        <b></b>
        <span class="text-base sm:text-xl lg:text-2xl">FORM YÊU CẦU TƯ VẤN &amp; NHẬN BÁO GIÁ NHANH</span>
        <b></b>
      </div>

      <div class="max-w-4xl mx-auto bg-brand-light rounded-2xl border border-brand-border p-4 sm:p-6 lg:p-8 shadow-sm">
        <p class="text-xs sm:text-sm text-stone-700 text-center mb-5">
          Quý học viên và Chủ quán vui lòng để lại thông tin bên dưới. Đội ngũ <strong>Đào tạo pha chế F&amp;B Base (0777.434.358)</strong> sẽ liên hệ tư vấn lộ trình học &amp; gửi bảng báo giá chi tiết ngay!
        </p>

        <form id="quoteForm" class="space-y-4" onsubmit="handleQuoteSubmit(event)">
          <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
            <div>
              <label for="customerName" class="block text-xs font-bold text-brand-dark mb-1">Họ và tên của bạn *</label>
              <input type="text" id="customerName" required placeholder="Nhập họ và tên..." class="w-full px-3.5 py-2.5 rounded-lg border border-brand-border bg-white text-xs sm:text-sm focus:outline-none focus:border-brand-accent">
            </div>
            <div>
              <label for="customerPhone" class="block text-xs font-bold text-brand-dark mb-1">Số điện thoại / Zalo *</label>
              <input type="tel" id="customerPhone" required placeholder="Ví dụ: 0905xxxxxx" class="w-full px-3.5 py-2.5 rounded-lg border border-brand-border bg-white text-xs sm:text-sm focus:outline-none focus:border-brand-accent">
            </div>
          </div>

          <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
            <div>
              <label for="serviceCategory" class="block text-xs font-bold text-brand-dark mb-1">Danh mục cần tư vấn &amp; báo giá *</label>
              <select id="serviceCategory" required class="w-full px-3.5 py-2.5 rounded-lg border border-brand-border bg-white text-xs sm:text-sm focus:outline-none focus:border-brand-accent">
                <option value="Khóa Học Pha Chế Tổng Hợp / Mở Quán">Khóa Học Pha Chế Tổng Hợp / Mở Quán</option>
                <option value="Khóa Học Barista Chuyên Nghiệp & Latte Art">Khóa Học Barista Chuyên Nghiệp &amp; Latte Art</option>
                <option value="Khóa Học Barista Dành Cho Du Học Sinh">Khóa Học Barista Dành Cho Du Học Sinh / Working Holiday</option>
                <option value="Khóa Học Pha Chế Trà Sữa / Bartender Cocktail">Khóa Học Pha Chế Trà Sữa / Bartender Cocktail</option>
                <option value="Dịch Vụ Setup Quán Cà Phê & Trà Sữa Trọn Gói">Dịch Vụ Setup Quán Cà Phê &amp; Trà Sữa Trọn Gói</option>
                <option value="Báo Giá Máy Móc Thiết Bị Pha Chế">Báo Giá Máy Móc Thiết Bị Pha Chế</option>
                <option value="Báo Giá Dụng Cụ, Nguyên Liệu & Ly Tách Pha Chế">Báo Giá Dụng Cụ, Nguyên Liệu &amp; Ly Tách Pha Chế</option>
              </select>
            </div>
            <div>
              <label for="customerProduct" class="block text-xs font-bold text-brand-dark mb-1">Sản phẩm / Khóa học quan tâm cụ thể</label>
              <input type="text" id="customerProduct" placeholder="Ví dụ: Khóa Barista 1-1, Máy làm đá Bingsu..." class="w-full px-3.5 py-2.5 rounded-lg border border-brand-border bg-white text-xs sm:text-sm focus:outline-none focus:border-brand-accent">
            </div>
          </div>

          <div>
            <label for="customerNote" class="block text-xs font-bold text-brand-dark mb-1">Nội dung yêu cầu chi tiết (Mô hình quán, ngân sách dự kiến, lịch học...)</label>
            <textarea id="customerNote" rows="3" placeholder="Nhập yêu cầu cụ thể của bạn để F&B Base báo giá sát nhất..." class="w-full px-3.5 py-2.5 rounded-lg border border-brand-border bg-white text-xs sm:text-sm focus:outline-none focus:border-brand-accent"></textarea>
          </div>

          <div class="flex flex-wrap items-center justify-center gap-3 pt-2">
            <button type="submit" class="px-6 py-3 rounded-xl bg-brand-dark text-white text-xs sm:text-sm font-extrabold hover:bg-brand-accent transition-colors inline-flex items-center gap-2">
              <i class="fa-solid fa-paper-plane"></i>
              GỬI YÊU CẦU &amp; NHẬN BÁO GIÁ
            </button>
            <a href="https://zalo.me/0777434358" target="_blank" rel="noopener" class="px-5 py-3 rounded-xl bg-[#0068FF] text-white text-xs sm:text-sm font-bold hover:opacity-90 transition-opacity inline-flex items-center gap-2">
              <i class="fa-solid fa-comment-dots"></i>
              Chat Zalo: 0777.434.358
            </a>
          </div>
        </form>

        <!-- Hộp thông báo gửi thành công (Thay cho alert) -->
        <div id="quoteSuccessBox" class="hidden mt-4 p-4 rounded-xl bg-emerald-50 border border-emerald-300 text-emerald-900 text-xs sm:text-sm">
          <div class="font-bold flex items-center gap-2 mb-1">
            <i class="fa-solid fa-circle-check text-emerald-600 text-base"></i>
            <span>Đã ghi nhận yêu cầu báo giá thành công!</span>
          </div>
          <p id="quoteSuccessText" class="text-xs leading-relaxed"></p>
        </div>
      </div>
    </div>
  </section>

  <!-- ==========================================================================
       [UX BUILDER: ĐƯA FANPAGE & GOOGLE MAP RA NGOÀI TRANG CHỦ]
       - Địa chỉ: 134/5 Yên Bái - Hải Châu - Đà Nẵng
       - SĐT: 0777.434.358
       - Fanpage: https://www.facebook.com/DaotaophacheFnBBase
       ========================================================================== -->
  <section id="lien-he" class="w-full py-8 sm:py-10 bg-brand-soft border-t border-brand-border">
    <div class="ux-container">
      <div class="flatsome-section-title">
        <b></b>
        <span class="text-base sm:text-xl lg:text-2xl">KẾT NỐI FANPAGE &amp; BẢN ĐỒ GOOGLE MAPS TRANG CHỦ</span>
        <b></b>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-stretch">
        
        <!-- CỘT 1 (5/12): FANPAGE ĐÀO TẠO PHA CHẾ - F&B BASE TRỰC TIẾP TRÊN TRANG CHỦ -->
        <div class="lg:col-span-5 bg-white rounded-2xl border border-brand-border p-4 sm:p-5 flex flex-col justify-between shadow-sm">
          <div>
            <div class="flex items-center justify-between gap-2 pb-3 mb-3 border-b border-brand-border">
              <div class="flex items-center gap-2.5">
                <img src="https://drive.google.com/thumbnail?id=1_Lmxu5-AwVn0MLzPvd0daTshr1HvShPm&sz=w200" alt="Logo F&B Base" class="w-10 h-10 rounded-full object-contain border border-brand-border bg-brand-light p-0.5" onerror="handleDriveImgError(this, 'F&B')">
                <div>
                  <h3 class="text-sm sm:text-base font-extrabold text-brand-dark">Đào tạo pha chế - F&amp;B Base</h3>
                  <p class="text-[11px] text-stone-500">Trường dạy pha chế • Setup Quán Cà Phê Trọn Gói</p>
                </div>
              </div>
              <a href="https://www.facebook.com/DaotaophacheFnBBase" target="_blank" rel="noopener" class="px-3 py-1.5 rounded-lg bg-[#1877F2] text-white text-xs font-bold hover:opacity-90 shrink-0 inline-flex items-center gap-1.5">
                <i class="fa-brands fa-facebook-f"></i> Theo dõi
              </a>
            </div>

            <!-- Nhúng Facebook Page Plugin thực tế + Khung thông tin Fanpage trực quan -->
            <div class="w-full overflow-hidden rounded-xl border border-brand-border bg-brand-light mb-3">
              <iframe 
                title="Fanpage Đào tạo pha chế - F&B Base"
                src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2FDaotaophacheFnBBase&tabs=timeline&width=500&height=260&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                class="w-full h-[260px] border-0 overflow-hidden" 
                scrolling="no" 
                frameborder="0" 
                allowfullscreen="true" 
                allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
              </iframe>
            </div>

            <div class="bg-brand-light rounded-xl p-3 border border-brand-border text-xs space-y-1.5">
              <p class="font-bold text-brand-dark">
                <i class="fa-solid fa-star text-brand-accent mr-1"></i> Điểm khác biệt tại Fanpage Đào tạo pha chế - F&amp;B Base:
              </p>
              <p class="text-stone-600 leading-relaxed">
                • Đào tạo nghiệp vụ Barista, Bartender, Bar trưởng, Mở quán cấp tốc, Du học sinh – Working Holiday.<br>
                • 80% thời lượng thực hành, cam kết đầu ra 10/10, hỗ trợ học viên trọn đời.<br>
                • Chương trình đào tạo nghề miễn phí cho thanh niên có hoàn cảnh khó khăn hoặc mồ côi.
              </p>
            </div>
          </div>

          <div class="mt-4 pt-3 border-t border-brand-border flex flex-wrap items-center justify-between gap-2">
            <a href="https://www.facebook.com/DaotaophacheFnBBase" target="_blank" rel="noopener" class="text-xs font-bold text-[#1877F2] hover:underline inline-flex items-center gap-1.5">
              <i class="fa-brands fa-facebook"></i> facebook.com/DaotaophacheFnBBase
            </a>
            <a href="https://zalo.me/0777434358" target="_blank" rel="noopener" class="text-xs font-bold text-brand-dark hover:text-brand-accent inline-flex items-center gap-1">
              <i class="fa-solid fa-phone-volume text-brand-accent"></i> 0777.434.358
            </a>
          </div>
        </div>

        <!-- CỘT 2 (7/12): BẢN ĐỒ GOOGLE MAPS TRỰC TIẾP TRÊN TRANG CHỦ (134/5 YÊN BÁI - HẢI CHÂU - ĐÀ NẴNG) -->
        <div class="lg:col-span-7 bg-white rounded-2xl border border-brand-border p-4 sm:p-5 flex flex-col justify-between shadow-sm">
          <div>
            <div class="flex flex-wrap items-center justify-between gap-2 pb-3 mb-3 border-b border-brand-border">
              <div>
                <h3 class="text-sm sm:text-base font-extrabold text-brand-dark uppercase">
                  <i class="fa-solid fa-location-dot text-brand-accent mr-1.5"></i>
                  BẢN ĐỒ GOOGLE MAPS: 134/5 YÊN BÁI - HẢI CHÂU - ĐÀ NẴNG
                </h3>
                <p class="text-xs text-stone-500 mt-0.5">Trụ sở Học viện Đào tạo pha chế F&amp;B Base • Hotline/Zalo: 0777.434.358</p>
              </div>
              <a 
                href="https://www.google.com/maps/place//data=!4m2!3m1!19sChIJWSnCMTMYQjERm8dAJ-q2t-E" 
                target="_blank" 
                rel="noopener" 
                class="px-3 py-1.5 rounded-lg bg-brand-dark text-white text-xs font-bold hover:bg-brand-accent transition-colors inline-flex items-center gap-1.5"
              >
                <i class="fa-solid fa-diamond-turn-right"></i> Mở Google Maps Lớn
              </a>
            </div>

            <!-- Google Map Embed trực tiếp ngoài trang chủ -->
            <div class="w-full h-[310px] sm:h-[340px] rounded-xl overflow-hidden border border-brand-border bg-stone-100">
              <iframe 
                title="Bản đồ Google Map Đào tạo pha chế F&B Base 134/5 Yên Bái Hải Châu Đà Nẵng"
                src="https://maps.google.com/maps?q=134/5%20Y%C3%AAn%20B%C3%A1i,%20H%E1%BA%A3i%20Ch%C3%A2u,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed" 
                class="w-full h-full border-0" 
                loading="lazy" 
                referrerpolicy="no-referrer-when-downgrade"
                allowfullscreen>
              </iframe>
            </div>
          </div>

          <!-- Thông tin địa chỉ & liên hệ nhanh dưới bản đồ -->
          <div class="mt-4 pt-3 border-t border-brand-border grid grid-cols-1 sm:grid-cols-3 gap-2 text-xs">
            <div class="flex items-center gap-2">
              <i class="fa-solid fa-map-pin text-brand-accent"></i>
              <span><strong>Địa chỉ:</strong> 134/5 Yên Bái, Hải Châu, Đà Nẵng</span>
            </div>
            <div class="flex items-center gap-2">
              <i class="fa-solid fa-phone text-brand-accent"></i>
              <span><strong>Hotline:</strong> <a href="tel:0777434358" class="font-bold hover:underline">0777.434.358</a></span>
            </div>
            <div class="flex items-center gap-2">
              <i class="fa-solid fa-globe text-brand-accent"></i>
              <span><strong>Website:</strong> fbbase.com</span>
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- ==========================================================================
       [UX BUILDER: FOOTER CHÂN TRANG CHUẨN FLATSOME]
       ========================================================================== -->
  <footer class="w-full bg-brand-dark text-stone-200 pt-10 pb-20 md:pb-8 border-t-4 border-brand-accent">
    <div class="ux-container">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6 pb-8 border-b border-white/15">
        
        <!-- Cột 1: Thông tin F&B Base -->
        <div class="space-y-3">
          <div class="flex items-center gap-2.5">
            <img src="https://drive.google.com/thumbnail?id=1_Lmxu5-AwVn0MLzPvd0daTshr1HvShPm&sz=w200" alt="Logo F&B Base" class="w-10 h-10 rounded-lg bg-white p-1 object-contain" onerror="handleDriveImgError(this, 'F&B')">
            <div>
              <h4 class="text-base font-extrabold text-white">ĐÀO TẠO PHA CHẾ F&amp;B BASE</h4>
              <p class="text-xs text-brand-accent font-semibold">Website: fbbase.com</p>
            </div>
          </div>
          <p class="text-xs text-stone-300 leading-relaxed">
            Học viện đào tạo pha chế chuyên sâu Barista, Bartender, Pha chế mở quán, Barista Du học sinh và cung cấp giải pháp Setup quán, Máy móc thiết bị, Dụng cụ, Nguyên liệu, Ly tách pha chế uy tín tại Đà Nẵng.
          </p>
        </div>

        <!-- Cột 2: Danh mục khóa học -->
        <div>
          <h4 class="text-sm font-extrabold text-white uppercase mb-3">KHÓA HỌC PHA CHẾ</h4>
          <ul class="space-y-2 text-xs text-stone-300">
            <li><a href="#khoa-hoc-pha-che" class="hover:text-brand-accent transition-colors">• Khóa Học Pha Chế Tổng Hợp</a></li>
            <li><a href="#khoa-hoc-pha-che" class="hover:text-brand-accent transition-colors">• Khóa Học Pha Chế Trà Sữa</a></li>
            <li><a href="#khoa-hoc-pha-che" class="hover:text-brand-accent transition-colors">• Khóa Học Pha Chế Barista &amp; Latte Art</a></li>
            <li><a href="#khoa-hoc-pha-che" class="hover:text-brand-accent transition-colors">• Khóa Học Pha Chế Rượu Cocktail</a></li>
            <li><a href="#khoa-hoc-pha-che" class="hover:text-brand-accent transition-colors">• Khóa Học Pha Chế Mở Quán</a></li>
            <li><a href="#khoa-hoc-pha-che" class="hover:text-brand-accent transition-colors">• Khóa Học Barista Du Học Sinh</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục sản phẩm & dịch vụ -->
        <div>
          <h4 class="text-sm font-extrabold text-white uppercase mb-3">SẢN PHẨM &amp; DỊCH VỤ</h4>
          <ul class="space-y-2 text-xs text-stone-300">
            <li><a href="#dich-vu-setup" class="hover:text-brand-accent transition-colors">• Tư Vấn &amp; Setup Quán Trọn Gói</a></li>
            <li><a href="#may-moc-thiet-bi" class="hover:text-brand-accent transition-colors">• Máy Móc Thiết Bị Pha Chế</a></li>
            <li><a href="#dung-cu-pha-che" class="hover:text-brand-accent transition-colors">• Dụng Cụ Pha Chế Quầy Bar</a></li>
            <li><a href="#nguyen-lieu-pha-che" class="hover:text-brand-accent transition-colors">• Nguyên Liệu Pha Chế Chính Hãng</a></li>
            <li><a href="#ly-tach-pha-che" class="hover:text-brand-accent transition-colors">• Ly Tách Thủy Tinh Pha Chế</a></li>
            <li><a href="#bao-gia" class="hover:text-brand-accent transition-colors">• Yêu Cầu Tư Vấn &amp; Báo Giá</a></li>
          </ul>
        </div>

        <!-- Cột 4: Thông tin liên hệ -->
        <div>
          <h4 class="text-sm font-extrabold text-white uppercase mb-3">THÔNG TIN LIÊN HỆ</h4>
          <ul class="space-y-2.5 text-xs text-stone-300">
            <li class="flex items-start gap-2">
              <i class="fa-solid fa-location-dot text-brand-accent mt-0.5"></i>
              <span>Địa chỉ: Tầng 2, Số 134/5 Yên Bái - Hải Châu - Đà Nẵng</span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-phone-volume text-brand-accent"></i>
              <span>Hotline / Zalo: <a href="tel:0777434358" class="text-white font-bold hover:text-brand-accent">0777.434.358</a></span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-globe text-brand-accent"></i>
              <span>Website: <a href="#trang-chu" class="text-white font-semibold hover:text-brand-accent">fbbase.com</a></span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-brands fa-facebook text-brand-accent"></i>
              <span>Fanpage: <a href="https://www.facebook.com/DaotaophacheFnBBase" target="_blank" rel="noopener" class="text-white hover:text-brand-accent underline">Đào tạo pha chế - F&amp;B Base</a></span>
            </li>
          </ul>
        </div>

      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-stone-400 text-center">
        <p>© Bản quyền thuộc về <strong>Đào tạo pha chế F&amp;B Base (fbbase.com)</strong> – 134/5 Yên Bái, Hải Châu, Đà Nẵng.</p>
        <p>Thiết kế chuẩn bố cục Flatsome UX Builder • Tối ưu máy tính (95%) &amp; điện thoại</p>
      </div>
    </div>
  </footer>

  <!-- ==========================================================================
       CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH MÁY TÍNH & ĐIỆN THOẠI
       ========================================================================== -->
  <div class="fixed right-3 bottom-4 z-50 flex flex-col items-end gap-2.5">
    
    <!-- Nút Zalo nổi bật -->
    <a 
      href="https://zalo.me/0777434358" 
      target="_blank" 
      rel="noopener"
      aria-label="Chat Zalo 0777.434.358"
      class="group flex items-center gap-2 bg-[#0068FF] text-white pl-3 pr-3.5 py-2.5 rounded-full shadow-lg hover:scale-105 transition-transform"
    >
      <span class="w-7 h-7 rounded-full bg-white text-[#0068FF] font-black text-xs flex items-center justify-center shrink-0">Zalo</span>
      <span class="text-xs font-bold whitespace-nowrap">Chat Zalo</span>
    </a>

    <!-- Nút Facebook Fanpage nổi bật -->
    <a 
      href="https://www.facebook.com/DaotaophacheFnBBase" 
      target="_blank" 
      rel="noopener"
      aria-label="Fanpage Đào tạo pha chế F&B Base"
      class="group flex items-center gap-2 bg-[#1877F2] text-white pl-3 pr-3.5 py-2.5 rounded-full shadow-lg hover:scale-105 transition-transform"
    >
      <span class="w-7 h-7 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
        <i class="fa-brands fa-facebook-f text-sm"></i>
      </span>
      <span class="text-xs font-bold whitespace-nowrap">Fanpage</span>
    </a>

    <!-- Nút Hotline nổi bật -->
    <a 
      href="tel:0777434358" 
      aria-label="Gọi ngay 0777.434.358"
      class="floating-pulse flex items-center gap-2 bg-brand-accent text-white pl-3 pr-4 py-2.5 rounded-full shadow-xl hover:bg-amber-600 transition-colors"
    >
      <span class="w-7 h-7 rounded-full bg-white text-brand-dark flex items-center justify-center shrink-0">
        <i class="fa-solid fa-phone-volume text-xs"></i>
      </span>
      <span class="text-xs font-extrabold whitespace-nowrap">0777.434.358</span>
    </a>

  </div>

  <!-- ==========================================================================
       JAVASCRIPT XỬ LÝ DỮ LIỆU SẢN PHẨM, SLIDER TỰ TRƯỢT, FALLBACK ẢNH DRIVE & FORM BÁO GIÁ
       ========================================================================== -->
  <script>
    // Danh sách 9 ID ảnh thực tế từ Google Drive do người dùng cung cấp
    const DRIVE_REAL_IMAGES = [
      '1rGho5fg969qDLR_0HwjCLl07fvvXFcnD',
      '1oEbPHQbnw-_fN12EN1L9-db6ScbpLutN',
      '1Zm8xvocINo_Gco_CWfjlO8Xjw2uA47NN',
      '1o0wBE5h1O8gI551OPfCPLYJLQzQQCD3-',
      '1ET0rUw8l3P5eMHkFFbxfloOQ7IwdHndj',
      '1wU8q1SH4yjgsfkgiY2mOZIhNXUL-H57m',
      '1ZF3YcSyo7r56g1n6dSe8G8c9VQZ29GBk',
      '1w-Z77OHU-cAzdUyvLZpE6V7KMuajJ9-4',
      '1MrWhPGxC_ZL_3Il-KwIS7J3GD0LNemZK'
    ];

    // Hàm tự động chuyển đổi sang link dự phòng nếu Google Drive chặn cookie bên thứ 3
    function handleDriveImgError(imgEl, fallbackLabel) {
      const driveId = imgEl.getAttribute('data-drive-id');
      const step = parseInt(imgEl.getAttribute('data-retry-step') || '0', 10);

      if (driveId && step === 0) {
        imgEl.setAttribute('data-retry-step', '1');
        imgEl.src = 'https://lh3.googleusercontent.com/d/' + driveId + '=w800';
      } else if (driveId && step === 1) {
        imgEl.setAttribute('data-retry-step', '2');
        imgEl.src = 'https://drive.google.com/uc?export=view&id=' + driveId;
      } else {
        imgEl.onerror = null;
        const encodedText = encodeURIComponent(fallbackLabel || 'F&B Base');
        imgEl.src = 'https://placehold.co/600x450/3A2115/FBF8F3?text=' + encodedText;
      }
    }

    // Dữ liệu 4 Danh mục Sản phẩm chuẩn theo web mẫu vincentdanang.vn kết hợp 9 ảnh thực tế Google Drive
    const CATALOG_DATA = {
      mayMoc: [
        { name: 'Máy Làm Đá Bào Bingsu Unibar ISM-130', price: '18.900.000 ₫', driveId: DRIVE_REAL_IMAGES[3] },
        { name: 'Máy Làm Đá Bào Bingsu Unibar ISM-90', price: '9.800.000 ₫', driveId: DRIVE_REAL_IMAGES[0] },
        { name: 'Máy Đánh Trứng, Đánh Kem, Trộn Bột Unitech SM-2000', price: '3.200.000 ₫', driveId: DRIVE_REAL_IMAGES[1] },
        { name: 'Lò Nướng Chuyên Dụng Unitech LU-63', price: '4.200.000 ₫', driveId: DRIVE_REAL_IMAGES[5] },
        { name: 'Máy Lắc Cốc Trà Sữa Đôi Unibar UB-LC2', price: '3.450.000 ₫', driveId: DRIVE_REAL_IMAGES[2] },
        { name: 'Nồi Nấu Trân Châu Tự Động Unibar UBS-16PLUS', price: '4.650.000 ₫', driveId: DRIVE_REAL_IMAGES[6] },
        { name: 'Nồi Nấu Trân Châu Tự Động Unibar UBN-8L', price: '2.390.000 ₫', driveId: DRIVE_REAL_IMAGES[7] },
        { name: 'Nồi Nấu Trân Châu Tự Động Unibar UBN-5L', price: '1.750.000 ₫', driveId: DRIVE_REAL_IMAGES[8] }
      ],
      dungCu: [
        { name: 'Kệ Đựng Chai Siro 6 Ngăn (Sắt Sơn Tĩnh Điện)', price: '500.000 ₫', driveId: DRIVE_REAL_IMAGES[1] },
        { name: 'Kệ Đựng Chai Siro 4 Ngăn (Sắt Sơn Tĩnh Điện)', price: '450.000 ₫', driveId: DRIVE_REAL_IMAGES[3] },
        { name: 'Kệ Đựng 9 Ngăn Vuông Quầy Bar (Mica)', price: '750.000 ₫', driveId: DRIVE_REAL_IMAGES[5] },
        { name: 'Kệ Đựng Cốc 4 Ngăn Vuông (Mica)', price: '450.000 ₫', driveId: DRIVE_REAL_IMAGES[6] },
        { name: 'Kệ Đựng Cốc 2 Tầng 4 Ngăn (Mica)', price: '700.000 ₫', driveId: DRIVE_REAL_IMAGES[0] },
        { name: 'Kệ Đựng Cốc 2 Tầng 8 Ngăn (Mica)', price: '860.000 ₫', driveId: DRIVE_REAL_IMAGES[4] },
        { name: 'Kệ Đựng Cốc 2 Ngăn Quầy Pha Chế (Mica)', price: '250.000 ₫', driveId: DRIVE_REAL_IMAGES[7] },
        { name: 'Kệ Đựng Cốc 2 Tầng 8 Ngăn (Nhựa ABS)', price: '800.000 ₫', driveId: DRIVE_REAL_IMAGES[8] }
      ],
      nguyenLieu: [
        { name: 'Syrup Hương Mãng Cầu Trendy 830ml', price: '110.000 ₫', driveId: DRIVE_REAL_IMAGES[2] },
        { name: 'Nước Cốt Lựu Đỏ Pha Chế Chuyên Dụng', price: '155.000 ₫', driveId: DRIVE_REAL_IMAGES[4] },
        { name: 'Bột Hạt Dẻ Cười Cô Gái Pha Chế', price: '125.000 ₫', driveId: DRIVE_REAL_IMAGES[6] },
        { name: 'Mứt Dưa Lưới Dedu Chính Hãng 1Kg', price: '160.000 ₫', driveId: DRIVE_REAL_IMAGES[7] },
        { name: 'Mứt Dedu Đào Pha Trà Trái Cây 1.3Kg', price: '115.000 ₫', driveId: DRIVE_REAL_IMAGES[8] },
        { name: 'Mứt Dedu Việt Quất Pha Chế 1.3Kg', price: '145.000 ₫', driveId: DRIVE_REAL_IMAGES[0] },
        { name: 'Mứt Dedu Xoài Nhiệt Đới 1.3Kg', price: '159.000 ₫', driveId: DRIVE_REAL_IMAGES[1] },
        { name: 'Mứt Dedu Dứa Tự Nhiên 1.3Kg', price: '120.000 ₫', driveId: DRIVE_REAL_IMAGES[5] }
      ],
      lyTach: [
        { name: 'Ly Thủy Tinh Dáng Bầu – Cao (530ml) Bộ 6 Ly', price: '306.000 ₫', driveId: DRIVE_REAL_IMAGES[4] },
        { name: 'Ly Thủy Tinh Tiki Pha Cocktail (400ml) Bộ 6 Ly', price: '245.000 ₫', driveId: DRIVE_REAL_IMAGES[6] },
        { name: 'Ly Thủy Tinh Vân Đá Loe (300ml) Bộ 6 Ly', price: '180.000 ₫', driveId: DRIVE_REAL_IMAGES[2] },
        { name: 'Ly Thủy Tinh Cong Vân Sọc (550ml) Bộ 6 Ly', price: '248.000 ₫', driveId: DRIVE_REAL_IMAGES[5] },
        { name: 'Ly Thủy Tinh Cong Cao Cấp (500ml) Bộ 6 Ly', price: '384.000 ₫', driveId: DRIVE_REAL_IMAGES[8] },
        { name: 'Ly Thủy Tinh Trụ Tròn – Cao (350ml) – LTT040', price: '204.000 ₫', driveId: DRIVE_REAL_IMAGES[0] },
        { name: 'Ly Thủy Tinh Trụ Tròn – Thấp (230ml) – LTT038', price: '192.000 ₫', driveId: DRIVE_REAL_IMAGES[1] },
        { name: 'Ly Thủy Tinh Vuông Cao Delicious (390ml) – LTT037', price: '294.000 ₫', driveId: DRIVE_REAL_IMAGES[3] }
      ]
    };

    // Hàm tạo thẻ sản phẩm chuẩn Flatsome:
    // - Không có nhãn dán (no badges)
    // - Tên sản phẩm hiển thị đầy đủ (product-title-full), không cắt chữ, không tràn viền
    function renderProductGrid(containerId, items) {
      const container = document.getElementById(containerId);
      if (!container) return;

      container.innerHTML = items.map(function(item) {
        const safeName = item.name.replace(/'/g, "\\'");
        return (
          '<div class="bg-white rounded-xl border border-brand-border overflow-hidden flex flex-col justify-between hover:shadow-md transition-shadow">' +
            '<div>' +
              '<div class="aspect-square w-full bg-stone-100 overflow-hidden">' +
                '<img ' +
                  'src="https://drive.google.com/thumbnail?id=' + item.driveId + '&sz=w700" ' +
                  'data-drive-id="' + item.driveId + '" ' +
                  'alt="' + item.name + '" ' +
                  'class="w-full h-full object-cover hover:scale-105 transition-transform duration-300" ' +
                  'onerror="handleDriveImgError(this, \'' + safeName + '\')"' +
                '>' +
              '</div>' +
              '<div class="p-2.5 sm:p-3.5">' +
                '<h3 class="product-title-full text-xs sm:text-sm font-bold text-brand-dark">' +
                  item.name +
                '</h3>' +
              '</div>' +
            '</div>' +
            '<div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 flex flex-wrap items-center justify-between gap-1.5 border-t border-brand-border/50">' +
              '<span class="text-xs sm:text-sm font-extrabold text-brand-accent">' + item.price + '</span>' +
              '<button type="button" onclick="prefillQuote(\'' + safeName + '\')" class="px-2.5 py-1.5 rounded bg-brand-dark text-white text-[11px] sm:text-xs font-semibold hover:bg-brand-accent transition-colors">' +
                'Báo giá' +
              '</button>' +
            '</div>' +
          '</div>'
        );
      }).join('');
    }

    // Điền nhanh sản phẩm/khóa học vào Form Yêu Cầu Báo Giá và cuộn xuống
    function prefillQuote(itemName) {
      const productInput = document.getElementById('customerProduct');
      const formSection = document.getElementById('bao-gia');
      if (productInput) {
        productInput.value = itemName;
      }
      if (formSection) {
        formSection.scrollIntoView({ behavior: 'smooth' });
      }
    }

    // Lọc danh mục bài viết ở trang chủ
    function filterPosts(category) {
      const cards = document.querySelectorAll('.blog-card');
      const buttons = document.querySelectorAll('.post-cat-btn');

      buttons.forEach(function(btn) {
        if (btn.getAttribute('data-cat') === category) {
          btn.className = 'post-cat-btn cat-nowrap px-3 py-1.5 rounded-md bg-brand-dark text-white text-xs font-semibold transition-colors';
        } else {
          btn.className = 'post-cat-btn cat-nowrap px-3 py-1.5 rounded-md bg-brand-light text-brand-dark border border-brand-border text-xs font-semibold hover:bg-brand-soft transition-colors';
        }
      });

      cards.forEach(function(card) {
        if (category === 'all' || card.getAttribute('data-category') === category) {
          card.classList.remove('hidden');
        } else {
          card.classList.add('hidden');
        }
      });
    }

    // Xử lý gửi Form Báo Giá ở trang chủ
    function handleQuoteSubmit(event) {
      event.preventDefault();
      const name = document.getElementById('customerName').value.trim();
      const phone = document.getElementById('customerPhone').value.trim();
      const category = document.getElementById('serviceCategory').value;
      const product = document.getElementById('customerProduct').value.trim();

      const successBox = document.getElementById('quoteSuccessBox');
      const successText = document.getElementById('quoteSuccessText');

      successText.textContent = 'Cảm ơn ' + name + ' (' + phone + '). Yêu cầu tư vấn "' + category + (product ? ' - ' + product : '') + '" đã được gửi tới bộ phận tuyển sinh & báo giá F&B Base (134/5 Yên Bái, Hải Châu, Đà Nẵng - Hotline/Zalo: 0777.434.358). Chúng tôi sẽ liên hệ lại với bạn trong ít phút!';
      successBox.classList.remove('hidden');
      event.target.reset();
    }

    // Khởi tạo giao diện khi tải trang
    window.addEventListener('DOMContentLoaded', function() {
      // 1. Render 4 danh mục sản phẩm
      renderProductGrid('grid-may-moc', CATALOG_DATA.mayMoc);
      renderProductGrid('grid-dung-cu', CATALOG_DATA.dungCu);
      renderProductGrid('grid-nguyen-lieu', CATALOG_DATA.nguyenLieu);
      renderProductGrid('grid-ly-tach', CATALOG_DATA.lyTach);

      // 2. Xử lý đóng/mở menu trên điện thoại
      const mobileMenuBtn = document.getElementById('mobileMenuBtn');
      const mobileMenuPanel = document.getElementById('mobileMenuPanel');
      if (mobileMenuBtn && mobileMenuPanel) {
        mobileMenuBtn.addEventListener('click', function() {
          mobileMenuPanel.classList.toggle('hidden');
        });
        document.querySelectorAll('.mobile-nav-link').forEach(function(link) {
          link.addEventListener('click', function() {
            mobileMenuPanel.classList.add('hidden');
          });
        });
      }

      // 3. Xử lý Slider 2 ảnh banner tự trượt chuyên nghiệp kích thước bằng nhau
      const slides = document.querySelectorAll('.banner-slide');
      const dots = document.querySelectorAll('.banner-dot');
      const prevBtn = document.getElementById('prevBannerBtn');
      const nextBtn = document.getElementById('nextBannerBtn');
      let currentSlide = 0;
      let slideTimer = null;

      function showSlide(index) {
        currentSlide = (index + slides.length) % slides.length;
        slides.forEach(function(slide, idx) {
          if (idx === currentSlide) {
            slide.classList.add('active');
          } else {
            slide.classList.remove('active');
          }
        });
        dots.forEach(function(dot, idx) {
          if (idx === currentSlide) {
            dot.className = 'banner-dot w-6 h-2 rounded-full bg-brand-accent transition-all';
          } else {
            dot.className = 'banner-dot w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all';
          }
        });
      }

      function startAutoSlide() {
        stopAutoSlide();
        slideTimer = setInterval(function() {
          showSlide(currentSlide + 1);
        }, 5000);
      }

      function stopAutoSlide() {
        if (slideTimer) clearInterval(slideTimer);
      }

      if (prevBtn) {
        prevBtn.addEventListener('click', function() {
          showSlide(currentSlide - 1);
          startAutoSlide();
        });
      }
      if (nextBtn) {
        nextBtn.addEventListener('click', function() {
          showSlide(currentSlide + 1);
          startAutoSlide();
        });
      }
      dots.forEach(function(dot) {
        dot.addEventListener('click', function() {
          const target = parseInt(dot.getAttribute('data-goto') || '0', 10);
          showSlide(target);
          startAutoSlide();
        });
      });

      startAutoSlide();
    });
  </script>
</body>
</html>
