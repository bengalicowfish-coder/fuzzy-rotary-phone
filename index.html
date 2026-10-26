<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ParcelGo & E-Commerce Management System</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Hind+Siliguri:wght@400;500;600;700&display=swap');
        body { font-family: 'Hind Siliguri', sans-serif; background-color: #f8fafc; }
        .custom-scrollbar::-webkit-scrollbar { width: 6px; }
        .custom-scrollbar::-webkit-scrollbar-track { background: #f1f5f9; }
        .custom-scrollbar::-webkit-scrollbar-thumb { background: #cbd5e1; border-radius: 4px; }
    </style>
</head>
<body class="text-slate-800 antialiased">

    <div class="flex h-screen overflow-hidden">
        <!-- Sidebar -->
        <aside class="w-64 bg-slate-900 text-white flex flex-col justify-between shrink-0">
            <div>
                <div class="h-16 flex items-center px-6 bg-slate-950 font-bold text-xl tracking-wide text-indigo-400 border-b border-slate-800">
                    <i class="fa-solid fa-truck-fast mr-3"></i> ParcelGo Express
                </div>
                <nav class="mt-4 px-3 space-y-1">
                    <button onclick="switchTab('dashboard')" id="nav-dashboard" class="nav-btn w-full flex items-center px-4 py-3 text-slate-300 hover:bg-slate-800 hover:text-white rounded-lg transition font-medium text-sm">
                        <i class="fa-solid fa-chart-pie w-6"></i> ড্যাশবোর্ড
                    </button>
                    <button onclick="switchTab('shop')" id="nav-shop" class="nav-btn w-full flex items-center px-4 py-3 text-slate-300 hover:bg-slate-800 hover:text-white rounded-lg transition font-medium text-sm">
                        <i class="fa-solid fa-store w-6"></i> ই-কমার্স শপ (সেলস)
                    </button>
                    <button onclick="switchTab('product-management')" id="nav-product-management" class="nav-btn w-full flex items-center px-4 py-3 text-slate-300 hover:bg-slate-800 hover:text-white rounded-lg transition font-medium text-sm">
                        <i class="fa-solid fa-boxes-stacked w-6"></i> প্রোডাক্ট যোগ ও স্টক
                    </button>
                    <button onclick="switchTab('create-parcel')" id="nav-create-parcel" class="nav-btn w-full flex items-center px-4 py-3 text-slate-300 hover:bg-slate-800 hover:text-white rounded-lg transition font-medium text-sm">
                        <i class="fa-solid fa-box-archive w-6"></i> পার্সেল বুকিং
                    </button>
                    <button onclick="switchTab('orders')" id="nav-orders" class="nav-btn w-full flex items-center px-4 py-3 text-slate-300 hover:bg-slate-800 hover:text-white rounded-lg transition font-medium text-sm">
                        <i class="fa-solid fa-list-check w-6"></i> অর্ডার ও ট্র্যাকিং
                    </button>
                    <button onclick="switchTab('payouts')" id="nav-payouts" class="nav-btn w-full flex items-center px-4 py-3 text-slate-300 hover:bg-slate-800 hover:text-white rounded-lg transition font-medium text-sm">
                        <i class="fa-solid fa-wallet w-6"></i> বিকাশ পেআউট সেটিংস
                    </button>
                </nav>
            </div>
            <div class="p-4 border-t border-slate-800 bg-slate-950">
                <div class="flex items-center space-x-3">
                    <div class="w-10 h-10 rounded-full bg-indigo-600 flex items-center justify-center font-bold text-white">
                        <i class="fa-solid fa-user-shield"></i>
                    </div>
                    <div>
                        <p class="text-sm font-semibold text-white">মার্চেন্ট প্যানেল</p>
                        <p class="text-xs text-slate-400">এপিআই কানেক্টেড</p>
                    </div>
                </div>
            </div>
        </aside>

        <!-- Main Content -->
        <main class="flex-1 flex flex-col min-w-0 bg-slate-50 overflow-hidden">
            <!-- Topbar -->
            <header class="h-16 bg-white border-b border-slate-200 flex items-center justify-between px-8 shrink-0">
                <div class="flex items-center space-x-4">
                    <h1 id="page-title" class="text-xl font-bold text-slate-800">ড্যাশবোর্ড</h1>
                </div>
                <div class="flex items-center space-x-4">
                    <button onclick="switchTab('shop')" class="relative p-2 text-slate-600 hover:text-indigo-600 transition">
                        <i class="fa-solid fa-cart-shopping text-xl"></i>
                        <span id="cart-count" class="absolute -top-1 -right-1 bg-rose-500 text-white text-xs font-bold w-5 h-5 rounded-full flex items-center justify-center">0</span>
                    </button>
                    <div class="h-6 w-px bg-slate-200"></div>
                    <span class="inline-flex items-center px-2.5 py-1 rounded-full text-xs font-medium bg-emerald-100 text-emerald-800">
                        <span class="w-2 h-2 mr-1.5 bg-emerald-500 rounded-full animate-pulse"></span> এপিআই লাইভ
                    </span>
                </div>
            </header>

            <!-- Scrollable Content View -->
            <div class="flex-1 overflow-y-auto p-8 custom-scrollbar">
                
                <!-- 1. DASHBOARD -->
                <section id="sec-dashboard" class="tab-content space-y-6">
                    <div class="grid grid-cols-1 md:grid-cols-4 gap-6">
                        <div class="bg-white p-6 rounded-xl border border-slate-200 shadow-sm">
                            <p class="text-xs font-semibold text-slate-500 uppercase tracking-wider">মোট প্রোডাক্ট সেলস</p>
                            <p class="text-2xl font-bold text-slate-800 mt-2">৳ <span id="dash-total-sales">১,৮,৫০০</span></p>
                        </div>
                        <div class="bg-white p-6 rounded-xl border border-slate-200 shadow-sm">
                            <p class="text-xs font-semibold text-slate-500 uppercase tracking-wider">সক্রিয় পার্সেল ডেলিভারি</p>
                            <p class="text-2xl font-bold text-slate-800 mt-2" id="dash-active-parcels">৪ টি</p>
                        </div>
                        <div class="bg-white p-6 rounded-xl border border-slate-200 shadow-sm">
                            <p class="text-xs font-semibold text-slate-500 uppercase tracking-wider">সফল ডেলিভারি</p>
                            <p class="text-2xl font-bold text-emerald-600 mt-2">১২৮ টি</p>
                        </div>
                        <div class="bg-white p-6 rounded-xl border border-slate-200 shadow-sm">
                            <p class="text-xs font-semibold text-slate-500 uppercase tracking-wider">বিকাশ পেআউট অ্যাকাউন্ট</p>
                            <p class="text-lg font-bold text-slate-800 mt-2 flex items-center">
                                <span id="dash-payout-number">015XXXXXX49</span>
                                <span class="ml-2 text-xs bg-indigo-100 text-indigo-700 px-2 py-0.5 rounded font-semibold">ডিফল্ট</span>
                            </p>
                        </div>
                    </div>

                    <div class="bg-white p-6 rounded-xl border border-slate-200 shadow-sm">
                        <h3 class="font-bold text-slate-800 mb-4 text-base">সাম্প্রতিক অর্ডার ও পার্সেল কার্যক্রম</h3>
                        <div class="overflow-x-auto">
                            <table class="w-full text-left text-sm">
                                <thead class="bg-slate-50 border-y border-slate-200 text-slate-600 font-semibold">
                                    <tr>
                                        <th class="py-3 px-4">অর্ডার আইডি</th>
                                        <th class="py-3 px-4">প্রাপক</th>
                                        <th class="py-3 px-4">ঠিকানা</th>
                                        <th class="py-3 px-4">চার্জ</th>
                                        <th class="py-3 px-4">স্ট্যাটাস</th>
                                    </tr>
                                </thead>
                                <tbody id="dash-table-body" class="divide-y divide-slate-100">
                                    <!-- Dynamic Rows -->
                                </tbody>
                            </table>
                        </div>
                    </div>
                </section>

                <!-- 2. E-COMMERCE SHOP -->
                <section id="sec-shop" class="tab-content hidden space-y-6">
                    <div class="flex justify-between items-center">
                        <h2 class="text-lg font-bold text-slate-800">ক্যাটালগ থেকে প্রোডাক্ট নির্বাচন করুন</h2>
                        <div class="flex space-x-2">
                            <input type="text" id="shop-search" placeholder="প্রোডাক্ট খুঁজুন..." class="border border-slate-300 rounded-lg px-4 py-2 text-sm focus:outline-none focus:ring-2 focus:ring-indigo-500 w-64">
                        </div>
                    </div>
                    <div class="grid grid-cols-1 md:grid-cols-3 gap-6" id="product-grid">
                        <!-- Dynamic Product Cards -->
                    </div>
                </section>

                <!-- 3. PRODUCT MANAGEMENT -->
                <section id="sec-product-management" class="tab-content hidden space-y-6">
                    <div class="grid grid-cols-1 lg:grid-cols-3 gap-8">
                        <div class="bg-white p-6 rounded-xl border border-slate-200 shadow-sm">
                            <h3 class="font-bold text-slate-800 mb-4 pb-2 border-b border-slate-100">নতুন প্রোডাক্ট যোগ করুন</h3>
                            <form id="add-product-form" onsubmit="handleAddProduct(event)" class="space-y-4">
                                <div>
                                    <label class="block text-xs font-semibold text-slate-600 mb-1">প্রোডাক্টের নাম</label>
                                    <input type="text" id="p-name" required class="w-full border border-slate-300 rounded-lg p-2.5 text-sm focus:ring-2 focus:ring-indigo-500 focus:outline-none">
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-slate-600 mb-1">ক্যাটাগরি</label>
                                    <select id="p-category" class="w-full border border-slate-300 rounded-lg p-2.5 text-sm focus:ring-2 focus:ring-indigo-500 focus:outline-none">
                                        <option value="Homemade Food">হোমমেড ফুড</option>
                                        <option value="Clothes">পোশাক</option>
                                        <option value="Electronics">ইলেক্ট্রনিক্স</option>
                                        <option value="Documents">ডকুমেন্টস</option>
                                    </select>
                                </div>
                                <div class="grid grid-cols-2 gap-4">
                                    <div>
                                        <label class="block text-xs font-semibold text-slate-600 mb-1">মূল্য (৳)</label>
                                        <input type="number" id="p-price" required class="w-full border border-slate-300 rounded-lg p-2.5 text-sm focus:ring-2 focus:ring-indigo-500 focus:outline-none">
                                    </div>
                                    <div>
                                        <label class="block text-xs font-semibold text-slate-600 mb-1">ওজন (গ্রাম)</label>
                                        <input type="number" id="p-weight" required class="w-full border border-slate-300 rounded-lg p-2.5 text-sm focus:ring-2 focus:ring-indigo-500 focus:outline-none">
                                    </div>
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-slate-600 mb-1">ছবি ইউআরএল</label>
                                    <input type="text" id="p-img" placeholder="https://..." class="w-full border border-slate-300 rounded-lg p-2.5 text-sm focus:ring-2 focus:ring-indigo-500 focus:outline-none">
                                </div>
                                <button type="submit" class="w-full bg-indigo-600 hover:bg-indigo-700 text-white font-semibold py-2.5 rounded-lg text-sm transition">
                                    <i class="fa-solid fa-plus mr-2"></i> প্রোডাক্ট সেভ করুন
                                </button>
                            </form>
                        </div>

                        <div class="lg:col-span-2 bg-white p-6 rounded-xl border border-slate-200 shadow-sm">
                            <h3 class="font-bold text-slate-800 mb-4 pb-2 border-b border-slate-100">বিদ্যমান প্রোডাক্ট লিস্ট</h3>
                            <div class="overflow-x-auto">
                                <table class="w-full text-left text-sm">
                                    <thead class="bg-slate-50 border-b border-slate-200 text-slate-600 font-semibold">
                                        <tr>
                                            <th class="py-3 px-4">প্রোডাক্ট</th>
                                            <th class="py-3 px-4">ক্যাটাগরি</th>
                                            <th class="py-3 px-4">মূল্য</th>
                                            <th class="py-3 px-4">ওজন</th>
                                            <th class="py-3 px-4 text-right">অ্যাকশন</th>
                                        </tr>
                                    </thead>
                                    <tbody id="product-list-table" class="divide-y divide-slate-100">
                                        <!-- Dynamic Inventory Table -->
                                    </tbody>
                                </table>
                            </div>
                        </div>
                    </div>
                </section>

                <!-- 4. PARCEL BOOKING -->
                <section id="sec-create-parcel" class="tab-content hidden space-y-6">
                    <div class="bg-white p-8 rounded-xl border border-slate-200 shadow-sm max-w-4xl mx-auto">
                        <h2 class="text-lg font-bold text-slate-800 mb-6 pb-2 border-b border-slate-100 flex items-center">
                            <i class="fa-solid fa-truck-ramp-box mr-3 text-indigo-600"></i> অন-ডিমান্ড পার্সেল বুকিং ফরম
                        </h2>
                        <form id="parcel-form" onsubmit="handleCreateParcel(event)" class="space-y-6">
                            <!-- Category Select -->
                            <div>
                                <label class="block text-xs font-semibold text-slate-600 mb-2">পার্সেল টাইপ নির্বাচন করুন</label>
                                <select id="parcel-type-select" class="w-full border border-slate-300 rounded-lg p-3 text-sm focus:ring-2 focus:ring-indigo-500 focus:outline-none">
                                    <option value="104">Homemade Food (Max 5,000g, ৳2,000)</option>
                                    <option value="101">Documents (Max 2,000g, ৳1,000)</option>
                                    <option value="102">Clothes (Max 10,000g, ৳5,000)</option>
                                    <option value="103">Electronics (Max 5,000g, ৳10,000)</option>
                                </select>
                            </div>

                            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                                <!-- Sender -->
                                <div class="p-4 bg-slate-50 rounded-lg border border-slate-200 space-y-3">
                                    <h4 class="font-bold text-sm text-slate-700">পিকআপ ডিটেইলস (প্রেরক)</h4>
                                    <input type="text" id="pickup-name" value="Imran" placeholder="নাম" required class="w-full border border-slate-300 rounded p-2 text-sm">
                                    <input type="text" id="pickup-phone" value="015XXXXXX49" placeholder="ফোন নম্বর" required class="w-full border border-slate-300 rounded p-2 text-sm">
                                    <input type="text" id="pickup-address" value="31, Road 7, Section 12" placeholder="ঠিকানা" required class="w-full border border-slate-300 rounded p-2 text-sm">
                                </div>

                                <!-- Receiver -->
                                <div class="p-4 bg-slate-50 rounded-lg border border-slate-200 space-y-3">
                                    <h4 class="font-bold text-sm text-slate-700">ড্রপঅফ ডিটেইলস (প্রাপক)</h4>
                                    <input type="text" id="receiver-name" value="Tanvir Ahmed" placeholder="নাম" required class="w-full border border-slate-300 rounded p-2 text-sm">
                                    <input type="text" id="receiver-phone" value="01711002233" placeholder="ফোন নম্বর" required class="w-full border border-slate-300 rounded p-2 text-sm">
                                    <input type="text" id="receiver-address" value="Mirpur 12 Bus Stand" placeholder="ঠিকানা" required class="w-full border border-slate-300 rounded p-2 text-sm">
                                </div>
                            </div>

                            <!-- Item Info -->
                            <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
                                <div>
                                    <label class="block text-xs font-semibold text-slate-600 mb-1">আইটেমের নাম</label>
                                    <input type="text" id="item-name" value="Pizza" required class="w-full border border-slate-300 rounded p-2 text-sm">
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-slate-600 mb-1">মূল্য (৳)</label>
                                    <input type="number" id="item-price" value="900" required class="w-full border border-slate-300 rounded p-2 text-sm">
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-slate-600 mb-1">ওজন (গ্রাম)</label>
                                    <input type="number" id="item-weight" value="120" required class="w-full border border-slate-300 rounded p-2 text-sm">
                                </div>
                            </div>

                            <button type="submit" class="w-full bg-emerald-600 hover:bg-emerald-700 text-white font-bold py-3 rounded-lg text-sm transition">
                                <i class="fa-solid fa-paper-plane mr-2"></i> কনফার্ম ও ডেলিভারি রিকোয়েস্ট পাঠান
                            </button>
                        </form>
                    </div>
                </section>

                <!-- 5. ORDERS & TRACKING -->
                <section id="sec-orders" class="tab-content hidden space-y-6">
                    <div class="bg-white p-6 rounded-xl border border-slate-200 shadow-sm">
                        <h3 class="font-bold text-slate-800 mb-4 pb-2 border-b border-slate-100">লাইব পার্সেল ট্র্যাকিং ও অর্ডার লিস্ট</h3>
                        <div class="space-y-4" id="orders-container">
                            <!-- Dynamic Active Orders List -->
                        </div>
                    </div>
                </section>

                <!-- 6. BKASH PAYOUT SETTINGS -->
                <section id="sec-payouts" class="tab-content hidden space-y-6">
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                        <div class="bg-white p-6 rounded-xl border border-slate-200 shadow-sm">
                            <h3 class="font-bold text-slate-800 mb-4 pb-2 border-b border-slate-100 flex items-center">
                                <i class="fa-solid fa-mobile-retro text-rose-500 mr-2"></i> বিকাশ পেআউট অ্যাকাউন্ট সংযুক্ত করুন
                            </h3>
                            <form id="payout-form" onsubmit="handleAddPayout(event)" class="space-y-4">
                                <div>
                                    <label class="block text-xs font-semibold text-slate-600 mb-1">অ্যাকাউন্ট টাইপ</label>
                                    <select id="payout-type" class="w-full border border-slate-300 rounded-lg p-2.5 text-sm">
                                        <option value="PERSONAL">PERSONAL</option>
                                        <option value="MERCHANT">MERCHANT</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="block text-xs font-semibold text-slate-600 mb-1">বিকাশ নম্বর</label>
                                    <input type="text" id="payout-number" placeholder="017XXXXXXXX" required class="w-full border border-slate-300 rounded-lg p-2.5 text-sm">
                                </div>
                                <button type="submit" class="w-full bg-rose-600 hover:bg-rose-700 text-white font-semibold py-2.5 rounded-lg text-sm transition">
                                    <i class="fa-solid fa-link mr-2"></i> পেআউট মেথড সেভ করুন
                                </button>
                            </form>
                        </div>

                        <div class="bg-white p-6 rounded-xl border border-slate-200 shadow-sm">
                            <h3 class="font-bold text-slate-800 mb-4 pb-2 border-b border-slate-100">সংযুক্ত পেআউট মেথডসমূহ</h3>
                            <div class="space-y-4" id="payout-list">
                                <!-- Dynamic Payout Methods -->
                            </div>
                        </div>
                    </div>
                </section>

            </div>
        </main>
    </div>

    <!-- JavaScript Application Logic -->
    <script>
        // State Management
        let products = [
            { id: 1, name: "চিকেন পিজ্জা (স্মল)", category: "Homemade Food", price: 900, weight: 120, img: "https://images.unsplash.com/photo-1513104890138-7c749659a591?w=400" },
            { id: 2, name: "লেদার ওয়ালেট", category: "Clothes", price: 1200, weight: 150, img: "https://images.unsplash.com/photo-1627123424574-724758594e93?w=400" },
            { id: 3, name: "ওয়্যারলেস ইয়ারবাডস", category: "Electronics", price: 2500, weight: 200, img: "https://images.unsplash.com/photo-1590658268037-6bf12165a8df?w=400" }
        ];

        let orders = [
            {
                orderId: "4LHV2YB",
                status: "CANCELLED",
                charge: 114.26,
                receiver: "Tanvir Ahmed",
                address: "Mirpur 12 Bus Stand",
                item: "Pizza",
                rider: { name: "asibul H Hasan", number: "01767191651", vehicle: "DHK METRO HA 55-5956" }
            },
            {
                orderId: "8KJH3NX",
                status: "DELIVERED",
                charge: 85.00,
                receiver: "Sajid Khan",
                address: "Uttara Sector 10",
                item: "Documents",
                rider: { name: "Kabir Hossain", number: "01811223344", vehicle: "DHK METRO HA 12-3456" }
            }
        ];

        let payoutMethods = [
            { slug: "84cf4c66262f53771bd547df", method: "BKASH", account_type: "PERSONAL", masked_number: "015XXXXXX49", is_default: true }
        ];

        let cart = [];

        // Tab Switcher
        function switchTab(tabId) {
            document.querySelectorAll('.tab-content').forEach(el => el.classList.add('hidden'));
            document.querySelectorAll('.nav-btn').forEach(el => {
                el.classList.remove('bg-slate-800', 'text-white');
                el.classList.add('text-slate-300');
            });

            document.getElementById(`sec-${tabId}`).classList.remove('hidden');
            const activeNav = document.getElementById(`nav-${tabId}`);
            if (activeNav) {
                activeNav.classList.add('bg-slate-800', 'text-white');
            }

            const titles = {
                'dashboard': 'ড্যাশবোর্ড ওভারভিউ',
                'shop': 'ই-কমার্স শপ',
                'product-management': 'প্রোডাক্ট স্টক ও ক্যাটালগ',
                'create-parcel': 'অন-ডিমান্ড পার্সেল বুকিং',
                'orders': 'অর্ডার ট্র্যাকিং সিস্টেম',
                'payouts': 'বিকাশ পেআউট সেটিংস'
            };
            document.getElementById('page-title').innerText = titles[tabId] || '';
            renderAll();
        }

        // Render Functions
        function renderAll() {
            renderDashboard();
            renderShop();
            renderProductTable();
            renderOrders();
            renderPayouts();
        }

        function renderDashboard() {
            const tbody = document.getElementById('dash-table-body');
            tbody.innerHTML = orders.map(o => `
                <tr>
                    <td class="py-3 px-4 font-mono font-bold text-indigo-600">#${o.orderId}</td>
                    <td class="py-3 px-4">${o.receiver}</td>
                    <td class="py-3 px-4">${o.address}</td>
                    <td class="py-3 px-4">৳ ${o.charge}</td>
                    <td class="py-3 px-4">
                        <span class="px-2 py-1 rounded text-xs font-bold ${o.status === 'CANCELLED' ? 'bg-rose-100 text-rose-700' : 'bg-emerald-100 text-emerald-700'}">
                            ${o.status}
                        </span>
                    </td>
                </tr>
            `).join('');

            document.getElementById('dash-active-parcels').innerText = `${orders.filter(o => o.status !== 'CANCELLED').length} টি`;
            const defPayout = payoutMethods.find(p => p.is_default);
            if(defPayout) {
                document.getElementById('dash-payout-number').innerText = defPayout.masked_number;
            }
        }

        function renderShop() {
            const grid = document.getElementById('product-grid');
            grid.innerHTML = products.map(p => `
                <div class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition">
                    <img src="${p.img || 'https://via.placeholder.com/300'}" class="h-40 w-full object-cover bg-slate-100">
                    <div class="p-4 space-y-2">
                        <span class="text-xs font-bold text-indigo-600 bg-indigo-50 px-2 py-0.5 rounded">${p.category}</span>
                        <h4 class="font-bold text-slate-800">${p.name}</h4>
                        <div class="flex justify-between items-center pt-2">
                            <span class="font-bold text-slate-900">৳ ${p.price}</span>
                            <button onclick="addToCart(${p.id})" class="bg-slate-900 hover:bg-indigo-600 text-white text-xs px-3 py-2 rounded-lg font-semibold transition">
                                <i class="fa-solid fa-cart-plus mr-1"></i> অর্ডার করুন
                            </button>
                        </div>
                    </div>
                </div>
            `).join('');
        }

        function renderProductTable() {
            const tbody = document.getElementById('product-list-table');
            tbody.innerHTML = products.map(p => `
                <tr>
                    <td class="py-3 px-4 font-semibold text-slate-800">${p.name}</td>
                    <td class="py-3 px-4"><span class="text-xs bg-slate-100 text-slate-600 px-2 py-1 rounded">${p.category}</span></td>
                    <td class="py-3 px-4">৳ ${p.price}</td>
                    <td class="py-3 px-4">${p.weight}g</td>
                    <td class="py-3 px-4 text-right">
                        <button onclick="deleteProduct(${p.id})" class="text-rose-500 hover:text-rose-700 text-xs font-semibold">
                            <i class="fa-solid fa-trash"></i> মুছে ফেলুন
                        </button>
                    </td>
                </tr>
            `).join('');
        }

        function renderOrders() {
            const container = document.getElementById('orders-container');
            container.innerHTML = orders.map(o => `
                <div class="border border-slate-200 rounded-lg p-5 bg-slate-50 space-y-3">
                    <div class="flex justify-between items-center border-b border-slate-200 pb-3">
                        <div>
                            <span class="text-xs font-bold text-slate-400">অর্ডার আইডি</span>
                            <h4 class="font-mono font-bold text-indigo-600 text-base">#${o.orderId}</h4>
                        </div>
                        <span class="px-3 py-1 rounded-full text-xs font-bold ${o.status === 'CANCELLED' ? 'bg-rose-100 text-rose-700' : 'bg-emerald-100 text-emerald-700'}">
                            ${o.status}
                        </span>
                    </div>
                    <div class="grid grid-cols-1 md:grid-cols-3 gap-4 text-xs">
                        <div>
                            <p class="text-slate-500">প্রাপক:</p>
                            <p class="font-bold text-slate-800">${o.receiver}</p>
                            <p class="text-slate-600">${o.address}</p>
                        </div>
                        <div>
                            <p class="text-slate-500">আইটেম:</p>
                            <p class="font-bold text-slate-800">${o.item}</p>
                            <p class="text-slate-600">ডেলিভারি চার্জ: ৳${o.charge}</p>
                        </div>
                        <div>
                            <p class="text-slate-500">রাইডার ডিটেইলস:</p>
                            <p class="font-bold text-slate-800">${o.rider.name} (${o.rider.number})</p>
                            <p class="text-slate-600">বাইক: ${o.rider.vehicle}</p>
                        </div>
                    </div>
                    ${o.status !== 'CANCELLED' ? `
                        <div class="pt-2 text-right">
                            <button onclick="cancelOrder('${o.orderId}')" class="bg-rose-600 hover:bg-rose-700 text-white text-xs px-3 py-1.5 rounded font-semibold transition">
                                পার্সেল ক্যানসেল করুন
                            </button>
                        </div>
                    ` : ''}
                </div>
            `).join('');
        }

        function renderPayouts() {
            const container = document.getElementById('payout-list');
            container.innerHTML = payoutMethods.map(p => `
                <div class="border border-slate-200 rounded-lg p-4 flex items-center justify-between bg-slate-50">
                    <div class="flex items-center space-x-3">
                        <div class="w-10 h-10 rounded-full bg-rose-100 text-rose-600 flex items-center justify-center font-bold">
                            <i class="fa-solid fa-mobile-screen-button"></i>
                        </div>
                        <div>
                            <p class="text-sm font-bold text-slate-800">${p.method} (${p.account_type})</p>
                            <p class="text-xs font-mono text-slate-500">${p.masked_number}</p>
                        </div>
                    </div>
                    <div class="flex items-center space-x-2">
                        ${p.is_default ? `
                            <span class="text-xs bg-emerald-100 text-emerald-700 px-2 py-1 rounded font-bold">ডিফল্ট</span>
                        ` : `
                            <button onclick="setDefaultPayout('${p.slug}')" class="text-xs bg-slate-200 hover:bg-slate-300 px-2 py-1 rounded font-semibold">ডিফল্ট করুন</button>
                        `}
                        <button onclick="deletePayout('${p.slug}')" class="text-rose-500 hover:text-rose-700 text-xs p-1">
                            <i class="fa-solid fa-trash"></i>
                        </button>
                    </div>
                </div>
            `).join('');
        }

        // Actions
        function handleAddProduct(e) {
            e.preventDefault();
            const newP = {
                id: Date.now(),
                name: document.getElementById('p-name').value,
                category: document.getElementById('p-category').value,
                price: parseFloat(document.getElementById('p-price').value),
                weight: parseInt(document.getElementById('p-weight').value),
                img: document.getElementById('p-img').value || 'https://images.unsplash.com/photo-1526170375885-4d8ecf77b99f?w=400'
            };
            products.unshift(newP);
            document.getElementById('add-product-form').reset();
            renderAll();
            alert('প্রোডাক্ট সফলভাবে যুক্ত হয়েছে!');
        }

        function deleteProduct(id) {
            products = products.filter(p => p.id !== id);
            renderAll();
        }

        function addToCart(pId) {
            cart.push(pId);
            document.getElementById('cart-count').innerText = cart.length;
            alert('প্রোডাক্ট কার্টে যুক্ত করা হয়েছে!');
        }

        function handleCreateParcel(e) {
            e.preventDefault();
            const newOrder = {
                orderId: Math.random().toString(36).substring(2, 9).toUpperCase(),
                status: "ACCEPTED",
                charge: 114.26,
                receiver: document.getElementById('receiver-name').value,
                address: document.getElementById('receiver-address').value,
                item: document.getElementById('item-name').value,
                rider: { name: "asibul H Hasan", number: "01767191651", vehicle: "DHK METRO HA 55-5956" }
            };
            orders.unshift(newOrder);
            switchTab('orders');
            alert('পার্সেল ডেলিভারি রিকোয়েস্ট তৈরি হয়েছে!');
        }

        function cancelOrder(orderId) {
            const order = orders.find(o => o.orderId === orderId);
            if (order) {
                order.status = "CANCELLED";
                renderAll();
                alert('পার্সেল অর্ডারটি বাতিল করা হয়েছে!');
            }
        }

        function handleAddPayout(e) {
            e.preventDefault();
            const newPayout = {
                slug: Math.random().toString(36).substring(2, 12),
                method: "BKASH",
                account_type: document.getElementById('payout-type').value,
                masked_number: document.getElementById('payout-number').value,
                is_default: payoutMethods.length === 0
            };
            payoutMethods.push(newPayout);
            document.getElementById('payout-form').reset();
            renderAll();
            alert('বিকাশ পেআউট অ্যাকাউন্ট যুক্ত হয়েছে!');
        }

        function setDefaultPayout(slug) {
            payoutMethods.forEach(p => p.is_default = (p.slug === slug));
            renderAll();
        }

        function deletePayout(slug) {
            payoutMethods = payoutMethods.filter(p => p.slug !== slug);
            renderAll();
        }

        // Initialize App
        document.addEventListener('DOMContentLoaded', () => {
            switchTab('dashboard');
        });
    </script>
</body>
</html>
