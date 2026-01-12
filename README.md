<html lang="en"><head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UMWTV New Year Growth Fund Promotion</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome -->
    <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
    <!-- GSAP for animations -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>
    <!-- AOS for scroll animations -->
    <link href="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/aos@2.3.4/dist/aos.js"></script>
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#0052cc',
                        secondary: '#0747a6',
                        accent: '#ffc107',
                        gold: '#d4af37',
                        darkBlue: '#001f4d',
                        lightBlue: '#e6f0ff'
                    },
                    fontFamily: {
                        sans: ['Inter', 'system-ui', 'sans-serif'],
                    },
                    boxShadow: {
                        'gold': '0 4px 20px rgba(212, 175, 55, 0.3)',
                        'blue': '0 4px 20px rgba(0, 82, 204, 0.2)',
                    }
                }
            }
        }
    </script>
    <style type="text/tailwindcss">
        @layer utilities {
            .text-shadow {
                text-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            }
            .text-shadow-lg {
                text-shadow: 0 4px 8px rgba(0, 0, 0, 0.12), 0 2px 4px rgba(0, 0, 0, 0.08);
            }
            .bg-gradient-gold {
                background: linear-gradient(135deg, #d4af37 0%, #f2d272 50%, #d4af37 100%);
            }
            .bg-gradient-blue {
                background: linear-gradient(135deg, #0052cc 0%, #0747a6 100%);
            }
            .animate-pulse-slow {
                animation: pulse 3s cubic-bezier(0.4, 0, 0.6, 1) infinite;
            }
            .card-hover {
                transition: all 0.3s ease;
            }
            .card-hover:hover {
                transform: translateY(-5px);
            }
        }
    </style>
</head>
<body class="bg-gray-50 font-sans">
    <!-- Hero Section with Countdown -->
    <header class="relative overflow-hidden">
        <!-- Background Image -->
        <div class="absolute inset-0 z-0">
            <img src="https://p3-flow-imagex-sign.byteimg.com/tos-cn-i-a9rns2rl98/rc/pc/super_tool/f60835f0490949e8a568312e72f121f0~tplv-a9rns2rl98-image.image?lk3s=8e244e95&amp;rcl=20260112155454F19D2B22513F0AA1271B&amp;rrcfp=f06b921b&amp;x-expires=1770796512&amp;x-signature=FNILLyFSfL8FdVrRtcOa4wZcdpM%3D" alt="New Year Celebration" class="w-full h-full object-cover opacity-90">
            <div class="absolute inset-0 bg-gradient-to-r from-primary/80 to-secondary/70"></div>
        </div>

        <!-- Content -->
        <div class="relative z-10 container mx-auto px-4 py-16 md:py-24">
            <div class="max-w-3xl">
                <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold text-white mb-4 text-shadow-lg" data-aos="fade-right">
                    UMWTV New Year <span class="text-gold">Growth Fund</span> Promotion
                </h1>
                <p class="text-xl md:text-2xl text-white/90 mb-8 text-shadow" data-aos="fade-right" data-aos-delay="100">
                    Celebrating 1 Year in South Africa - Exclusive 10-day Fixed Deposit Offer
                </p>
                
                <!-- Countdown Timer -->
                <div class="bg-white/10 backdrop-blur-md rounded-xl p-6 mb-8 shadow-blue" data-aos="fade-up" data-aos-delay="200">
                    <h3 class="text-xl text-white font-semibold mb-4 text-center">Limited Time Offer - Ends In:</h3>
                    <div id="countdown" class="grid grid-cols-4 gap-4 md:gap-6">
                        <div class="bg-white/20 rounded-lg p-4 text-center">
                            <span id="days" class="block text-3xl md:text-4xl font-bold text-gold">00</span>
                            <span class="text-white/80 text-sm uppercase">Days</span>
                        </div>
                        <div class="bg-white/20 rounded-lg p-4 text-center">
                            <span id="hours" class="block text-3xl md:text-4xl font-bold text-gold">00</span>
                            <span class="text-white/80 text-sm uppercase">Hours</span>
                        </div>
                        <div class="bg-white/20 rounded-lg p-4 text-center">
                            <span id="minutes" class="block text-3xl md:text-4xl font-bold text-gold">00</span>
                            <span class="text-white/80 text-sm uppercase">Minutes</span>
                        </div>
                        <div class="bg-white/20 rounded-lg p-4 text-center">
                            <span id="seconds" class="block text-3xl md:text-4xl font-bold text-gold">00</span>
                            <span class="text-white/80 text-sm uppercase">Seconds</span>
                        </div>
                    </div>
                </div>
                
                <div class="flex flex-wrap gap-4" data-aos="fade-up" data-aos-delay="300">
                    <a href="#details" class="bg-gold hover:bg-gold/90 text-darkBlue font-bold py-3 px-8 rounded-full shadow-gold transition-all">
                        Learn More
                    </a>
                    <a href="#calculator" class="bg-white/20 hover:bg-white/30 text-white font-bold py-3 px-8 rounded-full backdrop-blur-sm transition-all">
                        Calculate Returns
                    </a>
                </div>
            </div>
        </div>
    </header>

    <!-- Main Content -->
    <main class="container mx-auto px-4 py-12">
        <!-- Introduction Section -->
        <section id="details" class="max-w-4xl mx-auto mb-16">
            <div class="bg-white rounded-2xl shadow-xl overflow-hidden" data-aos="fade-up">
                <div class="p-8 md:p-12">
                    <h2 class="text-3xl font-bold text-primary mb-6">About UMWTV Growth Fund</h2>
                    <p class="text-lg text-gray-700 mb-6">
                        Since our launch in South Africa in 2025, UMWTV APP has been committed to providing exceptional service to our users. As we celebrate our first anniversary and welcome the New Year 2026, we're excited to announce our special "Growth Fund" promotion.
                    </p>
                    <p class="text-lg text-gray-700 mb-8">
                        With a remaining "Growth Fund" of 307 million ZAR, we're offering our valued users an exclusive opportunity to participate in our 10-day fixed deposit program with an impressive daily interest rate of 19.89%.
                    </p>
                    
                    <div class="bg-lightBlue rounded-xl p-6 mb-8">
                        <h3 class="text-xl font-semibold text-primary mb-4 flex items-center">
                            <i class="fa fa-info-circle mr-2 text-gold"></i>
                            Promotion Details
                        </h3>
                        <ul class="space-y-3 text-gray-700">
                            <li class="flex items-start">
                                <i class="fa fa-check-circle text-gold mt-1 mr-3"></i>
                                <span>Promotion Period: January 12 - 15, 2026</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fa fa-check-circle text-gold mt-1 mr-3"></i>
                                <span>Product: UMWTV "Growth Fund" Welfare Fund</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fa fa-check-circle text-gold mt-1 mr-3"></i>
                                <span>Term: 10-day fixed deposit</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fa fa-check-circle text-gold mt-1 mr-3"></i>
                                <span>Daily Interest Rate: 19.89%</span>
                            </li>
                            <li class="flex items-start">
                                <i class="fa fa-check-circle text-gold mt-1 mr-3"></i>
                                <span>Total Fund Allocation: 307 million ZAR</span>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>

        <!-- Benefits Section -->
        <section class="max-w-5xl mx-auto mb-16">
            <h2 class="text-3xl font-bold text-primary text-center mb-12">Exclusive Benefits</h2>
            
            <div class="grid md:grid-cols-2 gap-8">
                <!-- Left Column - Visual -->
                <div class="flex justify-center items-center" data-aos="fade-right">
                    <img src="https://p3-flow-imagex-sign.byteimg.com/tos-cn-i-a9rns2rl98/rc/pc/super_tool/04a6e9e614634cb48d593f0a2da877a9~tplv-a9rns2rl98-image.image?lk3s=8e244e95&amp;rcl=20260112155454F19D2B22513F0AA1271B&amp;rrcfp=f06b921b&amp;x-expires=1770796526&amp;x-signature=T9t11MFTH%2FWnQD%2BIlFhAal5QEU8%3D" alt="Growth Fund" class="w-full max-w-md rounded-2xl shadow-xl transform hover:scale-105 transition-transform duration-300">
                </div>
                
                <!-- Right Column - Benefits -->
                <div>
                    <div class="space-y-6">
                        <div class="bg-white p-6 rounded-xl shadow-blue card-hover" data-aos="fade-up">
                            <div class="flex items-start">
                                <div class="bg-gold/20 p-3 rounded-full mr-4">
                                    <i class="fa fa-money text-2xl text-gold"></i>
                                </div>
                                <div>
                                    <h3 class="text-xl font-semibold text-primary mb-2">Instant Cashback</h3>
                                    <p class="text-gray-700">Recharge your account and get 100% of your deposit amount instantly credited back to your working account balance.</p>
                                </div>
                            </div>
                        </div>
                        
                        <div class="bg-white p-6 rounded-xl shadow-blue card-hover" data-aos="fade-up" data-aos-delay="100">
                            <div class="flex items-start">
                                <div class="bg-gold/20 p-3 rounded-full mr-4">
                                    <i class="fa fa-line-chart text-2xl text-gold"></i>
                                </div>
                                <div>
                                    <h3 class="text-xl font-semibold text-primary mb-2">High Daily Returns</h3>
                                    <p class="text-gray-700">Earn an impressive 19.89% daily interest rate on your 10-day fixed deposit, compounding your growth.</p>
                                </div>
                            </div>
                        </div>
                        
                        <div class="bg-white p-6 rounded-xl shadow-blue card-hover" data-aos="fade-up" data-aos-delay="200">
                            <div class="flex items-start">
                                <div class="bg-gold/20 p-3 rounded-full mr-4">
                                    <i class="fa fa-shield text-2xl text-gold"></i>
                                </div>
                                <div>
                                    <h3 class="text-xl font-semibold text-primary mb-2">Secure Investment</h3>
                                    <p class="text-gray-700">Backed by UMWTV's established presence and remaining 307 million ZAR Growth Fund, ensuring reliability.</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Examples Section -->
        <section class="max-w-5xl mx-auto mb-16">
            <h2 class="text-3xl font-bold text-primary text-center mb-12">Investment Examples</h2>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Example 1 -->
                <div class="bg-white rounded-xl shadow-blue overflow-hidden card-hover" data-aos="fade-up">
                    <div class="bg-primary p-4">
                        <h3 class="text-xl font-semibold text-white">welfare fund 1
</h3>
                    </div>
                    <div class="p-6">
                        <div class="text-center mb-6">
                            <span class="text-4xl font-bold text-primary">1,000</span>
                            <span class="text-xl text-gray-600"> ZAR</span>
                        </div>
                        <ul class="space-y-3 mb-6">
                            <li class="flex justify-between">
                                <span class="text-gray-700">Deposit Amount:</span>
                                <span class="font-semibold">1,000 ZAR</span>
                            </li>
                            <li class="flex justify-between">
                                <span class="text-gray-700">Instant Cashback:</span>
                                <span class="font-semibold text-gold">1,000 ZAR</span>
                            </li>
                            <li class="flex justify-between">
                                <span class="text-gray-700">Daily Interest:</span>
                                <span class="font-semibold">198.90 ZAR</span>
                            </li>
                            <li class="flex justify-between">
                                <span class="text-gray-700">10-Day Return:</span>
                                <span class="font-semibold text-primary">1,989 ZAR</span>
                            </li>
                            <li class="flex justify-between border-t pt-3 mt-3">
                                <span class="font-semibold text-gray-800">Total Benefit:</span>
                                <span class="font-bold text-gold">2,989 ZAR</span>
                            </li>
                        </ul>
                        <a href="https://umw-tv.com/xml/index.html#/login" class="w-full bg-primary hover:bg-primary/90 text-white font-bold py-3 rounded-lg transition-colors text-center block">
                            Invest Now
                        </a>
                    </div>
                </div>
                
                <!-- Example 2 -->
                <div class="bg-white rounded-xl shadow-blue overflow-hidden card-hover" data-aos="fade-up" data-aos-delay="100">
                    <div class="bg-primary p-4">
                        <h3 class="text-xl font-semibold text-white">welfare fund 2
</h3>
                    </div>
                    <div class="p-6">
                        <div class="text-center mb-6">
                            <span class="text-4xl font-bold text-primary">2,000</span>
                            <span class="text-xl text-gray-600"> ZAR</span>
                        </div>
                        <ul class="space-y-3 mb-6">
                            <li class="flex justify-between">
                                <span class="text-gray-700">Deposit Amount:</span>
                                <span class="font-semibold">2,000 ZAR</span>
                            </li>
                            <li class="flex justify-between">
                                <span class="text-gray-700">Instant Cashback:</span>
                                <span class="font-semibold text-gold">2,000 ZAR</span>
                            </li>
                            <li class="flex justify-between">
                                <span class="text-gray-700">Daily Interest:</span>
                                <span class="font-semibold">397.80 ZAR</span>
                            </li>
                            <li class="flex justify-between">
                                <span class="text-gray-700">10-Day Return:</span>
                                <span class="font-semibold text-primary">3,978 ZAR</span>
                            </li>
                            <li class="flex justify-between border-t pt-3 mt-3">
                                <span class="font-semibold text-gray-800">Total Benefit:</span>
                                <span class="font-bold text-gold">5,978 ZAR</span>
                            </li>
                        </ul>
                        <a href="https://umw-tv.com/xml/index.html#/login" class="w-full bg-primary hover:bg-primary/90 text-white font-bold py-3 rounded-lg transition-colors text-center block">
                            Invest Now
                        </a>
                    </div>
                </div>
                
                <!-- Example 3 -->
                <div class="bg-white rounded-xl shadow-blue overflow-hidden card-hover" data-aos="fade-up" data-aos-delay="200">
                    <div class="bg-primary p-4">
                        <h3 class="text-xl font-semibold text-white">welfare fund 3
</h3>
                    </div>
                    <div class="p-6">
                        <div class="text-center mb-6">
                            <span class="text-4xl font-bold text-primary">5,000</span>
                            <span class="text-xl text-gray-600"> ZAR</span>
                        </div>
                        <ul class="space-y-3 mb-6">
                            <li class="flex justify-between">
                                <span class="text-gray-700">Deposit Amount:</span>
                                <span class="font-semibold">5,000 ZAR</span>
                            </li>
                            <li class="flex justify-between">
                                <span class="text-gray-700">Instant Cashback:</span>
                                <span class="font-semibold text-gold">5,000 ZAR</span>
                            </li>
                            <li class="flex justify-between">
                                <span class="text-gray-700">Daily Interest:</span>
                                <span class="font-semibold">994.50 ZAR</span>
                            </li>
                            <li class="flex justify-between">
                                <span class="text-gray-700">10-Day Return:</span>
                                <span class="font-semibold text-primary">9,945 ZAR</span>
                            </li>
                            <li class="flex justify-between border-t pt-3 mt-3">
                                <span class="font-semibold text-gray-800">Total Benefit:</span>
                                <span class="font-bold text-gold">14,945 ZAR</span>
                            </li>
                        </ul>
                        <a href="https://umw-tv.com/xml/index.html#/login" class="w-full bg-primary hover:bg-primary/90 text-white font-bold py-3 rounded-lg transition-colors text-center block">
                            Invest Now
                        </a>
                    </div>
                </div>
                
                <!-- Example 4 -->
                <div class="bg-white rounded-xl shadow-blue overflow-hidden card-hover transform md:scale-105 z-10" data-aos="fade-up" data-aos-delay="300">
                    <div class="bg-gold p-4">
                        <h3 class="text-xl font-semibold text-darkBlue">welfare fund 4 (Most Popular)
</h3>
                    </div>
                    <div class="p-6">
                        <div class="text-center mb-6">
                            <span class="text-4xl font-bold text-primary">10,000</span>
                            <span class="text-xl text-gray-600"> ZAR</span>
                        </div>
                        <ul class="space-y-3 mb-6">
                            <li class="flex justify-between">
                                <span class="text-gray-700">Deposit Amount:</span>
                                <span class="font-semibold">10,000 ZAR</span>
                            </li>
                            <li class="flex justify-between">
                                <span class="text-gray-700">Instant Cashback:</span>
                                <span class="font-semibold text-gold">10,000 ZAR</span>
                            </li>
                            <li class="flex justify-between">
                                <span class="text-gray-700">Daily Interest:</span>
                                <span class="font-semibold">1,989 ZAR</span>
                            </li>
                            <li class="flex justify-between">
                                <span class="text-gray-700">10-Day Return:</span>
                                <span class="font-semibold text-primary">19,890 ZAR</span>
                            </li>
                            <li class="flex justify-between border-t pt-3 mt-3">
                                <span class="font-semibold text-gray-800">Total Benefit:</span>
                                <span class="font-bold text-gold">29,890 ZAR</span>
                            </li>
                        </ul>
                        <a href="https://umw-tv.com/xml/index.html#/login" class="w-full bg-gold hover:bg-gold/90 text-darkBlue font-bold py-3 rounded-lg transition-colors text-center block">
                            Invest Now
                        </a>
                    </div>
                </div>
                
                <!-- Example 3 -->
                <div class="bg-white rounded-xl shadow-blue overflow-hidden card-hover" data-aos="fade-up" data-aos-delay="200">
                    <div class="bg-primary p-4">
                        <h3 class="text-xl font-semibold text-white">welfare fund 5 (More user recommendations)
</h3>
                    </div>
                    <div class="p-6">
                        <div class="text-center mb-6">
                            <span class="text-4xl font-bold text-primary">50,000</span>
                            <span class="text-xl text-gray-600"> ZAR</span>
                        </div>
                        <ul class="space-y-3 mb-6">
                            <li class="flex justify-between">
                                <span class="text-gray-700">Deposit Amount:</span>
                                <span class="font-semibold">50,000 ZAR</span>
                            </li>
                            <li class="flex justify-between">
                                <span class="text-gray-700">Instant Cashback:</span>
                                <span class="font-semibold text-gold">50,000 ZAR</span>
                            </li>
                            <li class="flex justify-between">
                                <span class="text-gray-700">Daily Interest:</span>
                                <span class="font-semibold">9,945 ZAR</span>
                            </li>
                            <li class="flex justify-between">
                                <span class="text-gray-700">10-Day Return:</span>
                                <span class="font-semibold text-primary">99,450 ZAR</span>
                            </li>
                            <li class="flex justify-between border-t pt-3 mt-3">
                                <span class="font-semibold text-gray-800">Total Benefit:</span>
                                <span class="font-bold text-gold">149,450 ZAR</span>
                            </li>
                        </ul>
                        <a href="https://umw-tv.com/xml/index.html#/login" class="w-full bg-primary hover:bg-primary/90 text-white font-bold py-3 rounded-lg transition-colors text-center block">
                            Invest Now
                        </a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Calculator Section -->
        <section id="calculator" class="max-w-4xl mx-auto mb-16">
            <div class="bg-white rounded-2xl shadow-xl overflow-hidden" data-aos="fade-up">
                <div class="bg-gradient-blue p-8">
                    <h2 class="text-3xl font-bold text-white text-center">Return Calculator</h2>
                    <p class="text-white/80 text-center mt-2">Calculate your potential earnings with our Growth Fund</p>
                </div>
                
                <div class="p-8">
                    <div class="mb-6">
                        <label for="investmentAmount" class="block text-gray-700 font-semibold mb-2">Investment Amount (ZAR)</label>
                        <input type="range" id="investmentAmount" min="1000" max="100000" step="1000" value="10000" class="w-full h-3 bg-gray-200 rounded-lg appearance-none cursor-pointer">
                        <div class="flex justify-between mt-2 text-sm text-gray-600">
                            <span>1,000 ZAR</span>
                            <span id="amountDisplay">10,000 ZAR</span>
                            <span>100,000 ZAR</span>
                        </div>
                    </div>
                    
                    <div class="grid md:grid-cols-3 gap-6 mb-8">
                        <div class="bg-lightBlue rounded-xl p-6 text-center">
                            <h3 class="text-gray-700 font-semibold mb-2">Instant Cashback</h3>
                            <p id="cashbackResult" class="text-3xl font-bold text-gold">10,000 ZAR</p>
                        </div>
                        <div class="bg-lightBlue rounded-xl p-6 text-center">
                            <h3 class="text-gray-700 font-semibold mb-2">10-Day Interest</h3>
                            <p id="interestResult" class="text-3xl font-bold text-primary">19,890 ZAR</p>
                        </div>
                        <div class="bg-lightBlue rounded-xl p-6 text-center">
                            <h3 class="text-gray-700 font-semibold mb-2">Total Benefit</h3>
                            <p id="totalResult" class="text-3xl font-bold text-darkBlue">29,890 ZAR</p>
                        </div>
                    </div>
                    
                    <div class="text-center">
                        <button id="calculateBtn" class="bg-primary hover:bg-primary/90 text-white font-bold py-3 px-8 rounded-lg transition-colors">
                            Calculate Returns
                        </button>
                    </div>
                </div>
            </div>
        </section>

        <!-- FAQ Section -->
        <section class="max-w-4xl mx-auto mb-16">
            <h2 class="text-3xl font-bold text-primary text-center mb-12">Frequently Asked Questions</h2>
            
            <div class="space-y-4">
                <div class="bg-white rounded-xl shadow-md overflow-hidden" data-aos="fade-up">
                    <button class="faq-toggle w-full text-left p-6 focus:outline-none">
                        <div class="flex justify-between items-center">
                            <h3 class="text-xl font-semibold text-primary">How does the instant cashback work?</h3>
                            <i class="fa fa-plus text-gold transition-transform duration-300"></i>
                        </div>
                    </button>
                    <div class="faq-content hidden px-6 pb-6">
                        <p class="text-gray-700">
                            When you invest in the UMWTV Growth Fund, 100% of your deposit amount is immediately credited back to your working account balance. For example, if you deposit 10,000 ZAR, you'll instantly receive 10,000 ZAR in your working account while your original deposit earns daily interest at 19.89%.
                        </p>
                    </div>
                </div>
                
                <div class="bg-white rounded-xl shadow-md overflow-hidden" data-aos="fade-up" data-aos-delay="100">
                    <button class="faq-toggle w-full text-left p-6 focus:outline-none">
                        <div class="flex justify-between items-center">
                            <h3 class="text-xl font-semibold text-primary">What is the duration of the fixed deposit?</h3>
                            <i class="fa fa-plus text-gold transition-transform duration-300"></i>
                        </div>
                    </button>
                    <div class="faq-content hidden px-6 pb-6">
                        <p class="text-gray-700">
                            The UMWTV Growth Fund is a 10-day fixed deposit product. Your investment will mature after 10 days, at which point your original deposit plus all accumulated interest will be available for withdrawal or reinvestment.
                        </p>
                    </div>
                </div>
                
                <div class="bg-white rounded-xl shadow-md overflow-hidden" data-aos="fade-up" data-aos-delay="200">
                    <button class="faq-toggle w-full text-left p-6 focus:outline-none">
                        <div class="flex justify-between items-center">
                            <h3 class="text-xl font-semibold text-primary">Is there a minimum or maximum investment amount?</h3>
                            <i class="fa fa-plus text-gold transition-transform duration-300"></i>
                        </div>
                    </button>
                    <div class="faq-content hidden px-6 pb-6">
                        <p class="text-gray-700">
                            The minimum investment amount is 1,000 ZAR, and the maximum is 100,000 ZAR per user. This promotion is available while the 307 million ZAR Growth Fund allocation lasts.
                        </p>
                    </div>
                </div>
                
                <div class="bg-white rounded-xl shadow-md overflow-hidden" data-aos="fade-up" data-aos-delay="300">
                    <button class="faq-toggle w-full text-left p-6 focus:outline-none">
                        <div class="flex justify-between items-center">
                            <h3 class="text-xl font-semibold text-primary">How is the daily interest calculated?</h3>
                            <i class="fa fa-plus text-gold transition-transform duration-300"></i>
                        </div>
                    </button>
                    <div class="faq-content hidden px-6 pb-6">
                        <p class="text-gray-700">
                            The daily interest is calculated at a rate of 19.89% of your deposit amount. For example, a 10,000 ZAR deposit earns 1,989 ZAR in interest per day, totaling 19,890 ZAR over the 10-day period. Interest is calculated daily but paid at the end of the term.
                        </p>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-darkBlue text-white">
        <div class="container mx-auto px-4 py-12">
            <div class="max-w-5xl mx-auto">
                <div class="grid md:grid-cols-2 gap-8 items-center">
                    <div>
                        <h2 class="text-2xl font-bold mb-4">UMWTV Growth Fund</h2>
                        <p class="text-white/80 mb-6">
                            Celebrating 1 year of operation in South Africa. Thank you for your continued support and trust.
                        </p>
                        <p class="text-white/60 text-sm">
                            Promotion Period: January 12 - 15, 2026<br>
                            Total Fund Allocation: 307 million ZAR
                        </p>
                    </div>
                    
                    <div class="text-center md:text-right">
                        <div class="inline-block bg-white/10 backdrop-blur-sm rounded-full p-4 mb-4">
                            <i class="fa fa-calendar-check-o text-4xl text-gold"></i>
                        </div>
                        <h3 class="text-xl font-semibold mb-2">Limited Time Offer</h3>
                        <p class="text-white/80">
                            Don't miss this exclusive opportunity to grow your investment with UMWTV's Growth Fund.
                        </p>
                    </div>
                </div>
                
                <div class="border-t border-white/20 mt-8 pt-8 text-center text-white/60 text-sm">
                    <p>© 2026 UMWTV. All rights reserved. This promotion is available for a limited time only.</p>
                </div>
            </div>
        </div>
    </footer>

    <!-- Success Modal -->
    <div id="successModal" class="fixed inset-0 z-50 hidden">
        <div class="absolute inset-0 bg-black/50 backdrop-blur-sm"></div>
        <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 bg-white rounded-2xl p-8 max-w-md w-full mx-4">
            <div class="text-center">
                <div class="inline-flex items-center justify-center w-16 h-16 rounded-full bg-green-100 mb-6">
                    <i class="fa fa-check text-3xl text-green-500"></i>
                </div>
                <h3 class="text-2xl font-bold text-primary mb-4">Investment Successful!</h3>
                <p class="text-gray-700 mb-6">
                    Your investment of <span id="modalAmount" class="font-bold">10,000 ZAR</span> has been processed successfully.
                </p>
                <p class="text-gray-700 mb-6">
                    <span class="font-semibold">Instant Cashback:</span> <span id="modalCashback" class="text-gold font-bold">10,000 ZAR</span><br>
                    <span class="font-semibold">Expected 10-Day Return:</span> <span id="modalReturn" class="text-primary font-bold">19,890 ZAR</span>
                </p>
                <button id="closeModal" class="bg-primary hover:bg-primary/90 text-white font-bold py-3 px-8 rounded-lg transition-colors">
                    Close
                </button>
            </div>
        </div>
    </div>

    <script>
        // Initialize AOS animation library
        document.addEventListener('DOMContentLoaded', function() {
            AOS.init({
                duration: 800,
                easing: 'ease-in-out',
                once: true
            });
            
            // Initialize countdown
            initializeCountdown();
            
            // Initialize calculator
            initializeCalculator();
            
            // Initialize FAQ toggles
            initializeFAQ();
            
            // Initialize investment buttons
            initializeInvestmentButtons();
            
            // Initialize modal
            initializeModal();
        });

        // Countdown Timer
        function initializeCountdown() {
            const endDate = new Date('2026-01-15T23:59:59').getTime();
            
            function updateCountdown() {
                const now = new Date().getTime();
                const distance = endDate - now;
                
                const days = Math.floor(distance / (1000 * 60 * 60 * 24));
                const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
                const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
                const seconds = Math.floor((distance % (1000 * 60)) / 1000);
                
                document.getElementById('days').innerText = days.toString().padStart(2, '0');
                document.getElementById('hours').innerText = hours.toString().padStart(2, '0');
                document.getElementById('minutes').innerText = minutes.toString().padStart(2, '0');
                document.getElementById('seconds').innerText = seconds.toString().padStart(2, '0');
                
                if (distance < 0) {
                    clearInterval(countdownInterval);
                    document.getElementById('countdown').innerHTML = `
                        <div class="col-span-4 bg-red-100 rounded-lg p-4 text-center">
                            <span class="block text-2xl font-bold text-red-600">Promotion Ended</span>
                            <span class="text-red-600">Thank you for your participation</span>
                        </div>
                    `;
                }
            }
            
            updateCountdown();
            const countdownInterval = setInterval(updateCountdown, 1000);
        }

        // Investment Calculator
        function initializeCalculator() {
            const amountSlider = document.getElementById('investmentAmount');
            const amountDisplay = document.getElementById('amountDisplay');
            const cashbackResult = document.getElementById('cashbackResult');
            const interestResult = document.getElementById('interestResult');
            const totalResult = document.getElementById('totalResult');
            const calculateBtn = document.getElementById('calculateBtn');
            
            function updateResults() {
                const amount = parseInt(amountSlider.value);
                amountDisplay.innerText = amount.toLocaleString() + ' ZAR';
                
                const cashback = amount;
                const dailyInterest = amount * 0.1989;
                const totalInterest = dailyInterest * 10;
                const totalBenefit = cashback + totalInterest;
                
                cashbackResult.innerText = cashback.toLocaleString() + ' ZAR';
                interestResult.innerText = totalInterest.toLocaleString() + ' ZAR';
                totalResult.innerText = totalBenefit.toLocaleString() + ' ZAR';
            }
            
            amountSlider.addEventListener('input', updateResults);
            
            calculateBtn.addEventListener('click', function() {
                // Add animation effect
                [cashbackResult, interestResult, totalResult].forEach(element => {
                    element.classList.add('scale-110', 'text-gold');
                    setTimeout(() => {
                        element.classList.remove('scale-110', 'text-gold');
                    }, 300);
                });
            });
            
            // Initial update
            updateResults();
        }

        // FAQ Toggles
        function initializeFAQ() {
            const faqToggles = document.querySelectorAll('.faq-toggle');
            
            faqToggles.forEach(toggle => {
                toggle.addEventListener('click', function() {
                    const content = this.nextElementSibling;
                    const icon = this.querySelector('i');
                    
                    content.classList.toggle('hidden');
                    icon.classList.toggle('fa-plus');
                    icon.classList.toggle('fa-minus');
                    icon.classList.toggle('rotate-45');
                });
            });
        }

        // Investment Buttons
        function initializeInvestmentButtons() {
            const investButtons = document.querySelectorAll('.invest-btn');
            
            investButtons.forEach(button => {
                button.addEventListener('click', function() {
                    const amount = this.getAttribute('data-amount');
                    showSuccessModal(amount);
                });
            });
        }

        // Success Modal
        function initializeModal() {
            const modal = document.getElementById('successModal');
            const closeModal = document.getElementById('closeModal');
            
            closeModal.addEventListener('click', function() {
                modal.classList.add('hidden');
                document.body.style.overflow = 'auto';
            });
            
            modal.addEventListener('click', function(e) {
                if (e.target === modal) {
                    modal.classList.add('hidden');
                    document.body.style.overflow = 'auto';
                }
            });
        }

        function showSuccessModal(amount) {
            const modal = document.getElementById('successModal');
            const modalAmount = document.getElementById('modalAmount');
            const modalCashback = document.getElementById('modalCashback');
            const modalReturn = document.getElementById('modalReturn');
            
            const amountNum = parseInt(amount);
            modalAmount.innerText = amountNum.toLocaleString() + ' ZAR';
            modalCashback.innerText = amountNum.toLocaleString() + ' ZAR';
            
            const totalInterest = amountNum * 0.1989 * 10;
            modalReturn.innerText = totalInterest.toLocaleString() + ' ZAR';
            
            modal.classList.remove('hidden');
            document.body.style.overflow = 'hidden';
            
            // Add animation
            const modalContent = modal.querySelector('.bg-white');
            modalContent.classList.add('scale-95', 'opacity-0');
            setTimeout(() => {
                modalContent.classList.remove('scale-95', 'opacity-0');
            }, 10);
        }

        // Add scroll animations
        window.addEventListener('scroll', function() {
            const header = document.querySelector('header');
            const scrolled = window.pageYOffset;
            
            if (scrolled > 100) {
                header.classList.add('bg-primary/90', 'backdrop-blur-md');
            } else {
                header.classList.remove('bg-primary/90', 'backdrop-blur-md');
            }
        });
    </script>

</body></html>
