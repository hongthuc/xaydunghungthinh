<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CÔNG TY TNHH THIẾT KẾ VÀ THI CÔNG NHÀ TRỌN GÓI HƯNG THỊNH | xaydunghungthinh.com</title>
    <meta name="description" content="Công ty TNHH Thiết Kế và Thi Công Nhà Trọn Gói Hưng Thịnh tại Đà Nẵng. Chuyên thiết kế kiến trúc, thi công phần thô, hoàn thiện, xây nhà trọn gói uy tín. Hotline: 0935.156.874.">

    <!-- Meta Thumbnail (Open Graph & Twitter Card) dùng Logo Công Ty khi chia sẻ link -->
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="Xây Dựng Hưng Thịnh - xaydunghungthinh.com">
    <meta property="og:title" content="CÔNG TY TNHH THIẾT KẾ VÀ THI CÔNG NHÀ TRỌN GÓI HƯNG THỊNH">
    <meta property="og:description" content="Thiết kế kiến trúc, thi công phần thô, hoàn thiện và xây nhà trọn gói chuyên nghiệp tại Đà Nẵng. Địa chỉ: 138 Lê Đại Hành, Cẩm Lệ, TP Đà Nẵng. Hotline: 0935.156.874.">
    <meta property="og:url" content="https://xaydunghungthinh.com">
    <meta property="og:image" content="https://xaydunghungthinh.com/assets/logo-hung-thinh-og.png">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta property="og:image:alt" content="Logo Công Ty TNHH Thiết Kế Và Thi Công Nhà Trọn Gói Hưng Thịnh">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH THIẾT KẾ VÀ THI CÔNG NHÀ TRỌN GÓI HƯNG THỊNH">
    <meta name="twitter:description" content="Xây nhà trọn gói, thiết kế kiến trúc và thi công chuyên nghiệp tại Đà Nẵng.">
    <meta name="twitter:image" content="https://xaydunghungthinh.com/assets/logo-hung-thinh-og.png">

    <!-- Favicon SVG gọn nhẹ theo Logo Hưng Thịnh -->
    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='12' fill='%230B2C5D'/%3E%3Cpath d='M12 30L32 13L52 30H45V50H36V36H28V50H19V30H12Z' fill='%23C8922A'/%3E%3C/svg%3E">

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Font Inter & Font Awesome Icons -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">

    <!-- Cấu hình màu sắc Tailwind đồng bộ theo Logo Hưng Thịnh -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            navy: '#0B2C5D',      // Màu xanh chủ đạo từ logo
                            navyDark: '#071E40',  // Xanh đậm cho footer & hover
                            navyLight: '#164385', // Xanh nhấn
                            gold: '#C8922A',      // Màu vàng đồng kiến trúc từ logo
                            goldLight: '#DFA93D', // Vàng sáng khi hover
                            surface: '#F6F8FB',   // Nền section nhẹ kiểu Flatsome
                            border: '#E5EAF2',    // Viền tinh tế
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền ngang và lệch sang phải trên mọi thiết bị */
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
            color: #1E293B;
            background-color: #FFFFFF;
            scroll-behavior: smooth;
        }

        /* Chiều ngang giao diện trên máy tính bằng đúng 95% kích thước màn hình */
        .flatsome-container {
            width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 640px) {
            .flatsome-container {
                padding-left: 16px;
                padding-right: 16px;
            }
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Kiểu tiêu đề Section chuẩn Flatsome UX Builder */
        .section-heading {
            position: relative;
            display: inline-block;
            padding-bottom: 10px;
        }
        .section-heading::after {
            content: '';
            position: absolute;
            left: 50%;
            bottom: 0;
            transform: translateX(-50%);
            width: 56px;
            height: 3px;
            background-color: #C8922A;
            border-radius: 2px;
        }
        .section-heading-left::after {
            left: 0;
            transform: none;
        }

        /* Dropdown menu chuẩn Flatsome */
        .nav-dropdown {
            opacity: 0;
            visibility: hidden;
            transform: translateY(8px);
            transition: all 0.2s ease;
        }
        .nav-item:hover .nav-dropdown {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        /* Đảm bảo 2 ảnh banner luôn có kích thước bằng nhau tuyệt đối và chữ không bao giờ bị cắt */
        .hero-slider-grid {
            display: grid;
            grid-template-columns: 1fr;
            width: 100%;
            position: relative;
            overflow: hidden;
        }
        .hero-slide-item {
            grid-area: 1 / 1;
            transition: opacity 0.65s ease-in-out, visibility 0.65s ease-in-out;
        }
        .hero-slide-active {
            opacity: 1;
            visibility: visible;
            z-index: 10;
        }
        .hero-slide-inactive {
            opacity: 0;
            visibility: hidden;
            z-index: 1;
            pointer-events: none;
        }

        /* Ẩn thanh cuộn cho dải danh mục mobile nhưng vẫn vuốt mượt */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }

        /* Hiệu ứng nhịp nhẹ cho nút hotline nổi */
        @keyframes softPulse {
            0% { box-shadow: 0 0 0 0 rgba(200, 146, 42, 0.55); }
            70% { box-shadow: 0 0 0 12px rgba(200, 146, 42, 0); }
            100% { box-shadow: 0 0 0 0 rgba(200, 146, 42, 0); }
        }
        .pulse-hotline {
            animation: softPulse 2.2s infinite;
        }

        /* Khoảng đệm dưới cùng cho mobile để không bị thanh liên hệ che nội dung */
        @media (max-width: 639px) {
            body {
                padding-bottom: 62px;
            }
        }
    </style>
</head>
<body class="bg-white text-slate-800 antialiased">

    <!-- ========================================================= -->
    <!-- 1. TOP BAR (Thông tin liên hệ gọn kiểu Flatsome)          -->
    <!-- ========================================================= -->
    <div class="bg-brand-navy text-white text-[11px] sm:text-xs py-2 border-b border-white/10">
        <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-3 sm:gap-5 flex-wrap">
                <a href="tel:0935156874" class="flex items-center gap-1.5 hover:text-brand-goldLight transition whitespace-nowrap">
                    <i class="fa-solid fa-phone text-brand-gold"></i>
                    <span>0935.156.874</span>
                </a>
                <span class="hidden sm:inline text-white/30">|</span>
                <span class="hidden md:flex items-center gap-1.5 text-slate-200 whitespace-nowrap">
                    <i class="fa-solid fa-location-dot text-brand-gold"></i>
                    <span>138 Lê Đại Hành, Phường Cẩm Lệ, TP Đà Nẵng</span>
                </span>
            </div>
            <div class="flex items-center gap-3 text-slate-200">
                <span class="hidden sm:inline whitespace-nowrap">xaydunghungthinh.com</span>
                <a href="https://facebook.com" target="_blank" rel="noopener" aria-label="Facebook Hưng Thịnh" class="hover:text-brand-goldLight transition">
                    <i class="fa-brands fa-facebook-f"></i>
                </a>
                <a href="https://zalo.me/0935156874" target="_blank" rel="noopener" aria-label="Zalo Hưng Thịnh" class="hover:text-brand-goldLight transition font-bold text-[11px]">
                    Zalo
                </a>
            </div>
        </div>
    </div>

    <!-- ========================================================= -->
    <!-- 2. HEADER CHÍNH (Logo gọn nhỏ + Menu 1 hàng, KHÔNG nút gọi)-->
    <!-- ========================================================= -->
    <header class="sticky top-0 z-40 bg-white/95 backdrop-blur-md border-b border-brand-border shadow-sm">
        <div class="flatsome-container flex items-center justify-between py-2.5 lg:py-3 gap-3">

            <!-- Logo Công Ty Chuyên Nghiệp (Thiết kế gọn nhỏ, sắc nét) -->
            <a href="#trang-chu" class="flex items-center gap-2 shrink-0 group" aria-label="Trang chủ Xây Dựng Hưng Thịnh">
                <svg class="w-9 h-9 sm:w-10 sm:h-10 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <rect width="64" height="64" rx="10" fill="#0B2C5D"/>
                    <!-- Khung mái nhà và trụ kiến trúc cách điệu chữ H & T -->
                    <path d="M11 29L32 12L53 29" stroke="#C8922A" stroke-width="4.2" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M19 28V50" stroke="#FFFFFF" stroke-width="4.5" stroke-linecap="round"/>
                    <path d="M32 24V50" stroke="#C8922A" stroke-width="4.5" stroke-linecap="round"/>
                    <path d="M45 28V50" stroke="#FFFFFF" stroke-width="4.5" stroke-linecap="round"/>
                    <path d="M19 38H32" stroke="#FFFFFF" stroke-width="4" stroke-linecap="round"/>
                    <path d="M36 27H49" stroke="#C8922A" stroke-width="3.6" stroke-linecap="round"/>
                </svg>
                <div class="leading-tight">
                    <div class="text-sm sm:text-[15px] font-extrabold tracking-tight text-brand-navy group-hover:text-brand-gold transition whitespace-nowrap">
                        HƯNG THỊNH
                    </div>
                    <div class="text-[9px] sm:text-[10px] font-semibold uppercase tracking-wider text-brand-gold whitespace-nowrap">
                        Thiết Kế &amp; Xây Nhà Trọn Gói
                    </div>
                </div>
            </a>

            <!-- Menu Máy Tính: Chữ nhỏ gọn, viết liền trên 1 hàng, không xuống dòng tên danh mục -->
            <nav class="hidden lg:flex items-center justify-end flex-wrap gap-x-3 xl:gap-x-5 gap-y-1.5" aria-label="Menu chính">
                <a href="#trang-chu" class="text-[12px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-brand-navy hover:text-brand-gold transition whitespace-nowrap py-1">
                    Trang chủ
                </a>
                <a href="#gioi-thieu" class="text-[12px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-slate-700 hover:text-brand-gold transition whitespace-nowrap py-1">
                    Giới thiệu
                </a>

                <!-- Dropdown: Công trình thực tế (theo web mẫu tintruongthinh.com) -->
                <div class="relative nav-item">
                    <a href="#cong-trinh-thuc-te" class="flex items-center gap-1 text-[12px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-slate-700 hover:text-brand-gold transition whitespace-nowrap py-1">
                        <span>Công trình thực tế</span>
                        <i class="fa-solid fa-chevron-down text-[9px]"></i>
                    </a>
                    <div class="nav-dropdown absolute left-0 top-full pt-2 w-60 z-50">
                        <div class="bg-white border border-brand-border rounded-lg shadow-lg py-2">
                            <a href="#cong-trinh-thuc-te" onclick="filterWorks('khach-san')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-surface hover:text-brand-navy transition whitespace-nowrap">Khách sạn – Căn hộ – Phòng trọ</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterWorks('biet-thu')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-surface hover:text-brand-navy transition whitespace-nowrap">Biệt thự</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterWorks('nha-pho')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-surface hover:text-brand-navy transition whitespace-nowrap">Nhà phố</a>
                            <a href="#cong-trinh-thuc-te" onclick="filterWorks('van-phong')" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-surface hover:text-brand-navy transition whitespace-nowrap">Văn phòng</a>
                        </div>
                    </div>
                </div>

                <!-- Dropdown: Lĩnh vực hoạt động -->
                <div class="relative nav-item">
                    <a href="#linh-vuc-hoat-dong" class="flex items-center gap-1 text-[12px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-slate-700 hover:text-brand-gold transition whitespace-nowrap py-1">
                        <span>Lĩnh vực hoạt động</span>
                        <i class="fa-solid fa-chevron-down text-[9px]"></i>
                    </a>
                    <div class="nav-dropdown absolute left-0 top-full pt-2 w-56 z-50">
                        <div class="bg-white border border-brand-border rounded-lg shadow-lg py-2">
                            <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-surface hover:text-brand-navy transition whitespace-nowrap">Thiết kế Kiến trúc – Nội thất</a>
                            <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-surface hover:text-brand-navy transition whitespace-nowrap">Thi công phần thô</a>
                            <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-surface hover:text-brand-navy transition whitespace-nowrap">Thi công hoàn thiện</a>
                            <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-surface hover:text-brand-navy transition whitespace-nowrap">Thi công nội thất</a>
                        </div>
                    </div>
                </div>

                <!-- Dropdown: Mẫu thiết kế -->
                <div class="relative nav-item">
                    <a href="#du-an-da-nang" class="flex items-center gap-1 text-[12px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-slate-700 hover:text-brand-gold transition whitespace-nowrap py-1">
                        <span>Dự án Đà Nẵng</span>
                        <i class="fa-solid fa-chevron-down text-[9px]"></i>
                    </a>
                    <div class="nav-dropdown absolute left-0 top-full pt-2 w-52 z-50">
                        <div class="bg-white border border-brand-border rounded-lg shadow-lg py-2">
                            <a href="#du-an-da-nang" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-surface hover:text-brand-navy transition whitespace-nowrap">Mẫu thiết kế nhà phố</a>
                            <a href="#du-an-da-nang" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-surface hover:text-brand-navy transition whitespace-nowrap">Mẫu thiết kế nội thất</a>
                            <a href="#du-an-da-nang" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-surface hover:text-brand-navy transition whitespace-nowrap">Dự án trọn gói Đà Nẵng</a>
                        </div>
                    </div>
                </div>

                <!-- Dropdown: Báo giá -->
                <div class="relative nav-item">
                    <a href="#bao-gia" class="flex items-center gap-1 text-[12px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-slate-700 hover:text-brand-gold transition whitespace-nowrap py-1">
                        <span>Báo giá</span>
                        <i class="fa-solid fa-chevron-down text-[9px]"></i>
                    </a>
                    <div class="nav-dropdown absolute right-0 top-full pt-2 w-56 z-50">
                        <div class="bg-white border border-brand-border rounded-lg shadow-lg py-2">
                            <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-surface hover:text-brand-navy transition whitespace-nowrap">Báo giá thiết kế kiến trúc</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-surface hover:text-brand-navy transition whitespace-nowrap">Báo giá thi công phần thô</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-surface hover:text-brand-navy transition whitespace-nowrap">Báo giá thi công hoàn thiện</a>
                            <a href="#bao-gia" class="block px-4 py-2 text-xs font-medium text-slate-700 hover:bg-brand-surface hover:text-brand-navy transition whitespace-nowrap">Báo giá thi công trọn gói</a>
                        </div>
                    </div>
                </div>

                <a href="#doi-tac" class="text-[12px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-slate-700 hover:text-brand-gold transition whitespace-nowrap py-1">
                    Đối tác
                </a>
                <a href="#tin-tuc" class="text-[12px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-slate-700 hover:text-brand-gold transition whitespace-nowrap py-1">
                    Tin tức
                </a>
                <a href="#lien-he" class="text-[12px] xl:text-[12.5px] font-semibold uppercase tracking-tight text-slate-700 hover:text-brand-gold transition whitespace-nowrap py-1">
                    Liên hệ
                </a>
            </nav>

            <!-- Nút mở Menu Mobile (Không đặt nút Gọi Ngay trên header để tránh tràn viền) -->
            <button id="mobileMenuBtn" type="button" aria-label="Mở menu điều hướng" class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-brand-border text-brand-navy hover:bg-brand-surface transition">
                <i class="fa-solid fa-bars text-lg"></i>
            </button>
        </div>

        <!-- Menu Di Động Dạng Ngăn Kéo Gọn Gàng -->
        <div id="mobileMenuPanel" class="hidden lg:hidden bg-white border-t border-brand-border shadow-md">
            <div class="flatsome-container py-3 flex flex-col divide-y divide-slate-100 text-sm font-semibold text-slate-700">
                <a href="#trang-chu" class="py-2.5 text-brand-navy hover:text-brand-gold mobile-link">Trang chủ</a>
                <a href="#gioi-thieu" class="py-2.5 hover:text-brand-gold mobile-link">Giới thiệu</a>
                <a href="#linh-vuc-hoat-dong" class="py-2.5 hover:text-brand-gold mobile-link">Lĩnh vực hoạt động</a>
                <a href="#cong-trinh-thuc-te" class="py-2.5 hover:text-brand-gold mobile-link">Công trình thực tế</a>
                <a href="#du-an-da-nang" class="py-2.5 hover:text-brand-gold mobile-link">Dự án tại Đà Nẵng</a>
                <a href="#bao-gia" class="py-2.5 hover:text-brand-gold mobile-link">Báo giá &amp; Tư vấn</a>
                <a href="#doi-tac" class="py-2.5 hover:text-brand-gold mobile-link">Đối tác</a>
                <a href="#tin-tuc" class="py-2.5 hover:text-brand-gold mobile-link">Tin tức &amp; Bài viết</a>
                <a href="#lien-he" class="py-2.5 hover:text-brand-gold mobile-link">Liên hệ &amp; Bản đồ</a>
            </div>
        </div>
    </header>

    <!-- ========================================================= -->
    <!-- 3. 2 ẢNH BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU             -->
    <!-- Chữ nằm trọn bên trong, cách xa viền ảnh, không bị thiếu  -->
    <!-- ========================================================= -->
    <section id="trang-chu" class="w-full bg-brand-navyDark">
        <div class="flatsome-container py-3 sm:py-4">
            <div class="hero-slider-grid rounded-xl shadow-lg bg-brand-navyDark" id="heroSlider">

                <!-- BANNER 1 -->
                <div class="hero-slide-item hero-slide-active relative w-full min-h-[270px] sm:min-h-[370px] lg:min-h-[450px] flex items-center">
                    <img src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1600"
                         data-drive-id="13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
                         alt="Thiết kế và thi công nhà trọn gói Hưng Thịnh Đà Nẵng"
                         class="absolute inset-0 w-full h-full object-cover object-center"
                         onerror="handleDriveImageError(this, 'Xay+Dung+Hung+Thinh+Da+Nang')">
                    <!-- Lớp phủ tối tạo độ tương phản chữ rõ ràng -->
                    <div class="absolute inset-0 bg-gradient-to-r from-brand-navyDark/90 via-brand-navy/75 to-brand-navyDark/55"></div>

                    <!-- Khối chữ có khoảng đệm an toàn rất rộng để cách xa 4 viền banner trên cả mobile và máy tính -->
                    <div class="relative z-10 w-full px-10 sm:px-16 md:px-20 lg:px-24 py-10 sm:py-14 md:py-16">
                        <div class="max-w-2xl">
                            <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-widest text-brand-goldLight mb-2">
                                CÔNG TY TNHH THIẾT KẾ &amp; THI CÔNG NHÀ TRỌN GÓI HƯNG THỊNH
                            </p>
                            <h1 class="text-lg sm:text-2xl md:text-3xl lg:text-4xl font-extrabold text-white leading-snug mb-3">
                                KIẾN TẠO TỔ ẤM BỀN VỮNG – CHÌA KHÓA TRAO TAY TẠI ĐÀ NẴNG
                            </h1>
                            <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed mb-5">
                                Thiết kế kiến trúc chuẩn công năng, thi công phần thô và hoàn thiện trọn gói đúng tiến độ, minh bạch vật tư, bảo hành kết cấu dài hạn.
                            </p>
                            <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
                                <a href="#bao-gia" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldLight text-white font-semibold text-xs sm:text-sm transition shadow">
                                    Nhận báo giá trọn gói
                                </a>
                                <a href="#cong-trinh-thuc-te" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/40 font-semibold text-xs sm:text-sm transition">
                                    Xem công trình thực tế
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- BANNER 2 -->
                <div class="hero-slide-item hero-slide-inactive relative w-full min-h-[270px] sm:min-h-[370px] lg:min-h-[450px] flex items-center">
                    <img src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1600"
                         data-drive-id="157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
                         alt="Thi công biệt thự nhà phố căn hộ tại Đà Nẵng - Hưng Thịnh"
                         class="absolute inset-0 w-full h-full object-cover object-center"
                         onerror="handleDriveImageError(this, 'Du+An+Thi+Cong+Tai+Da+Nang')">
                    <div class="absolute inset-0 bg-gradient-to-r from-brand-navyDark/90 via-brand-navy/75 to-brand-navyDark/55"></div>

                    <div class="relative z-10 w-full px-10 sm:px-16 md:px-20 lg:px-24 py-10 sm:py-14 md:py-16">
                        <div class="max-w-2xl">
                            <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-widest text-brand-goldLight mb-2">
                                HƠN 10 NĂM KINH NGHIỆM XÂY DỰNG DÂN DỤNG
                            </p>
                            <h2 class="text-lg sm:text-2xl md:text-3xl lg:text-4xl font-extrabold text-white leading-snug mb-3">
                                THI CÔNG NHÀ PHỐ – BIỆT THỰ – KHÁCH SẠN – CĂN HỘ CHUẨN KỸ THUẬT
                            </h2>
                            <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed mb-5">
                                Đội ngũ kiến trúc sư, kỹ sư giám sát trực tiếp tại công trình. Cam kết không phát sinh chi phí ngoài hợp đồng, hỗ trợ trọn gói hồ sơ xin phép xây dựng.
                            </p>
                            <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
                                <a href="#du-an-da-nang" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldLight text-white font-semibold text-xs sm:text-sm transition shadow">
                                    Khám phá dự án Đà Nẵng
                                </a>
                                <a href="#bao-gia" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/40 font-semibold text-xs sm:text-sm transition">
                                    Tư vấn miễn phí 24/7
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng 2 bên gọn nhỏ nằm sát mép ngoài vùng chữ -->
                <button type="button" onclick="prevSlide()" aria-label="Banner trước" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-brand-gold text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                </button>
                <button type="button" onclick="nextSlide()" aria-label="Banner tiếp theo" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-brand-gold text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                </button>

                <!-- Dấu chấm chuyển 2 banner -->
                <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button type="button" onclick="goToSlide(0)" id="dot-0" aria-label="Xem banner 1" class="w-6 h-2 rounded-full bg-brand-gold transition-all"></button>
                    <button type="button" onclick="goToSlide(1)" id="dot-1" aria-label="Xem banner 2" class="w-2.5 h-2 rounded-full bg-white/60 hover:bg-white transition-all"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ========================================================= -->
    <!-- 4. LĨNH VỰC HOẠT ĐỘNG / DỊCH VỤ TIÊU BIỂU (Giống web mẫu) -->
    <!-- ========================================================= -->
    <section id="linh-vuc-hoat-dong" class="py-10 sm:py-14 bg-white">
        <div class="flatsome-container">
            <div class="text-center mb-8">
                <h2 class="section-heading text-lg sm:text-2xl font-extrabold text-brand-navy uppercase tracking-tight">
                    Dịch Vụ Tiêu Biểu
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
                    Giải pháp đồng bộ từ khâu lên ý tưởng kiến trúc, thi công phần thô vững chắc đến hoàn thiện nội thất chìa khóa trao tay.
                </p>
            </div>

            <!-- 4 hạng mục dịch vụ chuẩn Flatsome (2 cột mobile, 4 cột desktop) -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <a href="#bao-gia" class="group block rounded-xl overflow-hidden border border-brand-border bg-white shadow-sm hover:shadow-md transition">
                    <div class="aspect-[4/3] overflow-hidden bg-slate-100">
                        <img src="https://drive.google.com/thumbnail?id=1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_&sz=w800"
                             data-drive-id="1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_"
                             alt="Thiết kế Kiến trúc - Nội thất"
                             class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
                             onerror="handleDriveImageError(this, 'Thiet+Ke+Kien+Truc')">
                    </div>
                    <div class="p-3 sm:p-4 text-center">
                        <h3 class="text-[12.5px] sm:text-sm font-bold text-brand-navy group-hover:text-brand-gold transition leading-snug break-words">
                            Thiết Kế Kiến Trúc – Nội Thất
                        </h3>
                        <p class="text-[11px] sm:text-xs text-slate-500 mt-1.5 leading-relaxed">
                            Hồ sơ 3D sắc nét, tối ưu công năng &amp; phong thủy gia chủ.
                        </p>
                    </div>
                </a>

                <a href="#bao-gia" class="group block rounded-xl overflow-hidden border border-brand-border bg-white shadow-sm hover:shadow-md transition">
                    <div class="aspect-[4/3] overflow-hidden bg-slate-100">
                        <img src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w800"
                             data-drive-id="1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR"
                             alt="Thi công phần thô chuẩn kỹ thuật"
                             class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
                             onerror="handleDriveImageError(this, 'Thi+Cong+Phan+Tho')">
                    </div>
                    <div class="p-3 sm:p-4 text-center">
                        <h3 class="text-[12.5px] sm:text-sm font-bold text-brand-navy group-hover:text-brand-gold transition leading-snug break-words">
                            Thi Công Phần Thô
                        </h3>
                        <p class="text-[11px] sm:text-xs text-slate-500 mt-1.5 leading-relaxed">
                            Kết cấu bê tông cốt thép đạt chuẩn, giám sát chặt từng hạng mục.
                        </p>
                    </div>
                </a>

                <a href="#bao-gia" class="group block rounded-xl overflow-hidden border border-brand-border bg-white shadow-sm hover:shadow-md transition">
                    <div class="aspect-[4/3] overflow-hidden bg-slate-100">
                        <img src="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w800"
                             data-drive-id="1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv"
                             alt="Thi công hoàn thiện nhà trọn gói"
                             class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
                             onerror="handleDriveImageError(this, 'Thi+Cong+Hoan+Thien')">
                    </div>
                    <div class="p-3 sm:p-4 text-center">
                        <h3 class="text-[12.5px] sm:text-sm font-bold text-brand-navy group-hover:text-brand-gold transition leading-snug break-words">
                            Thi Công Hoàn Thiện Trọn Gói
                        </h3>
                        <p class="text-[11px] sm:text-xs text-slate-500 mt-1.5 leading-relaxed">
                            Chìa khóa trao tay, vật tư chính hãng, không phát sinh chi phí.
                        </p>
                    </div>
                </a>

                <a href="#bao-gia" class="group block rounded-xl overflow-hidden border border-brand-border bg-white shadow-sm hover:shadow-md transition">
                    <div class="aspect-[4/3] overflow-hidden bg-slate-100">
                        <img src="https://drive.google.com/thumbnail?id=1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t&sz=w800"
                             data-drive-id="1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t"
                             alt="Thi công nội thất nhà phố biệt thự"
                             class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
                             onerror="handleDriveImageError(this, 'Thi+Cong+Noi+That')">
                    </div>
                    <div class="p-3 sm:p-4 text-center">
                        <h3 class="text-[12.5px] sm:text-sm font-bold text-brand-navy group-hover:text-brand-gold transition leading-snug break-words">
                            Thi Công Nội Thất
                        </h3>
                        <p class="text-[11px] sm:text-xs text-slate-500 mt-1.5 leading-relaxed">
                            Đồng bộ không gian sống sang trọng, tinh tế và bền đẹp lâu dài.
                        </p>
                    </div>
                </a>
            </div>
        </div>
    </section>

    <!-- ========================================================= -->
    <!-- 5. GIỚI THIỆU CÔNG TY & THẾ MẠNH CỦA CHÚNG TÔI            -->
    <!-- ========================================================= -->
    <section id="gioi-thieu" class="py-10 sm:py-14 bg-brand-surface border-y border-brand-border">
        <div class="flatsome-container">
            <!-- Phần giới thiệu 2 cột đơn giản dễ dựng lại trên UX Builder -->
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center mb-12">
                <div class="lg:col-span-5">
                    <div class="rounded-xl overflow-hidden shadow-md border border-brand-border bg-white">
                        <img src="https://drive.google.com/thumbnail?id=1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_&sz=w1000"
                             data-drive-id="1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_"
                             alt="Đội ngũ thi công Công ty TNHH Thiết Kế và Thi Công Nhà Trọn Gói Hưng Thịnh"
                             class="w-full aspect-[4/3] object-cover"
                             onerror="handleDriveImageError(this, 'Cong+Ty+Xay+Dung+Hung+Thinh')">
                    </div>
                </div>
                <div class="lg:col-span-7">
                    <h2 class="section-heading section-heading-left text-lg sm:text-2xl font-extrabold text-brand-navy uppercase leading-snug">
                        CÔNG TY TNHH THIẾT KẾ VÀ THI CÔNG NHÀ TRỌN GÓI HƯNG THỊNH
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed mt-4">
                        <strong>Hưng Thịnh</strong> chuyên Thiết kế – Xây dựng – Nội thất các công trình <strong>Nhà phố, Biệt thự, Khách sạn, Căn hộ cho thuê, Văn phòng</strong> tại khu vực Đà Nẵng và Quảng Nam. Với tiêu chí <em>“Nhà ở Gia đình – Tiêu chuẩn Công trình”</em>, chúng tôi luôn đặt cái “Tâm” trong nghề lên hàng đầu để mỗi công trình bàn giao đều đạt chuẩn <strong>An toàn – Chất lượng – Đúng tiến độ – Tối ưu chi phí</strong>.
                    </p>
                    <p class="text-xs sm:text-sm text-slate-600 leading-relaxed mt-3">
                        Đội ngũ kiến trúc sư, kỹ sư kết cấu giàu kinh nghiệm kết hợp cùng thợ lành nghề trực tiếp thi công giúp gia chủ hoàn toàn an tâm theo dõi từng giai đoạn công trình từ phần móng đến hoàn thiện chìa khóa trao tay.
                    </p>
                    <div class="grid grid-cols-3 gap-3 mt-6 pt-5 border-t border-brand-border">
                        <div>
                            <div class="text-xl sm:text-2xl font-extrabold text-brand-navy">10+</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Năm kinh nghiệm</div>
                        </div>
                        <div>
                            <div class="text-xl sm:text-2xl font-extrabold text-brand-gold">150+</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Công trình bàn giao</div>
                        </div>
                        <div>
                            <div class="text-xl sm:text-2xl font-extrabold text-brand-navy">05 Năm</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Bảo hành kết cấu</div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- 6 Thế mạnh của chúng tôi (Cấu trúc 3x2 giống tintruongthinh.com) -->
            <div class="text-center mb-7">
                <h3 class="section-heading text-base sm:text-xl font-extrabold text-brand-navy uppercase">
                    Thế Mạnh Của Chúng Tôi
                </h3>
            </div>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
                <div class="bg-white rounded-xl p-5 border border-brand-border shadow-sm">
                    <div class="w-10 h-10 rounded-lg bg-brand-navy text-brand-goldLight flex items-center justify-center mb-3">
                        <i class="fa-solid fa-helmet-safety"></i>
                    </div>
                    <h4 class="text-sm font-bold text-brand-navy mb-1.5">Đội ngũ kiến trúc sư, kỹ sư chuyên nghiệp</h4>
                    <p class="text-xs text-slate-600 leading-relaxed">Kiến trúc sư sáng tạo kết hợp kỹ sư giám sát giàu kinh nghiệm và đội thợ xây dựng lành nghề lâu năm.</p>
                </div>

                <div class="bg-white rounded-xl p-5 border border-brand-border shadow-sm">
                    <div class="w-10 h-10 rounded-lg bg-brand-navy text-brand-goldLight flex items-center justify-center mb-3">
                        <i class="fa-solid fa-compass-drafting"></i>
                    </div>
                    <h4 class="text-sm font-bold text-brand-navy mb-1.5">Cập nhật xu hướng thiết kế hiện đại</h4>
                    <p class="text-xs text-slate-600 leading-relaxed">Ứng dụng giải pháp kiến trúc thông thoáng, vật liệu bền vững phù hợp khí hậu nắng gió miền Trung – Đà Nẵng.</p>
                </div>

                <div class="bg-white rounded-xl p-5 border border-brand-border shadow-sm">
                    <div class="w-10 h-10 rounded-lg bg-brand-navy text-brand-goldLight flex items-center justify-center mb-3">
                        <i class="fa-solid fa-clipboard-check"></i>
                    </div>
                    <h4 class="text-sm font-bold text-brand-navy mb-1.5">Giám sát tiến độ chuẩn xác</h4>
                    <p class="text-xs text-slate-600 leading-relaxed">Cập nhật hình ảnh công trường thường xuyên theo từng giai đoạn, đảm bảo bàn giao nhà đúng thời hạn cam kết.</p>
                </div>

                <div class="bg-white rounded-xl p-5 border border-brand-border shadow-sm">
                    <div class="w-10 h-10 rounded-lg bg-brand-navy text-brand-goldLight flex items-center justify-center mb-3">
                        <i class="fa-solid fa-shield-halved"></i>
                    </div>
                    <h4 class="text-sm font-bold text-brand-navy mb-1.5">Bảo hành công trình lâu dài</h4>
                    <p class="text-xs text-slate-600 leading-relaxed">Bảo hành kết cấu 5 năm, bảo trì hoàn thiện nhanh chóng, luôn đồng hành hỗ trợ khách hàng tận tâm sau bàn giao.</p>
                </div>

                <div class="bg-white rounded-xl p-5 border border-brand-border shadow-sm">
                    <div class="w-10 h-10 rounded-lg bg-brand-navy text-brand-goldLight flex items-center justify-center mb-3">
                        <i class="fa-solid fa-file-invoice-dollar"></i>
                    </div>
                    <h4 class="text-sm font-bold text-brand-navy mb-1.5">Chi phí hợp lý, minh bạch vật tư</h4>
                    <p class="text-xs text-slate-600 leading-relaxed">Dự toán rõ ràng chủng loại vật tư, cân đối ngân sách hiệu quả, cam kết không phát sinh chi phí ngoài hợp đồng.</p>
                </div>

                <div class="bg-white rounded-xl p-5 border border-brand-border shadow-sm">
                    <div class="w-10 h-10 rounded-lg bg-brand-navy text-brand-goldLight flex items-center justify-center mb-3">
                        <i class="fa-solid fa-headset"></i>
                    </div>
                    <h4 class="text-sm font-bold text-brand-navy mb-1.5">Hỗ trợ tư vấn miễn phí 24/7</h4>
                    <p class="text-xs text-slate-600 leading-relaxed">Khảo sát thực địa miễn phí tại Đà Nẵng, hỗ trợ thủ tục xin cấp phép xây dựng và hoàn công trọn gói.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- ========================================================= -->
    <!-- 6. CÔNG TRÌNH THỰC TẾ (9 Ảnh Google Drive thi công thực tế)-->
    <!-- Chia 2 cột trên điện thoại, KHÔNG nhãn dán, tên đầy đủ    -->
    <!-- ========================================================= -->
    <section id="cong-trinh-thuc-te" class="py-10 sm:py-14 bg-white">
        <div class="flatsome-container">
            <div class="text-center mb-6">
                <h2 class="section-heading text-lg sm:text-2xl font-extrabold text-brand-navy uppercase">
                    Công Trình Thực Tế
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3">
                    Hình ảnh thi công thực tế tại công trường do đội ngũ Xây Dựng Hưng Thịnh trực tiếp thực hiện.
                </p>
            </div>

            <!-- Danh mục lọc nhỏ gọn: 1 hàng đẹp trên máy tính, vuốt mượt trên điện thoại, không xuống dòng tên danh mục -->
            <div class="flex items-center justify-start sm:justify-center gap-2 overflow-x-auto no-scrollbar pb-2 mb-6" id="worksCategoryTabs">
                <button type="button" onclick="filterWorks('all')" data-cat="all" class="cat-tab-btn px-3.5 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold whitespace-nowrap bg-brand-navy text-white border border-brand-navy transition">
                    Tất cả
                </button>
                <button type="button" onclick="filterWorks('nha-pho')" data-cat="nha-pho" class="cat-tab-btn px-3.5 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold whitespace-nowrap bg-white text-slate-700 border border-brand-border hover:border-brand-navy hover:text-brand-navy transition">
                    Nhà phố
                </button>
                <button type="button" onclick="filterWorks('biet-thu')" data-cat="biet-thu" class="cat-tab-btn px-3.5 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold whitespace-nowrap bg-white text-slate-700 border border-brand-border hover:border-brand-navy hover:text-brand-navy transition">
                    Biệt thự
                </button>
                <button type="button" onclick="filterWorks('khach-san')" data-cat="khach-san" class="cat-tab-btn px-3.5 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold whitespace-nowrap bg-white text-slate-700 border border-brand-border hover:border-brand-navy hover:text-brand-navy transition">
                    Khách sạn – Căn hộ – Phòng trọ
                </button>
                <button type="button" onclick="filterWorks('van-phong')" data-cat="van-phong" class="cat-tab-btn px-3.5 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold whitespace-nowrap bg-white text-slate-700 border border-brand-border hover:border-brand-navy hover:text-brand-navy transition">
                    Văn phòng
                </button>
            </div>

            <!-- Lưới sản phẩm/công trình: 2 cột trên điện thoại, 3 cột tablet, 4 cột desktop -->
            <div id="worksGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Dữ liệu được render tự động từ mảng thực tế bên dưới -->
            </div>
        </div>
    </section>

    <!-- ========================================================= -->
    <!-- 7. CÁC DỰ ÁN TẠI ĐÀ NẴNG (10 Ảnh Google Drive dự án ĐN)   -->
    <!-- ========================================================= -->
    <section id="du-an-da-nang" class="py-10 sm:py-14 bg-brand-surface border-y border-brand-border">
        <div class="flatsome-container">
            <div class="text-center mb-6">
                <h2 class="section-heading text-lg sm:text-2xl font-extrabold text-brand-navy uppercase">
                    Các Dự Án Tiêu Biểu Tại Đà Nẵng
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
                    Tuyển chọn các dự án nhà phố, biệt thự, căn hộ cho thuê và văn phòng đã thiết kế &amp; thi công trọn gói tại các quận Cẩm Lệ, Hải Châu, Sơn Trà, Ngũ Hành Sơn, Liên Chiểu.
                </p>
            </div>

            <!-- Bộ lọc khu vực Đà Nẵng gọn đẹp -->
            <div class="flex items-center justify-start sm:justify-center gap-2 overflow-x-auto no-scrollbar pb-2 mb-6" id="danangTabs">
                <button type="button" onclick="filterDaNang('all')" data-area="all" class="dn-tab-btn px-3.5 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold whitespace-nowrap bg-brand-navy text-white border border-brand-navy transition">
                    Tất cả Đà Nẵng
                </button>
                <button type="button" onclick="filterDaNang('cam-le')" data-area="cam-le" class="dn-tab-btn px-3.5 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold whitespace-nowrap bg-white text-slate-700 border border-brand-border hover:border-brand-navy hover:text-brand-navy transition">
                    Cẩm Lệ – Hòa Xuân
                </button>
                <button type="button" onclick="filterDaNang('ngu-hanh-son')" data-area="ngu-hanh-son" class="dn-tab-btn px-3.5 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold whitespace-nowrap bg-white text-slate-700 border border-brand-border hover:border-brand-navy hover:text-brand-navy transition">
                    Ngũ Hành Sơn
                </button>
                <button type="button" onclick="filterDaNang('son-tra')" data-area="son-tra" class="dn-tab-btn px-3.5 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold whitespace-nowrap bg-white text-slate-700 border border-brand-border hover:border-brand-navy hover:text-brand-navy transition">
                    Sơn Trà
                </button>
                <button type="button" onclick="filterDaNang('hai-chau')" data-area="hai-chau" class="dn-tab-btn px-3.5 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold whitespace-nowrap bg-white text-slate-700 border border-brand-border hover:border-brand-navy hover:text-brand-navy transition">
                    Hải Châu – Liên Chiểu
                </button>
            </div>

            <!-- Lưới dự án Đà Nẵng: 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div id="danangGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Dữ liệu 10 dự án Đà Nẵng render bằng JS -->
            </div>
        </div>
    </section>

    <!-- ========================================================= -->
    <!-- 8. BẢNG BÁO GIÁ THAM KHẢO & FORM YÊU CẦU BÁO GIÁ TRANG CHỦ -->
    <!-- ========================================================= -->
    <section id="bao-gia" class="py-10 sm:py-14 bg-white">
        <div class="flatsome-container">
            <div class="text-center mb-8">
                <h2 class="section-heading text-lg sm:text-2xl font-extrabold text-brand-navy uppercase">
                    Tư Vấn &amp; Báo Giá Miễn Phí
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
                    Để lại thông tin quy mô công trình, kỹ sư Xây Dựng Hưng Thịnh sẽ lập bảng dự toán chi tiết và liên hệ tư vấn trong vòng 15 phút.
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-8 items-start">
                <!-- Cột trái: Bảng đơn giá tham khảo các gói dịch vụ -->
                <div class="lg:col-span-5 space-y-3">
                    <div class="rounded-xl border border-brand-border bg-brand-surface p-4 sm:p-5">
                        <h3 class="text-sm sm:text-base font-bold text-brand-navy mb-3">
                            Bảng Đơn Giá Tham Khảo Tại Đà Nẵng
                        </h3>
                        <div class="space-y-2.5 text-xs sm:text-sm">
                            <div class="flex items-center justify-between gap-2 pb-2.5 border-b border-brand-border">
                                <span class="font-medium text-slate-700">Thiết kế kiến trúc – nội thất</span>
                                <span class="font-bold text-brand-navy whitespace-nowrap">120.000 – 180.000đ/m²</span>
                            </div>
                            <div class="flex items-center justify-between gap-2 pb-2.5 border-b border-brand-border">
                                <span class="font-medium text-slate-700">Thi công phần thô &amp; nhân công</span>
                                <span class="font-bold text-brand-navy whitespace-nowrap">3.400.000 – 3.700.000đ/m²</span>
                            </div>
                            <div class="flex items-center justify-between gap-2 pb-2.5 border-b border-brand-border">
                                <span class="font-medium text-slate-700">Thi công nhà phố trọn gói</span>
                                <span class="font-bold text-brand-gold whitespace-nowrap">5.500.000 – 6.800.000đ/m²</span>
                            </div>
                            <div class="flex items-center justify-between gap-2">
                                <span class="font-medium text-slate-700">Thi công biệt thự – khách sạn</span>
                                <span class="font-bold text-brand-navy whitespace-nowrap">Báo giá theo hồ sơ</span>
                            </div>
                        </div>
                        <p class="text-[11px] text-slate-500 mt-3 leading-relaxed">
                            * Miễn phí 100% chi phí thiết kế kiến trúc và hỗ trợ thủ tục xin phép xây dựng khi ký hợp đồng thi công nhà trọn gói.
                        </p>
                    </div>

                    <div class="rounded-xl bg-brand-navy text-white p-5">
                        <div class="text-xs uppercase tracking-wider text-brand-goldLight font-semibold mb-1">
                            Hỗ trợ khảo sát trực tiếp
                        </div>
                        <div class="text-base sm:text-lg font-extrabold mb-2">
                            Hotline / Zalo: 0935.156.874
                        </div>
                        <p class="text-xs text-slate-200 leading-relaxed">
                            Văn phòng: 138 Lê Đại Hành, Phường Cẩm Lệ, TP Đà Nẵng. Làm việc từ Thứ 2 – Thứ 7 (07:30 – 17:30).
                        </p>
                    </div>
                </div>

                <!-- Cột phải: Form yêu cầu và báo giá giống mẫu tintruongthinh.com -->
                <div class="lg:col-span-7 bg-white rounded-xl border border-brand-border shadow-sm p-5 sm:p-7">
                    <form id="quoteForm" class="space-y-4" novalidate>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label for="qName" class="block text-xs font-semibold text-slate-700 mb-1.5">Họ và tên *</label>
                                <input id="qName" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-brand-border focus:outline-none focus:border-brand-navy">
                            </div>
                            <div>
                                <label for="qPhone" class="block text-xs font-semibold text-slate-700 mb-1.5">Số điện thoại / Zalo *</label>
                                <input id="qPhone" type="tel" required placeholder="VD: 0935 156 874" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-brand-border focus:outline-none focus:border-brand-navy">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label for="qEmail" class="block text-xs font-semibold text-slate-700 mb-1.5">Email</label>
                                <input id="qEmail" type="email" placeholder="Nhập địa chỉ email (nếu có)" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-brand-border focus:outline-none focus:border-brand-navy">
                            </div>
                            <div>
                                <label for="qType" class="block text-xs font-semibold text-slate-700 mb-1.5">Loại công trình</label>
                                <select id="qType" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-brand-border bg-white focus:outline-none focus:border-brand-navy">
                                    <option value="Nhà phố">Nhà phố</option>
                                    <option value="Biệt thự">Biệt thự</option>
                                    <option value="Khách sạn – Căn hộ cho thuê – Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                                    <option value="Văn phòng">Văn phòng</option>
                                    <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                                    <option value="Chưa xác định">Chưa xác định</option>
                                </select>
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label for="qBudget" class="block text-xs font-semibold text-slate-700 mb-1.5">Mức đầu tư dự kiến</label>
                                <select id="qBudget" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-brand-border bg-white focus:outline-none focus:border-brand-navy">
                                    <option value="Chưa xác định">Chưa xác định</option>
                                    <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                    <option value="500 triệu – 1 tỷ">500 triệu – 1 tỷ</option>
                                    <option value="1 – 2 tỷ">1 – 2 tỷ</option>
                                    <option value="2 – 3 tỷ">2 – 3 tỷ</option>
                                    <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                </select>
                            </div>
                            <div>
                                <label for="qArea" class="block text-xs font-semibold text-slate-700 mb-1.5">Khu vực xây dựng &amp; diện tích</label>
                                <input id="qArea" type="text" placeholder="VD: Cẩm Lệ, Đà Nẵng - 5x20m, 3 tầng" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-brand-border focus:outline-none focus:border-brand-navy">
                            </div>
                        </div>

                        <div>
                            <label for="qNote" class="block text-xs font-semibold text-slate-700 mb-1.5">Yêu cầu chi tiết</label>
                            <textarea id="qNote" rows="3" placeholder="Mô tả nhu cầu thiết kế, số phòng ngủ, thời gian dự kiến khởi công..." class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-brand-border focus:outline-none focus:border-brand-navy"></textarea>
                        </div>

                        <!-- Thông báo trạng thái form (không dùng alert) -->
                        <div id="quoteFeedback" class="hidden rounded-lg p-3 text-xs sm:text-sm font-medium"></div>

                        <button type="submit" class="w-full sm:w-auto px-7 py-3 rounded-lg bg-brand-navy hover:bg-brand-gold text-white font-bold text-sm transition shadow">
                            Gửi Yêu Cầu Báo Giá Ngay
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- ========================================================= -->
    <!-- 9. DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KINH NGHIỆM)-->
    <!-- ========================================================= -->
    <section id="tin-tuc" class="py-10 sm:py-14 bg-brand-surface border-y border-brand-border">
        <div class="flatsome-container">
            <div class="text-center mb-8">
                <h2 class="section-heading text-lg sm:text-2xl font-extrabold text-brand-navy uppercase">
                    Tin Tức &amp; Kinh Nghiệm Xây Nhà
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3">
                    Chia sẻ kiến thức kỹ thuật thi công, phong thủy nhà ở và cập nhật đơn giá xây dựng mới nhất tại Đà Nẵng.
                </p>
            </div>

            <!-- 2 cột mobile, 4 cột desktop -->
            <div id="articlesGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Bài viết được render bằng JS để hỗ trợ xem chi tiết ngay trên trang -->
            </div>
        </div>
    </section>

    <!-- ========================================================= -->
    <!-- 10. DANH MỤC CÁC ĐỐI TÁC VẬT TƯ & ĐỒNG HÀNH               -->
    <!-- ========================================================= -->
    <section id="doi-tac" class="py-10 sm:py-12 bg-white">
        <div class="flatsome-container">
            <div class="text-center mb-7">
                <h2 class="section-heading text-lg sm:text-2xl font-extrabold text-brand-navy uppercase">
                    Đối Tác Cung Ứng Vật Tư
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3">
                    Cam kết sử dụng 100% vật liệu chính hãng từ các thương hiệu uy tín hàng đầu Việt Nam &amp; Quốc tế.
                </p>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-4 gap-3 sm:gap-4">
                <div class="rounded-xl border border-brand-border bg-brand-surface px-4 py-5 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                    <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">HÒA PHÁT</span>
                    <span class="text-[11px] text-slate-500 mt-1">Thép xây dựng tiêu chuẩn</span>
                </div>
                <div class="rounded-xl border border-brand-border bg-brand-surface px-4 py-5 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                    <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">SÔNG GIANH</span>
                    <span class="text-[11px] text-slate-500 mt-1">Xi măng công trình miền Trung</span>
                </div>
                <div class="rounded-xl border border-brand-border bg-brand-surface px-4 py-5 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                    <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">DULUX / JOTUN</span>
                    <span class="text-[11px] text-slate-500 mt-1">Sơn nội ngoại thất cao cấp</span>
                </div>
                <div class="rounded-xl border border-brand-border bg-brand-surface px-4 py-5 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                    <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">CADIVI</span>
                    <span class="text-[11px] text-slate-500 mt-1">Dây cáp điện an toàn</span>
                </div>
                <div class="rounded-xl border border-brand-border bg-brand-surface px-4 py-5 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                    <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">BÌNH MINH</span>
                    <span class="text-[11px] text-slate-500 mt-1">Ống nhựa cấp thoát nước</span>
                </div>
                <div class="rounded-xl border border-brand-border bg-brand-surface px-4 py-5 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                    <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">TOTO / INAX</span>
                    <span class="text-[11px] text-slate-500 mt-1">Thiết bị vệ sinh chính hãng</span>
                </div>
                <div class="rounded-xl border border-brand-border bg-brand-surface px-4 py-5 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                    <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">XINGFA</span>
                    <span class="text-[11px] text-slate-500 mt-1">Nhôm kính nhập khẩu</span>
                </div>
                <div class="rounded-xl border border-brand-border bg-brand-surface px-4 py-5 flex flex-col items-center justify-center text-center hover:border-brand-gold transition">
                    <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">AN CƯỜNG</span>
                    <span class="text-[11px] text-slate-500 mt-1">Gỗ công nghiệp nội thất</span>
                </div>
            </div>
        </div>
    </section>

    <!-- ========================================================= -->
    <!-- 11. FANPAGE & BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ         -->
    <!-- ========================================================= -->
    <section id="lien-he" class="py-10 sm:py-14 bg-brand-surface border-t border-brand-border">
        <div class="flatsome-container">
            <div class="text-center mb-8">
                <h2 class="section-heading text-lg sm:text-2xl font-extrabold text-brand-navy uppercase">
                    Kết Nối Fanpage &amp; Chỉ Đường Văn Phòng
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3">
                    Ghé thăm văn phòng Xây Dựng Hưng Thịnh tại 138 Lê Đại Hành, Phường Cẩm Lệ, TP Đà Nẵng hoặc theo dõi tiến độ thi công hằng ngày trên Fanpage.
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                <!-- Khối Google Map trực tiếp trên trang chủ -->
                <div class="lg:col-span-7 bg-white rounded-xl border border-brand-border shadow-sm overflow-hidden flex flex-col">
                    <div class="px-4 py-3 border-b border-brand-border flex items-center justify-between gap-2 bg-white">
                        <div class="flex items-center gap-2 text-xs sm:text-sm font-bold text-brand-navy">
                            <i class="fa-solid fa-map-location-dot text-brand-gold"></i>
                            <span>Bản đồ: 138 Lê Đại Hành, Phường Cẩm Lệ, TP Đà Nẵng</span>
                        </div>
                        <a href="https://maps.google.com/?q=138+L%C3%AA+%C4%90%E1%BA%A1i+H%C3%A0nh,+C%E1%BA%A9m+L%E1%BB%87,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener" class="text-xs font-semibold text-brand-gold hover:underline whitespace-nowrap">
                            Mở Google Maps
                        </a>
                    </div>
                    <div class="w-full h-[290px] sm:h-[340px] flex-1 bg-slate-100">
                        <iframe
                            title="Bản đồ Công Ty TNHH Thiết Kế Và Thi Công Nhà Trọn Gói Hưng Thịnh - 138 Lê Đại Hành, Cẩm Lệ, Đà Nẵng"
                            src="https://maps.google.com/maps?q=138+L%C3%AA+%C4%90%E1%BA%A1i+H%C3%A0nh,+C%E1%BA%A9m+L%E1%BB%87,+%C4%90%C3%A0+N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full border-0"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>
                </div>

                <!-- Khối Fanpage chính thức hiển thị ngay ngoài trang chủ -->
                <div class="lg:col-span-5 bg-white rounded-xl border border-brand-border shadow-sm overflow-hidden flex flex-col justify-between">
                    <div>
                        <div class="px-4 py-3 border-b border-brand-border flex items-center justify-between">
                            <div class="flex items-center gap-2 text-xs sm:text-sm font-bold text-brand-navy">
                                <i class="fa-brands fa-facebook text-[#1877F2] text-base"></i>
                                <span>Fanpage Chính Thức</span>
                            </div>
                            <span class="text-[11px] text-slate-500">Cập nhật công trình mỗi ngày</span>
                        </div>

                        <!-- Ảnh bìa Fanpage lấy ảnh dự án thực tế -->
                        <div class="relative h-36 sm:h-40 bg-brand-navy overflow-hidden">
                            <img src="https://drive.google.com/thumbnail?id=1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff&sz=w1000"
                                 data-drive-id="1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff"
                                 alt="Fanpage Xây Dựng Hưng Thịnh Đà Nẵng"
                                 class="w-full h-full object-cover opacity-85"
                                 onerror="handleDriveImageError(this, 'Fanpage+Xay+Dung+Hung+Thinh')">
                            <div class="absolute inset-0 bg-gradient-to-t from-black/75 via-black/25 to-transparent"></div>
                            <div class="absolute bottom-3 left-3 right-3 flex items-end gap-3">
                                <!-- Avatar Logo Hưng Thịnh -->
                                <div class="w-12 h-12 rounded-lg bg-brand-navy border-2 border-white shadow flex items-center justify-center shrink-0">
                                    <svg class="w-8 h-8" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                                        <path d="M11 29L32 12L53 29" stroke="#C8922A" stroke-width="4.5" stroke-linecap="round" stroke-linejoin="round"/>
                                        <path d="M19 28V50M45 28V50M19 38H32" stroke="#FFFFFF" stroke-width="4.5" stroke-linecap="round"/>
                                        <path d="M32 24V50M36 27H49" stroke="#C8922A" stroke-width="4.5" stroke-linecap="round"/>
                                    </svg>
                                </div>
                                <div class="min-w-0">
                                    <h3 class="text-white font-bold text-xs sm:text-sm leading-snug break-words">
                                        Xây Dựng Nhà Trọn Gói Hưng Thịnh – Đà Nẵng
                                    </h3>
                                    <p class="text-[11px] text-slate-200">xaydunghungthinh.com • 0935.156.874</p>
                                </div>
                            </div>
                        </div>

                        <!-- Nội dung nổi bật trên Fanpage -->
                        <div class="p-4 space-y-3">
                            <p class="text-xs text-slate-600 leading-relaxed">
                                Theo dõi Fanpage <strong>Công Ty TNHH Thiết Kế &amp; Thi Công Nhà Trọn Gói Hưng Thịnh</strong> để xem nhật ký thi công thực tế, livestream bàn giao nhà mới và nhận ưu đãi miễn phí hồ sơ thiết kế tại Đà Nẵng.
                            </p>
                            <div class="grid grid-cols-3 gap-2">
                                <img src="https://drive.google.com/thumbnail?id=1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz&sz=w400"
                                     data-drive-id="1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz"
                                     alt="Ảnh công trình Hưng Thịnh 1"
                                     class="w-full aspect-square object-cover rounded-lg border border-brand-border"
                                     onerror="handleDriveImageError(this, 'Cong+Trinh+1')">
                                <img src="https://drive.google.com/thumbnail?id=1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k&sz=w400"
                                     data-drive-id="1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k"
                                     alt="Ảnh công trình Hưng Thịnh 2"
                                     class="w-full aspect-square object-cover rounded-lg border border-brand-border"
                                     onerror="handleDriveImageError(this, 'Cong+Trinh+2')">
                                <img src="https://drive.google.com/thumbnail?id=1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N&sz=w400"
                                     data-drive-id="1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N"
                                     alt="Ảnh công trình Hưng Thịnh 3"
                                     class="w-full aspect-square object-cover rounded-lg border border-brand-border"
                                     onerror="handleDriveImageError(this, 'Cong+Trinh+3')">
                            </div>
                        </div>
                    </div>

                    <div class="px-4 pb-4 flex items-center gap-2.5">
                        <a href="https://facebook.com" target="_blank" rel="noopener" class="flex-1 inline-flex items-center justify-center gap-2 py-2.5 px-3 rounded-lg bg-[#1877F2] hover:bg-[#1465D0] text-white text-xs font-semibold transition">
                            <i class="fa-brands fa-facebook-f"></i>
                            <span>Thích Fanpage</span>
                        </a>
                        <a href="https://zalo.me/0935156874" target="_blank" rel="noopener" class="flex-1 inline-flex items-center justify-center gap-2 py-2.5 px-3 rounded-lg bg-brand-navy hover:bg-brand-gold text-white text-xs font-semibold transition">
                            <i class="fa-solid fa-comments"></i>
                            <span>Nhắn tin tư vấn</span>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ========================================================= -->
    <!-- 12. FOOTER CHUẨN FLATSOME                                 -->
    <!-- ========================================================= -->
    <footer class="bg-brand-navyDark text-slate-300 pt-10 pb-6">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 pb-8 border-b border-white/10">
                <!-- Cột 1: Thông tin công ty -->
                <div class="lg:col-span-2">
                    <div class="flex items-center gap-2.5 mb-3">
                        <svg class="w-9 h-9 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <rect width="64" height="64" rx="10" fill="#164385"/>
                            <path d="M11 29L32 12L53 29" stroke="#C8922A" stroke-width="4.2" stroke-linecap="round" stroke-linejoin="round"/>
                            <path d="M19 28V50M45 28V50M19 38H32" stroke="#FFFFFF" stroke-width="4.5" stroke-linecap="round"/>
                            <path d="M32 24V50M36 27H49" stroke="#C8922A" stroke-width="4.2" stroke-linecap="round"/>
                        </svg>
                        <div>
                            <div class="text-sm sm:text-base font-extrabold text-white">CÔNG TY TNHH THIẾT KẾ VÀ THI CÔNG NHÀ TRỌN GÓI HƯNG THỊNH</div>
                            <div class="text-[11px] text-brand-goldLight">Website: xaydunghungthinh.com</div>
                        </div>
                    </div>
                    <ul class="space-y-2 text-xs sm:text-sm text-slate-300 mt-4">
                        <li class="flex items-start gap-2.5">
                            <i class="fa-solid fa-location-dot text-brand-gold mt-1"></i>
                            <span>Trụ sở: 138 Lê Đại Hành, Phường Cẩm Lệ, TP Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-phone text-brand-gold"></i>
                            <a href="tel:0935156874" class="hover:text-white transition">Hotline / Zalo: 0935.156.874</a>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-globe text-brand-gold"></i>
                            <span>Website: xaydunghungthinh.com</span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-file-contract text-brand-gold"></i>
                            <span>Mã số thuế: 0401834235</span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Lĩnh vực hoạt động -->
                <div>
                    <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-3 pb-2 border-b border-brand-gold/50 inline-block">
                        Lĩnh Vực Hoạt Động
                    </h4>
                    <ul class="space-y-2 text-xs sm:text-sm">
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-brand-goldLight transition">Thiết kế kiến trúc – nội thất</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-brand-goldLight transition">Thi công phần thô chuẩn kỹ thuật</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-brand-goldLight transition">Thi công hoàn thiện trọn gói</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-brand-goldLight transition">Thi công nội thất nhà phố – biệt thự</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục nhanh -->
                <div>
                    <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-3 pb-2 border-b border-brand-gold/50 inline-block">
                        Danh Mục Chính
                    </h4>
                    <ul class="space-y-2 text-xs sm:text-sm">
                        <li><a href="#cong-trinh-thuc-te" class="hover:text-brand-goldLight transition">Công trình thực tế</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-brand-goldLight transition">Các dự án tại Đà Nẵng</a></li>
                        <li><a href="#bao-gia" class="hover:text-brand-goldLight transition">Bảng báo giá xây nhà trọn gói</a></li>
                        <li><a href="#tin-tuc" class="hover:text-brand-goldLight transition">Tin tức &amp; Kinh nghiệm xây dựng</a></li>
                    </ul>
                </div>
            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
                <p>© 2026 CÔNG TY TNHH THIẾT KẾ VÀ THI CÔNG NHÀ TRỌN GÓI HƯNG THỊNH. All rights reserved.</p>
                <p>Thiết kế giao diện chuẩn Flatsome UX Builder – xaydunghungthinh.com</p>
            </div>
        </div>
    </footer>

    <!-- ========================================================= -->
    <!-- 13. CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)     -->
    <!-- Tương thích hoàn hảo cho cả Máy tính và Điện thoại        -->
    <!-- ========================================================= -->

    <!-- Phiên bản Máy tính & Tablet: Cụm nút nổi gọn gàng góc phải dưới -->
    <div class="hidden sm:flex fixed right-4 bottom-5 z-50 flex-col gap-2.5">
        <a href="https://zalo.me/0935156874" target="_blank" rel="noopener"
           class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0052CC] text-white pl-3 pr-4 py-2.5 rounded-full shadow-lg transition">
            <span class="w-7 h-7 rounded-full bg-white text-[#0068FF] font-extrabold text-[11px] flex items-center justify-center shrink-0">Zalo</span>
            <span class="text-xs font-bold whitespace-nowrap">Chat Zalo</span>
        </a>
        <a href="https://facebook.com" target="_blank" rel="noopener"
           class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1465D0] text-white pl-3 pr-4 py-2.5 rounded-full shadow-lg transition">
            <span class="w-7 h-7 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
                <i class="fa-brands fa-facebook-f text-sm"></i>
            </span>
            <span class="text-xs font-bold whitespace-nowrap">Facebook</span>
        </a>
        <a href="tel:0935156874"
           class="pulse-hotline flex items-center gap-2 bg-brand-gold hover:bg-brand-goldLight text-white pl-3 pr-4 py-2.5 rounded-full shadow-lg transition">
            <span class="w-7 h-7 rounded-full bg-white text-brand-navy flex items-center justify-center shrink-0">
                <i class="fa-solid fa-phone text-xs"></i>
            </span>
            <span class="text-xs font-extrabold whitespace-nowrap">0935.156.874</span>
        </a>
    </div>

    <!-- Phiên bản Điện thoại (<640px): Thanh liên hệ nổi cố định đáy màn hình không che ảnh & không tràn viền -->
    <div class="sm:hidden fixed bottom-0 left-0 right-0 z-50 bg-white border-t border-brand-border shadow-[0_-4px_12px_rgba(0,0,0,0.08)] grid grid-cols-3 divide-x divide-slate-200">
        <a href="tel:0935156874" class="flex flex-col items-center justify-center py-2 bg-brand-navy text-white active:opacity-90">
            <i class="fa-solid fa-phone text-brand-goldLight text-sm mb-0.5"></i>
            <span class="text-[11px] font-bold whitespace-nowrap">0935.156.874</span>
        </a>
        <a href="https://zalo.me/0935156874" target="_blank" rel="noopener" class="flex flex-col items-center justify-center py-2 bg-[#0068FF] text-white active:opacity-90">
            <span class="text-xs font-extrabold leading-tight">Zalo</span>
            <span class="text-[10px] font-medium whitespace-nowrap">Tư vấn ngay</span>
        </a>
        <a href="https://facebook.com" target="_blank" rel="noopener" class="flex flex-col items-center justify-center py-2 bg-[#1877F2] text-white active:opacity-90">
            <i class="fa-brands fa-facebook-f text-sm mb-0.5"></i>
            <span class="text-[11px] font-bold whitespace-nowrap">Facebook</span>
        </a>
    </div>

    <!-- ========================================================= -->
    <!-- 14. MODAL XEM CHI TIẾT CÔNG TRÌNH / BÀI VIẾT              -->
    <!-- ========================================================= -->
    <div id="detailModal" class="hidden fixed inset-0 z-50 bg-black/70 backdrop-blur-sm flex items-center justify-center p-3 sm:p-5">
        <div class="bg-white rounded-xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-brand-border">
            <div class="flex items-center justify-between px-4 sm:px-5 py-3.5 border-b border-brand-border sticky top-0 bg-white z-10">
                <h3 id="modalTitle" class="text-sm sm:text-base font-bold text-brand-navy pr-4 leading-snug"></h3>
                <button type="button" onclick="closeModal()" aria-label="Đóng cửa sổ" class="w-8 h-8 rounded-lg bg-slate-100 hover:bg-slate-200 text-slate-700 flex items-center justify-center shrink-0">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div class="p-4 sm:p-5">
                <div class="rounded-lg overflow-hidden bg-slate-100 mb-4">
                    <img id="modalImage" src="" alt="" class="w-full max-h-[380px] object-cover">
                </div>
                <div id="modalMeta" class="text-xs font-semibold text-brand-gold mb-2"></div>
                <div id="modalBody" class="text-xs sm:text-sm text-slate-700 leading-relaxed space-y-2.5"></div>
                <div class="mt-5 pt-4 border-t border-brand-border flex flex-wrap items-center justify-between gap-3">
                    <a href="tel:0935156874" class="inline-flex items-center gap-2 px-4 py-2 rounded-lg bg-brand-navy hover:bg-brand-gold text-white text-xs font-semibold transition">
                        <i class="fa-solid fa-phone"></i>
                        <span>Gọi tư vấn mẫu này: 0935.156.874</span>
                    </a>
                    <a href="#bao-gia" onclick="closeModal()" class="inline-flex items-center gap-2 px-4 py-2 rounded-lg border border-brand-navy text-brand-navy hover:bg-brand-surface text-xs font-semibold transition">
                        <span>Nhận báo giá chi tiết</span>
                    </a>
                </div>
            </div>
        </div>
    </div>

    <!-- ========================================================= -->
    <!-- 15. JAVASCRIPT XỬ LÝ DỮ LIỆU, SLIDER, LỌC DANH MỤC & FORM -->
    <!-- ========================================================= -->
    <script>
        /**
         * Hàm hỗ trợ tải ảnh từ Google Drive ổn định:
         * Bước 1: Dùng endpoint thumbnail độ phân giải cao (nhanh & ít lỗi CORS).
         * Bước 2: Nếu lỗi, tự động thử sang lh3.googleusercontent.com/d/ID.
         * Bước 3: Nếu file chưa mở quyền công khai, hiển thị ảnh dự phòng chuyên nghiệp.
         */
        function getDriveThumb(id, size = 1000) {
            return `https://drive.google.com/thumbnail?id=${id}&sz=w${size}`;
        }

        function handleDriveImageError(imgEl, fallbackText) {
            const tried = imgEl.getAttribute('data-fallback-step') || '0';
            const driveId = imgEl.getAttribute('data-drive-id');

            if (tried === '0' && driveId) {
                imgEl.setAttribute('data-fallback-step', '1');
                imgEl.src = `https://lh3.googleusercontent.com/d/${driveId}=w1000`;
            } else if (tried !== '2') {
                imgEl.setAttribute('data-fallback-step', '2');
                imgEl.src = `https://placehold.co/800x600/0B2C5D/FFFFFF?text=${fallbackText || 'Xay+Dung+Hung+Thinh'}`;
            }
        }

        /**
         * Dữ liệu 9 ảnh thực tế thi công xây dựng từ link Google Drive của khách hàng
         * Phân loại theo đúng danh mục chuẩn của website mẫu tintruongthinh.com
         */
        const constructionWorks = [
            {
                id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                title: 'Thi Công Trọn Gói Nhà Phố 3 Tầng Hiện Đại',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố',
                info: 'Quy mô: 3 tầng • Thi công trọn gói chìa khóa trao tay',
                desc: 'Công trình nhà phố 3 tầng được Xây Dựng Hưng Thịnh thiết kế và thi công trọn gói từ phần móng đến hoàn thiện nội thất, tối ưu ánh sáng tự nhiên và thông gió chéo.'
            },
            {
                id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                title: 'Thi Công Phần Thô Kết Cấu Bê Tông Cốt Thép',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố',
                info: 'Hạng mục: Phần thô & nhân công hoàn thiện',
                desc: 'Thi công cốt thép dầm sàn, đổ bê tông tươi đúng mác thiết kế, kiểm tra độ sụt và bảo dưỡng bê tông tiêu chuẩn dưới sự giám sát trực tiếp của kỹ sư trưởng.'
            },
            {
                id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                title: 'Hoàn Thiện Mặt Tiền Nhà Phố Phong Cách Hiện Đại',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố',
                info: 'Hạng mục: Thi công hoàn thiện ngoại thất',
                desc: 'Tổ chức mặt đứng tinh tế với hệ lam chắn nắng, cửa nhôm kính cao cấp và sơn chống thấm ngoại thất chịu khí hậu nắng gió miền Trung.'
            },
            {
                id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                title: 'Thi Công Biệt Thự Phố 2 Mặt Tiền Sang Trọng',
                category: 'biet-thu',
                categoryLabel: 'Biệt thự',
                info: 'Quy mô: Biệt thự 3 tầng • Thiết kế & Thi công trọn gói',
                desc: 'Biệt thự 2 mặt tiền kiến trúc hiện đại, bố trí sân vườn xanh mát, gara ô tô rộng rãi cùng hệ kết cấu vững chắc bảo hành 5 năm.'
            },
            {
                id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                title: 'Thi Công Khách Sạn – Căn Hộ Dịch Vụ Cao Cấp',
                category: 'khach-san',
                categoryLabel: 'Khách sạn – Căn hộ – Phòng trọ',
                info: 'Quy mô: 5 tầng • Tiêu chuẩn kinh doanh lưu trú',
                desc: 'Thi công đồng bộ hệ thống MEP, phòng cháy chữa cháy, cách âm và hoàn thiện phòng nghỉ tối ưu hiệu suất khai thác cho chủ đầu tư.'
            },
            {
                id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
                title: 'Thi Công Hoàn Thiện Nội Thất Nhà Phố Trọn Gói',
                category: 'nha-pho',
                categoryLabel: 'Nhà phố',
                info: 'Hạng mục: Thiết kế & Thi công nội thất',
                desc: 'Thi công nội thất phòng khách, bếp ăn và phòng ngủ sử dụng gỗ chống ẩm cao cấp, đường nét sắc sảo đúng 100% phối cảnh 3D.'
            },
            {
                id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                title: 'Thi Công Móng Băng & Kết Cấu Khung Biệt Thự',
                category: 'biet-thu',
                categoryLabel: 'Biệt thự',
                info: 'Hạng mục: Thi công nền móng & kết cấu',
                desc: 'Xử lý địa chất kỹ lưỡng, gia công lắp dựng cốt thép móng chuẩn bản vẽ kết cấu, đảm bảo độ ổn định bền vững hàng chục năm.'
            },
            {
                id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
                title: 'Thiết Kế & Thi Công Văn Phòng Công Ty Hiện Đại',
                category: 'van-phong',
                categoryLabel: 'Văn phòng',
                info: 'Hạng mục: Xây dựng & hoàn thiện văn phòng',
                desc: 'Không gian làm việc mở, hệ thống chiếu sáng tiêu chuẩn, vách kính cách âm giúp nâng tầm hình ảnh thương hiệu doanh nghiệp.'
            },
            {
                id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
                title: 'Xây Dựng Căn Hộ Cho Thuê – Phòng Trọ Cao Cấp',
                category: 'khach-san',
                categoryLabel: 'Khách sạn – Căn hộ – Phòng trọ',
                info: 'Quy mô: 12 căn hộ khép kín • Chìa khóa trao tay',
                desc: 'Giải pháp tối ưu diện tích sàn, chi phí đầu tư hợp lý và thời gian thi công nhanh giúp chủ đầu tư sớm đưa vào vận hành sinh lời.'
            }
        ];

        /**
         * Dữ liệu 10 dự án tại Đà Nẵng từ link Google Drive của khách hàng
         */
        const danangProjects = [
            {
                id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                title: 'Nhà Phố 3 Tầng Anh Minh – Khu Đô Thị Hòa Xuân',
                area: 'cam-le',
                location: 'Quận Cẩm Lệ, TP Đà Nẵng',
                desc: 'Thiết kế và thi công nhà trọn gói diện tích 5x20m tại Khu đô thị sinh thái Hòa Xuân. Bàn giao đúng tiến độ 4,5 tháng, đầy đủ nội thất.'
            },
            {
                id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
                title: 'Biệt Thự Hiện Đại Chị Hương – Khu Nam Việt Á',
                area: 'ngu-hanh-son',
                location: 'Quận Ngũ Hành Sơn, TP Đà Nẵng',
                desc: 'Biệt thự vườn thiết kế thông tầng sang trọng, tối ưu đón gió sông Hàn, hoàn thiện vật tư cao cấp theo yêu cầu gia chủ.'
            },
            {
                id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
                title: 'Căn Hộ Dịch Vụ Cho Thuê – Đường Phạm Văn Đồng',
                area: 'son-tra',
                location: 'Quận Sơn Trà, TP Đà Nẵng',
                desc: 'Công trình căn hộ dịch vụ 5 tầng gần biển Mỹ Khê, thiết kế hiện đại, trang bị đầy đủ thang máy và hệ thống nội thất đồng bộ.'
            },
            {
                id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
                title: 'Nhà Phố 2 Mặt Tiền Anh Tuấn – Lê Đại Hành',
                area: 'cam-le',
                location: 'Phường Cẩm Lệ, TP Đà Nẵng',
                desc: 'Nhà ở kết hợp mặt bằng kinh doanh ngay tuyến đường Lê Đại Hành, kết cấu vững chắc, mặt tiền thông thoáng nổi bật.'
            },
            {
                id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
                title: 'Khách Sạn Boutique Mini – Khu Biển Mỹ Khê',
                area: 'son-tra',
                location: 'Quận Sơn Trà, TP Đà Nẵng',
                desc: 'Thiết kế kiến trúc mang hơi hướng nghỉ dưỡng ven biển, tối ưu số lượng phòng và tiện ích sảnh đón khách.'
            },
            {
                id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
                title: 'Nhà Phố Trọn Gói Chị Thảo – Khu Đô Thị Phước Lý',
                area: 'hai-chau',
                location: 'Quận Liên Chiểu, TP Đà Nẵng',
                desc: 'Nhà phố 2 tầng 1 tum với giếng trời rộng, đảm bảo đủ công năng cho gia đình 3 thế hệ với mức chi phí tối ưu.'
            },
            {
                id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
                title: 'Trụ Sở Văn Phòng Doanh Nghiệp – Hải Châu',
                area: 'hai-chau',
                location: 'Quận Hải Châu, TP Đà Nẵng',
                desc: 'Thi công hoàn thiện tòa nhà văn phòng 4 tầng tại trung tâm TP Đà Nẵng, đáp ứng chuẩn kỹ thuật và tiến độ khai trương.'
            },
            {
                id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
                title: 'Nhà Phố 4 Tầng Kết Hợp Văn Phòng – Nguyễn Hữu Thọ',
                area: 'cam-le',
                location: 'Quận Cẩm Lệ, TP Đà Nẵng',
                desc: 'Thiết kế đa năng vừa làm văn phòng đại diện vừa kết hợp không gian sinh hoạt riêng tư cho gia đình ở tầng trên.'
            },
            {
                id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
                title: 'Biệt Thự Phố Sân Vườn Anh Hùng – Hòa Quý',
                area: 'ngu-hanh-son',
                location: 'Quận Ngũ Hành Sơn, TP Đà Nẵng',
                desc: 'Biệt thự phố diện tích đất 150m², thiết kế mái hiện đại chống nóng hiệu quả kết hợp không gian sân vườn thư giãn.'
            },
            {
                id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
                title: 'Căn Hộ Cao Cấp View Sông Hàn – Sơn Trà',
                area: 'son-tra',
                location: 'Quận Sơn Trà, TP Đà Nẵng',
                desc: 'Dự án căn hộ cao cấp thiết kế ban công rộng mở hướng sông, hoàn thiện nội thất tinh tế và bền đẹp theo thời gian.'
            }
        ];

        /**
         * Danh mục bài viết trang chủ (Kinh nghiệm xây nhà & kỹ thuật thi công)
         */
        const homeArticles = [
            {
                title: 'Hướng Dẫn Bảo Dưỡng Bê Tông Móng Đúng Kỹ Thuật Sau Khi Đổ',
                date: '15/11/2026',
                imgId: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                excerpt: 'Quy trình giữ ẩm và bảo dưỡng bê tông móng trong 7 ngày đầu giúp đạt cường độ tối đa, hạn chế nứt chân chim.',
                content: 'Bê tông móng là nền tảng chịu lực cho toàn bộ ngôi nhà. Sau khi đổ bê tông từ 4 đến 6 giờ, cần tiến hành che phủ bao bố ẩm hoặc tưới nước giữ ẩm liên tục trong tối thiểu 7 ngày đầu tiên, đặc biệt trong điều kiện thời tiết nắng nóng tại Đà Nẵng. Xây Dựng Hưng Thịnh luôn áp dụng quy trình nghiệm thu và bảo dưỡng nghiêm ngặt tại mọi công trình.'
            },
            {
                title: '03 Nỗi Lo Lớn Nhất Khi Xây Nhà Trọn Gói Và Cách Phòng Tránh',
                date: '10/11/2026',
                imgId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                excerpt: 'Phát sinh chi phí, chậm tiến độ và vật tư không đúng cam kết là 3 vấn đề chủ đầu tư cần kiểm soát ngay từ hợp đồng.',
                content: 'Để tránh phát sinh chi phí khi xây nhà, gia chủ cần hoàn thiện hồ sơ thiết kế chi tiết trước khi khởi công, thống nhất rõ bảng chủng loại vật tư phần thô lẫn hoàn thiện trong phụ lục hợp đồng và lựa chọn nhà thầu có trụ sở, năng lực thi công thực tế rõ ràng tại địa phương.'
            },
            {
                title: 'Kinh Nghiệm Chọn Vật Liệu Hoàn Thiện Bền Đẹp Cho Khí Hậu Đà Nẵng',
                date: '04/11/2026',
                imgId: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                excerpt: 'Giải pháp chống thấm tường biên, chọn sơn ngoại thất và hệ cửa nhôm kính chống ăn mòn hiệu quả cho nhà phố ven biển.',
                content: 'Khí hậu Đà Nẵng có mùa nắng gắt và mùa mưa bão lớn, khu vực gần biển còn chịu ảnh hưởng hơi muối. Vì vậy, nên ưu tiên xử lý chống thấm 2 lớp cho sân thượng, tường hướng Tây, sử dụng sơn ngoại thất đàn hồi cao cấp và phụ kiện cửa inox 304 chống gỉ sét.'
            },
            {
                title: 'Quy Trình 5 Bước Xây Nhà Trọn Gói Chìa Khóa Trao Tay Tại Hưng Thịnh',
                date: '28/10/2026',
                imgId: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                excerpt: 'Từ khảo sát thực địa, xin phép xây dựng, thiết kế 3D đến thi công và bàn giao bảo hành kết cấu 5 năm.',
                content: 'Quy trình làm việc tại Công Ty TNHH Thiết Kế và Thi Công Nhà Trọn Gói Hưng Thịnh gồm 5 bước minh bạch: (1) Tiếp nhận nhu cầu & khảo sát khu đất; (2) Lên phương án mặt bằng & phối cảnh 3D; (3) Lập dự toán chi tiết & ký hợp đồng; (4) Xin phép xây dựng và thi công giám sát theo giai đoạn; (5) Nghiệm thu, bàn giao nhà và kích hoạt chế độ bảo hành.'
            }
        ];

        // =========================================================
        // RENDER CÔNG TRÌNH THỰC TẾ (Không nhãn dán, tên không cắt)
        // =========================================================
        function renderWorks(category = 'all') {
            const grid = document.getElementById('worksGrid');
            const filtered = category === 'all'
                ? constructionWorks
                : constructionWorks.filter(item => item.category === category);

            grid.innerHTML = filtered.map((item) => {
                const idx = constructionWorks.indexOf(item);
                return `
                    <article onclick="openWorkModal(${idx})" class="cursor-pointer group bg-white rounded-xl overflow-hidden border border-brand-border shadow-sm hover:shadow-md transition flex flex-col">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img src="${getDriveThumb(item.id, 800)}"
                                 data-drive-id="${item.id}"
                                 alt="${item.title}"
                                 loading="lazy"
                                 class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
                                 onerror="handleDriveImageError(this, 'Cong+Trinh+Hung+Thinh')">
                        </div>
                        <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                            <h3 class="text-[12px] sm:text-[13.5px] font-bold text-brand-navy group-hover:text-brand-gold transition leading-snug break-words">
                                ${item.title}
                            </h3>
                            <p class="text-[10.5px] sm:text-xs text-slate-500 mt-1.5 leading-snug break-words">
                                ${item.categoryLabel}
                            </p>
                        </div>
                    </article>
                `;
            }).join('');
        }

        function filterWorks(category) {
            renderWorks(category);
            document.querySelectorAll('.cat-tab-btn').forEach(btn => {
                const isActive = btn.getAttribute('data-cat') === category;
                btn.className = isActive
                    ? 'cat-tab-btn px-3.5 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold whitespace-nowrap bg-brand-navy text-white border border-brand-navy transition'
                    : 'cat-tab-btn px-3.5 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold whitespace-nowrap bg-white text-slate-700 border border-brand-border hover:border-brand-navy hover:text-brand-navy transition';
            });
        }

        // =========================================================
        // RENDER CÁC DỰ ÁN TẠI ĐÀ NẴNG
        // =========================================================
        function renderDaNangProjects(area = 'all') {
            const grid = document.getElementById('danangGrid');
            const filtered = area === 'all'
                ? danangProjects
                : danangProjects.filter(item => item.area === area);

            grid.innerHTML = filtered.map((item) => {
                const idx = danangProjects.indexOf(item);
                return `
                    <article onclick="openDaNangModal(${idx})" class="cursor-pointer group bg-white rounded-xl overflow-hidden border border-brand-border shadow-sm hover:shadow-md transition flex flex-col">
                        <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
                            <img src="${getDriveThumb(item.id, 800)}"
                                 data-drive-id="${item.id}"
                                 alt="${item.title}"
                                 loading="lazy"
                                 class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
                                 onerror="handleDriveImageError(this, 'Du+An+Da+Nang')">
                        </div>
                        <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                            <h3 class="text-[12px] sm:text-[13.5px] font-bold text-brand-navy group-hover:text-brand-gold transition leading-snug break-words">
                                ${item.title}
                            </h3>
                            <p class="text-[10.5px] sm:text-xs text-slate-500 mt-1.5 flex items-start gap-1 leading-snug break-words">
                                <i class="fa-solid fa-location-dot text-brand-gold mt-0.5 shrink-0"></i>
                                <span>${item.location}</span>
                            </p>
                        </div>
                    </article>
                `;
            }).join('');
        }

        function filterDaNang(area) {
            renderDaNangProjects(area);
            document.querySelectorAll('.dn-tab-btn').forEach(btn => {
                const isActive = btn.getAttribute('data-area') === area;
                btn.className = isActive
                    ? 'dn-tab-btn px-3.5 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold whitespace-nowrap bg-brand-navy text-white border border-brand-navy transition'
                    : 'dn-tab-btn px-3.5 py-1.5 rounded-lg text-[11.5px] sm:text-xs font-semibold whitespace-nowrap bg-white text-slate-700 border border-brand-border hover:border-brand-navy hover:text-brand-navy transition';
            });
        }

        // =========================================================
        // RENDER BÀI VIẾT TRANG CHỦ
        // =========================================================
        function renderArticles() {
            const grid = document.getElementById('articlesGrid');
            grid.innerHTML = homeArticles.map((art, idx) => `
                <article onclick="openArticleModal(${idx})" class="cursor-pointer group bg-white rounded-xl overflow-hidden border border-brand-border shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
                        <img src="${getDriveThumb(art.imgId, 700)}"
                             data-drive-id="${art.imgId}"
                             alt="${art.title}"
                             loading="lazy"
                             class="w-full h-full object-cover group-hover:scale-105 transition duration-500"
                             onerror="handleDriveImageError(this, 'Tin+Tuc+Xay+Dung')">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] text-slate-400 mb-1">${art.date}</div>
                            <h3 class="text-[12px] sm:text-[13.5px] font-bold text-brand-navy group-hover:text-brand-gold transition leading-snug break-words">
                                ${art.title}
                            </h3>
                            <p class="hidden sm:block text-xs text-slate-600 mt-2 leading-relaxed">
                                ${art.excerpt}
                            </p>
                        </div>
                        <div class="mt-2.5 text-[11px] sm:text-xs font-semibold text-brand-gold">
                            Đọc chi tiết →
                        </div>
                    </div>
                </article>
            `).join('');
        }

        // =========================================================
        // ĐIỀU KHIỂN 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP
        // =========================================================
        let currentSlide = 0;
        const slides = document.querySelectorAll('.hero-slide-item');
        let slideTimer = null;

        function showSlide(index) {
            currentSlide = (index + slides.length) % slides.length;
            slides.forEach((slide, i) => {
                if (i === currentSlide) {
                    slide.classList.remove('hero-slide-inactive');
                    slide.classList.add('hero-slide-active');
                } else {
                    slide.classList.remove('hero-slide-active');
                    slide.classList.add('hero-slide-inactive');
                }
            });

            // Cập nhật trạng thái chấm chỉ báo
            for (let i = 0; i < slides.length; i++) {
                const dot = document.getElementById(`dot-${i}`);
                if (dot) {
                    dot.className = i === currentSlide
                        ? 'w-6 h-2 rounded-full bg-brand-gold transition-all'
                        : 'w-2.5 h-2 rounded-full bg-white/60 hover:bg-white transition-all';
                }
            }
        }

        function nextSlide() {
            showSlide(currentSlide + 1);
            resetSliderTimer();
        }

        function prevSlide() {
            showSlide(currentSlide - 1);
            resetSliderTimer();
        }

        function goToSlide(index) {
            showSlide(index);
            resetSliderTimer();
        }

        function resetSliderTimer() {
            if (slideTimer) clearInterval(slideTimer);
            slideTimer = setInterval(() => {
                showSlide(currentSlide + 1);
            }, 5200);
        }

        // Hỗ trợ vuốt cảm ứng trái/phải cho Banner trên điện thoại
        (function initSliderSwipe() {
            const sliderEl = document.getElementById('heroSlider');
            let touchStartX = 0;
            sliderEl.addEventListener('touchstart', (e) => {
                touchStartX = e.changedTouches[0].screenX;
            }, { passive: true });
            sliderEl.addEventListener('touchend', (e) => {
                const diff = touchStartX - e.changedTouches[0].screenX;
                if (Math.abs(diff) > 40) {
                    if (diff > 0) nextSlide();
                    else prevSlide();
                }
            }, { passive: true });
        })();

        // =========================================================
        // MODAL XEM CHI TIẾT CÔNG TRÌNH & BÀI VIẾT
        // =========================================================
        function openWorkModal(index) {
            const item = constructionWorks[index];
            openModal(item.title, item.id, `${item.categoryLabel} • ${item.info}`, item.desc);
        }

        function openDaNangModal(index) {
            const item = danangProjects[index];
            openModal(item.title, item.id, `Dự án tại ${item.location}`, item.desc);
        }

        function openArticleModal(index) {
            const art = homeArticles[index];
            openModal(art.title, art.imgId, `Đăng ngày ${art.date} • Xây Dựng Hưng Thịnh`, art.content);
        }

        function openModal(title, driveId, meta, body) {
            const modal = document.getElementById('detailModal');
            const img = document.getElementById('modalImage');
            document.getElementById('modalTitle').textContent = title;
            document.getElementById('modalMeta').textContent = meta;
            document.getElementById('modalBody').textContent = body;
            img.setAttribute('data-drive-id', driveId);
            img.setAttribute('data-fallback-step', '0');
            img.src = getDriveThumb(driveId, 1200);
            img.alt = title;
            img.onerror = function() { handleDriveImageError(this, 'Xay+Dung+Hung+Thinh'); };
            modal.classList.remove('hidden');
            document.body.style.overflow = 'hidden';
        }

        function closeModal() {
            document.getElementById('detailModal').classList.add('hidden');
            document.body.style.overflow = '';
        }

        document.getElementById('detailModal').addEventListener('click', (e) => {
            if (e.target.id === 'detailModal') closeModal();
        });

        // =========================================================
        // MENU DI ĐỘNG & FORM YÊU CẦU BÁO GIÁ
        // =========================================================
        const mobileMenuBtn = document.getElementById('mobileMenuBtn');
        const mobileMenuPanel = document.getElementById('mobileMenuPanel');

        mobileMenuBtn.addEventListener('click', () => {
            mobileMenuPanel.classList.toggle('hidden');
        });

        document.querySelectorAll('.mobile-link').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenuPanel.classList.add('hidden');
            });
        });

        document.getElementById('quoteForm').addEventListener('submit', function(e) {
            e.preventDefault();
            const name = document.getElementById('qName').value.trim();
            const phone = document.getElementById('qPhone').value.trim();
            const type = document.getElementById('qType').value;
            const budget = document.getElementById('qBudget').value;
            const feedback = document.getElementById('quoteFeedback');

            if (!name || !phone) {
                feedback.textContent = 'Vui lòng nhập đầy đủ Họ và tên cùng Số điện thoại để kỹ sư Hưng Thịnh liên hệ báo giá.';
                feedback.className = 'rounded-lg p-3 text-xs sm:text-sm font-medium bg-red-50 text-red-700 border border-red-200';
                return;
            }

            feedback.textContent = `Cảm ơn ${name}! Yêu cầu báo giá hạng mục "${type}" (${budget}) đã được gửi thành công. Kỹ sư Hưng Thịnh sẽ gọi lại số ${phone} trong thời gian sớm nhất.`;
            feedback.className = 'rounded-lg p-3 text-xs sm:text-sm font-medium bg-emerald-50 text-emerald-800 border border-emerald-200';
            this.reset();
        });

        // Khởi tạo trang
        renderWorks('all');
        renderDaNangProjects('all');
        renderArticles();
        resetSliderTimer();
    </script>
</body>
</html>
