<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
    <title>同学拼单 · 每人限一单 · 统计总览</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: system-ui, 'Segoe UI', 'Roboto', 'Noto Sans', sans-serif;
        }

        body {
            background: #eef2f5;
            padding: 28px 20px;
        }

        .card {
            max-width: 1300px;
            margin: 0 auto;
            background: white;
            border-radius: 2rem;
            box-shadow: 0 20px 35px -10px rgba(0, 0, 0, 0.15);
            overflow: hidden;
        }

        .inner {
            padding: 1.8rem 2rem 2rem 2rem;
        }

        @media (max-width: 720px) {
            .inner {
                padding: 1.2rem;
            }
        }

        h1 {
            font-size: 1.9rem;
            font-weight: 800;
            background: linear-gradient(135deg, #2c3e4e, #e67e22);
            background-clip: text;
            -webkit-background-clip: text;
            color: transparent;
        }

        .sub {
            color: #5d6e7e;
            border-left: 3px solid #f5a65b;
            padding-left: 14px;
            margin: 10px 0 28px 0;
            font-size: 0.9rem;
            font-weight: 500;
        }

        /* 上方表单区域 */
        .form-panel {
            background: #fefcf7;
            border-radius: 1.5rem;
            padding: 1.5rem;
            margin-bottom: 2rem;
            border: 1px solid #f0e6db;
            box-shadow: 0 2px 6px rgba(0,0,0,0.02);
        }

        .form-row {
            display: flex;
            flex-wrap: wrap;
            gap: 1.5rem;
            align-items: flex-end;
            margin-bottom: 1.5rem;
        }

        .field {
            flex: 1;
            min-width: 180px;
        }

        .field label {
            display: block;
            font-size: 0.75rem;
            font-weight: 700;
            text-transform: uppercase;
            color: #b45f2b;
            letter-spacing: 0.5px;
            margin-bottom: 6px;
        }

        select, .radio-group {
            width: 100%;
        }

        select {
            padding: 12px 14px;
            border-radius: 1.2rem;
            border: 1.5px solid #e4dccf;
            background: white;
            font-size: 0.95rem;
            cursor: pointer;
            transition: 0.2s;
        }

        select:focus {
            outline: none;
            border-color: #f5a65b;
        }

        .radio-group {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }

        .radio-item {
            display: flex;
            align-items: center;
            gap: 8px;
            background: white;
            padding: 8px 16px;
            border-radius: 40px;
            border: 1px solid #e4dccf;
            cursor: pointer;
            transition: all 0.1s;
        }

        .radio-item.selected {
            border-color: #e67e22;
            background: #fff4e8;
        }

        .radio-item input {
            accent-color: #e67e22;
            margin: 0;
            width: 18px;
            height: 18px;
            cursor: pointer;
        }

        .radio-item label {
            font-weight: 600;
            cursor: pointer;
            margin: 0;
            color: #2c3e2f;
        }

        .price-badge {
            background: #f0e2d4;
            border-radius: 24px;
            padding: 2px 8px;
            font-size: 0.7rem;
            font-weight: 600;
            color: #b45f2b;
            margin-left: 6px;
        }

        .btn {
            border: none;
            padding: 10px 28px;
            border-radius: 40px;
            font-weight: 600;
            font-size: 0.9rem;
            cursor: pointer;
            transition: 0.2s;
        }

        .btn-primary {
            background: #e67e22;
            color: white;
            box-shadow: 0 2px 6px rgba(230,126,34,0.3);
        }

        .btn-primary:hover {
            background: #cf711f;
            transform: translateY(-1px);
        }

        .btn-outline {
            background: white;
            border: 1px solid #cfc5b6;
            color: #4b5e6c;
        }

        .btn-outline:hover {
            background: #faf6f0;
            border-color: #e67e22;
        }

        .flex-btns {
            display: flex;
            gap: 15px;
            flex-wrap: wrap;
            margin-top: 10px;
        }

        /* 统计区域 */
        .stats-area {
            margin-top: 20px;
        }

        .section-title {
            font-weight: 700;
            font-size: 1.3rem;
            margin: 28px 0 16px 0;
            color: #2c3e4e;
            border-left: 4px solid #e67e22;
            padding-left: 16px;
        }

        .stat-table {
            width: 100%;
            background: white;
            border-radius: 1rem;
            overflow: hidden;
            border: 1px solid #ede6db;
            margin-bottom: 24px;
        }

        .stat-table th {
            background: #faf3e8;
            padding: 12px 10px;
            font-weight: 700;
            color: #7b4a2e;
            text-align: center;
        }

        .stat-table td {
            padding: 10px 8px;
            text-align: center;
            border-bottom: 1px solid #f0e6db;
        }

        .total-row {
            background: #fff3e6;
            font-weight: 800;
        }

        .order-list {
            width: 100%;
            border-collapse: collapse;
            background: white;
            border-radius: 1rem;
            overflow: hidden;
            border: 1px solid #ede6db;
        }

        .order-list th {
            background: #faf3e8;
            padding: 12px;
            text-align: left;
        }

        .order-list td {
            padding: 10px 12px;
            border-bottom: 1px solid #f0e6db;
        }

        .status-badge {
            display: inline-block;
            background: #eef2f0;
            border-radius: 30px;
            padding: 4px 12px;
            font-size: 0.8rem;
        }

        .empty-tip {
            text-align: center;
            color: #9b8e7c;
            padding: 28px;
            font-style: italic;
        }

        footer {
            font-size: 0.7rem;
            text-align: right;
            margin-top: 32px;
            color: #94a3b8;
            border-top: 1px solid #ede6db;
            padding-top: 16px;
        }

        .warning-msg {
            color: #c2410c;
            background: #fff2e8;
            border-radius: 30px;
            padding: 6px 12px;
            font-size: 0.8rem;
            display: inline-block;
        }
    </style>
</head>
<body>
<div class="card">
    <div class="inner">
        <h1>🍚 同学拼单 · 每人仅限一单</h1>
        <div class="sub">✅ 选择你的姓名 + 餐品 → 提交 → 自动汇总统计 · 防重复点单 · 管理员可重置</div>

        <!-- 上方点餐面板 -->
        <div class="form-panel">
            <div class="form-row">
                <div class="field">
                    <label>👤 你的名字 (固定名单)</label>
                    <select id="studentSelect">
                        <option value="" disabled selected>— 请选择姓名 —</option>
                        <!-- 动态写入8人 -->
                    </select>
                </div>
                <div class="field">
                    <label>🍽️ 选择餐品 (单选)</label>
                    <div class="radio-group" id="foodRadiosGroup">
                        <!-- 动态生成4个餐品单选 -->
                    </div>
                </div>
            </div>
            <div class="flex-btns">
                <button class="btn btn-primary" id="submitBtn">✨ 提交订单</button>
                <button class="btn btn-outline" id="adminResetBtn">🔐 管理员重置全部数据</button>
            </div>
            <div style="font-size: 12px; margin-top: 16px; color: #ba8b4a;">
                ⚡ 每个姓名只能成功提交一次，不可重复。提交后自动更新下方统计。
            </div>
        </div>

        <!-- 下方统计展示区 -->
        <div class="stats-area">
            <div class="section-title">📊 餐品销售统计</div>
            <table class="stat-table" id="statsTable">
                <thead>
                    <tr><th>餐品</th><th>单价(元)</th><th>已点数量</th><th>小计(元)</th></tr>
                </thead>
                <tbody id="statsBody">
                    <tr><td colspan="4" style="text-align:center;">加载中...</td></tr>
                </tbody>
                <tfoot class="total-row">
                    <tr><td colspan="3" style="text-align:right; font-weight:800;">总营业额</td><td id="totalMoney" style="font-weight:800;">0 元</td></tr>
                </tfoot>
            </table>

            <div class="section-title">📋 点单明细 & 状态</div>
            <table class="order-list" id="orderTable">
                <thead>
                    <tr><th>姓名</th><th>所选餐品</th><th>金额</th><th>状态</th></tr>
                </thead>
                <tbody id="orderListBody">
                    <tr><td colspan="4" class="empty-tip">暂无订单，请上方提交~</td></tr>
                </tbody>
            </table>
        </div>
        <footer>🔒 管理员重置需密码 (预设密码可自行修改) · 数据存储于浏览器，防刷新丢失</footer>
    </div>
</div>

<script>
    // ---------- 固定名单 ----------
    const FIXED_NAMES = ['周', '陈', '袁', '范', '祝', '何', '黄', '宋'];
    
    // 餐品菜单
    const MENU = [
        { name: '炒饭', price: 6 },
        { name: '炒粉', price: 7 },
        { name: '汤粉', price: 5 },
        { name: '炒河粉', price: 6 }
    ];

    // 管理员密码 (自行设定)
    const ADMIN_PASSWORD = 'admin8888';   // 可改为任意密码，符合“我自己定”

    // localStorage 键名
    const STORAGE_KEY = 'team_meal_orders_v3';

    // 数据结构: orders 数组存储 { name, itemName, price }
    let orders = [];

    // ----------------- 辅助函数 -----------------
    // 保存订单至本地
    function saveOrders() {
        localStorage.setItem(STORAGE_KEY, JSON.stringify(orders));
    }

    // 加载订单
    function loadOrders() {
        const stored = localStorage.getItem(STORAGE_KEY);
        if (stored) {
            try {
                const parsed = JSON.parse(stored);
                if (Array.isArray(parsed)) orders = parsed;
                else orders = [];
            } catch(e) { orders = []; }
        } else {
            orders = [];
        }
    }

    // 检查某个姓名是否已经点过单 (防重复)
    function isNameAlreadyOrdered(name) {
        return orders.some(order => order.name === name);
    }

    // 添加订单
    function addOrder(name, menuItem) {
        if (!name || !menuItem) return false;
        if (isNameAlreadyOrdered(name)) {
            alert(`❌ 同学“${name}”已经提交过订单了！每人只能点一次。`);
            return false;
        }
        orders.push({
            name: name,
            itemName: menuItem.name,
            price: menuItem.price
        });
        saveOrders();
        return true;
    }

    // 计算统计数据 (各餐品销量、总价)
    function computeStats() {
        const statsMap = new Map(); // key: 餐品名 -> { count, price, total }
        MENU.forEach(menu => {
            statsMap.set(menu.name, { count: 0, price: menu.price, total: 0 });
        });
        let grandTotal = 0;
        for (let order of orders) {
            const item = order.itemName;
            if (statsMap.has(item)) {
                const stat = statsMap.get(item);
                stat.count += 1;
                stat.total = stat.count * stat.price;
                grandTotal += order.price;
            }
        }
        return { statsMap, grandTotal };
    }

    // 渲染统计表格
    function renderStats() {
        const { statsMap, grandTotal } = computeStats();
        const tbody = document.getElementById('statsBody');
        if (!tbody) return;
        tbody.innerHTML = '';
        for (let menu of MENU) {
            const stat = statsMap.get(menu.name);
            const count = stat ? stat.count : 0;
            const subtotal = count * menu.price;
            const row = document.createElement('tr');
            row.innerHTML = `
                <td style="font-weight:600;">🍽️ ${menu.name}</td>
                <td>${menu.price} 元</td>
                <td style="color:#e67e22; font-weight:700;">${count} 份</td>
                <td>${subtotal} 元</td>
            `;
            tbody.appendChild(row);
        }
        document.getElementById('totalMoney').innerText = `${grandTotal} 元`;
    }

    // 渲染订单明细表 + 每个人是否已点 (显示全部名单的状态)
    function renderOrderList() {
        const tbody = document.getElementById('orderListBody');
        if (!tbody) return;
        
        // 构建已点映射
        const orderedMap = new Map(); // name -> 订单详情
        orders.forEach(order => {
            orderedMap.set(order.name, order);
        });
        
        if (FIXED_NAMES.length === 0) {
            tbody.innerHTML = '<tr><td colspan="4" class="empty-tip">暂无名单</td></tr>';
            return;
        }
        
        let html = '';
        for (let name of FIXED_NAMES) {
            const order = orderedMap.get(name);
            if (order) {
                html += `
                    <tr>
                        <td style="font-weight:600;">${escapeHtml(name)}</td>
                        <td>${escapeHtml(order.itemName)}</td>
                        <td>${order.price} 元</td>
                        <td><span class="status-badge" style="background:#e0f2e9; color:#2b6e3f;">✅ 已点</span></td>
                    </tr>
                `;
            } else {
                html += `
                    <tr>
                        <td style="font-weight:600; color:#8b7a66;">${escapeHtml(name)}</td>
                        <td colspan="2">— 未点餐 —</td>
                        <td><span class="status-badge" style="background:#f0ece7; color:#8f7a63;">⏳ 待点餐</span></td>
                    </tr>
                `;
            }
        }
        tbody.innerHTML = html;
    }

    // 整体刷新UI
    function refreshUI() {
        renderStats();
        renderOrderList();
    }

    // 重置所有订单 (管理员)
    function adminReset() {
        const pwd = prompt("🔐 管理员权限验证\n请输入重置密码：");
        if (pwd !== ADMIN_PASSWORD) {
            alert("❌ 密码错误，无法重置！");
            return false;
        }
        const confirmAction = confirm("⚠️ 警告：重置将清空所有点单数据，不可撤销！确定继续吗？");
        if (!confirmAction) return false;
        orders = [];
        saveOrders();
        refreshUI();
        // 同时清空表单的选中状态
        const studentSelect = document.getElementById('studentSelect');
        if (studentSelect) studentSelect.value = '';
        const radios = document.querySelectorAll('input[name="foodRadio"]');
        radios.forEach(radio => radio.checked = false);
        document.querySelectorAll('.radio-item').forEach(item => item.classList.remove('selected'));
        alert("✅ 所有订单已清空，统计归零。");
        return true;
    }

    // 获取当前选中的餐品对象
    function getSelectedFood() {
        const selectedRadio = document.querySelector('input[name="foodRadio"]:checked');
        if (!selectedRadio) return null;
        const foodName = selectedRadio.value;
        return MENU.find(menu => menu.name === foodName);
    }

    // 提交逻辑
    function onSubmit() {
        const selectEl = document.getElementById('studentSelect');
        const selectedName = selectEl ? selectEl.value : '';
        if (!selectedName || !FIXED_NAMES.includes(selectedName)) {
            alert("请从下拉框中选择你的真实姓名！");
            return;
        }
        const selectedFood = getSelectedFood();
        if (!selectedFood) {
            alert("请选择一个餐品 🍜");
            return;
        }
        
        // 检查重复 (二次保险)
        if (isNameAlreadyOrdered(selectedName)) {
            alert(`❌ ${selectedName} 已经点过餐了，不可重复提交！`);
            return;
        }
        
        const success = addOrder(selectedName, selectedFood);
        if (success) {
            refreshUI();
            // 清空表单，方便下一位同学使用
            selectEl.value = '';
            // 清空radio选中
            const radios = document.querySelectorAll('input[name="foodRadio"]');
            radios.forEach(radio => radio.checked = false);
            document.querySelectorAll('.radio-item').forEach(item => item.classList.remove('selected'));
            // 友好提示
            const toast = document.createElement('div');
            toast.innerText = `🎉 ${selectedName} 点餐成功！ (${selectedFood.name})`;
            toast.style.position = 'fixed';
            toast.style.bottom = '24px';
            toast.style.left = '50%';
            toast.style.transform = 'translateX(-50%)';
            toast.style.backgroundColor = '#2c3e4e';
            toast.style.color = '#f8efdf';
            toast.style.padding = '10px 24px';
            toast.style.borderRadius = '40px';
            toast.style.fontSize = '0.9rem';
            toast.style.zIndex = '999';
            toast.style.boxShadow = '0 4px 12px rgba(0,0,0,0.2)';
            document.body.appendChild(toast);
            setTimeout(() => toast.remove(), 2000);
        } else {
            alert("提交失败，可能已经点过了，请刷新检查。");
        }
    }

    // 渲染下拉选项 + 渲染单选按钮组
    function renderSelectAndRadios() {
        // 下拉框填充
        const selectEl = document.getElementById('studentSelect');
        if (selectEl) {
            selectEl.innerHTML = '<option value="" disabled selected>— 请选择姓名 —</option>';
            FIXED_NAMES.forEach(name => {
                const option = document.createElement('option');
                option.value = name;
                option.textContent = name;
                selectEl.appendChild(option);
            });
        }
        
        // 渲染餐品单选按钮
        const radiosContainer = document.getElementById('foodRadiosGroup');
        if (radiosContainer) {
            radiosContainer.innerHTML = '';
            MENU.forEach((menu, idx) => {
                const radioId = `food_${idx}`;
                const div = document.createElement('div');
                div.className = 'radio-item';
                const radio = document.createElement('input');
                radio.type = 'radio';
                radio.name = 'foodRadio';
                radio.value = menu.name;
                radio.id = radioId;
                const label = document.createElement('label');
                label.htmlFor = radioId;
                label.innerHTML = `${menu.name} <span class="price-badge">${menu.price}元</span>`;
                div.appendChild(radio);
                div.appendChild(label);
                radio.addEventListener('change', function(e) {
                    // 高亮当前选中的radio项
                    document.querySelectorAll('.radio-item').forEach(item => item.classList.remove('selected'));
                    if (this.checked) div.classList.add('selected');
                });
                radiosContainer.appendChild(div);
            });
        }
    }

    // 页面初始加载
    function init() {
        loadOrders();              // 加载已有订单
        renderSelectAndRadios();   // 生成姓名下拉 + 餐品单选
        refreshUI();              // 刷新统计表 + 订单明细
        
        // 绑定按钮
        document.getElementById('submitBtn').addEventListener('click', onSubmit);
        document.getElementById('adminResetBtn').addEventListener('click', adminReset);
        
        // 可选：回车快捷提交 (在姓名下拉或餐品区域回车)
        const handleEnter = (e) => {
            if (e.key === 'Enter') onSubmit();
        };
        document.getElementById('studentSelect').addEventListener('keypress', handleEnter);
        document.querySelectorAll('input[name="foodRadio"]').forEach(r => r.addEventListener('keypress', handleEnter));
    }
    
    function escapeHtml(str) {
        if (!str) return '';
        return str.replace(/[&<>]/g, function(m) {
            if (m === '&') return '&amp;';
            if (m === '<') return '&lt;';
            if (m === '>') return '&gt;';
            return m;
        });
    }
    
    init();
</script>
</body>
  </html>
