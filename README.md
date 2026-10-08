# Beckygiftcards-shop-<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BECKY CARDSALES - Turn Your Gift Cards To Instant Naira</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            green: '#00A859',
                            darkGreen: '#008745',
                            lightGreen: '#E6F4ED',
                            gold: '#FFC72C',
                            darkGold: '#E5B11B',
                            dark: '#111827'
                        }
                    }
                }
            }
        }
    </script>
    <!-- FontAwesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts: Plus Jakarta Sans -->
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Plus Jakarta Sans', sans-serif; }
        @keyframes ticker {
            0% { transform: translate3d(0, 0, 0); }
            100% { transform: translate3d(-50%, 0, 0); }
        }
        .animate-ticker {
            display: flex;
            width: 200%;
            animation: ticker 25s linear infinite;
        }
        .animate-ticker:hover {
            animation-play-state: paused;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-900 antialiased selection:bg-brand-green selection:text-white">

    <!-- Top Live Ticker Bar -->
    <div class="bg-brand-dark text-white text-xs py-2 overflow-hidden whitespace-nowrap border-b border-gray-800">
        <div class="animate-ticker flex space-x-8 font-medium">
            <span class="inline-flex items-center"><i class="fa-solid fa-bolt text-brand-gold mr-1.5"></i> Amazon Rate: $1 = ₦1,250</span>
            <span class="inline-flex items-center"><i class="fa-solid fa-bolt text-brand-gold mr-1.5"></i> Steam Rate: $1 = ₦1,220</span>
            <span class="inline-flex items-center"><i class="fa-solid fa-bolt text-brand-gold mr-1.5"></i> Apple/iTunes: $1 = ₦1,200</span>
            <span class="inline-flex items-center"><i class="fa-solid fa-bolt text-brand-gold mr-1.5"></i> Google Play: $1 = ₦1,180</span>
            <span class="inline-flex items-center"><i class="fa-solid fa-bolt text-brand-gold mr-1.5"></i> Razer Gold: $1 = ₦1,230</span>
            <span class="inline-flex items-center text-brand-gold"><i class="fa-solid fa-circle-check mr-1"></i> Over 5,000+ Successful Trades in Lagos</span>
            <!-- Duplicate for smooth loop -->
            <span class="inline-flex items-center"><i class="fa-solid fa-bolt text-brand-gold mr-1.5"></i> Amazon Rate: $1 = ₦1,250</span>
            <span class="inline-flex items-center"><i class="fa-solid fa-bolt text-brand-gold mr-1.5"></i> Steam Rate: $1 = ₦1,220</span>
            <span class="inline-flex items-center"><i class="fa-solid fa-bolt text-brand-gold mr-1.5"></i> Apple/iTunes: $1 = ₦1,200</span>
            <span class="inline-flex items-center"><i class="fa-solid fa-bolt text-brand-gold mr-1.5"></i> Google Play: $1 = ₦1,180</span>
            <span class="inline-flex items-center"><i class="fa-solid fa-bolt text-brand-gold mr-1.5"></i> Razer Gold: $1 = ₦1,230</span>
        </div>
    </div>

    <!-- Header / Navbar -->
    <header class="sticky top-0 z-50 bg-white/90 backdrop-blur-md border-b border-gray-100 shadow-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <!-- Logo -->
            <a href="#" class="flex items-center space-x-3">
                <div class="w-11 h-11 rounded-2xl bg-brand-green flex items-center justify-center text-white shadow-lg shadow-brand-green/30">
                    <i class="fa-solid fa-wallet text-xl"></i>
                </div>
                <div>
                    <span class="text-xl font-extrabold tracking-tight text-brand-dark block leading-none">BECKY<span class="text-brand-green">CARDSALES</span></span>
                    <span class="text-[10px] font-bold text-brand-darkGold uppercase tracking-wider">Instant Gift Card Exchanger</span>
                </div>
            </a>

            <!-- Desktop Nav Links -->
            <nav class="hidden md:flex items-center space-x-8 font-semibold text-sm text-gray-600">
                <a href="#calculator" class="hover:text-brand-green transition">Rate Calculator</a>
                <a href="#how-it-works" class="hover:text-brand-green transition">How It Works</a>
                <a href="#cards" class="hover:text-brand-green transition">Cards We Buy</a>
                <a href="#why-us" class="hover:text-brand-green transition">Why Us</a>
                <a href="#testimonials" class="hover:text-brand-green transition">Reviews</a>
                <a href="#faq" class="hover:text-brand-green transition">FAQ</a>
            </nav>

            <!-- WhatsApp CTA Button -->
            <div class="flex items-center space-x-3">
                <a href="https://wa.me/2349079154392?text=Hello%20Becky%2C%20I%20want%20to%20sell%20my%20gift%20card." target="_blank" class="bg-brand-green hover:bg-brand-darkGreen text-white font-bold px-5 py-2.5 rounded-xl shadow-lg shadow-brand-green/30 flex items-center space-x-2 transition transform active:scale-95 text-sm">
                    <i class="fa-brands fa-whatsapp text-lg"></i>
                    <span>Chat on WhatsApp</span>
                </a>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative bg-gradient-to-b from-brand-lightGreen/50 via-white to-white pt-12 pb-20 overflow-hidden">
        <div class="absolute -top-24 -right-24 w-96 h-96 rounded-full bg-brand-green/10 blur-3xl pointer-events-none"></div>
        <div class="absolute top-1/2 -left-24 w-80 h-80 rounded-full bg-brand-gold/10 blur-3xl pointer-events-none"></div>
        
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="grid lg:grid-cols-12 gap-12 items-center">
                
                <!-- Left Hero Content -->
                <div class="lg:col-span-7 space-y-6 text-center lg:text-left">
                    <div class="inline-flex items-center space-x-2 bg-brand-green/10 text-brand-green px-4 py-2 rounded-full text-xs font-bold uppercase tracking-wider">
                        <span class="w-2 h-2 rounded-full bg-brand-green animate-ping"></span>
                        <span>Lagos, Nigeria • 24/7 Active Support</span>
                    </div>

                    <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold text-brand-dark tracking-tight leading-tight">
                        Turn Your Gift Cards To <span class="text-brand-green underline decoration-brand-gold decoration-4 underline-offset-8">Instant Cash</span>
                    </h1>

                    <p class="text-lg sm:text-xl font-semibold text-gray-700">
                        Best Rate <span class="text-brand-green mx-1">•</span> Instant Payment <span class="text-brand-green mx-1">•</span> 100% Trusted
                    </p>

                    <p class="text-gray-600 text-base max-w-xl mx-auto lg:mx-0">
                        Experience lightning-fast payouts directly to your Nigerian bank account or Opay/PalmPay wallet. No delays, zero scams, highest safety standards guaranteed.
                    </p>

                    <!-- Trust Badges -->
                    <div class="grid grid-cols-3 gap-4 pt-2 max-w-md mx-auto lg:mx-0">
                        <div class="bg-white p-3 rounded-xl border border-gray-100 shadow-sm text-center">
                            <i class="fa-solid fa-shield-halved text-brand-green text-xl mb-1"></i>
                            <div class="text-xs font-bold text-gray-800">100% Secure</div>
                        </div>
                        <div class="bg-white p-3 rounded-xl border border-gray-100 shadow-sm text-center">
                            <i class="fa-solid fa-bolt text-brand-gold text-xl mb-1"></i>
                            <div class="text-xs font-bold text-gray-800">&lt; 3 Mins Payout</div>
                        </div>
                        <div class="bg-white p-3 rounded-xl border border-gray-100 shadow-sm text-center">
                            <i class="fa-solid fa-star text-yellow-500 text-xl mb-1"></i>
                            <div class="text-xs font-bold text-gray-800">Top Market Rates</div>
                        </div>
                    </div>

                    <!-- CTA Buttons -->
                    <div class="pt-4 flex flex-col sm:flex-row items-center justify-center lg:justify-start gap-4">
                        <a href="https://wa.me/2349079154392?text=Hello%20Becky%2C%20I%20want%20to%20sell%20my%20gift%20card." target="_blank" class="w-full sm:w-auto bg-brand-green hover:bg-brand-darkGreen text-white font-extrabold px-8 py-4 rounded-2xl shadow-xl shadow-brand-green/30 flex items-center justify-center space-x-3 text-lg transition transform active:scale-95">
                            <i class="fa-brands fa-whatsapp text-2xl"></i>
                            <span>Trade Now on WhatsApp</span>
                        </a>
                        <a href="#calculator" class="w-full sm:w-auto bg-white hover:bg-gray-50 text-brand-dark border-2 border-gray-200 font-bold px-6 py-4 rounded-2xl flex items-center justify-center space-x-2 text-base transition">
                            <i class="fa-solid fa-calculator text-brand-green"></i>
                            <span>Calculate Rates</span>
                        </a>
                    </div>
                </div>

                <!-- Right Hero Card (Quick Mini Calculator Preview) -->
                <div class="lg:col-span-5">
                    <div class="bg-white p-6 sm:p-8 rounded-3xl shadow-2xl border border-gray-100 relative">
                        <div class="absolute -top-3 right-6 bg-brand-gold text-brand-dark text-xs font-extrabold px-3 py-1 rounded-full uppercase tracking-wider shadow">
                            ⚡ Instant Payout
                        </div>
                        <h3 class="text-xl font-bold text-brand-dark mb-4 flex items-center">
                            <i class="fa-solid fa-money-bill-transfer text-brand-green mr-2"></i> Quick Trade Preview
                        </h3>
                        <div class="space-y-4">
                            <div>
                                <label class="block text-xs font-bold text-gray-600 uppercase mb-1">Select Card</label>
                                <select id="heroCardSelect" class="w-full bg-gray-50 border border-gray-200 rounded-xl px-4 py-3 font-semibold text-gray-800 focus:outline-none focus:border-brand-green">
                                    <option value="amazon">Amazon Gift Card</option>
                                    <option value="steam">Steam Wallet Card</option>
                                    <option value="itunes">Apple / iTunes Card</option>
                                    <option value="google">Google Play Card</option>
                                    <option value="razer">Razer Gold PIN</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-600 uppercase mb-1">USD Amount ($)</label>
                                <input type="number" id="heroAmountInput" value="100" min="10" class="w-full bg-gray-50 border border-gray-200 rounded-xl px-4 py-3 font-bold text-gray-800 focus:outline-none focus:border-brand-green">
                            </div>
                            <div class="bg-brand-lightGreen p-4 rounded-2xl border border-brand-green/20">
                                <div class="text-xs font-bold text-brand-darkGreen uppercase">You Will Receive Approx:</div>
                                <div id="heroResultOutput" class="text-2xl font-extrabold text-brand-dark mt-1">₦125,000</div>
                            </div>
                            <a id="heroTradeBtn" href="https://wa.me/2349079154392?text=Hello%20Becky%2C%20I%20have%20a%20%24100%20Amazon%20card.%20How%20much%3F" target="_blank" class="w-full block bg-brand-green hover:bg-brand-darkGreen text-white text-center font-bold py-3.5 rounded-xl shadow-lg shadow-brand-green/20 transition">
                                <i class="fa-brands fa-whatsapp mr-2"></i> Sell This Card Now
                            </a>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Live Rate Calculator Section -->
    <section id="calculator" class="py-20 bg-white border-t border-gray-100">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center space-y-3 mb-12">
                <span class="bg-brand-gold/20 text-brand-dark text-xs font-bold px-3.5 py-1.5 rounded-full uppercase tracking-wider">Live Rate Calculator</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-brand-dark">Check What Your Card Is Worth Right Now</h2>
                <p class="text-gray-600 max-w-lg mx-auto">We offer unbeatable rates updated in real-time according to the market.</p>
            </div>

            <div class="bg-gray-50 border border-gray-200 p-6 sm:p-10 rounded-3xl shadow-xl">
                <div class="grid md:grid-cols-2 gap-6 mb-6">
                    <div>
                        <label class="block text-sm font-bold text-gray-700 mb-2"><i class="fa-solid fa-credit-card text-brand-green mr-1.5"></i> Select Gift Card Brand</label>
                        <select id="calcCardType" class="w-full bg-white border border-gray-300 rounded-2xl px-4 py-3.5 font-bold text-gray-800 focus:outline-none focus:border-brand-green text-base shadow-sm">
                            <option value="amazon">Amazon Gift Card (Physical / E-code)</option>
                            <option value="steam">Steam Wallet Card</option>
                            <option value="itunes">Apple / iTunes Gift Card</option>
                            <option value="google">Google Play Gift Card</option>
                            <option value="razer">Razer Gold Gift Card</option>
                        </select>
                    </div>
                    <div>
                        <label class="block text-sm font-bold text-gray-700 mb-2"><i class="fa-solid fa-dollar-sign text-brand-green mr-1.5"></i> Enter USD ($) Amount</label>
                        <input type="number" id="calcUsdAmount" value="50" min="5" class="w-full bg-white border border-gray-300 rounded-2xl px-4 py-3.5 font-bold text-gray-800 focus:outline-none focus:border-brand-green text-base shadow-sm">
                    </div>
                </div>

                <!-- Result Box -->
                <div class="bg-brand-dark text-white p-6 sm:p-8 rounded-2xl mb-8 flex flex-col sm:flex-row items-center justify-between shadow-lg">
                    <div>
                        <div class="text-xs font-bold text-brand-gold uppercase tracking-wider mb-1">Estimated Payout</div>
                        <div id="calcNairaResult" class="text-4xl sm:text-5xl font-extrabold text-white">₦62,500</div>
                        <div id="calcRateInfo" class="text-xs text-gray-400 mt-1">Rate: $1 = ₦1,250</div>
                    </div>
                    <div class="mt-4 sm:mt-0 text-right">
                        <span class="inline-flex items-center px-3 py-1 rounded-full text-xs font-bold bg-brand-green text-white">
                            <i class="fa-solid fa-circle-check mr-1"></i> Instant Bank / Opay Transfer
                        </span>
                    </div>
                </div>

                <!-- Action Button -->
                <a id="calcWhatsAppBtn" href="https://wa.me/2349079154392?text=Hello%20Becky%2C%20I%20want%20to%20sell%20my%20Amazon%20card%20worth%20%2450%20for%20%E2%82%A662%2C500." target="_blank" class="w-full bg-brand-green hover:bg-brand-darkGreen text-white text-center font-extrabold py-4 rounded-2xl shadow-xl shadow-brand-green/30 flex items-center justify-center space-x-3 text-lg transition transform active:scale-95">
                    <i class="fa-brands fa-whatsapp text-2xl"></i>
                    <span>Proceed to Trade on WhatsApp</span>
                </a>
            </div>
        </div>
    </section>

    <!-- How It Works -->
    <section id="how-it-works" class="py-20 bg-gray-50 border-t border-gray-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center space-y-3 mb-16">
                <span class="bg-brand-green/10 text-brand-green text-xs font-bold px-3.5 py-1.5 rounded-full uppercase tracking-wider">Simple 3-Step Process</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-brand-dark">How To Trade With BECKY CARDSALES</h2>
                <p class="text-gray-600 max-w-lg mx-auto">Get your cash in less than 3 minutes with our secure and straightforward steps.</p>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <!-- Step 1 -->
                <div class="bg-white p-8 rounded-3xl border border-gray-100 shadow-xl relative group hover:border-brand-green transition">
                    <div class="w-14 h-14 bg-brand-lightGreen rounded-2xl flex items-center justify-center text-brand-green font-extrabold text-2xl mb-6 shadow-sm">
                        01
                    </div>
                    <h3 class="text-xl font-bold text-brand-dark mb-3">Select Card & Rate</h3>
                    <p class="text-gray-600 text-sm leading-relaxed">
                        Use our live calculator or chat with us on WhatsApp to check the current exchange rate for your specific gift card type.
                    </p>
                    <div class="absolute top-6 right-6 text-gray-200 group-hover:text-brand-green/20 text-4xl font-black">
                        <i class="fa-solid fa-list-check"></i>
                    </div>
                </div>

                <!-- Step 2 -->
                <div class="bg-white p-8 rounded-3xl border border-gray-100 shadow-xl relative group hover:border-brand-green transition">
                    <div class="w-14 h-14 bg-brand-lightGreen rounded-2xl flex items-center justify-center text-brand-green font-extrabold text-2xl mb-6 shadow-sm">
                        02
                    </div>
                    <h3 class="text-xl font-bold text-brand-dark mb-3">Chat on WhatsApp</h3>
                    <p class="text-gray-600 text-sm leading-relaxed">
                        Click any of our WhatsApp buttons to send your card details or upload clear photos/codes securely to Becky.
                    </p>
                    <div class="absolute top-6 right-6 text-gray-200 group-hover:text-brand-green/20 text-4xl font-black">
                        <i class="fa-brands fa-whatsapp"></i>
                    </div>
                </div>

                <!-- Step 3 -->
                <div class="bg-white p-8 rounded-3xl border border-gray-100 shadow-xl relative group hover:border-brand-green transition">
                    <div class="w-14 h-14 bg-brand-lightGreen rounded-2xl flex items-center justify-center text-brand-green font-extrabold text-2xl mb-6 shadow-sm">
                        03
                    </div>
                    <h3 class="text-xl font-bold text-brand-dark mb-3">Get Instant Naira</h3>
                    <p class="text-gray-600 text-sm leading-relaxed">
                        Once verified within seconds, your Naira payment hits your bank or Opay/PalmPay account instantly. Alert drops!
                    </p>
                    <div class="absolute top-6 right-6 text-gray-200 group-hover:text-brand-green/20 text-4xl font-black">
                        <i class="fa-solid fa-money-bill-wave"></i>
                    </div>
                </div>
            </div>

            <div class="mt-12 text-center">
                <a href="https://wa.me/2349079154392?text=Hello%20Becky%2C%20I%20am%20ready%20to%20trade." target="_blank" class="inline-flex items-center space-x-3 bg-brand-green hover:bg-brand-darkGreen text-white font-extrabold px-8 py-4 rounded-2xl shadow-lg transition">
                    <i class="fa-brands fa-whatsapp text-2xl"></i>
                    <span>Start Trading Now</span>
                </a>
            </div>
        </div>
    </section>

    <!-- Cards We Buy -->
    <section id="cards" class="py-20 bg-white border-t border-gray-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center space-y-3 mb-16">
                <span class="bg-brand-gold/20 text-brand-dark text-xs font-bold px-3.5 py-1.5 rounded-full uppercase tracking-wider">Accepted Gift Cards</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-brand-dark">Cards We Buy at Highest Rates</h2>
                <p class="text-gray-600 max-w-lg mx-auto">We buy physical cards, e-codes, and receipts in any denomination.</p>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-6">
                <!-- Amazon -->
                <div class="bg-gray-50 border border-gray-200 p-6 rounded-3xl text-center hover:shadow-xl hover:border-brand-green transition group">
                    <div class="w-16 h-16 mx-auto bg-amber-100 text-amber-700 rounded-2xl flex items-center justify-center text-3xl mb-4 group-hover:scale-110 transition">
                        <i class="fa-brands fa-amazon"></i>
                    </div>
                    <h3 class="font-bold text-brand-dark text-lg mb-1">Amazon</h3>
                    <p class="text-xs text-gray-500 mb-3">US, UK, DE, CA, AU</p>
                    <a href="https://wa.me/2349079154392?text=Hello%20Becky%2C%20I%20want%20to%20sell%20Amazon%20gift%20card." target="_blank" class="text-xs font-bold text-brand-green hover:underline">Sell Now &rarr;</a>
                </div>

                <!-- Steam -->
                <div class="bg-gray-50 border border-gray-200 p-6 rounded-3xl text-center hover:shadow-xl hover:border-brand-green transition group">
                    <div class="w-16 h-16 mx-auto bg-blue-100 text-blue-800 rounded-2xl flex items-center justify-center text-3xl mb-4 group-hover:scale-110 transition">
                        <i class="fa-brands fa-steam"></i>
                    </div>
                    <h3 class="font-bold text-brand-dark text-lg mb-1">Steam</h3>
                    <p class="text-xs text-gray-500 mb-3">Wallet & Cards</p>
                    <a href="https://wa.me/2349079154392?text=Hello%20Becky%2C%20I%20want%20to%20sell%20Steam%20gift%20card." target="_blank" class="text-xs font-bold text-brand-green hover:underline">Sell Now &rarr;</a>
                </div>

                <!-- Apple / iTunes -->
                <div class="bg-gray-50 border border-gray-200 p-6 rounded-3xl text-center hover:shadow-xl hover:border-brand-green transition group">
                    <div class="w-16 h-16 mx-auto bg-gray-200 text-gray-900 rounded-2xl flex items-center justify-center text-3xl mb-4 group-hover:scale-110 transition">
                        <i class="fa-brands fa-apple"></i>
                    </div>
                    <h3 class="font-bold text-brand-dark text-lg mb-1">Apple / iTunes</h3>
                    <p class="text-xs text-gray-500 mb-3">Physical & E-code</p>
                    <a href="https://wa.me/2349079154392?text=Hello%20Becky%2C%20I%20want%20to%20sell%20Apple%20gift%20card." target="_blank" class="text-xs font-bold text-brand-green hover:underline">Sell Now &rarr;</a>
                </div>

                <!-- Google Play -->
                <div class="bg-gray-50 border border-gray-200 p-6 rounded-3xl text-center hover:shadow-xl hover:border-brand-green transition group">
                    <div class="w-16 h-16 mx-auto bg-emerald-100 text-emerald-700 rounded-2xl flex items-center justify-center text-3xl mb-4 group-hover:scale-110 transition">
                        <i class="fa-brands fa-google-play"></i>
                    </div>
                    <h3 class="font-bold text-brand-dark text-lg mb-1">Google Play</h3>
                    <p class="text-xs text-gray-500 mb-3">US, UK, EUR</p>
                    <a href="https://wa.me/2349079154392?text=Hello%20Becky%2C%20I%20want%20to%20sell%20Google%20Play%20gift%20card." target="_blank" class="text-xs font-bold text-brand-green hover:underline">Sell Now &rarr;</a>
                </div>

                <!-- Razer Gold -->
                <div class="bg-gray-50 border border-gray-200 p-6 rounded-3xl text-center hover:shadow-xl hover:border-brand-green transition group col-span-2 sm:col-span-1">
                    <div class="w-16 h-16 mx-auto bg-green-100 text-brand-green rounded-2xl flex items-center justify-center text-3xl mb-4 group-hover:scale-110 transition">
                        <i class="fa-solid fa-gamepad"></i>
                    </div>
                    <h3 class="font-bold text-brand-dark text-lg mb-1">Razer Gold</h3>
                    <p class="text-xs text-gray-500 mb-3">PINs & Cards</p>
                    <a href="https://wa.me/2349079154392?text=Hello%20Becky%2C%20I%20want%20to%20sell%20Razer%20Gold%20gift%20card." target="_blank" class="text-xs font-bold text-brand-green hover:underline">Sell Now &rarr;</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Why Choose Us -->
    <section id="why-us" class="py-20 bg-brand-dark text-white relative overflow-hidden">
        <div class="absolute top-0 right-0 w-96 h-96 bg-brand-green/10 rounded-full blur-3xl pointer-events-none"></div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="text-center space-y-3 mb-16">
                <span class="bg-brand-green text-white text-xs font-bold px-3.5 py-1.5 rounded-full uppercase tracking-wider">The BECKY Guarantee</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-white">Why Choose BECKY CARDSALES?</h2>
                <p class="text-gray-400 max-w-lg mx-auto">We prioritize your safety, speed, and satisfaction above everything else.</p>
            </div>

            <div class="grid md:grid-cols-4 gap-8">
                <!-- Feature 1 -->
                <div class="bg-gray-900/80 border border-gray-800 p-8 rounded-3xl">
                    <div class="w-12 h-12 bg-brand-green/20 text-brand-green rounded-2xl flex items-center justify-center text-xl mb-6">
                        <i class="fa-solid fa-shield-check"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">100% Trusted</h3>
                    <p class="text-gray-400 text-sm leading-relaxed">
                        Thousands of successful trades with zero scam history. Your card and funds are fully secure with us.
                    </p>
                </div>

                <!-- Feature 2 -->
                <div class="bg-gray-900/80 border border-gray-800 p-8 rounded-3xl">
                    <div class="w-12 h-12 bg-brand-gold/20 text-brand-gold rounded-2xl flex items-center justify-center text-xl mb-6">
                        <i class="fa-solid fa-bolt"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Best Rates</h3>
                    <p class="text-gray-400 text-sm leading-relaxed">
                        We give the highest payout rates in the Nigerian market so you get maximum value for your cards.
                    </p>
                </div>

                <!-- Feature 3 -->
                <div class="bg-gray-900/80 border border-gray-800 p-8 rounded-3xl">
                    <div class="w-12 h-12 bg-blue-500/20 text-blue-400 rounded-2xl flex items-center justify-center text-xl mb-6">
                        <i class="fa-solid fa-money-bill-transfer"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Instant Payment</h3>
                    <p class="text-gray-400 text-sm leading-relaxed">
                        Bank alerts drop within minutes of card verification. We support all Nigerian commercial banks and fintechs.
                    </p>
                </div>

                <!-- Feature 4 -->
                <div class="bg-gray-900/80 border border-gray-800 p-8 rounded-3xl">
                    <div class="w-12 h-12 bg-red-500/20 text-red-400 rounded-2xl flex items-center justify-center text-xl mb-6">
                        <i class="fa-solid fa-ban"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Zero Scam Policy</h3>
                    <p
