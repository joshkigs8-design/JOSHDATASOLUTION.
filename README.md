<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JOSH DATA SOLUTION | Instant Bundles</title>
    
    <!-- Tailwind CSS for Styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- FontAwesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f0f2f5;
        }
        .hero-bg {
            background: linear-gradient(rgba(17, 24, 39, 0.8), rgba(17, 24, 39, 0.8)), url('https://images.unsplash.com/photo-1519389950473-47ba0277781c?ixlib=rb-4.0.3&auto=format&fit=crop&w=1740&q=80');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
        }
        .glass-card {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.2);
        }
        .bundle-card {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .bundle-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
        .loader {
            border: 3px solid #f3f3f3;
            border-top: 3px solid #16a34a;
            border-radius: 50%;
            width: 24px;
            height: 24px;
            animation: spin 1s linear infinite;
        }
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
    </style>
</head>
<body class="text-gray-800 flex flex-col min-h-screen">

    <!-- Navbar -->
    <nav class="bg-blue-900 text-white shadow-xl sticky top-0 z-50 border-b border-blue-800">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <div class="bg-yellow-400 text-blue-900 p-2 rounded-lg">
                    <i class="fa-solid fa-signal text-lg"></i>
                </div>
                <div>
                    <h1 class="text-xl font-bold tracking-wider leading-none">JOSH DATA</h1>
                    <span class="text-xs text-blue-200 tracking-widest">SOLUTION</span>
                </div>
            </div>
            <div class="hidden md:flex space-x-6">
                <a href="#why-us" class="hover:text-yellow-400 transition font-medium">Why Us</a>
                <a href="#bundles" class="hover:text-yellow-400 transition font-medium">Data Plans</a>
                <a href="#contact" class="hover:text-yellow-400 transition font-medium">Contact</a>
            </div>
            <a href="tel:0742868209" class="bg-yellow-500 hover:bg-yellow-600 text-blue-900 font-bold py-2 px-4 rounded-full transition text-sm shadow-md flex items-center">
                <i class="fa-solid fa-headset mr-2"></i> 0742868209
            </a>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="hero-bg text-white py-24 px-4 text-center relative flex-grow flex items-center justify-center">
        <div class="container mx-auto max-w-4xl">
            <div class="inline-block mb-4 animate-bounce">
                <span class="bg-green-600 text-white text-xs font-bold px-4 py-1.5 rounded-full uppercase tracking-wide shadow-lg border border-green-500">
                    <i class="fa-solid fa-check-circle mr-1"></i> Verified M-Pesa Till: 3715282
                </span>
            </div>
            <h1 class="text-4xl md:text-6xl font-extrabold mb-6 leading-tight">
                Get <span class="text-transparent bg-clip-text bg-gradient-to-r from-yellow-400 to-orange-500">Bingwa Bundles</span><br> Instantly
            </h1>
            <p class="text-gray-300 mb-8 text-lg md:text-xl max-w-2xl mx-auto">
                Secure automated delivery. Select a plan, enter your number, and receive your data within seconds.
            </p>
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="#bundles" class="bg-blue-600 hover:bg-blue-700 text-white font-bold py-4 px-10 rounded-full shadow-lg transition transform hover:scale-105 flex items-center justify-center">
                    <span>View Offers</span>
                    <i class="fa-solid fa-arrow-down ml-2"></i>
                </a>
            </div>
            <p class="mt-6 text-xs text-gray-400">*Limited to 1 purchase per day per number</p>
        </div>
    </header>

    <!-- Why Choose Us Section -->
    <section id="why-us" class="py-16 bg-white border-b border-gray-200">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl font-bold text-gray-800">Why Choose Josh Data?</h2>
                <div class="w-16 h-1.5 bg-yellow-500 mx-auto mt-4 rounded-full"></div>
            </div>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 max-w-6xl mx-auto">
                <!-- Feature 1 -->
                <div class="text-center p-6 rounded-2xl bg-gray-50 hover:bg-white hover:shadow-xl transition border border-transparent hover:border-gray-100">
                    <div class="w-16 h-16 bg-blue-100 text-blue-600 rounded-full flex items-center justify-center mx-auto mb-4 text-2xl shadow-sm">
                        <i class="fa-solid fa-bolt"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2 text-gray-800">Instant Delivery</h3>
                    <p class="text-gray-600 leading-relaxed">No waiting. Our system processes your bundle immediately after payment confirmation.</p>
                </div>
                <!-- Feature 2 -->
                <div class="text-center p-6 rounded-2xl bg-gray-50 hover:bg-white hover:shadow-xl transition border border-transparent hover:border-gray-100">
                    <div class="w-16 h-16 bg-green-100 text-green-600 rounded-full flex items-center justify-center mx-auto mb-4 text-2xl shadow-sm">
                        <i class="fa-solid fa-tag"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2 text-gray-800">Unbeatable Rates</h3>
                    <p class="text-gray-600 leading-relaxed">We offer the most competitive rates for Safaricom Bingwa Bundles in the market.</p>
                </div>
                <!-- Feature 3 -->
                <div class="text-center p-6 rounded-2xl bg-gray-50 hover:bg-white hover:shadow-xl transition border border-transparent hover:border-gray-100">
                    <div class="w-16 h-16 bg-yellow-100 text-yellow-600 rounded-full flex items-center justify-center mx-auto mb-4 text-2xl shadow-sm">
                        <i class="fa-solid fa-shield-halved"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2 text-gray-800">Secure & Reliable</h3>
                    <p class="text-gray-600 leading-relaxed">Pay securely via M-Pesa Till Number 3715282. Your transaction is safe with us.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Bundles Section -->
    <section id="bundles" class="py-20 container mx-auto px-4 relative z-10 bg-[#f0f2f5]">
        <div class="text-center mb-12">
            <h2 class="text-3xl font-bold text-gray-800">Available Plans</h2>
            <div class="w-16 h-1.5 bg-yellow-500 mx-auto mt-4 rounded-full"></div>
            <p class="text-gray-500 mt-4 max-w-2xl mx-auto">Select a package that suits your needs. Click purchase to pay via M-Pesa.</p>
        </div>

        <!-- Grid Container for Bundles -->
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6" id="bundle-container">
            <!-- Bundles will be injected here by JavaScript -->
        </div>
    </section>

    <!-- Terms and Conditions Section -->
    <section class="py-12 bg-white border-t border-gray-200">
        <div class="container mx-auto px-4 max-w-4xl">
            <h2 class="text-2xl font-bold text-gray-800 mb-6 text-center">Terms & Conditions</h2>
            <div class="bg-gray-50 p-8 rounded-xl border border-gray-100 text-sm text-gray-600 space-y-4">
                <div class="flex items-start gap-3">
                    <i class="fa-solid fa-circle-exclamation text-blue-500 mt-1"></i>
                    <p><strong class="text-gray-800 block mb-1">Purchase Limit:</strong> As per Safaricom Bingwa Bundle regulations, each phone number is limited to <strong>one purchase per specific bundle type per day</strong>. Please do not attempt to buy the same bundle twice in 24 hours.</p>
                </div>
                <div class="flex items-start gap-3">
                    <i class="fa-solid fa-mobile-screen text-blue-500 mt-1"></i>
                    <p><strong class="text-gray-800 block mb-1">Correct Details:</strong> Please ensure you enter the correct Safaricom line. Refunds cannot be issued for data sent to the wrong number provided by the user.</p>
                </div>
                <div class="flex items-start gap-3">
                    <i class="fa-solid fa-clock text-blue-500 mt-1"></i>
                    <p><strong class="text-gray-800 block mb-1">Validity Period:</strong> Bundle validity (e.g., 1 hour, 24 hours, 7 days) starts immediately upon receipt of the data confirmation SMS.</p>
                </div>
                <div class="flex items-start gap-3">
                    <i class="fa-solid fa-headset text-blue-500 mt-1"></i>
                    <p><strong class="text-gray-800 block mb-1">Support:</strong> While instant, system delays may occasionally occur. If you do not receive data within 10 minutes, please contact support at 0742868209 with your M-Pesa transaction code.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer / Contact -->
    <footer id="contact" class="bg-gray-900 text-white pt-16 pb-8 border-t border-gray-800">
        <div class="container mx-auto px-4">
            <div class="grid md:grid-cols-3 gap-8 mb-12 text-center md:text-left">
                <div>
                    <h3 class="text-xl font-bold mb-4 text-white">JOSH DATA SOLUTION</h3>
                    <p class="text-gray-400 text-sm">Providing reliable and affordable data solutions to keep you connected. Powered by automation.</p>
                </div>
                <div class="flex flex-col items-center md:items-start">
                    <h4 class="font-bold text-gray-300 mb-4">Payment Info</h4>
                    <div class="flex items-center space-x-3 mb-3">
                        <div class="bg-blue-800 w-10 h-10 rounded-full flex items-center justify-center">
                            <i class="fa-solid fa-store text-white"></i>
                        </div>
                        <div>
                            <p class="text-xs text-gray-400">Buy Goods Till</p>
                            <p class="font-bold text-lg text-yellow-400">3715282</p>
                        </div>
                    </div>
                </div>
                <div class="flex flex-col items-center md:items-start">
                    <h4 class="font-bold text-gray-300 mb-4">Support</h4>
                    <div class="flex items-center space-x-3">
                        <div class="bg-green-600 w-10 h-10 rounded-full flex items-center justify-center">
                            <i class="fa-solid fa-phone text-white"></i>
                        </div>
                        <div>
                            <p class="text-xs text-gray-400">Helpline / Delays</p>
                            <p class="font-bold text-lg">0742868209</p>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="border-t border-gray-800 pt-8 flex flex-col md:flex-row justify-between items-center">
                <p class="text-gray-600 text-sm">&copy; 2024 Josh Data Solution. All Rights Reserved.</p>
                <div class="mt-4 md:mt-0">
                    <a href="https://bingwahybrid.com/JOSHDATASOLUTION" target="_blank" class="text-gray-600 hover:text-white text-sm transition flex items-center">
                        <i class="fa-solid fa-link mr-2"></i> Powered by Bingwa Hybrid
                    </a>
                </div>
            </div>
        </div>
    </footer>

    <!-- Payment Modal -->
    <div id="paymentModal" class="fixed inset-0 bg-black bg-opacity-70 z-[60] hidden flex items-center justify-center px-4 backdrop-blur-sm transition-opacity duration-300">
        <div class="glass-card w-full max-w-md p-6 md:p-8 rounded-2xl shadow-2xl relative animate-fade-in-up bg-white transform transition-all">
            <button onclick="closeModal()" class="absolute top-4 right-4 text-gray-400 hover:text-red-500 transition p-2">
                <i class="fa-solid fa-times text-2xl"></i>
            </button>

            <div class="text-center mb-6">
                <div class="bg-green-100 text-green-600 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4 shadow-sm">
                    <i class="fa-solid fa-mobile-screen-button text-3xl"></i>
                </div>
                <h3 class="text-2xl font-bold text-gray-800">Complete Purchase</h3>
                <p class="text-gray-500 text-sm mt-1">Enter your M-Pesa number to receive the prompt</p>
            </div>

            <!-- Selected Item Preview -->
            <div class="bg-gradient-to-r from-gray-50 to-gray-100 rounded-xl p-4 mb-6 border border-gray-200 flex justify-between items-center shadow-inner">
                <div class="flex items-center">
                    <div id="modal-icon" class="w-10 h-10 rounded-full bg-blue-100 text-blue-600 flex items-center justify-center mr-3">
                        <i class="fa-solid fa-wifi"></i>
                    </div>
                    <div>
                        <p class="font-bold text-gray-800 text-lg leading-tight" id="modal-bundle-name">1 GB</p>
                        <p class="text-xs text-blue-600 font-semibold uppercase tracking-wide" id="modal-bundle-validity">1 Hr</p>
                    </div>
                </div>
                <div class="text-right">
                    <p class="text-xs text-gray-500 uppercase font-bold">Total</p>
                    <p class="font-bold text-green-600 text-xl">KES <span id="modal-bundle-price">19</span></p>
                </div>
            </div>

            <!-- Form -->
            <form id="paymentForm" onsubmit="processPayment(event)">
                <div class="mb-6">
                    <label class="block text-gray-700 text-sm font-bold mb-2 ml-1" for="phone">
                        M-Pesa Number
                    </label>
                    <div class="relative">
                        <span class="absolute left-4 top-3.5 text-gray-500 font-bold text-lg">
                            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a4/Flag_of_Kenya.svg/255px-Flag_of_Kenya.svg.png" class="w-6 h-4 inline mr-1 shadow-sm" alt="KE"> +254
                        </span>
                        <input class="shadow-sm appearance-none border border-gray-300 rounded-xl w-full py-3.5 pl-24 pr-4 text-gray-700 text-lg leading-tight focus:outline-none focus:ring-2 focus:ring-green-500 focus:border-transparent transition" 
                               id="phone" type="tel" placeholder="712345678" required pattern="[0-9]{9}">
                    </div>
                </div>

                <button type="submit" id="payBtn" class="w-full bg-green-600 hover:bg-green-700 text-white font-bold py-4 rounded-xl shadow-lg hover:shadow-xl transition duration-200 flex justify-center items-center group">
                    <span id="btnText" class="group-hover:scale-105 transition-transform">Pay Now</span>
                    <i class="fa-solid fa-lock ml-2 text-sm opacity-70"></i>
                    <div id="loadingSpinner" class="loader ml-3 hidden"></div>
                </button>
            </form>
            
            <div class="mt-4 text-center">
                <p class="text-xs text-gray-400">
                    <i class="fa-solid fa-shield-halved mr-1"></i> Secure payment via Bingwa Hybrid
                </p>
            </div>
        </div>
    </div>

    <!-- JavaScript Logic -->
    <script>
        // Bundle Data
        const bundles = [
            { id: 1, data: "1 GB", duration: "1 Hr", price: 19, icon: "fa-bolt", color: "blue", tag: "Hot" },
            { id: 2, data: "1.5 GB", duration: "3 Hrs", price: 50, icon: "fa-clock", color: "indigo", tag: "" },
            { id: 3, data: "250 MB", duration: "24 Hrs", price: 20, icon: "fa-cloud", color: "teal", tag: "" },
            { id: 4, data: "1 GB", duration: "24 Hrs", price: 99, icon: "fa-star", color: "purple", tag: "Best Value" },
            { id: 5, data: "1.25 GB", duration: "Till Midnight", price: 55, icon: "fa-moon", color: "slate", tag: "" },
            { id: 6, data: "350 MB", duration: "7 Days", price: 49, icon: "fa-calendar-week", color: "orange", tag: "" },
            { id: 7, data: "2.5 GB", duration: "7 Days", price: 300, icon: "fa-calendar-check", color: "green", tag: "Weekly" },
            { id: 8, data: "6 GB", duration: "7 Days", price: 700, icon: "fa-server", color: "red", tag: "Heavy" }
        ];

        // Constants - The Link to Connect
        const API_ENDPOINT = "https://bingwahybrid.com/JOSHDATASOLUTION";
        let selectedBundle = null;

        // Render Bundles
        const container = document.getElementById('bundle-container');
        
        bundles.forEach(bundle => {
            const card = document.createElement('div');
            card.className = "bundle-card bg-white rounded-2xl shadow-md overflow-hidden border border-gray-100 flex flex-col relative";
            
            // Badge logic
            let badgeHTML = '';
            if(bundle.tag) {
                const badgeColor = bundle.tag === 'Hot' ? 'bg-red-500' : 'bg-blue-500';
                badgeHTML = `<span class="absolute top-0 right-0 ${badgeColor} text-white text-xs font-bold px-3 py-1 rounded-bl-lg z-10">${bundle.tag}</span>`;
            }

            card.innerHTML = `
                ${badgeHTML}
                <div class="p-6 flex-grow text-center relative z-0">
                    <div class="inline-flex items-center justify-center w-14 h-14 mb-4 rounded-2xl bg-${bundle.color}-50 text-${bundle.color}-600 shadow-sm transform rotate-3">
                        <i class="fa-solid ${bundle.icon} text-2xl"></i>
                    </div>
                    <h3 class="text-3xl font-bold text-gray-800 mb-1">${bundle.data}</h3>
                    <p class="text-xs font-bold uppercase text-gray-400 tracking-wider mb-4">${bundle.duration}</p>
                    
                    <div class="border-t border-gray-100 pt-4">
                        <span class="text-sm text-gray-500 align-top">KES</span>
                        <span class="text-4xl font-extrabold text-blue-900">${bundle.price}</span>
                    </div>
                </div>
                <div class="p-4 bg-gray-50">
                    <button onclick="openModal(${bundle.id})" class="w-full bg-white border-2 border-blue-600 text-blue-700 hover:bg-blue-600 hover:text-white font-bold py-3 px-4 rounded-xl transition duration-200 flex items-center justify-center">
                        Purchase
                        <i class="fa-solid fa-chevron-right ml-2 text-sm"></i>
                    </button>
                </div>
            `;
            container.appendChild(card);
        });

        // Modal Logic
        const modal = document.getElementById('paymentModal');
        
        function openModal(id) {
            selectedBundle = bundles.find(b => b.id === id);
            if(selectedBundle) {
                document.getElementById('modal-bundle-name').innerText = selectedBundle.data;
                document.getElementById('modal-bundle-validity').innerText = selectedBundle.duration;
                document.getElementById('modal-bundle-price').innerText = selectedBundle.price;
                
                // Update modal icon color dynamically
                const iconContainer = document.getElementById('modal-icon');
                iconContainer.className = `w-10 h-10 rounded-full bg-${selectedBundle.color}-100 text-${selectedBundle.color}-600 flex items-center justify-center mr-3`;
                iconContainer.innerHTML = `<i class="fa-solid ${selectedBundle.icon}"></i>`;
                
                modal.classList.remove('hidden');
            }
        }

        function closeModal() {
            modal.classList.add('hidden');
            document.getElementById('paymentForm').reset();
            resetButtonState();
        }

        function resetButtonState() {
            const btn = document.getElementById('payBtn');
            const btnText = document.getElementById('btnText');
            const spinner = document.getElementById('loadingSpinner');
            
            btn.disabled = false;
            btnText.innerText = "Pay Now";
            spinner.classList.add('hidden');
            btn.classList.remove('bg-gray-400');
            btn.classList.add('bg-green-600', 'hover:bg-green-700');
        }

        // Close modal if clicking outside
        window.onclick = function(event) {
            if (event.target == modal) {
                closeModal();
            }
        }

        // Payment Processing
        async function processPayment(e) {
            e.preventDefault();
            
            const phoneInput = document.getElementById('phone').value;
            // Standardize phone format to 254...
            let formattedPhone = phoneInput;
            if(formattedPhone.startsWith('0')) {
                formattedPhone = '254' + formattedPhone.substring(1);
            } else if (formattedPhone.startsWith('7') || formattedPhone.startsWith('1')) {
                formattedPhone = '254' + formattedPhone;
            }

            const btn = document.getElementById('payBtn');
            const btnText = document.getElementById('btnText');
            const spinner = document.getElementById('loadingSpinner');

            // UI Loading State
            btn.disabled = true;
            btnText.innerText = "Initiating...";
            spinner.classList.remove('hidden');
            btn.classList.remove('bg-green-600', 'hover:bg-green-700');
            btn.classList.add('bg-gray-400');

            // Data payload
            const payload = {
                phone: formattedPhone, // Trying both common naming conventions
                phoneNumber: formattedPhone,
                amount: selectedBundle.price,
                account: "JOSH DATA",
                ref: "WEB_PURCHASE"
            };

            try {
                // Attempt 1: Direct API Call
                const response = await fetch(API_ENDPOINT, {
                    method: 'POST',
                    headers: {
                        'Content-Type': 'application/json',
                    },
                    body: JSON.stringify(payload)
                });

                if (response.ok) {
                    alert(`STK Push sent to ${formattedPhone}. Please enter your PIN.`);
                    closeModal();
                } else {
                    throw new Error("Direct API failed");
                }

            } catch (error) {
                console.log("Direct fetch failed, switching to redirect method...");
                
                // Failover Mechanism:
                // If the direct background fetch fails (often due to CORS/Security on static sites),
                // we redirect the user to the Bingwa page with parameters to ensure the prompt happens.
                
                setTimeout(() => {
                    const fallbackUrl = `${API_ENDPOINT}?phone=${formattedPhone}&amount=${selectedBundle.price}`;
                    
                    // Option A: Open in new tab (Less intrusive)
                     window.open(fallbackUrl, '_blank');
                    
                    alert(`We are connecting you to Bingwa securely to complete payment for ${formattedPhone}.`);
                    closeModal();
                }, 1000);
            }
        }
    </script>
</body>
</html>
