<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Máy Tính Sĩ Kỳ - PC Gaming, Đồ Họa, Văn Phòng, Laptop & Linh Kiện Đà Nẵng | maytinhsiky.com</title>
    <meta name="description" content="Công Ty TNHH Công Nghệ Tin Học Sĩ Kỳ (maytinhsiky.com) - Chuyên PC Gaming, PC Đồ Họa Workstation, PC Văn Phòng, Laptop, Màn hình và Linh kiện chính hãng tại 22 Bình An 1, Phường Hòa Cường, TP. Đà Nẵng. Hotline: 0977.619.414.">
    <meta name="keywords" content="Máy Tính Sĩ Kỳ, Sĩ Kỳ Computer, maytinhsiky.com, PC Gaming Đà Nẵng, PC Đồ Họa Đà Nẵng, Máy tính văn phòng Đà Nẵng, 22 Bình An 1 Đà Nẵng">

    <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://maytinhsiky.com/">
    <meta property="og:site_name" content="Máy Tính Sĩ Kỳ - maytinhsiky.com">
    <meta property="og:title" content="Máy Tính Sĩ Kỳ - PC Gaming, Đồ Họa, Văn Phòng & Linh Kiện Chính Hãng Đà Nẵng">
    <meta property="og:description" content="Chuyên Build PC Gaming, Đồ Họa, Máy Tính Văn Phòng, Laptop & Màn Hình Chính Hãng. Địa chỉ: 22 Bình An 1, Phường Hòa Cường, Tp.Đà Nẵng - ĐT: 0977.619.414">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=10D1_3f93N-tXki1yhtqBiAZ_MtYxAyH2&sz=w1200">
    <meta property="og:image:secure_url" content="https://lh3.googleusercontent.com/d/10D1_3f93N-tXki1yhtqBiAZ_MtYxAyH2=w1200">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Máy Tính Sĩ Kỳ - maytinhsiky.com | 0977.619.414">
    <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=10D1_3f93N-tXki1yhtqBiAZ_MtYxAyH2&sz=w1200">
    <link rel="icon" type="image/png" href="https://drive.google.com/thumbnail?id=10D1_3f93N-tXki1yhtqBiAZ_MtYxAyH2&sz=w200">
    <link rel="apple-touch-icon" href="https://drive.google.com/thumbnail?id=10D1_3f93N-tXki1yhtqBiAZ_MtYxAyH2&sz=w200">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Google Fonts: Inter / Roboto chuẩn Flatsome -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome 6 -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        siky: {
                            primary: '#0056b3',    /* Màu xanh công nghệ chủ đạo theo logo Sĩ Kỳ */
                            dark: '#003d82',       /* Xanh đậm thanh điều hướng Flatsome */
                            light: '#eef6ff',      /* Nền xanh nhạt */
                            accent: '#00a8e8',     /* Xanh cyan điểm nhấn */
                            sale: '#d90429',       /* Đỏ giảm giá chuẩn Flatsome */
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
                    }
                }
            }
        }
    </script>

    <style>
        /* Reset chống tràn viền và chống lệch phải tuyệt đối */
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
            background-color: #f4f6f8;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Khung giao diện chuẩn 1500px trên máy tính, căn giữa tuyệt đối */
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
                padding-left: 16px;
                padding-right: 16px;
            }
        }

        /* Chuẩn Tên Danh Mục Trên Máy Tính: viết liền trên 1 hàng, không xuống dòng tên danh mục */
        .nav-cat-link {
            white-space: nowrap !important;
            display: inline-flex;
            align-items: center;
            gap: 5px;
            font-size: 12.5px;
            font-weight: 600;
            line-height: 1.2;
            padding: 7px 10px;
            border-radius: 6px;
            transition: all 0.2s ease;
        }
        .nav-cat-link:hover {
            background-color: rgba(255, 255, 255, 0.16);
        }

        /* Chữ danh mục ở trang chủ nhỏ gọn */
        .home-cat-title {
            font-size: 11.5px;
            line-height: 1.3;
            font-weight: 600;
            white-space: nowrap;
            overflow: hidden;
            text-overflow: ellipsis;
            max-width: 100%;
        }
        @media (min-width: 768px) {
            .home-cat-title {
                font-size: 12px;
            }
        }

        /* Thẻ sản phẩm chuẩn Flatsome (box-product) */
        .flatsome-product-box {
            background: #ffffff;
            border: 1px solid #e2e8f0;
            border-radius: 8px;
            transition: transform 0.2s ease, box-shadow 0.2s ease, border-color 0.2s ease;
            display: flex;
            flex-direction: column;
            height: 100%;
            position: relative;
            overflow: hidden;
        }
        .flatsome-product-box:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 20px -5px rgba(0, 86, 179, 0.12);
            border-color: #93c5fd;
        }

        /* Badge % giảm giá chuẩn Flatsome góc trên bên trái */
        .flatsome-Discount-badge {
            position: absolute;
            top: 8px;
            left: 8px;
            z-index: 10;
            background-color: #d90429;
            color: #ffffff;
            font-weight: 700;
            font-size: 11.5px;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            box-shadow: 0 2px 6px rgba(217, 4, 41, 0.35);
            line-height: 1;
        }
        @media (max-width: 640px) {
            .flatsome-Discount-badge {
                width: 34px;
                height: 34px;
                font-size: 10.5px;
                top: 6px;
                left: 6px;
            }
        }

        /* Tên sản phẩm hiển thị đầy đủ 100%, không bị cắt chữ (...) và không tràn ra ngoài */
        .product-full-title {
            font-size: 13px;
            line-height: 1.42;
            font-weight: 600;
            color: #1e293b;
            white-space: normal;
            word-break: break-word;
            overflow-wrap: break-word;
            display: block;
            margin-bottom: 6px;
        }
        @media (max-width: 640px) {
            .product-full-title {
                font-size: 12px;
                line-height: 1.38;
            }
        }
        .flatsome-product-box:hover .product-full-title {
            color: #0056b3;
        }

        /* Khung ảnh sản phẩm vuông chuẩn tỷ lệ 1:1 */
        .product-img-wrap {
            position: relative;
            width: 100%;
            aspect-ratio: 1 / 1;
            background-color: #f8fafc;
            display: flex;
            align-items: center;
            justify-content: center;
            overflow: hidden;
            border-bottom: 1px solid #f1f5f9;
        }
        .product-img-wrap img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.35s ease;
        }
        .flatsome-product-box:hover .product-img-wrap img {
            transform: scale(1.04);
        }

        /* Tiêu đề Section chuẩn Flatsome */
        .flatsome-section-header {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #0056b3;
            background: #ffffff;
            border-radius: 8px 8px 0 0;
            padding: 8px 14px;
            margin-bottom: 12px;
            flex-wrap: wrap;
            gap: 8px;
        }
        .flatsome-section-title {
            background: linear-gradient(90deg, #003d82 0%, #0056b3 100%);
            color: #ffffff;
            font-size: 13.5px;
            font-weight: 700;
            text-transform: uppercase;
            padding: 7px 14px;
            border-radius: 6px;
            display: inline-flex;
            align-items: center;
            gap: 8px;
            letter-spacing: 0.2px;
            white-space: nowrap;
        }
        @media (max-width: 640px) {
            .flatsome-section-title {
                font-size: 12px;
                padding: 6px 10px;
            }
        }

        /* Hiệu ứng nút liên hệ nổi bật */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(0, 86, 179, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(0, 86, 179, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(0, 86, 179, 0); }
        }
        .floating-btn-pulse {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body>

    <!-- =====================================================================
         HEADER WRAPPER (CHUẨN FLATSOME - KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN)
         ===================================================================== -->
    <header id="header" class="w-full bg-white shadow-sm sticky top-0 z-40">
        <!-- Top Bar thông tin cửa hàng -->
        <div class="bg-siky-dark text-white text-[11.5px] py-1.5 border-b border-blue-800">
            <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
                <div class="flex items-center gap-3 overflow-hidden">
                    <span class="inline-flex items-center gap-1.5 truncate">
                        <i class="fa-solid fa-location-dot text-cyan-300"></i>
                        <strong>Địa chỉ:</strong> 22 Bình An 1, Phường Hòa Cường, Tp.Đà Nẵng
                    </span>
                    <span class="hidden lg:inline-block text-blue-300">|</span>
                    <span class="hidden lg:inline-flex items-center gap-1.5">
                        <i class="fa-regular fa-clock text-cyan-300"></i>
                        Giờ mở cửa: 08:00 - 20:00 (Thứ 2 - Chủ Nhật)
                    </span>
                </div>
                <div class="hidden sm:flex items-center gap-4 text-[11.5px]">
                    <a href="#form-bao-gia" class="hover:text-cyan-300 transition flex items-center gap-1">
                        <i class="fa-solid fa-file-invoice-dollar"></i> Yêu cầu báo giá
                    </a>
                    <a href="#tin-tuc-trang-chu" class="hover:text-cyan-300 transition flex items-center gap-1">
                        <i class="fa-regular fa-newspaper"></i> Tin tức công nghệ
                    </a>
                    <a href="#bando-fanpage" class="hover:text-cyan-300 transition flex items-center gap-1">
                        <i class="fa-solid fa-map-location-dot"></i> Bản đồ & Fanpage
                    </a>
                </div>
            </div>
        </div>

        <!-- Header Main (Logo chỉnh gọn nhỏ lại + Thanh tìm kiếm + Giỏ hàng, KHÔNG có nút gọi ngay) -->
        <div class="bg-white py-2.5 border-b border-slate-200">
            <div class="flatsome-container flex items-center justify-between gap-2 sm:gap-4">
                <!-- Nút mở Menu Danh Mục trên Điện Thoại -->
                <button id="mobile-menu-btn" type="button" aria-label="Mở danh mục" class="lg:hidden inline-flex items-center justify-center w-9 h-9 rounded-lg bg-slate-100 text-siky-primary hover:bg-blue-50 shrink-0">
                    <i class="fa-solid fa-bars text-base"></i>
                </button>

                <!-- Logo chỉnh gọn nhỏ lại -->
                <a href="#" class="flex items-center gap-2 shrink-0 group" title="Máy Tính Sĩ Kỳ - maytinhsiky.com">
                    <div class="w-10 h-10 sm:w-11 sm:h-11 rounded-lg border border-slate-200 bg-white p-0.5 flex items-center justify-center overflow-hidden shrink-0 shadow-xs">
                        <img
                            src="https://drive.google.com/thumbnail?id=10D1_3f93N-tXki1yhtqBiAZ_MtYxAyH2&sz=w300"
                            data-drive-id="10D1_3f93N-tXki1yhtqBiAZ_MtYxAyH2"
                            alt="Logo Máy Tính Sĩ Kỳ"
                            class="w-full h-full object-contain"
                            onerror="handleDriveImgError(this, 'SK')"
                        >
                    </div>
                    <div class="leading-tight">
                        <span class="block font-extrabold text-siky-primary text-sm sm:text-base md:text-lg tracking-tight">MÁY TÍNH SĨ KỲ</span>
                        <span class="block text-[10px] sm:text-[11px] text-slate-500 font-medium">maytinhsiky.com</span>
                    </div>
                </a>

                <!-- Thanh tìm kiếm sản phẩm ở giữa -->
                <div class="flex-1 max-w-2xl mx-1 sm:mx-3">
                    <form id="search-form" onsubmit="handleProductSearch(event)" class="relative flex items-center w-full">
                        <input
                            id="search-input"
                            type="text"
                            placeholder="Tìm PC Gaming, PC Đồ Họa, Laptop, Màn hình, VGA..."
                            class="w-full h-9 sm:h-10 pl-3.5 pr-10 text-xs sm:text-sm rounded-lg border border-slate-300 bg-slate-50 focus:bg-white focus:border-siky-primary focus:outline-none transition"
                        >
                        <button type="submit" aria-label="Tìm kiếm" class="absolute right-1 top-1 bottom-1 px-3 rounded-md bg-siky-primary text-white hover:bg-siky-dark transition flex items-center justify-center">
                            <i class="fa-solid fa-magnifying-glass text-xs"></i>
                        </button>
                    </form>
                </div>

                <!-- Khu vực tiện ích gọn nhẹ bên phải (Không để nút gọi ngay để tránh tràn viền) -->
                <div class="flex items-center gap-2 shrink-0">
                    <a href="#form-bao-gia" class="hidden xl:inline-flex items-center gap-1.5 px-3 py-2 rounded-lg bg-slate-100 hover:bg-blue-50 text-slate-700 hover:text-siky-primary text-xs font-semibold transition">
                        <i class="fa-solid fa-screwdriver-wrench text-siky-primary"></i>
                        <span>Build PC Theo Yêu Cầu</span>
                    </a>
                    <button type="button" onclick="openQuoteModal('Giỏ hàng & Báo giá nhanh')" class="relative inline-flex items-center gap-1.5 px-2.5 sm:px-3 py-2 rounded-lg border border-slate-200 hover:border-siky-primary text-slate-700 hover:text-siky-primary text-xs font-semibold transition">
                        <i class="fa-solid fa-cart-shopping text-siky-primary text-sm"></i>
                        <span class="hidden sm:inline">Giỏ hàng</span>
                        <span id="cart-count-badge" class="inline-flex items-center justify-center min-w-[18px] h-[18px] px-1 rounded-full bg-siky-sale text-white text-[10px] font-bold">0</span>
                    </button>
                </div>
            </div>
        </div>

        <!-- Header Bottom: Thanh Danh Mục Sản Phẩm Trên Máy Tính
             Yêu cầu: Tên danh mục trên máy tính viết liền trên 1 hàng chữ nhỏ lại để nằm trên cùng 1 hàng hoặc xuống hàng 2, không được xuống dòng tên danh mục -->
        <nav class="hidden lg:block bg-siky-primary text-white shadow-xs">
            <div class="flatsome-container py-1">
                <ul class="flex flex-wrap items-center justify-start gap-x-1 gap-y-1">
                    <li>
                        <a href="#sec-pc-gaming" class="nav-cat-link bg-siky-dark text-white">
                            <i class="fa-solid fa-gamepad text-cyan-300"></i> PC Gaming
                        </a>
                    </li>
                    <li>
                        <a href="#sec-pc-dohoa" class="nav-cat-link">
                            <i class="fa-solid fa-cubes text-cyan-300"></i> PC Đồ Họa - Workstation
                        </a>
                    </li>
                    <li>
                        <a href="#sec-pc-vanphong" class="nav-cat-link">
                            <i class="fa-solid fa-desktop text-cyan-300"></i> PC Văn Phòng
                        </a>
                    </li>
                    <li>
                        <a href="#sec-pc-vanphong" class="nav-cat-link">
                            <i class="fa-solid fa-server text-cyan-300"></i> Máy Bộ - Máy Chủ
                        </a>
                    </li>
                    <li>
                        <a href="#sec-pc-gaming" class="nav-cat-link">
                            <i class="fa-solid fa-bolt text-cyan-300"></i> PC Cũ Giá Tốt
                        </a>
                    </li>
                    <li>
                        <a href="#sec-laptop" class="nav-cat-link">
                            <i class="fa-solid fa-laptop text-cyan-300"></i> Laptop Chính Hãng
                        </a>
                    </li>
                    <li>
                        <a href="#sec-manhinh" class="nav-cat-link">
                            <i class="fa-solid fa-tv text-cyan-300"></i> Màn Hình Máy Tính
                        </a>
                    </li>
                    <li>
                        <a href="#sec-linhkien" class="nav-cat-link">
                            <i class="fa-solid fa-microchip text-cyan-300"></i> Linh Kiện Máy Tính
                        </a>
                    </li>
                    <li>
                        <a href="#sec-linhkien" class="nav-cat-link">
                            <i class="fa-solid fa-keyboard text-cyan-300"></i> Phụ Kiện Gaming
                        </a>
                    </li>
                    <li>
                        <a href="#sec-vanphong-dn" class="nav-cat-link">
                            <i class="fa-solid fa-print text-cyan-300"></i> Thiết Bị Doanh Nghiệp
                        </a>
                    </li>
                    <li>
                        <a href="#sec-vanphong-dn" class="nav-cat-link">
                            <i class="fa-brands fa-windows text-cyan-300"></i> Phần Mềm Bản Quyền
                        </a>
                    </li>
                    <li>
                        <a href="#form-bao-gia" class="nav-cat-link">
                            <i class="fa-solid fa-headset text-cyan-300"></i> Báo Giá & Bảo Hành
                        </a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>

    <!-- =====================================================================
         DRAWER MENU DANH MỤC TRÊN ĐIỆN THOẠI
         ===================================================================== -->
    <div id="mobile-drawer-backdrop" onclick="toggleMobileDrawer(false)" class="fixed inset-0 bg-slate-900/60 z-50 hidden transition-opacity"></div>
    <aside id="mobile-drawer" class="fixed top-0 left-0 bottom-0 w-72 max-w-[85vw] bg-white z-50 -translate-x-full transition-transform duration-300 flex flex-col shadow-2xl">
        <div class="p-3.5 bg-siky-primary text-white flex items-center justify-between">
            <div class="flex items-center gap-2">
                <img
                    src="https://drive.google.com/thumbnail?id=10D1_3f93N-tXki1yhtqBiAZ_MtYxAyH2&sz=w150"
                    data-drive-id="10D1_3f93N-tXki1yhtqBiAZ_MtYxAyH2"
                    alt="Logo Sĩ Kỳ"
                    class="w-8 h-8 rounded bg-white p-0.5 object-contain"
                    onerror="handleDriveImgError(this, 'SK')"
                >
                <span class="font-bold text-sm">DANH MỤC SẢN PHẨM</span>
            </div>
            <button type="button" onclick="toggleMobileDrawer(false)" class="w-8 h-8 rounded-lg bg-white/15 flex items-center justify-center text-white">
                <i class="fa-solid fa-xmark"></i>
            </button>
        </div>
        <div class="flex-1 overflow-y-auto divide-y divide-slate-100 text-xs font-semibold text-slate-700">
            <a href="#sec-pc-gaming" onclick="toggleMobileDrawer(false)" class="flex items-center justify-between px-4 py-3 hover:bg-blue-50 hover:text-siky-primary">
                <span class="flex items-center gap-2.5"><i class="fa-solid fa-gamepad text-siky-primary w-4"></i> PC Gaming (Intel / AMD)</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
            <a href="#sec-pc-dohoa" onclick="toggleMobileDrawer(false)" class="flex items-center justify-between px-4 py-3 hover:bg-blue-50 hover:text-siky-primary">
                <span class="flex items-center gap-2.5"><i class="fa-solid fa-cubes text-siky-primary w-4"></i> PC Đồ Họa - Workstation</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
            <a href="#sec-pc-vanphong" onclick="toggleMobileDrawer(false)" class="flex items-center justify-between px-4 py-3 hover:bg-blue-50 hover:text-siky-primary">
                <span class="flex items-center gap-2.5"><i class="fa-solid fa-desktop text-siky-primary w-4"></i> PC Văn Phòng - Học Tập</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
            <a href="#sec-pc-vanphong" onclick="toggleMobileDrawer(false)" class="flex items-center justify-between px-4 py-3 hover:bg-blue-50 hover:text-siky-primary">
                <span class="flex items-center gap-2.5"><i class="fa-solid fa-server text-siky-primary w-4"></i> Máy Bộ Dell / HP / Asus - Server</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
            <a href="#sec-pc-gaming" onclick="toggleMobileDrawer(false)" class="flex items-center justify-between px-4 py-3 hover:bg-blue-50 hover:text-siky-primary">
                <span class="flex items-center gap-2.5"><i class="fa-solid fa-bolt text-siky-primary w-4"></i> PC Cũ Giá Tốt Đà Nẵng</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
            <a href="#sec-laptop" onclick="toggleMobileDrawer(false)" class="flex items-center justify-between px-4 py-3 hover:bg-blue-50 hover:text-siky-primary">
                <span class="flex items-center gap-2.5"><i class="fa-solid fa-laptop text-siky-primary w-4"></i> Laptop Gaming & Văn Phòng</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
            <a href="#sec-manhinh" onclick="toggleMobileDrawer(false)" class="flex items-center justify-between px-4 py-3 hover:bg-blue-50 hover:text-siky-primary">
                <span class="flex items-center gap-2.5"><i class="fa-solid fa-tv text-siky-primary w-4"></i> Màn Hình Máy Tính 24" - 34"</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
            <a href="#sec-linhkien" onclick="toggleMobileDrawer(false)" class="flex items-center justify-between px-4 py-3 hover:bg-blue-50 hover:text-siky-primary">
                <span class="flex items-center gap-2.5"><i class="fa-solid fa-microchip text-siky-primary w-4"></i> Linh Kiện (Main, CPU, RAM, VGA)</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
            <a href="#sec-linhkien" onclick="toggleMobileDrawer(false)" class="flex items-center justify-between px-4 py-3 hover:bg-blue-50 hover:text-siky-primary">
                <span class="flex items-center gap-2.5"><i class="fa-solid fa-keyboard text-siky-primary w-4"></i> Phụ Kiện Phím, Chuột, Tai Nghe</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
            <a href="#sec-vanphong-dn" onclick="toggleMobileDrawer(false)" class="flex items-center justify-between px-4 py-3 hover:bg-blue-50 hover:text-siky-primary">
                <span class="flex items-center gap-2.5"><i class="fa-solid fa-print text-siky-primary w-4"></i> Thiết Bị Doanh Nghiệp & Máy In</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
            <a href="#sec-vanphong-dn" onclick="toggleMobileDrawer(false)" class="flex items-center justify-between px-4 py-3 hover:bg-blue-50 hover:text-siky-primary">
                <span class="flex items-center gap-2.5"><i class="fa-brands fa-windows text-siky-primary w-4"></i> Phần Mềm Bản Quyền Windows/Office</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
            <a href="#form-bao-gia" onclick="toggleMobileDrawer(false)" class="flex items-center justify-between px-4 py-3 hover:bg-blue-50 hover:text-siky-primary">
                <span class="flex items-center gap-2.5"><i class="fa-solid fa-file-signature text-siky-primary w-4"></i> Gửi Yêu Cầu Báo Giá Nhanh</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
        </div>
        <div class="p-3.5 bg-slate-50 border-t border-slate-200 text-xs text-slate-600 space-y-1">
            <div class="font-bold text-siky-primary">CÔNG TY TNHH CÔNG NGHỆ TIN HỌC SĨ KỲ</div>
            <div>ĐC: 22 Bình An 1, P. Hòa Cường, TP. Đà Nẵng</div>
            <div>Hotline/Zalo: <strong class="text-siky-sale">0977.619.414</strong></div>
        </div>
    </aside>

    <!-- =====================================================================
         MAIN CONTENT (CHUẨN CẤU TRÚC UX BUILDER FLATSOME)
         ===================================================================== -->
    <main id="main" class="py-3 sm:py-4 space-y-5">

        <!-- 1. SECTION SLIDER 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU
             Thiết kế riêng 2 ảnh banner trên Máy tính (hidden md:block) và 2 ảnh banner mới trên Điện thoại (block md:hidden)
             để chữ bên trong ảnh nhỏ gọn, nằm hết 100% trong khung ảnh, tuyệt đối không tràn viền -->
        <section class="flatsome-container">
            <div class="relative w-full rounded-xl overflow-hidden shadow-sm border border-slate-200 bg-slate-900">

                <!-- ================= SLIDE 1 ================= -->
                <div class="hero-slide block transition-opacity duration-500" data-slide="0">
                    <!-- Phiên bản Banner 1 dành riêng cho MÁY TÍNH (Chiều cao cố định 370px) -->
                    <div class="hidden md:grid md:grid-cols-12 items-center w-full h-[370px] bg-gradient-to-r from-[#002855] via-[#004085] to-[#0056b3] px-10 lg:px-14 relative overflow-hidden">
                        <div class="col-span-7 z-10 pr-6 space-y-3">
                            <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-cyan-400/20 border border-cyan-300/40 text-cyan-200 text-xs font-semibold">
                                <i class="fa-solid fa-microchip"></i> MÁY TÍNH SĨ KỲ - MAYTINHSIKY.COM
                            </div>
                            <h1 class="text-white font-extrabold text-2xl lg:text-3xl leading-snug">
                                CHUYÊN BUILD PC GAMING, ĐỒ HỌA WORKSTATION & PC VĂN PHÒNG ĐÀ NẴNG
                            </h1>
                            <p class="text-blue-100 text-xs lg:text-sm leading-relaxed max-w-xl">
                                Linh kiện chính hãng 100% • Tối ưu hiệu năng theo đúng ngân sách • Bảo hành minh bạch lên đến 36 tháng • Hỗ trợ giao lắp tận nơi tại TP. Đà Nẵng.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center gap-3 text-xs">
                                <a href="#sec-pc-gaming" class="px-4 py-2.5 rounded-lg bg-cyan-400 hover:bg-cyan-300 text-slate-950 font-bold transition shadow-sm">
                                    Xem Cấu Hình PC Hot
                                </a>
                                <a href="#form-bao-gia" class="px-4 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white font-semibold border border-white/30 transition">
                                    Nhận Báo Giá Build PC
                                </a>
                                <span class="text-cyan-200 font-medium">
                                    <i class="fa-solid fa-location-dot mr-1"></i>22 Bình An 1, P. Hòa Cường, Đà Nẵng | ĐT: 0977.619.414
                                </span>
                            </div>
                        </div>
                        <div class="col-span-5 z-10 flex items-center justify-center">
                            <div class="grid grid-cols-2 gap-3 w-full max-w-[390px]">
                                <div class="bg-white/10 backdrop-blur-xs p-2 rounded-xl border border-white/20">
                                    <img src="https://drive.google.com/thumbnail?id=1y_ks82EgPIdXuaOtmPkjmgjxqp1W6TTj&sz=w500" data-drive-id="1y_ks82EgPIdXuaOtmPkjmgjxqp1W6TTj" alt="PC Gaming Sĩ Kỳ" class="w-full h-36 object-cover rounded-lg" onerror="handleDriveImgError(this, 'PC Gaming')">
                                </div>
                                <div class="bg-white/10 backdrop-blur-xs p-2 rounded-xl border border-white/20">
                                    <img src="https://drive.google.com/thumbnail?id=1h_Wt-hpWM3VerZ6nyJMvI4S7SDXhik3c&sz=w500" data-drive-id="1h_Wt-hpWM3VerZ6nyJMvI4S7SDXhik3c" alt="PC Đồ Họa Sĩ Kỳ" class="w-full h-36 object-cover rounded-lg" onerror="handleDriveImgError(this, 'PC Đồ Họa')">
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Phiên bản Banner 1 thiết kế mới dành riêng cho ĐIỆN THOẠI (Chiều cao cố định 215px, chữ nhỏ gọn nằm hết trong ảnh) -->
                    <div class="flex md:hidden flex-col justify-between w-full h-[215px] bg-gradient-to-br from-[#002855] via-[#004691] to-[#0056b3] p-3.5 relative overflow-hidden">
                        <div class="flex items-center gap-2">
                            <span class="px-2 py-0.5 rounded bg-cyan-400/20 border border-cyan-300/40 text-cyan-200 text-[10px] font-bold">
                                MAYTINHSIKY.COM
                            </span>
                            <span class="text-[10px] text-blue-100 font-medium truncate">ĐT: 0977.619.414</span>
                        </div>
                        <div class="grid grid-cols-12 gap-2 items-center my-auto">
                            <div class="col-span-8 space-y-1 pr-1">
                                <h2 class="text-white font-extrabold text-[13px] leading-snug">
                                    BUILD PC GAMING, ĐỒ HỌA & VĂN PHÒNG GIÁ TỐT ĐÀ NẴNG
                                </h2>
                                <p class="text-blue-100 text-[10.5px] leading-tight">
                                    Linh kiện chính hãng • Bảo hành 36 tháng • Giao lắp tận nơi tại Đà Nẵng.
                                </p>
                            </div>
                            <div class="col-span-4 flex justify-end">
                                <img src="https://drive.google.com/thumbnail?id=1y_ks82EgPIdXuaOtmPkjmgjxqp1W6TTj&sz=w300" data-drive-id="1y_ks82EgPIdXuaOtmPkjmgjxqp1W6TTj" alt="PC Sĩ Kỳ" class="w-20 h-20 object-cover rounded-lg border border-white/30 bg-white/10" onerror="handleDriveImgError(this, 'PC')">
                            </div>
                        </div>
                        <div class="flex items-center justify-between text-[10px] text-cyan-200 border-t border-white/15 pt-1.5">
                            <span class="truncate"><i class="fa-solid fa-location-dot mr-1"></i>22 Bình An 1, P. Hòa Cường, Đà Nẵng</span>
                            <a href="#sec-pc-gaming" class="px-2 py-0.5 rounded bg-cyan-400 text-slate-950 font-bold shrink-0">Xem ngay</a>
                        </div>
                    </div>
                </div>

                <!-- ================= SLIDE 2 ================= -->
                <div class="hero-slide hidden transition-opacity duration-500" data-slide="1">
                    <!-- Phiên bản Banner 2 dành riêng cho MÁY TÍNH (Chiều cao cố định 370px bằng đúng Banner 1) -->
                    <div class="hidden md:grid md:grid-cols-12 items-center w-full h-[370px] bg-gradient-to-r from-[#0a192f] via-[#0f3166] to-[#0056b3] px-10 lg:px-14 relative overflow-hidden">
                        <div class="col-span-7 z-10 pr-6 space-y-3">
                            <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-amber-400/20 border border-amber-300/40 text-amber-200 text-xs font-semibold">
                                <i class="fa-solid fa-tv"></i> MÀN HÌNH - LAPTOP - LINH KIỆN CHÍNH HÃNG
                            </div>
                            <h2 class="text-white font-extrabold text-2xl lg:text-3xl leading-snug">
                                PHÂN PHỐI MÀN HÌNH GAMING, LAPTOP, VGA & THIẾT BỊ DOANH NGHIỆP
                            </h2>
                            <p class="text-blue-100 text-xs lg:text-sm leading-relaxed max-w-xl">
                                Đa dạng màn hình 100Hz - 320Hz (ViewSonic, ASUS, LG, Samsung, MSI), Card đồ họa RTX/Radeon, nâng cấp SSD/RAM và bảo trì máy tính chuyên nghiệp.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center gap-3 text-xs">
                                <a href="#sec-manhinh" class="px-4 py-2.5 rounded-lg bg-amber-400 hover:bg-amber-300 text-slate-950 font-bold transition shadow-sm">
                                    Khám Phá Màn Hình & VGA
                                </a>
                                <a href="#bando-fanpage" class="px-4 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 text-white font-semibold border border-white/30 transition">
                                    Xem Địa Chỉ Showroom
                                </a>
                                <span class="text-amber-200 font-medium">
                                    <i class="fa-solid fa-phone-volume mr-1"></i>Tư vấn kỹ thuật: 0977.619.414
                                </span>
                            </div>
                        </div>
                        <div class="col-span-5 z-10 flex items-center justify-center">
                            <div class="grid grid-cols-2 gap-3 w-full max-w-[390px]">
                                <div class="bg-white/10 backdrop-blur-xs p-2 rounded-xl border border-white/20">
                                    <img src="https://drive.google.com/thumbnail?id=1qNVKyBdrJFcKIWjXwOYCl6O71A-wnPyf&sz=w500" data-drive-id="1qNVKyBdrJFcKIWjXwOYCl6O71A-wnPyf" alt="Màn Hình Máy Tính Sĩ Kỳ" class="w-full h-36 object-cover rounded-lg" onerror="handleDriveImgError(this, 'Màn Hình')">
                                </div>
                                <div class="bg-white/10 backdrop-blur-xs p-2 rounded-xl border border-white/20">
                                    <img src="https://drive.google.com/thumbnail?id=1Cwo4ZBOIO7IuqKdyl5mZVV3mmkB0KGY7&sz=w500" data-drive-id="1Cwo4ZBOIO7IuqKdyl5mZVV3mmkB0KGY7" alt="Linh Kiện Máy Tính Sĩ Kỳ" class="w-full h-36 object-cover rounded-lg" onerror="handleDriveImgError(this, 'Linh Kiện')">
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Phiên bản Banner 2 thiết kế mới dành riêng cho ĐIỆN THOẠI (Chiều cao cố định 215px bằng đúng Banner 1, chữ nhỏ gọn không tràn viền) -->
                    <div class="flex md:hidden flex-col justify-between w-full h-[215px] bg-gradient-to-br from-[#0a192f] via-[#0f3166] to-[#0056b3] p-3.5 relative overflow-hidden">
                        <div class="flex items-center gap-2">
                            <span class="px-2 py-0.5 rounded bg-amber-400/20 border border-amber-300/40 text-amber-200 text-[10px] font-bold">
                                SĨ KỲ COMPUTER
                            </span>
                            <span class="text-[10px] text-blue-100 font-medium truncate">Hotline: 0977.619.414</span>
                        </div>
                        <div class="grid grid-cols-12 gap-2 items-center my-auto">
                            <div class="col-span-8 space-y-1 pr-1">
                                <h2 class="text-white font-extrabold text-[13px] leading-snug">
                                    MÀN HÌNH GAMING, LAPTOP & LINH KIỆN VGA CHÍNH HÃNG
                                </h2>
                                <p class="text-blue-100 text-[10.5px] leading-tight">
                                    Đầy đủ màn hình 100Hz - 320Hz, RAM, SSD, Card đồ họa & Thiết bị văn phòng.
                                </p>
                            </div>
                            <div class="col-span-4 flex justify-end">
                                <img src="https://drive.google.com/thumbnail?id=1qNVKyBdrJFcKIWjXwOYCl6O71A-wnPyf&sz=w300" data-drive-id="1qNVKyBdrJFcKIWjXwOYCl6O71A-wnPyf" alt="Màn Hình Sĩ Kỳ" class="w-20 h-20 object-cover rounded-lg border border-white/30 bg-white/10" onerror="handleDriveImgError(this, 'Màn Hình')">
                            </div>
                        </div>
                        <div class="flex items-center justify-between text-[10px] text-amber-200 border-t border-white/15 pt-1.5">
                            <span class="truncate"><i class="fa-solid fa-location-dot mr-1"></i>22 Bình An 1, P. Hòa Cường, Đà Nẵng</span>
                            <a href="#sec-manhinh" class="px-2 py-0.5 rounded bg-amber-400 text-slate-950 font-bold shrink-0">Khám phá</a>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng Slider -->
                <button type="button" onclick="changeHeroSlide(-1)" aria-label="Banner trước" class=" -translate-y-1/2 absolute top-1/2 left-2 z-20 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button type="button" onclick="changeHeroSlide(1)" aria-label="Banner kế tiếp" class="-translate-y-1/2 absolute top-1/2 right-2 z-20 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>

                <!-- Chấm chỉ báo Slide -->
                <div class="absolute bottom-2 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button type="button" onclick="goToHeroSlide(0)" class="hero-dot w-5 h-1.5 rounded-full bg-white transition-all" aria-label="Slide 1"></button>
                    <button type="button" onclick="goToHeroSlide(1)" class="hero-dot w-2 h-1.5 rounded-full bg-white/50 transition-all" aria-label="Slide 2"></button>
                </div>
            </div>
        </section>

        <!-- 2. DANH MỤC SẢN PHẨM TRANG CHỦ (LẤY TỪ MẪU PHUCNGUYENDANANG.COM - CHỮ NHỎ GỌN, ĐẸP MẮT TRÊN CẢ PC & MOBILE) -->
        <section class="flatsome-container">
            <div class="bg-white rounded-xl p-3 sm:p-4 border border-slate-200 shadow-xs">
                <div class="flex items-center justify-between mb-3 pb-2 border-b border-slate-100">
                    <h2 class="text-xs sm:text-sm font-bold text-siky-primary uppercase flex items-center gap-2">
                        <i class="fa-solid fa-layer-group"></i> DANH MỤC SẢN PHẨM
                    </h2>
                    <span class="text-[11px] text-slate-500 hidden sm:inline">Chọn nhanh danh mục theo nhu cầu của bạn</span>
                </div>
                <!-- Lưới danh mục: chữ danh mục ở trang chủ nhỏ gọn, viết liền trên 1 hàng không bị gãy dòng -->
                <div class="grid grid-cols-3 sm:grid-cols-4 md:grid-cols-6 lg:grid-cols-11 gap-2">
                    <a href="#sec-pc-gaming" class="group flex flex-col items-center justify-center p-2 rounded-lg bg-slate-50 hover:bg-blue-50 border border-slate-200/80 hover:border-siky-primary transition text-center">
                        <div class="w-9 h-9 rounded-full bg-blue-100 text-siky-primary flex items-center justify-center mb-1.5 group-hover:bg-siky-primary group-hover:text-white transition">
                            <i class="fa-solid fa-gamepad text-sm"></i>
                        </div>
                        <span class="home-cat-title text-slate-700 group-hover:text-siky-primary">PC Gaming</span>
                    </a>
                    <a href="#sec-pc-dohoa" class="group flex flex-col items-center justify-center p-2 rounded-lg bg-slate-50 hover:bg-blue-50 border border-slate-200/80 hover:border-siky-primary transition text-center">
                        <div class="w-9 h-9 rounded-full bg-blue-100 text-siky-primary flex items-center justify-center mb-1.5 group-hover:bg-siky-primary group-hover:text-white transition">
                            <i class="fa-solid fa-cubes text-sm"></i>
                        </div>
                        <span class="home-cat-title text-slate-700 group-hover:text-siky-primary">PC Đồ Họa</span>
                    </a>
                    <a href="#sec-pc-vanphong" class="group flex flex-col items-center justify-center p-2 rounded-lg bg-slate-50 hover:bg-blue-50 border border-slate-200/80 hover:border-siky-primary transition text-center">
                        <div class="w-9 h-9 rounded-full bg-blue-100 text-siky-primary flex items-center justify-center mb-1.5 group-hover:bg-siky-primary group-hover:text-white transition">
                            <i class="fa-solid fa-desktop text-sm"></i>
                        </div>
                        <span class="home-cat-title text-slate-700 group-hover:text-siky-primary">PC Văn Phòng</span>
                    </a>
                    <a href="#sec-pc-vanphong" class="group flex flex-col items-center justify-center p-2 rounded-lg bg-slate-50 hover:bg-blue-50 border border-slate-200/80 hover:border-siky-primary transition text-center">
                        <div class="w-9 h-9 rounded-full bg-blue-100 text-siky-primary flex items-center justify-center mb-1.5 group-hover:bg-siky-primary group-hover:text-white transition">
                            <i class="fa-solid fa-server text-sm"></i>
                        </div>
                        <span class="home-cat-title text-slate-700 group-hover:text-siky-primary">Máy Bộ - Server</span>
                    </a>
                    <a href="#sec-pc-gaming" class="group flex flex-col items-center justify-center p-2 rounded-lg bg-slate-50 hover:bg-blue-50 border border-slate-200/80 hover:border-siky-primary transition text-center">
                        <div class="w-9 h-9 rounded-full bg-blue-100 text-siky-primary flex items-center justify-center mb-1.5 group-hover:bg-siky-primary group-hover:text-white transition">
                            <i class="fa-solid fa-bolt text-sm"></i>
                        </div>
                        <span class="home-cat-title text-slate-700 group-hover:text-siky-primary">PC Cũ Giá Tốt</span>
                    </a>
                    <a href="#sec-laptop" class="group flex flex-col items-center justify-center p-2 rounded-lg bg-slate-50 hover:bg-blue-50 border border-slate-200/80 hover:border-siky-primary transition text-center">
                        <div class="w-9 h-9 rounded-full bg-blue-100 text-siky-primary flex items-center justify-center mb-1.5 group-hover:bg-siky-primary group-hover:text-white transition">
                            <i class="fa-solid fa-laptop text-sm"></i>
                        </div>
                        <span class="home-cat-title text-slate-700 group-hover:text-siky-primary">Laptop</span>
                    </a>
                    <a href="#sec-manhinh" class="group flex flex-col items-center justify-center p-2 rounded-lg bg-slate-50 hover:bg-blue-50 border border-slate-200/80 hover:border-siky-primary transition text-center">
                        <div class="w-9 h-9 rounded-full bg-blue-100 text-siky-primary flex items-center justify-center mb-1.5 group-hover:bg-siky-primary group-hover:text-white transition">
                            <i class="fa-solid fa-tv text-sm"></i>
                        </div>
                        <span class="home-cat-title text-slate-700 group-hover:text-siky-primary">Màn Hình</span>
                    </a>
                    <a href="#sec-linhkien" class="group flex flex-col items-center justify-center p-2 rounded-lg bg-slate-50 hover:bg-blue-50 border border-slate-200/80 hover:border-siky-primary transition text-center">
                        <div class="w-9 h-9 rounded-full bg-blue-100 text-siky-primary flex items-center justify-center mb-1.5 group-hover:bg-siky-primary group-hover:text-white transition">
                            <i class="fa-solid fa-microchip text-sm"></i>
                        </div>
                        <span class="home-cat-title text-slate-700 group-hover:text-siky-primary">Linh Kiện PC</span>
                    </a>
                    <a href="#sec-linhkien" class="group flex flex-col items-center justify-center p-2 rounded-lg bg-slate-50 hover:bg-blue-50 border border-slate-200/80 hover:border-siky-primary transition text-center">
                        <div class="w-9 h-9 rounded-full bg-blue-100 text-siky-primary flex items-center justify-center mb-1.5 group-hover:bg-siky-primary group-hover:text-white transition">
                            <i class="fa-solid fa-headset text-sm"></i>
                        </div>
                        <span class="home-cat-title text-slate-700 group-hover:text-siky-primary">Phụ Kiện</span>
                    </a>
                    <a href="#sec-vanphong-dn" class="group flex flex-col items-center justify-center p-2 rounded-lg bg-slate-50 hover:bg-blue-50 border border-slate-200/80 hover:border-siky-primary transition text-center">
                        <div class="w-9 h-9 rounded-full bg-blue-100 text-siky-primary flex items-center justify-center mb-1.5 group-hover:bg-siky-primary group-hover:text-white transition">
                            <i class="fa-solid fa-print text-sm"></i>
                        </div>
                        <span class="home-cat-title text-slate-700 group-hover:text-siky-primary">Thiết Bị Văn Phòng</span>
                    </a>
                    <a href="#sec-vanphong-dn" class="group col-span-3 sm:col-span-2 md:col-span-2 lg:col-span-1 flex flex-col items-center justify-center p-2 rounded-lg bg-slate-50 hover:bg-blue-50 border border-slate-200/80 hover:border-siky-primary transition text-center">
                        <div class="w-9 h-9 rounded-full bg-blue-100 text-siky-primary flex items-center justify-center mb-1.5 group-hover:bg-siky-primary group-hover:text-white transition">
                            <i class="fa-brands fa-windows text-sm"></i>
                        </div>
                        <span class="home-cat-title text-slate-700 group-hover:text-siky-primary">Phần Mềm</span>
                    </a>
                </div>
            </div>
        </section>

        <!-- 3. SECTION SẢN PHẨM 1: CẤU HÌNH PC GAMING & ĐỒ HỌA THỰC TẾ TẠI SĨ KỲ (LẤY 10 ẢNH THỰC TẾ TRONG GOOGLE DRIVE CỦA BẠN)
             - Sản phẩm chia 2 cột trên điện thoại (grid-cols-2), 5 cột trên máy tính (lg:grid-cols-5)
             - Có % giảm giá góc trên bên trái giống Flatsome + giá gốc gạch ngang & giá giảm
             - Tên sản phẩm hiển thị đầy đủ không bị tràn hay thiếu chữ
             - Không để các nhãn dán dư thừa ở trang chủ -->
        <section id="sec-pc-gaming" class="flatsome-container">
            <div class="flatsome-section-header">
                <div class="flatsome-section-title">
                    <i class="fa-solid fa-fire"></i> CẤU HÌNH PC GAMING - ĐỒ HỌA - TRỌN BỘ THỰC TẾ TẠI SĨ KỲ
                </div>
                <div class="flex flex-wrap items-center gap-1.5 text-xs">
                    <a href="#sec-pc-dohoa" class="px-2.5 py-1 rounded bg-slate-100 hover:bg-siky-primary hover:text-white text-slate-700 font-medium transition whitespace-nowrap">PC Gaming Intel</a>
                    <a href="#sec-pc-dohoa" class="px-2.5 py-1 rounded bg-slate-100 hover:bg-siky-primary hover:text-white text-slate-700 font-medium transition whitespace-nowrap">PC Gaming AMD</a>
                    <a href="#sec-pc-dohoa" class="px-2.5 py-1 rounded bg-slate-100 hover:bg-siky-primary hover:text-white text-slate-700 font-medium transition whitespace-nowrap">PC Đồ Họa Render</a>
                    <a href="#form-bao-gia" class="px-2.5 py-1 rounded bg-blue-50 text-siky-primary font-semibold hover:underline whitespace-nowrap">Xem tất cả <i class="fa-solid fa-angle-right text-[10px]"></i></a>
                </div>
            </div>

            <!-- Lưới 10 sản phẩm sử dụng trực tiếp 10 ảnh thực tế từ Google Drive -->
            <div id="grid-drive-products" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-2.5 sm:gap-3.5">

                <!-- Sản phẩm thực tế Drive #1: 1y_ks82EgPIdXuaOtmPkjmgjxqp1W6TTj -->
                <article class="flatsome-product-box product-searchable">
                    <div class="flatsome-Discount-badge">-10%</div>
                    <div class="product-img-wrap">
                        <img
                            src="https://drive.google.com/thumbnail?id=1y_ks82EgPIdXuaOtmPkjmgjxqp1W6TTj&sz=w700"
                            data-drive-id="1y_ks82EgPIdXuaOtmPkjmgjxqp1W6TTj"
                            alt="PC Gaming Intel Core i5 12400F | RAM 16GB | SSD 512GB NVMe | RTX 3060 12GB"
                            loading="lazy"
                            onerror="handleDriveImgError(this, 'PC Gaming i5 12400F')"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] uppercase text-slate-400 font-semibold mb-1">PC GAMING</div>
                            <h3 class="product-full-title">
                                PC Gaming Intel Core i5 12400F | RAM 16GB | SSD 512GB NVMe | VGA RTX 3060 12GB GDDR6
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <del class="text-[11px] text-slate-400">18.990.000 ₫</del>
                                <ins class="text-xs sm:text-sm font-extrabold text-siky-sale no-underline">16.990.000 ₫</ins>
                            </div>
                            <div class="text-[11px] text-slate-500 mt-0.5">Bảo hành: 36 tháng</div>
                            <button type="button" onclick="openQuoteModal('PC Gaming Intel Core i5 12400F | RAM 16GB | SSD 512GB | RTX 3060 12GB')" class="mt-2 w-full py-1.5 px-2 rounded bg-siky-light hover:bg-siky-primary text-siky-primary hover:text-white text-xs font-bold transition">
                                Đặt mua / Tư vấn
                            </button>
                        </div>
                    </div>
                </article>

                <!-- Sản phẩm thực tế Drive #2: 1h_Wt-hpWM3VerZ6nyJMvI4S7SDXhik3c -->
                <article class="flatsome-product-box product-searchable">
                    <div class="flatsome-Discount-badge">-12%</div>
                    <div class="product-img-wrap">
                        <img
                            src="https://drive.google.com/thumbnail?id=1h_Wt-hpWM3VerZ6nyJMvI4S7SDXhik3c&sz=w700"
                            data-drive-id="1h_Wt-hpWM3VerZ6nyJMvI4S7SDXhik3c"
                            alt="PC Gaming Đồ Họa Intel Core i5 14400F | RAM 32GB DDR5 | NVMe 500GB | RTX 4060 8GB"
                            loading="lazy"
                            onerror="handleDriveImgError(this, 'PC i5 14400F RTX 4060')"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] uppercase text-slate-400 font-semibold mb-1">PC ĐỒ HỌA – WORKSTATION</div>
                            <h3 class="product-full-title">
                                PC Gaming Đồ Họa Intel Core i5 14400F | RAM 32GB DDR5 | NVMe 500GB | RTX 4060 8GB
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <del class="text-[11px] text-slate-400">24.500.000 ₫</del>
                                <ins class="text-xs sm:text-sm font-extrabold text-siky-sale no-underline">21.590.000 ₫</ins>
                            </div>
                            <div class="text-[11px] text-slate-500 mt-0.5">Bảo hành: 36 tháng</div>
                            <button type="button" onclick="openQuoteModal('PC Gaming Đồ Họa Intel Core i5 14400F | RAM 32GB DDR5 | RTX 4060 8GB')" class="mt-2 w-full py-1.5 px-2 rounded bg-siky-light hover:bg-siky-primary text-siky-primary hover:text-white text-xs font-bold transition">
                                Đặt mua / Tư vấn
                            </button>
                        </div>
                    </div>
                </article>

                <!-- Sản phẩm thực tế Drive #3: 1Ar6Jl6Qw5lVd6QpjwIyv9dGnoUcFafwh -->
                <article class="flatsome-product-box product-searchable">
                    <div class="flatsome-Discount-badge">-14%</div>
                    <div class="product-img-wrap">
                        <img
                            src="https://drive.google.com/thumbnail?id=1Ar6Jl6Qw5lVd6QpjwIyv9dGnoUcFafwh&sz=w700"
                            data-drive-id="1Ar6Jl6Qw5lVd6QpjwIyv9dGnoUcFafwh"
                            alt="PC Gaming AMD Ryzen 5 7500F | RAM 32GB DDR5 | SSD 500GB NVMe | RTX 3060 12GB"
                            loading="lazy"
                            onerror="handleDriveImgError(this, 'PC Ryzen 5 7500F')"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] uppercase text-slate-400 font-semibold mb-1">PC GAMING</div>
                            <h3 class="product-full-title">
                                PC Gaming AMD Ryzen 5 7500F | RAM 32GB DDR5 | SSD 500GB NVMe | VGA RTX 3060 12GB
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <del class="text-[11px] text-slate-400">22.900.000 ₫</del>
                                <ins class="text-xs sm:text-sm font-extrabold text-siky-sale no-underline">19.690.000 ₫</ins>
                            </div>
                            <div class="text-[11px] text-slate-500 mt-0.5">Bảo hành: 36 tháng</div>
                            <button type="button" onclick="openQuoteModal('PC Gaming AMD Ryzen 5 7500F | RAM 32GB DDR5 | RTX 3060 12GB')" class="mt-2 w-full py-1.5 px-2 rounded bg-siky-light hover:bg-siky-primary text-siky-primary hover:text-white text-xs font-bold transition">
                                Đặt mua / Tư vấn
                            </button>
                        </div>
                    </div>
                </article>

                <!-- Sản phẩm thực tế Drive #4: 1rszHhZm-mFf8i-tXxO3WsoJcgcBjeqat -->
                <article class="flatsome-product-box product-searchable">
                    <div class="flatsome-Discount-badge">-11%</div>
                    <div class="product-img-wrap">
                        <img
                            src="https://drive.google.com/thumbnail?id=1rszHhZm-mFf8i-tXxO3WsoJcgcBjeqat&sz=w700"
                            data-drive-id="1rszHhZm-mFf8i-tXxO3WsoJcgcBjeqat"
                            alt="PC Gaming Intel Core i5 13400F | RAM 16GB | NVMe 500GB | VGA RTX 3050 6GB GDDR6"
                            loading="lazy"
                            onerror="handleDriveImgError(this, 'PC i5 13400F RTX 3050')"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] uppercase text-slate-400 font-semibold mb-1">PC GAMING</div>
                            <h3 class="product-full-title">
                                PC Gaming Intel Core i5 13400F | RAM 16GB | NVMe 500GB | VGA RTX 3050 6GB GDDR6
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <del class="text-[11px] text-slate-400">16.900.000 ₫</del>
                                <ins class="text-xs sm:text-sm font-extrabold text-siky-sale no-underline">14.990.000 ₫</ins>
                            </div>
                            <div class="text-[11px] text-slate-500 mt-0.5">Bảo hành: 36 tháng</div>
                            <button type="button" onclick="openQuoteModal('PC Gaming Intel Core i5 13400F | RAM 16GB | NVMe 500GB | RTX 3050 6GB')" class="mt-2 w-full py-1.5 px-2 rounded bg-siky-light hover:bg-siky-primary text-siky-primary hover:text-white text-xs font-bold transition">
                                Đặt mua / Tư vấn
                            </button>
                        </div>
                    </div>
                </article>

                <!-- Sản phẩm thực tế Drive #5: 1qNVKyBdrJFcKIWjXwOYCl6O71A-wnPyf -->
                <article class="flatsome-product-box product-searchable">
                    <div class="flatsome-Discount-badge">-17%</div>
                    <div class="product-img-wrap">
                        <img
                            src="https://drive.google.com/thumbnail?id=1qNVKyBdrJFcKIWjXwOYCl6O71A-wnPyf&sz=w700"
                            data-drive-id="1qNVKyBdrJFcKIWjXwOYCl6O71A-wnPyf"
                            alt="Trọn Bộ PC Văn Phòng & Học Tập Core i5 | RAM 16GB | SSD 256GB NVMe Kèm Màn Hình IPS 24 Inch"
                            loading="lazy"
                            onerror="handleDriveImgError(this, 'Trọn Bộ PC Kèm Màn')"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] uppercase text-slate-400 font-semibold mb-1">PC VĂN PHÒNG</div>
                            <h3 class="product-full-title">
                                Trọn Bộ PC Văn Phòng Core i5 | RAM 16GB | SSD 256GB NVMe Kèm Màn Hình IPS 24 Inch 100Hz
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <del class="text-[11px] text-slate-400">10.500.000 ₫</del>
                                <ins class="text-xs sm:text-sm font-extrabold text-siky-sale no-underline">8.690.000 ₫</ins>
                            </div>
                            <div class="text-[11px] text-slate-500 mt-0.5">Bảo hành: 36 tháng</div>
                            <button type="button" onclick="openQuoteModal('Trọn Bộ PC Văn Phòng Core i5 | RAM 16GB | SSD 256GB Kèm Màn Hình 24 Inch')" class="mt-2 w-full py-1.5 px-2 rounded bg-siky-light hover:bg-siky-primary text-siky-primary hover:text-white text-xs font-bold transition">
                                Đặt mua / Tư vấn
                            </button>
                        </div>
                    </div>
                </article>

                <!-- Sản phẩm thực tế Drive #6: 1B2pUD7gMFD2cy7yIkl6LTt-nXSMCAvHn -->
                <article class="flatsome-product-box product-searchable">
                    <div class="flatsome-Discount-badge">-15%</div>
                    <div class="product-img-wrap">
                        <img
                            src="https://drive.google.com/thumbnail?id=1B2pUD7gMFD2cy7yIkl6LTt-nXSMCAvHn&sz=w700"
                            data-drive-id="1B2pUD7gMFD2cy7yIkl6LTt-nXSMCAvHn"
                            alt="PC Đồ Họa Workstation Intel Core i7 14700K | RAM 32GB DDR5 | SSD 1TB NVMe | RTX 4060Ti 16GB"
                            loading="lazy"
                            onerror="handleDriveImgError(this, 'PC Workstation i7')"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] uppercase text-slate-400 font-semibold mb-1">PC ĐỒ HỌA – WORKSTATION</div>
                            <h3 class="product-full-title">
                                PC Đồ Họa Workstation Intel Core i7 14700K | RAM 32GB DDR5 | SSD 1TB NVMe | RTX 4060Ti 16GB
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <del class="text-[11px] text-slate-400">38.900.000 ₫</del>
                                <ins class="text-xs sm:text-sm font-extrabold text-siky-sale no-underline">32.990.000 ₫</ins>
                            </div>
                            <div class="text-[11px] text-slate-500 mt-0.5">Bảo hành: 36 tháng</div>
                            <button type="button" onclick="openQuoteModal('PC Đồ Họa Workstation Intel Core i7 14700K | 32GB DDR5 | 1TB | RTX 4060Ti 16GB')" class="mt-2 w-full py-1.5 px-2 rounded bg-siky-light hover:bg-siky-primary text-siky-primary hover:text-white text-xs font-bold transition">
                                Đặt mua / Tư vấn
                            </button>
                        </div>
                    </div>
                </article>

                <!-- Sản phẩm thực tế Drive #7: 1Cwo4ZBOIO7IuqKdyl5mZVV3mmkB0KGY7 -->
                <article class="flatsome-product-box product-searchable">
                    <div class="flatsome-Discount-badge">-13%</div>
                    <div class="product-img-wrap">
                        <img
                            src="https://drive.google.com/thumbnail?id=1Cwo4ZBOIO7IuqKdyl5mZVV3mmkB0KGY7&sz=w700"
                            data-drive-id="1Cwo4ZBOIO7IuqKdyl5mZVV3mmkB0KGY7"
                            alt="PC Gaming Bể Cá White Edition Ryzen 5 5600X | RAM 16GB RGB | SSD 512GB | VGA RTX 3060"
                            loading="lazy"
                            onerror="handleDriveImgError(this, 'PC Gaming White RGB')"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] uppercase text-slate-400 font-semibold mb-1">PC GAMING</div>
                            <h3 class="product-full-title">
                                PC Gaming Bể Cá White Edition Ryzen 5 5600X | RAM 16GB RGB | SSD 512GB | VGA RTX 3060
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <del class="text-[11px] text-slate-400">17.900.000 ₫</del>
                                <ins class="text-xs sm:text-sm font-extrabold text-siky-sale no-underline">15.590.000 ₫</ins>
                            </div>
                            <div class="text-[11px] text-slate-500 mt-0.5">Bảo hành: 36 tháng</div>
                            <button type="button" onclick="openQuoteModal('PC Gaming Bể Cá White Edition Ryzen 5 5600X | RAM 16GB | RTX 3060')" class="mt-2 w-full py-1.5 px-2 rounded bg-siky-light hover:bg-siky-primary text-siky-primary hover:text-white text-xs font-bold transition">
                                Đặt mua / Tư vấn
                            </button>
                        </div>
                    </div>
                </article>

                <!-- Sản phẩm thực tế Drive #8: 1lrRSds5tvQb8Bg6aYl8P7toTYloOEzkj -->
                <article class="flatsome-product-box product-searchable">
                    <div class="flatsome-Discount-badge">-18%</div>
                    <div class="product-img-wrap">
                        <img
                            src="https://drive.google.com/thumbnail?id=1lrRSds5tvQb8Bg6aYl8P7toTYloOEzkj&sz=w700"
                            data-drive-id="1lrRSds5tvQb8Bg6aYl8P7toTYloOEzkj"
                            alt="PC Văn Phòng AMD Ryzen 5 5600GT | RAM 16GB | SSD 256GB NVMe | Radeon Vega 7 Graphics"
                            loading="lazy"
                            onerror="handleDriveImgError(this, 'PC Ryzen 5 5600GT')"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] uppercase text-slate-400 font-semibold mb-1">PC VĂN PHÒNG</div>
                            <h3 class="product-full-title">
                                PC Văn Phòng AMD Ryzen 5 5600GT | RAM 16GB | SSD 256GB NVMe | Radeon Vega 7 Graphics
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <del class="text-[11px] text-slate-400">9.200.000 ₫</del>
                                <ins class="text-xs sm:text-sm font-extrabold text-siky-sale no-underline">7.590.000 ₫</ins>
                            </div>
                            <div class="text-[11px] text-slate-500 mt-0.5">Bảo hành: 36 tháng</div>
                            <button type="button" onclick="openQuoteModal('PC Văn Phòng AMD Ryzen 5 5600GT | RAM 16GB | SSD 256GB NVMe')" class="mt-2 w-full py-1.5 px-2 rounded bg-siky-light hover:bg-siky-primary text-siky-primary hover:text-white text-xs font-bold transition">
                                Đặt mua / Tư vấn
                            </button>
                        </div>
                    </div>
                </article>

                <!-- Sản phẩm thực tế Drive #9: 1l6Cit0andz8u94BCMJyCN_wce6JkLTBj -->
                <article class="flatsome-product-box product-searchable">
                    <div class="flatsome-Discount-badge">-16%</div>
                    <div class="product-img-wrap">
                        <img
                            src="https://drive.google.com/thumbnail?id=1l6Cit0andz8u94BCMJyCN_wce6JkLTBj&sz=w700"
                            data-drive-id="1l6Cit0andz8u94BCMJyCN_wce6JkLTBj"
                            alt="Màn Hình Gaming ViewSonic VX2758-2K-PRO 27 Inch IPS 2K 180Hz 1ms Chính Hãng"
                            loading="lazy"
                            onerror="handleDriveImgError(this, 'Màn Hình 27 Inch 2K')"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] uppercase text-slate-400 font-semibold mb-1">MÀN HÌNH MÁY TÍNH</div>
                            <h3 class="product-full-title">
                                Màn Hình Gaming ViewSonic 27 Inch IPS 2K 180Hz 1ms Chuyên Game & Đồ Họa Chính Hãng
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <del class="text-[11px] text-slate-400">6.290.000 ₫</del>
                                <ins class="text-xs sm:text-sm font-extrabold text-siky-sale no-underline">5.290.000 ₫</ins>
                            </div>
                            <div class="text-[11px] text-slate-500 mt-0.5">Bảo hành: 36 tháng</div>
                            <button type="button" onclick="openQuoteModal('Màn Hình Gaming ViewSonic 27 Inch IPS 2K 180Hz 1ms')" class="mt-2 w-full py-1.5 px-2 rounded bg-siky-light hover:bg-siky-primary text-siky-primary hover:text-white text-xs font-bold transition">
                                Đặt mua / Tư vấn
                            </button>
                        </div>
                    </div>
                </article>

                <!-- Sản phẩm thực tế Drive #10: 1QNtowQmrjds3zWDNdDCsVsAEdjxr0T1o -->
                <article class="flatsome-product-box product-searchable">
                    <div class="flatsome-Discount-badge">-11%</div>
                    <div class="product-img-wrap">
                        <img
                            src="https://drive.google.com/thumbnail?id=1QNtowQmrjds3zWDNdDCsVsAEdjxr0T1o&sz=w700"
                            data-drive-id="1QNtowQmrjds3zWDNdDCsVsAEdjxr0T1o"
                            alt="Combo PC Gaming & Livestream Core i5 12400F | 16GB | SSD 512GB | Kèm Màn Hình Gaming 144Hz"
                            loading="lazy"
                            onerror="handleDriveImgError(this, 'Combo PC + Màn 144Hz')"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] uppercase text-slate-400 font-semibold mb-1">PC LIVE – STREAM</div>
                            <h3 class="product-full-title">
                                Combo PC Gaming & Livestream Core i5 12400F | 16GB | SSD 512GB | Kèm Màn Hình 24 Inch 144Hz
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <del class="text-[11px] text-slate-400">19.900.000 ₫</del>
                                <ins class="text-xs sm:text-sm font-extrabold text-siky-sale no-underline">17.690.000 ₫</ins>
                            </div>
                            <div class="text-[11px] text-slate-500 mt-0.5">Bảo hành: 36 tháng</div>
                            <button type="button" onclick="openQuoteModal('Combo PC Gaming & Livestream Core i5 12400F Kèm Màn Hình 24 Inch 144Hz')" class="mt-2 w-full py-1.5 px-2 rounded bg-siky-light hover:bg-siky-primary text-siky-primary hover:text-white text-xs font-bold transition">
                                Đặt mua / Tư vấn
                            </button>
                        </div>
                    </div>
                </article>

            </div>
        </section>

        <!-- 4. SECTION SẢN PHẨM 2: PC ĐỒ HỌA - WORKSTATION & PC VĂN PHÒNG / MÁY BỘ -->
        <section id="sec-pc-dohoa" class="flatsome-container">
            <div id="sec-pc-vanphong" class="flatsome-section-header">
                <div class="flatsome-section-title">
                    <i class="fa-solid fa-computer"></i> PC ĐỒ HỌA WORKSTATION & PC VĂN PHÒNG - MÁY BỘ
                </div>
                <div class="flex flex-wrap items-center gap-1.5 text-xs">
                    <a href="#form-bao-gia" class="px-2.5 py-1 rounded bg-slate-100 hover:bg-siky-primary hover:text-white text-slate-700 font-medium transition whitespace-nowrap">PC Dựng Phim / Render</a>
                    <a href="#form-bao-gia" class="px-2.5 py-1 rounded bg-slate-100 hover:bg-siky-primary hover:text-white text-slate-700 font-medium transition whitespace-nowrap">PC Kế Toán / Doanh Nghiệp</a>
                    <a href="#form-bao-gia" class="px-2.5 py-1 rounded bg-slate-100 hover:bg-siky-primary hover:text-white text-slate-700 font-medium transition whitespace-nowrap">Máy Bộ Dell / HP / Asus</a>
                </div>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-2.5 sm:gap-3.5">
                <!-- SP 2.1 -->
                <article class="flatsome-product-box product-searchable">
                    <div class="flatsome-Discount-badge">-10%</div>
                    <div class="product-img-wrap">
                        <img src="https://drive.google.com/thumbnail?id=1B2pUD7gMFD2cy7yIkl6LTt-nXSMCAvHn&sz=w700" data-drive-id="1B2pUD7gMFD2cy7yIkl6LTt-nXSMCAvHn" alt="PC Đồ Họa Kiến Trúc Core Ultra 7 265K" loading="lazy" onerror="handleDriveImgError(this, 'PC Core Ultra 7')">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] uppercase text-slate-400 font-semibold mb-1">PC ĐỒ HỌA – WORKSTATION</div>
                            <h3 class="product-full-title">
                                PC Đồ Họa Intel Core Ultra 7 265K | 32GB DDR5 | NVMe 1TB | NVIDIA RTX 5060Ti 16GB GDDR7
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <del class="text-[11px] text-slate-400">49.900.000 ₫</del>
                                <ins class="text-xs sm:text-sm font-extrabold text-siky-sale no-underline">44.900.000 ₫</ins>
                            </div>
                            <div class="text-[11px] text-slate-500 mt-0.5">Bảo hành: 36 tháng</div>
                            <button type="button" onclick="openQuoteModal('PC Đồ Họa Intel Core Ultra 7 265K | 32GB DDR5 | NVMe 1TB | RTX 5060Ti 16GB')" class="mt-2 w-full py-1.5 px-2 rounded bg-siky-light hover:bg-siky-primary text-siky-primary hover:text-white text-xs font-bold transition">
                                Đặt mua / Tư vấn
                            </button>
                        </div>
                    </div>
                </article>

                <!-- SP 2.2 -->
                <article class="flatsome-product-box product-searchable">
                    <div class="flatsome-Discount-badge">-17%</div>
                    <div class="product-img-wrap">
                        <img src="https://drive.google.com/thumbnail?id=1lrRSds5tvQb8Bg6aYl8P7toTYloOEzkj&sz=w700" data-drive-id="1lrRSds5tvQb8Bg6aYl8P7toTYloOEzkj" alt="PC Văn Phòng Ryzen 5 3400G" loading="lazy" onerror="handleDriveImgError(this, 'PC Ryzen 5 3400G')">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] uppercase text-slate-400 font-semibold mb-1">PC VĂN PHÒNG</div>
                            <h3 class="product-full-title">
                                PC Văn Phòng Ryzen 5 3400G | RAM 16GB | NVMe 256GB | Vega Graphics 11 Kèm Màn Hình & Phím Chuột
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <del class="text-[11px] text-slate-400">11.990.000 ₫</del>
                                <ins class="text-xs sm:text-sm font-extrabold text-siky-sale no-underline">9.950.000 ₫</ins>
                            </div>
                            <div class="text-[11px] text-slate-500 mt-0.5">Bảo hành: 36 tháng</div>
                            <button type="button" onclick="openQuoteModal('PC Văn Phòng Ryzen 5 3400G | 16GB | NVMe 256GB Kèm Màn Hình & Phím Chuột')" class="mt-2 w-full py-1.5 px-2 rounded bg-siky-light hover:bg-siky-primary text-siky-primary hover:text-white text-xs font-bold transition">
                                Đặt mua / Tư vấn
                            </button>
                        </div>
                    </div>
                </article>

                <!-- SP 2.3 -->
                <article class="flatsome-product-box product-searchable">
                    <div class="flatsome-Discount-badge">-15%</div>
                    <div class="product-img-wrap">
                        <img src="https://drive.google.com/thumbnail?id=1qNVKyBdrJFcKIWjXwOYCl6O71A-wnPyf&sz=w700" data-drive-id="1qNVKyBdrJFcKIWjXwOYCl6O71A-wnPyf" alt="PC Kế Toán Doanh Nghiệp Core i3 12100" loading="lazy" onerror="handleDriveImgError(this, 'PC Văn Phòng i3 12100')">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] uppercase text-slate-400 font-semibold mb-1">PC DOANH NGHIỆP</div>
                            <h3 class="product-full-title">
                                PC Văn Phòng Kế Toán Intel Core i3 12100 | RAM 8GB DDR4 | SSD 256GB NVMe | Nguồn Công Suất Thực
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <del class="text-[11px] text-slate-400">6.990.000 ₫</del>
                                <ins class="text-xs sm:text-sm font-extrabold text-siky-sale no-underline">5.950.000 ₫</ins>
                            </div>
                            <div class="text-[11px] text-slate-500 mt-0.5">Bảo hành: 36 tháng</div>
                            <button type="button" onclick="openQuoteModal('PC Văn Phòng Kế Toán Intel Core i3 12100 | RAM 8GB | SSD 256GB')" class="mt-2 w-full py-1.5 px-2 rounded bg-siky-light hover:bg-siky-primary text-siky-primary hover:text-white text-xs font-bold transition">
                                Đặt mua / Tư vấn
                            </button>
                        </div>
                    </div>
                </article>

                <!-- SP 2.4 -->
                <article class="flatsome-product-box product-searchable">
                    <div class="flatsome-Discount-badge">-9%</div>
                    <div class="product-img-wrap">
                        <img src="https://drive.google.com/thumbnail?id=1h_Wt-hpWM3VerZ6nyJMvI4S7SDXhik3c&sz=w700" data-drive-id="1h_Wt-hpWM3VerZ6nyJMvI4S7SDXhik3c" alt="PC Giả Lập MMO Dual Xeon" loading="lazy" onerror="handleDriveImgError(this, 'PC Giả Lập MMO')">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] uppercase text-slate-400 font-semibold mb-1">PC GIẢ LẬP – MMO</div>
                            <h3 class="product-full-title">
                                PC Giả Lập Đa Nhiệm & Render 3D Intel Core i7 13700F | RAM 64GB DDR5 | SSD 1TB NVMe | RTX 4060 8GB
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <del class="text-[11px] text-slate-400">31.500.000 ₫</del>
                                <ins class="text-xs sm:text-sm font-extrabold text-siky-sale no-underline">28.690.000 ₫</ins>
                            </div>
                            <div class="text-[11px] text-slate-500 mt-0.5">Bảo hành: 36 tháng</div>
                            <button type="button" onclick="openQuoteModal('PC Giả Lập & Render 3D Core i7 13700F | RAM 64GB | RTX 4060')" class="mt-2 w-full py-1.5 px-2 rounded bg-siky-light hover:bg-siky-primary text-siky-primary hover:text-white text-xs font-bold transition">
                                Đặt mua / Tư vấn
                            </button>
                        </div>
                    </div>
                </article>

                <!-- SP 2.5 -->
                <article class="flatsome-product-box product-searchable">
                    <div class="flatsome-Discount-badge">-11%</div>
                    <div class="product-img-wrap">
                        <img src="https://drive.google.com/thumbnail?id=1rszHhZm-mFf8i-tXxO3WsoJcgcBjeqat&sz=w700" data-drive-id="1rszHhZm-mFf8i-tXxO3WsoJcgcBjeqat" alt="Máy Bộ Đồng Bộ Dell OptiPlex" loading="lazy" onerror="handleDriveImgError(this, 'Máy Bộ Dell')">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] uppercase text-slate-400 font-semibold mb-1">MÁY BỘ – MÁY CHỦ</div>
                            <h3 class="product-full-title">
                                Máy Bộ Dell Vostro / OptiPlex Core i5 12400 | RAM 16GB | SSD 512GB NVMe | Win 11 Bản Quyền
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <del class="text-[11px] text-slate-400">13.990.000 ₫</del>
                                <ins class="text-xs sm:text-sm font-extrabold text-siky-sale no-underline">12.450.000 ₫</ins>
                            </div>
                            <div class="text-[11px] text-slate-500 mt-0.5">Bảo hành: 36 tháng</div>
                            <button type="button" onclick="openQuoteModal('Máy Bộ Dell Vostro / OptiPlex Core i5 12400 | RAM 16GB | SSD 512GB')" class="mt-2 w-full py-1.5 px-2 rounded bg-siky-light hover:bg-siky-primary text-siky-primary hover:text-white text-xs font-bold transition">
                                Đặt mua / Tư vấn
                            </button>
                        </div>
                    </div>
                </article>
            </div>
        </section>

        <!-- 5. SECTION SẢN PHẨM 3: LAPTOP CHÍNH HÃNG & MÀN HÌNH MÁY TÍNH & LINH KIỆN VGA -->
        <section id="sec-laptop" class="flatsome-container">
            <div id="sec-manhinh" class="flatsome-section-header">
                <div id="sec-linhkien" class="flatsome-section-title">
                    <i class="fa-solid fa-laptop"></i> LAPTOP CHÍNH HÃNG - MÀN HÌNH MÁY TÍNH - CARD ĐỒ HỌA VGA
                </div>
                <div class="flex flex-wrap items-center gap-1.5 text-xs">
                    <a href="#form-bao-gia" class="px-2.5 py-1 rounded bg-slate-100 hover:bg-siky-primary hover:text-white text-slate-700 font-medium transition whitespace-nowrap">Laptop Gaming / Văn Phòng</a>
                    <a href="#form-bao-gia" class="px-2.5 py-1 rounded bg-slate-100 hover:bg-siky-primary hover:text-white text-slate-700 font-medium transition whitespace-nowrap">Màn Hình 100Hz - 320Hz</a>
                    <a href="#form-bao-gia" class="px-2.5 py-1 rounded bg-slate-100 hover:bg-siky-primary hover:text-white text-slate-700 font-medium transition whitespace-nowrap">VGA RTX / Radeon</a>
                </div>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-2.5 sm:gap-3.5">
                <!-- SP 3.1 -->
                <article class="flatsome-product-box product-searchable">
                    <div class="flatsome-Discount-badge">-10%</div>
                    <div class="product-img-wrap">
                        <img src="https://drive.google.com/thumbnail?id=1QNtowQmrjds3zWDNdDCsVsAEdjxr0T1o&sz=w700" data-drive-id="1QNtowQmrjds3zWDNdDCsVsAEdjxr0T1o" alt="Laptop Lenovo Gaming LOQ 15IAX9E" loading="lazy" onerror="handleDriveImgError(this, 'Laptop Lenovo LOQ')">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] uppercase text-slate-400 font-semibold mb-1">LAPTOP GAMING</div>
                            <h3 class="product-full-title">
                                Laptop Lenovo Gaming LOQ 15IAX9E (Core i5 12450HX | RAM 16GB | SSD 512GB | RTX 3050 6GB | 15.6 Inch FHD 144Hz)
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <del class="text-[11px] text-slate-400">22.990.000 ₫</del>
                                <ins class="text-xs sm:text-sm font-extrabold text-siky-sale no-underline">20.690.000 ₫</ins>
                            </div>
                            <div class="text-[11px] text-slate-500 mt-0.5">Bảo hành: 24 tháng</div>
                            <button type="button" onclick="openQuoteModal('Laptop Lenovo Gaming LOQ 15IAX9E i5 12450HX | 16GB | RTX 3050 6GB')" class="mt-2 w-full py-1.5 px-2 rounded bg-siky-light hover:bg-siky-primary text-siky-primary hover:text-white text-xs font-bold transition">
                                Đặt mua / Tư vấn
                            </button>
                        </div>
                    </div>
                </article>

                <!-- SP 3.2 -->
                <article class="flatsome-product-box product-searchable">
                    <div class="flatsome-Discount-badge">-19%</div>
                    <div class="product-img-wrap">
                        <img src="https://drive.google.com/thumbnail?id=1l6Cit0andz8u94BCMJyCN_wce6JkLTBj&sz=w700" data-drive-id="1l6Cit0andz8u94BCMJyCN_wce6JkLTBj" alt="Màn Hình ViewSonic VA2432-H-2" loading="lazy" onerror="handleDriveImgError(this, 'ViewSonic 24 Inch')">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] uppercase text-slate-400 font-semibold mb-1">MÀN HÌNH VĂN PHÒNG</div>
                            <h3 class="product-full-title">
                                Màn Hình ViewSonic VA2432-H-2 (23.8 Inch / Full HD / SuperClear IPS / 100Hz / 1ms / Viền Mỏng)
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <del class="text-[11px] text-slate-400">2.450.000 ₫</del>
                                <ins class="text-xs sm:text-sm font-extrabold text-siky-sale no-underline">1.990.000 ₫</ins>
                            </div>
                            <div class="text-[11px] text-slate-500 mt-0.5">Bảo hành: 36 tháng</div>
                            <button type="button" onclick="openQuoteModal('Màn Hình ViewSonic VA2432-H-2 23.8 Inch IPS 100Hz')" class="mt-2 w-full py-1.5 px-2 rounded bg-siky-light hover:bg-siky-primary text-siky-primary hover:text-white text-xs font-bold transition">
                                Đặt mua / Tư vấn
                            </button>
                        </div>
                    </div>
                </article>

                <!-- SP 3.3 -->
                <article class="flatsome-product-box product-searchable">
                    <div class="flatsome-Discount-badge">-15%</div>
                    <div class="product-img-wrap">
                        <img src="https://drive.google.com/thumbnail?id=1qNVKyBdrJFcKIWjXwOYCl6O71A-wnPyf&sz=w700" data-drive-id="1qNVKyBdrJFcKIWjXwOYCl6O71A-wnPyf" alt="Màn Hình ASUS VY249HG2 144Hz" loading="lazy" onerror="handleDriveImgError(this, 'ASUS 24 Inch 144Hz')">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] uppercase text-slate-400 font-semibold mb-1">MÀN HÌNH GAMING</div>
                            <h3 class="product-full-title">
                                Màn Hình Gaming ASUS VY249HG2 (23.8 Inch / IPS / Full HD / 144Hz / 1ms / Bảo Vệ Mắt Eye Care Plus)
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <del class="text-[11px] text-slate-400">2.700.000 ₫</del>
                                <ins class="text-xs sm:text-sm font-extrabold text-siky-sale no-underline">2.290.000 ₫</ins>
                            </div>
                            <div class="text-[11px] text-slate-500 mt-0.5">Bảo hành: 36 tháng</div>
                            <button type="button" onclick="openQuoteModal('Màn Hình Gaming ASUS VY249HG2 23.8 Inch IPS 144Hz')" class="mt-2 w-full py-1.5 px-2 rounded bg-siky-light hover:bg-siky-primary text-siky-primary hover:text-white text-xs font-bold transition">
                                Đặt mua / Tư vấn
                            </button>
                        </div>
                    </div>
                </article>

                <!-- SP 3.4 -->
                <article class="flatsome-product-box product-searchable">
                    <div class="flatsome-Discount-badge">-8%</div>
                    <div class="product-img-wrap">
                        <img src="https://drive.google.com/thumbnail?id=1Cwo4ZBOIO7IuqKdyl5mZVV3mmkB0KGY7&sz=w700" data-drive-id="1Cwo4ZBOIO7IuqKdyl5mZVV3mmkB0KGY7" alt="Card Màn Hình GeForce RTX 5060 8GB" loading="lazy" onerror="handleDriveImgError(this, 'VGA RTX 5060 8GB')">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] uppercase text-slate-400 font-semibold mb-1">VGA – CARD ĐỒ HỌA</div>
                            <h3 class="product-full-title">
                                Card Màn Hình ASUS / PNY GeForce RTX 4060 & RTX 5060 8GB OC Dual Fan Chính Hãng
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <del class="text-[11px] text-slate-400">9.290.000 ₫</del>
                                <ins class="text-xs sm:text-sm font-extrabold text-siky-sale no-underline">8.550.000 ₫</ins>
                            </div>
                            <div class="text-[11px] text-slate-500 mt-0.5">Bảo hành: 36 tháng</div>
                            <button type="button" onclick="openQuoteModal('Card Màn Hình GeForce RTX 4060 / RTX 5060 8GB OC')" class="mt-2 w-full py-1.5 px-2 rounded bg-siky-light hover:bg-siky-primary text-siky-primary hover:text-white text-xs font-bold transition">
                                Đặt mua / Tư vấn
                            </button>
                        </div>
                    </div>
                </article>

                <!-- SP 3.5 -->
                <article id="sec-vanphong-dn" class="flatsome-product-box product-searchable">
                    <div class="flatsome-Discount-badge">-14%</div>
                    <div class="product-img-wrap">
                        <img src="https://drive.google.com/thumbnail?id=1Ar6Jl6Qw5lVd6QpjwIyv9dGnoUcFafwh&sz=w700" data-drive-id="1Ar6Jl6Qw5lVd6QpjwIyv9dGnoUcFafwh" alt="Combo Nâng Cấp Linh Kiện & Thiết Bị Văn Phòng" loading="lazy" onerror="handleDriveImgError(this, 'Linh Kiện & Thiết Bị')">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[10.5px] uppercase text-slate-400 font-semibold mb-1">LINH KIỆN & THIẾT BỊ</div>
                            <h3 class="product-full-title">
                                Combo Nâng Cấp RAM DDR4/DDR5 16GB + Ổ Cứng SSD NVMe Gen4 512GB Chính Hãng Tốc Độ Cao
                            </h3>
                        </div>
                        <div class="pt-2 border-t border-slate-100 mt-1">
                            <div class="flex flex-wrap items-baseline gap-1.5">
                                <del class="text-[11px] text-slate-400">2.450.000 ₫</del>
                                <ins class="text-xs sm:text-sm font-extrabold text-siky-sale no-underline">2.090.000 ₫</ins>
                            </div>
                            <div class="text-[11px] text-slate-500 mt-0.5">Bảo hành: 36 tháng</div>
                            <button type="button" onclick="openQuoteModal('Combo Nâng Cấp RAM 16GB + SSD NVMe 512GB')" class="mt-2 w-full py-1.5 px-2 rounded bg-siky-light hover:bg-siky-primary text-siky-primary hover:text-white text-xs font-bold transition">
                                Đặt mua / Tư vấn
                            </button>
                        </div>
                    </div>
                </article>
            </div>
        </section>

        <!-- 6. FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ (TƯ VẤN BUILD PC & BÁO GIÁ THIẾT BỊ NHANH) -->
        <section id="form-bao-gia" class="flatsome-container">
            <div class="bg-white rounded-xl border border-slate-200 shadow-xs overflow-hidden">
                <div class="grid grid-cols-1 lg:grid-cols-12">
                    <!-- Cột thông tin cam kết của Máy Tính Sĩ Kỳ -->
                    <div class="lg:col-span-5 bg-gradient-to-br from-siky-dark to-siky-primary text-white p-5 sm:p-6 flex flex-col justify-between">
                        <div class="space-y-3">
                            <span class="inline-block px-2.5 py-1 rounded bg-white/15 text-cyan-200 text-xs font-bold uppercase">
                                Tư Vấn Cấu Hình & Báo Giá Sỉ Lẻ
                            </span>
                            <h2 class="text-lg sm:text-xl font-extrabold leading-snug">
                                GỬI YÊU CẦU TƯ VẤN BUILD PC & NHẬN BÁO GIÁ TỐT NHẤT TẠI SĨ KỲ COMPUTER
                            </h2>
                            <p class="text-xs sm:text-sm text-blue-100 leading-relaxed">
                                Đội ngũ kỹ thuật viên tại <strong>Máy Tính Sĩ Kỳ</strong> sẽ lên cấu hình tối ưu theo đúng nhu cầu chơi Game, làm Đồ họa 3D/Render hoặc trang bị dàn máy văn phòng, trường học, doanh nghiệp tại Đà Nẵng.
                            </p>
                            <ul class="space-y-2 text-xs sm:text-sm text-blue-50 pt-1">
                                <li class="flex items-start gap-2">
                                    <i class="fa-solid fa-circle-check text-cyan-300 mt-0.5"></i>
                                    <span>Linh kiện chính hãng mới 100%, đầy đủ hóa đơn VAT công ty.</span>
                                </li>
                                <li class="flex items-start gap-2">
                                    <i class="fa-solid fa-circle-check text-cyan-300 mt-0.5"></i>
                                    <span>Miễn phí lắp đặt, đi dây thẩm mỹ, cài đặt phần mềm & giao hàng tận nơi tại Đà Nẵng.</span>
                                </li>
                                <li class="flex items-start gap-2">
                                    <i class="fa-solid fa-circle-check text-cyan-300 mt-0.5"></i>
                                    <span>Hỗ trợ thu cũ đổi mới, nâng cấp PC/Laptop nhanh chóng.</span>
                                </li>
                            </ul>
                        </div>
                        <div class="mt-5 pt-4 border-t border-white/15 text-xs space-y-1">
                            <div><i class="fa-solid fa-building mr-1.5 text-cyan-300"></i><strong>CÔNG TY TNHH CÔNG NGHỆ TIN HỌC SĨ KỲ</strong></div>
                            <div><i class="fa-solid fa-location-dot mr-1.5 text-cyan-300"></i>22 Bình An 1, Phường Hòa Cường, Tp.Đà Nẵng</div>
                            <div><i class="fa-solid fa-phone mr-1.5 text-cyan-300"></i>Hotline / Zalo báo giá: <strong class="text-amber-300 text-sm">0977.619.414</strong></div>
                        </div>
                    </div>

                    <!-- Cột Form nhập thông tin yêu cầu báo giá -->
                    <div class="lg:col-span-7 p-5 sm:p-6">
                        <h3 class="text-sm sm:text-base font-bold text-slate-800 mb-3 flex items-center gap-2">
                            <i class="fa-solid fa-paper-plane text-siky-primary"></i> Điền thông tin nhận báo giá chi tiết
                        </h3>
                        <form id="homepage-quote-form" onsubmit="submitQuoteForm(event)" class="space-y-3">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div>
                                    <label class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên khách hàng / Đơn vị *</label>
                                    <input id="q-name" type="text" required placeholder="Nhập họ và tên của bạn..." class="w-full h-10 px-3 rounded-lg border border-slate-300 text-xs sm:text-sm focus:border-siky-primary focus:outline-none">
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo nhận báo giá *</label>
                                    <input id="q-phone" type="tel" required placeholder="Ví dụ: 0977619414" class="w-full h-10 px-3 rounded-lg border border-slate-300 text-xs sm:text-sm focus:border-siky-primary focus:outline-none">
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div>
                                    <label class="block text-xs font-semibold text-slate-700 mb-1">Danh mục cần tư vấn / Báo giá</label>
                                    <select id="q-category" class="w-full h-10 px-3 rounded-lg border border-slate-300 text-xs sm:text-sm bg-white focus:border-siky-primary focus:outline-none">
                                        <option value="Build PC Gaming theo yêu cầu">Build PC Gaming theo yêu cầu</option>
                                        <option value="PC Đồ Họa - Render - Kiến Trúc">PC Đồ Họa - Render - Kiến Trúc</option>
                                        <option value="PC Văn Phòng - Doanh Nghiệp">PC Văn Phòng - Kế Toán - Doanh Nghiệp</option>
                                        <option value="Màn Hình Máy Tính Chính Hãng">Màn Hình Máy Tính Chính Hãng</option>
                                        <option value="Laptop Gaming / Văn Phòng">Laptop Gaming / Văn Phòng</option>
                                        <option value="Linh Kiện (VGA, CPU, Main, RAM, SSD)">Linh Kiện (VGA, CPU, Main, RAM, SSD)</option>
                                        <option value="Thiết Bị Doanh Nghiệp & Máy In">Thiết Bị Doanh Nghiệp & Máy In</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-slate-700 mb-1">Ngân sách dự kiến</label>
                                    <select id="q-budget" class="w-full h-10 px-3 rounded-lg border border-slate-300 text-xs sm:text-sm bg-white focus:border-siky-primary focus:outline-none">
                                        <option value="Từ 5 - 10 triệu">Từ 5.000.000đ - 10.000.000đ</option>
                                        <option value="Từ 10 - 15 triệu">Từ 10.000.000đ - 15.000.000đ</option>
                                        <option value="Từ 15 - 25 triệu" selected>Từ 15.000.000đ - 25.000.000đ</option>
                                        <option value="Trên 25 triệu">Trên 25.000.000đ (Workstation / Hi-End)</option>
                                        <option value="Báo giá số lượng cho công ty">Báo giá số lượng cho công ty / dự án</option>
                                    </select>
                                </div>
                            </div>

                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Yêu cầu chi tiết (tên game, phần mềm sử dụng hoặc sản phẩm cần mua)</label>
                                <textarea id="q-note" rows="3" placeholder="Ví dụ: Cần build trọn bộ PC + Màn hình 24 inch 144Hz chơi Valorant, GTA V, làm AutoCAD, Photoshop..." class="w-full p-3 rounded-lg border border-slate-300 text-xs sm:text-sm focus:border-siky-primary focus:outline-none"></textarea>
                            </div>

                            <div class="flex flex-wrap items-center justify-between gap-3 pt-1">
                                <button type="submit" class="px-5 py-2.5 rounded-lg bg-siky-primary hover:bg-siky-dark text-white font-bold text-xs sm:text-sm transition flex items-center gap-2 shadow-xs">
                                    <i class="fa-solid fa-check-circle"></i> GỬI YÊU CẦU & NHẬN BÁO GIÁ NGAY
                                </button>
                                <a href="https://zalo.me/0977619414" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-siky-primary hover:underline flex items-center gap-1.5">
                                    <i class="fa-solid fa-comment-dots"></i> Hoặc nhắn trực tiếp qua Zalo: 0977.619.414
                                </a>
                            </div>

                            <!-- Thông báo kết quả gửi form -->
                            <div id="quote-form-feedback" class="hidden p-3 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs font-medium"></div>
                        </form>
                    </div>
                </div>
            </div>
        </section>

        <!-- 7. ĐƯA FANPAGE VÀ BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ -->
        <section id="bando-fanpage" class="flatsome-container">
            <div class="flatsome-section-header">
                <div class="flatsome-section-title">
                    <i class="fa-solid fa-map-location-dot"></i> KẾT NỐI FANPAGE & BẢN ĐỒ ĐƯỜNG ĐI ĐẾN MÁY TÍNH SĨ KỲ
                </div>
                <a href="https://maps.app.goo.gl/nDxYM2RDuF1ArSjK6" target="_blank" rel="noopener noreferrer" class="text-xs font-bold text-siky-primary hover:underline flex items-center gap-1">
                    <i class="fa-solid fa-diamond-turn-right"></i> Mở Google Maps chỉ đường
                </a>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-4">
                <!-- Cột Fanpage Máy Tính Sĩ Kỳ ngoài trang chủ -->
                <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 p-4 shadow-xs flex flex-col justify-between space-y-3">
                    <div class="flex items-center justify-between border-b border-slate-100 pb-2.5">
                        <div class="flex items-center gap-2">
                            <i class="fa-brands fa-facebook text-blue-600 text-lg"></i>
                            <h3 class="font-bold text-xs sm:text-sm text-slate-800 uppercase">FANPAGE CHÍNH THỨC: MÁY TÍNH SĨ KỲ</h3>
                        </div>
                        <a href="https://www.facebook.com/maytinhsiky" target="_blank" rel="noopener noreferrer" class="text-[11px] font-semibold text-blue-600 hover:underline">
                            facebook.com/maytinhsiky
                        </a>
                    </div>

                    <!-- Khung giao diện Fanpage trực tiếp kèm Facebook Plugin -->
                    <div class="rounded-xl border border-slate-200 overflow-hidden bg-slate-50">
                        <div class="bg-gradient-to-r from-siky-dark to-siky-primary p-3.5 text-white flex items-center gap-3">
                            <img
                                src="https://drive.google.com/thumbnail?id=10D1_3f93N-tXki1yhtqBiAZ_MtYxAyH2&sz=w200"
                                data-drive-id="10D1_3f93N-tXki1yhtqBiAZ_MtYxAyH2"
                                alt="Logo Fanpage Máy Tính Sĩ Kỳ"
                                class="w-12 h-12 rounded-lg bg-white p-1 object-contain shrink-0"
                                onerror="handleDriveImgError(this, 'SK')"
                            >
                            <div class="min-w-0">
                                <a href="https://www.facebook.com/maytinhsiky" target="_blank" rel="noopener noreferrer" class="font-bold text-sm hover:underline block truncate">
                                    Sĩ Kỳ Computer – PC Gaming , Văn Phòng , Đồ Họa
                                </a>
                                <div class="text-[11px] text-cyan-200 flex items-center gap-2 mt-0.5">
                                    <span><i class="fa-solid fa-star text-amber-300"></i> 5.0/5 Đánh giá uy tín</span>
                                    <span>•</span>
                                    <span>Cửa hàng máy tính Đà Nẵng</span>
                                </div>
                            </div>
                        </div>
                        <div class="p-3 space-y-2.5 text-xs text-slate-600">
                            <p class="leading-relaxed">
                                Cập nhật hình ảnh lắp đặt PC thực tế mỗi ngày, chương trình khuyến mãi linh kiện, màn hình, laptop và hỗ trợ kỹ thuật nhanh chóng trên Fanpage <strong>Máy Tính Sĩ Kỳ</strong>.
                            </p>
                            <!-- Nhúng Facebook Page Iframe chuẩn -->
                            <div class="w-full overflow-hidden rounded-lg border border-slate-200 bg-white">
                                <iframe
                                    title="Fanpage Máy Tính Sĩ Kỳ"
                                    src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fmaytinhsiky&tabs=timeline&width=500&height=210&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true"
                                    width="100%"
                                    height="210"
                                    style="border:none;overflow:hidden"
                                    scrolling="no"
                                    frameborder="0"
                                    allowfullscreen="true"
                                    allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                                </iframe>
                            </div>
                            <div class="grid grid-cols-2 gap-2 pt-1">
                                <a href="https://www.facebook.com/maytinhsiky" target="_blank" rel="noopener noreferrer" class="py-2 px-3 rounded-lg bg-blue-600 hover:bg-blue-700 text-white font-bold text-center text-xs transition flex items-center justify-center gap-1.5">
                                    <i class="fa-brands fa-facebook-f"></i> Theo Dõi Fanpage
                                </a>
                                <a href="https://www.facebook.com/maytinhsiky" target="_blank" rel="noopener noreferrer" class="py-2 px-3 rounded-lg bg-slate-200 hover:bg-slate-300 text-slate-800 font-bold text-center text-xs transition flex items-center justify-center gap-1.5">
                                    <i class="fa-brands fa-facebook-messenger text-blue-600"></i> Nhắn Tin Tư Vấn
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Cột Bản đồ Google Maps trực tiếp ngoài trang chủ -->
                <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 p-4 shadow-xs flex flex-col justify-between space-y-3">
                    <div class="flex flex-wrap items-center justify-between gap-2 border-b border-slate-100 pb-2.5">
                        <div>
                            <h3 class="font-bold text-xs sm:text-sm text-slate-800 uppercase flex items-center gap-1.5">
                                <i class="fa-solid fa-location-dot text-siky-sale"></i>
                                BẢN ĐỒ GOOGLE MAPS: 22 BÌNH AN 1, PHƯỜNG HÒA CƯỜNG, TP. ĐÀ NẴNG
                            </h3>
                        </div>
                        <a href="https://maps.app.goo.gl/nDxYM2RDuF1ArSjK6" target="_blank" rel="noopener noreferrer" class="px-2.5 py-1 rounded bg-blue-50 text-siky-primary font-bold text-[11px] hover:bg-siky-primary hover:text-white transition">
                            Mở ứng dụng Google Maps <i class="fa-solid fa-up-right-from-square ml-1"></i>
                        </a>
                    </div>

                    <!-- Bản đồ Google Maps hiển thị trực tiếp ngoài trang chủ -->
                    <div class="relative w-full h-[290px] sm:h-[320px] rounded-xl overflow-hidden border border-slate-200 bg-slate-100">
                        <iframe
                            title="Google Map Máy Tính Sĩ Kỳ 22 Bình An 1 Đà Nẵng"
                            src="https://www.google.com/maps?q=S%C4%A8+K%E1%BB%B2+COMPUTER+22+B%C3%ACnh+An+1,+H%C3%B2a+C%C6%B0%E1%BB%9Dng,+%C4%90%C3%A0+N%E1%BA%B5ng&output=embed"
                            width="100%"
                            height="100%"
                            style="border:0;"
                            allowfullscreen=""
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>

                    <div class="flex flex-wrap items-center justify-between gap-2 pt-1 text-xs text-slate-600">
                        <div>
                            <strong class="text-slate-800">Địa chỉ Showroom:</strong> 22 Bình An 1, Phường Hòa Cường, Tp.Đà Nẵng — <strong>SĐT:</strong> <a href="tel:0977619414" class="text-siky-sale font-bold">0977.619.414</a>
                        </div>
                        <a href="https://maps.app.goo.gl/nDxYM2RDuF1ArSjK6" target="_blank" rel="noopener noreferrer" class="inline-flex items-center gap-1.5 px-3 py-1.5 rounded-lg bg-siky-primary text-white font-semibold text-xs hover:bg-siky-dark transition">
                            <i class="fa-solid fa-map-pin"></i> Xem vị trí trên Google Maps
                        </a>
                    </div>
                </div>
            </div>
        </section>

        <!-- 8. DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TIN TỨC & KINH NGHIỆM CÔNG NGHỆ) -->
        <section id="tin-tuc-trang-chu" class="flatsome-container">
            <div class="flatsome-section-header">
                <div class="flatsome-section-title">
                    <i class="fa-regular fa-newspaper"></i> DANH MỤC BÀI VIẾT & TIN TỨC CÔNG NGHỆ
                </div>
                <div class="flex flex-wrap items-center gap-1.5 text-xs">
                    <span class="px-2.5 py-1 rounded bg-slate-100 text-slate-700 font-medium">Tư vấn Build PC</span>
                    <span class="px-2.5 py-1 rounded bg-slate-100 text-slate-700 font-medium">Kinh nghiệm chọn màn hình</span>
                    <span class="px-2.5 py-1 rounded bg-slate-100 text-slate-700 font-medium">Thủ thuật máy tính</span>
                </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-3.5">
                <!-- Bài viết 1 -->
                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs hover:shadow-md transition flex flex-col">
                    <div class="h-40 bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1y_ks82EgPIdXuaOtmPkjmgjxqp1W6TTj&sz=w600" data-drive-id="1y_ks82EgPIdXuaOtmPkjmgjxqp1W6TTj" alt="Kinh nghiệm Build PC Gaming Đà Nẵng" class="w-full h-full object-cover" onerror="handleDriveImgError(this, 'Tin Tức 1')">
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between space-y-2">
                        <div>
                            <span class="text-[10.5px] font-bold text-siky-primary uppercase">Tư vấn cấu hình PC</span>
                            <h3 class="font-bold text-xs sm:text-sm text-slate-800 mt-1 leading-snug">
                                Kinh nghiệm Build PC Gaming & Đồ họa tối ưu hiệu năng trong tầm giá 15 - 20 triệu tại Đà Nẵng
                            </h3>
                            <p class="text-xs text-slate-500 mt-1.5 leading-relaxed">
                                Hướng dẫn lựa chọn CPU Intel Core i5 / AMD Ryzen 5 kết hợp VGA RTX 3060 / RTX 4060 cân mọi tựa game eSports và làm đồ họa mượt mà.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="text-xs font-semibold text-siky-primary hover:underline inline-flex items-center gap-1 pt-1">
                            Nhận tư vấn cấu hình <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs hover:shadow-md transition flex flex-col">
                    <div class="h-40 bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1l6Cit0andz8u94BCMJyCN_wce6JkLTBj&sz=w600" data-drive-id="1l6Cit0andz8u94BCMJyCN_wce6JkLTBj" alt="Cách chọn màn hình máy tính" class="w-full h-full object-cover" onerror="handleDriveImgError(this, 'Tin Tức 2')">
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between space-y-2">
                        <div>
                            <span class="text-[10.5px] font-bold text-siky-primary uppercase">Màn hình máy tính</span>
                            <h3 class="font-bold text-xs sm:text-sm text-slate-800 mt-1 leading-snug">
                                Cách chọn màn hình IPS 100Hz - 180Hz chuẩn màu cho dân thiết kế đồ họa và game thủ
                            </h3>
                            <p class="text-xs text-slate-500 mt-1.5 leading-relaxed">
                                So sánh chi tiết các dòng màn hình 24 inch và 27 inch 2K từ ViewSonic, ASUS, LG, Samsung đang có sẵn giá tốt tại Máy Tính Sĩ Kỳ.
                            </p>
                        </div>
                        <a href="#sec-manhinh" class="text-xs font-semibold text-siky-primary hover:underline inline-flex items-center gap-1 pt-1">
                            Xem danh mục màn hình <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs hover:shadow-md transition flex flex-col">
                    <div class="h-40 bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1qNVKyBdrJFcKIWjXwOYCl6O71A-wnPyf&sz=w600" data-drive-id="1qNVKyBdrJFcKIWjXwOYCl6O71A-wnPyf" alt="Giải pháp máy tính văn phòng" class="w-full h-full object-cover" onerror="handleDriveImgError(this, 'Tin Tức 3')">
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between space-y-2">
                        <div>
                            <span class="text-[10.5px] font-bold text-siky-primary uppercase">Giải pháp doanh nghiệp</span>
                            <h3 class="font-bold text-xs sm:text-sm text-slate-800 mt-1 leading-snug">
                                Giải pháp lắp đặt trọn bộ máy tính văn phòng, kế toán bền bỉ tiết kiệm chi phí cho công ty
                            </h3>
                            <p class="text-xs text-slate-500 mt-1.5 leading-relaxed">
                                Sĩ Kỳ Computer cung cấp trọn gói máy tính để bàn, máy in, thiết bị mạng với chế độ bảo hành tận nơi và xuất hóa đơn VAT đầy đủ.
                            </p>
                        </div>
                        <a href="#form-bao-gia" class="text-xs font-semibold text-siky-primary hover:underline inline-flex items-center gap-1 pt-1">
                            Yêu cầu báo giá dự án <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-xs hover:shadow-md transition flex flex-col">
                    <div class="h-40 bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1B2pUD7gMFD2cy7yIkl6LTt-nXSMCAvHn&sz=w600" data-drive-id="1B2pUD7gMFD2cy7yIkl6LTt-nXSMCAvHn" alt="Dịch vụ nâng cấp vệ sinh PC Đà Nẵng" class="w-full h-full object-cover" onerror="handleDriveImgError(this, 'Tin Tức 4')">
                    </div>
                    <div class="p-3.5 flex-1 flex flex-col justify-between space-y-2">
                        <div>
                            <span class="text-[10.5px] font-bold text-siky-primary uppercase">Dịch vụ kỹ thuật</span>
                            <h3 class="font-bold text-xs sm:text-sm text-slate-800 mt-1 leading-snug">
                                Dịch vụ nâng cấp SSD, RAM, tra keo tản nhiệt và vệ sinh PC - Laptop lấy liền tại Hòa Cường, Đà Nẵng
                            </h3>
                            <p class="text-xs text-slate-500 mt-1.5 leading-relaxed">
                                Khắc phục ngay tình trạng máy chạy chậm, nóng máy khi render hoặc chơi game tại 22 Bình An 1, Phường Hòa Cường, TP. Đà Nẵng.
                            </p>
                        </div>
                        <a href="tel:0977619414" class="text-xs font-semibold text-siky-primary hover:underline inline-flex items-center gap-1 pt-1">
                            Liên hệ kỹ thuật: 0977.619.414 <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>
            </div>
        </section>

        <!-- 9. DANH MỤC CÁC ĐỐI TÁC CHÍNH HÃNG -->
        <section id="doi-tac-chinh-hang" class="flatsome-container">
            <div class="bg-white rounded-xl p-4 border border-slate-200 shadow-xs">
                <div class="flex items-center justify-between mb-3 pb-2 border-b border-slate-100">
                    <h2 class="text-xs sm:text-sm font-bold text-siky-primary uppercase flex items-center gap-2">
                        <i class="fa-solid fa-handshake"></i> ĐỐI TÁC & THƯƠNG HIỆU PHÂN PHỐI CHÍNH HÃNG
                    </h2>
                    <span class="text-[11px] text-slate-500 hidden sm:inline">Cam kết 100% sản phẩm chính hãng tại maytinhsiky.com</span>
                </div>
                <div class="grid grid-cols-3 sm:grid-cols-4 md:grid-cols-7 gap-2.5">
                    <div class="h-12 rounded-lg border border-slate-200 bg-slate-50 flex items-center justify-center font-extrabold text-sm text-[#0071c5] tracking-wider">INTEL</div>
                    <div class="h-12 rounded-lg border border-slate-200 bg-slate-50 flex items-center justify-center font-extrabold text-sm text-[#ed1c24] tracking-wider">AMD RYZEN</div>
                    <div class="h-12 rounded-lg border border-slate-200 bg-slate-50 flex items-center justify-center font-extrabold text-sm text-[#00539b] tracking-wider">ASUS</div>
                    <div class="h-12 rounded-lg border border-slate-200 bg-slate-50 flex items-center justify-center font-extrabold text-sm text-[#ff6600] tracking-wider">GIGABYTE</div>
                    <div class="h-12 rounded-lg border border-slate-200 bg-slate-50 flex items-center justify-center font-extrabold text-sm text-[#e60012] tracking-wider">MSI</div>
                    <div class="h-12 rounded-lg border border-slate-200 bg-slate-50 flex items-center justify-center font-extrabold text-sm text-[#76b900] tracking-wider">NVIDIA</div>
                    <div class="h-12 rounded-lg border border-slate-200 bg-slate-50 flex items-center justify-center font-extrabold text-sm text-[#900028] tracking-wider">VIEWSONIC</div>
                    <div class="h-12 rounded-lg border border-slate-200 bg-slate-50 flex items-center justify-center font-extrabold text-sm text-[#007db8] tracking-wider">DELL</div>
                    <div class="h-12 rounded-lg border border-slate-200 bg-slate-50 flex items-center justify-center font-extrabold text-sm text-[#0096d6] tracking-wider">HP</div>
                    <div class="h-12 rounded-lg border border-slate-200 bg-slate-50 flex items-center justify-center font-extrabold text-sm text-[#e2231a] tracking-wider">LENOVO</div>
                    <div class="h-12 rounded-lg border border-slate-200 bg-slate-50 flex items-center justify-center font-extrabold text-sm text-[#a50034] tracking-wider">LG</div>
                    <div class="h-12 rounded-lg border border-slate-200 bg-slate-50 flex items-center justify-center font-extrabold text-sm text-[#1428a0] tracking-wider">SAMSUNG</div>
                    <div class="h-12 rounded-lg border border-slate-200 bg-slate-50 flex items-center justify-center font-extrabold text-sm text-[#1e293b] tracking-wider">KINGSTON</div>
                    <div class="h-12 rounded-lg border border-slate-200 bg-slate-50 flex items-center justify-center font-extrabold text-sm text-[#0056b3] tracking-wider">DEEPCOOL</div>
                </div>
            </div>
        </section>

    </main>

    <!-- =====================================================================
         FOOTER WRAPPER (CHUẨN FLATSOME)
         ===================================================================== -->
    <footer id="footer" class="bg-slate-900 text-slate-300 pt-8 pb-6 mt-6 border-t-4 border-siky-primary">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 pb-6 border-b border-slate-800">
                <!-- Cột 1: Thông tin công ty -->
                <div class="lg:col-span-5 space-y-2.5">
                    <div class="flex items-center gap-2.5">
                        <img
                            src="https://drive.google.com/thumbnail?id=10D1_3f93N-tXki1yhtqBiAZ_MtYxAyH2&sz=w200"
                            data-drive-id="10D1_3f93N-tXki1yhtqBiAZ_MtYxAyH2"
                            alt="Logo Máy Tính Sĩ Kỳ"
                            class="w-10 h-10 rounded-lg bg-white p-0.5 object-contain shrink-0"
                            onerror="handleDriveImgError(this, 'SK')"
                        >
                        <div>
                            <h3 class="text-white font-extrabold text-sm sm:text-base">CÔNG TY TNHH CÔNG NGHỆ TIN HỌC SĨ KỲ</h3>
                            <p class="text-xs text-cyan-400 font-medium">Website chính thức: maytinhsiky.com — MST: 0402323089</p>
                        </div>
                    </div>
                    <p class="text-xs text-slate-400 leading-relaxed">
                        Chuyên cung cấp PC Gaming, PC Đồ Họa – Workstation, Máy tính văn phòng, Laptop, Màn hình máy tính và Linh kiện chính hãng tại TP. Đà Nẵng. Nhận Build PC trọn gói theo yêu cầu với chính sách bảo hành uy tín, tận tâm.
                    </p>
                    <ul class="space-y-1.5 text-xs text-slate-300 pt-1">
                        <li><i class="fa-solid fa-location-dot text-cyan-400 w-5"></i><strong>Địa chỉ:</strong> 22 Bình An 1, Phường Hòa Cường, Tp.Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone text-cyan-400 w-5"></i><strong>Điện thoại / Zalo:</strong> <a href="tel:0977619414" class="text-white font-bold hover:text-cyan-300">0977.619.414</a></li>
                        <li><i class="fa-solid fa-envelope text-cyan-400 w-5"></i><strong>Email:</strong> sikynt@gmail.com</li>
                        <li><i class="fa-brands fa-facebook text-cyan-400 w-5"></i><strong>Fanpage:</strong> <a href="https://www.facebook.com/maytinhsiky" target="_blank" rel="noopener noreferrer" class="hover:text-cyan-300 underline">facebook.com/maytinhsiky</a></li>
                        <li><i class="fa-solid fa-map-location-dot text-cyan-400 w-5"></i><strong>Google Map:</strong> <a href="https://maps.app.goo.gl/nDxYM2RDuF1ArSjK6" target="_blank" rel="noopener noreferrer" class="hover:text-cyan-300 underline">Xem bản đồ chỉ đường</a></li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục sản phẩm -->
                <div class="lg:col-span-3 space-y-2">
                    <h4 class="text-white font-bold text-xs uppercase tracking-wider border-b border-slate-800 pb-2">DANH MỤC SẢN PHẨM</h4>
                    <ul class="space-y-1.5 text-xs text-slate-400">
                        <li><a href="#sec-pc-gaming" class="hover:text-white transition">PC Gaming Intel / AMD</a></li>
                        <li><a href="#sec-pc-dohoa" class="hover:text-white transition">PC Đồ Họa – Workstation – Render</a></li>
                        <li><a href="#sec-pc-vanphong" class="hover:text-white transition">PC Văn Phòng – Học Tập – Kế Toán</a></li>
                        <li><a href="#sec-pc-vanphong" class="hover:text-white transition">Máy Bộ Dell / HP / Asus – Máy Chủ</a></li>
                        <li><a href="#sec-laptop" class="hover:text-white transition">Laptop Chính Hãng Gaming & Văn Phòng</a></li>
                        <li><a href="#sec-manhinh" class="hover:text-white transition">Màn Hình Máy Tính 24" / 27" / 32"</a></li>
                        <li><a href="#sec-linhkien" class="hover:text-white transition">Linh Kiện Máy Tính & Card Đồ Họa VGA</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Chính sách & Hỗ trợ khách hàng -->
                <div class="lg:col-span-4 space-y-2">
                    <h4 class="text-white font-bold text-xs uppercase tracking-wider border-b border-slate-800 pb-2">CHÍNH SÁCH & HỖ TRỢ KHÁCH HÀNG</h4>
                    <ul class="space-y-1.5 text-xs text-slate-400">
                        <li><a href="#form-bao-gia" class="hover:text-white transition">Chính sách bảo hành chính hãng lên đến 36 tháng</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-white transition">Chính sách vận chuyển & lắp đặt tận nơi tại Đà Nẵng</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-white transition">Chính sách đổi trả & kiểm hàng minh bạch</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-white transition">Hỗ trợ trả góp & thanh toán chuyển khoản / quẹt thẻ</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-white transition">Tư vấn cấu hình Build PC & Báo giá dự án doanh nghiệp</a></li>
                    </ul>
                </div>
            </div>

            <div class="pt-4 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
                <div>© Bản quyền thuộc về <strong class="text-white">Máy Tính Sĩ Kỳ (maytinhsiky.com)</strong> - 22 Bình An 1, Phường Hòa Cường, Tp.Đà Nẵng.</div>
                <div>Hotline CSKH & Bảo hành: <strong class="text-cyan-400">0977.619.414</strong></div>
            </div>
        </div>
    </footer>

    <!-- =====================================================================
         CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH TRÊN MÁY TÍNH VÀ ĐIỆN THOẠI
         ===================================================================== -->
    <div class="fixed bottom-4 right-3 sm:right-4 z-40 flex flex-col items-end gap-2.5">
        <!-- Nút Facebook Fanpage -->
        <a
            href="https://www.facebook.com/maytinhsiky"
            target="_blank"
            rel="noopener noreferrer"
            title="Chat Facebook Máy Tính Sĩ Kỳ"
            class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1464cc] text-white rounded-full p-2.5 sm:px-3.5 sm:py-2 shadow-lg transition"
        >
            <i class="fa-brands fa-facebook-messenger text-lg"></i>
            <span class="hidden sm:inline text-xs font-bold">Facebook Sĩ Kỳ</span>
        </a>

        <!-- Nút Chat Zalo -->
        <a
            href="https://zalo.me/0977619414"
            target="_blank"
            rel="noopener noreferrer"
            title="Chat Zalo 0977.619.414"
            class="group flex items-center gap-2 bg-[#0068ff] hover:bg-[#0055d4] text-white rounded-full p-2.5 sm:px-3.5 sm:py-2 shadow-lg transition"
        >
            <span class="w-5 h-5 rounded-full bg-white text-[#0068ff] font-black text-[10px] flex items-center justify-center shrink-0">Zalo</span>
            <span class="hidden sm:inline text-xs font-bold">Chat Zalo: 0977.619.414</span>
        </a>

        <!-- Nút Hotline nổi bật -->
        <a
            href="tel:0977619414"
            title="Gọi Hotline 0977.619.414"
            class="floating-btn-pulse flex items-center gap-2 bg-siky-sale hover:bg-red-700 text-white rounded-full p-3 sm:px-4 sm:py-2.5 shadow-xl transition"
        >
            <i class="fa-solid fa-phone-volume text-base"></i>
            <span class="text-xs font-extrabold tracking-wide">0977.619.414</span>
        </a>
    </div>

    <!-- =====================================================================
         MODAL ĐẶT MUA / BÁO GIÁ NHANH SẢN PHẨM (THAY THẾ HOÀN TOÀN ALERT)
         ===================================================================== -->
    <div id="quote-modal" class="fixed inset-0 bg-slate-900/60 z-50 hidden items-center justify-center p-3">
        <div class="bg-white rounded-xl max-w-md w-full p-5 shadow-2xl border border-slate-200 relative">
            <button type="button" onclick="closeQuoteModal()" class="absolute top-3 right-3 w-8 h-8 rounded-full bg-slate-100 hover:bg-slate-200 flex items-center justify-center text-slate-600">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div class="flex items-center gap-2 text-siky-primary font-extrabold text-sm uppercase mb-2">
                <i class="fa-solid fa-cart-plus"></i> Đặt Mua & Nhận Tư Vấn Nhanh
            </div>
            <p id="modal-product-name" class="text-xs font-semibold text-slate-700 bg-slate-100 p-2.5 rounded-lg mb-3"></p>
            <form onsubmit="submitModalOrder(event)" class="space-y-2.5">
                <div>
                    <label class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên của bạn *</label>
                    <input id="m-name" type="text" required placeholder="Nhập họ tên..." class="w-full h-9 px-3 rounded-lg border border-slate-300 text-xs focus:border-siky-primary focus:outline-none">
                </div>
                <div>
                    <label class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo liên hệ *</label>
                    <input id="m-phone" type="tel" required placeholder="Nhập số điện thoại..." class="w-full h-9 px-3 rounded-lg border border-slate-300 text-xs focus:border-siky-primary focus:outline-none">
                </div>
                <div>
                    <label class="block text-xs font-semibold text-slate-700 mb-1">Ghi chú thêm (nâng cấp RAM/SSD, giao hàng...)</label>
                    <input id="m-note" type="text" placeholder="Ghi chú yêu cầu..." class="w-full h-9 px-3 rounded-lg border border-slate-300 text-xs focus:border-siky-primary focus:outline-none">
                </div>
                <div id="modal-feedback" class="hidden p-2.5 rounded-lg bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs font-medium"></div>
                <div class="pt-1 flex items-center gap-2">
                    <button type="submit" class="flex-1 py-2.5 rounded-lg bg-siky-primary hover:bg-siky-dark text-white font-bold text-xs transition">
                        Gửi Yêu Cầu Đặt Hàng
                    </button>
                    <a href="https://zalo.me/0977619414" target="_blank" rel="noopener noreferrer" class="py-2.5 px-3 rounded-lg bg-blue-50 text-siky-primary font-bold text-xs hover:bg-blue-100 transition">
                        Chat Zalo
                    </a>
                </div>
            </form>
        </div>
    </div>

    <!-- =====================================================================
         JAVASCRIPT XỬ LÝ SLIDER, FALLBACK ẢNH GOOGLE DRIVE, TÌM KIẾM & FORM
         ===================================================================== -->
    <script>
        /* 1. Xử lý dự phòng đa tầng cho ảnh Google Drive để luôn hiển thị mượt mà */
        function handleDriveImgError(imgEl, fallbackLabel) {
            const driveId = imgEl.getAttribute('data-drive-id');
            const retryStep = parseInt(imgEl.getAttribute('data-retry-step') || '0', 10);

            if (driveId && retryStep === 0) {
                imgEl.setAttribute('data-retry-step', '1');
                imgEl.src = 'https://lh3.googleusercontent.com/d/' + driveId + '=w800';
            } else if (driveId && retryStep === 1) {
                imgEl.setAttribute('data-retry-step', '2');
                imgEl.src = 'https://drive.google.com/uc?export=view&id=' + driveId;
            } else {
                imgEl.onerror = null;
                const cleanText = encodeURIComponent(fallbackLabel || 'May Tinh Si Ky');
                imgEl.src = 'https://placehold.co/600x600/0056b3/ffffff?text=' + cleanText;
            }
        }

        /* 2. Điều khiển Slider 2 ảnh Banner tự trượt chuyên nghiệp */
        let currentHeroSlide = 0;
        const totalHeroSlides = 2;
        let heroSlideInterval = null;

        function updateHeroSliderUI() {
            const slides = document.querySelectorAll('.hero-slide');
            const dots = document.querySelectorAll('.hero-dot');
            slides.forEach((slide, idx) => {
                if (idx === currentHeroSlide) {
                    slide.classList.remove('hidden');
                    slide.classList.add('block');
                } else {
                    slide.classList.remove('block');
                    slide.classList.add('hidden');
                }
            });
            dots.forEach((dot, idx) => {
                if (idx === currentHeroSlide) {
                    dot.className = 'hero-dot w-5 h-1.5 rounded-full bg-white transition-all';
                } else {
                    dot.className = 'hero-dot w-2 h-1.5 rounded-full bg-white/50 transition-all';
                }
            });
        }

        function changeHeroSlide(step) {
            currentHeroSlide = (currentHeroSlide + step + totalHeroSlides) % totalHeroSlides;
            updateHeroSliderUI();
            resetHeroInterval();
        }

        function goToHeroSlide(index) {
            currentHeroSlide = index;
            updateHeroSliderUI();
            resetHeroInterval();
        }

        function resetHeroInterval() {
            if (heroSlideInterval) clearInterval(heroSlideInterval);
            heroSlideInterval = setInterval(() => {
                currentHeroSlide = (currentHeroSlide + 1) % totalHeroSlides;
                updateHeroSliderUI();
            }, 5000);
        }

        /* 3. Menu danh mục trên điện thoại */
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        if (mobileMenuBtn) {
            mobileMenuBtn.addEventListener('click', () => toggleMobileDrawer(true));
        }

        function toggleMobileDrawer(open) {
            const drawer = document.getElementById('mobile-drawer');
            const backdrop = document.getElementById('mobile-drawer-backdrop');
            if (open) {
                backdrop.classList.remove('hidden');
                drawer.classList.remove('-translate-x-full');
            } else {
                backdrop.classList.add('hidden');
                drawer.classList.add('-translate-x-full');
            }
        }

        /* 4. Tìm kiếm nhanh sản phẩm trên trang chủ */
        function handleProductSearch(event) {
            event.preventDefault();
            const keyword = (document.getElementById('search-input').value || '').trim().toLowerCase();
            const cards = document.querySelectorAll('.product-searchable');
            let firstMatch = null;

            cards.forEach(card => {
                const text = card.innerText.toLowerCase();
                if (!keyword || text.includes(keyword)) {
                    card.style.display = '';
                    if (!firstMatch && keyword) firstMatch = card;
                } else {
                    card.style.display = 'none';
                }
            });

            if (firstMatch) {
                firstMatch.scrollIntoView({ behavior: 'smooth', block: 'center' });
            } else if (!keyword) {
                document.getElementById('sec-pc-gaming').scrollIntoView({ behavior: 'smooth' });
            }
        }

        /* 5. Xử lý Modal Đặt mua & Giỏ hàng */
        let cartCount = 0;
        function openQuoteModal(productTitle) {
            cartCount += 1;
            const badge = document.getElementById('cart-count-badge');
            if (badge) badge.textContent = String(cartCount);

            const modal = document.getElementById('quote-modal');
            const titleEl = document.getElementById('modal-product-name');
            const feedbackEl = document.getElementById('modal-feedback');
            if (titleEl) titleEl.textContent = 'Sản phẩm: ' + productTitle;
            if (feedbackEl) feedbackEl.classList.add('hidden');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeQuoteModal() {
            const modal = document.getElementById('quote-modal');
            modal.classList.remove('flex');
            modal.classList.add('hidden');
        }

        function submitModalOrder(event) {
            event.preventDefault();
            const name = document.getElementById('m-name').value;
            const phone = document.getElementById('m-phone').value;
            const feedbackEl = document.getElementById('modal-feedback');
            feedbackEl.textContent = 'Cảm ơn ' + name + '! Máy Tính Sĩ Kỳ đã ghi nhận số ' + phone + ' và sẽ liên hệ tư vấn ngay.';
            feedbackEl.classList.remove('hidden');
        }

        /* 6. Xử lý Form yêu cầu báo giá ngoài trang chủ */
        function submitQuoteForm(event) {
            event.preventDefault();
            const name = document.getElementById('q-name').value;
            const phone = document.getElementById('q-phone').value;
            const cat = document.getElementById('q-category').value;
            const budget = document.getElementById('q-budget').value;
            const feedback = document.getElementById('quote-form-feedback');

            feedback.innerHTML = '<i class="fa-solid fa-circle-check mr-1"></i> Đã gửi yêu cầu báo giá thành công! Chuyên viên kỹ thuật <strong>Máy Tính Sĩ Kỳ (0977.619.414)</strong> sẽ liên hệ với <strong>' + name + ' (' + phone + ')</strong> để tư vấn gói <em>' + cat + ' (' + budget + ')</em> trong ít phút.';
            feedback.classList.remove('hidden');
        }

        window.onload = function () {
            resetHeroInterval();
        };
    </script>
</body>
</html>
