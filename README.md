<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ManuscriptPro | Professional Book Formatting in 72 Hours</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700;900&family=Playfair+Display:ital,wght@0,700;1,700&display=swap" rel="stylesheet">
    <style>
        body { 
            font-family: 'Inter', sans-serif; 
            scroll-behavior: smooth;
            background-color: #ffffff;
        }
        .serif { font-family: 'Playfair Display', serif; }
        
        /* BRAND STANDARD: BOLD SKETCHING & LABELING */
        .sketch-border {
            border: 3px solid #1e1b4b;
            box-shadow: 8px 8px 0px #6366f1;
        }
        .sketch-card-dark {
            border: 3px solid #1e1b4b;
            box-shadow: 8px 8px 0px #1e1b4b;
        }
        .btn-brand {
            border: 3px solid #1e1b4b;
            box-shadow: 4px 4px 0px #1e1b4b;
            transition: all 0.1s ease;
        }
        .btn-brand:active {
            transform: translate(2px, 2px);
            box-shadow: 0px 0px 0px #1e1b4b;
        }
        .label-bold {
            display: inline-block;
            padding: 2px 8px;
            background: #1e1b4b;
            color: white;
            font-size: 0.65rem;
            font-weight: 900;
            text-transform: uppercase;
            letter-spacing: 0.1em;
        }
        footer {
            border-top: 4px solid #1e1b4b;
        }
    </style>
</head>
<body class="text-slate-900">

    <!-- Navigation -->
    <nav class="sticky top-0 w-full z-50 bg-white border-b-4 border-indigo-950">
        <div class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">
            <div class="flex items-center space-x-2">
                <div class="w-10 h-10 bg-indigo-600 border-2 border-indigo-950 flex items-center justify-center">
                    <span class="text-white font-black text-xl">M</span>
                </div>
                <span class="font-black text-2xl tracking-tighter text-indigo-950 uppercase italic">Manuscript<span class="text-indigo-600">Pro</span></span>
            </div>
            <div class="hidden md:flex items-center space-x-8">
                <a href="#how-it-works" class="font-bold text-slate-600 hover:text-indigo-600">How it Works</a>
                <a href="https://manuscriptpro.online" class="font-bold text-slate-600 hover:text-indigo-600 underline underline-offset-4 decoration-indigo-600">Preview</a>
                <a href="https://dashboard.paystack.com/#/pages/2059005" class="btn-brand bg-indigo-600 text-white px-6 py-2 font-black uppercase text-sm">Get Started</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="pt-24 pb-20 px-6">
        <div class="max-w-7xl mx-auto text-center">
            <div class="label-bold mb-6">Standard: 72-Hour Delivery</div>
            <h1 class="serif text-5xl md:text-7xl font-bold text-indigo-950 mb-8 leading-[1.1]">
                Turn Your Manuscript Into a <br> <span class="text-indigo-600 italic">Published Book</span> — Today.
            </h1>
            <p class="text-xl md:text-2xl text-slate-600 mb-12 max-w-3xl mx-auto font-medium">
                Professional book layout and formatting for authors, coaches, and pastors. Fast, outcome-focused, and ready for Amazon.
            </p>
            <div class="flex flex-col sm:flex-row items-center justify-center gap-6 mb-20">
                <!-- PAYSTACK LINK -->
                <a href="https://dashboard.paystack.com/#/pages/2059005" class="btn-brand w-full sm:w-auto px-10 py-5 bg-indigo-600 text-white font-black text-xl uppercase tracking-tight">
                    Get My Book Formatted
                </a>
                <!-- PREVIEW LINK -->
                <a href="https://manuscriptpro.online" class="btn-brand w-full sm:w-auto px-10 py-5 bg-white text-indigo-950 font-black text-xl uppercase tracking-tight">
                    Try Free Preview
                </a>
            </div>

            <!-- Transformation Visual -->
            <div class="max-w-5xl mx-auto sketch-border bg-white p-8 md:p-12 flex flex-col md:flex-row items-center gap-12">
                <div class="w-full md:w-1/2 text-left opacity-30">
                    <div class="label-bold bg-slate-400 mb-4">Input: Raw Manuscript</div>
                    <div class="space-y-3">
                        <div class="h-3 w-full bg-slate-200 rounded-sm"></div>
                        <div class="h-3 w-full bg-slate-200 rounded-sm"></div>
                        <div class="h-3 w-4/5 bg-slate-200 rounded-sm"></div>
                    </div>
                </div>
                <div class="hidden md:block">
                    <svg class="w-12 h-12 text-indigo-600" fill="none" stroke="currentColor" stroke-width="4" viewBox="0 0 24 24"><path d="M13 5l7 7-7 7M5 12h14"></path></svg>
                </div>
                <div class="w-full md:w-1/2 text-left p-8 border-4 border-indigo-600 bg-white relative">
                    <div class="label-bold mb-4">Output: ManuscriptPro Ready</div>
                    <div class="serif text-3xl font-black text-indigo-950 mb-4">Chapter One</div>
                    <div class="space-y-2">
                        <div class="h-2 w-full bg-indigo-50"></div>
                        <div class="h-2 w-full bg-indigo-50"></div>
                        <div class="h-2 w-3/4 bg-indigo-50"></div>
                    </div>
                    <div class="absolute -right-4 -bottom-4 bg-indigo-600 text-white px-3 py-1 text-[10px] font-black uppercase shadow-lg">KDP Approved</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Pricing Section -->
    <section class="py-24 px-6">
        <div class="max-w-5xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="serif text-4xl font-black text-indigo-950 uppercase italic">Simple, Clear Pricing</h2>
            </div>
            <div class="grid md:grid-cols-2 gap-12">
                <!-- Standard -->
                <div class="p-10 sketch-card-dark bg-white relative">
                    <div class="label-bold absolute -top-4 left-6">Basic</div>
                    <h3 class="font-black text-2xl mb-2">Standard Plan</h3>
                    <div class="text-4xl font-black text-indigo-600 mb-8">₦75,000</div>
                    <ul class="space-y-4 mb-10 font-bold text-slate-700">
                        <li>• Print-Ready PDF Layout</li>
                        <li>• Reflowable eBook (ePub)</li>
                        <li>• 72-Hour Delivery</li>
                        <li>• 1 Revision Round</li>
                    </ul>
                    <a href="https://dashboard.paystack.com/#/pages/2059005" class="btn-brand block text-center w-full py-4 bg-white text-indigo-600 font-black uppercase">Choose Standard</a>
                </div>
                <!-- VIP -->
                <div class="p-10 sketch-border bg-indigo-600 text-white relative scale-105">
                    <div class="label-bold bg-yellow-400 text-indigo-950 absolute -top-4 right-6">Most Popular</div>
                    <h3 class="font-black text-2xl mb-2">VIP Premium</h3>
                    <div class="text-4xl font-black text-white mb-8">₦150,000</div>
                    <ul class="space-y-4 mb-10 font-bold text-indigo-50">
                        <li>• Everything in Standard</li>
                        <li>• Custom Chapter Headers</li>
                        <li>• Unlimited Revisions</li>
                        <li>• Priority 48-Hour Support</li>
                    </ul>
                    <a href="https://dashboard.paystack.com/#/pages/2059005" class="btn-brand block text-center w-full py-4 bg-white text-indigo-600 font-black uppercase">Choose VIP</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-white py-16 px-6">
        <div class="max-w-7xl mx-auto">
            <div class="grid md:grid-cols-4 gap-12 mb-12">
                <div class="col-span-1 md:col-span-2">
                    <div class="flex items-center space-x-2 mb-6">
                        <div class="w-8 h-8 bg-indigo-600 border-2 border-indigo-950 flex items-center justify-center">
                            <span class="text-white font-black text-sm">M</span>
                        </div>
                        <span class="font-black text-xl tracking-tighter text-indigo-950 uppercase italic">Manuscript<span class="text-indigo-600">Pro</span></span>
                    </div>
                    <p class="text-slate-600 font-medium max-w-xs mb-6">The gold standard in automated and high-precision book formatting for the modern author.</p>
                    <div class="label-bold">Service Status: 100% Operational</div>
                </div>

                <div>
                    <h4 class="font-black uppercase text-indigo-950 mb-6 text-sm tracking-widest underline decoration-2 decoration-indigo-600">Quick Links</h4>
                    <ul class="space-y-3 font-bold text-slate-600 text-sm">
                        <!-- UPDATED PREVIEW LINK -->
                        <li><a href="https://manuscriptpro.online" class="hover:text-indigo-600">Free Preview</a></li>
                        <li><a href="https://dashboard.paystack.com/#/pages/2059005" class="hover:text-indigo-600">Pricing & Checkout</a></li>
                        <li><a href="https://wa.me/2349155975173" class="hover:text-indigo-600">WhatsApp Support</a></li>
                    </ul>
                </div>

                <div>
                    <h4 class="font-black uppercase text-indigo-950 mb-6 text-sm tracking-widest underline decoration-2 decoration-indigo-600">Guarantee</h4>
                    <div class="p-4 border-2 border-dashed border-slate-300 rounded-lg">
                        <p class="text-xs font-bold text-slate-500 italic">"Every layout is triple-checked for Amazon KDP and IngramSpark compliance."</p>
                    </div>
                </div>
            </div>

            <div class="pt-8 border-t-2 border-slate-100 flex flex-col md:flex-row justify-between items-center gap-6">
                <p class="text-xs font-black text-slate-400 uppercase tracking-tighter">© 2024 ManuscriptPro Formatting Services. All rights reserved.</p>
                <img src="https://upload.wikimedia.org/wikipedia/commons/e/ed/Paystack_Logo.png" alt="Paystack" class="h-4 opacity-50">
            </div>
        </div>
    </footer>

    <!-- WhatsApp Support -->
    <a href="https://wa.me/2349155975173" target="_blank" class="fixed bottom-8 right-8 z-[100] flex items-center space-x-3 bg-white px-5 py-3 sketch-card-dark group">
        <div class="w-8 h-8 bg-green-500 border-2 border-indigo-950 rounded-full flex items-center justify-center text-white">
            <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/></svg>
        </div>
        <div class="flex flex-col">
            <span class="text-[10px] text-indigo-600 font-black leading-none uppercase">Support</span>
            <span class="text-xs font-black text-indigo-950">Chat with us about your book</span>
        </div>
    </a>

</body>
</html>
