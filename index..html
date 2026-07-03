<!DOCTYPE html>
<html lang="fa" dir="rtl">

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>درس‌یار</title>

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Vazirmatn:wght@300;400;500;700;800&display=swap" rel="stylesheet">

<style>
    :root {
        --main-color:#1565c0; --main-dark:#0d47a1; --main-light:#d6e8ff;
        --bg-color:#f5f7fb; --card-bg:#ffffff; --sidebar-bg:#111a2b;
        --text-color:#2b2b2b; --text-light:#666666; --border-c:#e3e7ee;
        --shadow:0 5px 15px rgba(0,0,0,0.08); --radius:12px;
    }
    body.theme-light-green {
        --main-color:#2e7d32; --main-dark:#1b5e20; --main-light:#c8e6c9;
        --bg-color:#f1f8f2; --card-bg:#ffffff; --sidebar-bg:#0f1f13;
        --text-color:#22301f; --text-light:#5c6b5f; --border-c:#dbe7d9;
    }
    body.theme-dark-blue {
        --main-color:#4f9dff; --main-dark:#2f7fe0; --main-light:#294064;
        --bg-color:#14161c; --card-bg:#1e212b; --sidebar-bg:#0b0d12;
        --text-color:#eef1f8; --text-light:#a3a9b8; --border-c:#2b2f3a;
        --shadow:0 5px 15px rgba(0,0,0,0.4);
    }
    body.theme-dark-green {
        --main-color:#4caf50; --main-dark:#357a38; --main-light:#25392a;
        --bg-color:#121613; --card-bg:#1c221d; --sidebar-bg:#0a0d0a;
        --text-color:#eaf3ea; --text-light:#a3b3a5; --border-c:#293029;
        --shadow:0 5px 15px rgba(0,0,0,0.4);
    }
    body.theme-dark-purple {
        --main-color:#b388ff; --main-dark:#8557e6; --main-light:#332b52;
        --bg-color:#15121c; --card-bg:#211c2c; --sidebar-bg:#0b0910;
        --text-color:#f1ecfb; --text-light:#b0a3c4; --border-c:#2c2438;
        --shadow:0 5px 15px rgba(0,0,0,0.4);
    }

    * { margin:0; padding:0; box-sizing:border-box; }
    html, body { overflow-x:hidden; }
    body {
        font-family:"Vazirmatn",sans-serif;
        background:var(--bg-color); color:var(--text-color);
        line-height:1.9; transition:background .3s,color .3s;
    }
    .hidden { display:none !important; }
    a { text-decoration:none; color:inherit; }
    button { font-family:inherit; cursor:pointer; border:none; background:none; }
    input, select, textarea { font-family:inherit; }
    ::placeholder { color:var(--text-light); opacity:.7; }

    /* ============ صفحه ورود اول ============ */
    #onboarding-screen { min-height:100vh; display:flex; align-items:center; justify-content:center; padding:20px; }
    .onboarding-box { background:var(--card-bg); border-radius:var(--radius); box-shadow:var(--shadow); padding:40px 30px; max-width:460px; width:100%; }
    .onboarding-box h1 { color:var(--main-color); text-align:center; margin-bottom:10px; font-size:26px; }
    .onboarding-box .sub { text-align:center; color:var(--text-light); margin-bottom:22px; font-size:14px; }
    .warning-box { background:#fff3cd; color:#7a5c00; border-radius:8px; padding:14px 16px; font-size:13px; margin-bottom:22px; line-height:1.7; }
    .form-group { margin-bottom:14px; }
    .form-group label { display:block; margin-bottom:6px; font-size:13px; color:var(--text-light); font-weight:500; }
    .form-group input, .form-group select, .form-group textarea {
        width:100%; padding:11px 14px; border-radius:8px; border:1px solid var(--border-c);
        background:var(--bg-color); color:var(--text-color); font-size:14px;
    }
    .big-btn { width:100%; background:var(--main-color); color:#fff; padding:13px; border-radius:10px; font-size:15px; font-weight:bold; transition:.3s; margin-top:6px; }
    .big-btn:hover { background:var(--main-dark); }

    /* ============ ساختار کلی: سایدبار + محتوا ============ */
    #app { display:flex; min-height:100vh; }

    .sidebar {
        position:fixed; top:0; left:0; height:100vh; width:220px;
        background:var(--sidebar-bg); color:#fff; z-index:200;
        transition:width .25s; display:flex; flex-direction:column; overflow:hidden;
    }
    .sidebar.collapsed { width:64px; }
    .sidebar-logo { display:flex; align-items:center; gap:10px; padding:18px 16px; font-weight:800; font-size:18px; white-space:nowrap; border-bottom:1px solid rgba(255,255,255,0.08); }
    .sidebar-logo .emoji { font-size:22px; flex-shrink:0; }
    .sidebar-nav { flex:1; padding:10px 8px; overflow-y:auto; }
    .sidebar-nav button {
        display:flex; align-items:center; gap:12px; width:100%; padding:11px 12px;
        border-radius:8px; color:#c7cde0; font-size:14px; margin-bottom:4px; white-space:nowrap;
        transition:.2s;
    }
    .sidebar-nav button:hover { background:rgba(255,255,255,0.08); color:#fff; }
    .sidebar-nav button.active { background:var(--main-color); color:#fff; }
    .sidebar-nav .icon { flex-shrink:0; width:20px; display:flex; align-items:center; justify-content:center; }
    .sidebar-logo .emoji { display:flex; align-items:center; justify-content:center; }
    .sidebar.collapsed .nav-label { display:none; }
    .sidebar.collapsed .sidebar-nav button { justify-content:center; padding:12px 0; gap:0; }
    .sidebar.collapsed .sidebar-logo { justify-content:center; padding:18px 0; gap:0; }
    .sidebar-nav button { justify-content:flex-start; }
    .sidebar-toggle-btn { padding:14px; color:#c7cde0; font-size:18px; text-align:center; border-top:1px solid rgba(255,255,255,0.08); }
    .sidebar-toggle-btn:hover { color:#fff; }

    .content-area { flex:1; margin-right:0; margin-left:220px; transition:margin-left .25s; min-width:0; }
    .sidebar.collapsed ~ .content-area { margin-left:64px; }

    /* ============ نوار بالا ============ */
    .topbar {
        position:sticky; top:0; z-index:150;
        background:var(--card-bg); border-bottom:1px solid var(--border-c);
        padding:12px 20px; display:flex; align-items:center; gap:14px;
    }
    .mobile-menu-btn { display:none; font-size:22px; color:var(--text-color); }
    .search-wrap { flex:1; position:relative; max-width:500px; }
    .search-wrap input {
        width:100%; padding:10px 40px 10px 14px; border-radius:20px; border:1px solid var(--border-c);
        background:var(--bg-color); color:var(--text-color); font-size:14px;
    }
    .search-wrap .search-icon { position:absolute; left:14px; top:50%; transform:translateY(-50%); color:var(--text-light); pointer-events:none; }
    .search-results {
        position:absolute; top:calc(100% + 6px); right:0; left:0; background:var(--card-bg);
        border-radius:10px; box-shadow:var(--shadow); max-height:340px; overflow-y:auto; z-index:180;
    }
    .search-result-item { padding:12px 16px; border-bottom:1px solid var(--border-c); cursor:pointer; font-size:14px; }
    .search-result-item:last-child { border-bottom:none; }
    .search-result-item:hover { background:var(--bg-color); }
    .search-result-item .sr-type { font-size:11px; color:var(--main-color); font-weight:600; }
    .theme-quick-toggle { font-size:20px; padding:8px; border-radius:50%; }
    .theme-quick-toggle:hover { background:var(--bg-color); }

    main { padding:26px 20px 60px; }
    .container { width:100%; max-width:1000px; margin:auto; }

    .page-title { color:var(--main-color); font-size:24px; margin-bottom:6px; }
    .page-sub { color:var(--text-light); margin-bottom:22px; font-size:14px; }

    .card { background:var(--card-bg); border-radius:var(--radius); box-shadow:var(--shadow); padding:22px; margin-bottom:18px; }
    .card h3 { color:var(--main-color); margin-bottom:14px; font-size:17px; display:flex; justify-content:space-between; align-items:center; }
    .view-all-link { font-size:13px; color:var(--main-color); font-weight:600; }

    /* ============ داشبورد خانه ============ */
    .greeting { font-size:21px; margin-bottom:3px; }
    .greeting-sub { color:var(--text-light); margin-bottom:22px; font-size:13px; }
    .dash-grid { display:grid; grid-template-columns:repeat(2,1fr); gap:16px; margin-bottom:16px; }
    .progress-bar-bg { background:var(--bg-color); border-radius:20px; height:12px; overflow:hidden; margin-top:8px; }
    .progress-bar-fill { background:var(--main-color); height:100%; transition:width .3s; }
    .mini-row { display:flex; justify-content:space-between; padding:8px 0; border-bottom:1px solid var(--border-c); font-size:14px; }
    .mini-row:last-child { border-bottom:none; }
    .quick-actions { display:flex; gap:12px; flex-wrap:wrap; }
    .quick-actions button { background:var(--main-color); color:#fff; padding:12px 20px; border-radius:10px; font-weight:600; font-size:14px; }
    .quick-actions button:hover { background:var(--main-dark); }
    .quick-actions button.secondary { background:var(--bg-color); color:var(--main-color); border:1px solid var(--main-color); }

    /* ============ فرم‌های افزودن ============ */
    .add-row { display:flex; gap:10px; flex-wrap:wrap; margin-bottom:18px; }
    .add-row input, .add-row select { padding:10px 14px; border-radius:8px; border:1px solid var(--border-c); background:var(--bg-color); color:var(--text-color); flex:1; min-width:120px; }
    .add-row button { background:var(--main-color); color:#fff; padding:10px 20px; border-radius:8px; font-weight:bold; white-space:nowrap; }
    .add-row button:hover { background:var(--main-dark); }

    .tag-chip { display:inline-block; background:var(--main-light); color:var(--main-dark); font-size:11px; padding:3px 10px; border-radius:20px; margin-left:4px; }

    /* ============ تسک‌ها ============ */
    .task-item, .habit-item, .exam-item { display:flex; align-items:center; justify-content:space-between; padding:13px 0; border-bottom:1px solid var(--border-c); gap:10px; flex-wrap:wrap; }
    .task-item:last-child, .habit-item:last-child, .exam-item:last-child { border-bottom:none; }
    .task-left { display:flex; align-items:center; gap:12px; flex-wrap:wrap; }
    .task-left input[type=checkbox] { width:19px; height:19px; cursor:pointer; }
    .task-tag { background:var(--main-light); color:var(--main-dark); font-size:11px; padding:3px 10px; border-radius:20px; }
    .delete-btn { color:#e05353; font-size:12px; padding:4px 8px; }
    .archive-toggle { color:var(--main-color); font-weight:600; font-size:14px; margin:6px 0 10px; }

    /* ============ یادداشت‌ها ============ */
    .note-item { border-bottom:1px solid var(--border-c); padding:11px 0; }
    .note-item:last-child { border-bottom:none; }
    .note-title-row { display:flex; justify-content:space-between; align-items:center; cursor:pointer; }
    .note-title-row span.t { font-weight:600; }
    .note-content { margin-top:9px; color:var(--text-light); font-size:14px; white-space:pre-wrap; }

    /* ============ عادت‌ها ============ */
    .habit-name { font-weight:600; }
    .habit-count { color:var(--text-light); font-size:12px; }
    .habit-btn { background:var(--bg-color); color:var(--main-color); padding:7px 14px; border-radius:8px; font-weight:600; font-size:12px; border:1px solid var(--main-color); }
    .habit-btn.done { background:var(--main-color); color:#fff; }

    /* ============ برنامه‌ریز ============ */
    .planner-type-switch { display:flex; gap:10px; margin-bottom:18px; }
    .planner-type-switch button { flex:1; padding:11px; border-radius:8px; background:var(--card-bg); color:var(--text-color); box-shadow:var(--shadow); font-weight:600; }
    .planner-type-switch button.active { background:var(--main-color); color:#fff; }
    .schedule-item { display:flex; justify-content:space-between; align-items:center; padding:11px 0; border-bottom:1px solid var(--border-c); }
    .schedule-item:last-child { border-bottom:none; }
    .schedule-time { background:var(--main-light); color:var(--main-dark); padding:4px 12px; border-radius:20px; font-size:12px; font-weight:600; white-space:nowrap; }
    .day-group h4 { color:var(--main-color); margin:16px 0 8px; font-size:14px; }
    .day-group:first-child h4 { margin-top:0; }

    /* ============ مطالعه: پومودورو و کرونومتر ============ */
    .study-grid { display:grid; grid-template-columns:1fr 1fr; gap:18px; }
    .timer-display { font-size:52px; font-weight:800; text-align:center; color:var(--main-color); margin:14px 0; letter-spacing:2px; }
    .timer-mode-label { text-align:center; font-size:13px; color:var(--text-light); }
    .timer-controls { display:flex; gap:10px; justify-content:center; margin-top:14px; }
    .timer-controls button { background:var(--main-color); color:#fff; padding:10px 18px; border-radius:8px; font-weight:600; font-size:13px; }
    .timer-controls button.reset-btn { background:var(--bg-color); color:var(--text-color); border:1px solid var(--border-c); }
    .pomodoro-config { display:flex; gap:10px; margin-top:14px; }
    .pomodoro-config div { flex:1; }
    .pomodoro-config label { font-size:12px; color:var(--text-light); display:block; margin-bottom:4px; }
    .pomodoro-config input { width:100%; padding:8px; border-radius:6px; border:1px solid var(--border-c); background:var(--bg-color); color:var(--text-color); }

    /* ============ پروفایل/تنظیمات ============ */
    .stats-grid { display:grid; grid-template-columns:repeat(3,1fr); gap:12px; margin-bottom:16px; }
    .stat-mini { background:var(--bg-color); border-radius:10px; text-align:center; padding:14px 6px; }
    .stat-mini .num { font-size:22px; font-weight:800; color:var(--main-color); }
    .stat-mini .label { font-size:11px; color:var(--text-light); margin-top:4px; }
    .danger-btn { background:#d64545; color:#fff; padding:11px 20px; border-radius:8px; font-weight:bold; }

    .theme-grid { display:grid; grid-template-columns:repeat(5,1fr); gap:12px; margin-bottom:6px; }
    .theme-option { border-radius:12px; padding:12px 6px; text-align:center; cursor:pointer; border:2px solid transparent; font-size:12px; font-weight:600; position:relative; }
    .theme-option.selected { border-color:var(--main-color); }
    .theme-dot { width:28px; height:28px; border-radius:50%; margin:0 auto 8px; }
    .theme-check { position:absolute; top:4px; left:4px; background:var(--main-color); color:#fff; width:16px; height:16px; border-radius:50%; font-size:10px; display:flex; align-items:center; justify-content:center; }
    .dot-light-blue { background:linear-gradient(135deg,#1565c0,#0d47a1); }
    .dot-light-green { background:linear-gradient(135deg,#2e7d32,#1b5e20); }
    .dot-dark-blue { background:linear-gradient(135deg,#1a1c22,#4f9dff); }
    .dot-dark-green { background:linear-gradient(135deg,#12161c,#4caf50); }
    .dot-dark-purple { background:linear-gradient(135deg,#15121c,#b388ff); }

    .about-text p { color:var(--text-light); margin-bottom:10px; font-size:14px; }
    .about-text b { color:var(--text-color); }

    .empty-msg { color:var(--text-light); font-size:14px; text-align:center; padding:18px 0; }

    /* ============ مودال تایید حذف ============ */
    .modal-overlay { position:fixed; inset:0; background:rgba(0,0,0,0.5); z-index:300; display:flex; align-items:center; justify-content:center; padding:20px; }
    .modal-box { background:var(--card-bg); border-radius:var(--radius); padding:28px; max-width:400px; width:100%; }
    .modal-box h3 { color:#d64545; margin-bottom:12px; }
    .modal-box p { color:var(--text-light); font-size:14px; margin-bottom:10px; }
    .modal-list { background:var(--bg-color); border-radius:8px; padding:12px 16px; margin-bottom:16px; font-size:13px; }
    .modal-list div { padding:3px 0; }
    .modal-warning { color:#d64545; font-weight:600; font-size:13px; margin-bottom:18px; }
    .modal-actions { display:flex; gap:10px; }
    .modal-actions button { flex:1; padding:11px; border-radius:8px; font-weight:600; }
    .modal-cancel { background:var(--bg-color); color:var(--text-color); border:1px solid var(--border-c); }
    .modal-confirm { background:#d64545; color:#fff; }

    /* ============ ریسپانسیو ============ */
    @media (max-width:900px) {
        .sidebar { transform:translateX(100%); }
        .sidebar.mobile-open { transform:translateX(0); }
        .content-area { margin-left:0 !important; }
        .mobile-menu-btn { display:block; }
        .dash-grid, .study-grid { grid-template-columns:1fr; }
        .theme-grid { grid-template-columns:repeat(3,1fr); }
        .stats-grid { grid-template-columns:1fr 1fr; }
    }
</style>
</head>

<body>

<!-- ============ صفحه ورود اول ============ -->
<div id="onboarding-screen">
    <div class="onboarding-box">
        <h1>به درس‌یار خوش اومدی</h1>
        <p class="sub">قبل از شروع، چندتا سوال کوچیک ازت می‌پرسیم.</p>
        <div class="warning-box"><svg width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="vertical-align:-2px;margin-left:4px"><path d="M12 2L2 21h20L12 2z"/><path d="M12 9v5M12 17h.01"/></svg>توجه: تمام اطلاعاتی که اینجا وارد می‌کنی فقط روی همین مرورگر و همین دستگاه ذخیره می‌شه. اگه از دستگاه یا مرورگر دیگه‌ای وارد بشی، این اطلاعات رو نمی‌بینی.</div>
        <form id="onboarding-form">
            <div class="form-group"><label>اسم *</label><input type="text" id="ob-firstname" required placeholder="مثلاً محمد"></div>
            <div class="form-group"><label>فامیل (اختیاری)</label><input type="text" id="ob-lastname" placeholder="اختیاری"></div>
            <div class="form-group"><label>سن</label><input type="number" id="ob-age" min="5" max="25" required placeholder="مثلاً ۱۵"></div>
            <div class="form-group">
                <label>پایه (کلاس چندمی؟)</label>
                <select id="ob-grade" required>
                    <option value="">انتخاب کن</option>
                    <option value="5">پنجم</option><option value="6">ششم</option><option value="7">هفتم</option>
                    <option value="8">هشتم</option><option value="9">نهم</option><option value="10">دهم</option>
                    <option value="11">یازدهم</option><option value="12">دوازدهم</option>
                </select>
            </div>
            <button type="submit" class="big-btn">شروع کن</button>
        </form>
    </div>
</div>

<!-- ============ اپلیکیشن اصلی ============ -->
<div id="app" class="hidden">
    <aside class="sidebar" id="sidebar">
        <div class="sidebar-logo"><span class="emoji"><svg width="30" height="30" viewBox="0 0 512 512"><defs><linearGradient id="bgGrad" x1="0" y1="0" x2="512" y2="512" gradientUnits="userSpaceOnUse"><stop offset="0%" stop-color="#1E88E5"/><stop offset="100%" stop-color="#0D47A1"/></linearGradient><linearGradient id="pageLeft" x1="130" y1="180" x2="256" y2="360" gradientUnits="userSpaceOnUse"><stop offset="0%" stop-color="#FFFFFF"/><stop offset="100%" stop-color="#E8F1FC"/></linearGradient><linearGradient id="pageRight" x1="256" y1="180" x2="382" y2="360" gradientUnits="userSpaceOnUse"><stop offset="0%" stop-color="#F4F9FF"/><stop offset="100%" stop-color="#D6E8FC"/></linearGradient></defs><rect width="512" height="512" rx="112" fill="url(#bgGrad)"/><path d="M256 196 C 222 178, 176 172, 138 184 L 138 344 C 176 332, 222 338, 256 356 Z" fill="url(#pageLeft)"/><path d="M256 196 C 290 178, 336 172, 374 184 L 374 344 C 336 332, 290 338, 256 356 Z" fill="url(#pageRight)"/><line x1="256" y1="196" x2="256" y2="356" stroke="#0D47A1" stroke-width="4" stroke-linecap="round" opacity="0.35"/><path d="M164 220 L228 234 M164 250 L228 264 M164 280 L212 291" stroke="#0D47A1" stroke-width="6" stroke-linecap="round" opacity="0.28"/><path d="M348 220 L284 234 M348 250 L284 264 M348 280 L300 291" stroke="#0D47A1" stroke-width="6" stroke-linecap="round" opacity="0.28"/><path d="M392 118 C 396 132, 404 140, 418 144 C 404 148, 396 156, 392 170 C 388 156, 380 148, 366 144 C 380 140, 388 132, 392 118 Z" fill="#FFC107"/></svg></span><span class="nav-label">درس‌یار</span></div>
        <nav class="sidebar-nav" id="sidebar-nav">
            <button data-tab="home"><span class="icon"><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M3 11l9-8 9 8"/><path d="M5 10v10h14V10"/></svg></span><span class="nav-label">خانه</span></button>
            <button data-tab="tasks"><span class="icon"><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="3" width="18" height="18" rx="2"/><path d="M8 12l3 3 5-6"/></svg></span><span class="nav-label">تسک‌ها</span></button>
            <button data-tab="notes"><span class="icon"><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M6 2h9l5 5v15H6z"/><path d="M9 13h6M9 17h6M9 9h3"/></svg></span><span class="nav-label">یادداشت‌ها</span></button>
            <button data-tab="habits"><span class="icon"><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 22c-4 0-7-3-7-7 0-4 3-6 4-9 1 2 2 3 3 3 0-2 1-3 3-4 0 3 3 4 3 8 0 4-2 9-6 9z"/></svg></span><span class="nav-label">عادت‌ها</span></button>
            <button data-tab="exams"><span class="icon"><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="4" width="18" height="18" rx="2"/><path d="M3 9h18M8 2v4M16 2v4"/></svg></span><span class="nav-label">امتحان‌ها</span></button>
            <button data-tab="study"><span class="icon"><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="13" r="8"/><path d="M12 9v4l3 2M9 2h6"/></svg></span><span class="nav-label">مطالعه</span></button>
            <button data-tab="planner"><span class="icon"><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="4" width="18" height="18" rx="2"/><path d="M3 9h18M8 2v4M16 2v4M8 14h3M8 18h6"/></svg></span><span class="nav-label">برنامه‌ریز</span></button>
            <button data-tab="settings"><span class="icon"><svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="3"/><path d="M19.4 15a1.65 1.65 0 00.33 1.82l.06.06a2 2 0 11-2.83 2.83l-.06-.06a1.65 1.65 0 00-1.82-.33 1.65 1.65 0 00-1 1.51V21a2 2 0 01-4 0v-.09a1.65 1.65 0 00-1-1.51 1.65 1.65 0 00-1.82.33l-.06.06a2 2 0 11-2.83-2.83l.06-.06a1.65 1.65 0 00.33-1.82 1.65 1.65 0 00-1.51-1H3a2 2 0 010-4h.09a1.65 1.65 0 001.51-1 1.65 1.65 0 00-.33-1.82l-.06-.06a2 2 0 112.83-2.83l.06.06a1.65 1.65 0 001.82.33H9a1.65 1.65 0 001-1.51V3a2 2 0 014 0v.09a1.65 1.65 0 001 1.51 1.65 1.65 0 001.82-.33l.06-.06a2 2 0 112.83 2.83l-.06.06a1.65 1.65 0 00-.33 1.82V9a1.65 1.65 0 001.51 1H21a2 2 0 010 4h-.09a1.65 1.65 0 00-1.51 1z"/></svg></span><span class="nav-label">تنظیمات</span></button>
        </nav>
        <button class="sidebar-toggle-btn" id="sidebar-collapse-btn">◀</button>
    </aside>

    <div class="content-area">
        <div class="topbar">
            <button class="mobile-menu-btn" id="mobile-menu-btn"><svg width="22" height="22" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"><path d="M3 6h18M3 12h18M3 18h18"/></svg></button>
            <div class="search-wrap">
                <input type="text" id="global-search" placeholder="جستجو در همه‌جا...">
                <span class="search-icon"><svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="11" cy="11" r="7"/><path d="M21 21l-4.35-4.35"/></svg></span>
                <div class="search-results hidden" id="search-results"></div>
            </div>
            <button class="theme-quick-toggle" id="theme-quick-toggle"><svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 12.8A9 9 0 1111.2 3a7 7 0 009.8 9.8z"/></svg></button>
        </div>
        <main><div class="container" id="main-content"></div></main>
    </div>
</div>

<script>
const KEYS = {
    user:'daras_user', tasks:'daras_tasks', notes:'daras_notes', habits:'daras_habits',
    exams:'daras_exams', plannerHourly:'daras_planner_hourly', plannerWeekly:'daras_planner_weekly',
    plannerType:'daras_planner_type', theme:'daras_theme', sidebarCollapsed:'daras_sidebar_collapsed',
    pomodoroConfig:'daras_pomodoro_config'
};

function getData(key, fallback){ const raw = localStorage.getItem(key); return raw ? JSON.parse(raw) : fallback; }
function setData(key, value){ localStorage.setItem(key, JSON.stringify(value)); }
function uid(){ return Date.now().toString(36) + Math.random().toString(36).slice(2,7); }
function todayStr(){ return new Date().toISOString().slice(0,10); }
function gradeName(g){ const n={5:'پنجم',6:'ششم',7:'هفتم',8:'هشتم',9:'نهم',10:'دهم',11:'یازدهم',12:'دوازدهم'}; return n[g]||g; }
function escapeHtml(str){ const d=document.createElement('div'); d.textContent = str||''; return d.innerHTML; }
function parseTags(str){ return (str||'').split(',').map(t=>t.trim()).filter(Boolean); }
function tagsHtml(tags){ return (tags||[]).map(t=>`<span class="tag-chip">#${escapeHtml(t)}</span>`).join(''); }

let currentTab = 'home';

/* ============================================================ راه‌اندازی اولیه ============================================================ */
function init(){
    const theme = getData(KEYS.theme, 'light-blue');
    if (theme !== 'light-blue') document.body.classList.add('theme-' + theme);
    document.getElementById('theme-quick-toggle').innerHTML = theme.startsWith('dark') ? SUN_ICON : MOON_ICON;

    if (getData(KEYS.sidebarCollapsed, false)) {
        document.getElementById('sidebar').classList.add('collapsed');
        document.getElementById('sidebar-collapse-btn').textContent = '▶';
    }

    const user = getData(KEYS.user, null);
    if (user){
        document.getElementById('onboarding-screen').classList.add('hidden');
        document.getElementById('app').classList.remove('hidden');
        renderTab('home');
    } else {
        document.getElementById('onboarding-screen').classList.remove('hidden');
        document.getElementById('app').classList.add('hidden');
    }
}

document.getElementById('onboarding-form').addEventListener('submit', function(e){
    e.preventDefault();
    const user = {
        firstName: document.getElementById('ob-firstname').value.trim(),
        lastName: document.getElementById('ob-lastname').value.trim(),
        age: document.getElementById('ob-age').value,
        grade: document.getElementById('ob-grade').value,
        firstVisitDate: todayStr()
    };
    setData(KEYS.user, user);
    document.getElementById('onboarding-screen').classList.add('hidden');
    document.getElementById('app').classList.remove('hidden');
    renderTab('home');
});

/* ============================================================ سایدبار ============================================================ */
document.getElementById('sidebar-nav').addEventListener('click', function(e){
    const btn = e.target.closest('button[data-tab]');
    if (!btn) return;
    renderTab(btn.dataset.tab);
    document.getElementById('sidebar').classList.remove('mobile-open');
});

document.getElementById('sidebar-collapse-btn').addEventListener('click', function(){
    const sb = document.getElementById('sidebar');
    sb.classList.toggle('collapsed');
    const collapsed = sb.classList.contains('collapsed');
    this.textContent = collapsed ? '▶' : '◀';
    setData(KEYS.sidebarCollapsed, collapsed);
});

document.getElementById('mobile-menu-btn').addEventListener('click', function(){
    document.getElementById('sidebar').classList.toggle('mobile-open');
});

function renderTab(tab){
    currentTab = tab;
    document.querySelectorAll('.sidebar-nav button').forEach(b => b.classList.toggle('active', b.dataset.tab === tab));
    const map = { home:renderHome, tasks:renderTasks, notes:()=>renderNotes(''), habits:renderHabits, exams:renderExams, study:renderStudy, planner:renderPlanner, settings:renderSettings };
    map[tab]();
    window.scrollTo(0,0);
}

/* ============================================================ تم روشن/تیره سریع + کامل ============================================================ */
document.getElementById('theme-quick-toggle').addEventListener('click', function(){
    const cur = getData(KEYS.theme, 'light-blue');
    const isDark = cur.startsWith('dark');
    const next = isDark ? 'light-blue' : 'dark-blue';
    applyTheme(next);
});

const SUN_ICON = '<svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="4"/><path d="M12 2v2M12 20v2M4 12H2M22 12h-2M4.9 4.9l1.4 1.4M17.7 17.7l1.4 1.4M4.9 19.1l1.4-1.4M17.7 6.3l1.4-1.4"/></svg>';
const MOON_ICON = '<svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 12.8A9 9 0 1111.2 3a7 7 0 009.8 9.8z"/></svg>';

function ic(name, size){
    size = size || 15;
    const paths = {
        warning: '<path d="M12 2L2 21h20L12 2z"/><path d="M12 9v5M12 17h.01"/>',
        check: '<path d="M4 12l6 6L20 6"/>',
        fire: '<path d="M12 22c-4 0-7-3-7-7 0-4 3-6 4-9 1 2 2 3 3 3 0-2 1-3 3-4 0 3 3 4 3 8 0 4-2 9-6 9z"/>',
        target: '<circle cx="12" cy="12" r="8"/><circle cx="12" cy="12" r="4"/><circle cx="12" cy="12" r=".5"/>',
        coffee: '<path d="M4 9h13v6a4 4 0 01-4 4H8a4 4 0 01-4-4V9z"/><path d="M17 10h2a2 2 0 010 4h-2"/><path d="M8 2v2M11 2v2M14 2v2"/>',
        folder: '<path d="M3 6a2 2 0 012-2h4l2 2h8a2 2 0 012 2v9a2 2 0 01-2 2H5a2 2 0 01-2-2V6z"/>',
        search: '<circle cx="11" cy="11" r="7"/><path d="M21 21l-4.35-4.35"/>',
        tomato: '<circle cx="12" cy="13" r="8"/><path d="M12 5c1-2 3-2 4-1"/>',
        pencil: '<path d="M12 20h9"/><path d="M16.5 3.5a2.1 2.1 0 013 3L7 19l-4 1 1-4z"/>',
        palette: '<path d="M12 2a10 10 0 100 20 2 2 0 002-2 2 2 0 012-2h1a3 3 0 003-3 10 10 0 00-8-13z"/><circle cx="7" cy="10" r="1"/><circle cx="12" cy="7" r="1"/><circle cx="17" cy="10" r="1"/>',
        clipboard: '<rect x="6" y="4" width="12" height="17" rx="2"/><path d="M9 2h6v4H9z"/>',
        calendar: '<rect x="3" y="4" width="18" height="18" rx="2"/><path d="M3 9h18M8 2v4M16 2v4"/>',
        person: '<circle cx="12" cy="8" r="4"/><path d="M4 21c0-4 4-6 8-6s8 2 8 6"/>',
        menu: '<path d="M3 6h18M3 12h18M3 18h18"/>',
        chart: '<path d="M4 20V10M10 20V4M16 20v-7M22 20H2"/>',
        note: '<path d="M6 2h9l5 5v15H6z"/><path d="M9 13h6M9 17h6M9 9h3"/>',
        checklist: '<rect x="3" y="3" width="18" height="18" rx="2"/><path d="M8 12l3 3 5-6"/>',
        wave: '<circle cx="12" cy="12" r="9"/><path d="M9 10h.01M15 10h.01M8 15c1.5 1.5 6.5 1.5 8 0"/>'
    };
    return `<svg width="${size}" height="${size}" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="vertical-align:-3px;margin-left:4px">${paths[name]||''}</svg>`;
}

function applyTheme(t){
    document.body.className = '';
    if (t !== 'light-blue') document.body.classList.add('theme-' + t);
    setData(KEYS.theme, t);
    document.getElementById('theme-quick-toggle').innerHTML = t.startsWith('dark') ? SUN_ICON : MOON_ICON;
    if (currentTab === 'settings') renderSettings();
}

/* ============================================================ جستجوی سراسری ============================================================ */
const searchInput = document.getElementById('global-search');
const searchResultsBox = document.getElementById('search-results');

searchInput.addEventListener('input', function(){
    const term = this.value.trim().toLowerCase();
    if (!term){ searchResultsBox.classList.add('hidden'); searchResultsBox.innerHTML=''; return; }

    const tasks = getData(KEYS.tasks, []).filter(t => t.title.toLowerCase().includes(term));
    const notes = getData(KEYS.notes, []).filter(n => n.title.toLowerCase().includes(term));
    const habits = getData(KEYS.habits, []).filter(h => h.name.toLowerCase().includes(term));
    const exams = getData(KEYS.exams, []).filter(x => x.title.toLowerCase().includes(term));

    const results = [
        ...tasks.map(t => ({type:'تسک', label:t.title, tab:'tasks'})),
        ...notes.map(n => ({type:'یادداشت', label:n.title, tab:'notes'})),
        ...habits.map(h => ({type:'عادت', label:h.name, tab:'habits'})),
        ...exams.map(x => ({type:'امتحان', label:x.title, tab:'exams'}))
    ];

    if (results.length === 0){
        searchResultsBox.innerHTML = '<div class="search-result-item">چیزی پیدا نشد</div>';
    } else {
        searchResultsBox.innerHTML = results.map(r => `
            <div class="search-result-item" data-tab="${r.tab}">
                <div class="sr-type">${r.type}</div>
                <div>${escapeHtml(r.label)}</div>
            </div>
        `).join('');
    }
    searchResultsBox.classList.remove('hidden');
});

searchResultsBox.addEventListener('click', function(e){
    const item = e.target.closest('[data-tab]');
    if (!item) return;
    renderTab(item.dataset.tab);
    searchResultsBox.classList.add('hidden');
    searchInput.value = '';
});

document.addEventListener('click', function(e){
    if (!e.target.closest('.search-wrap')) searchResultsBox.classList.add('hidden');
});

/* ============================================================ صفحه خانه ============================================================ */
function renderHome(){
    const user = getData(KEYS.user, {});
    const tasks = getData(KEYS.tasks, []);
    const habits = getData(KEYS.habits, []);
    const notes = getData(KEYS.notes, []);
    const today = todayStr();

    const activeTasks = tasks.filter(t => !t.archived);
    const doneToday = tasks.filter(t => t.archived && t.completedDate === today).length;
    const totalRelevant = activeTasks.length + doneToday;
    const taskPercent = totalRelevant ? Math.round((doneToday/totalRelevant)*100) : 0;
    const habitsNotDoneToday = habits.filter(h => !(h.completedDates||[]).includes(today));

    document.getElementById('main-content').innerHTML = `
        <div class="greeting">سلام ${escapeHtml(user.firstName||'')}</div>
        <div class="greeting-sub">پایه ${gradeName(user.grade)} — این خلاصه امروزته</div>

        <div class="card">
            <h3>${ic('chart')} پیشرفت امروز</h3>
            <p style="font-size:13px;color:var(--text-light)">${doneToday} از ${totalRelevant} تسک انجام شده (${taskPercent}٪)</p>
            <div class="progress-bar-bg"><div class="progress-bar-fill" style="width:${taskPercent}%"></div></div>
        </div>

        <div class="dash-grid">
            <div class="card">
                <h3>${ic('checklist')} تسک‌های باز <button class="view-all-link" data-goto="tasks">مشاهده همه</button></h3>
                ${activeTasks.length === 0 ? '<p class="empty-msg">تسک بازی نداری</p>' : activeTasks.slice(0,3).map(t=>`<div class="mini-row"><span>${escapeHtml(t.title)}</span><span class="task-tag">${escapeHtml(t.subject)}</span></div>`).join('')}
            </div>
            <div class="card">
                <h3>${ic('note')} آخرین یادداشت‌ها <button class="view-all-link" data-goto="notes">مشاهده همه</button></h3>
                ${notes.length === 0 ? '<p class="empty-msg">یادداشتی نداری</p>' : notes.slice(-3).reverse().map(n=>`<div class="mini-row"><span>${escapeHtml(n.title)}</span></div>`).join('')}
            </div>
            <div class="card">
                <h3>${ic('fire')} عادت‌های امروز <button class="view-all-link" data-goto="habits">مشاهده همه</button></h3>
                ${habits.length === 0 ? '<p class="empty-msg">عادتی نداری</p>' : `<p style="font-size:13px;color:var(--text-light)">${habits.length - habitsNotDoneToday.length} از ${habits.length} انجام شده</p>` + habitsNotDoneToday.slice(0,3).map(h=>`<div class="mini-row"><span>${escapeHtml(h.name)}</span><span style="color:var(--text-light);font-size:12px">هنوز نزدی</span></div>`).join('')}
            </div>
            <div class="card">
                <h3>مطالعه</h3>
                <p style="font-size:13px;color:var(--text-light);margin-bottom:12px">با یه پومودورو سریع شروع کن یا کرونومتر بزن.</p>
                <div class="quick-actions">
                    <button data-action="quick-pomodoro">شروع پومودورو</button>
                    <button class="secondary" data-goto="study">کرونومتر</button>
                </div>
            </div>
        </div>
    `;
}

document.getElementById('main-content').addEventListener('click', function(e){
    const goto = e.target.closest('[data-goto]');
    if (goto){ renderTab(goto.dataset.goto); return; }
    const qp = e.target.closest('[data-action="quick-pomodoro"]');
    if (qp){ renderTab('study'); startPomodoro(); return; }
});

/* ============================================================ تسک‌ها ============================================================ */
function renderTasks(){
    const tasks = getData(KEYS.tasks, []);
    const active = tasks.filter(t => !t.archived);
    const archived = tasks.filter(t => t.archived);

    document.getElementById('main-content').innerHTML = `
        <h2 class="page-title">تسک‌ها</h2>
        <p class="page-sub">کارهایی که باید انجام بدی رو اضافه کن.</p>
        <div class="card">
            <div class="add-row">
                <input type="text" id="new-task-title" placeholder="عنوان تسک">
                <select id="new-task-subject">
                    <option value="ریاضی">ریاضی</option><option value="فیزیک">فیزیک</option><option value="شیمی">شیمی</option>
                    <option value="زیست">زیست</option><option value="انگلیسی">انگلیسی</option><option value="برنامه‌نویسی">برنامه‌نویسی</option><option value="سایر">سایر</option>
                </select>
                <input type="text" id="new-task-tags" placeholder="تگ‌ها (با ویرگول جدا کن)">
                <button id="add-task-btn">افزودن</button>
            </div>
            ${active.length === 0 ? '<p class="empty-msg">تسکی اضافه نکردی</p>' : active.map(t => `
                <div class="task-item">
                    <div class="task-left">
                        <input type="checkbox" data-action="complete-task" data-id="${t.id}">
                        <span>${escapeHtml(t.title)}</span>
                        <span class="task-tag">${escapeHtml(t.subject)}</span>
                        ${tagsHtml(t.tags)}
                    </div>
                    <button class="delete-btn" data-action="delete-task" data-id="${t.id}">حذف</button>
                </div>`).join('')}
        </div>
        <button class="archive-toggle" id="toggle-archive">${ic('folder')} تسک‌های انجام‌شده (${archived.length})</button>
        <div class="card hidden" id="archive-box">
            ${archived.length === 0 ? '<p class="empty-msg">هنوز چیزی تموم نکردی</p>' : archived.slice().reverse().map(t => `
                <div class="task-item">
                    <div class="task-left"><span style="text-decoration:line-through;color:var(--text-light)">${escapeHtml(t.title)}</span><span class="task-tag">${escapeHtml(t.subject)}</span></div>
                    <button class="delete-btn" data-action="delete-task" data-id="${t.id}">حذف</button>
                </div>`).join('')}
        </div>
    `;
    document.getElementById('add-task-btn').addEventListener('click', addTask);
    document.getElementById('new-task-title').addEventListener('keypress', e => { if (e.key==='Enter') addTask(); });
    document.getElementById('toggle-archive').addEventListener('click', () => document.getElementById('archive-box').classList.toggle('hidden'));
}

function addTask(){
    const title = document.getElementById('new-task-title').value.trim();
    if (!title) return;
    const subject = document.getElementById('new-task-subject').value;
    const tags = parseTags(document.getElementById('new-task-tags').value);
    const tasks = getData(KEYS.tasks, []);
    tasks.push({ id:uid(), title, subject, tags, archived:false, completedDate:null, createdDate:todayStr() });
    setData(KEYS.tasks, tasks);
    renderTasks();
}

document.addEventListener('click', function(e){
    const completeBtn = e.target.closest('[data-action="complete-task"]');
    if (completeBtn){
        const tasks = getData(KEYS.tasks, []);
        const task = tasks.find(t => t.id === completeBtn.dataset.id);
        if (task){ task.archived = true; task.completedDate = todayStr(); setData(KEYS.tasks, tasks); renderTasks(); }
        return;
    }
    const deleteTaskBtn = e.target.closest('[data-action="delete-task"]');
    if (deleteTaskBtn){ setData(KEYS.tasks, getData(KEYS.tasks,[]).filter(t=>t.id!==deleteTaskBtn.dataset.id)); renderTasks(); return; }

    const noteToggle = e.target.closest('[data-action="toggle-note"]');
    if (noteToggle){ const box = document.getElementById('note-content-'+noteToggle.dataset.id); if (box) box.classList.toggle('hidden'); return; }
    const deleteNoteBtn = e.target.closest('[data-action="delete-note"]');
    if (deleteNoteBtn){ setData(KEYS.notes, getData(KEYS.notes,[]).filter(n=>n.id!==deleteNoteBtn.dataset.id)); renderNotesList(searchInput._noteTerm||''); return; }

    const habitToggle = e.target.closest('[data-action="toggle-habit"]');
    if (habitToggle){
        const habits = getData(KEYS.habits, []);
        const habit = habits.find(h => h.id === habitToggle.dataset.id);
        if (habit){
            const today = todayStr();
            habit.completedDates = habit.completedDates || [];
            const idx = habit.completedDates.indexOf(today);
            if (idx > -1) habit.completedDates.splice(idx,1); else habit.completedDates.push(today);
            setData(KEYS.habits, habits); renderHabits();
        }
        return;
    }
    const deleteHabitBtn = e.target.closest('[data-action="delete-habit"]');
    if (deleteHabitBtn){ setData(KEYS.habits, getData(KEYS.habits,[]).filter(h=>h.id!==deleteHabitBtn.dataset.id)); renderHabits(); return; }

    const toggleExamBtn = e.target.closest('[data-action="toggle-exam-ready"]');
    if (toggleExamBtn){
        const exams = getData(KEYS.exams, []);
        const exam = exams.find(x => x.id === toggleExamBtn.dataset.id);
        if (exam){ exam.ready = !exam.ready; setData(KEYS.exams, exams); renderExams(); }
        return;
    }
    const deleteExamBtn = e.target.closest('[data-action="delete-exam"]');
    if (deleteExamBtn){ setData(KEYS.exams, getData(KEYS.exams,[]).filter(x=>x.id!==deleteExamBtn.dataset.id)); renderExams(); return; }

    const deleteScheduleBtn = e.target.closest('[data-action="delete-schedule-item"]');
    if (deleteScheduleBtn){
        const type = deleteScheduleBtn.dataset.type;
        const key = type === 'hourly' ? KEYS.plannerHourly : KEYS.plannerWeekly;
        const data = getData(key, type==='hourly' ? {start:'',end:'',items:[]} : {items:[]});
        data.items = data.items.filter(it => it.id !== deleteScheduleBtn.dataset.id);
        setData(key, data); renderPlanner();
        return;
    }
});

/* ============================================================ یادداشت‌ها (با رفع باگ پرش کرسر در جستجو) ============================================================ */
function renderNotes(initialTerm){
    document.getElementById('main-content').innerHTML = `
        <h2 class="page-title">یادداشت‌ها</h2>
        <p class="page-sub">هر چیزی که می‌خوای یادت بمونه رو اینجا بنویس.</p>
        <div class="card">
            <div class="form-group"><input type="text" id="search-notes" placeholder="جستجو بین یادداشت‌ها..." value="${escapeHtml(initialTerm||'')}"></div>
            <div class="form-group"><input type="text" id="new-note-title" placeholder="عنوان یادداشت"></div>
            <div class="form-group"><textarea id="new-note-content" rows="3" placeholder="متن یادداشت..."></textarea></div>
            <div class="form-group"><input type="text" id="new-note-tags" placeholder="تگ‌ها (با ویرگول جدا کن)"></div>
            <button class="big-btn" id="add-note-btn">افزودن یادداشت</button>
        </div>
        <div class="card"><div id="notes-list-box"></div></div>
    `;
    document.getElementById('add-note-btn').addEventListener('click', addNote);
    const searchBox = document.getElementById('search-notes');
    searchBox.addEventListener('input', function(){ renderNotesList(this.value); });
    renderNotesList(initialTerm || '');
}

function renderNotesList(term){
    searchInput._noteTerm = term;
    const notes = getData(KEYS.notes, []);
    const filtered = term ? notes.filter(n => n.title.toLowerCase().includes(term.toLowerCase())) : notes;
    const box = document.getElementById('notes-list-box');
    if (!box) return;
    box.innerHTML = filtered.length === 0 ? '<p class="empty-msg">یادداشتی پیدا نشد</p>' : filtered.slice().reverse().map(n => `
        <div class="note-item">
            <div class="note-title-row" data-action="toggle-note" data-id="${n.id}">
                <span class="t">${ic('note')} ${escapeHtml(n.title)} ${tagsHtml(n.tags)}</span>
                <button class="delete-btn" data-action="delete-note" data-id="${n.id}">حذف</button>
            </div>
            <div class="note-content hidden" id="note-content-${n.id}">${escapeHtml(n.content)}</div>
        </div>`).join('');
}

function addNote(){
    const title = document.getElementById('new-note-title').value.trim();
    const content = document.getElementById('new-note-content').value.trim();
    if (!title) return;
    const tags = parseTags(document.getElementById('new-note-tags').value);
    const notes = getData(KEYS.notes, []);
    notes.push({ id:uid(), title, content, tags, createdDate:todayStr() });
    setData(KEYS.notes, notes);
    document.getElementById('new-note-title').value = '';
    document.getElementById('new-note-content').value = '';
    document.getElementById('new-note-tags').value = '';
    renderNotesList(document.getElementById('search-notes').value);
}

/* ============================================================ عادت‌ها ============================================================ */
function renderHabits(){
    const habits = getData(KEYS.habits, []);
    const today = todayStr();
    document.getElementById('main-content').innerHTML = `
        <h2 class="page-title">عادت‌ها</h2>
        <p class="page-sub">عادتی که می‌خوای بسازی رو اضافه کن و هر روز بزن.</p>
        <div class="card">
            <div class="add-row"><input type="text" id="new-habit-name" placeholder="مثلاً: نیم ساعت مطالعه انگلیسی"><button id="add-habit-btn">افزودن</button></div>
            ${habits.length === 0 ? '<p class="empty-msg">هنوز عادتی اضافه نکردی</p>' : habits.map(h => { const doneToday=(h.completedDates||[]).includes(today); const count=(h.completedDates||[]).length; return `
                <div class="habit-item">
                    <div><div class="habit-name">${escapeHtml(h.name)}</div><div class="habit-count">${count} روز انجام دادی</div></div>
                    <div style="display:flex;gap:8px;align-items:center">
                        <button class="habit-btn ${doneToday?'done':''}" data-action="toggle-habit" data-id="${h.id}">${doneToday?ic('check')+' امروز انجام شد':'امروز انجام دادم'}</button>
                        <button class="delete-btn" data-action="delete-habit" data-id="${h.id}">حذف</button>
                    </div>
                </div>`; }).join('')}
        </div>
    `;
    document.getElementById('add-habit-btn').addEventListener('click', addHabit);
    document.getElementById('new-habit-name').addEventListener('keypress', e => { if (e.key==='Enter') addHabit(); });
}
function addHabit(){
    const input = document.getElementById('new-habit-name');
    const name = input.value.trim();
    if (!name) return;
    const habits = getData(KEYS.habits, []);
    habits.push({ id:uid(), name, completedDates:[] });
    setData(KEYS.habits, habits);
    renderHabits();
}

/* ============================================================ امتحان‌ها (بدون فیلد تاریخ) ============================================================ */
function renderExams(){
    const exams = getData(KEYS.exams, []);
    document.getElementById('main-content').innerHTML = `
        <h2 class="page-title">امتحان‌ها</h2>
        <p class="page-sub">امتحان‌هایی که در پیش داری رو لیست کن، وقتی آماده شدی تیک بزن.</p>
        <div class="card">
            <div class="add-row">
                <input type="text" id="new-exam-title" placeholder="عنوان امتحان (مثلاً: امتحان فصل ۳)">
                <select id="new-exam-subject">
                    <option value="ریاضی">ریاضی</option><option value="فیزیک">فیزیک</option><option value="شیمی">شیمی</option>
                    <option value="زیست">زیست</option><option value="انگلیسی">انگلیسی</option><option value="سایر">سایر</option>
                </select>
                <input type="text" id="new-exam-tags" placeholder="تگ‌ها">
                <button id="add-exam-btn">افزودن</button>
            </div>
            ${exams.length === 0 ? '<p class="empty-msg">امتحانی اضافه نکردی</p>' : exams.map(x => `
                <div class="exam-item">
                    <div class="task-left">
                        <span>${escapeHtml(x.title)}</span>
                        <span class="task-tag">${escapeHtml(x.subject)}</span>
                        ${tagsHtml(x.tags)}
                    </div>
                    <div style="display:flex;gap:8px;align-items:center">
                        <button class="habit-btn ${x.ready?'done':''}" data-action="toggle-exam-ready" data-id="${x.id}">${x.ready?ic('check')+' آماده‌ام':'هنوز آماده نیستم'}</button>
                        <button class="delete-btn" data-action="delete-exam" data-id="${x.id}">حذف</button>
                    </div>
                </div>`).join('')}
        </div>
    `;
    document.getElementById('add-exam-btn').addEventListener('click', function(){
        const title = document.getElementById('new-exam-title').value.trim();
        if (!title) return;
        const subject = document.getElementById('new-exam-subject').value;
        const tags = parseTags(document.getElementById('new-exam-tags').value);
        const exams = getData(KEYS.exams, []);
        exams.push({ id:uid(), title, subject, tags, ready:false });
        setData(KEYS.exams, exams);
        renderExams();
    });
}

/* ============================================================ مطالعه: پومودورو + کرونومتر ============================================================ */
const pomodoro = { mode:'work', secondsLeft: 25*60, running:false, intervalId:null };
const stopwatch = { elapsedMs:0, running:false, intervalId:null, lastTick:null };

function fmtTime(totalSeconds){
    const m = Math.floor(totalSeconds/60).toString().padStart(2,'0');
    const s = Math.floor(totalSeconds%60).toString().padStart(2,'0');
    return m+':'+s;
}
function fmtStopwatch(ms){
    const totalSec = Math.floor(ms/1000);
    const m = Math.floor(totalSec/60).toString().padStart(2,'0');
    const s = (totalSec%60).toString().padStart(2,'0');
    return m+':'+s;
}
function beep(){
    try{
        const ctx = new (window.AudioContext||window.webkitAudioContext)();
        const osc = ctx.createOscillator();
        osc.frequency.value = 880;
        osc.connect(ctx.destination);
        osc.start(); osc.stop(ctx.currentTime + 0.3);
    }catch(e){}
}

function startPomodoro(){
    if (pomodoro.running) return;
    pomodoro.running = true;
    pomodoro.intervalId = setInterval(() => {
        pomodoro.secondsLeft--;
        if (pomodoro.secondsLeft <= 0){
            beep();
            const cfg = getData(KEYS.pomodoroConfig, {work:25, break:5});
            pomodoro.mode = pomodoro.mode === 'work' ? 'break' : 'work';
            pomodoro.secondsLeft = (pomodoro.mode === 'work' ? cfg.work : cfg.break) * 60;
            pomodoro.running = false;
            clearInterval(pomodoro.intervalId);
        }
        if (currentTab === 'study') updateStudyDisplay();
    }, 1000);
}
function pausePomodoro(){ pomodoro.running = false; clearInterval(pomodoro.intervalId); }
function resetPomodoro(){
    pausePomodoro();
    const cfg = getData(KEYS.pomodoroConfig, {work:25, break:5});
    pomodoro.mode = 'work';
    pomodoro.secondsLeft = cfg.work * 60;
    if (currentTab === 'study') updateStudyDisplay();
}

function startStopwatch(){
    if (stopwatch.running) return;
    stopwatch.running = true;
    stopwatch.lastTick = Date.now();
    stopwatch.intervalId = setInterval(() => {
        const now = Date.now();
        stopwatch.elapsedMs += now - stopwatch.lastTick;
        stopwatch.lastTick = now;
        if (currentTab === 'study') updateStudyDisplay();
    }, 250);
}
function pauseStopwatch(){ stopwatch.running = false; clearInterval(stopwatch.intervalId); }
function resetStopwatch(){ pauseStopwatch(); stopwatch.elapsedMs = 0; if (currentTab==='study') updateStudyDisplay(); }

function updateStudyDisplay(){
    const pd = document.getElementById('pomodoro-display');
    const pm = document.getElementById('pomodoro-mode-label');
    if (pd) pd.textContent = fmtTime(pomodoro.secondsLeft);
    if (pm) pm.innerHTML = pomodoro.mode === 'work' ? (ic('target')+'زمان کار') : (ic('coffee')+'زمان استراحت');
    const sd = document.getElementById('stopwatch-display');
    if (sd) sd.textContent = fmtStopwatch(stopwatch.elapsedMs);
}

function renderStudy(){
    const cfg = getData(KEYS.pomodoroConfig, {work:25, break:5});
    document.getElementById('main-content').innerHTML = `
        <h2 class="page-title">مطالعه</h2>
        <p class="page-sub">با پومودورو تمرکز کن یا با کرونومتر زمان مطالعه‌ت رو اندازه بگیر.</p>
        <div class="study-grid">
            <div class="card">
                <h3>${ic('tomato')} پومودورو</h3>
                <div class="timer-mode-label" id="pomodoro-mode-label">${pomodoro.mode==='work'?(ic('target')+'زمان کار'):(ic('coffee')+'زمان استراحت')}</div>
                <div class="timer-display" id="pomodoro-display">${fmtTime(pomodoro.secondsLeft)}</div>
                <div class="timer-controls">
                    <button data-action="pomodoro-start"><svg width="12" height="12" viewBox="0 0 24 24" fill="currentColor" style="vertical-align:-1px;margin-left:3px"><path d="M6 4l14 8-14 8V4z"/></svg>شروع</button>
                    <button data-action="pomodoro-pause"><svg width="12" height="12" viewBox="0 0 24 24" fill="currentColor" style="vertical-align:-1px;margin-left:3px"><rect x="6" y="4" width="4" height="16"/><rect x="14" y="4" width="4" height="16"/></svg>توقف</button>
                    <button class="reset-btn" data-action="pomodoro-reset"><svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="vertical-align:-1px;margin-left:3px"><path d="M3 12a9 9 0 109-9 9.75 9.75 0 00-6.74 2.74L3 8"/><path d="M3 3v5h5"/></svg>ریست</button>
                </div>
                <div class="pomodoro-config">
                    <div><label>دقیقه کار</label><input type="number" id="cfg-work" value="${cfg.work}" min="1"></div>
                    <div><label>دقیقه استراحت</label><input type="number" id="cfg-break" value="${cfg.break}" min="1"></div>
                </div>
            </div>
            <div class="card">
                <h3>کرونومتر</h3>
                <div class="timer-mode-label">زمان سپری‌شده</div>
                <div class="timer-display" id="stopwatch-display">${fmtStopwatch(stopwatch.elapsedMs)}</div>
                <div class="timer-controls">
                    <button data-action="stopwatch-start"><svg width="12" height="12" viewBox="0 0 24 24" fill="currentColor" style="vertical-align:-1px;margin-left:3px"><path d="M6 4l14 8-14 8V4z"/></svg>شروع</button>
                    <button data-action="stopwatch-pause"><svg width="12" height="12" viewBox="0 0 24 24" fill="currentColor" style="vertical-align:-1px;margin-left:3px"><rect x="6" y="4" width="4" height="16"/><rect x="14" y="4" width="4" height="16"/></svg>توقف</button>
                    <button class="reset-btn" data-action="stopwatch-reset"><svg width="12" height="12" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="vertical-align:-1px;margin-left:3px"><path d="M3 12a9 9 0 109-9 9.75 9.75 0 00-6.74 2.74L3 8"/><path d="M3 3v5h5"/></svg>ریست</button>
                </div>
            </div>
        </div>
    `;
    document.getElementById('cfg-work').addEventListener('change', function(){
        const c = getData(KEYS.pomodoroConfig, {work:25,break:5}); c.work = parseInt(this.value)||25; setData(KEYS.pomodoroConfig, c);
        if (!pomodoro.running && pomodoro.mode==='work') { pomodoro.secondsLeft = c.work*60; updateStudyDisplay(); }
    });
    document.getElementById('cfg-break').addEventListener('change', function(){
        const c = getData(KEYS.pomodoroConfig, {work:25,break:5}); c.break = parseInt(this.value)||5; setData(KEYS.pomodoroConfig, c);
        if (!pomodoro.running && pomodoro.mode==='break') { pomodoro.secondsLeft = c.break*60; updateStudyDisplay(); }
    });
}

document.addEventListener('click', function(e){
    if (e.target.closest('[data-action="pomodoro-start"]')) startPomodoro();
    if (e.target.closest('[data-action="pomodoro-pause"]')) pausePomodoro();
    if (e.target.closest('[data-action="pomodoro-reset"]')) resetPomodoro();
    if (e.target.closest('[data-action="stopwatch-start"]')) startStopwatch();
    if (e.target.closest('[data-action="stopwatch-pause"]')) pauseStopwatch();
    if (e.target.closest('[data-action="stopwatch-reset"]')) resetStopwatch();
});

/* ============================================================ برنامه‌ریز ============================================================ */
function renderPlanner(){
    const type = getData(KEYS.plannerType, 'hourly');
    document.getElementById('main-content').innerHTML = `
        <h2 class="page-title">برنامه‌ریز</h2>
        <p class="page-sub">نوع برنامه‌ریزی که می‌خوای رو انتخاب کن.</p>
        <div class="planner-type-switch">
            <button data-action="set-planner-type" data-type="hourly" class="${type==='hourly'?'active':''}">ساعتی روزانه</button>
            <button data-action="set-planner-type" data-type="weekly" class="${type==='weekly'?'active':''}">هفتگی</button>
        </div>
        <div id="planner-body"></div>
    `;
    document.querySelectorAll('[data-action="set-planner-type"]').forEach(btn => btn.addEventListener('click', function(){ setData(KEYS.plannerType, this.dataset.type); renderPlanner(); }));
    if (type === 'hourly') renderHourlyPlanner(); else renderWeeklyPlanner();
}

function renderHourlyPlanner(){
    const data = getData(KEYS.plannerHourly, {start:'08:00', end:'22:00', items:[]});
    const sorted = data.items.slice().sort((a,b)=>a.time.localeCompare(b.time));
    document.getElementById('planner-body').innerHTML = `
        <div class="card">
            <h3>بازه زمانی برنامه</h3>
            <div class="add-row">
                <div style="flex:1"><label style="font-size:12px;color:var(--text-light)">از ساعت</label><input type="time" id="planner-start" value="${data.start}"></div>
                <div style="flex:1"><label style="font-size:12px;color:var(--text-light)">تا ساعت</label><input type="time" id="planner-end" value="${data.end}"></div>
                <button id="save-hourly-range" style="align-self:flex-end;background:var(--main-color);color:#fff;padding:10px 20px;border-radius:8px;">ذخیره</button>
            </div>
        </div>
        <div class="card">
            <h3>افزودن برنامه</h3>
            <div class="add-row"><input type="time" id="new-schedule-time" value="12:00"><input type="text" id="new-schedule-label" placeholder="مثلاً: مطالعه ریاضی"><button id="add-schedule-item">افزودن</button></div>
            ${sorted.length===0?'<p class="empty-msg">هنوز برنامه‌ای اضافه نکردی</p>':sorted.map(it=>`
                <div class="schedule-item"><span class="schedule-time">${it.time}</span><span style="flex:1;padding:0 12px">${escapeHtml(it.label)}</span><button class="delete-btn" data-action="delete-schedule-item" data-type="hourly" data-id="${it.id}">حذف</button></div>
            `).join('')}
        </div>
    `;
    document.getElementById('save-hourly-range').addEventListener('click', function(){
        const d = getData(KEYS.plannerHourly, {start:'',end:'',items:[]});
        d.start = document.getElementById('planner-start').value; d.end = document.getElementById('planner-end').value;
        setData(KEYS.plannerHourly, d); renderPlanner();
    });
    document.getElementById('add-schedule-item').addEventListener('click', function(){
        const time = document.getElementById('new-schedule-time').value;
        const label = document.getElementById('new-schedule-label').value.trim();
        if (!time || !label){ alert('لطفاً هم ساعت و هم عنوان برنامه رو وارد کن.'); return; }
        const d = getData(KEYS.plannerHourly, {start:'08:00',end:'22:00',items:[]});
        d.items.push({id:uid(), time, label}); setData(KEYS.plannerHourly, d); renderPlanner();
    });
}

function renderWeeklyPlanner(){
    const data = getData(KEYS.plannerWeekly, {items:[]});
    const days = ['شنبه','یکشنبه','دوشنبه','سه‌شنبه','چهارشنبه','پنجشنبه','جمعه'];
    let groupsHtml = days.map(day => {
        const dayItems = data.items.filter(it => it.day === day);
        if (dayItems.length === 0) return '';
        return `<div class="day-group"><h4>${day}</h4>${dayItems.map(it=>`
            <div class="schedule-item"><span class="schedule-time">${it.part}</span><span style="flex:1;padding:0 12px">${escapeHtml(it.label)}</span><button class="delete-btn" data-action="delete-schedule-item" data-type="weekly" data-id="${it.id}">حذف</button></div>
        `).join('')}</div>`;
    }).join('');
    if (!groupsHtml.trim()) groupsHtml = '<p class="empty-msg">هنوز برنامه‌ای اضافه نکردی</p>';
    document.getElementById('planner-body').innerHTML = `
        <div class="card">
            <h3>افزودن برنامه هفتگی</h3>
            <div class="add-row">
                <select id="new-week-day">${days.map(d=>`<option value="${d}">${d}</option>`).join('')}</select>
                <select id="new-week-part"><option value="صبح">صبح</option><option value="عصر">عصر</option><option value="شب">شب</option></select>
                <input type="text" id="new-week-label" placeholder="مثلاً: مطالعه فیزیک">
                <button id="add-week-item">افزودن</button>
            </div>
        </div>
        <div class="card">${groupsHtml}</div>
    `;
    document.getElementById('add-week-item').addEventListener('click', function(){
        const day = document.getElementById('new-week-day').value;
        const part = document.getElementById('new-week-part').value;
        const label = document.getElementById('new-week-label').value.trim();
        if (!label){ alert('لطفاً عنوان برنامه رو وارد کن.'); return; }
        const d = getData(KEYS.plannerWeekly, {items:[]});
        d.items.push({id:uid(), day, part, label}); setData(KEYS.plannerWeekly, d); renderPlanner();
    });
}

/* ============================================================ تنظیمات (شامل پروفایل) ============================================================ */
function renderSettings(){
    const user = getData(KEYS.user, {});
    const tasks = getData(KEYS.tasks, []);
    const habits = getData(KEYS.habits, []);
    const theme = getData(KEYS.theme, 'light-blue');
    const firstDate = new Date(user.firstVisitDate);
    const daysUsed = Math.max(1, Math.floor((new Date() - firstDate)/86400000) + 1);
    const completedTasksCount = tasks.filter(t=>t.archived).length;

    const themes = [
        {key:'light-blue', label:'آبی روشن', dot:'dot-light-blue'},
        {key:'light-green', label:'سبز روشن', dot:'dot-light-green'},
        {key:'dark-blue', label:'تیره + آبی', dot:'dot-dark-blue'},
        {key:'dark-green', label:'تیره + سبز', dot:'dot-dark-green'},
        {key:'dark-purple', label:'تیره + بنفش', dot:'dot-dark-purple'}
    ];

    document.getElementById('main-content').innerHTML = `
        <h2 class="page-title">تنظیمات</h2>

        <div class="card">
            <h3>${ic('person')} پروفایل</h3>
            <div class="stats-grid">
                <div class="stat-mini"><div class="num">${daysUsed}</div><div class="label">روز عضویت</div></div>
                <div class="stat-mini"><div class="num">${habits.length}</div><div class="label">عادت فعال</div></div>
                <div class="stat-mini"><div class="num">${completedTasksCount}</div><div class="label">تسک انجام‌شده</div></div>
            </div>
            <button class="big-btn" id="edit-profile-btn" style="background:var(--bg-color);color:var(--main-color);border:1px solid var(--main-color)">${ic('pencil')}ویرایش پروفایل</button>
            <div id="edit-profile-form" class="hidden" style="margin-top:16px">
                <div class="form-group"><label>اسم</label><input type="text" id="edit-firstname" value="${escapeHtml(user.firstName||'')}"></div>
                <div class="form-group"><label>فامیل</label><input type="text" id="edit-lastname" value="${escapeHtml(user.lastName||'')}"></div>
                <div class="form-group"><label>پایه</label><select id="edit-grade">${[5,6,7,8,9,10,11,12].map(g=>`<option value="${g}" ${String(user.grade)===String(g)?'selected':''}>${gradeName(g)}</option>`).join('')}</select></div>
                <button class="big-btn" id="save-profile-btn">ذخیره تغییرات</button>
            </div>
        </div>

        <div class="card">
            <h3>${ic('palette')} تم رنگی</h3>
            <div class="theme-grid">
                ${themes.map(t => `
                    <div class="theme-option ${theme===t.key?'selected':''}" data-action="set-theme" data-theme="${t.key}">
                        ${theme===t.key?`<span class="theme-check">${ic('check',10)}</span>`:''}
                        <div class="theme-dot ${t.dot}"></div>${t.label}
                    </div>`).join('')}
            </div>
        </div>

        <div class="card">
            <h3><svg width="15" height="15" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" style="vertical-align:-3px;margin-left:4px"><circle cx="12" cy="12" r="9"/><path d="M12 16v-5M12 8h.01"/></svg>درباره ما</h3>
            <div class="about-text">
                <p><b>سازنده:</b> محمد</p>
                <p><b>هدف پروژه:</b> کمک به دانش‌آموزان فارسی‌زبان برای مدیریت بهتر درس، برنامه‌ریزی و مطالعه.</p>
                <p><b>کانال تلگرام:</b> <a href="https://t.me/darasyar_ir" target="_blank" style="color:var(--main-color);font-weight:600">t.me/darasyar_ir</a></p>
            </div>
        </div>

        <div class="card">
            <h3 style="color:#d64545">منطقه خطر</h3>
            <p style="color:var(--text-light);font-size:13px;margin-bottom:14px">همه اطلاعاتت رو برای همیشه پاک می‌کنه.</p>
            <button class="danger-btn" id="clear-all-btn">پاک کردن همه اطلاعات</button>
        </div>
    `;

    document.getElementById('edit-profile-btn').addEventListener('click', () => document.getElementById('edit-profile-form').classList.toggle('hidden'));
    document.getElementById('save-profile-btn').addEventListener('click', function(){
        const u = getData(KEYS.user, {});
        u.firstName = document.getElementById('edit-firstname').value.trim();
        u.lastName = document.getElementById('edit-lastname').value.trim();
        u.grade = document.getElementById('edit-grade').value;
        setData(KEYS.user, u); renderSettings();
    });
    document.querySelectorAll('[data-action="set-theme"]').forEach(el => el.addEventListener('click', function(){ applyTheme(this.dataset.theme); }));
    document.getElementById('clear-all-btn').addEventListener('click', showDeleteModal);
}

/* ============================================================ مودال تایید حذف کامل ============================================================ */
function showDeleteModal(){
    const tasks = getData(KEYS.tasks, []).length;
    const notes = getData(KEYS.notes, []).length;
    const habits = getData(KEYS.habits, []).length;
    const exams = getData(KEYS.exams, []).length;

    const overlay = document.createElement('div');
    overlay.className = 'modal-overlay';
    overlay.innerHTML = `
        <div class="modal-box">
            <h3>${ic('warning')} پاک کردن همه اطلاعات</h3>
            <p>این موارد برای همیشه پاک می‌شن:</p>
            <div class="modal-list">
                <div>${ic('clipboard')} ${tasks} تسک</div>
                <div>${ic('note')} ${notes} یادداشت</div>
                <div>${ic('fire')} ${habits} عادت</div>
                <div>${ic('calendar')} ${exams} امتحان</div>
                <div>${ic('person')} اطلاعات پروفایل</div>
            </div>
            <p class="modal-warning">این عمل قابل بازگشت نیست.</p>
            <div class="modal-actions">
                <button class="modal-cancel" id="modal-cancel-btn">انصراف</button>
                <button class="modal-confirm" id="modal-confirm-btn">بله، پاک کن</button>
            </div>
        </div>
    `;
    document.body.appendChild(overlay);
    document.getElementById('modal-cancel-btn').addEventListener('click', () => overlay.remove());
    document.getElementById('modal-confirm-btn').addEventListener('click', () => { localStorage.clear(); location.reload(); });
    overlay.addEventListener('click', e => { if (e.target === overlay) overlay.remove(); });
}

init();
</script>

</body>
</html>
