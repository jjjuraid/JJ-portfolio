<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JJ Aljuraid | Investigative Journalist & Political Thinker</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@300;400;500;700&family=Merriweather:ital,wght@0,300;0,400;0,700;1,300&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Merriweather', serif; }
        h1, h2, h3, h4, .headline { font-family: 'Oswald', sans-serif; }
        
        /* Smooth Fade In */
        .fade-in { opacity: 0; transform: translateY(20px); animation: fadeInUp 0.8s forwards; }
        @keyframes fadeInUp { to { opacity: 1; transform: translateY(0); } }

        /* Rolling Ticker Animation */
        .ticker-wrap {
            width: 100%;
            overflow: hidden;
            background-color: #0f172a; /* Slate 900 */
            padding-left: 100%;
            box-sizing: content-box;
            border-top: 1px solid #1e293b;
            border-bottom: 1px solid #1e293b;
        }
        .ticker {
            display: inline-flex;
            align-items: center;
            height: 6rem;
            white-space: nowrap;
            padding-right: 100%;
            box-sizing: content-box;
            animation: ticker 40s linear infinite;
        }
        .ticker__item {
            display: inline-block;
            padding: 0 3rem;
            flex-shrink: 0;
        }
        /* Logo Styling */
        .ticker__logo {
            height: 3rem;
            width: auto;
            max-width: 180px;
            filter: grayscale(100%) brightness(0.8) contrast(1.2);
            opacity: 0.6;
            transition: all 0.3s ease;
            object-fit: contain;
        }
        .ticker__logo:hover {
            filter: grayscale(0%) brightness(1);
            opacity: 1;
            transform: scale(1.1);
        }

        @keyframes ticker {
            0% { transform: translate3d(0, 0, 0); }
            100% { transform: translate3d(-100%, 0, 0); }
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased selection:bg-blue-200 selection:text-blue-900">

    <!-- Navbar -->
    <nav class="bg-white/95 backdrop-blur-md border-b border-slate-200 fixed w-full top-0 z-50 transition-all duration-300 shadow-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-24 items-center">
                <div class="flex items-center gap-4">
                    <!-- Initials Logo -->
                    <div class="w-12 h-12 bg-slate-900 text-white flex items-center justify-center font-bold text-2xl rounded-sm shadow-lg border-2 border-blue-500">JJ</div>
                    <div>
                        <span class="block text-2xl font-bold text-slate-900 headline uppercase tracking-wide leading-none">Jasem Aljuraid</span>
                        <span class="text-xs text-blue-700 font-bold uppercase tracking-widest">Investigative Journalist & Political Thinker</span>
                    </div>
                </div>
                <div class="hidden lg:flex items-center space-x-8">
                    <a href="#about" class="text-sm font-bold uppercase tracking-wider text-slate-500 hover:text-blue-900 transition">About</a>
                    <a href="#media" class="text-sm font-bold uppercase tracking-wider text-slate-500 hover:text-blue-900 transition">Interviews</a>
                    <a href="#gallery" class="text-sm font-bold uppercase tracking-wider text-slate-500 hover:text-blue-900 transition">Gallery</a>
                    <a href="#contact" class="bg-blue-900 text-white px-6 py-3 rounded-sm font-bold uppercase text-sm tracking-wider hover:bg-blue-800 transition shadow-lg hover:shadow-blue-900/30">
                        <i class="fas fa-envelope mr-2"></i> Contact
                    </a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="relative pt-40 pb-20 lg:pt-56 lg:pb-40 overflow-hidden bg-slate-900 text-white">
        <!-- Background Image -->
        <div class="absolute inset-0 opacity-30">
            <img src="https://images.unsplash.com/photo-1451187580459-43490279c0fa?ixlib=rb-4.0.3&auto=format&fit=crop&w=2000&q=80" class="w-full h-full object-cover" alt="Global Network">
        </div>
        <div class="absolute inset-0 bg-gradient-to-r from-slate-900 via-slate-900/90 to-slate-900/40"></div>

        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="grid lg:grid-cols-2 gap-16 items-center">
                <div class="fade-in">
                    <div class="flex flex-wrap gap-3 mb-8">
                        <span class="bg-blue-600 border border-blue-400 text-white px-4 py-1 text-sm font-bold uppercase tracking-widest rounded-sm">Protected Person (Canada)</span>
                        <span class="bg-emerald-600 border border-emerald-400 text-white px-4 py-1 text-sm font-bold uppercase tracking-widest rounded-sm">
                            <i class="fas fa-language mr-1"></i> Arabic & English
                        </span>
                    </div>
                    <h1 class="text-6xl lg:text-7xl font-bold leading-tight mb-6 drop-shadow-2xl headline">
                        WRITER. ANALYST.<br>
                        <span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-emerald-400">STRATEGIC THINKER.</span>
                    </h1>
                    <p class="text-xl text-slate-300 leading-relaxed max-w-2xl mb-10 font-light border-l-4 border-blue-500 pl-6">
                        I paid 12 years of my freedom for speaking the truth. I am an investigative journalist who exposed the Muslim Brotherhood's funding in the Gulf and broke the ultimate taboo by speaking directly to Israel.
                    </p>
                    <div class="flex flex-col sm:flex-row gap-4">
                        <a href="#media" class="flex items-center justify-center gap-3 bg-white text-slate-900 px-8 py-4 rounded-sm font-bold uppercase tracking-widest transition hover:bg-blue-50 headline shadow-xl">
                            <i class="fas fa-play-circle text-xl text-blue-600"></i> Watch Evidence
                        </a>
                        <a href="#contact" class="flex items-center justify-center gap-3 border-2 border-white/30 hover:border-white text-white px-8 py-4 rounded-sm font-bold uppercase tracking-widest transition headline backdrop-blur-sm">
                            Request Briefing
                        </a>
                    </div>
                </div>
                
                <!-- Hero Visual Placeholder -->
                <div class="relative fade-in hidden lg:block" style="animation-delay: 0.2s;">
                    <div class="relative z-10 transform rotate-2 hover:rotate-0 transition duration-700">
                        <!-- REPLACE WITH YOUR MAIN HEADSHOT -->
                        <img src="https://placehold.co/600x700/1e293b/ffffff?text=JJ+Aljuraid+Portrait" class="rounded-lg shadow-2xl border-4 border-white/10 w-full object-cover" alt="Jasem Aljuraid">
                        
                        <!-- Overlay Card -->
                        <div class="absolute bottom-10 -left-10 bg-white/95 backdrop-blur p-6 rounded shadow-2xl border-l-8 border-blue-600 max-w-sm">
                            <p class="text-slate-900 font-bold text-lg headline uppercase">"Liberalism is the belief in intellectual freedom."</p>
                            <div class="mt-4 flex items-center justify-between text-slate-500 text-xs font-bold uppercase tracking-wider">
                                <span>Followers</span>
                                <span>84,000+</span>
                            </div>
                        </div>
                    </div>
                    <!-- Decorative Element -->
                    <div class="absolute -top-10 -right-10 w-72 h-72 bg-blue-500/20 rounded-full blur-3xl"></div>
                </div>
            </div>
        </div>
    </header>

    <!-- ROLLING LOGO TICKER SECTION -->
    <section class="bg-slate-900 py-6 border-b border-slate-800">
         <div class="ticker-wrap">
            <div class="ticker">
                <!-- Logos via Clearbit -->
                <div class="ticker__item"><img src="https://logo.clearbit.com/alqabas.com" alt="Al-Qabas" class="ticker__logo"></div>
                <div class="ticker__item"><img src="https://logo.clearbit.com/i24news.tv" alt="i24NEWS" class="ticker__logo"></div>
                <div class="ticker__item"><img src="https://logo.clearbit.com/haaretz.com" alt="Haaretz" class="ticker__logo"></div>
                <div class="ticker__item"><img src="https://logo.clearbit.com/memri.org" alt="MEMRI" class="ticker__logo"></div>
                <div class="ticker__item"><img src="https://logo.clearbit.com/fairobserver.com" alt="Fair Observer" class="ticker__logo"></div>
                <div class="ticker__item"><img src="https://logo.clearbit.com/moderndiplomacy.eu" alt="Modern Diplomacy" class="ticker__logo"></div>
                <div class="ticker__item"><img src="https://logo.clearbit.com/jpost.com" alt="Jerusalem Post" class="ticker__logo"></div>
                <div class="ticker__item"><img src="https://logo.clearbit.com/independentarabia.com" alt="Independent Arabia" class="ticker__logo"></div>
                <div class="ticker__item"><img src="https://logo.clearbit.com/alhurra.com" alt="Alhurra" class="ticker__logo"></div>
                <div class="ticker__item"><img src="https://logo.clearbit.com/jns.org" alt="JNS" class="ticker__logo"></div>
                <div class="ticker__item"><img src="https://logo.clearbit.com/cdt.ch" alt="Corriere del Ticino" class="ticker__logo"></div>
                <div class="ticker__item"><img src="https://logo.clearbit.com/israeltoday.co.il" alt="Israel Today" class="ticker__logo"></div>
                <!-- Duplicate for loop -->
                <div class="ticker__item"><img src="https://logo.clearbit.com/i24news.tv" alt="i24NEWS" class="ticker__logo"></div>
                <div class="ticker__item"><img src="https://logo.clearbit.com/haaretz.com" alt="Haaretz" class="ticker__logo"></div>
            </div>
        </div>
    </section>

    <!-- VIDEO WALL SECTION -->
    <section id="media" class="py-24 bg-slate-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <span class="text-blue-600 font-bold uppercase tracking-widest text-sm mb-3 block">Investigative Reports & Interviews</span>
                <h2 class="text-4xl lg:text-5xl font-bold text-slate-900 headline mb-6">UNVARNISHED INTELLIGENCE</h2>
                <p class="text-lg text-slate-600">Direct engagement with Western, Israeli, and Arab media on the topics others are afraid to touch.</p>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-10">
                
                <!-- Video 1: Goldie Show -->
                <div class="bg-white rounded-lg overflow-hidden shadow-lg hover:shadow-2xl transition-all duration-300 group">
                    <div class="aspect-w-16 aspect-h-9 bg-black">
                        <iframe class="w-full h-64" src="https://www.youtube.com/embed/YBICyBLGse4" title="Goldie Show" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    </div>
                    <div class="p-8 border-t-4 border-red-600">
                        <div class="flex items-center justify-between mb-4">
                            <span class="text-xs font-bold text-slate-400 uppercase tracking-wider">The Goldie Show (Canada)</span>
                            <i class="fas fa-video text-slate-300"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900 mb-3 headline leading-tight group-hover:text-blue-700 transition">Genocide in Sudan & Islamist Disinformation</h3>
                        <p class="text-sm text-slate-600 leading-relaxed">Exposing the Muslim Brotherhood's role in the Sudanese civil war with MPP Goldie Ghamari.</p>
                    </div>
                </div>

                <!-- Video 2: i24 Zvi -->
                <div class="bg-white rounded-lg overflow-hidden shadow-lg hover:shadow-2xl transition-all duration-300 group">
                    <div class="aspect-w-16 aspect-h-9 bg-black">
                        <iframe class="w-full h-64" src="https://www.youtube.com/embed/1I9633RhANw" title="i24 Zvi" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    </div>
                    <div class="p-8 border-t-4 border-blue-600">
                        <div class="flex items-center justify-between mb-4">
                            <span class="text-xs font-bold text-slate-400 uppercase tracking-wider">i24NEWS (Israel)</span>
                            <i class="fas fa-video text-slate-300"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900 mb-3 headline leading-tight group-hover:text-blue-700 transition">"When Palestinians Betrayed Us"</h3>
                        <p class="text-sm text-slate-600 leading-relaxed">A candid discussion with Zvi Yehezkeli on the 1991 expulsion and internal security threats.</p>
                    </div>
                </div>

                <!-- Video 3: i24 Arabic -->
                <div class="bg-white rounded-lg overflow-hidden shadow-lg hover:shadow-2xl transition-all duration-300 group">
                    <div class="aspect-w-16 aspect-h-9 bg-black">
                        <iframe class="w-full h-64" src="https://www.youtube.com/embed/iDDcnFU2nPs" title="i24 Arabic" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    </div>
                    <div class="p-8 border-t-4 border-emerald-600">
                        <div class="flex items-center justify-between mb-4">
                            <span class="text-xs font-bold text-slate-400 uppercase tracking-wider">i24NEWS (Arabic)</span>
                            <i class="fas fa-video text-slate-300"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900 mb-3 headline leading-tight group-hover:text-blue-700 transition">Why the Arab World Rejects Refugees</h3>
                        <p class="text-sm text-slate-600 leading-relaxed">Analyzing Gulf security policy and the strategic refusal to import political instability.</p>
                    </div>
                </div>

                <!-- Video 4: MEMRI 1 -->
                <div class="bg-white rounded-lg overflow-hidden shadow-lg hover:shadow-2xl transition-all duration-300 group">
                    <div class="aspect-w-16 aspect-h-9 bg-black">
                        <iframe class="w-full h-64" src="https://www.youtube.com/embed/z9A4adCtLWs" title="MEMRI 1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    </div>
                    <div class="p-8 border-t-4 border-slate-600">
                        <div class="flex items-center justify-between mb-4">
                            <span class="text-xs font-bold text-slate-400 uppercase tracking-wider">MEMRI TV</span>
                            <i class="fas fa-tv text-slate-300"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900 mb-3 headline leading-tight group-hover:text-blue-700 transition">Defending Normalization</h3>
                        <p class="text-sm text-slate-600 leading-relaxed">"Kuwait Should Have Peace with Israel." Defending UN charter obligations on national TV.</p>
                    </div>
                </div>

                <!-- Video 5: MEMRI 2 -->
                <div class="bg-white rounded-lg overflow-hidden shadow-lg hover:shadow-2xl transition-all duration-300 group">
                    <div class="aspect-w-16 aspect-h-9 bg-black">
                        <iframe class="w-full h-64" src="https://www.youtube.com/embed/QdxWi9cqtrk" title="MEMRI 2" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                    </div>
                    <div class="p-8 border-t-4 border-slate-600">
                        <div class="flex items-center justify-between mb-4">
                            <span class="text-xs font-bold text-slate-400 uppercase tracking-wider">MEMRI TV</span>
                            <i class="fas fa-tv text-slate-300"></i>
                        </div>
                        <h3 class="text-xl font-bold text-slate-900 mb-3 headline leading-tight group-hover:text-blue-700 transition">Against Sports Boycotts</h3>
                        <p class="text-sm text-slate-600 leading-relaxed">A viral critique of the hypocrisy of Kuwaiti athletes withdrawing from matches against Israelis.</p>
                    </div>
                </div>

                <!-- Feature: Avichay Adraee -->
                <div class="bg-slate-900 rounded-lg overflow-hidden shadow-2xl hover:shadow-blue-900/50 transition-all duration-300 relative group flex flex-col">
                     <div class="absolute top-0 right-0 bg-red-600 text-white text-xs font-bold px-4 py-2 uppercase tracking-widest rounded-bl-lg z-20">Key Event</div>
                    <div class="h-64 bg-slate-800 flex items-center justify-center text-slate-600 relative overflow-hidden">
                        <div class="absolute inset-0 bg-blue-900/20 group-hover:bg-blue-900/10 transition"></div>
                        <i class="fas fa-microphone-lines text-7xl opacity-50 group-hover:scale-110 transition duration-700"></i>
                    </div>
                    <div class="p-8 flex-grow flex flex-col justify-between">
                        <div>
                            <div class="flex items-center gap-2 mb-4">
                                <span class="text-blue-400 text-xs font-bold uppercase tracking-widest">X Spaces Live</span>
                            </div>
                            <h3 class="text-2xl font-bold text-white mb-4 headline leading-tight">Hosting Avichay Adraee</h3>
                            <p class="text-slate-400 mb-6 text-sm">The historic direct dialogue with the IDF Spokesperson to Arab Media, breaking the silence.</p>
                        </div>
                        <a href="https://x.com/i/spaces/1BdxYrMpBpNKX" target="_blank" class="inline-flex items-center justify-center w-full text-white border-2 border-white/20 hover:bg-white hover:text-slate-900 px-6 py-3 rounded-sm transition font-bold uppercase tracking-wider">
                            <i class="fas fa-headphones mr-3"></i> Listen
                        </a>
                        <a href="https://x.com/i/spaces/1yoJMwlzVzkKQ" target="_blank" class="mt-4 inline-flex items-center justify-center w-full text-slate-300 border-2 border-slate-700 hover:border-slate-500 hover:text-white px-6 py-3 rounded-sm transition font-bold uppercase tracking-wider text-xs">
                            <i class="fas fa-headphones mr-3"></i> Listen (Part 2)
                        </a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- NEW GALLERY SECTION -->
    <section id="gallery" class="py-24 bg-white border-t border-slate-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-4xl font-bold text-slate-900 headline mb-12 border-l-8 border-slate-900 pl-6">
                ON THE GROUND
            </h2>
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-4">
                <!-- PHOTO 1: REPLACE SRC -->
                <div class="relative group h-80 overflow-hidden rounded-sm">
                    <img src="https://placehold.co/400x600/1e293b/ffffff?text=Kuwait+Parliament+Campaign" class="w-full h-full object-cover transition duration-700 group-hover:scale-110 grayscale group-hover:grayscale-0" alt="Campaign">
                    <div class="absolute inset-0 bg-gradient-to-t from-slate-900/90 to-transparent opacity-0 group-hover:opacity-100 transition duration-300 flex items-end p-6">
                        <span class="text-white font-bold headline text-lg">Parliament Campaign</span>
                    </div>
                </div>
                <!-- PHOTO 2: REPLACE SRC -->
                <div class="relative group h-80 overflow-hidden rounded-sm lg:col-span-2">
                    <img src="https://placehold.co/800x600/3b82f6/ffffff?text=Speaking+Engagement" class="w-full h-full object-cover transition duration-700 group-hover:scale-110 grayscale group-hover:grayscale-0" alt="Speaking">
                    <div class="absolute inset-0 bg-gradient-to-t from-slate-900/90 to-transparent opacity-0 group-hover:opacity-100 transition duration-300 flex items-end p-6">
                        <span class="text-white font-bold headline text-lg">International Policy Forums</span>
                    </div>
                </div>
                <!-- PHOTO 3: REPLACE SRC -->
                <div class="relative group h-80 overflow-hidden rounded-sm">
                    <img src="https://placehold.co/400x600/10b981/ffffff?text=Media+Appearance" class="w-full h-full object-cover transition duration-700 group-hover:scale-110 grayscale group-hover:grayscale-0" alt="Media">
                    <div class="absolute inset-0 bg-gradient-to-t from-slate-900/90 to-transparent opacity-0 group-hover:opacity-100 transition duration-300 flex items-end p-6">
                        <span class="text-white font-bold headline text-lg">Media Commentary</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FOOTER / CONTACT -->
    <footer id="contact" class="bg-slate-900 text-white py-24 relative overflow-hidden">
        <div class="absolute inset-0 bg-[url('https://www.transparenttextures.com/patterns/cubes.png')] opacity-5"></div>
        <div class="max-w-5xl mx-auto px-4 text-center relative z-10">
            <h2 class="text-5xl lg:text-6xl font-bold mb-8 headline">LET'S REDEFINE THE NARRATIVE</h2>
            <p class="text-slate-400 text-xl mb-16 max-w-3xl mx-auto font-light">
                Available for high-level policy briefs, op-eds, and strategic consulting regarding Gulf Security and the Islamist threat.
            </p>

            <div class="grid md:grid-cols-2 gap-8 mb-16">
                <a href="mailto:jjuraid@gmail.com" class="bg-blue-600 hover:bg-blue-500 p-10 rounded-sm transition transform hover:-translate-y-2 shadow-2xl group">
                    <i class="fas fa-envelope text-4xl mb-6 text-blue-200 group-hover:text-white transition"></i>
                    <h3 class="text-2xl font-bold headline uppercase tracking-widest mb-2">Email Me</h3>
                    <p class="text-lg text-blue-100 group-hover:text-white font-sans">jjuraid@gmail.com</p>
                </a>
                <a href="tel:+16133244412" class="bg-slate-800 hover:bg-slate-700 p-10 rounded-sm transition transform hover:-translate-y-2 shadow-2xl group border border-slate-700">
                    <i class="fas fa-phone text-4xl mb-6 text-emerald-400 group-hover:text-emerald-300 transition"></i>
                    <h3 class="text-2xl font-bold headline uppercase tracking-widest mb-2">Call Direct</h3>
                    <p class="text-lg text-slate-300 group-hover:text-white font-sans">+1 (613) 324-4412</p>
                </a>
            </div>

            <div class="flex justify-center space-x-8">
                <a href="https://twitter.com/JJJuraid" target="_blank" class="text-slate-500 hover:text-white transition text-3xl hover:scale-110 transform"><i class="fab fa-x-twitter"></i></a>
                <a href="https://youtube.com" target="_blank" class="text-slate-500 hover:text-red-600 transition text-3xl hover:scale-110 transform"><i class="fab fa-youtube"></i></a>
            </div>
            
            <p class="mt-16 text-xs text-slate-600 uppercase tracking-widest font-bold">&copy; 2025 Jasem Aljuraid. All Rights Reserved.</p>
        </div>
    </footer>

</body>
</html>
