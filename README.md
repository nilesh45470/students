<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Complete Computing Fundamentals Study Guide</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        body { font-family: 'Inter', sans-serif; }
        .gradient-bg { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); }
        .code-block { background: #1e293b; color: #e2e8f0; }
        .concept-card { transition: all 0.3s ease; }
        .concept-card:hover { transform: translateY(-2px); }
        .section-divider { border-image: linear-gradient(90deg, #667eea, #764ba2) 1; }
        @media print {
            body { font-size: 12px; }
            .no-print { display: none; }
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- Header -->
    <header class="gradient-bg text-white py-12">
        <div class="container mx-auto px-6">
            <h1 class="text-5xl font-bold mb-4 text-center">
                <i class="fas fa-laptop-code mr-4"></i>
                Computing Fundamentals Study Guide
            </h1>
            <p class="text-xl text-center opacity-90">
                Comprehensive coverage of processes, systems, networking, and programming concepts
            </p>
            <div class="flex justify-center mt-6 space-x-6">
                <span class="bg-white bg-opacity-20 px-4 py-2 rounded-full text-sm">
                    <i class="fas fa-cogs mr-2"></i>Processes & Systems
                </span>
                <span class="bg-white bg-opacity-20 px-4 py-2 rounded-full text-sm">
                    <i class="fas fa-network-wired mr-2"></i>Networking
                </span>
                <span class="bg-white bg-opacity-20 px-4 py-2 rounded-full text-sm">
                    <i class="fas fa-code mr-2"></i>Programming
                </span>
            </div>
        </div>
    </header>

    <div class="container mx-auto px-6 py-8">

        <!-- Table of Contents -->
        <div class="bg-white rounded-lg shadow-lg p-6 mb-8">
            <h2 class="text-2xl font-bold mb-4 text-gray-800">
                <i class="fas fa-list mr-3 text-blue-600"></i>Table of Contents
            </h2>
            <div class="grid md:grid-cols-3 gap-4">
                <div class="space-y-2">
                    <a href="#processes" class="block text-blue-600 hover:text-blue-800 transition-colors">
                        <i class="fas fa-play-circle mr-2"></i>1. Process & Booting
                    </a>
                    <a href="#addressing" class="block text-blue-600 hover:text-blue-800 transition-colors">
                        <i class="fas fa-map-marker-alt mr-2"></i>2. Addressing Concepts
                    </a>
                    <a href="#systems" class="block text-blue-600 hover:text-blue-800 transition-colors">
                        <i class="fas fa-sitemap mr-2"></i>3. Systems & Conditions
                    </a>
                </div>
                <div class="space-y-2">
                    <a href="#rules" class="block text-blue-600 hover:text-blue-800 transition-colors">
                        <i class="fas fa-gavel mr-2"></i>4. Rules & Instructions
                    </a>
                    <a href="#execution" class="block text-blue-600 hover:text-blue-800 transition-colors">
                        <i class="fas fa-rocket mr-2"></i>5. Program Execution
                    </a>
                    <a href="#protocols" class="block text-blue-600 hover:text-blue-800 transition-colors">
                        <i class="fas fa-handshake mr-2"></i>6. Protocols & Framework
                    </a>
                </div>
                <div class="space-y-2">
                    <a href="#networking" class="block text-blue-600 hover:text-blue-800 transition-colors">
                        <i class="fas fa-globe mr-2"></i>7. Networking
                    </a>
                    <a href="#communication" class="block text-blue-600 hover:text-blue-800 transition-colors">
                        <i class="fas fa-comments mr-2"></i>8. Communication
                    </a>
                    <a href="#postal" class="block text-blue-600 hover:text-blue-800 transition-colors">
                        <i class="fas fa-mail-bulk mr-2"></i>9. Postal System Analogy
                    </a>
                </div>
            </div>
        </div>

        <!-- Section 1: Process & Booting -->
        <section id="processes" class="mb-12">
            <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                <div class="gradient-bg text-white p-6">
                    <h2 class="text-3xl font-bold">
                        <i class="fas fa-play-circle mr-3"></i>1. Process & Booting
                    </h2>
                    <p class="mt-2 opacity-90">Understanding fundamental computing processes and system startup</p>
                </div>
                
                <div class="p-6">
                    <!-- Q1: What is a process? -->
                    <div class="concept-card bg-blue-50 border-l-4 border-blue-500 p-6 mb-6 rounded-r-lg">
                        <h3 class="text-xl font-semibold text-blue-800 mb-3">
                            <i class="fas fa-question-circle mr-2"></i>Q1. What is a process?
                        </h3>
                        
                        <div class="mb-4">
                            <h4 class="font-semibold text-gray-700 mb-2">Definition:</h4>
                            <p class="text-gray-600 bg-white p-3 rounded border-l-2 border-blue-300">
                                A process is a defined sequence of steps taken to achieve a specific goal in computing or real life.
                            </p>
                        </div>

                        <div class="mb-4">
                            <h4 class="font-semibold text-gray-700 mb-2">Details:</h4>
                            <div class="grid md:grid-cols-2 gap-4">
                                <div class="bg-white p-4 rounded border">
                                    <h5 class="font-medium text-gray-800 mb-2">
                                        <i class="fas fa-desktop mr-2 text-blue-500"></i>In Computing
                                    </h5>
                                    <p class="text-gray-600 text-sm">A process is a program in execution, managed by the operating system with its own memory space, CPU time, and system resources.</p>
                                </div>
                                <div class="bg-white p-4 rounded border">
                                    <h5 class="font-medium text-gray-800 mb-2">
                                        <i class="fas fa-users mr-2 text-green-500"></i>In Real Life
                                    </h5>
                                    <p class="text-gray-600 text-sm">An ordered set of actions that transforms inputs into meaningful outputs, like cooking a recipe or following assembly instructions.</p>
                                </div>
                            </div>
                        </div>

                        <div class="bg-yellow-50 border border-yellow-200 p-4 rounded">
                            <h4 class="font-semibold text-yellow-800 mb-2">
                                <i class="fas fa-lightbulb mr-2"></i>Key Insight
                            </h4>
                            <p class="text-yellow-700">Without processes, both computers and humans cannot organize tasks into meaningful order. They provide structure, predictability, and error prevention.</p>
                        </div>
                    </div>

                    <!-- Q2: Why is process emphasized? -->
                    <div class="concept-card bg-green-50 border-l-4 border-green-500 p-6 mb-6 rounded-r-lg">
                        <h3 class="text-xl font-semibold text-green-800 mb-3">
                            <i class="fas fa-question-circle mr-2"></i>Q2. Why is the concept of process emphasized?
                        </h3>
                        
                        <div class="grid md:grid-cols-3 gap-4 mb-4">
                            <div class="text-center">
                                <div class="bg-green-100 w-16 h-16 mx-auto rounded-full flex items-center justify-center mb-2">
                                    <i class="fas fa-bullseye text-green-600 text-2xl"></i>
                                </div>
                                <h4 class="font-medium text-green-800">Precision</h4>
                                <p class="text-sm text-green-600">Exact, unambiguous steps</p>
                            </div>
                            <div class="text-center">
                                <div class="bg-green-100 w-16 h-16 mx-auto rounded-full flex items-center justify-center mb-2">
                                    <i class="fas fa-check-circle text-green-600 text-2xl"></i>
                                </div>
                                <h4 class="font-medium text-green-800">Definiteness</h4>
                                <p class="text-sm text-green-600">Clear, well-defined outcomes</p>
                            </div>
                            <div class="text-center">
                                <div class="bg-green-100 w-16 h-16 mx-auto rounded-full flex items-center justify-center mb-2">
                                    <i class="fas fa-trophy text-green-600 text-2xl"></i>
                                </div>
                                <h4 class="font-medium text-green-800">Meaningful Results</h4>
                                <p class="text-sm text-green-600">Purposeful, valuable outputs</p>
                            </div>
                        </div>

                        <div class="bg-white p-4 rounded border">
                            <h4 class="font-semibold text-gray-700 mb-2">Examples of Process Importance:</h4>
                            <ul class="space-y-2">
                                <li class="flex items-start">
                                    <i class="fas fa-computer text-blue-500 mr-2 mt-1"></i>
                                    <span class="text-gray-600"><strong>Computers:</strong> Follow strict algorithmic processes for accuracy and reliability</span>
                                </li>
                                <li class="flex items-start">
                                    <i class="fas fa-user text-purple-500 mr-2 mt-1"></i>
                                    <span class="text-gray-600"><strong>Humans:</strong> Use processes for efficiency, consistency, and quality control</span>
                                </li>
                                <li class="flex items-start">
                                    <i class="fas fa-industry text-orange-500 mr-2 mt-1"></i>
                                    <span class="text-gray-600"><strong>Manufacturing:</strong> Assembly lines ensure consistent product quality</span>
                                </li>
                            </ul>
                        </div>
                    </div>

                    <!-- Q3: Booting Process -->
                    <div class="concept-card bg-purple-50 border-l-4 border-purple-500 p-6 mb-6 rounded-r-lg">
                        <h3 class="text-xl font-semibold text-purple-800 mb-3">
                            <i class="fas fa-question-circle mr-2"></i>Q3. Explain the Booting process of a computer
                        </h3>
                        
                        <div class="mb-4">
                            <h4 class="font-semibold text-gray-700 mb-2">Definition:</h4>
                            <p class="text-gray-600 bg-white p-3 rounded border-l-2 border-purple-300">
                                Booting is the process of starting a computer and loading the operating system into memory, transforming the hardware from a powered-off state to a fully functional computing environment.
                            </p>
                        </div>

                        <!-- Visual Booting Process -->
                        <div class="mb-6">
                            <h4 class="font-semibold text-gray-700 mb-3">Boot Process Flowchart:</h4>
                            <div class="bg-white p-4 rounded border">
                                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/bf/Flow-diagram-computer-booting-sequences.svg/1200px-Flow-diagram-computer-booting-sequences.svg.png" 
                                     alt="Computer Booting Process Flowchart" 
                                     class="w-full max-w-2xl mx-auto rounded shadow">
                            </div>
                        </div>

                        <!-- Detailed Steps -->
                        <div class="space-y-4">
                            <h4 class="font-semibold text-gray-700 mb-3">Detailed Boot Steps:</h4>
                            
                            <div class="grid gap-4">
                                <div class="flex items-start bg-white p-4 rounded border">
                                    <div class="bg-red-100 text-red-600 w-8 h-8 rounded-full flex items-center justify-center mr-3 font-bold">1</div>
                                    <div>
                                        <h5 class="font-medium text-gray-800 mb-1">Power ON</h5>
                                        <p class="text-gray-600 text-sm">Electrical power is supplied to motherboard and components. Power supply unit (PSU) converts AC to DC power.</p>
                                    </div>
                                </div>

                                <div class="flex items-start bg-white p-4 rounded border">
                                    <div class="bg-orange-100 text-orange-600 w-8 h-8 rounded-full flex items-center justify-center mr-3 font-bold">2</div>
                                    <div>
                                        <h5 class="font-medium text-gray-800 mb-1">POST (Power-On Self Test)</h5>
                                        <p class="text-gray-600 text-sm">BIOS/UEFI performs hardware diagnostics: checks CPU, RAM, storage devices, and basic hardware functionality.</p>
                                    </div>
                                </div>

                                <div class="flex items-start bg-white p-4 rounded border">
                                    <div class="bg-yellow-100 text-yellow-600 w-8 h-8 rounded-full flex items-center justify-center mr-3 font-bold">3</div>
                                    <div>
                                        <h5 class="font-medium text-gray-800 mb-1">BIOS/UEFI Initialization</h5>
                                        <p class="text-gray-600 text-sm">Basic Input/Output System loads and initializes hardware components, sets up system configuration.</p>
                                    </div>
                                </div>

                                <div class="flex items-start bg-white p-4 rounded border">
                                    <div class="bg-green-100 text-green-600 w-8 h-8 rounded-full flex items-center justify-center mr-3 font-bold">4</div>
                                    <div>
                                        <h5 class="font-medium text-gray-800 mb-1">Bootloader Execution</h5>
                                        <p class="text-gray-600 text-sm">BIOS finds and loads the bootloader from the Master Boot Record (MBR) or EFI System Partition (ESP).</p>
                                    </div>
                                </div>

                                <div class="flex items-start bg-white p-4 rounded border">
                                    <div class="bg-blue-100 text-blue-600 w-8 h-8 rounded-full flex items-center justify-center mr-3 font-bold">5</div>
                                    <div>
                                        <h5 class="font-medium text-gray-800 mb-1">OS Kernel Loading</h5>
                                        <p class="text-gray-600 text-sm">Bootloader locates and loads the operating system kernel into RAM, initializes core system services.</p>
                                    </div>
                                </div>

                                <div class="flex items-start bg-white p-4 rounded border">
                                    <div class="bg-purple-100 text-purple-600 w-8 h-8 rounded-full flex items-center justify-center mr-3 font-bold">6</div>
                                    <div>
                                        <h5 class="font-medium text-gray-800 mb-1">System Ready</h5>
                                        <p class="text-gray-600 text-sm">OS takes control, loads drivers, starts services, and presents user interface (desktop/login screen).</p>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- BIOS vs UEFI Comparison -->
                        <div class="mt-6 bg-white p-4 rounded border">
                            <h4 class="font-semibold text-gray-700 mb-3">BIOS vs UEFI Comparison:</h4>
                            <div class="grid md:grid-cols-2 gap-4">
                                <div class="border rounded p-3">
                                    <h5 class="font-medium text-blue-600 mb-2">
                                        <i class="fas fa-microchip mr-2"></i>BIOS (Legacy)
                                    </h5>
                                    <ul class="text-sm text-gray-600 space-y-1">
                                        <li>• 16-bit mode operation</li>
                                        <li>• Limited to 2TB disk size</li>
                                        <li>• Text-based interface</li>
                                        <li>• Slower boot times</li>
                                        <li>• MBR partition table</li>
                                    </ul>
                                </div>
                                <div class="border rounded p-3">
                                    <h5 class="font-medium text-green-600 mb-2">
                                        <i class="fas fa-rocket mr-2"></i>UEFI (Modern)
                                    </h5>
                                    <ul class="text-sm text-gray-600 space-y-1">
                                        <li>• 32/64-bit mode operation</li>
                                        <li>• Supports >2TB disk size</li>
                                        <li>• Graphical interface</li>
                                        <li>• Faster boot times</li>
                                        <li>• GPT partition table</li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 2: Addressing Concepts -->
        <section id="addressing" class="mb-12">
            <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                <div class="bg-gradient-to-r from-indigo-500 to-purple-600 text-white p-6">
                    <h2 class="text-3xl font-bold">
                        <i class="fas fa-map-marker-alt mr-3"></i>2. Addressing Concepts
                    </h2>
                    <p class="mt-2 opacity-90">Understanding how identification and location systems work</p>
                </div>
                
                <div class="p-6">
                    <!-- Q4: Significance of addressing -->
                    <div class="concept-card bg-indigo-50 border-l-4 border-indigo-500 p-6 mb-6 rounded-r-lg">
                        <h3 class="text-xl font-semibold text-indigo-800 mb-3">
                            <i class="fas fa-question-circle mr-2"></i>Q4. What is the significance of addressing?
                        </h3>
                        
                        <div class="mb-4">
                            <h4 class="font-semibold text-gray-700 mb-2">Definition:</h4>
                            <p class="text-gray-600 bg-white p-3 rounded border-l-2 border-indigo-300">
                                Address is an identification system used to locate a person, device, or data uniquely within a larger network or system.
                            </p>
                        </div>

                        <div class="grid md:grid-cols-2 gap-6 mb-4">
                            <div class="bg-white p-4 rounded border">
                                <h5 class="font-medium text-gray-800 mb-3">
                                    <i class="fas fa-home mr-2 text-green-500"></i>Real Life Addressing
                                </h5>
                                <div class="space-y-2 text-sm">
                                    <div class="flex items-center">
                                        <i class="fas fa-map-pin mr-2 text-red-400"></i>
                                        <span><strong>Postal:</strong> Street, City, PIN Code</span>
                                    </div>
                                    <div class="flex items-center">
                                        <i class="fas fa-phone mr-2 text-blue-400"></i>
                                        <span><strong>Phone:</strong> Country + Area + Number</span>
                                    </div>
                                    <div class="flex items-center">
                                        <i class="fas fa-id-card mr-2 text-purple-400"></i>
                                        <span><strong>Personal:</strong> SSN, Passport, ID</span>
                                    </div>
                                </div>
                            </div>
                            <div class="bg-white p-4 rounded border">
                                <h5 class="font-medium text-gray-800 mb-3">
                                    <i class="fas fa-desktop mr-2 text-blue-500"></i>Computing Addressing
                                </h5>
                                <div class="space-y-2 text-sm">
                                    <div class="flex items-center">
                                        <i class="fas fa-globe mr-2 text-green-400"></i>
                                        <span><strong>IP:</strong> 192.168.1.1</span>
                                    </div>
                                    <div class="flex items-center">
                                        <i class="fas fa-memory mr-2 text-orange-400"></i>
                                        <span><strong>Memory:</strong> 0x1A2B3C4D</span>
                                    </div>
                                    <div class="flex items-center">
                                        <i class="fas fa-envelope mr-2 text-red-400"></i>
                                        <span><strong>Email:</strong> user@domain.com</span>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <div class="bg-yellow-50 border border-yellow-200 p-4 rounded">
                            <h4 class="font-semibold text-yellow-800 mb-2">
                                <i class="fas fa-exclamation-triangle mr-2"></i>Critical Point
                            </h4>
                            <p class="text-yellow-700">Without addressing systems, delivery (postal mail or data packets) would be impossible. Every communication system requires a method to identify source and destination.</p>
                        </div>
                    </div>

                    <!-- Q5: Address format -->
                    <div class="concept-card bg-purple-50 border-l-4 border-purple-500 p-6 mb-6 rounded-r-lg">
                        <h3 class="text-xl font-semibold text-purple-800 mb-3">
                            <i class="fas fa-question-circle mr-2"></i>Q5. Why is address format numeric or alphabetical?
                        </h3>
                        
                        <div class="mb-4">
                            <h4 class="font-semibold text-gray-700 mb-2">Core Principle:</h4>
                            <p class="text-gray-600 bg-white p-3 rounded border-l-2 border-purple-300">
                                Addresses must be representable in a definite, unambiguous system that both humans and machines can understand and process efficiently.
                            </p>
                        </div>

                        <div class="grid md:grid-cols-2 gap-4 mb-4">
                            <div class="bg-white p-4 rounded border">
                                <h5 class="font-medium text-blue-600 mb-2">
                                    <i class="fas fa-calculator mr-2"></i>Numeric Addresses
                                </h5>
                                <div class="space-y-2">
                                    <p class="text-sm text-gray-600"><strong>Advantages:</strong></p>
                                    <ul class="text-sm text-gray-600 ml-4 space-y-1">
                                        <li>• Precise and unambiguous</li>
                                        <li>• Efficient for machines</li>
                                        <li>• Easy to sort and compare</li>
                                        <li>• Compact representation</li>
                                    </ul>
                                    <p class="text-sm text-blue-600 font-medium">Examples: IP addresses, ZIP codes, memory addresses</p>
                                </div>
                            </div>
                            <div class="bg-white p-4 rounded border">
                                <h5 class="font-medium text-green-600 mb-2">
                                    <i class="fas fa-font mr-2"></i>Alphabetical Addresses
                                </h5>
                                <div class="space-y-2">
                                    <p class="text-sm text-gray-600"><strong>Advantages:</strong></p>
                                    <ul class="text-sm text-gray-600 ml-4 space-y-1">
                                        <li>• Human-readable and memorable</li>
                                        <li>• Descriptive and meaningful</li>
                                        <li>• Cultural and linguistic context</li>
                                        <li>• Easier to communicate verbally</li>
                                    </ul>
                                    <p class="text-sm text-green-600 font-medium">Examples: Domain names, street names, email addresses</p>
                                </div>
                            </div>
                        </div>

                        <!-- Address Format Examples -->
                        <div class="bg-white p-4 rounded border">
                            <h4 class="font-semibold text-gray-700 mb-3">Real-World Address Format Examples:</h4>
                            <div class="grid md:grid-cols-3 gap-4">
                                <div class="text-center">
                                    <div class="bg-blue-100 p-3 rounded mb-2">
                                        <i class="fas fa-globe text-blue-600 text-2xl"></i>
                                    </div>
                                    <h6 class="font-medium">IP Address</h6>
                                    <code class="text-sm bg-gray-100 px-2 py-1 rounded">192.168.1.100</code>
                                    <p class="text-xs text-gray-500 mt-1">Pure numeric for machine efficiency</p>
                                </div>
                                <div class="text-center">
                                    <div class="bg-green-100 p-3 rounded mb-2">
                                        <i class="fas fa-link text-green-600 text-2xl"></i>
                                    </div>
                                    <h6 class="font-medium">Domain Name</h6>
                                    <code class="text-sm bg-gray-100 px-2 py-1 rounded">www.google.com</code>
                                    <p class="text-xs text-gray-500 mt-1">Alphabetic for human readability</p>
                                </div>
                                <div class="text-center">
                                    <div class="bg-purple-100 p-3 rounded mb-2">
                                        <i class="fas fa-home text-purple-600 text-2xl"></i>
                                    </div>
                                    <h6 class="font-medium">Postal Address</h6>
                                    <code class="text-sm bg-gray-100 px-2 py-1 rounded">123 Main St, NYC 10001</code>
                                    <p class="text-xs text-gray-500 mt-1">Mixed format for versatility</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 3: Systems & Conditions -->
        <section id="systems" class="mb-12">
            <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                <div class="bg-gradient-to-r from-green-500 to-teal-600 text-white p-6">
                    <h2 class="text-3xl font-bold">
                        <i class="fas fa-sitemap mr-3"></i>3. Systems & Conditions
                    </h2>
                    <p class="mt-2 opacity-90">Understanding organized structures and their operating rules</p>
                </div>
                
                <div class="p-6">
                    <!-- Q6: What is a system? -->
                    <div class="concept-card bg-green-50 border-l-4 border-green-500 p-6 mb-6 rounded-r-lg">
                        <h3 class="text-xl font-semibold text-green-800 mb-3">
                            <i class="fas fa-question-circle mr-2"></i>Q6. What is a system? Are system and conditions the same?
                        </h3>
                        
                        <div class="mb-4">
                            <h4 class="font-semibold text-gray-700 mb-2">System Definition:</h4>
                            <p class="text-gray-600 bg-white p-3 rounded border-l-2 border-green-300">
                                A system is an organized set of interconnected components working together cohesively to achieve a specific purpose or goal.
                            </p>
                        </div>

                        <div class="mb-4">
                            <h4 class="font-semibold text-gray-700 mb-2">System vs. Conditions:</h4>
                            <div class="grid md:grid-cols-2 gap-4">
                                <div class="bg-blue-50 p-4 rounded border border-blue-200">
                                    <h5 class="font-medium text-blue-800 mb-2">
                                        <i class="fas fa-cogs mr-2"></i>System
                                    </h5>
                                    <ul class="text-sm text-blue-700 space-y-1">
                                        <li>• The complete organized structure</li>
                                        <li>• Contains multiple components</li>
                                        <li>• Has defined boundaries</li>
                                        <li>• Produces outputs from inputs</li>
                                        <li>• Examples: Computer, ecosystem, organization</li>
                                    </ul>
                                </div>
                                <div class="bg-orange-50 p-4 rounded border border-orange-200">
                                    <h5 class="font-medium text-orange-800 mb-2">
                                        <i class="fas fa-list-check mr-2"></i>Conditions
                                    </h5>
                                    <ul class="text-sm text-orange-700 space-y-1">
                                        <li>• Rules that govern system behavior</li>
                                        <li>• Define operational parameters</li>
                                        <li>• Control system responses</li>
                                        <li>• Can be changed without changing system</li>
                                        <li>• Examples: if/else rules, policies, constraints</li>
                                    </ul>
                                </div>
                            </div>
                        </div>

                        <!-- System Examples -->
                        <div class="bg-white p-4 rounded border">
                            <h4 class="font-semibold text-gray-700 mb-3">System Examples with Their Conditions:</h4>
                            <div class="space-y-3">
                                <div class="flex items-start p-3 bg-gray-50 rounded">
                                    <i class="fas fa-desktop text-blue-500 mr-3 mt-1"></i>
                                    <div>
                                        <h6 class="font-medium">Computer System</h6>
                                        <p class="text-sm text-gray-600">Components: CPU, RAM, Storage, OS</p>
                                        <p class="text-sm text-blue-600">Conditions: Memory limits, processing priority, access permissions</p>
                                    </div>
                                </div>
                                <div class="flex items-start p-3 bg-gray-50 rounded">
                                    <i class="fas fa-leaf text-green-500 mr-3 mt-1"></i>
                                    <div>
                                        <h6 class="font-medium">Ecosystem</h6>
                                        <p class="text-sm text-gray-600">Components: Plants, animals, environment, resources</p>
                                        <p class="text-sm text-green-600">Conditions: Temperature range, water availability, food chains</p>
                                    </div>
                                </div>
                                <div class="flex items-start p-3 bg-gray-50 rounded">
                                    <i class="fas fa-building text-purple-500 mr-3 mt-1"></i>
                                    <div>
                                        <h6 class="font-medium">Organization</h6>
                                        <p class="text-sm text-gray-600">Components: People, departments, resources, processes</p>
                                        <p class="text-sm text-purple-600">Conditions: Policies, budgets, deadlines, performance metrics</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Q7: Contradictory conditions -->
                    <div class="concept-card bg-red-50 border-l-4 border-red-500 p-6 mb-6 rounded-r-lg">
                        <h3 class="text-xl font-semibold text-red-800 mb-3">
                            <i class="fas fa-question-circle mr-2"></i>Q7. What are contradictory conditions?
                        </h3>
                        
                        <div class="mb-4">
                            <h4 class="font-semibold text-gray-700 mb-2">Definition:</h4>
                            <p class="text-gray-600 bg-white p-3 rounded border-l-2 border-red-300">
                                Contradictory conditions are rules or requirements that oppose each other and cannot both be true or satisfied simultaneously within the same system.
                            </p>
                        </div>

                        <div class="grid md:grid-cols-2 gap-4 mb-4">
                            <div class="bg-white p-4 rounded border">
                                <h5 class="font-medium text-red-600 mb-2">
                                    <i class="fas fa-exclamation-triangle mr-2"></i>Examples of Contradictory Conditions
                                </h5>
                                <div class="space-y-2 text-sm">
                                    <div class="p-2 bg-red-50 rounded">
                                        <strong>System Rule 1:</strong> "System must always be ON"<br>
                                        <strong>System Rule 2:</strong> "System must always be OFF"
                                    </div>
                                    <div class="p-2 bg-red-50 rounded">
                                        <strong>Access Rule 1:</strong> "All users have admin access"<br>
                                        <strong>Access Rule 2:</strong> "No users have admin access"
                                    </div>
                                    <div class="p-2 bg-red-50 rounded">
                                        <strong>Traffic Rule 1:</strong> "Always turn left at intersection"<br>
                                        <strong>Traffic Rule 2:</strong> "Always turn right at intersection"
                                    </div>
                                </div>
                            </div>
                            <div class="bg-white p-4 rounded border">
                                <h5 class="font-medium text-blue-600 mb-2">
                                    <i class="fas fa-tools mr-2"></i>Resolution Strategies
                                </h5>
                                <ul class="text-sm text-gray-600 space-y-1">
                                    <li><strong>Priority-based:</strong> Assign priority levels to conditions</li>
                                    <li><strong>Context-based:</strong> Apply different rules in different contexts</li>
                                    <li><strong>Time-based:</strong> Rules apply at different times</li>
                                    <li><strong>Conditional logic:</strong> Use if-then-else structures</li>
                                    <li><strong>Default behavior:</strong> Define fallback actions</li>
                                </ul>
                            </div>
                        </div>

                        <div class="bg-yellow-50 border border-yellow-200 p-4 rounded">
                            <h4 class="font-semibold text-yellow-800 mb-2">
                                <i class="fas fa-lightbulb mr-2"></i>Impact of Contradictory Conditions
                            </h4>
                            <p class="text-yellow-700">Contradictory conditions can cause system failures, infinite loops, deadlocks, or unpredictable behavior. Proper system design must identify and resolve such conflicts before implementation.</p>
                        </div>
                    </div>

                    <!-- Q8: Applications and rules of systems -->
                    <div class="concept-card bg-teal-50 border-l-4 border-teal-500 p-6 mb-6 rounded-r-lg">
                        <h3 class="text-xl font-semibold text-teal-800 mb-3">
                            <i class="fas fa-question-circle mr-2"></i>Q8. What are the applications and rules of systems?
                        </h3>
                        
                        <div class="mb-6">
                            <h4 class="font-semibold text-gray-700 mb-3">System Applications:</h4>
                            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-4">
                                <div class="text-center p-4 bg-white rounded border">
                                    <i class="fas fa-desktop text-blue-500 text-3xl mb-2"></i>
                                    <h6 class="font-medium">Computing</h6>
                                    <p class="text-xs text-gray-500">Operating systems, networks, databases</p>
                                </div>
                                <div class="text-center p-4 bg-white rounded border">
                                    <i class="fas fa-dna text-green-500 text-3xl mb-2"></i>
                                    <h6 class="font-medium">Biology</h6>
                                    <p class="text-xs text-gray-500">Nervous system, circulatory system</p>
                                </div>
                                <div class="text-center p-4 bg-white rounded border">
                                    <i class="fas fa-building text-purple-500 text-3xl mb-2"></i>
                                    <h6 class="font-medium">Organizations</h6>
                                    <p class="text-xs text-gray-500">Management, workflows, hierarchies</p>
                                </div>
                                <div class="text-center p-4 bg-white rounded border">
                                    <i class="fas fa-users text-orange-500 text-3xl mb-2"></i>
                                    <h6 class="font-medium">Society</h6>
                                    <p class="text-xs text-gray-500">Government, law, economy</p>
                                </div>
                            </div>
                        </div>

                        <div class="bg-white p-4 rounded border">
                            <h4 class="font-semibold text-gray-700 mb-3">Universal System Rules:</h4>
                            <div class="space-y-3">
                                <div class="flex items-center p-3 bg-blue-50 rounded">
                                    <i class="fas fa-arrow-right text-blue-500 mr-3"></i>
                                    <div>
                                        <h6 class="font-medium">Input → Process → Output</h6>
                                        <p class="text-sm text-gray-600">Every system transforms inputs through processes to produce outputs</p>
                                    </div>
                                </div>
                                <div class="flex items-center p-3 bg-green-50 rounded">
                                    <i class="fas fa-border-all text-green-500 mr-3"></i>
                                    <div>
                                        <h6 class="font-medium">System Boundaries</h6>
                                        <p class="text-sm text-gray-600">Clear definition of what's inside vs. outside the system</p>
                                    </div>
                                </div>
                                <div class="flex items-center p-3 bg-purple-50 rounded">
                                    <i class="fas fa-recycle text-purple-500 mr-3"></i>
                                    <div>
                                        <h6 class="font-medium">Feedback Loops</h6>
                                        <p class="text-sm text-gray-600">Output information that influences future inputs and behavior</p>
                                    </div>
                                </div>
                                <div class="flex items-center p-3 bg-orange-50 rounded">
                                    <i class="fas fa-balance-scale text-orange-500 mr-3"></i>
                                    <div>
                                        <h6 class="font-medium">Equilibrium</h6>
                                        <p class="text-sm text-gray-600">Systems tend toward stable states and resist change</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 4: Rules, Laws, and Instructions -->
        <section id="rules" class="mb-12">
            <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                <div class="bg-gradient-to-r from-red-500 to-pink-600 text-white p-6">
                    <h2 class="text-3xl font-bold">
                        <i class="fas fa-gavel mr-3"></i>4. Rules, Laws, and Instructions
                    </h2>
                    <p class="mt-2 opacity-90">Understanding different types of directives and their enforcement</p>
                </div>
                
                <div class="p-6">
                    <!-- Comprehensive comparison chart -->
                    <div class="bg-white p-6 rounded border mb-6">
                        <h3 class="text-xl font-semibold text-gray-800 mb-4">
                            <i class="fas fa-table mr-2"></i>Complete Comparison: Rules, Laws, Instructions & Guidelines
                        </h3>
                        <div class="overflow-x-auto">
                            <table class="w-full border-collapse border border-gray-300">
                                <thead>
                                    <tr class="bg-gray-100">
                                        <th class="border border-gray-300 p-3 text-left font-semibold">Aspect</th>
                                        <th class="border border-gray-300 p-3 text-center font-semibold text-blue-600">Rules</th>
                                        <th class="border border-gray-300 p-3 text-center font-semibold text-red-600">Laws</th>
                                        <th class="border border-gray-300 p-3 text-center font-semibold text-green-600">Instructions</th>
                                        <th class="border border-gray-300 p-3 text-center font-semibold text-purple-600">Guidelines</th>
                                    </tr>
                                </thead>
                                <tbody>
                                    <tr>
                                        <td class="border border-gray-300 p-3 font-medium">Definition</td>
                                        <td class="border border-gray-300 p-3 text-sm">Principles guiding actions within specific contexts</td>
                                        <td class="border border-gray-300 p-3 text-sm">Formal, enforceable rules by legal authority</td>
                                        <td class="border border-gray-300 p-3 text-sm">Specific step-by-step directions</td>
                                        <td class="border border-gray-300 p-3 text-sm">Recommendations or advisory principles</td>
                                    </tr>
                                    <tr class="bg-gray-50">
                                        <td class="border border-gray-300 p-3 font-medium">Enforcement</td>
                                        <td class="border border-gray-300 p-3 text-sm">Group/organization level</td>
                                        <td class="border border-gray-300 p-3 text-sm">Government/legal system</td>
                                        <td class="border border-gray-300 p-3 text-sm">Task/process level</td>
                                        <td class="border border-gray-300 p-3 text-sm">Optional/advisory</td>
                                    </tr>
                                    <tr>
                                        <td class="border border-gray-300 p-3 font-medium">Flexibility</td>
                                        <td class="border border-gray-300 p-3 text-sm">Moderate - context dependent</td>
                                        <td class="border border-gray-300 p-3 text-sm">Low - rigid enforcement</td>
                                        <td class="border border-gray-300 p-3 text-sm">Low - exact sequence</td>
                                        <td class="border border-gray-300 p-3 text-sm">High - adaptable</td>
                                    </tr>
                                    <tr class="bg-gray-50">
                                        <td class="border border-gray-300 p-3 font-medium">Consequences</td>
                                        <td class="border border-gray-300 p-3 text-sm">Group sanctions, penalties</td>
                                        <td class="border border-gray-300 p-3 text-sm">Legal punishment, fines</td>
                                        <td class="border border-gray-300 p-3 text-sm">Task failure, errors</td>
                                        <td class="border border-gray-300 p-3 text-sm">Suboptimal outcomes</td>
                                    </tr>
                                    <tr>
                                        <td class="border border-gray-300 p-3 font-medium">Examples</td>
                                        <td class="border border-gray-300 p-3 text-sm">Game rules, company policies</td>
                                        <td class="border border-gray-300 p-3 text-sm">Traffic laws, criminal code</td>
                                        <td class="border border-gray-300 p-3 text-sm">Recipe steps, assembly manual</td>
                                        <td class="border border-gray-300 p-3 text-sm">Best practices, recommendations</td>
                                    </tr>
                                </tbody>
                            </table>
                        </div>
                    </div>

                    <!-- Detailed Q&A -->
                    <div class="space-y-6">
                        <!-- Q9: Rules -->
                        <div class="concept-card bg-blue-50 border-l-4 border-blue-500 p-6 rounded-r-lg">
                            <h3 class="text-xl font-semibold text-blue-800 mb-3">
                                <i class="fas fa-question-circle mr-2"></i>Q9. What are rules?
                            </h3>
                            
                            <div class="mb-4">
                                <p class="text-gray-600 bg-white p-3 rounded border-l-2 border-blue-300">
                                    <strong>Definition:</strong> A set of principles that guide behavior and actions within a specific context or system, providing boundaries and expectations for acceptable conduct.
                                </p>
                            </div>

                            <div class="grid md:grid-cols-3 gap-4">
                                <div class="bg-white p-4 rounded border text-center">
                                    <i class="fas fa-gamepad text-blue-500 text-2xl mb-2"></i>
                                    <h5 class="font-medium mb-1">Games</h5>
                                    <p class="text-xs text-gray-600">Chess rules, sports regulations</p>
                                </div>
                                <div class="bg-white p-4 rounded border text-center">
                                    <i class="fas fa-users text-green-500 text-2xl mb-2"></i>
                                    <h5 class="font-medium mb-1">Society</h5>
                                    <p class="text-xs text-gray-600">Social norms, etiquette</p>
                                </div>
                                <div class="bg-white p-4 rounded border text-center">
                                    <i class="fas fa-laptop-code text-purple-500 text-2xl mb-2"></i>
                                    <h5 class="font-medium mb-1">Computing</h5>
                                    <p class="text-xs text-gray-600">Programming syntax, algorithms</p>
                                </div>
                            </div>
                        </div>

                        <!-- Q10: Instructions -->
                        <div class="concept-card bg-green-50 border-l-4 border-green-500 p-6 rounded-r-lg">
                            <h3 class="text-xl font-semibold text-green-800 mb-3">
                                <i class="fas fa-question-circle mr-2"></i>Q10. What are instructions?
                            </h3>
                            
                            <div class="mb-4">
                                <p class="text-gray-600 bg-white p-3 rounded border-l-2 border-green-300">
                                    <strong>Definition:</strong> Specific, step-by-step directions that describe exactly how to perform a task or achieve a particular outcome, leaving no ambiguity about the sequence or method.
                                </p>
                            </div>

                            <div class="bg-white p-4 rounded border">
                                <h4 class="font-semibold text-gray-700 mb-2">Key Difference: Rules vs Instructions</h4>
                                <div class="grid md:grid-cols-2 gap-4">
                                    <div class="p-3 bg-blue-50 rounded">
                                        <h5 class="font-medium text-blue-600">Rules (General)</h5>
                                        <p class="text-sm text-gray-600">"Drive safely and obey traffic signals"</p>
                                    </div>
                                    <div class="p-3 bg-green-50 rounded">
                                        <h5 class="font-medium text-green-600">Instructions (Specific)</h5>
                                        <p class="text-sm text-gray-600">"1. Stop at red light 2. Check for pedestrians 3. Proceed when green"</p>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- Q11: Guidelines -->
                        <div class="concept-card bg-purple-50 border-l-4 border-purple-500 p-6 rounded-r-lg">
                            <h3 class="text-xl font-semibold text-purple-800 mb-3">
                                <i class="fas fa-question-circle mr-2"></i>Q11. What are guidelines?
                            </h3>
                            
                            <div class="mb-4">
                                <p class="text-gray-600 bg-white p-3 rounded border-l-2 border-purple-300">
                                    <strong>Definition:</strong> Recommendations or advisory principles that provide direction and suggest best practices, but are not mandatory and allow for flexibility in implementation.
                                </p>
                            </div>

                            <div class="grid md:grid-cols-2 gap-4">
                                <div class="bg-white p-4 rounded border">
                                    <h5 class="font-medium text-purple-600 mb-2">
                                        <i class="fas fa-check-circle mr-2"></i>Advantages of Guidelines
                                    </h5>
                                    <ul class="text-sm text-gray-600 space-y-1">
                                        <li>• Provide flexibility and adaptability</li>
                                        <li>• Allow for professional judgment</li>
                                        <li>• Encourage innovation and creativity</li>
                                        <li>• Can be adjusted based on context</li>
                                    </ul>
                                </div>
                                <div class="bg-white p-4 rounded border">
                                    <h5 class="font-medium text-orange-600 mb-2">
                                        <i class="fas fa-exclamation-triangle mr-2"></i>Considerations
                                    </h5>
                                    <ul class="text-sm text-gray-600 space-y-1">
                                        <li>• May lead to inconsistent application</li>
                                        <li>• Requires good judgment to implement</li>
                                        <li>• May be misinterpreted or ignored</li>
                                        <li>• Less predictable outcomes</li>
                                    </ul>
                                </div>
                            </div>
                        </div>

                        <!-- Q12: Laws -->
                        <div class="concept-card bg-red-50 border-l-4 border-red-500 p-6 rounded-r-lg">
                            <h3 class="text-xl font-semibold text-red-800 mb-3">
                                <i class="fas fa-question-circle mr-2"></i>Q12. What are laws?
                            </h3>
                            
                            <div class="mb-4">
                                <p class="text-gray-600 bg-white p-3 rounded border-l-2 border-red-300">
                                    <strong>Definition:</strong> Formal, enforceable rules established by governmental or legal authority that govern behavior within society, backed by the power of the state and enforced through legal institutions.
                                </p>
                            </div>

                            <div class="bg-white p-4 rounded border">
                                <h4 class="font-semibold text-gray-700 mb-3">Hierarchy of Authority:</h4>
                                <div class="space-y-2">
                                    <div class="flex items-center p-2 bg-red-50 rounded">
                                        <i class="fas fa-crown text-red-500 mr-3"></i>
                                        <span><strong>Laws:</strong> Government/Legal authority - Universal enforcement</span>
                                    </div>
                                    <div class="flex items-center p-2 bg-blue-50 rounded">
                                        <i class="fas fa-building text-blue-500 mr-3"></i>
                                        <span><strong>Rules:</strong> Organizations/Groups - Limited scope</span>
                                    </div>
                                    <div class="flex items-center p-2 bg-purple-50 rounded">
                                        <i class="fas fa-lightbulb text-purple-500 mr-3"></i>
                                        <span><strong>Guidelines:</strong> Advisory bodies - Recommended practices</span>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- Q14: Set of conditions -->
                        <div class="concept-card bg-orange-50 border-l-4 border-orange-500 p-6 rounded-r-lg">
                            <h3 class="text-xl font-semibold text-orange-800 mb-3">
                                <i class="fas fa-question-circle mr-2"></i>Q14. What is meant by a set of conditions?
                            </h3>
                            
                            <div class="mb-4">
                                <p class="text-gray-600 bg-white p-3 rounded border-l-2 border-orange-300">
                                    <strong>Definition:</strong> A collection of requirements, criteria, or circumstances that must be satisfied simultaneously for a particular action, decision, or outcome to occur.
                                </p>
                            </div>

                            <div class="bg-white p-4 rounded border">
                                <h4 class="font-semibold text-gray-700 mb-3">Programming Example:</h4>
                                <div class="code-block p-4 rounded">
                                    <code class="text-green-400">
                                        <span class="text-purple-400">if</span> (x > <span class="text-yellow-400">0</span> <span class="text-red-400">&&</span> y < <span class="text-yellow-400">5</span> <span class="text-red-400">&&</span> user.isAuthenticated()) {<br>
                                        &nbsp;&nbsp;<span class="text-gray-300">// All three conditions must be true</span><br>
                                        &nbsp;&nbsp;executeAction();<br>
                                        }
                                    </code>
                                </div>
                                <p class="text-sm text-gray-600 mt-2">This demonstrates a set of three conditions that must ALL be satisfied for the action to execute.</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 5: Program Execution -->
        <section id="execution" class="mb-12">
            <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                <div class="bg-gradient-to-r from-yellow-500 to-orange-600 text-white p-6">
                    <h2 class="text-3xl font-bold">
                        <i class="fas fa-rocket mr-3"></i>5. Program Execution
                    </h2>
                    <p class="mt-2 opacity-90">Understanding how programs are compiled and executed</p>
                </div>
                
                <div class="p-6">
                    <!-- Q15: C++ compilation and execution -->
                    <div class="concept-card bg-yellow-50 border-l-4 border-yellow-500 p-6 mb-6 rounded-r-lg">
                        <h3 class="text-xl font-semibold text-yellow-800 mb-3">
                            <i class="fas fa-question-circle mr-2"></i>Q15. What happens when we compile and run a C++ program?
                        </h3>
                        
                        <div class="mb-6">
                            <h4 class="font-semibold text-gray-700 mb-3">Complete Compilation Process:</h4>
                            <div class="space-y-4">
                                <div class="flex items-center">
                                    <div class="bg-blue-100 w-10 h-10 rounded-full flex items-center justify-center mr-4">
                                        <i class="fas fa-file-code text-blue-600"></i>
                                    </div>
                                    <div class="flex-1">
                                        <div class="flex items-center justify-between">
                                            <h5 class="font-medium">Source Code (.cpp/.h)</h5>
                                            <i class="fas fa-arrow-right text-gray-400"></i>
                                        </div>
                                        <p class="text-sm text-gray-600">Human-readable C++ code with headers and implementations</p>
                                    </div>
                                </div>

                                <div class="flex items-center">
                                    <div class="bg-green-100 w-10 h-10 rounded-full flex items-center justify-center mr-4">
                                        <i class="fas fa-cogs text-green-600"></i>
                                    </div>
                                    <div class="flex-1">
                                        <div class="flex items-center justify-between">
                                            <h5 class="font-medium">Preprocessor</h5>
                                            <i class="fas fa-arrow-right text-gray-400"></i>
                                        </div>
                                        <p class="text-sm text-gray-600">Handles #include, #define, conditional compilation</p>
                                    </div>
                                </div>

                                <div class="flex items-center">
                                    <div class="bg-purple-100 w-10 h-10 rounded-full flex items-center justify-center mr-4">
                                        <i class="fas fa-microchip text-purple-600"></i>
                                    </div>
                                    <div class="flex-1">
                                        <div class="flex items-center justify-between">
                                            <h5 class="font-medium">Compiler</h5>
                                            <i class="fas fa-arrow-right text-gray-400"></i>
                                        </div>
                                        <p class="text-sm text-gray-600">Translates C++ to assembly language</p>
                                    </div>
                                </div>

                                <div class="flex items-center">
                                    <div class="bg-orange-100 w-10 h-10 rounded-full flex items-center justify-center mr-4">
                                        <i class="fas fa-code text-orange-600"></i>
                                    </div>
                                    <div class="flex-1">
                                        <div class="flex items-center justify-between">
                                            <h5 class="font-medium">Assembler</h5>
                                            <i class="fas fa-arrow-right text-gray-400"></i>
                                        </div>
                                        <p class="text-sm text-gray-600">Converts assembly to machine code (.obj/.o files)</p>
                                    </div>
                                </div>

                                <div class="flex items-center">
                                    <div class="bg-red-100 w-10 h-10 rounded-full flex items-center justify-center mr-4">
                                        <i class="fas fa-link text-red-600"></i>
                                    </div>
                                    <div class="flex-1">
                                        <div class="flex items-center justify-between">
                                            <h5 class="font-medium">Linker</h5>
                                            <i class="fas fa-arrow-right text-gray-400"></i>
                                        </div>
                                        <p class="text-sm text-gray-600">Combines object files and libraries into executable</p>
                                    </div>
                                </div>

                                <div class="flex items-center">
                                    <div class="bg-indigo-100 w-10 h-10 rounded-full flex items-center justify-center mr-4">
                                        <i class="fas fa-play text-indigo-600"></i>
                                    </div>
                                    <div class="flex-1">
                                        <h5 class="font-medium">Executable Program</h5>
                                        <p class="text-sm text-gray-600">Ready-to-run machine code (.exe on Windows)</p>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- Code example -->
                        <div class="bg-white p-4 rounded border">
                            <h4 class="font-semibold text-gray-700 mb-2">Compilation Commands Example:</h4>
                            <div class="code-block p-4 rounded">
                                <code class="text-green-400">
                                    <span class="text-gray-300"># Step-by-step compilation</span><br>
                                    g++ -E main.cpp -o main.i      <span class="text-gray-400"># Preprocessing</span><br>
                                    g++ -S main.i -o main.s        <span class="text-gray-400"># Compilation to assembly</span><br>
                                    g++ -c main.s -o main.o        <span class="text-gray-400"># Assembly to object</span><br>
                                    g++ main.o -o main             <span class="text-gray-400"># Linking to executable</span><br><br>
                                    
                                    <span class="text-gray-300"># Or in one command</span><br>
                                    g++ main.cpp -o main           <span class="text-gray-400"># Complete compilation</span>
                                </code>
                            </div>
                        </div>
                    </div>

                    <!-- Q16: Execution steps -->
                    <div class="concept-card bg-orange-50 border-l-4 border-orange-500 p-6 mb-6 rounded-r-lg">
                        <h3 class="text-xl font-semibold text-orange-800 mb-3">
                            <i class="fas fa-question-circle mr-2"></i>Q16. What are the steps of execution after compilation?
                        </h3>
                        
                        <div class="space-y-4">
                            <div class="bg-white p-4 rounded border">
                                <div class="flex items-start">
                                    <div class="bg-blue-100 text-blue-600 w-8 h-8 rounded-full flex items-center justify-center mr-3 font-bold">1</div>
                                    <div>
                                        <h5 class="font-medium text-gray-800 mb-1">Program Loading (Loader)</h5>
                                        <p class="text-gray-600 text-sm">Operating system loads executable from disk to RAM. Creates process control block (PCB) and allocates memory segments.</p>
                                    </div>
                                </div>
                            </div>

                            <div class="bg-white p-4 rounded border">
                                <div class="flex items-start">
                                    <div class="bg-green-100 text-green-600 w-8 h-8 rounded-full flex items-center justify-center mr-3 font-bold">2</div>
                                    <div>
                                        <h5 class="font-medium text-gray-800 mb-1">Memory Allocation</h5>
                                        <p class="text-gray-600 text-sm">OS assigns memory segments: Code/Text (instructions), Data (global variables), Heap (dynamic allocation), Stack (local variables, function calls).</p>
                                    </div>
                                </div>
                            </div>

                            <div class="bg-white p-4 rounded border">
                                <div class="flex items-start">
                                    <div class="bg-purple-100 text-purple-600 w-8 h-8 rounded-full flex items-center justify-center mr-3 font-bold">3</div>
                                    <div>
                                        <h5 class="font-medium text-gray-800 mb-1">Process Creation</h5>
                                        <p class="text-gray-600 text-sm">OS creates new process with unique Process ID (PID), sets up execution context, and initializes registers.</p>
                                    </div>
                                </div>
                            </div>

                            <div class="bg-white p-4 rounded border">
                                <div class="flex items-start">
                                    <div class="bg-yellow-100 text-yellow-600 w-8 h-8 rounded-full flex items-center justify-center mr-3 font-bold">4</div>
                                    <div>
                                        <h5 class="font-medium text-gray-800 mb-1">CPU Execution</h5>
                                        <p class="text-gray-600 text-sm">CPU begins fetch-decode-execute cycle starting from main() function entry point. Program Counter (PC) tracks current instruction.</p>
                                    </div>
                                </div>
                            </div>

                            <div class="bg-white p-4 rounded border">
                                <div class="flex items-start">
                                    <div class="bg-red-100 text-red-600 w-8 h-8 rounded-full flex items-center justify-center mr-3 font-bold">5</div>
                                    <div>
                                        <h5 class="font-medium text-gray-800 mb-1">Runtime Operations</h5>
                                        <p class="text-gray-600 text-sm">Program executes instructions, handles I/O operations, manages memory dynamically, and interacts with OS services.</p>
                                    </div>
                                </div>
                            </div>

                            <div class="bg-white p-4 rounded border">
                                <div class="flex items-start">
                                    <div class="bg-indigo-100 text-indigo-600 w-8 h-8 rounded-full flex items-center justify-center mr-3 font-bold">6</div>
                                    <div>
                                        <h5 class="font-medium text-gray-800 mb-1">Program Termination</h5>
                                        <p class="text-gray-600 text-sm">Program completes execution, returns exit code to OS, memory is deallocated, and process is removed from process table.</p>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- Memory Layout Visualization -->
                        <div class="mt-6 bg-white p-4 rounded border">
                            <h4 class="font-semibold text-gray-700 mb-3">Program Memory Layout:</h4>
                            <div class="grid md:grid-cols-4 gap-2">
                                <div class="text-center p-3 bg-blue-50 rounded border">
                                    <i class="fas fa-code text-blue-500 mb-2"></i>
                                    <h6 class="font-medium text-blue-600">Code Segment</h6>
                                    <p class="text-xs text-gray-600">Program instructions</p>
                                </div>
                                <div class="text-center p-3 bg-green-50 rounded border">
                                    <i class="fas fa-database text-green-500 mb-2"></i>
                                    <h6 class="font-medium text-green-600">Data Segment</h6>
                                    <p class="text-xs text-gray-600">Global variables</p>
                                </div>
                                <div class="text-center p-3 bg-purple-50 rounded border">
                                    <i class="fas fa-expand-arrows-alt text-purple-500 mb-2"></i>
                                    <h6 class="font-medium text-purple-600">Heap</h6>
                                    <p class="text-xs text-gray-600">Dynamic allocation</p>
                                </div>
                                <div class="text-center p-3 bg-orange-50 rounded border">
                                    <i class="fas fa-layer-group text-orange-500 mb-2"></i>
                                    <h6 class="font-medium text-orange-600">Stack</h6>
                                    <p class="text-xs text-gray-600">Function calls, locals</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 6: Protocols & Framework -->
        <section id="protocols" class="mb-12">
            <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                <div class="bg-gradient-to-r from-teal-500 to-cyan-600 text-white p-6">
                    <h2 class="text-3xl font-bold">
                        <i class="fas fa-handshake mr-3"></i>6. Protocols & Framework
                    </h2>
                    <p class="mt-2 opacity-90">Understanding communication standards and development structures</p>
                </div>
                
                <div class="p-6">
                    <!-- Protocol definitions -->
                    <div class="grid md:grid-cols-2 gap-6 mb-6">
                        <!-- Q17: Protocol -->
                        <div class="concept-card bg-teal-50 border-l-4 border-teal-500 p-6 rounded-r-lg">
                            <h3 class="text-xl font-semibold text-teal-800 mb-3">
                                <i class="fas fa-question-circle mr-2"></i>Q17. What is a protocol?
                            </h3>
                            
                            <div class="mb-4">
                                <p class="text-gray-600 bg-white p-3 rounded border-l-2 border-teal-300">
                                    <strong>Definition:</strong> A protocol is a set of standardized rules and procedures that govern communication and interaction between systems, devices, or entities.
                                </p>
                            </div>

                            <div class="space-y-3">
                                <div class="bg-white p-3 rounded border">
                                    <h5 class="font-medium text-blue-600">
                                        <i class="fas fa-network-wired mr-2"></i>Network Protocols
                                    </h5>
                                    <p class="text-sm text-gray-600">TCP/IP, HTTP, FTP, SMTP</p>
                                </div>
                                <div class="bg-white p-3 rounded border">
                                    <h5 class="font-medium text-green-600">
                                        <i class="fas fa-users mr-2"></i>Social Protocols
                                    </h5>
                                    <p class="text-sm text-gray-600">Etiquette, diplomatic procedures</p>
                                </div>
                                <div class="bg-white p-3 rounded border">
                                    <h5 class="font-medium text-purple-600">
                                        <i class="fas fa-flask mr-2"></i>Scientific Protocols
                                    </h5>
                                    <p class="text-sm text-gray-600">Experimental procedures, research methods</p>
                                </div>
                            </div>
                        </div>

                        <!-- Q20: Framework -->
                        <div class="concept-card bg-cyan-50 border-l-4 border-cyan-500 p-6 rounded-r-lg">
                            <h3 class="text-xl font-semibold text-cyan-800 mb-3">
                                <i class="fas fa-question-circle mr-2"></i>Q20. What is a framework?
                            </h3>
                            
                            <div class="mb-4">
                                <p class="text-gray-600 bg-white p-3 rounded border-l-2 border-cyan-300">
                                    <strong>Definition:</strong> A structured environment or foundation that provides reusable components, tools, and guidelines for development or management, reducing complexity and development time.
                                </p>
                            </div>

                            <div class="space-y-3">
                                <div class="bg-white p-3 rounded border">
                                    <h5 class="font-medium text-blue-600">
                                        <i class="fas fa-code mr-2"></i>Software Frameworks
                                    </h5>
                                    <p class="text-sm text-gray-600">Django, React, Angular, .NET</p>
                                </div>
                                <div class="bg-white p-3 rounded border">
                                    <h5 class="font-medium text-green-600">
                                        <i class="fas fa-building mr-2"></i>Business Frameworks
                                    </h5>
                                    <p class="text-sm text-gray-600">Agile, ITIL, Six Sigma</p>
                                </div>
                                <div class="bg-white p-3 rounded border">
                                    <h5 class="font-medium text-purple-600">
                                        <i class="fas fa-balance-scale mr-2"></i>Legal Frameworks
                                    </h5>
                                    <p class="text-sm text-gray-600">Constitutional law, regulatory systems</p>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Additional concepts -->
                    <div class="grid md:grid-cols-2 gap-6">
                        <!-- Q18: Policy -->
                        <div class="concept-card bg-blue-50 border-l-4 border-blue-500 p-6 rounded-r-lg">
                            <h3 class="text-xl font-semibold text-blue-800 mb-3">
                                <i class="fas fa-question-circle mr-2"></i>Q18. What is a policy?
                            </h3>
                            
                            <div class="mb-4">
                                <p class="text-gray-600 bg-white p-3 rounded border-l-2 border-blue-300">
                                    <strong>Definition:</strong> A policy is a high-level guiding principle or course of action that shapes decision-making and establishes the framework for creating specific rules and procedures.
                                </p>
                            </div>

                            <div class="bg-white p-3 rounded border">
                                <h5 class="font-medium text-gray-700 mb-2">Policy Examples:</h5>
                                <ul class="text-sm text-gray-600 space-y-1">
                                    <li>• Corporate security policy</li>
                                    <li>• Privacy policy</li>
                                    <li>• Government fiscal policy</li>
                                    <li>• Educational policy</li>
                                </ul>
                            </div>
                        </div>

                        <!-- Q19: Procedure -->
                        <div class="concept-card bg-green-50 border-l-4 border-green-500 p-6 rounded-r-lg">
                            <h3 class="text-xl font-semibold text-green-800 mb-3">
                                <i class="fas fa-question-circle mr-2"></i>Q19. What is a procedure?
                            </h3>
                            
                            <div class="mb-4">
                                <p class="text-gray-600 bg-white p-3 rounded border-l-2 border-green-300">
                                    <strong>Definition:</strong> A procedure is a detailed sequence of steps and actions that implement policies and rules, providing specific instructions for how tasks should be performed.
                                </p>
                            </div>

                            <div class="bg-white p-3 rounded border">
                                <h5 class="font-medium text-gray-700 mb-2">Procedure Examples:</h5>
                                <ul class="text-sm text-gray-600 space-y-1">
                                    <li>• User registration procedure</li>
                                    <li>• Data backup procedure</li>
                                    <li>• Emergency response procedure</li>
                                    <li>• Quality control procedure</li>
                                </ul>
                            </div>
                        </div>
                    </div>

                    <!-- Relationship diagram -->
                    <div class="mt-6 bg-white p-6 rounded border">
                        <h4 class="font-semibold text-gray-700 mb-4 text-center">Relationship Hierarchy</h4>
                        <div class="flex flex-col items-center space-y-4">
                            <div class="text-center p-4 bg-purple-100 rounded-lg border-2 border-purple-300">
                                <h5 class="font-bold text-purple-800">POLICY</h5>
                                <p class="text-sm text-purple-600">High-level principles</p>
                            </div>
                            <i class="fas fa-arrow-down text-gray-400 text-2xl"></i>
                            <div class="text-center p-4 bg-blue-100 rounded-lg border-2 border-blue-300">
                                <h5 class="font-bold text-blue-800">PROTOCOL</h5>
                                <p class="text-sm text-blue-600">Communication standards</p>
                            </div>
                            <i class="fas fa-arrow-down text-gray-400 text-2xl"></i>
                            <div class="text-center p-4 bg-green-100 rounded-lg border-2 border-green-300">
                                <h5 class="font-bold text-green-800">PROCEDURE</h5>
                                <p class="text-sm text-green-600">Detailed implementation steps</p>
                            </div>
                            <i class="fas fa-arrow-down text-gray-400 text-2xl"></i>
                            <div class="text-center p-4 bg-orange-100 rounded-lg border-2 border-orange-300">
                                <h5 class="font-bold text-orange-800">FRAMEWORK</h5>
                                <p class="text-sm text-orange-600">Supporting structure & tools</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 7: Networking -->
        <section id="networking" class="mb-12">
            <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                <div class="bg-gradient-to-r from-blue-500 to-indigo-600 text-white p-6">
                    <h2 class="text-3xl font-bold">
                        <i class="fas fa-globe mr-3"></i>7. Networking
                    </h2>
                    <p class="mt-2 opacity-90">Understanding network communication and addressing</p>
                </div>
                
                <div class="p-6">
                    <!-- Q21: IP -->
                    <div class="concept-card bg-blue-50 border-l-4 border-blue-500 p-6 mb-6 rounded-r-lg">
                        <h3 class="text-xl font-semibold text-blue-800 mb-3">
                            <i class="fas fa-question-circle mr-2"></i>Q21. What is IP (Internet Protocol)?
                        </h3>
                        
                        <div class="mb-4">
                            <p class="text-gray-600 bg-white p-3 rounded border-l-2 border-blue-300">
                                <strong>Definition:</strong> Internet Protocol (IP) is a unique numerical identifier assigned to every device connected to a network, enabling data packets to be routed to the correct destination across interconnected networks.
                            </p>
                        </div>

                        <!-- TCP/IP Stack Visualization -->
                        <div class="mb-6">
                            <h4 class="font-semibold text-gray-700 mb-3">TCP/IP Protocol Stack:</h4>
                            <div class="bg-white p-4 rounded border">
                                <img src="https://docs.oracle.com/cd/E18752_01/html/816-4554/figures/ipov.fig88.png" 
                                     alt="TCP/IP Protocol Stack" 
                                     class="w-full max-w-lg mx-auto rounded shadow">
                            </div>
                        </div>

                        <div class="grid md:grid-cols-2 gap-4 mb-4">
                            <div class="bg-white p-4 rounded border">
                                <h5 class="font-medium text-blue-600 mb-2">
                                    <i class="fas fa-globe mr-2"></i>IPv4 Format
                                </h5>
                                <div class="space-y-2">
                                    <code class="bg-gray-100 px-2 py-1 rounded text-sm">192.168.1.100</code>
                                    <p class="text-sm text-gray-600">32-bit address (4 octets)</p>
                                    <p class="text-sm text-gray-600">Range: 0.0.0.0 to 255.255.255.255</p>
                                    <p class="text-sm text-gray-600">~4.3 billion unique addresses</p>
                                </div>
                            </div>
                            <div class="bg-white p-4 rounded border">
                                <h5 class="font-medium text-green-600 mb-2">
                                    <i class="fas fa-expand mr-2"></i>IPv6 Format
                                </h5>
                                <div class="space-y-2">
                                    <code class="bg-gray-100 px-2 py-1 rounded text-sm">2001:0db8:85a3::8a2e:0370:7334</code>
                                    <p class="text-sm text-gray-600">128-bit address (8 groups)</p>
                                    <p class="text-sm text-gray-600">Hexadecimal notation</p>
                                    <p class="text-sm text-gray-600">~340 undecillion addresses</p>
                                </div>
                            </div>
                        </div>

                        <div class="bg-yellow-50 border border-yellow-200 p-4 rounded">
                            <h4 class="font-semibold text-yellow-800 mb-2">
                                <i class="fas fa-exclamation-triangle mr-2"></i>Critical Function
                            </h4>
                            <p class="text-yellow-700">Without IP addressing, data packets cannot reach their intended destination. Every device needs a unique IP to participate in network communication.</p>
                        </div>
                    </div>

                    <!-- Q22 & Q23: Path and Route -->
                    <div class="grid md:grid-cols-2 gap-6 mb-6">
                        <div class="concept-card bg-green-50 border-l-4 border-green-500 p-6 rounded-r-lg">
                            <h3 class="text-xl font-semibold text-green-800 mb-3">
                                <i class="fas fa-question-circle mr-2"></i>Q22. What is a path in networking?
                            </h3>
                            
                            <div class="mb-4">
                                <p class="text-gray-600 bg-white p-3 rounded border-l-2 border-green-300">
                                    <strong>Definition:</strong> A path is the actual route that data takes from source to destination, which may change dynamically based on network conditions, traffic, and available connections.
                                </p>
                            </div>

                            <div class="bg-white p-3 rounded border">
                                <h5 class="font-medium text-gray-700 mb-2">Path Characteristics:</h5>
                                <ul class="text-sm text-gray-600 space-y-1">
                                    <li>• Dynamic and adaptive</li>
                                    <li>• Changes based on network conditions</li>
                                    <li>• May vary for each packet</li>
                                    <li>• Optimized for current traffic</li>
                                </ul>
                            </div>
                        </div>

                        <div class="concept-card bg-purple-50 border-l-4 border-purple-500 p-6 rounded-r-lg">
                            <h3 class="text-xl font-semibold text-purple-800 mb-3">
                                <i class="fas fa-question-circle mr-2"></i>Q23. What is a route in networking?
                            </h3>
                            
                            <div class="mb-4">
                                <p class="text-gray-600 bg-white p-3 rounded border-l-2 border-purple-300">
                                    <strong>Definition:</strong> A route is a predetermined set of directions or network hops that has been configured or learned by routing protocols to reach a specific destination network.
                                </p>
                            </div>

                            <div class="bg-white p-3 rounded border">
                                <h5 class="font-medium text-gray-700 mb-2">Route Characteristics:</h5>
                                <ul class="text-sm text-gray-600 space-y-1">
                                    <li>• Stored in routing tables</li>
                                    <li>• Configured by network administrators</li>
                                    <li>• Used by routing protocols</li>
                                    <li>• More stable than paths</li>
                                </ul>
                            </div>
                        </div>
                    </div>

                    <!-- Path vs Route comparison -->
                    <div class="bg-white p-6 rounded border">
                        <h4 class="font-semibold text-gray-700 mb-4">Path vs Route: Real-World Analogy</h4>
                        <div class="grid md:grid-cols-2 gap-6">
                            <div class="text-center">
                                <div class="bg-green-100 p-4 rounded-lg mb-3">
                                    <i class="fas fa-route text-green-600 text-3xl mb-2"></i>
                                    <h5 class="font-medium text-green-800">PATH</h5>
                                </div>
                                <p class="text-sm text-gray-600 italic">"The actual roads your GPS guides you through in real-time, avoiding traffic jams and construction"</p>
                                <div class="mt-3 text-xs text-green-600">
                                    <strong>Example:</strong> Home → Main St → Highway 101 → Oak Ave → Destination
                                </div>
                            </div>
                            <div class="text-center">
                                <div class="bg-purple-100 p-4 rounded-lg mb-3">
                                    <i class="fas fa-map text-purple-600 text-3xl mb-2"></i>
                                    <h5 class="font-medium text-purple-800">ROUTE</h5>
                                </div>
                                <p class="text-sm text-gray-600 italic">"The planned directions stored in your GPS database for reaching specific destinations"</p>
                                <div class="mt-3 text-xs text-purple-600">
                                    <strong>Example:</strong> Route to Downtown: "Take Highway 101 South for 5 miles"
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 8: Communication & Language -->
        <section id="communication" class="mb-12">
            <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                <div class="bg-gradient-to-r from-pink-500 to-rose-600 text-white p-6">
                    <h2 class="text-3xl font-bold">
                        <i class="fas fa-comments mr-3"></i>8. Communication & Language
                    </h2>
                    <p class="mt-2 opacity-90">Understanding information exchange and language systems</p>
                </div>
                
                <div class="p-6">
                    <!-- Q24: Communication -->
                    <div class="concept-card bg-pink-50 border-l-4 border-pink-500 p-6 mb-6 rounded-r-lg">
                        <h3 class="text-xl font-semibold text-pink-800 mb-3">
                            <i class="fas fa-question-circle mr-2"></i>Q24. What is communication?
                        </h3>
                        
                        <div class="mb-4">
                            <p class="text-gray-600 bg-white p-3 rounded border-l-2 border-pink-300">
                                <strong>Definition:</strong> Communication is the process of exchanging information, ideas, thoughts, or feelings between a sender and receiver through various channels and media.
                            </p>
                        </div>

                        <!-- Communication Model -->
                        <div class="mb-6">
                            <h4 class="font-semibold text-gray-700 mb-3">Basic Communication Model:</h4>
                            <div class="flex items-center justify-center space-x-4 p-4 bg-white rounded border">
                                <div class="text-center">
                                    <div class="bg-blue-100 w-16 h-16 rounded-full flex items-center justify-center mb-2">
                                        <i class="fas fa-user text-blue-600 text-xl"></i>
                                    </div>
                                    <h6 class="font-medium text-blue-600">Sender</h6>
                                </div>
                                <i class="fas fa-arrow-right text-gray-400 text-2xl"></i>
                                <div class="text-center">
                                    <div class="bg-green-100 w-16 h-16 rounded-full flex items-center justify-center mb-2">
                                        <i class="fas fa-envelope text-green-600 text-xl"></i>
                                    </div>
                                    <h6 class="font-medium text-green-600">Message</h6>
                                </div>
                                <i class="fas fa-arrow-right text-gray-400 text-2xl"></i>
                                <div class="text-center">
                                    <div class="bg-purple-100 w-16 h-16 rounded-full flex items-center justify-center mb-2">
                                        <i class="fas fa-broadcast-tower text-purple-600 text-xl"></i>
                                    </div>
                                    <h6 class="font-medium text-purple-600">Medium</h6>
                                </div>
                                <i class="fas fa-arrow-right text-gray-400 text-2xl"></i>
                                <div class="text-center">
                                    <div class="bg-orange-100 w-16 h-16 rounded-full flex items-center justify-center mb-2">
                                        <i class="fas fa-user-friends text-orange-600 text-xl"></i>
                                    </div>
                                    <h6 class="font-medium text-orange-600">Receiver</h6>
                                </div>
                            </div>
                        </div>

                        <div class="grid md:grid-cols-2 gap-4">
                            <div class="bg-white p-4 rounded border">
                                <h5 class="font-medium text-blue-600 mb-2">
                                    <i class="fas fa-tv mr-2"></i>Communication Mediums
                                </h5>
                                <ul class="text-sm text-gray-600 space-y-1">
                                    <li>• Verbal (speech, conversations)</li>
                                    <li>• Written (text, documents)</li>
                                    <li>• Digital (email, messaging)</li>
                                    <li>• Visual (images, videos)</li>
                                    <li>• Non-verbal (gestures, body language)</li>
                                </ul>
                            </div>
                            <div class="bg-white p-4 rounded border">
                                <h5 class="font-medium text-green-600 mb-2">
                                    <i class="fas fa-exchange-alt mr-2"></i>Communication Types
                                </h5>
                                <ul class="text-sm text-gray-600 space-y-1">
                                    <li>• One-way (broadcast, announcements)</li>
                                    <li>• Two-way (conversation, dialogue)</li>
                                    <li>• Multi-way (group discussions)</li>
                                    <li>• Synchronous (real-time)</li>
                                    <li>• Asynchronous (delayed response)</li>
                                </ul>
                            </div>
                        </div>
                    </div>

                    <!-- Q25: Language -->
                    <div class="concept-card bg-rose-50 border-l-4 border-rose-500 p-6 mb-6 rounded-r-lg">
                        <h3 class="text-xl font-semibold text-rose-800 mb-3">
                            <i class="fas fa-question-circle mr-2"></i>Q25. What is language?
                        </h3>
                        
                        <div class="mb-4">
                            <p class="text-gray-600 bg-white p-3 rounded border-l-2 border-rose-300">
                                <strong>Definition:</strong> Language is a structured system of symbols, rules, and conventions used for communication, enabling the expression and understanding of complex ideas, emotions, and information.
                            </p>
                        </div>

                        <div class="grid md:grid-cols-2 gap-4 mb-4">
                            <div class="bg-white p-4 rounded border">
                                <h5 class="font-medium text-blue-600 mb-2">
                                    <i class="fas fa-users mr-2"></i>Human Languages
                                </h5>
                                <div class="space-y-2 text-sm text-gray-600">
                                    <p><strong>Natural:</strong> English, Spanish, Mandarin</p>
                                    <p><strong>Components:</strong> Grammar, vocabulary, syntax</p>
                                    <p><strong>Features:</strong> Cultural context, evolution</p>
                                </div>
                            </div>
                            <div class="bg-white p-4 rounded border">
                                <h5 class="font-medium text-green-600 mb-2">
                                    <i class="fas fa-code mr-2"></i>Programming Languages
                                </h5>
                                <div class="space-y-2 text-sm text-gray-600">
                                    <p><strong>Formal:</strong> C++, Python, Java</p>
                                    <p><strong>Components:</strong> Syntax, semantics, keywords</p>
                                    <p><strong>Features:</strong> Precise, unambiguous</p>
                                </div>
                            </div>
                        </div>

                        <div class="bg-white p-4 rounded border">
                            <h4 class="font-semibold text-gray-700 mb-3">Language Characteristics:</h4>
                            <div class="grid md:grid-cols-4 gap-3">
                                <div class="text-center p-2 bg-blue-50 rounded">
                                    <i class="fas fa-puzzle-piece text-blue-500 mb-1"></i>
                                    <h6 class="text-sm font-medium">Structure</h6>
                                    <p class="text-xs text-gray-600">Rules & patterns</p>
                                </div>
                                <div class="text-center p-2 bg-green-50 rounded">
                                    <i class="fas fa-share-alt text-green-500 mb-1"></i>
                                    <h6 class="text-sm font-medium">Shared</h6>
                                    <p class="text-xs text-gray-600">Community understanding</p>
                                </div>
                                <div class="text-center p-2 bg-purple-50 rounded">
                                    <i class="fas fa-sync text-purple-500 mb-1"></i>
                                    <h6 class="text-sm font-medium">Dynamic</h6>
                                    <p class="text-xs text-gray-600">Evolves over time</p>
                                </div>
                                <div class="text-center p-2 bg-orange-50 rounded">
                                    <i class="fas fa-infinity text-orange-500 mb-1"></i>
                                    <h6 class="text-sm font-medium">Generative</h6>
                                    <p class="text-xs text-gray-600">Infinite expressions</p>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Q26 & Q27: Role and Exchange -->
                    <div class="grid md:grid-cols-2 gap-6">
                        <div class="concept-card bg-indigo-50 border-l-4 border-indigo-500 p-6 rounded-r-lg">
                            <h3 class="text-xl font-semibold text-indigo-800 mb-3">
                                <i class="fas fa-question-circle mr-2"></i>Q26. Role of language in communication
                            </h3>
                            
                            <div class="space-y-3">
                                <div class="bg-white p-3 rounded border">
                                    <h6 class="font-medium text-indigo-600">
                                        <i class="fas fa-eye mr-2"></i>Provides Clarity
                                    </h6>
                                    <p class="text-sm text-gray-600">Structured symbols eliminate confusion</p>
                                </div>
                                <div class="bg-white p-3 rounded border">
                                    <h6 class="font-medium text-green-600">
                                        <i class="fas fa-crosshairs mr-2"></i>Removes Ambiguity
                                    </h6>
                                    <p class="text-sm text-gray-600">Precise meanings through grammar</p>
                                </div>
                                <div class="bg-white p-3 rounded border">
                                    <h6 class="font-medium text-purple-600">
                                        <i class="fas fa-share mr-2"></i>Enables Knowledge Sharing
                                    </h6>
                                    <p class="text-sm text-gray-600">Transfer of complex concepts</p>
                                </div>
                            </div>
                        </div>

                        <div class="concept-card bg-teal-50 border-l-4 border-teal-500 p-6 rounded-r-lg">
                            <h3 class="text-xl font-semibold text-teal-800 mb-3">
                                <i class="fas fa-question-circle mr-2"></i>Q27. Exchange of language
                            </h3>
                            
                            <div class="mb-4">
                                <p class="text-gray-600 bg-white p-3 rounded border-l-2 border-teal-300">
                                    <strong>Definition:</strong> The transfer of meaning between parties through a shared linguistic medium, involving encoding by sender and decoding by receiver.
                                </p>
                            </div>

                            <div class="bg-white p-3 rounded border">
                                <h6 class="font-medium text-gray-700 mb-2">Exchange Process:</h6>
                                <div class="space-y-1 text-sm text-gray-600">
                                    <p><strong>1.</strong> Sender encodes thoughts into language</p>
                                    <p><strong>2.</strong> Message transmitted through medium</p>
                                    <p><strong>3.</strong> Receiver decodes language into meaning</p>
                                    <p><strong>4.</strong> Feedback confirms understanding</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 9: Postal System Analogy -->
        <section id="postal" class="mb-12">
            <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                <div class="bg-gradient-to-r from-amber-500 to-orange-600 text-white p-6">
                    <h2 class="text-3xl font-bold">
                        <i class="fas fa-mail-bulk mr-3"></i>9. Postal System Analogy
                    </h2>
                    <p class="mt-2 opacity-90">Understanding networking through real-world postal communication</p>
                </div>
                
                <div class="p-6">
                    <div class="concept-card bg-amber-50 border-l-4 border-amber-500 p-6 mb-6 rounded-r-lg">
                        <h3 class="text-xl font-semibold text-amber-800 mb-3">
                            <i class="fas fa-question-circle mr-2"></i>Q28. Explain the postal system as a communication process
                        </h3>
                        
                        <div class="mb-6">
                            <p class="text-gray-600 bg-white p-3 rounded border-l-2 border-amber-300">
                                <strong>Definition:</strong> The postal system is a physical network infrastructure that enables the delivery of messages and packages from sender to recipient through standardized addressing and routing mechanisms.
                            </p>
                        </div>

                        <!-- Postal Process Flow -->
                        <div class="mb-6">
                            <h4 class="font-semibold text-gray-700 mb-3">Postal System Working Process:</h4>
                            <div class="space-y-4">
                                <div class="flex items-start bg-white p-4 rounded border">
                                    <div class="bg-blue-100 text-blue-600 w-8 h-8 rounded-full flex items-center justify-center mr-3 font-bold">1</div>
                                    <div>
                                        <h5 class="font-medium text-gray-800 mb-1">
                                            <i class="fas fa-user mr-2 text-blue-500"></i>Sender Preparation
                                        </h5>
                                        <p class="text-gray-600 text-sm">Person writes message, places in envelope, writes complete address with PIN code, affixes postage stamp</p>
                                    </div>
                                </div>

                                <div class="flex items-start bg-white p-4 rounded border">
                                    <div class="bg-green-100 text-green-600 w-8 h-8 rounded-full flex items-center justify-center mr-3 font-bold">2</div>
                                    <div>
                                        <h5 class="font-medium text-gray-800 mb-1">
                                            <i class="fas fa-mailbox mr-2 text-green-500"></i>Collection
                                        </h5>
                                        <p class="text-gray-600 text-sm">Mail dropped in post box or taken to post office, collected by postal workers at scheduled times</p>
                                    </div>
                                </div>

                                <div class="flex items-start bg-white p-4 rounded border">
                                    <div class="bg-purple-100 text-purple-600 w-8 h-8 rounded-full flex items-center justify-center mr-3 font-bold">3</div>
                                    <div>
                                        <h5 class="font-medium text-gray-800 mb-1">
                                            <i class="fas fa-sort mr-2 text-purple-500"></i>Local Sorting
                                        </h5>
                                        <p class="text-gray-600 text-sm">Mail sorted at local post office by PIN code and destination, bundled for efficient transport</p>
                                    </div>
                                </div>

                                <div class="flex items-start bg-white p-4 rounded border">
                                    <div class="bg-orange-100 text-orange-600 w-8 h-8 rounded-full flex items-center justify-center mr-3 font-bold">4</div>
                                    <div>
                                        <h5 class="font-medium text-gray-800 mb-1">
                                            <i class="fas fa-truck mr-2 text-orange-500"></i>Transportation
                                        </h5>
                                        <p class="text-gray-600 text-sm">Mail transported via trucks, trains, or planes to regional sorting facilities and destination areas</p>
                                    </div>
                                </div>

                                <div class="flex items-start bg-white p-4 rounded border">
                                    <div class="bg-red-100 text-red-600 w-8 h-8 rounded-full flex items-center justify-center mr-3 font-bold">5</div>
                                    <div>
                                        <h5 class="font-medium text-gray-800 mb-1">
                                            <i class="fas fa-building mr-2 text-red-500"></i>Destination Sorting
                                        </h5>
                                        <p class="text-gray-600 text-sm">Mail sorted at destination post office by specific address, assigned to delivery routes</p>
                                    </div>
                                </div>

                                <div class="flex items-start bg-white p-4 rounded border">
                                    <div class="bg-indigo-100 text-indigo-600 w-8 h-8 rounded-full flex items-center justify-center mr-3 font-bold">6</div>
                                    <div>
                                        <h5 class="font-medium text-gray-800 mb-1">
                                            <i class="fas fa-home mr-2 text-indigo-500"></i>Final Delivery
                                        </h5>
                                        <p class="text-gray-600 text-sm">Postal worker delivers mail to specific address, recipient receives the message</p>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- PIN Code System -->
                        <div class="mb-6">
                            <h4 class="font-semibold text-gray-700 mb-3">PIN Code System in India:</h4>
                            <div class="bg-white p-4 rounded border">
                                <div class="grid md:grid-cols-2 gap-4">
                                    <div>
                                        <h5 class="font-medium text-blue-600 mb-2">
                                            <i class="fas fa-map-pin mr-2"></i>PIN Code Structure
                                        </h5>
                                        <div class="space-y-2 text-sm">
                                            <div class="p-2 bg-blue-50 rounded font-mono">
                                                <span class="text-red-600">4</span><span class="text-blue-600">1</span><span class="text-green-600">0</span><span class="text-purple-600">0</span><span class="text-orange-600">2</span><span class="text-pink-600">8</span>
                                            </div>
                                            <p><span class="text-red-600">■</span> <strong>First digit:</strong> Regional zone</p>
                                            <p><span class="text-blue-600">■</span> <strong>Second digit:</strong> Sub-zone</p>
                                            <p><span class="text-green-600">■</span><span class="text-purple-600">■</span> <strong>Third-Fourth:</strong> Sorting district</p>
                                            <p><span class="text-orange-600">■</span><span class="text-pink-600">■</span> <strong>Last two:</strong> Delivery post office</p>
                                        </div>
                                    </div>
                                    <div>
                                        <h5 class="font-medium text-green-600 mb-2">
                                            <i class="fas fa-cogs mr-2"></i>PIN Code Benefits
                                        </h5>
                                        <ul class="text-sm text-gray-600 space-y-1">
                                            <li>• Efficient sorting and routing</li>
                                            <li>• Reduced delivery errors</li>
                                            <li>• Faster processing times</li>
                                            <li>• Automated sorting machines</li>
                                            <li>• Geographic organization</li>
                                        </ul>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <!-- Computing Analogy -->
                        <div class="bg-gray-50 p-6 rounded border">
                            <h4 class="font-semibold text-gray-700 mb-4 text-center">
                                <i class="fas fa-arrows-alt-h mr-2"></i>Postal System ↔ Computer Networking Analogy
                            </h4>
                            
                            <div class="grid md:grid-cols-2 gap-6">
                                <div class="bg-white p-4 rounded border">
                                    <h5 class="font-bold text-amber-600 mb-3 text-center">
                                        <i class="fas fa-mail-bulk mr-2"></i>Postal System
                                    </h5>
                                    <div class="space-y-2 text-sm">
                                        <div class="flex justify-between">
                                            <span class="text-gray-600">Sender:</span>
                                            <span class="font-medium">Person writing letter</span>
                                        </div>
                                        <div class="flex justify-between">
                                            <span class="text-gray-600">Message:</span>
                                            <span class="font-medium">Letter/Package</span>
                                        </div>
                                        <div class="flex justify-between">
                                            <span class="text-gray-600">Address:</span>
                                            <span class="font-medium">PIN Code system</span>
                                        </div>
                                        <div class="flex justify-between">
                                            <span class="text-gray-600">Network:</span>
                                            <span class="font-medium">Post offices</span>
                                        </div>
                                        <div class="flex justify-between">
                                            <span class="text-gray-600">Routing:</span>
                                            <span class="font-medium">Sorting facilities</span>
                                        </div>
                                        <div class="flex justify-between">
                                            <span class="text-gray-600">Transport:</span>
                                            <span class="font-medium">Trucks, trains, planes</span>
                                        </div>
                                        <div class="flex justify-between">
                                            <span class="text-gray-600">Delivery:</span>
                                            <span class="font-medium">Postal worker</span>
                                        </div>
                                        <div class="flex justify-between">
                                            <span class="text-gray-600">Recipient:</span>
                                            <span class="font-medium">Person receiving letter</span>
                                        </div>
                                    </div>
                                </div>

                                <div class="bg-white p-4 rounded border">
                                    <h5 class="font-bold text-blue-600 mb-3 text-center">
                                        <i class="fas fa-network-wired mr-2"></i>Computer Networking
                                    </h5>
                                    <div class="space-y-2 text-sm">
                                        <div class="flex justify-between">
                                            <span class="text-gray-600">Sender:</span>
                                            <span class="font-medium">Source computer</span>
                                        </div>
                                        <div class="flex justify-between">
                                            <span class="text-gray-600">Message:</span>
                                            <span class="font-medium">Data packet</span>
                                        </div>
                                        <div class="flex justify-between">
                                            <span class="text-gray-600">Address:</span>
                                            <span class="font-medium">IP address</span>
                                        </div>
                                        <div class="flex justify-between">
                                            <span class="text-gray-600">Network:</span>
                                            <span class="font-medium">Internet infrastructure</span>
                                        </div>
                                        <div class="flex justify-between">
                                            <span class="text-gray-600">Routing:</span>
                                            <span class="font-medium">Routers and switches</span>
                                        </div>
                                        <div class="flex justify-between">
                                            <span class="text-gray-600">Transport:</span>
                                            <span class="font-medium">Network cables, fiber optics</span>
                                        </div>
                                        <div class="flex justify-between">
                                            <span class="text-gray-600">Delivery:</span>
                                            <span class="font-medium">Network interface</span>
                                        </div>
                                        <div class="flex justify-between">
                                            <span class="text-gray-600">Recipient:</span>
                                            <span class="font-medium">Destination computer</span>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 10: Extra Questions -->
        <section id="extra" class="mb-12">
            <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                <div class="bg-gradient-to-r from-gray-700 to-gray-900 text-white p-6">
                    <h2 class="text-3xl font-bold">
                        <i class="fas fa-plus-circle mr-3"></i>10. Extended Topics
                    </h2>
                    <p class="mt-2 opacity-90">Additional concepts for deeper understanding</p>
                </div>
                
                <div class="p-6">
                    <div class="grid md:grid-cols-2 gap-6">
                        <!-- Q29: Automation -->
                        <div class="concept-card bg-gray-50 border-l-4 border-gray-500 p-6 rounded-r-lg">
                            <h3 class="text-xl font-semibold text-gray-800 mb-3">
                                <i class="fas fa-question-circle mr-2"></i>Q29. What is automation?
                            </h3>
                            
                            <div class="mb-4">
                                <p class="text-gray-600 bg-white p-3 rounded border-l-2 border-gray-300">
                                    <strong>Definition:</strong> Automation is the use of technology to perform tasks with minimal human intervention, improving efficiency, accuracy, and consistency.
                                </p>
                            </div>

                            <div class="space-y-3">
                                <div class="bg-white p-3 rounded border">
                                    <h6 class="font-medium text-blue-600">
                                        <i class="fas fa-home mr-2"></i>Daily Life Examples
                                    </h6>
                                    <p class="text-sm text-gray-600">Smart homes, automatic doors, washing machines, ATMs</p>
                                </div>
                                <div class="bg-white p-3 rounded border">
                                    <h6 class="font-medium text-green-600">
                                        <i class="fas fa-industry mr-2"></i>Industrial Examples
                                    </h6>
                                    <p class="text-sm text-gray-600">Assembly lines, robotic manufacturing, quality control systems</p>
                                </div>
                            </div>
                        </div>

                        <!-- Q30: Cyber advancement -->
                        <div class="concept-card bg-blue-50 border-l-4 border-blue-500 p-6 rounded-r-lg">
                            <h3 class="text-xl font-semibold text-blue-800 mb-3">
                                <i class="fas fa-question-circle mr-2"></i>Q30. Cyber advancement impact
                            </h3>
                            
                            <div class="mb-4">
                                <p class="text-gray-600 bg-white p-3 rounded border-l-2 border-blue-300">
                                    <strong>Impact:</strong> Cyber advancement has transformed human social life through digital communication, remote work, online education, and virtual communities.
                                </p>
                            </div>

                            <div class="grid grid-cols-2 gap-2">
                                <div class="bg-green-50 p-2 rounded text-center">
                                    <i class="fas fa-plus text-green-500 mb-1"></i>
                                    <h6 class="text-xs font-medium">Positive</h6>
                                    <p class="text-xs text-gray-600">Global connectivity, access to information, efficiency</p>
                                </div>
                                <div class="bg-red-50 p-2    make a webside using the given code and generate the link of web
