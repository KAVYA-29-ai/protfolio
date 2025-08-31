# protfolio
my protfolio





<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kavya Rajput - AI Innovator & Data Wizard</title>
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Framer Motion -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/framer-motion/10.16.4/framer-motion.js"></script>
    
    <!-- Lucide React Icons -->
    <script type="module">
        import { createIcons, ChevronDown, Github, ExternalLink, X, MessageCircle, Mail, Phone, MapPin, Calendar, Award, Code, Database, BarChart3, PenTool, Cloud, Bot, Sparkles, Zap, Star, Layers, Cpu, Target, Brain, Eye, Users, TrendingUp, Rocket, Heart, Coffee, Music, ArrowRight, ArrowUp, Globe, Linkedin, Twitter, Instagram, Play, Pause, Volume2, Minimize2 } from 'https://unpkg.com/lucide@latest/dist/esm/lucide.js';
        createIcons();
    </script>
    
    <style>
        .animate-gradient-x {
            animation: gradient-x 15s ease infinite;
            background-size: 200% 200%;
        }
        
        @keyframes gradient-x {
            0%, 100% {
                background-position: 0% 50%;
            }
            50% {
                background-position: 100% 50%;
            }
        }
        
        .line-clamp-2 {
            display: -webkit-box;
            -webkit-line-clamp: 2;
            -webkit-box-orient: vertical;
            overflow: hidden;
        }
        
        .line-clamp-3 {
            display: -webkit-box;
            -webkit-line-clamp: 3;
            -webkit-box-orient: vertical;
            overflow: hidden;
        }
        
        body {
            background: linear-gradient(135deg, #0f172a 0%, #1e293b 50%, #0f172a 100%);
            color: white;
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
        }
        
        .glass-effect {
            backdrop-filter: blur(20px);
            background: rgba(255, 255, 255, 0.1);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        
        .hover-glow:hover {
            box-shadow: 0 0 30px rgba(6, 182, 212, 0.5);
        }
        
        .typewriter {
            overflow: hidden;
            border-right: 0.15em solid #06b6d4;
            white-space: nowrap;
            animation: typing 3.5s steps(40, end), blink-caret 0.75s step-end infinite;
        }
        
        @keyframes typing {
            from { width: 0 }
            to { width: 100% }
        }
        
        @keyframes blink-caret {
            from, to { border-color: transparent }
            50% { border-color: #06b6d4 }
        }
        
        .floating {
            animation: floating 3s ease-in-out infinite;
        }
        
        @keyframes floating {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
            100% { transform: translateY(0px); }
        }
        
        .scroll-smooth {
            scroll-behavior: smooth;
        }
    </style>
</head>
<body class="bg-gray-900 text-white overflow-x-hidden">
    
    <!-- Navigation -->
    <nav class="fixed top-0 left-0 right-0 z-50 glass-effect">
        <div class="max-w-7xl mx-auto px-8">
            <div class="flex justify-between items-center h-20">
                <div class="text-3xl font-black bg-gradient-to-r from-cyan-400 via-purple-400 to-pink-400 bg-clip-text text-transparent cursor-pointer">
                    KR
                </div>
                
                <div class="hidden md:flex items-center space-x-2">
                    <a href="#home" class="px-6 py-3 rounded-full font-semibold transition-all duration-300 text-gray-300 hover:text-cyan-400 hover:bg-white/5 flex items-center gap-2">
                        <span>🏠</span> Home
                    </a>
                    <a href="#about" class="px-6 py-3 rounded-full font-semibold transition-all duration-300 text-gray-300 hover:text-cyan-400 hover:bg-white/5 flex items-center gap-2">
                        <span>👋</span> About
                    </a>
                    <a href="#skills" class="px-6 py-3 rounded-full font-semibold transition-all duration-300 text-gray-300 hover:text-cyan-400 hover:bg-white/5 flex items-center gap-2">
                        <span>⚡</span> Skills
                    </a>
                    <a href="#certificates" class="px-6 py-3 rounded-full font-semibold transition-all duration-300 text-gray-300 hover:text-cyan-400 hover:bg-white/5 flex items-center gap-2">
                        <span>🏆</span> Certificates
                    </a>
                    <a href="#projects" class="px-6 py-3 rounded-full font-semibold transition-all duration-300 text-gray-300 hover:text-cyan-400 hover:bg-white/5 flex items-center gap-2">
                        <span>🚀</span> Projects
                    </a>
                    <a href="#contact" class="px-6 py-3 rounded-full font-semibold transition-all duration-300 text-gray-300 hover:text-cyan-400 hover:bg-white/5 flex items-center gap-2">
                        <span>📧</span> Contact
                    </a>
                </div>
                
                <button class="md:hidden w-12 h-12 rounded-full bg-gradient-to-r from-cyan-500/20 to-purple-500/20 border border-cyan-500/30 glass-effect flex items-center justify-center">
                    <div class="w-6 h-0.5 bg-white"></div>
                </button>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="min-h-screen flex items-center justify-between px-8 lg:px-16 relative overflow-hidden">
        <!-- Animated background elements -->
        <div class="absolute inset-0 bg-gradient-to-br from-cyan-500/5 via-purple-500/5 to-pink-500/5 rounded-full blur-3xl"></div>

        <div class="flex-1 max-w-3xl relative z-10">
            <div class="mb-6">
                <span class="inline-block px-6 py-2 bg-gradient-to-r from-cyan-500/20 to-purple-500/20 border border-cyan-500/30 rounded-full text-cyan-400 text-sm font-semibold glass-effect">
                    ✨ Portfolio 2025
                </span>
            </div>

            <h1 class="text-7xl lg:text-9xl font-black mb-8 leading-none">
                <span class="block bg-gradient-to-r from-cyan-400 via-purple-400 to-pink-400 bg-clip-text text-transparent animate-gradient-x">
                    Kavya
                </span>
                <span class="block bg-gradient-to-r from-pink-400 via-purple-400 to-cyan-400 bg-clip-text text-transparent">
                    Rajput
                </span>
            </h1>
            
            <div class="text-3xl lg:text-4xl text-gray-300 mb-10 h-16 relative">
                <span class="typewriter">AI Innovator | Data Wizard | Future Builder</span>
            </div>

            <p class="text-2xl text-gray-400 mb-12 leading-relaxed max-w-2xl">
                Transforming data into intelligence, dreams into reality. 
                Building the future with <span class="text-transparent bg-gradient-to-r from-cyan-400 to-purple-400 bg-clip-text font-bold">AI & Analytics</span>
            </p>

            <div class="flex gap-8 flex-wrap">
                <button class="px-10 py-5 bg-gradient-to-r from-cyan-600 via-blue-600 to-purple-600 text-white rounded-full font-bold text-lg hover:from-cyan-500 hover:to-purple-500 transition-all duration-300 flex items-center gap-3 relative overflow-hidden group hover-glow">
                    <i data-lucide="rocket"></i>
                    <span>Explore My Universe</span>
                </button>
                
                <button class="px-10 py-5 border-2 border-cyan-500/50 text-cyan-400 rounded-full font-bold text-lg hover:bg-cyan-500/10 transition-all duration-300 flex items-center gap-3 glass-effect">
                    <i data-lucide="message-circle"></i>
                    Let's Connect
                </button>
            </div>

            <!-- Stats Counter -->
            <div class="mt-16 grid grid-cols-3 gap-8 max-w-lg">
                <div class="text-center">
                    <div class="text-3xl font-bold bg-gradient-to-r from-cyan-400 to-purple-400 bg-clip-text text-transparent">
                        15+
                    </div>
                    <div class="text-gray-500 text-sm mt-1">Certifications</div>
                </div>
                <div class="text-center">
                    <div class="text-3xl font-bold bg-gradient-to-r from-cyan-400 to-purple-400 bg-clip-text text-transparent">
                        10+
                    </div>
                    <div class="text-gray-500 text-sm mt-1">Projects</div>
                </div>
                <div class="text-center">
                    <div class="text-3xl font-bold bg-gradient-to-r from-cyan-400 to-purple-400 bg-clip-text text-transparent">
                        100%
                    </div>
                    <div class="text-gray-500 text-sm mt-1">Passion</div>
                </div>
            </div>
        </div>

        <!-- 3D Avatar -->
        <div class="flex-1 flex justify-center items-center relative">
            <div class="relative">
                <!-- Main avatar container -->
                <div class="relative w-[500px] h-[500px] bg-gradient-to-br from-cyan-400/10 via-purple-600/10 to-pink-400/10 rounded-full flex items-center justify-center glass-effect border border-cyan-500/20">
                    <div class="text-9xl floating">🚀</div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-32 px-8 lg:px-16 relative overflow-hidden">
        <div class="max-w-6xl mx-auto">
            <h2 class="text-6xl lg:text-7xl font-black text-center mb-20 relative">
                <span class="bg-gradient-to-r from-cyan-400 via-purple-400 to-pink-400 bg-clip-text text-transparent">
                    About Me
                </span>
            </h2>

            <div class="grid lg:grid-cols-2 gap-16 items-center">
                <!-- Text Content -->
                <div class="space-y-8">
                    <p class="text-2xl text-gray-300 leading-relaxed">
                        I'm a passionate <span class="text-transparent bg-gradient-to-r from-cyan-400 to-purple-400 bg-clip-text font-bold">B.Tech student</span> with an insatiable curiosity for 
                        Artificial Intelligence, Machine Learning, and Data Analytics.
                    </p>

                    <p class="text-xl text-gray-400 leading-relaxed">
                        My mission? To bridge the gap between complex data and meaningful insights, 
                        creating intelligent solutions that transform how we understand and interact with technology.
                    </p>

                    <!-- Achievement badges -->
                    <div class="grid grid-cols-2 gap-4">
                        <div class="bg-gradient-to-r from-red-500 to-pink-500 p-4 rounded-2xl text-white font-semibold flex items-center gap-3 glass-effect">
                            <i data-lucide="target"></i>
                            <span>Problem Solver</span>
                        </div>
                        <div class="bg-gradient-to-r from-blue-500 to-cyan-500 p-4 rounded-2xl text-white font-semibold flex items-center gap-3 glass-effect">
                            <i data-lucide="brain"></i>
                            <span>AI Enthusiast</span>
                        </div>
                        <div class="bg-gradient-to-r from-green-500 to-emerald-500 p-4 rounded-2xl text-white font-semibold flex items-center gap-3 glass-effect">
                            <i data-lucide="trending-up"></i>
                            <span>Data Driven</span>
                        </div>
                        <div class="bg-gradient-to-r from-purple-500 to-pink-500 p-4 rounded-2xl text-white font-semibold flex items-center gap-3 glass-effect">
                            <i data-lucide="heart"></i>
                            <span>Innovation Lover</span>
                        </div>
                    </div>
                </div>

                <!-- Interactive Info Cards -->
                <div class="space-y-6">
                    <div class="bg-gray-800/80 glass-effect rounded-2xl p-6 hover:border-cyan-500/50 transition-all duration-300 group">
                        <div class="flex items-center gap-4">
                            <div class="w-14 h-14 rounded-2xl bg-gradient-to-r from-cyan-500 to-blue-500 flex items-center justify-center">
                                <i data-lucide="calendar" class="text-white"></i>
                            </div>
                            <div>
                                <h3 class="text-xl font-bold text-white mb-1 group-hover:text-cyan-400 transition-colors">
                                    Current Status
                                </h3>
                                <p class="text-gray-400">B.Tech Student - Pursuing Excellence</p>
                            </div>
                        </div>
                    </div>

                    <div class="bg-gray-800/80 glass-effect rounded-2xl p-6 hover:border-cyan-500/50 transition-all duration-300 group">
                        <div class="flex items-center gap-4">
                            <div class="w-14 h-14 rounded-2xl bg-gradient-to-r from-purple-500 to-pink-500 flex items-center justify-center">
                                <i data-lucide="map-pin" class="text-white"></i>
                            </div>
                            <div>
                                <h3 class="text-xl font-bold text-white mb-1 group-hover:text-cyan-400 transition-colors">
                                    Location
                                </h3>
                                <p class="text-gray-400">India - Building Global Solutions</p>
                            </div>
                        </div>
                    </div>

                    <div class="bg-gray-800/80 glass-effect rounded-2xl p-6 hover:border-cyan-500/50 transition-all duration-300 group">
                        <div class="flex items-center gap-4">
                            <div class="w-14 h-14 rounded-2xl bg-gradient-to-r from-yellow-500 to-orange-500 flex items-center justify-center">
                                <i data-lucide="zap" class="text-white"></i>
                            </div>
                            <div>
                                <h3 class="text-xl font-bold text-white mb-1 group-hover:text-cyan-400 transition-colors">
                                    Specialization
                                </h3>
                                <p class="text-gray-400">AI/ML - Future Technology</p>
                            </div>
                        </div>
                    </div>

                    <div class="bg-gray-800/80 glass-effect rounded-2xl p-6 hover:border-cyan-500/50 transition-all duration-300 group">
                        <div class="flex items-center gap-4">
                            <div class="w-14 h-14 rounded-2xl bg-gradient-to-r from-green-500 to-emerald-500 flex items-center justify-center">
                                <i data-lucide="bar-chart-3" class="text-white"></i>
                            </div>
                            <div>
                                <h3 class="text-xl font-bold text-white mb-1 group-hover:text-cyan-400 transition-colors">
                                    Expertise
                                </h3>
                                <p class="text-gray-400">Data Analytics - Insights & Intelligence</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="py-32 px-8 lg:px-16 bg-gray-900/50 relative overflow-hidden">
        <div class="max-w-7xl mx-auto relative z-10">
            <h2 class="text-6xl lg:text-7xl font-black text-center mb-8">
                <span class="bg-gradient-to-r from-cyan-400 via-purple-400 to-pink-400 bg-clip-text text-transparent">
                    Skills & Expertise
                </span>
            </h2>

            <p class="text-2xl text-gray-400 text-center mb-20 max-w-3xl mx-auto">
                Mastering the tools that shape tomorrow's technology landscape
            </p>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- AI/ML Skill -->
                <div class="group bg-gray-800/80 glass-effect rounded-3xl p-8 text-center hover:border-cyan-500/50 transition-all duration-500 relative overflow-hidden hover-glow">
                    <div class="w-20 h-20 mx-auto mb-6 rounded-3xl bg-gradient-to-r from-cyan-500 to-blue-500 flex items-center justify-center">
                        <i data-lucide="brain" class="text-white" size="28"></i>
                    </div>
                    <h3 class="text-2xl font-bold text-white mb-3 group-hover:text-cyan-400 transition-colors">AI/ML</h3>
                    <p class="text-gray-400 mb-6 text-sm">Neural Networks & Deep Learning</p>
                    <div class="w-full bg-gray-700/50 rounded-full h-3 overflow-hidden">
                        <div class="h-3 bg-gradient-to-r from-cyan-500 to-blue-500 rounded-full" style="width: 85%"></div>
                    </div>
                    <div class="flex items-center justify-center gap-2 text-gray-500 mt-4">
                        <i data-lucide="layers" size="16"></i>
                        <span class="text-sm">8 Projects</span>
                    </div>
                </div>

                <!-- Data Analytics Skill -->
                <div class="group bg-gray-800/80 glass-effect rounded-3xl p-8 text-center hover:border-cyan-500/50 transition-all duration-500 relative overflow-hidden hover-glow">
                    <div class="w-20 h-20 mx-auto mb-6 rounded-3xl bg-gradient-to-r from-purple-500 to-pink-500 flex items-center justify-center">
                        <i data-lucide="bar-chart-3" class="text-white" size="28"></i>
                    </div>
                    <h3 class="text-2xl font-bold text-white mb-3 group-hover:text-cyan-400 transition-colors">Data Analytics</h3>
                    <p class="text-gray-400 mb-6 text-sm">Statistical Analysis & Visualization</p>
                    <div class="w-full bg-gray-700/50 rounded-full h-3 overflow-hidden">
                        <div class="h-3 bg-gradient-to-r from-purple-500 to-pink-500 rounded-full" style="width: 90%"></div>
                    </div>
                    <div class="flex items-center justify-center gap-2 text-gray-500 mt-4">
                        <i data-lucide="layers" size="16"></i>
                        <span class="text-sm">12 Projects</span>
                    </div>
                </div>

                <!-- Python Skill -->
                <div class="group bg-gray-800/80 glass-effect rounded-3xl p-8 text-center hover:border-cyan-500/50 transition-all duration-500 relative overflow-hidden hover-glow">
                    <div class="w-20 h-20 mx-auto mb-6 rounded-3xl bg-gradient-to-r from-yellow-500 to-orange-500 flex items-center justify-center">
                        <i data-lucide="code" class="text-white" size="28"></i>
                    </div>
                    <h3 class="text-2xl font-bold text-white mb-3 group-hover:text-cyan-400 transition-colors">Python</h3>
                    <p class="text-gray-400 mb-6 text-sm">Advanced Programming & Libraries</p>
                    <div class="w-full bg-gray-700/50 rounded-full h-3 overflow-hidden">
                        <div class="h-3 bg-gradient-to-r from-yellow-500 to-orange-500 rounded-full" style="width: 88%"></div>
                    </div>
                    <div class="flex items-center justify-center gap-2 text-gray-500 mt-4">
                        <i data-lucide="layers" size="16"></i>
                        <span class="text-sm">15 Projects</span>
                    </div>
                </div>

                <!-- SQL Skill -->
                <div class="group bg-gray-800/80 glass-effect rounded-3xl p-8 text-center hover:border-cyan-500/50 transition-all duration-500 relative overflow-hidden hover-glow">
                    <div class="w-20 h-20 mx-auto mb-6 rounded-3xl bg-gradient-to-r from-blue-500 to-indigo-500 flex items-center justify-center">
                        <i data-lucide="database" class="text-white" size="28"></i>
                    </div>
                    <h3 class="text-2xl font-bold text-white mb-3 group-hover:text-cyan-400 transition-colors">SQL</h3>
                    <p class="text-gray-400 mb-6 text-sm">Complex Queries & Optimization</p>
                    <div class="w-full bg-gray-700/50 rounded-full h-3 overflow-hidden">
                        <div class="h-3 bg-gradient-to-r from-blue-500 to-indigo-500 rounded-full" style="width: 82%"></div>
                    </div>
                    <div class="flex items-center justify-center gap-2 text-gray-500 mt-4">
                        <i data-lucide="layers" size="16"></i>
                        <span class="text-sm">10 Projects</span>
                    </div>
                </div>
            </div>

            <!-- Skills summary -->
            <div class="mt-20 text-center">
                <div class="inline-flex items-center gap-4 bg-gray-800/80 glass-effect border border-cyan-500/30 rounded-full px-8 py-4 hover-glow">
                    <i data-lucide="star" class="text-cyan-400"></i>
                    <span class="text-xl font-semibold text-white">
                        Average Proficiency: <span class="text-cyan-400">81%</span>
                    </span>
                    <i data-lucide="star" class="text-cyan-400"></i>
                </div>
            </div>
        </div>
    </section>

                        </div>

                        <h3 class="text-xl font-bold text-white mb-2 group-hover:text-cyan-400 transition-colors line-clamp-2">
                            Problem Solving (Intermediate)
                        </h3>
                        
                        <div class="flex items-center gap-2 mb-4">
                            <div class="w-8 h-8 rounded-full bg-gradient-to-r from-green-500 to-teal-500 flex items-center justify-center">
                                <i data-lucide="award" size="16" class="text-white"></i>
                            </div>
                            <div>
                                <p class="text-cyan-400 font-semibold text-sm">HackerRank</p>
                                <p class="text-gray-500 text-xs">Dec 05, 2024</p>
                            </div>
                        </div>

                        <div class="mb-4">
                            <p class="text-xs text-gray-500 mb-2">Skills Validated:</p>
                            <div class="flex flex-wrap gap-2">
                                <span class="px-2 py-1 bg-gray-700/50 text-gray-300 text-xs rounded-full border border-gray-600/50">
                                    Algorithms
                                </span>
                                <span class="px-2 py-1 bg-gray-700/50 text-gray-300 text-xs rounded-full border border-gray-600/50">
                                    Logic Building
                                </span>
                            </div>
                        </div>

                        <div class="border-t border-gray-700/50 pt-4">
                            <p class="text-xs text-gray-500 mb-2">Credential ID:</p>
                            <p class="text-xs text-cyan-400 font-mono">HR-PS-INT-2024</p>
                        </div>
                    </div>

                    <div class="absolute top-4 right-4 w-8 h-8 bg-green-500 rounded-full flex items-center justify-center">
                        ✓
                    </div>
                </div>

                <!-- Certificate 3 -->
                <div class="group bg-gray-800/80 glass-effect rounded-3xl overflow-hidden hover:border-cyan-500/50 transition-all duration-500 hover-glow">
                    <div class="p-6 pb-4">
                        <div class="flex items-center justify-between mb-4">
                            <div class="w-16 h-16 rounded-2xl bg-gradient-to-r from-cyan-500 to-blue-600 flex items-center justify-center text-2xl">
                                ☁️
                            </div>
                            <div class="px-3 py-1 rounded-full text-xs font-semibold bg-gradient-to-r from-cyan-500 to-blue-600 text-white">
                                Fundamentals
                            </div>
                        </div>

                        <h3 class="text-xl font-bold text-white mb-2 group-hover:text-cyan-400 transition-colors line-clamp-2">
                            Azure Fundamentals
                        </h3>
                        
                        <div class="flex items-center gap-2 mb-4">
                            <div class="w-8 h-8 rounded-full bg-gradient-to-r from-cyan-500 to-blue-600 flex items-center justify-center">
                                <i data-lucide="award" size="16" class="text-white"></i>
                            </div>
                            <div>
                                <p class="text-cyan-400 font-semibold text-sm">Microsoft</p>
                                <p class="text-gray-500 text-xs">Jan 18, 2025</p>
                            </div>
                        </div>

                        <div class="mb-4">
                            <p class="text-xs text-gray-500 mb-2">Skills Validated:</p>
                            <div class="flex flex-wrap gap-2">
                                <span class="px-2 py-1 bg-gray-700/50 text-gray-300 text-xs rounded-full border border-gray-600/50">
                                    Cloud Computing
                                </span>
                                <span class="px-2 py-1 bg-gray-700/50 text-gray-300 text-xs rounded-full border border-gray-600/50">
                                    Azure Services
                                </span>
                            </div>
                        </div>

                        <div class="border-t border-gray-700/50 pt-4">
                            <p class="text-xs text-gray-500 mb-2">Credential ID:</p>
                            <p class="text-xs text-cyan-400 font-mono">MS-AZ-900-2025</p>
                        </div>
                    </div>

                    <div class="absolute top-4 right-4 w-8 h-8 bg-green-500 rounded-full flex items-center justify-center">
                        ✓
                    </div>
                </div>
            </div>

            <!-- Call to action -->
            <div class="text-center mt-20">
                <button class="px-12 py-4 bg-gradient-to-r from-cyan-600 to-purple-600 text-white rounded-full font-bold text-lg hover:from-cyan-500 hover:to-purple-500 transition-all duration-300 flex items-center gap-3 mx-auto hover-glow">
                    <i data-lucide="external-link"></i>
                    View All Certificates
                    <i data-lucide="arrow-right"></i>
                </button>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-32 px-8 lg:px-16 bg-gray-900/50 relative overflow-hidden">
        <div class="max-w-7xl mx-auto relative z-10">
            <div class="text-center mb-16">
                <h2 class="text-6xl lg:text-7xl font-black mb-8">
                    <span class="bg-gradient-to-r from-cyan-400 via-purple-400 to-pink-400 bg-clip-text text-transparent">
                        Featured Projects
                    </span>
                </h2>
                
                <p class="text-2xl text-gray-400 max-w-4xl mx-auto mb-8">
                    Innovative solutions that push the boundaries of technology and create meaningful impact
                </p>

                <div class="flex justify-center gap-12">
                    <div class="text-center">
                        <div class="text-4xl font-bold text-cyan-400">6</div>
                        <div class="text-gray-500">Total Projects</div>
                    </div>
                    <div class="text-center">
                        <div class="text-4xl font-bold text-purple-400">3</div>
                        <div class="text-gray-500">Featured</div>
                    </div>
                    <div class="text-center">
                        <div class="text-4xl font-bold text-pink-400">4</div>
                        <div class="text-gray-500">Completed</div>
                    </div>
                </div>
            </div>

            <!-- Projects grid -->
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10">
                <!-- Project 1 -->
                <div class="group bg-gray-800/80 glass-effect rounded-3xl overflow-hidden hover:border-cyan-500/50 transition-all duration-500 cursor-pointer hover-glow">
                    <div class="h-64 bg-gradient-to-br from-cyan-500 to-blue-500 relative overflow-hidden flex items-center justify-center">
                        <div class="text-8xl opacity-60">🤖</div>
                        
                        <div class="absolute top-4 left-4 bg-gradient-to-r from-yellow-500 to-orange-500 text-white px-3 py-1 rounded-full text-sm font-bold flex items-center gap-1">
                            <i data-lucide="star" size="14"></i>
                            Featured
                        </div>

                        <div class="absolute top-4 right-4 px-3 py-1 rounded-full text-sm font-semibold bg-green-500/20 text-green-400 border border-green-500/30">
                            ✅ Complete
                        </div>
                    </div>

                    <div class="p-8">
                        <div class="flex items-center justify-between mb-4">
                            <span class="px-3 py-1 rounded-full text-xs font-semibold bg-gradient-to-r from-cyan-500 to-blue-500 text-white">
                                AI/ML
                            </span>
                            <span class="text-gray-500 text-sm">2025</span>
                        </div>

                        <h3 class="text-2xl font-bold text-white mb-4 group-hover:text-cyan-400 transition-colors">
                            AI Portfolio Generator
                        </h3>
                        
                        <p class="text-gray-400 mb-6 line-clamp-3 leading-relaxed">
                            Revolutionary AI-powered platform that transforms marketing vision into compelling case studies and winning proposals using advanced machine learning algorithms.
                        </p>
                        
                        <div class="flex flex-wrap gap-2 mb-6">
                            <span class="px-3 py-1 bg-gray-700/50 text-gray-300 text-sm rounded-full border border-gray-600/50">React</span>
                            <span class="px-3 py-1 bg-gray-700/50 text-gray-300 text-sm rounded-full border border-gray-600/50">OpenAI</span>
                            <span class="px-3 py-1 bg-gray-700/50 text-gray-300 text-sm rounded-full border border-gray-600/50">Node.js</span>
                            <span class="px-3 py-1 bg-gray-700/50 text-gray-400 text-sm rounded-full">+3 more</span>
                        </div>
                        
                        <div class="flex gap-4">
                            <button class="flex items-center gap-2 px-4 py-2 bg-cyan-600 text-white rounded-xl hover:bg-cyan-500 transition-colors text-sm font-semibold">
                                <i data-lucide="github" size="16"></i>
                                Code
                            </button>
                            <button class="flex items-center gap-2 px-4 py-2 border border-cyan-500/50 text-cyan-400 rounded-xl hover:bg-cyan-500/10 transition-colors text-sm font-semibold">
                                <i data-lucide="external-link" size="16"></i>
                                Live Demo
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Project 2 -->
                <div class="group bg-gray-800/80 glass-effect rounded-3xl overflow-hidden hover:border-cyan-500/50 transition-all duration-500 cursor-pointer hover-glow">
                    <div class="h-64 bg-gradient-to-br from-purple-500 to-pink-500 relative overflow-hidden flex items-center justify-center">
                        <div class="text-8xl opacity-60">📊</div>
                        
                        <div class="absolute top-4 left-4 bg-gradient-to-r from-yellow-500 to-orange-500 text-white px-3 py-1 rounded-full text-sm font-bold flex items-center gap-1">
                            <i data-lucide="star" size="14"></i>
                            Featured
                        </div>

                        <div class="absolute top-4 right-4 px-3 py-1 rounded-full text-sm font-semibold bg-green-500/20 text-green-400 border border-green-500/30">
                            ✅ Complete
                        </div>
                    </div>

                    <div class="p-8">
                        <div class="flex items-center justify-between mb-4">
                            <span class="px-3 py-1 rounded-full text-xs font-semibold bg-gradient-to-r from-purple-500 to-pink-500 text-white">
                                Data Analytics
                            </span>
                            <span class="text-gray-500 text-sm">2024</span>
                        </div>

                        <h3 class="text-2xl font-bold text-white mb-4 group-hover:text-cyan-400 transition-colors">
                            SentimentScope
                        </h3>
                        
                        <p class="text-gray-400 mb-6 line-clamp-3 leading-relaxed">
                            Real-time social media sentiment analysis platform using Reddit posts and Gemini AI for comprehensive emotional intelligence insights.
                        </p>
                        
                        <div class="flex flex-wrap gap-2 mb-6">
                            <span class="px-3 py-1 bg-gray-700/50 text-gray-300 text-sm rounded-full border border-gray-600/50">Python</span>
                            <span class="px-3 py-1 bg-gray-700/50 text-gray-300 text-sm rounded-full border border-gray-600/50">Transformers</span>
                            <span class="px-3 py-1 bg-gray-700/50 text-gray-300 text-sm rounded-full border border-gray-600/50">React</span>
                            <span class="px-3 py-1 bg-gray-700/50 text-gray-400 text-sm rounded-full">+3 more</span>
                        </div>
                        
                        <div class="flex gap-4">
                            <button class="flex items-center gap-2 px-4 py-2 bg-cyan-600 text-white rounded-xl hover:bg-cyan-500 transition-colors text-sm font-semibold">
                                <i data-lucide="github" size="16"></i>
                                Code
                            </button>
                            <button class="flex items-center gap-2 px-4 py-2 border border-cyan-500/50 text-cyan-400 rounded-xl hover:bg-cyan-500/10 transition-colors text-sm font-semibold">
                                <i data-lucide="external-link" size="16"></i>
                                Live Demo
                            </button>
                        </div>
                    </div>
                </div>

                <!-- Project 3 -->
                <div class="group bg-gray-800/80 glass-effect rounded-3xl overflow-hidden hover:border-cyan-500/50 transition-all duration-500 cursor-pointer hover-glow">
                    <div class="h-64 bg-gradient-to-br from-indigo-500 to-purple-500 relative overflow-hidden flex items-center justify-center">
                        <div class="text-8xl opacity-60">🌐</div>
                        
                        <div class="absolute top-4 left-4 bg-gradient-to-r from-yellow-500 to-orange-500 text-white px-3 py-1 rounded-full text-sm font-bold flex items-center gap-1">
                            <i data-lucide="star" size="14"></i>
                            Featured
                        </div>

                        <div class="absolute top-4 right-4 px-3 py-1 rounded-full text-sm font-semibold bg-orange-500/20 text-orange-400 border border-orange-500/30">
                            🔄 In Progress
                        </div>
                    </div>

                    <div class="p-8">
                        <div class="flex items-center justify-between mb-4">
                            <span class="px-3 py-1 rounded-full text-xs font-semibold bg-gradient-to-r from-indigo-500 to-purple-500 text-white">
                                IoT
                            </span>
                            <span class="text-gray-500 text-sm">2025</span>
                        </div>

                        <h3 class="text-2xl font-bold text-white mb-4 group-hover:text-cyan-400 transition-colors">
                            Smart City IoT Platform
                        </h3>
                        
                        <p class="text-gray-400 mb-6 line-clamp-3 leading-relaxed">
                            IoT-based smart city management system for traffic optimization, energy management, and environmental monitoring.
                        </p>
                        
                        <div class="flex flex-wrap gap-2 mb-6">
                            <span class="px-3 py-1 bg-gray-700/50 text-gray-300 text-sm rounded-full border border-gray-600/50">Python</span>
                            <span class="px-3 py-1 bg-gray-700/50 text-gray-300 text-sm rounded-full border border-gray-600/50">IoT</span>
                            <span class="px-3 py-1 bg-gray-700/50 text-gray-300 text-sm rounded-full border border-gray-600/50">MQTT</span>
                            <span class="px-3 py-1 bg-gray-700/50 text-gray-400
