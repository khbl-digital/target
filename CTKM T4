<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dashboard Ưu Đãi PNJ Online - Tháng 04/2026</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <!-- Bổ sung font Playfair Display cho tiêu đề sang trọng -->
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700;800&family=Playfair+Display:ital,wght@0,600;0,700;0,800;1,600;1,700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <style>
        :root {
            --pnj-navy: #002244;
            --pnj-blue: #003274;
            --pnj-light-blue: #d4e3f1;
            --pnj-gold: #D4AF37;
            --pnj-light-gold: #fcf9f0;
            --bg-color: #f4f7f9;
            --text-main: #334155;
            --text-light: #64748b;
            --white: #ffffff;
            --danger: #ef4444;
            --danger-light: #fef2f2;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Montserrat', sans-serif; /* Font body mặc định */
        }

        body {
            background-color: #f0f5fa;
            /* Gradient mô phỏng nền trời xanh nhạt chuyển dần xuống trắng sáng của poster */
            background-image: linear-gradient(180deg, #d3e4f3 0%, #ffffff 800px);
            background-attachment: fixed;
            background-repeat: no-repeat;
            color: var(--text-main);
            line-height: 1.6;
            min-height: 100vh;
        }

        /* Tiêu đề dùng font Serif sang trọng */
        h1, h2, h3, .offer-title, .huge-discount, .header-title {
            font-family: 'Playfair Display', serif;
        }

        /* Header trong suốt, thanh lịch */
        header {
            background: transparent;
            color: var(--pnj-navy);
            padding: 40px 20px 20px;
            text-align: center;
            position: relative;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .header-logo-box {
            position: absolute;
            left: 40px;
            top: 50%;
            transform: translateY(-50%);
            width: 80px;
            height: 80px;
            background-color: #ffffff;
            background-image: radial-gradient(circle, #fff, #fdfbf4);
            border: 2px solid #D4AF37;
            border-radius: 50%;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            box-shadow: 0 4px 15px rgba(212, 175, 55, 0.2);
            z-index: 10;
        }

        .header-logo-box .num {
            font-family: 'Playfair Display', serif;
            font-size: 38px;
            font-weight: 800;
            color: #002244;
            line-height: 1;
        }

        .header-logo-box .text {
            font-size: 10px;
            font-weight: 700;
            color: #D4AF37;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .header-title {
            font-size: 38px;
            font-weight: 800;
            text-transform: uppercase;
            color: var(--pnj-navy);
            text-shadow: 0 2px 4px rgba(255,255,255,0.5);
        }

        .global-warning {
            background-color: #fef2f2;
            border: 1px solid #fca5a5;
            color: #991b1b;
            padding: 12px 20px;
            border-radius: 8px;
            max-width: 1000px;
            margin: 10px auto 30px;
            position: relative;
            z-index: 10;
            box-shadow: 0 4px 15px rgba(239, 68, 68, 0.08);
            font-size: 14px;
            display: flex;
            align-items: flex-start;
            gap: 10px;
        }

        .global-warning i {
            margin-top: 3px;
            color: #ef4444;
        }

        /* Navigation Tabs */
        .tabs-container {
            max-width: 1200px;
            margin: 20px auto 30px;
            padding: 0 20px;
            position: relative;
            z-index: 10;
        }

        .tabs {
            display: flex;
            gap: 20px;
            background: transparent;
        }

        .tab-btn {
            flex: 1;
            padding: 20px 10px;
            border: 1px solid rgba(0, 34, 68, 0.1);
            background-color: rgba(255, 255, 255, 0.8);
            backdrop-filter: blur(10px);
            border-radius: 40px;
            font-size: 16px;
            font-weight: 700;
            color: #002244;
            cursor: pointer;
            transition: all 0.3s ease;
            text-transform: uppercase;
            box-shadow: 0 4px 15px rgba(0, 34, 68, 0.03);
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
        }

        .tab-btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 20px rgba(0, 34, 68, 0.08);
            background-color: #ffffff;
        }

        .tab-btn.active {
            color: #ffffff;
            background-color: #002244;
            background-image: linear-gradient(135deg, #002244 0%, #003274 100%);
            border-color: #002244;
            box-shadow: 0 8px 20px rgba(0, 34, 68, 0.15);
        }

        /* Main Content Area */
        main {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px 60px;
        }

        .tab-content {
            display: none;
            animation: fadeIn 0.4s ease;
        }

        .tab-content.active {
            display: block;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(10px); }
            to { opacity: 1; transform: translateY(0); }
        }

        /* Card Layouts */
        .section-title {
            font-size: 26px;
            font-weight: 800;
            color: #002244;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid rgba(212, 175, 55, 0.5);
            display: inline-block;
        }
        
        .saledeal-text {
            color: #ef4444;
            font-weight: 800;
            font-size: 18px;
            margin: 25px 0 15px;
            display: block;
            text-transform: uppercase;
        }

        /* Saledeal Tag */
        .saledeal-tag {
            display: inline-flex;
            align-items: center;
            gap: 6px;
            background-color: #fef2f2;
            color: #ef4444;
            border: 1px dashed #fca5a5;
            padding: 4px 10px;
            border-radius: 6px;
            font-size: 12px;
            font-weight: 700;
            margin-bottom: 15px;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }

        .saledeal-tag.dark {
            background-color: rgba(212, 175, 55, 0.1);
            color: #b58c2a;
            border-color: #D4AF37;
        }

        .grid-2 { display: grid; grid-template-columns: 1fr 1fr; gap: 25px; margin-bottom: 40px; }
        .grid-3 { display: grid; grid-template-columns: repeat(3, 1fr); gap: 20px; margin-bottom: 40px; }
        .grid-4 { display: grid; grid-template-columns: repeat(4, 1fr); gap: 15px; margin-bottom: 40px; }
        
        /* Gold Card Grid Layouts - Cập nhật gradient bóng bẩy kim loại */
        .gold-card {
            background-color: #d4af37;
            background-image: linear-gradient(135deg, #fdf1cd 0%, #d4af37 50%, #b38519 100%);
            border-radius: 12px;
            padding: 15px;
            text-align: center;
            color: #002244;
            box-shadow: 0 8px 15px rgba(212, 175, 55, 0.25);
            display: flex;
            flex-direction: column;
            justify-content: center;
            position: relative;
            border: 1px solid rgba(255,255,255,0.6);
            transition: transform 0.2s ease, box-shadow 0.2s ease;
            min-height: 100px;
            z-index: 1;
        }

        .gold-card:hover { 
            transform: translateY(-3px); 
            box-shadow: 0 12px 20px rgba(212, 175, 55, 0.35);
        }

        .gold-card .offer-title {
            font-size: 24px;
            font-weight: 800;
            text-transform: uppercase;
            margin-bottom: 5px;
            line-height: 1.2;
            color: #002244;
        }

        .gold-card .offer-sub {
            font-size: 13px;
            font-weight: 600;
            color: #002244;
        }

        .gold-card .offer-badge {
            position: absolute;
            top: -10px;
            right: -10px;
            background-color: #ef4444; 
            color: #ffffff;
            padding: 3px 10px;
            border-radius: 12px;
            font-size: 11px;
            font-weight: 700;
            box-shadow: 0 2px 6px rgba(0,0,0,0.2);
            z-index: 10;
            white-space: nowrap;
            font-family: 'Montserrat', sans-serif;
        }

        /* Thẻ cơ bản */
        .card {
            background-color: #ffffff;
            border-radius: 12px;
            padding: 25px;
            box-shadow: 0 10px 30px rgba(0,34,68,0.05);
            border: 1px solid #eef2f6;
            border-top: 4px solid #002244;
            position: relative;
        }

        .card.highlight {
            border-top: 4px solid #D4AF37;
            background-color: #fdfdfc;
            background-image: linear-gradient(to bottom, #fdfdfc 0%, #ffffff 100%);
            box-shadow: 0 12px 30px rgba(212, 175, 55, 0.1);
        }

        .card-badge {
            position: absolute;
            top: -12px;
            right: 20px;
            background-color: #D4AF37;
            background-image: linear-gradient(135deg, #fdf1cd 0%, #d4af37 100%);
            color: #002244;
            font-size: 12px;
            font-weight: 700;
            padding: 4px 15px;
            border-radius: 20px;
            box-shadow: 0 4px 8px rgba(212, 175, 55, 0.3);
        }
        
        .huge-discount {
            font-size: 48px;
            font-weight: 800;
            color: #D4AF37;
            line-height: 1;
            margin: 10px 0;
            text-shadow: 1px 2px 4px rgba(0,0,0,0.05);
            background: -webkit-linear-gradient(135deg, #b38519, #d4af37, #fdf1cd);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .card h3 { color: #002244; font-size: 20px; font-weight: 700; margin-bottom: 15px; display: flex; align-items: center; gap: 10px; }
        .card h3 i { color: #D4AF37; }
        .card ul { list-style: none; margin-bottom: 15px; }
        .card ul li { margin-bottom: 8px; padding-left: 20px; position: relative; font-size: 15px; }
        .card ul li::before { content: '•'; color: #D4AF37; position: absolute; left: 0; top: 0; font-weight: bold; font-size: 18px; }

        .highlight-text { color: #b38519; font-weight: 700; }
        .navy-text { color: #002244; font-weight: 700; }

        /* Note box */
        .note-box {
            background-color: #f8fafc;
            border-left: 4px solid #002244;
            padding: 15px 20px;
            border-radius: 0 8px 8px 0;
            font-size: 14px;
            margin-top: 20px;
        }

        /* Tab footer */
        .tab-footer {
            margin-top: 40px;
            padding-top: 20px;
            border-top: 1px dashed #cbd5e1;
            text-align: right;
            font-size: 14px;
            color: #64748b;
        }
        
        .tab-footer a { color: #003274; font-weight: 700; text-decoration: none; transition: color 0.3s ease; }
        .tab-footer a:hover { text-decoration: underline; color: #002244; }

        /* Banner Tab 1 - Tinh chỉnh sang dải màu sáng nhẹ giống Poster */
        .visual-header {
            background-color: #ffffff;
            background-image: linear-gradient(135deg, #ffffff 0%, #e0ebf5 100%);
            border-radius: 12px;
            padding: 40px 30px;
            color: #002244;
            display: flex;
            align-items: center;
            justify-content: space-between;
            margin-bottom: 30px;
            box-shadow: 0 10px 25px rgba(0, 34, 68, 0.05);
            border: 1px solid #c9dcf0;
            position: relative;
            overflow: hidden;
        }
        
        .visual-header h2 {
            font-size: 32px; 
            color: #002244; 
            margin-bottom: 10px;
        }

        .visual-header::after {
            content: '\f06b'; /* fa-gift icon */
            font-family: "Font Awesome 6 Free";
            font-weight: 900;
            position: absolute;
            right: 20px;
            top: -20px;
            font-size: 150px;
            color: rgba(212, 175, 55, 0.1);
            transform: rotate(-15deg);
        }

        .img-placeholder {
            width: 100%;
            height: 140px;
            background-color: #e2e8f0;
            border-radius: 8px;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            overflow: hidden;
        }

        /* Thẻ Xanh nhạt mô phỏng hộp thông tin góc dưới Poster */
        .blue-card {
            background-color: #eaf2fa;
            background-image: linear-gradient(180deg, #eff5fc 0%, #d4e3f1 100%);
            border: 1px solid #ffffff;
            color: #002244;
        }

        /* Responsive */
        @media (max-width: 900px) {
            .grid-4 { grid-template-columns: repeat(2, 1fr); gap: 20px; } 
            .grid-2, .grid-3 { grid-template-columns: 1fr; }
            .tabs { flex-direction: column; }
            .tab-btn { border-radius: 12px; text-align: left; padding: 15px 20px; justify-content: flex-start; }
            .header-logo-box { display: none; }
            .header-title { font-size: 28px; }
        }
    </style>
</head>
<body>

    <header>
        <div class="header-logo-box">
            <span class="num">38</span>
            <span class="text">NĂM</span>
        </div>
        <div class="header-title">Tổng Hợp Ưu Đãi PNJ Online<br><span style="font-size: 24px; font-weight: 600; color: #D4AF37;">Tháng 04/2026</span></div>
    </header>

    <div class="global-warning">
        <i class="fa-solid fa-triangle-exclamation"></i>
        <div>
            <strong>LƯU Ý NGOẠI TRỪ CHUNG CHO HẦU HẾT CÁC MÃ/CTKM:</strong><br>
            KHÔNG ÁP DỤNG cho: Trang sức Ý, Dây chuyền/SP không gắn đá (Vàng/Platinum), Vàng Tài Lộc, Kim Bảo Cát Tường, Đồng vàng/Quà tặng 22k/24k, Nhẫn trơn, Trang sức vàng 22k/23k/24k, Kim cương/Đá rời, Trang sức bộ lớn, Phụ kiện, PNJ Art. <em>(Vui lòng kiểm tra chi tiết theo từng tab)</em>.
        </div>
    </div>

    <div class="tabs-container">
        <div class="tabs">
            <button class="tab-btn active" onclick="openTab(event, 'tab1')">
                <i class="fa-solid fa-cake-candles" style="color: #D4AF37;"></i> Sinh Nhật PNJ 38 Năm
            </button>
            <button class="tab-btn" onclick="openTab(event, 'tab2')">
                <i class="fa-solid fa-tags" style="color: #D4AF37;"></i> Chương Trình AWO
            </button>
            <button class="tab-btn" onclick="openTab(event, 'tab3')">
                <i class="fa-solid fa-qrcode" style="color: #D4AF37;"></i> Code AWO (Mã Gửi Tự Động)
            </button>
        </div>
    </div>

    <main>
        <!-- TAB 1: SINH NHẬT -->
        <div id="tab1" class="tab-content active">
            <div class="visual-header">
                <div style="position: relative; z-index: 2;">
                    <div class="card-badge" style="position: static; display: inline-block; margin-bottom: 15px;">10/04 - 03/05/2026</div>
                    <h2>Sinh Nhật PNJ 38 Năm trên ZMP<br>và hoạt động out-of-store</h2>
                    <p style="font-size: 16px; opacity: 0.9; max-width: 650px; font-weight: 500;">Chuỗi hoạt động tương tác và tri ân khách hàng triển khai chính thức trên nền tảng <strong>Zalo Mini App (ZMP)</strong>, mang đến hàng ngàn quà tặng và mã ưu đãi giá trị.</p>
                </div>
            </div>
            
            <div class="grid-2">
                <div class="card highlight">
                    <div class="img-placeholder" style="background-color: #fcf9f0; background-image: linear-gradient(135deg, #fdf1cd 0%, #ffffff 100%);">
                        <i class="fa-solid fa-gem" style="font-size: 40px; color: #D4AF37;"></i>
                    </div>
                    <h3><i class="fa-solid fa-puzzle-piece"></i> 1. Sưu Tầm Mảnh Ghép Nhận Quà Vàng</h3>
                    <p style="margin-bottom: 15px; font-size: 14px;">Hoạt động tương tác trên ZMP giúp khách hàng thu thập mảnh ghép đổi quà giá trị.</p>
                    <ul>
                        <li><strong>Điều kiện:</strong> Thu thập đủ 04 mảnh ghép.</li>
                        <li><strong>Quà tặng:</strong> <span class="highlight-text">Thẻ vàng may mắn trị giá 6.990.000Đ</span>.</li>
                        <li><strong>Số lượng:</strong> Duy nhất 03 giải trong chương trình.</li>
                    </ul>
                    <div class="note-box" style="margin-top: auto; font-size: 13px;">
                        * Không áp dụng cho NV nội bộ. Mỗi KH nhận 1 thẻ, không quy tiền mặt.
                    </div>
                </div>

                <div class="card">
                    <div class="img-placeholder" style="background-color: #002244; background-image: linear-gradient(135deg, #002244 0%, #003274 100%);">
                        <i class="fa-solid fa-gift" style="font-size: 40px; color: #D4AF37;"></i>
                    </div>
                    <h3><i class="fa-brands fa-weixin"></i> 2. Quà Tặng Cho Khách Không Mua Hàng</h3>
                    <p style="margin-bottom: 15px; font-size: 14px;">Tham gia hoạt động trên ZMP nhận ngẫu nhiên quà tri ân không cần hóa đơn.</p>
                    <ul>
                        <li><strong>Quà 1:</strong> Thẻ Dát Vàng Cinnamoroll trị giá <span class="navy-text">500.000Đ</span> (30 phần).</li>
                        <li><strong>Quà 2:</strong> 10 Mặt Nạ Giấy TFS (20 phần).</li>
                    </ul>
                    <div class="note-box" style="margin-top: auto; font-size: 13px;">
                        * Lưu vào ví quà tặng KH. Không cấp lại, không quy tiền mặt.
                    </div>
                </div>
            </div>

            <h3 class="section-title"><i class="fa-solid fa-qrcode" style="color: #D4AF37; margin-right: 8px;"></i> 3. Tham Gia Nhận Ưu Đãi Mua Hàng (HSD: 04/06)</h3>
            <p style="font-size: 15px; margin-bottom: 5px; font-weight: 500;">Khách hàng quét mã QR tại sự kiện hoặc tham gia trên ZMP để lưu mã ưu đãi vào ví quà tặng.</p>
            
            <div class="saledeal-tag" style="margin-top: 10px;"><i class="fa-solid fa-barcode"></i> SALEDEAL 20: TBU</div>
            
            <div class="grid-4">
                <div class="gold-card">
                    <div class="offer-badge">KH MỚI</div>
                    <div class="offer-title">MÃ 9%</div>
                    <div class="offer-sub">Tối đa 1.5 triệu</div>
                </div>
                <div class="gold-card">
                    <div class="offer-badge" style="background-color: #002244; color: #ffffff;">MỚI & CŨ</div>
                    <div class="offer-title">MÃ 360K</div>
                    <div class="offer-sub">Đơn từ 4 triệu</div>
                </div>
                <div class="gold-card">
                    <div class="offer-badge" style="background-color: #002244; color: #ffffff;">MỚI & CŨ</div>
                    <div class="offer-title">MÃ 1.2 TR</div>
                    <div class="offer-sub">Đơn từ 15 triệu</div>
                </div>
                <div class="gold-card">
                    <div class="offer-badge" style="background-color: #002244; color: #ffffff;">MỚI & CŨ</div>
                    <div class="offer-title">MÃ 1.6 TR</div>
                    <div class="offer-sub">Đơn từ 20 triệu</div>
                </div>
                
                <div class="gold-card">
                    <div class="offer-badge" style="background-color: #002244; color: #ffffff;">MỚI & CŨ</div>
                    <div class="offer-title">MÃ 800K</div>
                    <div class="offer-sub">Đơn từ 10 triệu</div>
                </div>
                <div class="gold-card">
                    <div class="offer-badge" style="background-color: #002244; color: #ffffff;">MỚI & CŨ</div>
                    <div class="offer-title">MÃ 100K</div>
                    <div class="offer-sub">Bạc/HKCC từ 850K</div>
                </div>
                <div class="gold-card">
                    <div class="offer-badge" style="background-color: #002244; color: #ffffff;">MỚI & CŨ</div>
                    <div class="offer-title">MÃ 200K</div>
                    <div class="offer-sub">Bạc/HKCC từ 1.7tr</div>
                </div>
                <div class="gold-card">
                    <div class="offer-badge" style="background-color: #002244; color: #ffffff;">MỚI & CŨ</div>
                    <div class="offer-title">MÃ 5%</div>
                    <div class="offer-sub">TS Ý/Dây chuyền</div>
                </div>
                
                <div class="gold-card">
                    <div class="offer-badge" style="background-color: #002244; color: #ffffff;">MỚI & CŨ</div>
                    <div class="offer-title">MÃ 12%</div>
                    <div class="offer-sub">STYLE by PNJ</div>
                </div>
                <div class="gold-card">
                    <div class="offer-badge" style="background-color: #002244; color: #ffffff;">MỚI & CŨ</div>
                    <div class="offer-title">MÃ 10%</div>
                    <div class="offer-sub">Hello Kitty</div>
                </div>
                <div class="gold-card">
                    <div class="offer-badge" style="background-color: #002244; color: #ffffff;">MỚI & CŨ</div>
                    <div class="offer-title">MÃ 14%</div>
                    <div class="offer-sub">Disney, Doraemon...</div>
                </div>
            </div>

            <div class="note-box">
                <strong>Điều kiện:</strong> Mã dùng được sau 30p nhận tin. ĐƯỢC gộp Cổng thanh toán & Trả góp. KHÔNG gộp KM khác/Thẻ VIP.
            </div>

            <div class="tab-footer">
                Chi tiết xem thêm tại <a href="https://pnjcomvn-my.sharepoint.com/:w:/r/personal/hau_hp_pnj_com_vn/_layouts/15/Doc.aspx?sourcedoc=%7B9937F117-E203-486E-94C3-E823A85230A2%7D&file=TH%C3%94NG-B%C3%81O-CTKM-ONLINE-TH%C3%81NG-04-2026.docx&action=default&mobileredirect=true" target="_blank">Thông báo CTKM Online tháng 04.2026</a>
            </div>
        </div>

        <!-- TAB 2: CHƯƠNG TRÌNH AWO -->
        <div id="tab2" class="tab-content">
            <h2 class="section-title">Chương Trình AWO Khuyến Mãi Trực Tiếp</h2>

            <div class="grid-2">
                <div class="card highlight" style="text-align: center; border-width: 3px;">
                    <div class="card-badge">07/04 - 30/04</div>
                    <h3 style="justify-content: center; margin-bottom: 5px;"><i class="fa-solid fa-fire"></i> CHƯƠNG TRÌNH TABSALE</h3>
                    <div class="saledeal-tag" style="margin: 0 auto 15px;"><i class="fa-solid fa-barcode"></i> SALEDEAL: TBU</div>
                    
                    <div style="display: flex; justify-content: space-around; margin: 20px 0;">
                        <div>
                            <div style="font-size: 15px; font-weight: 700; color: #002244; text-transform: uppercase;">Trang Sức Vàng</div>
                            <div class="huge-discount">35%</div>
                        </div>
                        <div style="width: 2px; background-color: #e2e8f0;"></div>
                        <div>
                            <div style="font-size: 15px; font-weight: 700; color: #002244; text-transform: uppercase;">Trang Sức Bạc</div>
                            <div class="huge-discount">50%</div>
                        </div>
                    </div>
                    <div class="note-box" style="text-align: left;">
                        <strong>Lưu ý:</strong> Chỉ áp dụng chọn hàng CÓ SẴN (đủ size/ni). KHÔNG áp dụng đặt hàng lại. KHÔNG gộp KM khác/Thẻ VIP.
                    </div>
                </div>

                <div>
                    <div class="card" style="margin-bottom: 25px;">
                        <div class="card-badge">01/02 - 30/04</div>
                        <h3 style="margin-bottom: 5px;"><i class="fa-solid fa-cart-shopping"></i> Style by PNJ (Sàn TMĐT)</h3>
                        <div class="saledeal-tag"><i class="fa-solid fa-barcode"></i> SALEDEAL: 70006594</div>
                        <p style="margin-bottom: 15px; font-size: 14px;">Áp dụng trên gian hàng chính hãng Shopee / Tiktok.</p>
                        
                        <div style="background-color: #f8fafc; border: 1px solid #e2e8f0; border-left: 4px solid #002244; padding: 15px; border-radius: 8px;">
                            <div style="display: flex; justify-content: space-between; align-items: center; margin-bottom: 5px;">
                                <span style="font-weight: 600; font-size: 15px;">Trang sức Bạc</span>
                                <span class="navy-text" style="font-size: 18px; font-family: 'Playfair Display', serif;">Ưu đãi đến 20%</span>
                            </div>
                            <div style="font-size: 13px; color: #64748b; font-style: italic;">(Áp dụng theo danh mục SP chọn lọc)</div>
                        </div>
                    </div>

                    <div class="card">
                        <div class="card-badge">01/04 - 30/06</div>
                        <h3 style="margin-bottom: 5px;"><i class="fa-solid fa-video"></i> Ưu Đãi Livestream</h3>
                        <div class="saledeal-tag"><i class="fa-solid fa-barcode"></i> SALEDEAL: TBU</div>
                        
                        <div style="background-color: #fcf9f0; border: 1px solid #fde68a; border-left: 4px solid #D4AF37; padding: 15px; border-radius: 8px;">
                            <div style="margin-bottom: 8px; font-size: 15px;"><span style="color: #64748b;">Hóa đơn từ:</span> <strong class="navy-text">1.500.000Đ</strong></div>
                            <div style="font-size: 15px;"><span style="color: #64748b;">Quà tặng:</span> <strong class="highlight-text" style="font-size: 16px;">Ghim/Pin thời trang</strong></div>
                        </div>

                        <div style="font-size: 13px; color: #ef4444; margin-top: 15px;">
                            <strong>* Bắt buộc:</strong> Ghi rõ nguồn đơn từ Livestream khi tạo SO/hóa đơn.
                        </div>
                    </div>
                </div>
            </div>

            <div class="tab-footer">
                Chi tiết xem thêm tại <a href="https://pnjcomvn-my.sharepoint.com/:w:/r/personal/hau_hp_pnj_com_vn/_layouts/15/Doc.aspx?sourcedoc=%7B9937F117-E203-486E-94C3-E823A85230A2%7D&file=TH%C3%94NG-B%C3%81O-CTKM-ONLINE-TH%C3%81NG-04-2026.docx&action=default&mobileredirect=true" target="_blank">Thông báo CTKM Online tháng 04.2026</a>
            </div>
        </div>

        <!-- TAB 3: CODE AWO -->
        <div id="tab3" class="tab-content">
            <h2 class="section-title">Code AWO (Mã Gửi Tự Động Qua SMS/ZNS)</h2>

            <div class="grid-2">
                <div class="card highlight" style="border-width: 3px; background-color: #002244; background-image: linear-gradient(135deg, #002244 0%, #003274 100%); color: #ffffff;">
                    <div class="card-badge" style="background-color: #ef4444; color: #ffffff; background-image: none;">KHÁCH HÀNG MỚI</div>
                    <h3 style="color: #D4AF37; margin-bottom: 5px;"><i class="fa-solid fa-user-plus"></i> Web-Engagement</h3>
                    <div class="saledeal-tag dark"><i class="fa-solid fa-barcode"></i> SALEDEAL 20: TBU</div>
                    <p style="margin-bottom: 15px; font-size: 14px; color: #cbd5e1;">Khách mới lần đầu giao dịch, điền form trên popup Website nhận mã ngay. (HSD 15 ngày)</p>
                    <div class="huge-discount" style="text-align: center; margin: 10px 0;">GIẢM 9%</div>
                    <p style="text-align: center; font-weight: 600; font-size: 14px; color: #ffffff;">Tối đa 1.500.000Đ</p>
                </div>

                <div class="card highlight" style="border-width: 3px;">
                    <div class="card-badge">GIỮ CHÂN KHÁCH</div>
                    <h3 style="margin-bottom: 5px;"><i class="fa-solid fa-door-open"></i> Exit Intent</h3>
                    <div class="saledeal-tag"><i class="fa-solid fa-barcode"></i> SALEDEAL: TBU</div>
                    <p style="margin-bottom: 20px; font-size: 14px;">Popup hiện ra khi khách có ý định thoát trang web. (HSD 30 ngày)</p>
                    <div class="grid-2" style="gap: 15px; margin-bottom: 0;">
                        <div class="gold-card" style="min-height: 80px;">
                            <div class="offer-badge" style="background-color: #002244; color: #ffffff;">KH CŨ</div>
                            <div class="offer-title">MÃ 8%</div>
                        </div>
                        <div class="gold-card" style="min-height: 80px;">
                            <div class="offer-badge">KH MỚI</div>
                            <div class="offer-title">MÃ 9%</div>
                        </div>
                    </div>
                </div>
            </div>

            <div style="display: flex; align-items: center; gap: 15px; margin-top: 20px;">
                <h3 class="section-title" style="font-size: 22px; margin: 0;">Mã CSKH & Mã Click & Collect</h3>
                <div class="saledeal-tag" style="margin: 0;"><i class="fa-solid fa-barcode"></i> SALEDEAL 20: TBU</div>
            </div>
            
            <p style="font-size: 14px; margin: 10px 0 20px; color: #ef4444; font-weight: 500;">
                <em>* Lưu ý: Mã Click & Collect chỉ có hạn dùng trong <strong>48 giờ</strong>. Mã CSKH hạn dùng theo SMS.</em>
            </p>
            
            <div class="grid-4">
                <!-- Vàng/Pt/ĐH -->
                <div class="gold-card">
                    <div class="offer-badge" style="background-color: #002244; color: #ffffff;">VÀNG/PT</div>
                    <div class="offer-title">GIẢM 150K</div>
                    <div class="offer-sub">Từ 2.000.000Đ</div>
                </div>
                <div class="gold-card">
                    <div class="offer-badge" style="background-color: #002244; color: #ffffff;">VÀNG/PT</div>
                    <div class="offer-title">GIẢM 300K</div>
                    <div class="offer-sub">Từ 4.000.000Đ</div>
                </div>
                <div class="gold-card">
                    <div class="offer-badge" style="background-color: #002244; color: #ffffff;">VÀNG/PT</div>
                    <div class="offer-title">GIẢM 450K</div>
                    <div class="offer-sub">Từ 6.000.000Đ</div>
                </div>
                <div class="gold-card">
                    <div class="offer-badge" style="background-color: #002244; color: #ffffff;">VÀNG/PT</div>
                    <div class="offer-title">GIẢM 800K</div>
                    <div class="offer-sub">Từ 10.000.000Đ</div>
                </div>
                <div class="gold-card">
                    <div class="offer-badge" style="background-color: #002244; color: #ffffff;">VÀNG/PT</div>
                    <div class="offer-title">GIẢM 1.2 TR</div>
                    <div class="offer-sub">Từ 15.000.000Đ</div>
                </div>
                <div class="gold-card">
                    <div class="offer-badge" style="background-color: #002244; color: #ffffff;">VÀNG/PT</div>
                    <div class="offer-title">GIẢM 2 TR</div>
                    <div class="offer-sub">Từ 25.000.000Đ</div>
                </div>
                <div class="gold-card">
                    <div class="offer-badge" style="background-color: #002244; color: #ffffff;">VÀNG/PT</div>
                    <div class="offer-title">GIẢM 3.2 TR</div>
                    <div class="offer-sub">Từ 40.000.000Đ</div>
                </div>
                <div class="gold-card">
                    <div class="offer-badge" style="background-color: #002244; color: #ffffff;">VÀNG/PT</div>
                    <div class="offer-title">GIẢM 4.2 TR</div>
                    <div class="offer-sub">Từ 60.000.000Đ</div>
                </div>
                <!-- Bạc (Blue Cards based on poster accent boxes) -->
                <div class="gold-card blue-card">
                    <div class="offer-badge" style="background-color: #64748b; color: #ffffff;">CHỈ BẠC</div>
                    <div class="offer-title">GIẢM 50K</div>
                    <div class="offer-sub">Từ 500.000Đ</div>
                </div>
                <div class="gold-card blue-card">
                    <div class="offer-badge" style="background-color: #64748b; color: #ffffff;">CHỈ BẠC</div>
                    <div class="offer-title">GIẢM 110K</div>
                    <div class="offer-sub">Từ 1.000.000Đ</div>
                </div>
                <div class="gold-card blue-card">
                    <div class="offer-badge" style="background-color: #64748b; color: #ffffff;">CHỈ BẠC</div>
                    <div class="offer-title">GIẢM 240K</div>
                    <div class="offer-sub">Từ 2.000.000Đ</div>
                </div>
            </div>

            <h3 class="section-title" style="font-size: 22px; margin-top: 10px;">Các Mã Code Hệ Thống Khác</h3>
            <div class="grid-3">
                <div class="card">
                    <h3 style="font-size: 18px; margin-bottom: 5px;"><i class="fa-solid fa-heart-crack"></i> Sorry Code</h3>
                    <div class="saledeal-tag"><i class="fa-solid fa-barcode"></i> SALEDEAL 20: TBU</div>
                    <ul>
                        <li>Đơn 200K &rarr; <span class="navy-text">Giảm 100K</span></li>
                        <li>Đơn 400K &rarr; <span class="navy-text">Giảm 200K</span></li>
                        <li>Đơn 1TR &rarr; <span class="navy-text">Giảm 500K</span></li>
                    </ul>
                </div>
                <div class="card">
                    <h3 style="font-size: 18px; margin-bottom: 5px;"><i class="fa-solid fa-user-check"></i> Code Retention</h3>
                    <div class="saledeal-tag"><i class="fa-solid fa-barcode"></i> SALEDEAL 20: TBU</div>
                    <ul>
                        <li>Mọi HĐ &rarr; <span class="navy-text">Giảm 8% (Max 1.5tr)</span></li>
                        <li>Đơn 20TR &rarr; <span class="navy-text">Giảm 1.6TR</span></li>
                        <li>Đơn 30TR &rarr; <span class="navy-text">Giảm 2.4TR</span></li>
                    </ul>
                </div>
                <div class="card">
                    <h3 style="font-size: 18px; margin-bottom: 5px;"><i class="fa-solid fa-store"></i> Code Marketplace</h3>
                    <div class="saledeal-tag"><i class="fa-solid fa-barcode"></i> SALEDEAL 20: TBU</div>
                    <ul>
                        <li>Bạc 300K &rarr; <span class="navy-text">Giảm 10%</span></li>
                        <li>Bạc 700K &rarr; <span class="navy-text">Giảm 12%</span></li>
                        <li>Đ.Hồ 1TR &rarr; <span class="navy-text">Giảm 10%</span></li>
                    </ul>
                </div>
            </div>

            <div class="tab-footer">
                Chi tiết xem thêm tại <a href="https://pnjcomvn-my.sharepoint.com/:w:/r/personal/hau_hp_pnj_com_vn/_layouts/15/Doc.aspx?sourcedoc=%7B9937F117-E203-486E-94C3-E823A85230A2%7D&file=TH%C3%94NG-B%C3%81O-CTKM-ONLINE-TH%C3%81NG-04-2026.docx&action=default&mobileredirect=true" target="_blank">Thông báo CTKM Online tháng 04.2026</a>
            </div>
        </div>
    </main>

    <script>
        function openTab(evt, tabId) {
            // Hide all tab contents
            const tabContents = document.getElementsByClassName("tab-content");
            for (let i = 0; i < tabContents.length; i++) {
                tabContents[i].classList.remove("active");
            }

            // Remove active class from all buttons
            const tabBtns = document.getElementsByClassName("tab-btn");
            for (let i = 0; i < tabBtns.length; i++) {
                tabBtns[i].classList.remove("active");
            }

            // Show current tab and add active class to clicked button
            document.getElementById(tabId).classList.add("active");
            evt.currentTarget.classList.add("active");
        }
    </script>
</body>
</html>
