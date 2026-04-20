<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ManuscriptPro | Premium Book Formatting</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;600;800&family=Playfair+Display:ital,wght@0,700;1,700&display=swap" rel="stylesheet">
    <style>
        body { 
            font-family: 'Plus Jakarta Sans', sans-serif; 
            scroll-behavior: smooth;
        }
        .serif { font-family: 'Playfair Display', serif; }
        
        /* BRAND STANDARD: BOLD SKETCHING & LABELING */
        .sketch-border {
            border: 4px solid #1e1b4b;
            box-shadow: 10px 10px 0px #6366f1;
        }
        .sketch-card {
            border: 3px solid #1e1b4b;
            box-shadow: 6px 6px 0px #1e1b4b;
            transition: all 0.2s ease;
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
            padding: 4px 12px;
            background: #1e1b4b;
            color: white;
            font-size: 0.75rem;
            font-weight: 800;
            text-transform: uppercase;
            letter-spacing: 0.1em;
        }
        .purple-gradient {
            background: linear-gradient(135deg, #f5f3ff 0%, #ffffff 100%);
        }
    </style>
</head>
<body class="text-slate-900 bg-white">

    <!-- Navigation -->
    <nav class="sticky top-0 w-full z-50 bg-white/90 backdrop-blur-md border-b-4 border-indigo-950">
        <div class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">
            <div class="flex items-center space-x-2">
                <div class="w-10 h-10 bg-indigo-600 border-2 border-indigo-950 flex items-center justify-center">
                    <span class="text-white font-black text-xl italic">M</span>
                </div>
                <span class="font-black text-2xl tracking-tighter text-indigo-950 uppercase italic">Manuscript<span class="text-indigo-600">Pro</span></span>
            </div>
            <div class="hidden md:flex items-center space-x-8">
                <a href="#how-it-works" class="font-bold text-slate-600 hover:text-indigo-600">Process</a>
                <a href="#pricing" class="font-bold text-slate-600 hover:text-indigo-600">Pricing</a>
                <a href="https://manuscriptpro.online" class="font-bold text-indigo-600 underline underline-offset-4 decoration-2">Preview</a>
                <a href="https://paystack.shop/pay/u6krvg7c2x" class="btn-brand bg-indigo-600 text-white px-6 py-2 font-black uppercase text-sm">Get Started</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="pt-20 pb-24 px-6 purple-gradient">
        <div class="max-w-7xl mx-auto text-center">
            <div class="label-bold mb-8">Professional Excellence in 72 Hours</div>
            <h1 class="serif text-5xl md:text-7xl font-bold text-indigo-950 mb-8 leading-[1.15]">
                Turn Your Manuscript Into a Professionally Published Book — <span class="text-indigo-600 italic">Without Hiring a Designer</span>
            </h1>
            <p class="text-xl md:text-2xl text-slate-600 mb-12 max-w-3xl mx-auto font-medium leading-relaxed">
                Premium layout, perfect typography, and guaranteed KDP approval. We transform your raw document into a masterpiece in just 3 days.
            </p>
            <div class="flex flex-col sm:flex-row items-center justify-center gap-6 mb-24">
                <a href="https://paystack.shop/pay/u6krvg7c2x" class="btn-brand w-full sm:w-auto px-10 py-5 bg-indigo-600 text-white font-black text-xl uppercase tracking-tight">
                    Get My Book Formatted
                </a>
                <a href="https://manuscriptpro.online" class="btn-brand w-full sm:w-auto px-10 py-5 bg-white text-indigo-950 font-black text-xl uppercase tracking-tight">
                    Try Free Preview
                </a>
            </div>

            <!-- Transformation Visual -->
            <div class="max-w-4xl mx-auto sketch-border bg-white p-10 flex flex-col md:flex-row items-center gap-8">
                <div class="flex-1 opacity-40 text-left border-2 border-dashed border-slate-300 p-6">
                    <p class="text-xs font-mono text-slate-400 mb-2">// raw_manuscript.docx</p>
                    <div class="space-y-3">
                        <div class="h-2 w-full bg-slate-200"></div>
                        <div class="h-2 w-full bg-slate-200"></div>
                        <div class="h-2 w-3/4 bg-slate-200"></div>
                    </div>
                </div>
                <div class="p-4 bg-indigo-50 rounded-full">
                    <svg class="w-8 h-8 text-indigo-600" fill="none" stroke="currentColor" stroke-width="3" viewBox="0 0 24 24"><path d="M13 5l7 7-7 7M5 12h14"></path></svg>
                </div>
                <div class="flex-1 text-left p-8 border-4 border-indigo-600 relative bg-white">
                    <div class="label-bold absolute -top-4 -right-4 italic">Ready</div>
                    <h3 class="serif text-2xl font-bold mb-4">Chapter One</h3>
                    <div class="space-y-2">
                        <div class="h-1.5 w-full bg-indigo-100"></div>
                        <div class="h-1.5 w-full bg-indigo-100"></div>
                        <div class="h-1.5 w-4/5 bg-indigo-100"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Problem Section -->
    <section class="py-24 px-6 border-y-4 border-indigo-950 bg-slate-50">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="serif text-4xl font-bold text-indigo-950 uppercase italic">The Author's Struggle</h2>
            </div>
            <div class="grid md:grid-cols-4 gap-8">
                <div class="p-8 sketch-card bg-white">
                    <div class="w-12 h-12 bg-indigo-100 flex items-center justify-center mb-6 border-2 border-indigo-950">
                        <span class="font-black text-indigo-600">!</span>
                    </div>
                    <h3 class="font-extrabold text-lg mb-3 uppercase">Expensive Designers</h3>
                    <p class="text-sm text-slate-600 font-medium leading-relaxed">Top-tier designers charge thousands for simple layouts. We don't.</p>
                </div>
                <div class="p-8 sketch-card bg-white">
                    <div class="w-12 h-12 bg-indigo-100 flex items-center justify-center mb-6 border-2 border-indigo-950">
                        <span class="font-black text-indigo-600">?</span>
                    </div>
                    <h3 class="font-extrabold text-lg mb-3 uppercase">Format Confusion</h3>
                    <p class="text-sm text-slate-600 font-medium leading-relaxed">Margins, bleeds, and gutter sizes are a headache. Let us handle them.</p>
                </div>
                <div class="p-8 sketch-card bg-white">
                    <div class="w-12 h-12 bg-indigo-100 flex items-center justify-center mb-6 border-2 border-indigo-950">
                        <span class="font-black text-indigo-600">X</span>
                    </div>
                    <h3 class="font-extrabold text-lg mb-3 uppercase">Rejected Files</h3>
                    <p class="text-sm text-slate-600 font-medium leading-relaxed">Avoid the heartbreak of Amazon KDP rejecting your DIY manuscript.</p>
                </div>
                <div class="p-8 sketch-card bg-white">
                    <div class="w-12 h-12 bg-indigo-100 flex items-center justify-center mb-6 border-2 border-indigo-950">
                        <span class="font-black text-indigo-600">⌛</span>
                    </div>
                    <h3 class="font-extrabold text-lg mb-3 uppercase">Wasted Time</h3>
                    <p class="text-sm text-slate-600 font-medium leading-relaxed">Stop fighting with Word. Spend your time writing the next book instead.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Solution Section -->
    <section class="py-24 px-6 bg-white">
        <div class="max-w-5xl mx-auto flex flex-col md:flex-row items-center gap-16">
            <div class="md:w-1/2">
                <div class="label-bold mb-6">Outcome Focused</div>
                <h2 class="serif text-4xl font-bold text-indigo-950 mb-6">High-End Precision <br> Meets Human Craft</h2>
                <p class="text-lg text-slate-600 font-medium mb-8 leading-relaxed">
                    ManuscriptPro bridges the gap between raw text and professional publishing. We use advanced layout technology combined with human refinement to ensure every page looks like it came from a major publishing house.
                </p>
                <div class="space-y-4">
                    <div class="flex items-center space-x-3">
                        <div class="w-5 h-5 bg-indigo-600 text-white flex items-center justify-center text-[10px] font-bold">✓</div>
                        <span class="font-bold text-indigo-950">Guaranteed KDP Acceptance</span>
                    </div>
                    <div class="flex items-center space-x-3">
                        <div class="w-5 h-5 bg-indigo-600 text-white flex items-center justify-center text-[10px] font-bold">✓</div>
                        <span class="font-bold text-indigo-950">Custom Chapter Heading Styles</span>
                    </div>
                </div>
            </div>
            <div class="md:w-1/2">
                <div class="sketch-border p-2 bg-indigo-950">
                    <div class="bg-white p-6">
                        <div class="h-64 bg-slate-100 flex items-center justify-center text-indigo-950 font-black text-4xl italic opacity-20">MANUSCRIPTPRO</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- How It Works -->
    <section id="how-it-works" class="py-24 px-6 bg-indigo-950 text-white">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-20">
                <h2 class="serif text-4xl font-bold uppercase italic tracking-wider">The 72-Hour Path</h2>
            </div>
            <div class="grid md:grid-cols-4 gap-12">
                <div class="text-center">
                    <div class="w-16 h-16 bg-indigo-600 mx-auto mb-6 flex items-center justify-center border-4 border-white rotate-3">
                        <span class="font-black text-2xl italic">01</span>
                    </div>
                    <h4 class="font-extrabold uppercase mb-2">Submit</h4>
                    <p class="text-xs text-indigo-200 font-medium">Upload your Word document or raw manuscript.</p>
                </div>
                <div class="text-center">
                    <div class="w-16 h-16 bg-indigo-600 mx-auto mb-6 flex items-center justify-center border-4 border-white -rotate-3">
                        <span class="font-black text-2xl italic">02</span>
                    </div>
                    <h4 class="font-extrabold uppercase mb-2">Preview</h4>
                    <p class="text-xs text-indigo-200 font-medium">See an instant automated draft of your future book.</p>
                </div>
                <div class="text-center">
                    <div class="w-16 h-16 bg-indigo-600 mx-auto mb-6 flex items-center justify-center border-4 border-white rotate-6">
                        <span class="font-black text-2xl italic">03</span>
                    </div>
                    <h4 class="font-extrabold uppercase mb-2">Refine</h4>
                    <p class="text-xs text-indigo-200 font-medium">Our experts polish the layout for perfect readability.</p>
                </div>
                <div class="text-center">
                    <div class="w-16 h-16 bg-indigo-600 mx-auto mb-6 flex items-center justify-center border-4 border-white -rotate-6">
                        <span class="font-black text-2xl italic">04</span>
                    </div>
                    <h4 class="font-extrabold uppercase mb-2">Deliver</h4>
                    <p class="text-xs text-indigo-200 font-medium">Get your final KDP-ready PDF and ePub files.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Pricing Section -->
    <section id="pricing" class="py-24 px-6 bg-white">
        <div class="max-w-5xl mx-auto">
            <div class="text-center mb-20">
                <h2 class="serif text-5xl font-bold text-indigo-950 mb-4">Invest in Your Legacy</h2>
                <p class="text-slate-500 font-bold uppercase tracking-widest text-sm">Clear pricing. Zero hidden fees.</p>
            </div>
            <div class="grid md:grid-cols-2 gap-12">
                <!-- Standard -->
                <div class="p-12 sketch-card bg-white relative">
                    <div class="label-bold absolute -top-4 left-8">Standard</div>
                    <h3 class="text-2xl font-extrabold text-indigo-950 mb-2 italic">Essential Layout</h3>
                    <div class="text-5xl font-black text-indigo-600 mb-8">₦75,000</div>
                    <ul class="space-y-5 mb-10 font-bold text-slate-700">
                        <li class="flex items-center gap-3"><span class="text-indigo-600">✓</span> Print-Ready PDF (KDP)</li>
                        <li class="flex items-center gap-3"><span class="text-indigo-600">✓</span> Reflowable ePub</li>
                        <li class="flex items-center gap-3"><span class="text-indigo-600">✓</span> Standard Typography</li>
                        <li class="flex items-center gap-3"><span class="text-indigo-600">✓</span> 72-Hour Turnaround</li>
                    </ul>
                    <a href="https://paystack.shop/pay/u6krvg7c2x" class="btn-brand block text-center w-full py-4 bg-white text-indigo-950 font-black uppercase">Choose Standard</a>
                </div>
                <!-- VIP -->
                <div class="p-12 sketch-border bg-indigo-600 text-white relative">
                    <div class="label-bold bg-yellow-400 text-indigo-950 absolute -top-4 right-8">Most Popular</div>
                    <h3 class="text-2xl font-extrabold mb-2 italic text-white">VIP Premium</h3>
                    <div class="text-5xl font-black text-white mb-8">₦150,000</div>
                    <ul class="space-y-5 mb-10 font-bold text-indigo-100">
                        <li class="flex items-center gap-3"><span>★</span> Everything in Standard</li>
                        <li class="flex items-center gap-3"><span>★</span> Custom Chapter Headings</li>
                        <li class="flex items-center gap-3"><span>★</span> Priority Support</li>
                        <li class="flex items-center gap-3"><span>★</span> Unlimited Revisions</li>
                    </ul>
                    <a href="https://paystack.shop/pay/u6krvg7c2x" class="btn-brand block text-center w-full py-4 bg-white text-indigo-600 font-black uppercase">Choose VIP</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Comparison Section -->
    <section class="py-24 px-6 bg-slate-50 border-y-4 border-indigo-950">
        <div class="max-w-4xl mx-auto">
            <h2 class="serif text-3xl font-bold text-center mb-16 italic underline decoration-indigo-600">The Comparison</h2>
            <div class="grid grid-cols-3 gap-4 text-center">
                <div class="font-black uppercase text-xs text-slate-400 py-4">Feature</div>
                <div class="font-black uppercase text-xs text-indigo-950 py-4 bg-indigo-50 border-x-2 border-indigo-950">ManuscriptPro</div>
                <div class="font-black uppercase text-xs text-slate-400 py-4">Designers</div>
                
                <div class="font-bold text-sm py-4 border-b border-slate-200">Speed</div>
                <div class="font-black text-sm py-4 border-b-2 border-indigo-950 bg-indigo-50 text-indigo-600 italic">72 Hours</div>
                <div class="font-bold text-sm py-4 border-b border-slate-200 text-slate-400">2-4 Weeks</div>

                <div class="font-bold text-sm py-4 border-b border-slate-200">Price</div>
                <div class="font-black text-sm py-4 border-b-2 border-indigo-950 bg-indigo-50 text-indigo-600 italic underline decoration-1">₦75k - ₦150k</div>
                <div class="font-bold text-sm py-4 border-b border-slate-200 text-slate-400">₦350k+</div>

                <div class="font-bold text-sm py-4">Process</div>
                <div class="font-black text-sm py-4 border-indigo-950 bg-indigo-50 text-indigo-600 italic">Automated Ease</div>
                <div class="font-bold text-sm py-4 text-slate-400">Manual & Back-and-forth</div>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section class="py-24 px-6 bg-white">
        <div class="max-w-3xl mx-auto">
            <h2 class="serif text-4xl font-bold text-center mb-16 italic">Questions</h2>
            <div class="space-y-6">
                <details class="group sketch-card p-6 cursor-pointer bg-white" open>
                    <summary class="font-black uppercase text-sm flex justify-between items-center list-none">
                        What files do I get?
                        <span class="group-open:rotate-180 transition-transform">↓</span>
                    </summary>
                    <p class="mt-4 text-sm font-medium text-slate-600 leading-relaxed">
                        You receive a print-ready interior PDF (ready for Amazon KDP) and a reflowable ePub file for Kindle and Apple Books.
                    </p>
                </details>
                <details class="group sketch-card p-6 cursor-pointer bg-white">
                    <summary class="font-black uppercase text-sm flex justify-between items-center list-none">
                        Do you design covers too?
                        <span class="group-open:rotate-180 transition-transform">↓</span>
                    </summary>
                    <p class="mt-4 text-sm font-medium text-slate-600 leading-relaxed">
                        ManuscriptPro focuses exclusively on the interior layout. We ensure your pages are professional, readable, and technically perfect.
                    </p>
                </details>
            </div>
        </div>
    </section>

    <!-- Final CTA -->
    <section class="py-32 bg-indigo-950 text-white text-center px-6 border-t-8 border-indigo-600">
        <div class="max-w-4xl mx-auto">
            <h2 class="serif text-4xl md:text-6xl font-black mb-8 italic">Your manuscript deserves to be a real book.</h2>
            <p class="text-xl text-indigo-200 mb-12 font-medium">Join 500+ authors who skipped the formatting headache.</p>
            <a href="https://paystack.shop/pay/u6krvg7c2x" class="btn-brand inline-block px-12 py-6 bg-indigo-600 text-white font-black text-2xl uppercase">
                Get Started Now
            </a>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-white py-16 px-6">
        <div class="max-w-7xl mx-auto">
            <div class="grid md:grid-cols-4 gap-12 mb-12">
                <div class="col-span-2">
                    <div class="flex items-center space-x-2 mb-6">
                        <div class="w-8 h-8 bg-indigo-600 border-2 border-indigo-950 flex items-center justify-center">
                            <span class="text-white font-black text-sm italic">M</span>
                        </div>
                        <span class="font-black text-xl tracking-tighter text-indigo-950 uppercase italic">Manuscript<span class="text-indigo-600">Pro</span></span>
                    </div>
                    <p class="text-slate-600 font-bold max-w-xs mb-6 italic">Professional interior book formatting for authors who demand excellence.</p>
                    <div class="label-bold">Service Status: Active</div>
                </div>
                <div>
                    <h4 class="font-black uppercase text-indigo-950 mb-6 text-sm tracking-widest underline decoration-4 decoration-indigo-600 underline-offset-4">Legal</h4>
                    <ul class="space-y-3 font-bold text-slate-500 text-sm">
                        <li>Privacy Policy</li>
                        <li>Terms of Service</li>
                        <li>Contact: support@manuscriptpro.com</li>
                    </ul>
                </div>
                <div>
                    <h4 class="font-black uppercase text-indigo-950 mb-6 text-sm tracking-widest underline decoration-4 decoration-indigo-600 underline-offset-4">Support</h4>
                    <a href="https://wa.me/2349155975173" class="font-black text-green-600 hover:underline">Chat on WhatsApp</a>
                </div>
            </div>
            <div class="pt-8 border-t-4 border-indigo-950 flex justify-between items-center">
                <p class="text-[10px] font-black text-slate-400 uppercase tracking-widest">© 2024 ManuscriptPro. Built for Authors.</p>
                <img src="https://upload.wikimedia.org/wikipedia/commons/e/ed/Paystack_Logo.png" alt="Paystack" class="h-4 opacity-50 grayscale">
            </div>
        </div>
    </footer>

    <!-- WhatsApp Support Button -->
    <a href="https://wa.me/2349155975173" target="_blank" class="fixed bottom-8 right-8 z-[100] flex items-center space-x-3 bg-white px-5 py-3 sketch-card group hover:bg-green-50 transition-colors">
        <div class="w-8 h-8 bg-green-500 border-2 border-indigo-950 rounded-full flex items-center justify-center text-white">
            <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/></svg>
        </div>
        <div class="flex flex-col">
            <span class="text-[10px] text-indigo-600 font-black leading-none uppercase tracking-tighter">Support</span>
            <span class="text-xs font-black text-indigo-950">Chat with us about your book</span>
        </div>
    </a>

</body>
</html>
