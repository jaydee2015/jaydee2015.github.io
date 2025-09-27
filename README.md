<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jedydah A. Owino | GIS & Data Specialist</title>
    <!-- Load Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Use Inter font -->
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f7f7f7;
            color: #1f2937; /* Dark Gray */
        }
        .hero-bg {
            background-color: #10b981; /* Emerald Green */
            color: white;
        }
    </style>
</head>
<body class="antialiased">

    <!-- Navigation -->
    <header class="sticky top-0 z-50 bg-white shadow-md">
        <nav class="container mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
            <a class="text-xl font-extrabold text-[#10b981] hover:text-[#059669]" href="#">Jedydah Owino</a>
            <div class="flex space-x-4">
                <a href="#about" class="text-gray-600 hover:text-[#059669] font-medium transition duration-150">About</a>
                <a href="#skills" class="text-gray-600 hover:text-[#059669] font-medium transition duration-150">Skills</a>
                <a href="#projects" class="text-gray-600 hover:text-[#059669] font-medium transition duration-150">Projects</a>
            </div>
        </nav>
    </header>
    
    <!-- Hero Section -->
    <section class="hero-bg py-24 md:py-32">
        <div class="container mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h1 class="text-5xl md:text-7xl font-extrabold mb-4 leading-tight">Jedydah A. Owino</h1>
            <p class="text-lg md:text-xl font-light opacity-90 max-w-3xl mx-auto mb-8">
                GIS & Data Specialist | M&E | Project Management | Climate Resilience
            </p>
            <a href="assets/Jedydah_Owino_CV.pdf" target="_blank" class="inline-flex items-center justify-center px-8 py-3 border border-transparent text-base font-medium rounded-lg shadow-lg text-[#10b981] bg-white hover:bg-gray-100 transition duration-300 transform hover:scale-105">
                Download CV
            </a>
        </div>
    </section>

    <!-- About -->
    <section id="about" class="container mx-auto my-16 md:my-24 px-4 sm:px-6 lg:px-8 max-w-5xl">
        <h2 class="text-4xl font-bold mb-6 text-[#10b981] border-b-4 border-[#10b981] pb-2">About Me</h2>
        <div class="text-lg space-y-4 leading-relaxed text-gray-700">
            <p>
                Results-driven **GIS and Data Analyst** with 12+ years of experience leveraging spatial analytics, remote sensing, and data visualization to solve complex challenges across urban planning, public health, **climate resilience**, and international development.
            </p>
            <p>
                I’ve led cross-functional teams and supported multi-country donor-funded programs (World Bank, Mastercard Foundation, FCDO, Save the Children) across **Kenya, Nigeria, Uganda, Mozambique, and Madagascar**.
            </p>
            <p>
                My work has been instrumental in improving data governance, Monitoring & Evaluation (M&E) systems, and evidence-based decision-making through actionable insights derived from **over 300,000 records**.
            </p>
        </div>
    </section>

    <!-- Skills -->
    <section id="skills" class="bg-white py-16 md:py-24">
        <div class="container mx-auto px-4 sm:px-6 lg:px-8 max-w-5xl">
            <h2 class="text-4xl font-bold mb-10 text-[#10b981] text-center">Key Skills</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Skill Column 1: M&E & Data Governance -->
                <div class="p-6 bg-gray-50 rounded-xl shadow-lg hover:shadow-xl transition duration-300">
                    <h3 class="text-xl font-semibold mb-3 text-[#059669]">Data Systems & M&E</h3>
                    <ul class="list-disc list-inside space-y-1 text-gray-700">
                        <li>M&E Systems Development</li>
                        <li>Data Governance & Policy</li>
                        <li>**SQL** (PostgreSQL/PostGIS)</li>
                        <li>Power BI, Tableau (Data Viz)</li>
                    </ul>
                </div>
                
                <!-- Skill Column 2: Geospatial & Tech -->
                <div class="p-6 bg-gray-50 rounded-xl shadow-lg hover:shadow-xl transition duration-300">
                    <h3 class="text-xl font-semibold mb-3 text-[#059669]">Geospatial & Remote Sensing</h3>
                    <ul class="list-disc list-inside space-y-1 text-gray-700">
                        <li>**GIS** (ArcGIS Pro, QGIS, GEE)</li>
                        <li>Remote Sensing (Sentinel, Landsat, UAV)</li>
                        <li>Data Collection (KoBoToolbox, ODK)</li>
                        <li>Python (pandas, geopandas)</li>
                    </ul>
                </div>

                <!-- Skill Column 3: Management & Policy -->
                <div class="p-6 bg-gray-50 rounded-xl shadow-lg hover:shadow-xl transition duration-300">
                    <h3 class="text-xl font-semibold mb-3 text-[#059669]">Project Leadership & Policy</h3>
                    <ul class="list-disc list-inside space-y-1 text-gray-700">
                        <li>Project Management (MS Project, Asana)</li>
                        <li>Training & Capacity Building</li>
                        <li>Quality Assurance & Data Audits</li>
                        <li>Climate & Sustainability Research</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects -->
    <section id="projects" class="container mx-auto my-16 md:my-24 px-4 sm:px-6 lg:px-8 max-w-5xl">
        <h2 class="text-4xl font-bold mb-10 text-[#10b981] border-b-4 border-[#10b981] pb-2">Featured Projects</h2>
        
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Project 1: MIS Development -->
            <div class="bg-white rounded-xl overflow-hidden shadow-xl border border-gray-100 hover:shadow-2xl transition duration-300 transform hover:-translate-y-1">
                <div class="p-6">
                    <h5 class="text-xl font-bold mb-2 text-gray-900">Jiinue Growth Program MIS</h5>
                    <p class="text-gray-600">
                        Designed and implemented a **PostgreSQL-based Management Information System (JMIS)**, migrating 300,000+ records from disparate Excel files. This streamlined M&E reporting for 7+ partner organizations, ensuring data integrity and timely donor compliance.
                    </p>
                </div>
            </div>

            <!-- Project 2: Data Visualization -->
            <div class="bg-white rounded-xl overflow-hidden shadow-xl border border-gray-100 hover:shadow-2xl transition duration-300 transform hover:-translate-y-1">
                <div class="p-6">
                    <h5 class="text-xl font-bold mb-2 text-gray-900">Automated Power BI Dashboards</h5>
                    <p class="text-gray-600">
                        Developed and deployed automated, real-time reporting dashboards using **Power BI** connected to live databases. This initiative reduced manual reporting effort by **40%** and significantly improved the speed and quality of strategic decision-making.
                    </p>
                </div>
            </div>

            <!-- Project 3: Geospatial Analysis -->
            <div class="bg-white rounded-xl overflow-hidden shadow-xl border border-gray-100 hover:shadow-2xl transition duration-300 transform hover:-translate-y-1">
                <div class="p-6">
                    <h5 class="text-xl font-bold mb-2 text-gray-900">Multi-Criteria Suitability Analysis</h5>
                    <p class="text-gray-600">
                        Conducted a **Weighted Overlay Analysis (MCE)** for multi-country water and land resources planning (e.g., in Uganda). Provided a spatial understanding for planning interventions and designing **climate-resilient** water management strategies.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Education & Awards -->
    <section class="bg-gray-100 py-16 md:py-24">
        <div class="container mx-auto px-4 sm:px-6 lg:px-8 max-w-5xl">
            <h2 class="text-4xl font-bold mb-6 text-[#10b981] text-center">Education & Awards</h2>
            
            <div class="bg-white p-8 rounded-xl shadow-xl max-w-3xl mx-auto">
                <h3 class="text-2xl font-semibold mb-4 text-gray-900">Academic History</h3>
                <p class="text-lg text-gray-700 mb-4">
                    <strong>MSc Project Management (Ongoing)</strong> – JKUAT, Kenya (Expected 2025)<br>
                    <strong>BTech, Geo-information Technology</strong> – Technical University of Kenya, 2019<br>
                    <strong>Diploma, Geo-informatics</strong> – TUK, 2012
                </p>

                <h3 class="text-2xl font-semibold mb-4 text-gray-900 border-t pt-4 mt-4 border-gray-200">Recognition</h3>
                <p class="text-lg text-gray-700">
                    **Awards:** Climate Governance & Diplomacy Fellow (2024), Women for Africa Canarias Scholar (2022), Learn Africa Scholar (2024).
                </p>
            </div>
        </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="container mx-auto my-16 md:my-24 px-4 sm:px-6 lg:px-8 max-w-5xl text-center">
        <h2 class="text-4xl font-bold mb-6 text-[#10b981]">Get In Touch</h2>
        <div class="space-y-4 text-lg text-gray-700">
            <p>
                Email: <a href="mailto:jedydahowino@gmail.com" class="text-blue-600 hover:text-blue-800 font-medium transition duration-150">jedydahowino@gmail.com</a>
            </p>
            <p>
                LinkedIn: <a href="https://www.linkedin.com/in/atieno20" target="_blank" class="text-blue-600 hover:text-blue-800 font-medium transition duration-150">
                    https://www.linkedin.com/in/atieno20
                </a>
            </p>
        </div>
    </section>
    
    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-6">
        <div class="container mx-auto px-4 sm:px-6 lg:px-8 text-center text-sm">
            <small>&copy; 2025 Jedydah Owino | Built with Tailwind CSS and powered by GitHub Pages</small>
        </div>
    </footer>
    
</body>
</html>
