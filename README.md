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
            scroll-behavior: smooth; /* Smooth scrolling for navigation */
        }
        /* Primary color is deep Navy Blue (#1e3a8a) for professionalism */
        .primary-color {
            color: #1e3a8a; /* Navy Blue - Tailwind blue-800 */
        }
        .primary-bg {
            background-color: #1e3a8a;
        }
        /* Accent color is calm Sky Blue/Cyan (#38bdf8) */
        .accent-color {
            color: #38bdf8; /* Sky Blue - Tailwind sky-400 */
        }
        .accent-bg {
            background-color: #38bdf8;
        }
        /* Custom class for the hero button text */
        .hero-button-text {
            color: #1e3a8a;
        }
    </style>
</head>
<body class="antialiased">

    <!-- Navigation -->
    <header class="sticky top-0 z-50 bg-white shadow-md">
        <nav class="container mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
            <!-- Updated color classes -->
            <a class="text-xl font-extrabold primary-color hover:text-[#172554]" href="#">Jedydah Owino</a>
            <div class="flex space-x-4">
                <a href="#about" class="text-gray-600 hover:primary-color font-medium transition duration-150">About</a>
                <a href="#skills" class="text-gray-600 hover:primary-color font-medium transition duration-150">Skills</a>
                <a href="#projects" class="text-gray-600 hover:primary-color font-medium transition duration-150">Projects</a>
            </div>
        </nav>
    </header>
    
    <!-- Hero Section -->
    <!-- Updated background color -->
    <section class="primary-bg py-24 md:py-32">
        <div class="container mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h1 class="text-5xl md:text-7xl font-extrabold mb-4 leading-tight text-white">Jedydah A. Owino</h1>
            <p class="text-lg md:text-xl font-light text-white opacity-90 max-w-3xl mx-auto mb-8">
                GIS & Data Specialist | M&E | Project Management | Climate Resilience
            </p>
            <!-- UPDATED: Text changed to "Request CV" and href changed to link to the contact section (#contact) -->
            <a href="#contact" class="inline-flex items-center justify-center px-8 py-3 border border-transparent text-base font-medium rounded-lg shadow-lg hero-button-text bg-white hover:bg-gray-100 transition duration-300 transform hover:scale-105">
                Request CV
            </a>
        </div>
    </section>

    <!-- About -->
    <section id="about" class="container mx-auto my-16 md:my-24 px-4 sm:px-6 lg:px-8 max-w-5xl">
        <!-- Updated color classes -->
        <h2 class="text-4xl font-bold mb-6 primary-color border-b-4 border-accent-color pb-2">About Me</h2>
        <div class="text-lg space-y-4 leading-relaxed text-gray-700">
            <p>
                Results-driven <strong>GIS and Data Analyst</strong> with 12+ years of experience leveraging spatial analytics, remote sensing, and data visualization to solve complex challenges across urban planning, public health, <strong>climate resilience</strong>, and international development.
            </p>
            <p>
                I’ve led cross-functional teams and supported multi-country donor-funded programs (World Bank, Mastercard Foundation, FCDO, Save the Children) across <strong>Kenya, Nigeria, Uganda, Mozambique, and Madagascar</strong>.
            </p>
            <p>
                My work has been instrumental in improving data governance, Monitoring & Evaluation (M&E) systems, and evidence-based decision-making through actionable insights derived from <strong>over 300,000 records</strong>.
            </p>
        </div>
    </section>

    <!-- Skills -->
    <section id="skills" class="bg-white py-16 md:py-24">
        <div class="container mx-auto px-4 sm:px-6 lg:px-8 max-w-5xl">
            <!-- Updated color classes -->
            <h2 class="text-4xl font-bold mb-10 primary-color text-center">Key Skills</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Skill Column 1: M&E & Data Governance -->
                <div class="p-6 bg-gray-50 rounded-xl shadow-lg hover:shadow-xl transition duration-300">
                    <h3 class="text-xl font-semibold mb-3 primary-color">Data Systems & M&E</h3>
                    <ul class="list-disc list-inside space-y-1 text-gray-700">
                        <li>M&E Systems Development</li>
                        <li>Data Governance & Policy</li>
                        <li><strong>SQL</strong> (PostgreSQL/PostGIS)</li>
                        <li>Power BI, Tableau (Data Viz)</li>
                    </ul>
                </div>
                
                <!-- Skill Column 2: Geospatial & Tech -->
                <div class="p-6 bg-gray-50 rounded-xl shadow-lg hover:shadow-xl transition duration-300">
                    <h3 class="text-xl font-semibold mb-3 primary-color">Geospatial & Remote Sensing</h3>
                    <ul class="list-disc list-inside space-y-1 text-gray-700">
                        <li><strong>GIS</strong> (ArcGIS Pro, QGIS, GEE)</li>
                        <li>Remote Sensing (Sentinel, Landsat, UAV)</li>
                        <li>Data Collection (KoBoToolbox, ODK)</li>
                        <li>Python (pandas, geopandas)</li>
                    </ul>
                </div>

                <!-- Skill Column 3: Management & Policy -->
                <div class="p-6 bg-gray-50 rounded-xl shadow-lg hover:shadow-xl transition duration-300">
                    <h3 class="text-xl font-semibold mb-3 primary-color">Project Leadership & Policy</h3>
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
        <!-- Updated color classes -->
        <h2 class="text-4xl font-bold mb-10 primary-color border-b-4 border-accent-color pb-2">Featured Projects</h2>
        
        <!-- Project cards stack vertically, full-width up to max-w-4xl, with vertical spacing (space-y-16) -->
        <div class="space-y-16">
            
            <!-- Project 1: MIS Development -->
            <div class="bg-white rounded-xl shadow-xl border border-gray-100 hover:shadow-2xl transition duration-300 transform hover:-translate-y-1 overflow-hidden max-w-4xl mx-auto">
                <div class="p-6">
                    <h5 class="text-2xl font-bold mb-3 text-gray-900 primary-color">Jiinue Growth Program MIS</h5>
                    <p class="text-gray-700 mb-4 leading-relaxed">
                        Designed and implemented a <strong>PostgreSQL-based Management Information System (JMIS)</strong>, migrating 300,000+ records from disparate Excel files. This streamlined M&E reporting for 7+ partner organizations, ensuring data integrity and timely donor compliance.
                    </p>
                </div>
                <!-- LIVE IMAGE URL 1 -->
                <img src="https://jaydee2015.github.io/Sample.jpg" 
                     alt="Jiinue Growth Program MIS Screenshot" 
                     onerror="this.onerror=null; this.src='https://placehold.co/800x450/e0e0e0/4a4a4a?text=Image+Unavailable'"
                     class="w-full h-auto object-cover border-t border-gray-100">
            </div>

            <!-- Project 2: Catchment and Land Use Analysis  -->
            <div class="bg-white rounded-xl shadow-xl border border-gray-100 hover:shadow-2xl transition duration-300 transform hover:-translate-y-1 overflow-hidden max-w-4xl mx-auto">
                <div class="p-6">
                    <h5 class="text-2xl font-bold mb-3 text-gray-900 primary-color">Catchment and Land Use Analysis</h5>
                    <p class="text-gray-700 mb-4 leading-relaxed">
                        the spatial distribution of three major hydrological systems—the Lokok, Lokere, and Awoja Catchments—and their respective sub-catchments. It overlays this hydrological framework with current Land Use data, revealing distinct regional characteristics:

Northern Catchments (Lokok/Lokere): Dominated by Trees, Shrubs, and Grassland, indicating semi-arid, mountainous, or grazing areas, which are critical for headwater protection.

Southern Catchment (Awoja): Characterized by extensive Cropland and vast, connected Wetlands, signifying intensive agriculture and large floodplain ecosystems.

The analysis is crucial for managing water resources, mitigating flood risks, and addressing the impact of agricultural runoff on the region's vital wetland systems that drain toward Lake Kyoga..
                    </p>
                </div>
                <!-- LIVE IMAGE URL 2 (No change here, still uses Power BI Dashboard.png) -->
                <img src="https://jaydee2015.github.io/Catchment%20Mapping.png" 
                     alt="Automated Power BI Dashboard Screenshot" 
                     onerror="this.onerror=null; this.src='https://placehold.co/800x450/e0e0e0/4a4a4a?text=Image+Unavailable'"
                     class="w-full h-auto object-cover border-t border-gray-100">
            </div>

            <!-- Project 3: Geospatial Analysis - UPDATED DESCRIPTION -->
            <div class="bg-white rounded-xl shadow-xl border border-gray-100 hover:shadow-2xl transition duration-300 transform hover:-translate-y-1 overflow-hidden max-w-4xl mx-auto">
                <div class="p-6">
                    <h5 class="text-2xl font-bold mb-3 text-gray-900 primary-color">Multi-Criteria Suitability Analysis</h5>
                    <p class="text-gray-700 mb-4 leading-relaxed">
                        Conducted a Weighted Overlay Analysis (MCE) for intersection of child-care, poverty and climate effect in Madagascar, focusing on Atsimo-Andrefana, Androy, and Anosy regions. The analysis revealed areas of very high suitability (red/orange) in Atsimo-Andrefana and Androy, while Anosy presented a mixed profile, providing crucial spatial intelligence for targeted interventions.
                    </p>
                </div>
                <!-- LIVE IMAGE URL 3 - Updated link in previous turn -->
                <img src="https://jaydee2015.github.io/Suitability.png" 
                     alt="Multi-Criteria Suitability Catchment Map" 
                     onerror="this.onerror=null; this.src='https://placehold.co/800x450/e0e0e0/4a4a4a?text=Image+Unavailable'"
                     class="w-full h-auto object-cover border-t border-gray-100">
            </div>
                        <!-- Project 4: Urban Development & Digital Mapping Consultancy (NEW) -->
            <div class="bg-white rounded-xl shadow-xl border border-gray-100 hover:shadow-2xl transition duration-300 transform hover:-translate-y-1 overflow-hidden max-w-4xl mx-auto">
                <div class="p-6">
                    <h5 class="text-2xl font-bold mb-3 text-gray-900 primary-color">Urban Development & Digital Mapping Consultancy</h5>
                    <p class="text-gray-700 mb-4 leading-relaxed">
                        Led large-scale urban development and digital mapping initiatives across seven Kenyan counties (Meru, Samburu, Siaya, Kisumu, Machakos, Nyamira, Makueni). The core focus was preparing Integrated Strategic Urban Development Plans (ISUDPs) and Local Physical Development Plans (LPDPs) for sustainable planning and informal settlement upgrading.
                    </p>
                    <p class="text-gray-700 mb-4 leading-relaxed">
                       conducted reconnaissance, base map preparation, and socio-economic data analysis, using GIS and spatial modeling to design key sectoral improvement plans (transport, housing, environment). This provided county governments with robust, data-driven planning tools to enhance urban management and climate-resilient strategies.
                    </p>
                </div>
                <!-- LIVE IMAGE URL 4 -->
                <img src="https://jaydee2015.github.io/Local%20Development%20Plan.png" 
                     alt="Urban Development Planning Map of Kenyan County" 
                     onerror="this.onerror=null; this.src='https://placehold.co/800x450/e0e0e0/4a4a4a?text=Image+Unavailable'"
                     class="w-full h-auto object-cover border-t border-gray-100">
        </div>
        </div>
    </section>

    <!-- Education & Awards -->
    <section class="bg-gray-100 py-16 md:py-24">
        <div class="container mx-auto px-4 sm:px-6 lg:px-8 max-w-5xl">
            <!-- Updated color classes -->
            <h2 class="text-4xl font-bold mb-6 primary-color text-center">Education & Awards</h2>
            
            <div class="bg-white p-8 rounded-xl shadow-xl max-w-3xl mx-auto">
                <h3 class="text-2xl font-semibold mb-4 text-gray-900">Academic History</h3>
                <p class="text-lg text-gray-700 mb-4">
                    <strong>MSc Project Management (Ongoing)</strong> – JKUAT, Kenya (Expected 2025)<br>
                    <strong>BTech, Geo-information Technology</strong> – Technical University of Kenya, 2019<br>
                    <strong>Diploma, Geo-informatics</strong> – TUK, 2012
                </p>

                <h3 class="text-2xl font-semibold mb-4 text-gray-900 border-t pt-4 mt-4 border-gray-200">Recognition</h3>
                <p class="text-lg text-gray-700">
                    <strong>Awards:</strong> Climate Governance & Diplomacy Fellow (2024), Women for Africa Canarias Scholar (2022), Learn Africa Scholar (2024).
                </p>
            </div>
        </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="container mx-auto my-16 md:my-24 px-4 sm:px-6 lg:px-8 max-w-5xl text-center">
        <!-- Updated color classes -->
        <h2 class="text-4xl font-bold mb-6 primary-color">Get In Touch</h2>
        <p class="text-xl text-gray-800 mb-8">
            I look forward to discussing how my GIS and data expertise can support your next project.
        </p>
        <div class="space-y-4 text-lg text-gray-700 max-w-sm mx-auto p-6 bg-white rounded-xl shadow-lg border border-gray-200">
            <p>
                <strong class="primary-color">Email:</strong> <a href="mailto:jedydahowino@gmail.com" class="text-blue-600 hover:text-blue-800 font-medium transition duration-150">jedydahowino@gmail.com</a>
            </p>
            <p>
                <strong class="primary-color">LinkedIn:</strong> <a href="https://www.linkedin.com/in/atieno20" target="_blank" class="text-blue-600 hover:text-blue-800 font-medium transition duration-150">
                    Connect on LinkedIn
                </a>
            </p>
            <p class="pt-4 text-sm text-gray-500">
                Mention "Request CV" in your message for a copy of my full resume.
            </p>
        </div>
    </section>
    
    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-6">
        <div class="container mx-auto px-4 sm:px-6 lg:px-8 text-center text-sm">
            <small>&copy; 2025 Jedydah Owino | GIS & Data Specialist</small>
        </div>
    </footer>
    
</body>
</html>
