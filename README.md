index.html
style.css
script.js
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Aaryushi Creation | Insurance & Financial Services</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
  <style>
    html { scroll-behavior: smooth; }
  </style>
</head>
<body class="bg-slate-50 text-slate-800 font-sans antialiased">

  <!-- Navigation -->
  <header class="sticky top-0 z-50 bg-white/95 backdrop-blur shadow-sm border-b border-slate-100">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex items-center justify-between h-16">
      <div class="flex items-center space-x-2">
        <span class="w-10 h-10 rounded-lg bg-blue-600 flex items-center justify-center text-white font-bold text-xl">A</span>
        <div>
          <span class="text-xl font-bold text-slate-900 tracking-tight">Aaryushi Creation</span>
          <p class="text-[10px] text-slate-500 uppercase tracking-widest leading-none">Financial & Utility Hub</p>
        </div>
      </div>
      <nav class="hidden md:flex space-x-8 text-sm font-medium text-slate-600">
        <a href="#insurance" class="hover:text-blue-600 transition">Insurance</a>
        <a href="#pan" class="hover:text-blue-600 transition">PAN Card</a>
        <a href="#services" class="hover:text-blue-600 transition">More Services</a>
        <a href="#partners" class="hover:text-blue-600 transition">Our Partners</a>
        <a href="#contact" class="hover:text-blue-600 transition">Contact</a>
      </nav>
      <a href="#contact" class="bg-blue-600 hover:bg-blue-700 text-white text-sm font-medium px-4 py-2 rounded-lg shadow-sm transition">
        Get a Quote
      </a>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="relative bg-gradient-to-b from-blue-50 to-white py-16 sm:py-24">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
      <span class="inline-block bg-blue-100 text-blue-700 text-xs font-semibold px-3 py-1 rounded-full uppercase tracking-wider mb-4">
        Trusted Doorstep & Online Assistance
      </span>
      <h1 class="text-4xl sm:text-5xl font-extrabold text-slate-900 tracking-tight max-w-3xl mx-auto leading-tight">
        Complete Insurance & Citizen Financial Services Under One Roof
      </h1>
      <p class="mt-4 text-base sm:text-lg text-slate-600 max-w-2xl mx-auto">
        Protect your family, secure your assets, and streamline PAN & government documentation with trusted guidance and fast turnaround.
      </p>
      <div class="mt-8 flex justify-center gap-4 flex-wrap">
        <a href="#insurance" class="bg-blue-600 hover:bg-blue-700 text-white font-semibold px-6 py-3 rounded-lg shadow-md transition">
          Explore Insurance Plans
        </a>
        <a href="#pan" class="bg-white hover:bg-slate-100 text-slate-700 border border-slate-200 font-semibold px-6 py-3 rounded-lg shadow-sm transition">
          Apply for PAN Card
        </a>
      </div>
    </div>
  </section>

  <!-- Insurance Services -->
  <section id="insurance" class="py-16 bg-white border-y border-slate-100">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="text-center max-w-xl mx-auto mb-12">
        <h2 class="text-3xl font-bold text-slate-900">Insurance Solutions</h2>
        <p class="mt-2 text-slate-600">Tailored policies matched across India's top insurance providers.</p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
        <!-- Life / Term -->
        <div class="p-6 rounded-xl border border-slate-100 bg-slate-50 hover:shadow-md transition">
          <div class="w-12 h-12 rounded-lg bg-blue-600 text-white flex items-center justify-center text-xl mb-4">
            <i class="fa-solid fa-heart-pulse"></i>
          </div>
          <h3 class="text-lg font-semibold text-slate-900">Life & Term Insurance</h3>
          <p class="text-sm text-slate-600 mt-2">Comprehensive protection plans, ULIPs, and retirement pensions with top life insurers.</p>
        </div>

        <!-- Health -->
        <div class="p-6 rounded-xl border border-slate-100 bg-slate-50 hover:shadow-md transition">
          <div class="w-12 h-12 rounded-lg bg-emerald-600 text-white flex items-center justify-center text-xl mb-4">
            <i class="fa-solid fa-shield-halved"></i>
          </div>
          <h3 class="text-lg font-semibold text-slate-900">Health & Mediclaim</h3>
          <p class="text-sm text-slate-600 mt-2">Individual, family floater, and critical illness policies offering cashless hospitalization.</p>
        </div>

        <!-- Motor -->
        <div class="p-6 rounded-xl border border-slate-100 bg-slate-50 hover:shadow-md transition">
          <div class="w-12 h-12 rounded-lg bg-amber-600 text-white flex items-center justify-center text-xl mb-4">
            <i class="fa-solid fa-car"></i>
          </div>
          <h3 class="text-lg font-semibold text-slate-900">Motor Insurance</h3>
          <p class="text-sm text-slate-600 mt-2">Instant renewals and comprehensive coverage for bikes, private cars, and commercial vehicles.</p>
        </div>

        <!-- Commercial / Travel -->
        <div class="p-6 rounded-xl border border-slate-100 bg-slate-50 hover:shadow-md transition">
          <div class="w-12 h-12 rounded-lg bg-purple-600 text-white flex items-center justify-center text-xl mb-4">
            <i class="fa-solid fa-plane-departure"></i>
          </div>
          <h3 class="text-lg font-semibold text-slate-900">Travel & Business</h3>
          <p class="text-sm text-slate-600 mt-2">Fire, shopkeeper policies, marine cargo, and overseas travel insurance packages.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- PAN Card & Citizen Services -->
  <section id="pan" class="py-16 bg-slate-50">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="text-center max-w-xl mx-auto mb-12">
        <h2 class="text-3xl font-bold text-slate-900">PAN Card & Registration Desk</h2>
        <p class="mt-2 text-slate-600">Hassle-free document preparation, tracking, and issue assistance.</p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <div class="bg-white p-6 rounded-xl border border-slate-200 shadow-sm">
          <h3 class="font-bold text-lg text-slate-900 mb-2">New PAN Card (Form 49A)</h3>
          <p class="text-sm text-slate-600">Quick processing for individual adults, minors, and commercial entities using Aadhaar e-KYC.</p>
          <ul class="mt-4 text-xs text-slate-500 space-y-1">
            <li>• Aadhaar biometric verification</li>
            <li>• e-PAN delivery within 48 hours</li>
            <li>• Physical card dispatched to doorstep</li>
          </ul>
        </div>

        <div class="bg-white p-6 rounded-xl border border-slate-200 shadow-sm">
          <h3 class="font-bold text-lg text-slate-900 mb-2">PAN Correction & Reprint</h3>
          <p class="text-sm text-slate-600">Correction of name, DOB, signature, or address misspellings along with damaged card reprint requests.</p>
          <ul class="mt-4 text-xs text-slate-500 space-y-1">
            <li>• Discrepancy resolution</li>
            <li>• Name changes post-marriage</li>
            <li>• Lost PAN recovery support</li>
          </ul>
        </div>

        <div class="bg-white p-6 rounded-xl border border-slate-200 shadow-sm">
          <h3 class="font-bold text-lg text-slate-900 mb-2">Aadhaar-PAN Linking</h3>
          <p class="text-sm text-slate-600">Status checks, penalty challan payment assistance, and immediate linking verification.</p>
          <ul class="mt-4 text-xs text-slate-500 space-y-1">
            <li>• Inoperative PAN rectification</li>
            <li>• IT Department fee challans</li>
            <li>• Status certificate generation</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- Additional Services -->
  <section id="services" class="py-16 bg-white border-y border-slate-100">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="text-center max-w-xl mx-auto mb-12">
        <h2 class="text-3xl font-bold text-slate-900">Additional Services</h2>
        <p class="mt-2 text-slate-600">One-stop documentation and utility assistance.</p>
      </div>

      <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-4 text-center">
        <div class="p-4 rounded-lg bg-slate-50 border border-slate-100">
          <i class="fa-solid fa-passport text-blue-600 text-2xl mb-2"></i>
          <p class="text-sm font-semibold text-slate-800">Passport Seva</p>
        </div>
        <div class="p-4 rounded-lg bg-slate-50 border border-slate-100">
          <i class="fa-solid fa-file-invoice-dollar text-blue-600 text-2xl mb-2"></i>
          <p class="text-sm font-semibold text-slate-800">ITR Assistance</p>
        </div>
        <div class="p-4 rounded-lg bg-slate-50 border border-slate-100">
          <i class="fa-solid fa-id-badge text-blue-600 text-2xl mb-2"></i>
          <p class="text-sm font-semibold text-slate-800">Voter ID Cards</p>
        </div>
        <div class="p-4 rounded-lg bg-slate-50 border border-slate-100">
          <i class="fa-solid fa-briefcase text-blue-600 text-2xl mb-2"></i>
          <p class="text-sm font-semibold text-slate-800">Udyam / MSME</p>
        </div>
        <div class="p-4 rounded-lg bg-slate-50 border border-slate-100">
          <i class="fa-solid fa-money-check text-blue-600 text-2xl mb-2"></i>
          <p class="text-sm font-semibold text-slate-800">Bill Payments</p>
        </div>
        <div class="p-4 rounded-lg bg-slate-50 border border-slate-100">
          <i class="fa-solid fa-stamp text-blue-600 text-2xl mb-2"></i>
          <p class="text-sm font-semibold text-slate-800">Affidavits & Stamp</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Partner Logos / Insurers -->
  <section id="partners" class="py-12 bg-slate-50">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
      <p class="text-xs uppercase tracking-widest text-slate-500 font-semibold mb-6">Offering Plans Across India's Leading Insurance Companies</p>
      <div class="flex flex-wrap justify-center items-center gap-6 text-slate-600 text-sm font-semibold">
        <span class="px-4 py-2 bg-white rounded shadow-sm border border-slate-200">LIC of India</span>
        <span class="px-4 py-2 bg-white rounded shadow-sm border border-slate-200">HDFC ERGO</span>
        <span class="px-4 py-2 bg-white rounded shadow-sm border border-slate-200">ICICI Lombard</span>
        <span class="px-4 py-2 bg-white rounded shadow-sm border border-slate-200">Star Health</span>
        <span class="px-4 py-2 bg-white rounded shadow-sm border border-slate-200">Bajaj Allianz</span>
        <span class="px-4 py-2 bg-white rounded shadow-sm border border-slate-200">Tata AIG</span>
        <span class="px-4 py-2 bg-white rounded shadow-sm border border-slate-200">Care Health</span>
      </div>
    </div>
  </section>

  <!-- Contact & Lead Form -->
  <section id="contact" class="py-16 bg-white">
    <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="bg-slate-50 border border-slate-200 rounded-2xl p-8 sm:p-12 shadow-sm">
        <h2 class="text-2xl sm:text-3xl font-bold text-slate-900 text-center mb-2">Contact Aaryushi Creation</h2>
        <p class="text-sm text-slate-600 text-center mb-8">Send us your requirement to receive immediate policy quotes or document checklists.</p>
        
        <form onsubmit="event.preventDefault(); alert('Inquiry received! We will contact you shortly.');" class="space-y-4">
          <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
            <div>
              <label class="block text-xs font-semibold text-slate-700 uppercase mb-1">Full Name</label>
              <input type="text" required placeholder="Your Name" class="w-full px-4 py-2 text-sm border border-slate-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-600" />
            </div>
            <div>
              <label class="block text-xs font-semibold text-slate-700 uppercase mb-1">Phone Number</label>
              <input type="tel" required placeholder="Mobile Number" class="w-full px-4 py-2 text-sm border border-slate-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-600" />
            </div>
          </div>

          <div>
            <label class="block text-xs font-semibold text-slate-700 uppercase mb-1">Service Required</label>
            <select class="w-full px-4 py-2 text-sm border border-slate-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-600 bg-white">
              <option>Health Insurance</option>
              <option>Life / Term Insurance</option>
              <option>Vehicle / Motor Insurance</option>
              <option>New PAN Card Application</option>
              <option>PAN Correction / Duplicate</option>
              <option>Other Document Services</option>
            </select>
          </div>

          <div>
            <label class="block text-xs font-semibold text-slate-700 uppercase mb-1">Message (Optional)</label>
            <textarea rows="3" placeholder="Specify your requirements (e.g. 2-wheeler renewal, 1 Cr term plan)..." class="w-full px-4 py-2 text-sm border border-slate-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-600"></textarea>
          </div>

          <button type="submit" class="w-full bg-blue-600 hover:bg-blue-700 text-white font-semibold py-3 rounded-lg shadow-sm transition">
            Submit Request
          </button>
        </form>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-slate-900 text-slate-400 text-xs py-8 border-t border-slate-800">
    <div class="max-w-7xl mx-auto px-4 text-center sm:flex sm:justify-between items-center">
      <p>&copy; 2026 Aaryushi Creation. All rights reserved.</p>
      <p class="mt-2 sm:mt-0 text-slate-500">Disclaimer: Insurance is the subject matter of solicitation. Services are facilitated through authorized agency channels.</p>
    </div>
  </footer>

</body>
</html>
