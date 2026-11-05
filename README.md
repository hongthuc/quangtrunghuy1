<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>CÔNG TY TNHH VẬN TẢI VÀ THƯƠNG MẠI QUANG TRUNG HUY - quangtrunghuy.vn</title>
    <meta name="description" content="Công ty TNHH Vận Tải Và Thương Mại Quang Trung Huy chuyên vận chuyển hàng hoá trong nước và quốc tế, vận chuyển container Việt Nam - Lào, dịch vụ thủ tục hải quan tại các cửa khẩu Việt - Lào.">
    
    <!-- Open Graph Thumbnail là Logo trang web khi gửi link -->
    <meta property="og:title" content="CÔNG TY TNHH VẬN TẢI VÀ THƯƠNG MẠI QUANG TRUNG HUY | quangtrunghuy.vn">
    <meta property="og:description" content="Chuyên vận chuyển hàng hoá trong nước & quốc tế, vận chuyển container Việt Nam - Lào, dịch vụ thủ tục hải quan cửa khẩu Việt - Lào. Hotline: 0905.606.660 - 0839.443.444">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://quangtrunghuy.vn">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1jKoMo8WKywpUye5CqsEK0Fq1K5mtnbZn">
    <link rel="icon" href="https://lh3.googleusercontent.com/d/1jKoMo8WKywpUye5CqsEK0Fq1K5mtnbZn" type="image/png">

    <!-- Tailwind CSS & Font Awesome -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            blue: '#0a3d7a',
                            dark: '#062852',
                            light: '#eef4fb',
                            red: '#d9251d',
                            redDark: '#b51b14',
                            gold: '#f59e0b'
                        }
                    },
                    maxWidth: {
                        '1500': '1500px',
                    }
                }
            }
        }
    </script>

    <style>
        /* Đảm bảo tuyệt đối không tràn viền, không lệch sang phải trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Container chuẩn Flatsome 1500px trên máy tính */
        .flatsome-container {
            width: 100%;
            max-width: 1500px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                padding-left: 20px;
                padding-right: 20px;
            }
        }

        /* Danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng, không xuống dòng từng mục */
        .nav-menu-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: flex-end;
            gap: 2px;
            max-width: 100%;
        }
        @media (min-width: 1280px) {
            .nav-menu-list {
                justify-content: flex-end;
                gap: 3px;
            }
        }
        .nav-item-link {
            white-space: nowrap;
            display: inline-flex;
            align-items: center;
            font-size: 11.5px;
            font-weight: 700;
            text-transform: uppercase;
            padding: 6px 8px;
            border-radius: 5px;
            transition: all 0.2s ease;
            color: #0a3d7a;
            letter-spacing: -0.01em;
        }
        .nav-item-link:hover, .nav-item-link.active {
            background-color: #0a3d7a;
            color: #ffffff;
        }

        /* Tiêu đề danh mục chuẩn UX Builder Flatsome */
        .section-title-container {
            margin-bottom: 20px;
        }
        .section-title-main {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #e2e8f0;
            padding-bottom: 10px;
            gap: 10px;
            flex-wrap: wrap;
        }
        .section-title-text {
            font-size: 16px;
            font-weight: 800;
            color: #0a3d7a;
            text-transform: uppercase;
            position: relative;
            padding-left: 12px;
            line-height: 1.3;
        }
        @media (min-width: 768px) {
            .section-title-text {
                font-size: 19px;
            }
        }
        .section-title-text::before {
            content: "";
            position: absolute;
            left: 0;
            top: 2px;
            bottom: 2px;
            width: 4px;
            background-color: #d9251d;
            border-radius: 2px;
        }

        /* Đảm bảo tên sản phẩm / dịch vụ hiển thị đầy đủ, không bị cắt chữ hay tràn ra ngoài */
        .product-title-full {
            word-wrap: break-word;
            overflow-wrap: break-word;
            white-space: normal;
            line-height: 1.38;
        }

        /* Nút liên hệ nổi bên phải */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 37, 29, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(217, 37, 29, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 37, 29, 0); }
        }
        .pulse-btn {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body class="w-full overflow-x-hidden">

    <!-- TOP BAR (Đơn giản, chuẩn Flatsome, không có thanh công cụ UXBuilder) -->
    <div class="bg-brand-dark text-white text-xs py-2 border-b border-blue-900 w-full">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
                <span class="inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-globe text-amber-400"></i>
                    <strong class=" tracking-wide">quangtrunghuy.vn</strong>
                </span>
                <span class="hidden md:inline-flex items-center gap-1.5 text-slate-200">
                    <i class="fa-solid fa-location-dot text-red-400"></i>
                    <span data-i18n="top_addr">10 Hồ Huân Nghiệp, P. Ngũ Hành Sơn & 167 Ngô Quyền, P. Sơn Trà, TP. Đà Nẵng</span>
                </span>
                <span class="inline-flex items-center gap-1.5 text-slate-200">
                    <i class="fa-solid fa-phone-volume text-emerald-400"></i>
                    <span>0905.606.660 - 0839.443.444</span>
                </span>
            </div>

            <!-- Bộ chuyển đổi ngôn ngữ: Tiếng Việt - Tiếng Anh - Tiếng Lào -->
            <div class="flex items-center gap-1.5 ml-auto">
                <span class="text-[11px] text-slate-300 hidden sm:inline" data-i18n="lang_label">Ngôn ngữ:</span>
                <button onclick="setLanguage('vi')" id="btn-lang-vi" class="px-2 py-0.5 rounded text-[11px] font-bold bg-brand-red text-white transition">
                    🇻🇳 VI
                </button>
                <button onclick="setLanguage('en')" id="btn-lang-en" class="px-2 py-0.5 rounded text-[11px] font-bold bg-blue-900/80 hover:bg-blue-800 text-slate-200 transition">
                    🇬🇧 EN
                </button>
                <button onclick="setLanguage('lo')" id="btn-lang-lo" class="px-2 py-0.5 rounded text-[11px] font-bold bg-blue-900/80 hover:bg-blue-800 text-slate-200 transition">
                    🇱🇦 LAO
                </button>
            </div>
        </div>
    </div>

    <!-- HEADER CHÍNH (Không để nút gọi ngay trên header để tránh tràn viền, danh mục chữ nhỏ gọn nằm trên 1 hàng) -->
    <header class="bg-white shadow-sm sticky top-0 z-40 w-full border-b border-slate-200">
        <div class="flatsome-container py-2">
            <div class="flex items-center justify-between gap-2">
                <!-- Logo & Tên công ty nhỏ gọn -->
                <a href="#" class="flex items-center gap-2 min-w-0 shrink-0">
                    <img 
                        src="https://lh3.googleusercontent.com/d/1jKoMo8WKywpUye5CqsEK0Fq1K5mtnbZn" 
                        onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1jKoMo8WKywpUye5CqsEK0Fq1K5mtnbZn&sz=w400';"
                        alt="Logo Quang Trung Huy" 
                        class="h-9 sm:h-10 w-auto object-contain rounded bg-white p-0.5 border border-slate-100 shrink-0"
                    >
                    <div class="min-w-0 leading-tight">
                        <div class="text-[9.5px] sm:text-[10px] font-bold text-brand-red uppercase tracking-tight" data-i18n="company_sub">
                            CÔNG TY TNHH VẬN TẢI & TM
                        </div>
                        <div class="text-xs sm:text-sm font-extrabold text-brand-blue uppercase tracking-tight">
                            QUANG TRUNG HUY
                        </div>
                        <div class="text-[10px] text-slate-500 hidden sm:block">
                            quangtrunghuy.vn
                        </div>
                    </div>
                </a>

                <!-- Menu danh mục trên máy tính: Ngắn gọn, nằm gọn trong khung, không tràn viền -->
                <nav class="hidden lg:block min-w-0 flex-1">
                    <ul class="nav-menu-list">
                        <li><a href="#trang-chu" class="nav-item-link active" data-i18n="nav_home">Trang chủ</a></li>
                        <li><a href="#dich-vu-chinh" class="nav-item-link" data-i18n="nav_domestic">Vận tải Nội địa & Quốc tế</a></li>
                        <li><a href="#dich-vu-chinh" class="nav-item-link" data-i18n="nav_container">Container Việt - Lào</a></li>
                        <li><a href="#dich-vu-chinh" class="nav-item-link" data-i18n="nav_customs">Hải quan Việt - Lào</a></li>
                        <li><a href="#doi-xe-thuc-te" class="nav-item-link" data-i18n="nav_fleet">Đội xe</a></li>
                        <li><a href="#bao-gia-nhanh" class="nav-item-link" data-i18n="nav_quote">Báo giá</a></li>
                        <li><a href="#tin-tuc" class="nav-item-link" data-i18n="nav_news">Bài viết</a></li>
                        <li><a href="#doi-tac" class="nav-item-link" data-i18n="nav_partners">Đối tác</a></li>
                        <li><a href="#lien-he" class="nav-item-link" data-i18n="nav_contact">Liên hệ</a></li>
                    </ul>
                </nav>

                <!-- Nút mở Menu trên Điện thoại -->
                <button onclick="toggleMobileMenu()" aria-label="Menu" class="lg:hidden p-2 rounded-lg bg-slate-100 text-brand-blue hover:bg-slate-200 shrink-0">
                    <i id="mobile-menu-icon" class="fa-solid fa-bars text-base"></i>
                </button>
            </div>

            <!-- Thanh danh mục rút gọn hiển thị trên Điện thoại (Thiết kế đẹp, nhỏ gọn, không tràn viền) -->
            <div class="lg:hidden mt-1.5 pt-1.5 border-t border-slate-100 flex flex-wrap gap-1 justify-center">
                <a href="#dich-vu-chinh" class="px-2 py-1 rounded bg-brand-light text-brand-blue font-bold text-[10.5px] whitespace-nowrap" data-i18n="nav_domestic_short">Nội địa & Quốc tế</a>
                <a href="#dich-vu-chinh" class="px-2 py-1 rounded bg-brand-light text-brand-blue font-bold text-[10.5px] whitespace-nowrap" data-i18n="nav_container_short">Container Việt - Lào</a>
                <a href="#dich-vu-chinh" class="px-2 py-1 rounded bg-brand-light text-brand-blue font-bold text-[10.5px] whitespace-nowrap" data-i18n="nav_customs_short">Hải quan Việt - Lào</a>
                <a href="#bao-gia-nhanh" class="px-2 py-1 rounded bg-red-50 text-brand-red font-bold text-[10.5px] whitespace-nowrap" data-i18n="nav_quote">Báo giá</a>
            </div>

            <!-- Menu xổ xuống trên Điện thoại -->
            <div id="mobile-menu-drawer" class="hidden lg:hidden mt-2 pt-2 border-t border-slate-200">
                <div class="grid grid-cols-2 gap-1.5 pb-2">
                    <a href="#trang-chu" onclick="toggleMobileMenu()" class="px-2.5 py-1.5 rounded bg-slate-50 text-brand-blue font-semibold text-xs" data-i18n="nav_home">Trang chủ</a>
                    <a href="#dich-vu-chinh" onclick="toggleMobileMenu()" class="px-2.5 py-1.5 rounded bg-slate-50 text-brand-blue font-semibold text-xs" data-i18n="nav_domestic">Vận tải Nội địa & Quốc tế</a>
                    <a href="#dich-vu-chinh" onclick="toggleMobileMenu()" class="px-2.5 py-1.5 rounded bg-slate-50 text-brand-blue font-semibold text-xs" data-i18n="nav_container">Container Việt - Lào</a>
                    <a href="#dich-vu-chinh" onclick="toggleMobileMenu()" class="px-2.5 py-1.5 rounded bg-slate-50 text-brand-blue font-semibold text-xs" data-i18n="nav_customs">Hải quan Việt - Lào</a>
                    <a href="#doi-xe-thuc-te" onclick="toggleMobileMenu()" class="px-2.5 py-1.5 rounded bg-slate-50 text-brand-blue font-semibold text-xs" data-i18n="nav_fleet">Đội xe</a>
                    <a href="#bao-gia-nhanh" onclick="toggleMobileMenu()" class="px-2.5 py-1.5 rounded bg-slate-50 text-brand-blue font-semibold text-xs" data-i18n="nav_quote">Báo giá</a>
                    <a href="#tin-tuc" onclick="toggleMobileMenu()" class="px-2.5 py-1.5 rounded bg-slate-50 text-brand-blue font-semibold text-xs" data-i18n="nav_news">Bài viết</a>
                    <a href="#doi-tac" onclick="toggleMobileMenu()" class="px-2.5 py-1.5 rounded bg-slate-50 text-brand-blue font-semibold text-xs" data-i18n="nav_partners">Đối tác</a>
                    <a href="#lien-he" onclick="toggleMobileMenu()" class="px-2.5 py-1.5 rounded bg-slate-50 text-brand-blue font-semibold text-xs col-span-2" data-i18n="nav_contact">Liên hệ & Bản đồ</a>
                </div>
            </div>
        </div>
    </header>

    <!-- SLIDER 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP (Kích thước bằng nhau tuyệt đối, tối ưu chữ nhỏ gọn nằm trọn trong ảnh trên điện thoại) -->
    <section id="trang-chu" class="w-full py-3 bg-white">
        <div class="flatsome-container">
            <div class="relative w-full h-[230px] sm:h-[340px] md:h-[430px] lg:h-[480px] rounded-xl overflow-hidden shadow-md bg-brand-dark">
                
                <!-- Slide 1 -->
                <div id="banner-slide-0" class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10">
                    <img 
                        src="https://lh3.googleusercontent.com/d/1q4OxLgcJ134ja9NZj6pXYxzdg0BbxbJ6" 
                        onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1q4OxLgcJ134ja9NZj6pXYxzdg0BbxbJ6&sz=w1600';"
                        alt="Banner Vận Tải Quang Trung Huy 1" 
                        class="w-full h-full object-cover object-center"
                    >
                    <div class="absolute inset-0 bg-gradient-to-r from-brand-dark/90 via-brand-dark/70 to-brand-dark/30 flex items-center">
                        <div class="w-full px-4 sm:px-10 md:px-14 max-w-3xl text-white">
                            <p class="text-[10px] sm:text-xs md:text-sm font-bold uppercase tracking-wider text-amber-400 mb-1" data-i18n="b1_sub">
                                CÔNG TY TNHH VẬN TẢI VÀ THƯƠNG MẠI QUANG TRUNG HUY
                            </p>
                            <h1 class="text-sm sm:text-xl md:text-3xl lg:text-4xl font-extrabold leading-snug mb-1.5 sm:mb-3 break-words" data-i18n="b1_title">
                                CHUYÊN VẬN CHUYỂN HÀNG HOÁ TRONG NƯỚC & QUỐC TẾ - CONTAINER VIỆT NAM - LÀO
                            </h1>
                            <p class="text-[11px] sm:text-sm md:text-base text-slate-200 leading-relaxed mb-2.5 sm:mb-5 break-words" data-i18n="b1_desc">
                                Đội xe đầu kéo container hiện đại, vận tải hai chiều Việt - Lào an toàn, đúng tiến độ, chi phí tối ưu cho doanh nghiệp.
                            </p>
                            <div class="flex flex-wrap items-center gap-2">
                                <a href="#bao-gia-nhanh" class="px-3 py-1.5 sm:px-5 sm:py-2.5 rounded-lg bg-brand-red hover:bg-brand-redDark text-white font-bold text-[11px] sm:text-sm transition">
                                    <span data-i18n="btn_get_quote">Nhận báo giá ngay</span>
                                </a>
                                <a href="tel:0905606660" class="px-3 py-1.5 sm:px-5 sm:py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white font-bold text-[11px] sm:text-sm transition">
                                    0905.606.660 - 0839.443.444
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Slide 2 (Kích thước bằng nhau 100% với Slide 1) -->
                <div id="banner-slide-1" class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0">
                    <img 
                        src="https://lh3.googleusercontent.com/d/1XDmvgQJ4GXuCJ2Bmivb-XBHsHgE1Iicv" 
                        onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1XDmvgQJ4GXuCJ2Bmivb-XBHsHgE1Iicv&sz=w1600';"
                        alt="Banner Vận Tải Quang Trung Huy 2" 
                        class="w-full h-full object-cover object-center"
                    >
                    <div class="absolute inset-0 bg-gradient-to-r from-brand-dark/90 via-brand-dark/70 to-brand-dark/30 flex items-center">
                        <div class="w-full px-4 sm:px-10 md:px-14 max-w-3xl text-white">
                            <p class="text-[10px] sm:text-xs md:text-sm font-bold uppercase tracking-wider text-amber-400 mb-1" data-i18n="b2_sub">
                                DỊCH VỤ LOGISTICS & HẢI QUAN TRỌN GÓI
                            </p>
                            <h2 class="text-sm sm:text-xl md:text-3xl lg:text-4xl font-extrabold leading-snug mb-1.5 sm:mb-3 break-words" data-i18n="b2_title">
                                DỊCH VỤ THỦ TỤC HẢI QUAN TẠI CÁC CỬA KHẨU VIỆT - LÀO NHANH CHÓNG
                            </h2>
                            <p class="text-[11px] sm:text-sm md:text-base text-slate-200 leading-relaxed mb-2.5 sm:mb-5 break-words" data-i18n="b2_desc">
                                Khai báo hải quan xuất nhập khẩu, quá cảnh hàng hóa tại Lao Bảo, Cha Lo, Cầu Treo, Bờ Y, Nam Giang uy tín và chuyên nghiệp.
                            </p>
                            <div class="flex flex-wrap items-center gap-2">
                                <a href="#dich-vu-chinh" class="px-3 py-1.5 sm:px-5 sm:py-2.5 rounded-lg bg-brand-red hover:bg-brand-redDark text-white font-bold text-[11px] sm:text-sm transition">
                                    <span data-i18n="btn_view_services">Xem dịch vụ vận tải</span>
                                </a>
                                <a href="tel:0839443444" class="px-3 py-1.5 sm:px-5 sm:py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/40 text-white font-bold text-[11px] sm:text-sm transition">
                                    0905.606.660 - 0839.443.444
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng Banner -->
                <button onclick="changeSlide(-1)" aria-label="Slide trước" class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-black/70 text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                </button>
                <button onclick="changeSlide(1)" aria-label="Slide tiếp" class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-black/70 text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                </button>

                <!-- Chấm chỉ báo Slide -->
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button onclick="goToSlide(0)" id="dot-0" class="w-6 h-2 rounded-full bg-amber-400 transition-all"></button>
                    <button onclick="goToSlide(1)" id="dot-1" class="w-2.5 h-2 rounded-full bg-white/60 transition-all"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- 3 LĨNH VỰC TRỌNG TÂM CỦA CÔNG TY (Thiết kế 3 Cột chuẩn UX Builder Flatsome, không nhãn dán) -->
    <section class="py-4 bg-white">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                <!-- Lĩnh vực 1 -->
                <div class="p-4 rounded-xl bg-brand-light border border-blue-100 flex items-start gap-3.5">
                    <div class="w-11 h-11 rounded-lg bg-brand-blue text-white flex items-center justify-center shrink-0 text-lg">
                        <i class="fa-solid fa-truck-fast"></i>
                    </div>
                    <div class="min-w-0">
                        <h3 class="text-sm sm:text-base font-bold text-brand-blue mb-1 product-title-full" data-i18n="core1_title">
                            Vận chuyển hàng hoá trong nước & quốc tế
                        </h3>
                        <p class="text-xs text-slate-600 leading-relaxed" data-i18n="core1_desc">
                            Nhận vận chuyển hàng ghép, hàng nguyên chuyến Bắc - Trung - Nam và liên vận quốc tế đi Lào an toàn, đúng lịch trình.
                        </p>
                    </div>
                </div>
                <!-- Lĩnh vực 2 -->
                <div class="p-4 rounded-xl bg-brand-light border border-blue-100 flex items-start gap-3.5">
                    <div class="w-11 h-11 rounded-lg bg-brand-red text-white flex items-center justify-center shrink-0 text-lg">
                        <i class="fa-solid fa-trailer"></i>
                    </div>
                    <div class="min-w-0">
                        <h3 class="text-sm sm:text-base font-bold text-brand-blue mb-1 product-title-full" data-i18n="core2_title">
                            Vận chuyển hàng hoá bằng Container Việt Nam - Lào
                        </h3>
                        <p class="text-xs text-slate-600 leading-relaxed" data-i18n="core2_desc">
                            Đội xe đầu kéo container 20ft, 40ft, 45ft, moóc sàn, moóc lồng chuyên tuyến Đà Nẵng / Việt Nam đi Viêng Chăn, Savannakhet, Pakse.
                        </p>
                    </div>
                </div>
                <!-- Lĩnh vực 3 -->
                <div class="p-4 rounded-xl bg-brand-light border border-blue-100 flex items-start gap-3.5">
                    <div class="w-11 h-11 rounded-lg bg-brand-blue text-white flex items-center justify-center shrink-0 text-lg">
                        <i class="fa-solid fa-file-shield"></i>
                    </div>
                    <div class="min-w-0">
                        <h3 class="text-sm sm:text-base font-bold text-brand-blue mb-1 product-title-full" data-i18n="core3_title">
                            Dịch vụ thủ tục hải quan tại các cửa khẩu Việt - Lào
                        </h3>
                        <p class="text-xs text-slate-600 leading-relaxed" data-i18n="core3_desc">
                            Tư vấn chứng từ xuất nhập khẩu, thông quan hàng thương mại, hàng dự án và hàng quá cảnh tại tất cả các cửa khẩu Việt - Lào.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- DANH MỤC DỊCH VỤ & SẢN PHẨM VẬN TẢI (Chia 2 cột trên điện thoại, 4 cột trên máy tính, không nhãn dán, tên hiển thị đầy đủ không mất chữ) -->
    <section id="dich-vu-chinh" class="py-7 bg-slate-50">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-main">
                    <h2 class="section-title-text" data-i18n="sec_services_title">
                        DỊCH VỤ VẬN TẢI & HẢI QUAN CHUYÊN NGHIỆP
                    </h2>
                    <div class="flex flex-wrap items-center gap-1.5">
                        <a href="#bao-gia-nhanh" class="text-xs font-semibold text-brand-blue hover:text-brand-red px-2.5 py-1 rounded bg-white border border-slate-200 whitespace-nowrap" data-i18n="cat_tag_all">
                            Tất cả dịch vụ
                        </a>
                        <a href="#bao-gia-nhanh" class="text-xs font-semibold text-slate-600 hover:text-brand-blue px-2.5 py-1 rounded bg-white border border-slate-200 whitespace-nowrap" data-i18n="cat_tag_vnlao">
                            Tuyến Việt - Lào
                        </a>
                        <a href="#bao-gia-nhanh" class="text-xs font-semibold text-slate-600 hover:text-brand-blue px-2.5 py-1 rounded bg-white border border-slate-200 whitespace-nowrap" data-i18n="cat_tag_customs">
                            Hải quan cửa khẩu
                        </a>
                    </div>
                </div>
            </div>

            <!-- Lưới sản phẩm / dịch vụ: 2 cột trên giao diện điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4) -->
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
                
                <!-- Dịch vụ 1 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1ec6rbPC1wPFkrinaBZur1ZP9hhVZQTAn" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1ec6rbPC1wPFkrinaBZur1ZP9hhVZQTAn&sz=w800';"
                            alt="Vận chuyển hàng hoá bằng container Việt Nam - Lào" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="text-xs sm:text-[15px] font-bold text-brand-blue mb-1.5 product-title-full" data-i18n="srv1_title">
                                Vận chuyển hàng hoá bằng Container Việt Nam - Lào
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed mb-3 product-title-full" data-i18n="srv1_desc">
                                Vận tải container 20ft, 40ft nguyên chuyến từ Đà Nẵng và các tỉnh Việt Nam sang Lào.
                            </p>
                        </div>
                        <a href="#bao-gia-nhanh" class="w-full text-center py-1.5 px-2 rounded bg-brand-blue hover:bg-brand-dark text-white font-semibold text-[11px] sm:text-xs transition" data-i18n="btn_ask_quote">
                            Yêu cầu báo giá
                        </a>
                    </div>
                </div>

                <!-- Dịch vụ 2 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1wdeSwgn9Gv9wFT5l-hWUQUn9wjgrlSit" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1wdeSwgn9Gv9wFT5l-hWUQUn9wjgrlSit&sz=w800';"
                            alt="Vận chuyển hàng hoá trong nước Bắc - Trung - Nam" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="text-xs sm:text-[15px] font-bold text-brand-blue mb-1.5 product-title-full" data-i18n="srv2_title">
                                Vận chuyển hàng hoá trong nước Bắc - Trung - Nam
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed mb-3 product-title-full" data-i18n="srv2_desc">
                                Chuyên vận tải đường bộ nội địa nguyên xe hoặc ghép hàng từ Đà Nẵng đi toàn quốc.
                            </p>
                        </div>
                        <a href="#bao-gia-nhanh" class="w-full text-center py-1.5 px-2 rounded bg-brand-blue hover:bg-brand-dark text-white font-semibold text-[11px] sm:text-xs transition" data-i18n="btn_ask_quote">
                            Yêu cầu báo giá
                        </a>
                    </div>
                </div>

                <!-- Dịch vụ 3 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1Blch74NNv1jUpZSayDaIABVlRi-Ln5_f" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Blch74NNv1jUpZSayDaIABVlRi-Ln5_f&sz=w800';"
                            alt="Dịch vụ thủ tục hải quan tại các cửa khẩu Việt - Lào" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="text-xs sm:text-[15px] font-bold text-brand-blue mb-1.5 product-title-full" data-i18n="srv3_title">
                                Dịch vụ thủ tục hải quan tại các cửa khẩu Việt - Lào
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed mb-3 product-title-full" data-i18n="srv3_desc">
                                Khai báo hải quan trọn gói tại cửa khẩu Lao Bảo, Cha Lo, Cầu Treo, Nam Giang, Bờ Y.
                            </p>
                        </div>
                        <a href="#bao-gia-nhanh" class="w-full text-center py-1.5 px-2 rounded bg-brand-blue hover:bg-brand-dark text-white font-semibold text-[11px] sm:text-xs transition" data-i18n="btn_ask_quote">
                            Yêu cầu báo giá
                        </a>
                    </div>
                </div>

                <!-- Dịch vụ 4 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1uGMMEs5UD5wVBNvpS96GJGv0GFhbWDSc" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1uGMMEs5UD5wVBNvpS96GJGv0GFhbWDSc&sz=w800';"
                            alt="Vận chuyển hàng quá cảnh và tạm nhập tái xuất Việt - Lào" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="text-xs sm:text-[15px] font-bold text-brand-blue mb-1.5 product-title-full" data-i18n="srv4_title">
                                Vận chuyển hàng quá cảnh & Tạm nhập tái xuất Việt - Lào
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed mb-3 product-title-full" data-i18n="srv4_desc">
                                Kéo container từ cảng Tiên Sa Đà Nẵng quá cảnh sang Lào và ngược lại nhanh gọn.
                            </p>
                        </div>
                        <a href="#bao-gia-nhanh" class="w-full text-center py-1.5 px-2 rounded bg-brand-blue hover:bg-brand-dark text-white font-semibold text-[11px] sm:text-xs transition" data-i18n="btn_ask_quote">
                            Yêu cầu báo giá
                        </a>
                    </div>
                </div>

                <!-- Dịch vụ 5 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img 
                            src="https://lh3.googleusercontent.com/d/199f7zl1iv9ojoa02BITELJhwY_1AF2rt" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=199f7zl1iv9ojoa02BITELJhwY_1AF2rt&sz=w800';"
                            alt="Vận chuyển sắt thép, vật liệu xây dựng và máy móc công trình" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="text-xs sm:text-[15px] font-bold text-brand-blue mb-1.5 product-title-full" data-i18n="srv5_title">
                                Vận chuyển sắt thép, vật liệu xây dựng & Máy móc công trình
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed mb-3 product-title-full" data-i18n="srv5_desc">
                                Phục vụ các dự án thủy điện, khoáng sản, xây dựng hạ tầng tại Việt Nam và Lào.
                            </p>
                        </div>
                        <a href="#bao-gia-nhanh" class="w-full text-center py-1.5 px-2 rounded bg-brand-blue hover:bg-brand-dark text-white font-semibold text-[11px] sm:text-xs transition" data-i18n="btn_ask_quote">
                            Yêu cầu báo giá
                        </a>
                    </div>
                </div>

                <!-- Dịch vụ 6 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1-b-tMlxSzbvMxp-xL9s_0ks9uhCshxOE" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1-b-tMlxSzbvMxp-xL9s_0ks9uhCshxOE&sz=w800';"
                            alt="Vận chuyển nông sản, quặng, thạch cao, kali từ Lào về Việt Nam" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="text-xs sm:text-[15px] font-bold text-brand-blue mb-1.5 product-title-full" data-i18n="srv6_title">
                                Vận chuyển nông sản, khoáng sản từ Lào về Việt Nam
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed mb-3 product-title-full" data-i18n="srv6_desc">
                                Vận chuyển hàng chiều về từ Lào về các cảng biển và khu công nghiệp tại Việt Nam.
                            </p>
                        </div>
                        <a href="#bao-gia-nhanh" class="w-full text-center py-1.5 px-2 rounded bg-brand-blue hover:bg-brand-dark text-white font-semibold text-[11px] sm:text-xs transition" data-i18n="btn_ask_quote">
                            Yêu cầu báo giá
                        </a>
                    </div>
                </div>

                <!-- Dịch vụ 7 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1v_kh8OOOxAA5a6pAcLHZLoa4lC-w6FYz" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1v_kh8OOOxAA5a6pAcLHZLoa4lC-w6FYz&sz=w800';"
                            alt="Dịch vụ kéo vỏ container và giao nhận hàng hóa tại cảng Đà Nẵng" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="text-xs sm:text-[15px] font-bold text-brand-blue mb-1.5 product-title-full" data-i18n="srv7_title">
                                Giao nhận vận tải Container tại Cảng Đà Nẵng & Miền Trung
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed mb-3 product-title-full" data-i18n="srv7_desc">
                                Kéo container xuất nhập khẩu từ Cảng Tiên Sa đi các khu công nghiệp và cửa khẩu.
                            </p>
                        </div>
                        <a href="#bao-gia-nhanh" class="w-full text-center py-1.5 px-2 rounded bg-brand-blue hover:bg-brand-dark text-white font-semibold text-[11px] sm:text-xs transition" data-i18n="btn_ask_quote">
                            Yêu cầu báo giá
                        </a>
                    </div>
                </div>

                <!-- Dịch vụ 8 -->
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1uDG0DjVe3oAGTnWJbynOwIqFfIK25kBK" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1uDG0DjVe3oAGTnWJbynOwIqFfIK25kBK&sz=w800';"
                            alt="Hỗ trợ chứng từ C/O, kiểm dịch và thông quan biên giới Việt - Lào" 
                            class="w-full h-full object-cover hover:scale-105 transition duration-300"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="text-xs sm:text-[15px] font-bold text-brand-blue mb-1.5 product-title-full" data-i18n="srv8_title">
                                Thủ tục kiểm dịch, C/O & Ủy thác xuất nhập khẩu Việt - Lào
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed mb-3 product-title-full" data-i18n="srv8_desc">
                                Hoàn thiện hồ sơ pháp lý, giấy phép liên vận, C/O mẫu S, kiểm dịch thực vật trọn gói.
                            </p>
                        </div>
                        <a href="#bao-gia-nhanh" class="w-full text-center py-1.5 px-2 rounded bg-brand-blue hover:bg-brand-dark text-white font-semibold text-[11px] sm:text-xs transition" data-i18n="btn_ask_quote">
                            Yêu cầu báo giá
                        </a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- HÌNH ẢNH ĐỘI XE THỰC TẾ QUANG TRUNG HUY (Trọn bộ 13 ảnh xe thực tế từ Google Drive, chia 2 cột trên điện thoại, tên đầy đủ không tràn viền) -->
    <section id="doi-xe-thuc-te" class="py-7 bg-white">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-main">
                    <h2 class="section-title-text" data-i18n="sec_fleet_title">
                        HÌNH ẢNH ĐỘI XE VẬN TẢI THỰC TẾ QUANG TRUNG HUY
                    </h2>
                    <span class="text-xs text-slate-500 font-medium" data-i18n="sec_fleet_sub">
                        100% Hình ảnh phương tiện vận chuyển thực tế của công ty
                    </span>
                </div>
            </div>

            <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-4" id="fleet-gallery-grid">
                <!-- Danh sách 13 ảnh xe thực tế được render bằng HTML rõ ràng để dễ chỉnh sửa trên Flatsome -->
                <div class="rounded-xl border border-slate-200 overflow-hidden bg-slate-50 flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1q4OxLgcJ134ja9NZj6pXYxzdg0BbxbJ6" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1q4OxLgcJ134ja9NZj6pXYxzdg0BbxbJ6&sz=w800';" alt="Đội xe thực tế 01" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="text-xs font-bold text-brand-blue product-title-full" data-i18n="fleet_cap_1">Đầu kéo Container Việt - Lào #01</p>
                    </div>
                </div>

                <div class="rounded-xl border border-slate-200 overflow-hidden bg-slate-50 flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1XDmvgQJ4GXuCJ2Bmivb-XBHsHgE1Iicv" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1XDmvgQJ4GXuCJ2Bmivb-XBHsHgE1Iicv&sz=w800';" alt="Đội xe thực tế 02" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="text-xs font-bold text-brand-blue product-title-full" data-i18n="fleet_cap_2">Xe đầu kéo vận chuyển quốc tế #02</p>
                    </div>
                </div>

                <div class="rounded-xl border border-slate-200 overflow-hidden bg-slate-50 flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1ec6rbPC1wPFkrinaBZur1ZP9hhVZQTAn" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1ec6rbPC1wPFkrinaBZur1ZP9hhVZQTAn&sz=w800';" alt="Đội xe thực tế 03" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="text-xs font-bold text-brand-blue product-title-full" data-i18n="fleet_cap_3">Vận chuyển Container cửa khẩu #03</p>
                    </div>
                </div>

                <div class="rounded-xl border border-slate-200 overflow-hidden bg-slate-50 flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1wdeSwgn9Gv9wFT5l-hWUQUn9wjgrlSit" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1wdeSwgn9Gv9wFT5l-hWUQUn9wjgrlSit&sz=w800';" alt="Đội xe thực tế 04" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="text-xs font-bold text-brand-blue product-title-full" data-i18n="fleet_cap_4">Đội xe tải nặng Quang Trung Huy #04</p>
                    </div>
                </div>

                <div class="rounded-xl border border-slate-200 overflow-hidden bg-slate-50 flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1Blch74NNv1jUpZSayDaIABVlRi-Ln5_f" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1Blch74NNv1jUpZSayDaIABVlRi-Ln5_f&sz=w800';" alt="Đội xe thực tế 05" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="text-xs font-bold text-brand-blue product-title-full" data-i18n="fleet_cap_5">Bốc xếp & Vận tải hàng dự án #05</p>
                    </div>
                </div>

                <div class="rounded-xl border border-slate-200 overflow-hidden bg-slate-50 flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1uGMMEs5UD5wVBNvpS96GJGv0GFhbWDSc" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1uGMMEs5UD5wVBNvpS96GJGv0GFhbWDSc&sz=w800';" alt="Đội xe thực tế 06" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="text-xs font-bold text-brand-blue product-title-full" data-i18n="fleet_cap_6">Kéo Container tại cảng & kho bãi #06</p>
                    </div>
                </div>

                <div class="rounded-xl border border-slate-200 overflow-hidden bg-slate-50 flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/199f7zl1iv9ojoa02BITELJhwY_1AF2rt" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=199f7zl1iv9ojoa02BITELJhwY_1AF2rt&sz=w800';" alt="Đội xe thực tế 07" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="text-xs font-bold text-brand-blue product-title-full" data-i18n="fleet_cap_7">Vận chuyển thiết bị công nghiệp #07</p>
                    </div>
                </div>

                <div class="rounded-xl border border-slate-200 overflow-hidden bg-slate-50 flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1-b-tMlxSzbvMxp-xL9s_0ks9uhCshxOE" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1-b-tMlxSzbvMxp-xL9s_0ks9uhCshxOE&sz=w800';" alt="Đội xe thực tế 08" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="text-xs font-bold text-brand-blue product-title-full" data-i18n="fleet_cap_8">Vận tải đường bộ xuyên biên giới #08</p>
                    </div>
                </div>

                <div class="rounded-xl border border-slate-200 overflow-hidden bg-slate-50 flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1v_kh8OOOxAA5a6pAcLHZLoa4lC-w6FYz" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1v_kh8OOOxAA5a6pAcLHZLoa4lC-w6FYz&sz=w800';" alt="Đội xe thực tế 09" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="text-xs font-bold text-brand-blue product-title-full" data-i18n="fleet_cap_9">Xe Container chuyên tuyến Đà Nẵng - Lào #09</p>
                    </div>
                </div>

                <div class="rounded-xl border border-slate-200 overflow-hidden bg-slate-50 flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1uDG0DjVe3oAGTnWJbynOwIqFfIK25kBK" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1uDG0DjVe3oAGTnWJbynOwIqFfIK25kBK&sz=w800';" alt="Đội xe thực tế 10" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="text-xs font-bold text-brand-blue product-title-full" data-i18n="fleet_cap_10">Thông quan hàng hóa tại cửa khẩu #10</p>
                    </div>
                </div>

                <div class="rounded-xl border border-slate-200 overflow-hidden bg-slate-50 flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1C6Cjmrd_JlPjQtbsLgdOK4rEl0V6BmVQ" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1C6Cjmrd_JlPjQtbsLgdOK4rEl0V6BmVQ&sz=w800';" alt="Đội xe thực tế 11" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="text-xs font-bold text-brand-blue product-title-full" data-i18n="fleet_cap_11">Đoàn xe đầu kéo Quang Trung Huy #11</p>
                    </div>
                </div>

                <div class="rounded-xl border border-slate-200 overflow-hidden bg-slate-50 flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/15fz2ke3EDTXu4mWm8BB-SN8Ea50TuAxq" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=15fz2ke3EDTXu4mWm8BB-SN8Ea50TuAxq&sz=w800';" alt="Đội xe thực tế 12" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="text-xs font-bold text-brand-blue product-title-full" data-i18n="fleet_cap_12">Vận chuyển hàng siêu trường siêu trọng #12</p>
                    </div>
                </div>

                <div class="rounded-xl border border-slate-200 overflow-hidden bg-slate-50 flex flex-col col-span-2 sm:col-span-1">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1bb9O8tQr-WbxScgUXShY8ncQXCQv4IBy" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1bb9O8tQr-WbxScgUXShY8ncQXCQv4IBy&sz=w800';" alt="Đội xe thực tế 13" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 text-center">
                        <p class="text-xs font-bold text-brand-blue product-title-full" data-i18n="fleet_cap_13">Phương tiện sẵn sàng phục vụ 24/7 #13</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ (Thiết kế 2 cột rõ ràng, dễ làm lại trên Flatsome) -->
    <section id="bao-gia-nhanh" class="py-8 bg-brand-dark text-white">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                
                <!-- Cột thông tin cam kết -->
                <div class="lg:col-span-5 space-y-4">
                    <h2 class="text-lg sm:text-2xl font-extrabold text-amber-400 uppercase leading-snug" data-i18n="quote_heading">
                        ĐĂNG KÝ YÊU CẦU VẬN CHUYỂN & NHẬN BÁO GIÁ NHANH
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-200 leading-relaxed" data-i18n="quote_sub">
                        Quý khách vui lòng điền thông tin lộ trình, loại hàng hóa hoặc dịch vụ hải quan cần hỗ trợ. Bộ phận điều vận Quang Trung Huy sẽ phản hồi báo giá chi tiết trong vòng 15 phút.
                    </p>
                    <div class="space-y-2.5 text-xs sm:text-sm">
                        <div class="flex items-center gap-3 bg-white/10 p-3 rounded-lg">
                            <i class="fa-solid fa-phone-volume text-amber-400 text-lg shrink-0"></i>
                            <div>
                                <div class="text-slate-300 text-xs" data-i18n="hotline_247">Hotline tư vấn & báo giá 24/7:</div>
                                <div class="font-extrabold text-base text-white">0905.606.660 - 0839.443.444</div>
                            </div>
                        </div>
                        <div class="flex items-start gap-3 bg-white/10 p-3 rounded-lg">
                            <i class="fa-solid fa-location-dot text-red-400 text-lg mt-0.5 shrink-0"></i>
                            <div>
                                <div class="font-semibold text-white" data-i18n="addr_main_label">Trụ sở chính:</div>
                                <div class="text-slate-200 text-xs">10 Hồ Huân Nghiệp, Phường Ngũ Hành Sơn, Tp.Đà Nẵng</div>
                                <div class="font-semibold text-white mt-1.5" data-i18n="addr_office_label">Văn phòng giao dịch:</div>
                                <div class="text-slate-200 text-xs">167 Ngô Quyền, Phường Sơn Trà, Tp.Đà Nẵng</div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Cột Form Báo Giá -->
                <div class="lg:col-span-7 bg-white text-slate-800 rounded-xl p-4 sm:p-6 shadow-lg">
                    <h3 class="text-base sm:text-lg font-extrabold text-brand-blue uppercase mb-4 pb-2 border-b border-slate-200" data-i18n="form_title">
                        FORM YÊU CẦU VÀ BÁO GIÁ VẬN TẢI
                    </h3>
                    <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="space-y-3">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1" data-i18n="f_name">Họ và tên / Tên công ty *</label>
                                <input type="text" id="q_name" required placeholder="Nhập tên của quý khách..." class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-blue">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1" data-i18n="f_phone">Số điện thoại liên hệ *</label>
                                <input type="tel" id="q_phone" required placeholder="Ví dụ: 0905606660" class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-blue">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1" data-i18n="f_service">Dịch vụ cần báo giá *</label>
                                <select id="q_service" class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-blue bg-white">
                                    <option value="Vận chuyển Container Việt Nam - Lào" data-i18n="opt_1">Vận chuyển hàng hoá bằng Container Việt Nam - Lào</option>
                                    <option value="Vận chuyển hàng hoá trong nước & quốc tế" data-i18n="opt_2">Vận chuyển hàng hoá trong nước / quốc tế</option>
                                    <option value="Thủ tục hải quan cửa khẩu Việt - Lào" data-i18n="opt_3">Dịch vụ thủ tục hải quan tại các cửa khẩu Việt - Lào</option>
                                    <option value="Vận chuyển hàng quá cảnh / dự án" data-i18n="opt_4">Vận chuyển hàng quá cảnh / máy móc dự án</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1" data-i18n="f_route">Tuyến đường / Cửa khẩu dự kiến</label>
                                <input type="text" id="q_route" placeholder="VD: Đà Nẵng - Lao Bảo - Viêng Chăn" class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-blue">
                            </div>
                        </div>

                        <div>
                            <label class="block text-xs font-bold text-slate-700 mb-1" data-i18n="f_detail">Thông tin hàng hóa (Tên hàng, số lượng, trọng lượng, loại container...)</label>
                            <textarea id="q_detail" rows="3" placeholder="Nhập chi tiết quy cách hàng hóa, điểm nhận hàng và điểm giao hàng..." class="w-full px-3 py-2 text-xs sm:text-sm rounded-lg border border-slate-300 focus:outline-none focus:border-brand-blue"></textarea>
                        </div>

                        <button type="submit" class="w-full py-2.5 px-4 rounded-lg bg-brand-red hover:bg-brand-redDark text-white font-bold text-xs sm:text-sm uppercase tracking-wide transition">
                            <i class="fa-solid fa-paper-plane mr-1.5"></i>
                            <span data-i18n="btn_submit_quote">GỬI YÊU CẦU BÁO GIÁ NGAY</span>
                        </button>

                        <!-- Thông báo gửi thành công -->
                        <div id="quoteSuccessMsg" class="hidden p-3 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs font-semibold">
                            Cảm ơn Quý khách! Yêu cầu báo giá đã được ghi nhận. Chúng tôi sẽ liên hệ ngay qua số điện thoại của Quý khách hoặc Quý khách có thể kết nối trực tiếp Zalo: 0905.606.660.
                        </div>
                    </form>
                </div>

            </div>
        </div>
    </section>

    <!-- DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (Chia 2 cột trên điện thoại, 4 cột trên máy tính, chữ không tràn viền) -->
    <section id="tin-tuc" class="py-7 bg-slate-50">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-main">
                    <h2 class="section-title-text" data-i18n="sec_news_title">
                        DANH MỤC BÀI VIẾT & TIN TỨC VẬN TẢI
                    </h2>
                    <span class="text-xs text-slate-500 font-medium" data-i18n="sec_news_sub">
                        Kiến thức Logistics, thủ tục hải quan Việt - Lào & hoạt động công ty
                    </span>
                </div>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-4 gap-3 sm:gap-5">
                <!-- Bài viết 1 -->
                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
                    <div class="aspect-[16/10] w-full bg-slate-100 overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/1C6Cjmrd_JlPjQtbsLgdOK4rEl0V6BmVQ" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1C6Cjmrd_JlPjQtbsLgdOK4rEl0V6BmVQ&sz=w800';" alt="Quy trình vận chuyển hàng hóa bằng container đi Lào" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 sm:p-4 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-brand-blue mb-1.5 product-title-full" data-i18n="news1_title">
                                Quy trình vận chuyển hàng hóa bằng Container từ Việt Nam sang Lào trọn gói
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed product-title-full" data-i18n="news1_desc">
                                Hướng dẫn chi tiết các bước đóng hàng, khai báo hải quan và vận tải đường bộ qua các cửa khẩu quốc tế Việt - Lào.
                            </p>
                        </div>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
                    <div class="aspect-[16/10] w-full bg-slate-100 overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/15fz2ke3EDTXu4mWm8BB-SN8Ea50TuAxq" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=15fz2ke3EDTXu4mWm8BB-SN8Ea50TuAxq&sz=w800';" alt="Thủ tục hải quan tại cửa khẩu Lao Bảo, Cha Lo, Nam Giang, Bờ Y" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 sm:p-4 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-brand-blue mb-1.5 product-title-full" data-i18n="news2_title">
                                Hồ sơ cần chuẩn bị khi làm thủ tục hải quan tại các cửa khẩu Việt - Lào
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed product-title-full" data-i18n="news2_desc">
                                Tổng hợp danh mục chứng từ Invoice, Packing List, C/O Form S và thủ tục thông quan nhanh tại Lao Bảo, Nam Giang, Cha Lo.
                            </p>
                        </div>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
                    <div class="aspect-[16/10] w-full bg-slate-100 overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/1bb9O8tQr-WbxScgUXShY8ncQXCQv4IBy" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1bb9O8tQr-WbxScgUXShY8ncQXCQv4IBy&sz=w800';" alt="Tuyến vận tải Đà Nẵng đi Viêng Chăn, Savannakhet, Pakse" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 sm:p-4 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-brand-blue mb-1.5 product-title-full" data-i18n="news3_title">
                                Lịch trình và thời gian vận chuyển hàng từ Đà Nẵng đi Viêng Chăn, Pakse, Savannakhet
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed product-title-full" data-i18n="news3_desc">
                                Tối ưu chi phí cước vận tải hai chiều Việt Nam - Lào với đội xe đầu kéo container hoạt động liên tục mỗi ngày.
                            </p>
                        </div>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm flex flex-col">
                    <div class="aspect-[16/10] w-full bg-slate-100 overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/1q4OxLgcJ134ja9NZj6pXYxzdg0BbxbJ6" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1q4OxLgcJ134ja9NZj6pXYxzdg0BbxbJ6&sz=w800';" alt="Kinh nghiệm vận chuyển hàng quá cảnh và hàng dự án đi Lào" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3 sm:p-4 flex flex-col flex-1 justify-between">
                        <div>
                            <h3 class="text-xs sm:text-sm font-bold text-brand-blue mb-1.5 product-title-full" data-i18n="news4_title">
                                Giải pháp vận chuyển hàng quá cảnh và thiết bị dự án qua cảng Đà Nẵng đi Lào
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed product-title-full" data-i18n="news4_desc">
                                Quang Trung Huy cung cấp giải pháp khai thác hàng quá cảnh từ Cảng Tiên Sa đi thẳng đến chân công trình tại Lào.
                            </p>
                        </div>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- DANH MỤC CÁC ĐỐI TÁC (Chia 2 cột trên điện thoại, 6 cột trên máy tính) -->
    <section id="doi-tac" class="py-7 bg-white border-t border-slate-200">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-main">
                    <h2 class="section-title-text" data-i18n="sec_partners_title">
                        ĐỐI TÁC & KHÁCH HÀNG TIÊU BIỂU
                    </h2>
                    <span class="text-xs text-slate-500 font-medium" data-i18n="sec_partners_sub">
                        Đồng hành cùng các cảng biển, hãng tàu và doanh nghiệp xuất nhập khẩu Việt - Lào
                    </span>
                </div>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
                <div class="p-3.5 rounded-xl bg-slate-50 border border-slate-200 text-center flex flex-col items-center justify-center">
                    <i class="fa-solid fa-anchor text-2xl text-brand-blue mb-1.5"></i>
                    <div class="text-xs font-extrabold text-brand-blue product-title-full" data-i18n="p1_name">CẢNG ĐÀ NẴNG (TIÊN SA)</div>
                    <div class="text-[11px] text-slate-500 mt-0.5" data-i18n="p1_sub">Đối tác khai thác cảng</div>
                </div>
                <div class="p-3.5 rounded-xl bg-slate-50 border border-slate-200 text-center flex flex-col items-center justify-center">
                    <i class="fa-solid fa-road-barrier text-2xl text-brand-red mb-1.5"></i>
                    <div class="text-xs font-extrabold text-brand-blue product-title-full" data-i18n="p2_name">HẢI QUAN CỬA KHẨU VIỆT - LÀO</div>
                    <div class="text-[11px] text-slate-500 mt-0.5" data-i18n="p2_sub">Lao Bảo - Nam Giang - Cha Lo - Bờ Y</div>
                </div>
                <div class="p-3.5 rounded-xl bg-slate-50 border border-slate-200 text-center flex flex-col items-center justify-center">
                    <i class="fa-solid fa-ship text-2xl text-brand-blue mb-1.5"></i>
                    <div class="text-xs font-extrabold text-brand-blue product-title-full" data-i18n="p3_name">HÃNG TÀU CONTAINER QUỐC TẾ</div>
                    <div class="text-[11px] text-slate-500 mt-0.5" data-i18n="p3_sub">Đối tác vỏ Cont 20ft / 40ft</div>
                </div>
                <div class="p-3.5 rounded-xl bg-slate-50 border border-slate-200 text-center flex flex-col items-center justify-center">
                    <i class="fa-solid fa-industry text-2xl text-brand-red mb-1.5"></i>
                    <div class="text-xs font-extrabold text-brand-blue product-title-full" data-i18n="p4_name">KHU CÔNG NGHIỆP MIỀN TRUNG</div>
                    <div class="text-[11px] text-slate-500 mt-0.5" data-i18n="p4_sub">Hòa Khánh - Chu Lai - Dung Quất</div>
                </div>
                <div class="p-3.5 rounded-xl bg-slate-50 border border-slate-200 text-center flex flex-col items-center justify-center">
                    <i class="fa-solid fa-helmet-safety text-2xl text-brand-blue mb-1.5"></i>
                    <div class="text-xs font-extrabold text-brand-blue product-title-full" data-i18n="p5_name">TẬP ĐOÀN XÂY DỰNG & KHOÁNG SẢN</div>
                    <div class="text-[11px] text-slate-500 mt-0.5" data-i18n="p5_sub">Dự án thủy điện & năng lượng Lào</div>
                </div>
                <div class="p-3.5 rounded-xl bg-slate-50 border border-slate-200 text-center flex flex-col items-center justify-center">
                    <i class="fa-solid fa-boxes-packing text-2xl text-brand-red mb-1.5"></i>
                    <div class="text-xs font-extrabold text-brand-blue product-title-full" data-i18n="p6_name">DOANH NGHIỆP XUẤT NHẬP KHẨU</div>
                    <div class="text-[11px] text-slate-500 mt-0.5" data-i18n="p6_sub">Thương mại song phương Việt - Lào</div>
                </div>
            </div>
        </div>
    </section>

    <!-- ĐƯA FANPAGE & GOOGLE MAP RA NGOÀI TRANG CHỦ (Hiển thị trực quan ngay trên trang chủ) -->
    <section id="lien-he" class="py-7 bg-slate-100 border-t border-slate-200">
        <div class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-main">
                    <h2 class="section-title-text" data-i18n="sec_connect_title">
                        KẾT NỐI FANPAGE & BẢN ĐỒ GOOGLE MAPS QUANG TRUNG HUY
                    </h2>
                </div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-2 gap-5">
                
                <!-- Khung Fanpage Facebook ngoài trang chủ -->
                <div class="bg-white rounded-xl border border-slate-200 p-4 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between gap-2 pb-3 mb-3 border-b border-slate-100">
                            <div class="flex items-center gap-2.5 min-w-0">
                                <img 
                                    src="https://lh3.googleusercontent.com/d/1jKoMo8WKywpUye5CqsEK0Fq1K5mtnbZn" 
                                    onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1jKoMo8WKywpUye5CqsEK0Fq1K5mtnbZn&sz=w200';"
                                    alt="Logo Fanpage Quang Trung Huy" 
                                    class="w-11 h-11 rounded-full object-contain border border-slate-200 p-0.5 shrink-0"
                                >
                                <div class="min-w-0">
                                    <h3 class="text-xs sm:text-sm font-extrabold text-brand-blue product-title-full">
                                        CÔNG TY TNHH VẬN TẢI VÀ THƯƠNG MẠI QUANG TRUNG HUY
                                    </h3>
                                    <p class="text-[11px] text-slate-500">Facebook Fanpage Chính Thức</p>
                                </div>
                            </div>
                            <a href="https://www.facebook.com/profile.php?id=100063623618046" target="_blank" rel="noopener noreferrer" class="px-3 py-1.5 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white font-bold text-xs whitespace-nowrap shrink-0">
                                <i class="fa-brands fa-facebook mr-1"></i> Theo dõi Fanpage
                            </a>
                        </div>

                        <!-- Hình ảnh hoạt động Fanpage & Plugin nhúng -->
                        <div class="grid grid-cols-2 gap-2.5 mb-3">
                            <a href="https://www.facebook.com/profile.php?id=100063623618046" target="_blank" rel="noopener noreferrer" class="block aspect-[16/10] rounded-lg overflow-hidden bg-slate-100 border border-slate-200">
                                <img src="https://lh3.googleusercontent.com/d/1q4OxLgcJ134ja9NZj6pXYxzdg0BbxbJ6" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1q4OxLgcJ134ja9NZj6pXYxzdg0BbxbJ6&sz=w600';" alt="Hoạt động Fanpage 1" class="w-full h-full object-cover">
                            </a>
                            <a href="https://www.facebook.com/profile.php?id=100063623618046" target="_blank" rel="noopener noreferrer" class="block aspect-[16/10] rounded-lg overflow-hidden bg-slate-100 border border-slate-200">
                                <img src="https://lh3.googleusercontent.com/d/1XDmvgQJ4GXuCJ2Bmivb-XBHsHgE1Iicv" onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1XDmvgQJ4GXuCJ2Bmivb-XBHsHgE1Iicv&sz=w600';" alt="Hoạt động Fanpage 2" class="w-full h-full object-cover">
                            </a>
                        </div>

                        <div class="w-full overflow-hidden rounded-lg border border-slate-200 bg-slate-50 p-3 text-xs text-slate-700 space-y-1.5">
                            <p class="font-bold text-brand-blue"><i class="fa-solid fa-circle-check text-emerald-600 mr-1"></i> Chuyên: Vận chuyển hàng hoá trong nước / quốc tế</p>
                            <p class="font-bold text-brand-blue"><i class="fa-solid fa-circle-check text-emerald-600 mr-1"></i> Chuyên: Vận chuyển hàng hoá bằng container Việt Nam - Lào</p>
                            <p class="font-bold text-brand-blue"><i class="fa-solid fa-circle-check text-emerald-600 mr-1"></i> Chuyên: Dịch vụ thủ tục hải quan tại các cửa khẩu Việt - Lào</p>
                        </div>
                    </div>

                    <div class="mt-3 pt-3 border-t border-slate-100 flex flex-wrap items-center justify-between gap-2">
                        <span class="text-xs text-slate-500">Cập nhật hình ảnh đóng hàng & thông quan hàng ngày</span>
                        <a href="https://www.facebook.com/profile.php?id=100063623618046" target="_blank" rel="noopener noreferrer" class="text-xs font-bold text-[#1877F2] hover:underline">
                            Mở trang Fanpage Facebook <i class="fa-solid fa-arrow-up-right-from-square ml-1"></i>
                        </a>
                    </div>
                </div>

                <!-- Khung Bản đồ Google Map ngoài trang chủ -->
                <div class="bg-white rounded-xl border border-slate-200 p-4 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between gap-2 pb-3 mb-3 border-b border-slate-100">
                            <div>
                                <h3 class="text-xs sm:text-sm font-extrabold text-brand-blue uppercase" data-i18n="map_box_title">
                                    VỊ TRÍ TRỤ SỞ & VĂN PHÒNG TRÊN GOOGLE MAPS
                                </h3>
                                <p class="text-[11px] text-slate-500">10 Hồ Huân Nghiệp, P. Ngũ Hành Sơn & 167 Ngô Quyền, P. Sơn Trà, Đà Nẵng</p>
                            </div>
                            <a href="https://maps.app.goo.gl/e44dXZHWxA93c2zn9" target="_blank" rel="noopener noreferrer" class="px-3 py-1.5 rounded-lg bg-brand-red hover:bg-brand-redDark text-white font-bold text-xs whitespace-nowrap shrink-0">
                                <i class="fa-solid fa-map-location-dot mr-1"></i> Mở Google Maps
                            </a>
                        </div>

                        <!-- Bản đồ Google Maps nhúng trực tiếp ngoài trang chủ -->
                        <div class="w-full h-[240px] sm:h-[260px] rounded-lg overflow-hidden border border-slate-200 bg-slate-100">
                            <iframe 
                                title="Bản đồ Công ty TNHH Vận Tải Và Thương Mại Quang Trung Huy"
                                src="https://maps.google.com/maps?q=167%20Ng%C3%B4%20Quy%E1%BB%81n,%20S%C6%A1n%20Tr%C3%A0,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=14&ie=UTF8&iwloc=&output=embed" 
                                class="w-full h-full border-0" 
                                allowfullscreen="" 
                                loading="lazy" 
                                referrerpolicy="no-referrer-when-downgrade">
                            </iframe>
                        </div>
                    </div>

                    <div class="mt-3 pt-3 border-t border-slate-100 flex flex-wrap items-center justify-between gap-2 text-xs">
                        <span class="text-slate-600 font-medium">
                            <i class="fa-solid fa-location-dot text-brand-red mr-1"></i>
                            Link Map chính thức: <strong class="text-brand-blue">maps.app.goo.gl/e44dXZHWxA93c2zn9</strong>
                        </span>
                        <a href="https://maps.app.goo.gl/e44dXZHWxA93c2zn9" target="_blank" rel="noopener noreferrer" class="font-bold text-brand-blue hover:text-brand-red">
                            Chỉ đường ngay <i class="fa-solid fa-diamond-turn-right ml-1"></i>
                        </a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- FOOTER (Chuẩn Flatsome, rõ ràng, đầy đủ thông tin công ty) -->
    <footer class="bg-brand-dark text-white pt-8 pb-20 sm:pb-8 border-t-4 border-brand-red">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 pb-6 border-b border-blue-900">
                
                <!-- Thông tin công ty -->
                <div class="lg:col-span-5 space-y-2.5">
                    <div class="flex items-center gap-3">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1jKoMo8WKywpUye5CqsEK0Fq1K5mtnbZn" 
                            onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1jKoMo8WKywpUye5CqsEK0Fq1K5mtnbZn&sz=w200';"
                            alt="Logo Quang Trung Huy" 
                            class="h-12 w-auto bg-white p-1 rounded"
                        >
                        <div>
                            <h3 class="text-sm sm:text-base font-extrabold text-amber-400 uppercase leading-snug" data-i18n="footer_company">
                                CÔNG TY TNHH VẬN TẢI VÀ THƯƠNG MẠI QUANG TRUNG HUY
                            </h3>
                            <p class="text-xs text-slate-300">Website: quangtrunghuy.vn</p>
                        </div>
                    </div>
                    <p class="text-xs text-slate-300 leading-relaxed" data-i18n="footer_about">
                        Đơn vị uy tín hàng đầu chuyên vận chuyển hàng hoá trong nước và quốc tế, vận chuyển hàng hoá bằng container Việt Nam - Lào và dịch vụ thủ tục hải quan trọn gói tại các cửa khẩu Việt - Lào.
                    </p>
                </div>

                <!-- Dịch vụ chính -->
                <div class="lg:col-span-3 space-y-2">
                    <h4 class="text-xs sm:text-sm font-extrabold uppercase text-amber-400 tracking-wide" data-i18n="footer_srv_head">
                        LĨNH VỰC HOẠT ĐỘNG
                    </h4>
                    <ul class="space-y-1.5 text-xs text-slate-200">
                        <li><a href="#dich-vu-chinh" class="hover:text-amber-400">• <span data-i18n="core1_title">Vận chuyển hàng hoá trong nước & quốc tế</span></a></li>
                        <li><a href="#dich-vu-chinh" class="hover:text-amber-400">• <span data-i18n="core2_title">Vận chuyển hàng hoá bằng Container Việt Nam - Lào</span></a></li>
                        <li><a href="#dich-vu-chinh" class="hover:text-amber-400">• <span data-i18n="core3_title">Dịch vụ thủ tục hải quan tại các cửa khẩu Việt - Lào</span></a></li>
                        <li><a href="#bao-gia-nhanh" class="hover:text-amber-400">• <span data-i18n="srv4_title">Vận chuyển hàng quá cảnh & Tạm nhập tái xuất Việt - Lào</span></a></li>
                    </ul>
                </div>

                <!-- Địa chỉ & Liên hệ -->
                <div class="lg:col-span-4 space-y-2 text-xs text-slate-200">
                    <h4 class="text-xs sm:text-sm font-extrabold uppercase text-amber-400 tracking-wide" data-i18n="footer_contact_head">
                        THÔNG TIN LIÊN HỆ
                    </h4>
                    <p><i class="fa-solid fa-building text-amber-400 mr-1.5"></i> <strong data-i18n="addr_main_label">Địa chỉ:</strong> 10 Hồ Huân Nghiệp, Phường Ngũ Hành Sơn, Tp.Đà Nẵng</p>
                    <p><i class="fa-solid fa-location-dot text-red-400 mr-1.5"></i> <strong data-i18n="addr_office_label">Văn phòng:</strong> 167 Ngô Quyền, Phường Sơn Trà, Tp.Đà Nẵng</p>
                    <p><i class="fa-solid fa-phone-volume text-emerald-400 mr-1.5"></i> <strong>Hotline:</strong> <a href="tel:0905606660" class="font-bold text-white hover:text-amber-400">0905.606.660</a> - <a href="tel:0839443444" class="font-bold text-white hover:text-amber-400">0839.443.444</a></p>
                    <p><i class="fa-brands fa-facebook text-blue-400 mr-1.5"></i> <strong>Fanpage:</strong> <a href="https://www.facebook.com/profile.php?id=100063623618046" target="_blank" rel="noopener noreferrer" class="underline hover:text-amber-400">Vận Tải Quang Trung Huy</a></p>
                    <p><i class="fa-solid fa-map text-amber-400 mr-1.5"></i> <strong>Google Map:</strong> <a href="https://maps.app.goo.gl/e44dXZHWxA93c2zn9" target="_blank" rel="noopener noreferrer" class="underline hover:text-amber-400">Xem vị trí trên bản đồ</a></p>
                </div>

            </div>

            <div class="pt-4 flex flex-wrap items-center justify-between gap-2 text-xs text-slate-400">
                <p>© Bản quyền thuộc về CÔNG TY TNHH VẬN TẢI VÀ THƯƠNG MẠI QUANG TRUNG HUY (quangtrunghuy.vn)</p>
                <p>Hotline: 0905.606.660 - 0839.443.444</p>
            </div>
        </div>
    </footer>

    <!-- CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE (Gọn gàng, không tràn viền) -->
    <div class="fixed right-3 bottom-4 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Zalo nổi bật -->
        <a href="https://zalo.me/0905606660" target="_blank" rel="noopener noreferrer" class="flex items-center gap-2 px-3 py-2 rounded-full bg-[#0068ff] hover:bg-blue-700 text-white shadow-lg transition">
            <span class="w-7 h-7 rounded-full bg-white text-[#0068ff] font-black text-xs flex items-center justify-center shrink-0">Zalo</span>
            <span class="text-xs font-bold pr-1 hidden sm:inline">Chat Zalo: 0905.606.660</span>
        </a>

        <!-- Nút Facebook Fanpage nổi bật -->
        <a href="https://www.facebook.com/profile.php?id=100063623618046" target="_blank" rel="noopener noreferrer" class="flex items-center gap-2 px-3 py-2 rounded-full bg-[#1877F2] hover:bg-blue-800 text-white shadow-lg transition">
            <span class="w-7 h-7 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
                <i class="fa-brands fa-facebook-f text-sm"></i>
            </span>
            <span class="text-xs font-bold pr-1 hidden sm:inline">Fanpage Facebook</span>
        </a>

        <!-- Nút Hotline 1 nổi bật -->
        <a href="tel:0905606660" class="pulse-btn flex items-center gap-2 px-3 py-2 rounded-full bg-brand-red hover:bg-brand-redDark text-white shadow-lg transition">
            <span class="w-7 h-7 rounded-full bg-white text-brand-red flex items-center justify-center shrink-0">
                <i class="fa-solid fa-phone-volume text-xs"></i>
            </span>
            <span class="text-xs font-extrabold pr-1">0905.606.660</span>
        </a>

        <!-- Nút Hotline 2 nổi bật -->
        <a href="tel:0839443444" class="flex items-center gap-2 px-3 py-2 rounded-full bg-brand-blue hover:bg-brand-dark text-white shadow-lg transition">
            <span class="w-7 h-7 rounded-full bg-amber-400 text-brand-dark flex items-center justify-center shrink-0">
                <i class="fa-solid fa-phone text-xs"></i>
            </span>
            <span class="text-xs font-extrabold pr-1">0839.443.444</span>
        </a>
    </div>

    <!-- JAVASCRIPT: SLIDER TỰ TRƯỢT + ĐA NGÔN NGỮ (VIỆT - ANH - LÀO) + FORM BÁO GIÁ -->
    <script>
        // 1. Điều khiển Menu Điện thoại
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobile-menu-drawer');
            const icon = document.getElementById('mobile-menu-icon');
            if (drawer.classList.contains('hidden')) {
                drawer.classList.remove('hidden');
                icon.className = 'fa-solid fa-xmark text-lg';
            } else {
                drawer.classList.add('hidden');
                icon.className = 'fa-solid fa-bars text-lg';
            }
        }

        // 2. Điều khiển 2 Banner tự trượt chuyên nghiệp kích thước bằng nhau
        let currentSlide = 0;
        const totalSlides = 2;
        let slideInterval = null;

        function showSlide(index) {
            currentSlide = (index + totalSlides) % totalSlides;
            for (let i = 0; i < totalSlides; i++) {
                const slide = document.getElementById('banner-slide-' + i);
                const dot = document.getElementById('dot-' + i);
                if (i === currentSlide) {
                    slide.classList.remove('opacity-0', 'z-0');
                    slide.classList.add('opacity-100', 'z-10');
                    dot.className = 'w-6 h-2 rounded-full bg-amber-400 transition-all';
                } else {
                    slide.classList.remove('opacity-100', 'z-10');
                    slide.classList.add('opacity-0', 'z-0');
                    dot.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
                }
            }
        }

        function changeSlide(step) {
            showSlide(currentSlide + step);
            resetSlideTimer();
        }

        function goToSlide(index) {
            showSlide(index);
            resetSlideTimer();
        }

        function resetSlideTimer() {
            if (slideInterval) clearInterval(slideInterval);
            slideInterval = setInterval(() => {
                showSlide(currentSlide + 1);
            }, 5000);
        }

        // 3. Xử lý gửi Form Báo Giá
        function submitQuoteForm(e) {
            e.preventDefault();
            const msg = document.getElementById('quoteSuccessMsg');
            msg.classList.remove('hidden');
            document.getElementById('quoteForm').reset();
        }

        // 4. Từ điển Đa ngôn ngữ: Tiếng Việt (vi), Tiếng Anh (en), Tiếng Lào (lo)
        const translations = {
            vi: {
                top_addr: "10 Hồ Huân Nghiệp, P. Ngũ Hành Sơn & 167 Ngô Quyền, P. Sơn Trà, TP. Đà Nẵng",
                lang_label: "Ngôn ngữ:",
                company_sub: "CÔNG TY TNHH VẬN TẢI & TM",
                nav_home: "Trang chủ",
                nav_domestic: "Vận tải Nội địa & Quốc tế",
                nav_container: "Container Việt - Lào",
                nav_customs: "Hải quan Việt - Lào",
                nav_fleet: "Đội xe",
                nav_quote: "Báo giá",
                nav_news: "Bài viết",
                nav_partners: "Đối tác",
                nav_contact: "Liên hệ",
                nav_domestic_short: "Nội địa & Quốc tế",
                nav_container_short: "Container Việt - Lào",
                nav_customs_short: "Hải quan Việt - Lào",
                b1_sub: "CÔNG TY TNHH VẬN TẢI VÀ THƯƠNG MẠI QUANG TRUNG HUY",
                b1_title: "CHUYÊN VẬN CHUYỂN HÀNG HOÁ TRONG NƯỚC & QUỐC TẾ - CONTAINER VIỆT NAM - LÀO",
                b1_desc: "Đội xe đầu kéo container hiện đại, vận tải hai chiều Việt - Lào an toàn, đúng tiến độ, chi phí tối ưu cho doanh nghiệp.",
                b2_sub: "DỊCH VỤ LOGISTICS & HẢI QUAN TRỌN GÓI",
                b2_title: "DỊCH VỤ THỦ TỤC HẢI QUAN TẠI CÁC CỬA KHẨU VIỆT - LÀO NHANH CHÓNG",
                b2_desc: "Khai báo hải quan xuất nhập khẩu, quá cảnh hàng hóa tại Lao Bảo, Cha Lo, Cầu Treo, Bờ Y, Nam Giang uy tín và chuyên nghiệp.",
                btn_get_quote: "Nhận báo giá ngay",
                btn_view_services: "Xem dịch vụ vận tải",
                core1_title: "Vận chuyển hàng hoá trong nước & quốc tế",
                core1_desc: "Nhận vận chuyển hàng ghép, hàng nguyên chuyến Bắc - Trung - Nam và liên vận quốc tế đi Lào an toàn, đúng lịch trình.",
                core2_title: "Vận chuyển hàng hoá bằng Container Việt Nam - Lào",
                core2_desc: "Đội xe đầu kéo container 20ft, 40ft, 45ft, moóc sàn, moóc lồng chuyên tuyến Đà Nẵng / Việt Nam đi Viêng Chăn, Savannakhet, Pakse.",
                core3_title: "Dịch vụ thủ tục hải quan tại các cửa khẩu Việt - Lào",
                core3_desc: "Tư vấn chứng từ xuất nhập khẩu, thông quan hàng thương mại, hàng dự án và hàng quá cảnh tại tất cả các cửa khẩu Việt - Lào.",
                sec_services_title: "DỊCH VỤ VẬN TẢI & HẢI QUAN CHUYÊN NGHIỆP",
                cat_tag_all: "Tất cả dịch vụ",
                cat_tag_vnlao: "Tuyến Việt - Lào",
                cat_tag_customs: "Hải quan cửa khẩu",
                srv1_title: "Vận chuyển hàng hoá bằng Container Việt Nam - Lào",
                srv1_desc: "Vận tải container 20ft, 40ft nguyên chuyến từ Đà Nẵng và các tỉnh Việt Nam sang Lào.",
                srv2_title: "Vận chuyển hàng hoá trong nước Bắc - Trung - Nam",
                srv2_desc: "Chuyên vận tải đường bộ nội địa nguyên xe hoặc ghép hàng từ Đà Nẵng đi toàn quốc.",
                srv3_title: "Dịch vụ thủ tục hải quan tại các cửa khẩu Việt - Lào",
                srv3_desc: "Khai báo hải quan trọn gói tại cửa khẩu Lao Bảo, Cha Lo, Cầu Treo, Nam Giang, Bờ Y.",
                srv4_title: "Vận chuyển hàng quá cảnh & Tạm nhập tái xuất Việt - Lào",
                srv4_desc: "Kéo container từ cảng Tiên Sa Đà Nẵng quá cảnh sang Lào và ngược lại nhanh gọn.",
                srv5_title: "Vận chuyển sắt thép, vật liệu xây dựng & Máy móc công trình",
                srv5_desc: "Phục vụ các dự án thủy điện, khoáng sản, xây dựng hạ tầng tại Việt Nam và Lào.",
                srv6_title: "Vận chuyển nông sản, khoáng sản từ Lào về Việt Nam",
                srv6_desc: "Vận chuyển hàng chiều về từ Lào về các cảng biển và khu công nghiệp tại Việt Nam.",
                srv7_title: "Giao nhận vận tải Container tại Cảng Đà Nẵng & Miền Trung",
                srv7_desc: "Kéo container xuất nhập khẩu từ Cảng Tiên Sa đi các khu công nghiệp và cửa khẩu.",
                srv8_title: "Thủ tục kiểm dịch, C/O & Ủy thác xuất nhập khẩu Việt - Lào",
                srv8_desc: "Hoàn thiện hồ sơ pháp lý, giấy phép liên vận, C/O mẫu S, kiểm dịch thực vật trọn gói.",
                btn_ask_quote: "Yêu cầu báo giá",
                sec_fleet_title: "HÌNH ẢNH ĐỘI XE VẬN TẢI THỰC TẾ QUANG TRUNG HUY",
                sec_fleet_sub: "100% Hình ảnh phương tiện vận chuyển thực tế của công ty",
                quote_heading: "ĐĂNG KÝ YÊU CẦU VẬN CHUYỂN & NHẬN BÁO GIÁ NHANH",
                quote_sub: "Quý khách vui lòng điền thông tin lộ trình, loại hàng hóa hoặc dịch vụ hải quan cần hỗ trợ. Bộ phận điều vận Quang Trung Huy sẽ phản hồi báo giá chi tiết trong vòng 15 phút.",
                hotline_247: "Hotline tư vấn & báo giá 24/7:",
                addr_main_label: "Địa chỉ trụ sở:",
                addr_office_label: "Văn phòng:",
                form_title: "FORM YÊU CẦU VÀ BÁO GIÁ VẬN TẢI",
                f_name: "Họ và tên / Tên công ty *",
                f_phone: "Số điện thoại liên hệ *",
                f_service: "Dịch vụ cần báo giá *",
                f_route: "Tuyến đường / Cửa khẩu dự kiến",
                f_detail: "Thông tin hàng hóa (Tên hàng, số lượng, trọng lượng, loại container...)",
                btn_submit_quote: "GỬI YÊU CẦU BÁO GIÁ NGAY",
                sec_news_title: "DANH MỤC BÀI VIẾT & TIN TỨC VẬN TẢI",
                sec_news_sub: "Kiến thức Logistics, thủ tục hải quan Việt - Lào & hoạt động công ty",
                news1_title: "Quy trình vận chuyển hàng hóa bằng Container từ Việt Nam sang Lào trọn gói",
                news1_desc: "Hướng dẫn chi tiết các bước đóng hàng, khai báo hải quan và vận tải đường bộ qua các cửa khẩu quốc tế Việt - Lào.",
                news2_title: "Hồ sơ cần chuẩn bị khi làm thủ tục hải quan tại các cửa khẩu Việt - Lào",
                news2_desc: "Tổng hợp danh mục chứng từ Invoice, Packing List, C/O Form S và thủ tục thông quan nhanh tại Lao Bảo, Nam Giang, Cha Lo.",
                news3_title: "Lịch trình và thời gian vận chuyển hàng từ Đà Nẵng đi Viêng Chăn, Pakse, Savannakhet",
                news3_desc: "Tối ưu chi phí cước vận tải hai chiều Việt Nam - Lào với đội xe đầu kéo container hoạt động liên tục mỗi ngày.",
                news4_title: "Giải pháp vận chuyển hàng quá cảnh và thiết bị dự án qua cảng Đà Nẵng đi Lào",
                news4_desc: "Quang Trung Huy cung cấp giải pháp khai thác hàng quá cảnh từ Cảng Tiên Sa đi thẳng đến chân công trình tại Lào.",
                sec_partners_title: "ĐỐI TÁC & KHÁCH HÀNG TIÊU BIỂU",
                sec_partners_sub: "Đồng hành cùng các cảng biển, hãng tàu và doanh nghiệp xuất nhập khẩu Việt - Lào",
                sec_connect_title: "KẾT NỐI FANPAGE & BẢN ĐỒ GOOGLE MAPS QUANG TRUNG HUY",
                map_box_title: "VỊ TRÍ TRỤ SỞ & VĂN PHÒNG TRÊN GOOGLE MAPS",
                footer_company: "CÔNG TY TNHH VẬN TẢI VÀ THƯƠNG MẠI QUANG TRUNG HUY",
                footer_about: "Đơn vị uy tín hàng đầu chuyên vận chuyển hàng hoá trong nước và quốc tế, vận chuyển hàng hoá bằng container Việt Nam - Lào và dịch vụ thủ tục hải quan trọn gói tại các cửa khẩu Việt - Lào.",
                footer_srv_head: "LĨNH VỰC HOẠT ĐỘNG",
                footer_contact_head: "THÔNG TIN LIÊN HỆ"
            },
            en: {
                top_addr: "10 Ho Huan Nghiep, Ngu Hanh Son Ward & 167 Ngo Quyen, Son Tra Ward, Da Nang City",
                lang_label: "Language:",
                company_sub: "TRANSPORT & TRADING CO., LTD",
                nav_home: "Home",
                nav_domestic: "Domestic & Int'l",
                nav_container: "VN - Laos Container",
                nav_customs: "VN - Laos Customs",
                nav_fleet: "Fleet",
                nav_quote: "Quote",
                nav_news: "Articles",
                nav_partners: "Partners",
                nav_contact: "Contact",
                nav_domestic_short: "Domestic & Int'l",
                nav_container_short: "VN-Laos Container",
                nav_customs_short: "VN-Laos Customs",
                b1_sub: "QUANG TRUNG HUY TRANSPORT & TRADING CO., LTD",
                b1_title: "DOMESTIC & INTERNATIONAL FREIGHT - VIETNAM - LAOS CONTAINER TRANSPORT",
                b1_desc: "Modern container tractor fleet providing safe, on-time two-way Vietnam - Laos cross-border transport at optimal cost.",
                b2_sub: "FULL-PACKAGE LOGISTICS & CUSTOMS SERVICES",
                b2_title: "FAST CUSTOMS CLEARANCE AT ALL VIETNAM - LAOS BORDER GATES",
                b2_desc: "Professional import-export and transit cargo customs declaration at Lao Bao, Cha Lo, Cau Treo, Bo Y, and Nam Giang.",
                btn_get_quote: "Get a Quote Now",
                btn_view_services: "View Services",
                core1_title: "Domestic & International Cargo Transport",
                core1_desc: "Reliable LTL and FTL road freight across North - Central - South Vietnam and cross-border transport to Laos.",
                core2_title: "Vietnam - Laos Container Freight Transport",
                core2_desc: "20ft, 40ft, 45ft containers, flatbed and bulk trailers from Da Nang / Vietnam to Vientiane, Savannakhet, and Pakse.",
                core3_title: "Customs Clearance at Vietnam - Laos Border Gates",
                core3_desc: "Import-export documentation, commercial cargo, project cargo, and transit customs clearance at all Vietnam - Laos borders.",
                sec_services_title: "PROFESSIONAL TRANSPORT & CUSTOMS SERVICES",
                cat_tag_all: "All Services",
                cat_tag_vnlao: "Vietnam - Laos Route",
                cat_tag_customs: "Border Customs",
                srv1_title: "Vietnam - Laos Container Cargo Transport",
                srv1_desc: "Full container load (20ft, 40ft) transport from Da Nang and Vietnamese provinces to Laos.",
                srv2_title: "Domestic North - Central - South Road Freight",
                srv2_desc: "Dedicated truckload and consolidated cargo from Da Nang to all provinces across Vietnam.",
                srv3_title: "Customs Clearance Services at Vietnam - Laos Borders",
                srv3_desc: "Full customs brokerage at Lao Bao, Cha Lo, Cau Treo, Nam Giang, and Bo Y border gates.",
                srv4_title: "Transit Cargo & Temporary Import / Re-export VN - Laos",
                srv4_desc: "Seamless container haulage from Tien Sa Port (Da Nang) in transit to Laos and vice versa.",
                srv5_title: "Steel, Construction Materials & Project Machinery Transport",
                srv5_desc: "Serving hydropower, mining, and infrastructure construction projects in Vietnam and Laos.",
                srv6_title: "Agricultural & Mineral Freight from Laos to Vietnam",
                srv6_desc: "Backhaul cargo transport from Laos to seaports and industrial zones in Vietnam.",
                srv7_title: "Container Trucking at Da Nang Port & Central Vietnam",
                srv7_desc: "Import-export container drayage from Tien Sa Port to industrial parks and border gates.",
                srv8_title: "Quarantine, C/O & Import-Export Entrustment VN - Laos",
                srv8_desc: "Complete legal documentation, cross-border permits, Form S C/O, and phytosanitary certificates.",
                btn_ask_quote: "Request Quote",
                sec_fleet_title: "QUANG TRUNG HUY REAL TRUCK & CONTAINER FLEET",
                sec_fleet_sub: "100% Real photos of our company's transport vehicles",
                quote_heading: "REQUEST TRANSPORT & RECEIVE A QUICK QUOTATION",
                quote_sub: "Please fill in your route, cargo details, or customs service needs. Our dispatch team will respond within 15 minutes.",
                hotline_247: "24/7 Consultation & Quote Hotline:",
                addr_main_label: "Head Office:",
                addr_office_label: "Branch Office:",
                form_title: "TRANSPORT QUOTATION REQUEST FORM",
                f_name: "Full Name / Company Name *",
                f_phone: "Phone Number *",
                f_service: "Service Required *",
                f_route: "Expected Route / Border Gate",
                f_detail: "Cargo Details (Commodity, quantity, weight, container size...)",
                btn_submit_quote: "SEND QUOTATION REQUEST NOW",
                sec_news_title: "LOGISTICS ARTICLES & TRANSPORT NEWS",
                sec_news_sub: "Vietnam - Laos customs procedures, logistics insights & company activities",
                news1_title: "Full Process of Container Cargo Transport from Vietnam to Laos",
                news1_desc: "Step-by-step guide on container stuffing, customs declaration, and cross-border trucking.",
                news2_title: "Required Documents for Customs Clearance at Vietnam - Laos Borders",
                news2_desc: "Checklist of Invoice, Packing List, C/O Form S, and fast clearance at Lao Bao, Nam Giang, Cha Lo.",
                news3_title: "Schedule & Transit Time from Da Nang to Vientiane, Pakse, Savannakhet",
                news3_desc: "Optimize two-way Vietnam - Laos freight rates with our daily container tractor fleet.",
                news4_title: "Transit Cargo & Project Equipment Solutions via Da Nang Port to Laos",
                news4_desc: "Quang Trung Huy delivers transit cargo directly from Tien Sa Port to project sites in Laos.",
                sec_partners_title: "OUR VALUED PARTNERS & CLIENTS",
                sec_partners_sub: "Partnering with seaports, shipping lines, and Vietnam - Laos import-export enterprises",
                sec_connect_title: "OFFICIAL FANPAGE & GOOGLE MAPS LOCATION",
                map_box_title: "HEADQUARTER & OFFICE LOCATION ON GOOGLE MAPS",
                footer_company: "QUANG TRUNG HUY TRANSPORT AND TRADING CO., LTD",
                footer_about: "Leading provider of domestic & international freight transport, Vietnam - Laos container haulage, and customs clearance at Vietnam - Laos border gates.",
                footer_srv_head: "CORE SERVICES",
                footer_contact_head: "CONTACT INFORMATION"
            },
            lo: {
                top_addr: "10 ໂຮ່ຮວນງຽບ, ເມືອງຫງູແຮ່ງເຊີນ & 167 ໂງກວຽນ, ເມືອງເຊີນຈ່າ, ນະຄອນດານັງ",
                lang_label: "ພາສາ:",
                company_sub: "ບໍລິສັດ ຂົນສົ່ງ & ການຄ້າ",
                nav_home: "ໜ້າຫຼັກ",
                nav_domestic: "ພາຍໃນ & ສາກົນ",
                nav_container: "ຄອນເທນເນີ ຫວຽດ-ລາວ",
                nav_customs: "ພາສີ ຫວຽດ-ລາວ",
                nav_fleet: "ທີມລົດ",
                nav_quote: "ລາຄາ",
                nav_news: "ບົດຄວາມ",
                nav_partners: "ຄູ່ຮ່ວມມື",
                nav_contact: "ຕິດຕໍ່",
                nav_domestic_short: "ພາຍໃນ & ສາກົນ",
                nav_container_short: "ຄອນເທນເນີ ຫວຽດ-ລາວ",
                nav_customs_short: "ພາສີ ຫວຽດ-ລາວ",
                b1_sub: "ບໍລິສັດ ຂົນສົ່ງ ແລະ ການຄ້າ ກວາງຈຸງຮຸຍ ຈຳກັດ",
                b1_title: "ບໍລິການຂົນສົ່ງສິນຄ້າພາຍໃນ & ສາກົນ - ຂົນສົ່ງຕູ້ຄອນເທນເນີ ຫວຽດນາມ - ລາວ",
                b1_desc: "ທີມລົດລາກຕູ້ຄອນເທນເນີທັນສະໄໝ ຂົນສົ່ງສອງສົ້ນ ຫວຽດນາມ - ລາວ ປອດໄພ, ຖືກເວລາ ແລະ ລາຄາประหยัด.",
                b2_sub: "ບໍລິການ ໂລຈິສຕິກ ແລະ ແຈ້ງພາສີຄົບວົງຈອນ",
                b2_title: "ບໍລິການແຈ້ງພາສີຢູ່ທຸກດ່ານຊາຍແດນ ຫວຽດນາມ - ລາວ ວ່ອງໄວ",
                b2_desc: "ແຈ້ງພາສີນຳເຂົ້າ-ສົ່ງອອກ ແລະ ສິນຄ້າຜ່ານແດນ ຢູ່ດ່ານລາວບາວ, ຈາໂລ, ເກົ່າແຈວ, ເບີ່ອີ, ນາມຢາງ.",
                btn_get_quote: "ຂໍໃບສະເໜີລາຄາທັນທີ",
                btn_view_services: "ເບິ່ງບໍລິການຂົນສົ່ງ",
                core1_title: "ຂົນສົ່ງສິນຄ້າພາຍໃນປະເທດ ແລະ ສາກົນ",
                core1_desc: "ຮັບຂົນສົ່ງສິນຄ້າເໝົາຄັນ ແລະ ສິນຄ້າລວມ ຈາກຫວຽດນາມໄປລາວ ປອດໄພ ແລະ ທັນເວລາ.",
                core2_title: "ຂົນສົ່ງສິນຄ້າດ້ວຍຕູ້ຄອນເທນເນີ ຫວຽດນາມ - ລາວ",
                core2_desc: "ລົດລາກຕູ້ຄອນເທນເນີ 20ft, 40ft, 45ft ຈາກດານັງ / ຫວຽດນາມ ໄປ ວຽງຈັນ, ສະຫວັນນະເຂດ, ປາກເຊ.",
                core3_title: "ບໍລິການແຈ້ງພາສີຢູ່ບັນດາດ່ານຊາຍແດນ ຫວຽດນາມ - ລາວ",
                core3_desc: "ໃຫ້ຄຳປຶກສາເອກະສານນຳເຂົ້າ-ສົ່ງອອກ, ແຈ້ງພາສີສິນຄ້າການຄ້າ, ສິນຄ້າໂຄງການ ແລະ ສິນຄ້າຜ່ານແດນ.",
                sec_services_title: "ບໍລິການຂົນສົ່ງ ແລະ ແຈ້ງພາສີມືອາຊີບ",
                cat_tag_all: "ບໍລິການທັງໝົດ",
                cat_tag_vnlao: "ສາຍທາງ ຫວຽດ-ລາວ",
                cat_tag_customs: "ພາສີດ່ານຊາຍແດນ",
                srv1_title: "ຂົນສົ່ງສິນຄ້າດ້ວຍຕູ້ຄອນເທນເນີ ຫວຽດນາມ - ລາວ",
                srv1_desc: "ຂົນສົ່ງຕູ້ຄອນເທນເນີ 20ft, 40ft ຈາກດານັງ ແລະ ແຂວງຕ່າງໆຂອງຫວຽດນາມ ໄປ ລາວ.",
                srv2_title: "ຂົນສົ່ງສິນຄ້າພາຍໃນປະເທດ ເໜືອ - ກາງ - ໃຕ້",
                srv2_desc: "ຂົນສົ່ງທາງບົກພາຍໃນປະເທດ ຈາກນະຄອນດານັງໄປທຸກແຂວງທົ່ວປະເທດຫວຽດນາມ.",
                srv3_title: "ບໍລິການແຈ້ງພາສີຢູ່ບັນດາດ່ານຊາຍແດນ ຫວຽດນາມ - ລາວ",
                srv3_desc: "ແຈ້ງພາສີຄົບວົງຈອນຢູ່ດ່ານລາວບາວ, ຈາໂລ, ເກົ່າແຈວ, ນາມຢາງ, ເບີ່ອີ.",
                srv4_title: "ຂົນສົ່ງສິນຄ້າຜ່ານແດນ (Transit) ຫວຽດນາມ - ລາວ",
                srv4_desc: "ລາກຕູ້ຄອນເທນເນີຈາກທ່າເຮືອຕຽນຊາ (ດານັງ) ຜ່ານແດນໄປລາວ ແລະ ขากลับວ່ອງໄວ.",
                srv5_title: "ຂົນສົ່ງເຫຼັກ, ວັດສະດຸກໍ່ສ້າງ ແລະ ເຄື່ອງຈັກໂຄງການ",
                srv5_desc: "ຮັບໃຊ້ໂຄງການໄຟຟ້າພະລັງນ້ຳ, ບໍ່ແຮ່ ແລະ ກໍ່ສ້າງພື້ນຖານໂຄງລ່າງຢູ່ຫວຽດນາມ ແລະ ລາວ.",
                srv6_title: "ຂົນສົ່ງຜົນຜະລິດກະສິກຳ ແລະ ແຮ່ທາດ ຈາກລາວມາຫວຽດນາມ",
                srv6_desc: "ຂົນສົ່ງສິນຄ້າຂາກັບຈາກລາວ ໄປຍັງທ່າເຮືອ ແລະ ເຂດອຸດສາຫະກຳຢູ່ຫວຽດນາມ.",
                srv7_title: "ບໍລິການລາກຕູ້ຄອນເທນເນີຢູ່ທ່າເຮືອດານັງ ແລະ ພາກກາງ",
                srv7_desc: "ລາກຕູ້ຄອນເທນເນີນຳເຂົ້າ-ສົ່ງອອກ ຈາກທ່າເຮືອຕຽນຊາ ໄປເຂດອຸດສາຫະກຳ ແລະ ດ່ານຊາຍແດນ.",
                srv8_title: "ບໍລິການກວດກາພືດ, ໃບຢັ້ງຢືນແຫຼ່ງກຳເນີດ C/O ຫວຽດ - ລາວ",
                srv8_desc: "ຈັດທຳເອກະສານກົດໝາຍ, ໃບອະນຸຍາດຂົນສົ່ງຂ້າມແດນ, C/O Form S ຄົບວົງຈອນ.",
                btn_ask_quote: "ຂໍໃບສະເໜີລາຄາ",
                sec_fleet_title: "ຮູບພາບທີມລົດຂົນສົ່ງຕົວຈິງ ກວາງຈຸງຮຸຍ",
                sec_fleet_sub: "ຮູບພາບລົດບັນທຸກ ແລະ ຕູ້ຄອນເທນເນີຕົວຈິງຂອງບໍລິສັດ 100%",
                quote_heading: "ລົງທະບຽນຂໍໃບສະເໜີລາຄາຂົນສົ່ງດ່ວນ",
                quote_sub: "ກະລຸນາປ້ອນຂໍ້ມູນເສັ້ນທາງ, ປະເພດສິນຄ້າ ຫຼື ບໍລິການພາສີທີ່ຕ້ອງການ. ທີມງານຈະຕິດຕໍ່ກັບພາຍໃນ 15 ນາທີ.",
                hotline_247: "ສາຍດ່ວນປຶກສາ & ສະເໜີລາຄາ 24/7:",
                addr_main_label: "ທີ່ຢູ່ສຳນັກງານໃຫຍ່:",
                addr_office_label: "ຫ້ອງການ:",
                form_title: "ແບບຟອມຂໍໃບສະເໜີລາຄາຂົນສົ່ງ",
                f_name: "ຊື່ ແລະ ນາມສະກຸນ / ຊື່ບໍລິສັດ *",
                f_phone: "ເບີໂທລະສັບຕິດຕໍ່ *",
                f_service: "ບໍລິການທີ່ຕ້ອງການ *",
                f_route: "ເສັ້ນທາງ / ດ່ານຊາຍແດນ",
                f_detail: "ລາຍລະອຽດສິນຄ້າ (ຊື່ສິນຄ້າ, ຈຳນວນ, ນ້ຳໜັກ, ຂະໜາດຕູ້ຄອນເທນເນີ...)",
                btn_submit_quote: "ສົ່ງຄຳຂໍໃບສະເໜີລາຄາທັນທີ",
                sec_news_title: "ໝວດໝູ່ບົດຄວາມ ແລະ ຂ່າວສານການຂົນສົ່ງ",
                sec_news_sub: "ຄວາມຮູ້ດ້ານໂລຈິສຕິກ, ລະບຽບການພາສີ ຫວຽດນາມ - ລາວ",
                news1_title: "ຂັ້ນຕອນການຂົນສົ່ງສິນຄ້າດ້ວຍຕູ້ຄອນເທນເນີ ຈາກຫວຽດນາມໄປລາວ ຄົບວົງຈອນ",
                news1_desc: "ຄຳແນະນຳລະອຽດກ່ຽວກັບການບັນຈຸສິນຄ້າ, ແຈ້ງພາສີ ແລະ ຂົນສົ່ງຜ່ານດ່ານສາກົນ ຫວຽດນາມ-ລາວ.",
                news2_title: "ເອກະສານທີ່ຕ້ອງກະກຽມເມື່ອແຈ້ງພາສີຢູ່ດ່ານຊາຍແດນ ຫວຽດນາມ - ລາວ",
                news2_desc: "ລວບລວມເອກະສານ Invoice, Packing List, C/O Form S ແລະ ຂັ້ນຕອນການຜ່ານດ່ານລາວບາວ, ນາມຢາງ, ຈາໂລ.",
                news3_title: "ຕາຕະລາງ ແລະ ເວລາຂົນສົ່ງສິນຄ້າຈາກດານັງໄປ ວຽງຈັນ, ປາກເຊ, ສະຫວັນນະເຂດ",
                news3_desc: "ປະหยัดຄ່າຂົນສົ່ງສອງສົ້ນ ຫວຽດນາມ - ລາວ ດ້ວຍທີມລົດລາກຄອນເທນເນີແລ່ນທຸກມື້.",
                news4_title: "ການຂົນສົ່ງສິນຄ້າຜ່ານແດນ ແລະ ອຸປະກອນໂຄງການຜ່ານທ່າເຮືອດານັງໄປລາວ",
                news4_desc: "ກວາງຈຸງຮຸຍ ສະໜອງການຂົນສົ່ງສິນຄ້າຜ່ານແດນຈາກທ່າເຮືອຕຽນຊາ ໄປເຖິງສະໜາມກໍ່ສ້າງຢູ່ລາວ.",
                sec_partners_title: "ຄູ່ຮ່ວມມື ແລະ ລູກຄ້າຂອງພວກເຮົາ",
                sec_partners_sub: "ຮ່ວມມືກັບທ່າເຮືອ, ສາຍເຮືອ ແລະ ວິສາຫະກິດນຳເຂົ້າ-ສົ່ງອອກ ຫວຽດນາມ - ລາວ",
                sec_connect_title: "ເຊື່ອມຕໍ່ FANPAGE & ແຜນທີ່ GOOGLE MAPS ກວາງຈຸງຮຸຍ",
                map_box_title: "ທີ່ຕັ້ງສຳນັກງານ ແລະ ຫ້ອງການເທິງ GOOGLE MAPS",
                footer_company: "ບໍລິສັດ ຂົນສົ່ງ ແລະ ການຄ້າ ກວາງຈຸງຮຸຍ ຈຳກັດ",
                footer_about: "ຜູ້ให้บริการຊັ້ນນຳດ້ານການຂົນສົ່ງສິນຄ້າພາຍໃນ ແລະ ສາກົນ, ຂົນສົ່ງຕູ້ຄອນເທນເນີ ຫວຽດນາມ - ລາວ ແລະ ບໍລິການແຈ້ງພາສີຢູ່ທຸກດ່ານຊາຍແດນ ຫວຽດນາມ - ລາວ.",
                footer_srv_head: "ຂະແໜງການບໍລິການ",
                footer_contact_head: "ຂໍ້ມູນຕິດຕໍ່"
            }
        };

        function setLanguage(lang) {
            const dict = translations[lang] || translations.vi;
            document.querySelectorAll('[data-i18n]').forEach(el => {
                const key = el.getAttribute('data-i18n');
                if (dict[key]) {
                    el.textContent = dict[key];
                }
            });

            // Cập nhật trạng thái nút ngôn ngữ
            ['vi', 'en', 'lo'].forEach(code => {
                const btn = document.getElementById('btn-lang-' + code);
                if (btn) {
                    if (code === lang) {
                        btn.className = 'px-2 py-0.5 rounded text-[11px] font-bold bg-brand-red text-white transition';
                    } else {
                        btn.className = 'px-2 py-0.5 rounded text-[11px] font-bold bg-blue-900/80 hover:bg-blue-800 text-slate-200 transition';
                    }
                }
            });
        }

        window.onload = function() {
            resetSlideTimer();
        };
    </script>
</body>
</html>
