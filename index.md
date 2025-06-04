<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Transform Your Health & Fitness | Coaching for Men 30+</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            /* Base background and text colors will be set by JS based on theme */
        }
        /* Custom styles for form focus */
        input:focus, textarea:focus {
            outline: none;
            box-shadow: 0 0 0 3px rgba(59, 130, 246, 0.5); /* Blue focus ring */
            border-color: #3b82f6; /* Blue border */
        }
    </style>
</head>
<body class="antialiased" data-theme="dark"> <!-- Default theme set to dark -->

    <!-- Hero Section -->
    <header id="main-header" data-theme-target="header-gradient" class="relative py-20 md:py-32 overflow-hidden rounded-b-lg">
        <!-- Changed placeholder text for background image -->
        <div class="absolute inset-0 bg-cover bg-center opacity-30" style="background-image: url('https://placehold.co/1920x1080/0f172a/cbd5e1?text=Tactical+Performance+Training');"></div>
        <div class="container mx-auto px-4 relative z-10 text-center">
            <!-- Theme Toggle Button -->
            <button id="theme-toggle" class="absolute top-4 right-4 p-2 rounded-full bg-gray-700 text-white hover:bg-gray-600 focus:outline-none focus:ring-2 focus:ring-gray-500 transition duration-200">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 3v1m0 16v1m9-9h1M4 12H3m15.325 5.325l-.707.707M6.372 6.372l-.707-.707m12.728 0l-.707-.707M6.372 17.628l-.707.707M16 12a4 4 0 11-8 0 4 4 0 018 0z" />
                </svg>
            </button>

            <h1 data-theme-target="header-main-text" class="text-4xl md:text-6xl font-extrabold leading-tight mb-4 rounded-md">
                Unleash Your Potential: <span id="hero-span" data-theme-target="hero-span-text" class="block">Elite Fitness & Nutrition Coaching</span>
            </h1>
            <p data-theme-target="header-main-text" class="text-xl md:text-2xl mb-8 max-w-3xl mx-auto rounded-md">
                Our coaching builds resilience, strength, and vitality through cutting-edge functional movement and foundational nutrition strategies.
            </p>
            <a href="#apply-now" id="hero-cta" data-theme-target="hero-cta-button" class="inline-block font-bold py-3 px-8 rounded-full shadow-lg transition duration-300 ease-in-out transform hover:scale-105">
                Apply for Your Free Discovery Call
            </a>
        </div>
    </header>

    <!-- Problem/Solution Section -->
    <section id="problem-section" data-theme-target="section-bg-1" class="py-16 md:py-24 rounded-lg shadow-md mx-4 md:mx-auto mt-8 max-w-6xl">
        <div class="container mx-auto px-4 text-center">
            <h2 id="problem-heading" data-theme-target="section-heading" class="text-3xl md:text-4xl font-bold mb-12 rounded-md">
                Are You Experiencing These Challenges?
            </h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div id="problem-card-1" data-theme-target="card-bg-1" class="p-6 rounded-lg shadow-sm hover:shadow-md transition duration-300 ease-in-out">
                    <h3 data-theme-target="card-heading-text" class="text-xl font-semibold mb-3">Demanding Shifts & Chronic Stress</h3>
                    <p data-theme-target="card-body-text">Struggling to maintain energy and focus through long, unpredictable hours?</p>
                </div>
                <div id="problem-card-2" data-theme-target="card-bg-1" class="p-6 rounded-lg shadow-sm hover:shadow-md transition duration-300 ease-in-out">
                    <h3 data-theme-target="card-heading-text" class="text-xl font-semibold mb-3">Maintaining Peak Performance & Preventing Injury</h3>
                    <p data-theme-target="card-body-text">Worried about physical decline or injuries impacting your career and quality of life?</p>
                </div>
                <div id="problem-card-3" data-theme-target="card-bg-1" class="p-6 rounded-lg shadow-sm hover:shadow-md transition duration-300 ease-in-out">
                    <h3 data-theme-target="card-heading-text" class="text-xl font-semibold mb-3">Navigating Conflicting Health Advice</h3>
                    <p data-theme-target="card-body-text">Tired of fad diets and complex workout routines that don't fit your real-world demands?</p>
                </div>
            </div>
            <p id="problem-text-bottom" data-theme-target="card-body-text" class="text-lg md:text-xl mt-12 rounded-md">
                You're not alone. We understand the unique demands on men 30+ and those in high-stakes professions.
                <span class="font-semibold block mt-2">It's time for a solution that truly works for your life.</span>
            </p>
        </div>
    </section>

    <!-- How It Works / Benefits Section -->
    <section id="benefits-section" data-theme-target="section-bg-2" class="py-16 md:py-24 rounded-lg shadow-md mx-4 md:mx-auto mt-8 max-w-6xl">
        <div class="container mx-auto px-4 text-center">
            <h2 id="benefits-heading" data-theme-target="section-heading" class="text-3xl md:text-4xl font-bold mb-12 rounded-md">
                Our Coaching: Your Path to Lasting Transformation
            </h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div id="benefit-card-1" data-theme-target="card-bg-2" class="flex flex-col items-center p-6 rounded-lg shadow-sm hover:shadow-md transition duration-300 ease-in-out">
                    <div data-theme-target="emoji-color" class="text-5xl mb-4">💪</div> <!-- Emoji for icon -->
                    <h3 data-theme-target="card-heading-text" class="text-xl font-semibold mb-3">Functional Strength & Resilience</h3>
                    <p data-theme-target="card-body-text">Build real-world strength and physical resilience that translates directly to your demanding role and everyday life.</p>
                </div>
                <div id="benefit-card-2" data-theme-target="card-bg-2" class="flex flex-col items-center p-6 rounded-lg shadow-sm hover:shadow-md transition duration-300 ease-in-out">
                    <div data-theme-target="emoji-color" class="text-5xl mb-4">🍏</div> <!-- Emoji for icon -->
                    <h3 data-theme-target="card-heading-text" class="text-xl font-semibold mb-3">Foundational Nutrition Strategies</h3>
                    <p data-theme-target="card-body-text">Fuel your body with nutrient-dense foods, optimizing energy, recovery, and long-term health without restrictive diets.</p>
                </div>
                <div id="benefit-card-3" data-theme-target="card-bg-2" class="flex flex-col items-center p-6 rounded-lg shadow-sm hover:shadow-md transition duration-300 ease-in-out">
                    <div data-theme-target="emoji-color" class="text-5xl mb-4">📈</div> <!-- Emoji for icon -->
                    <h3 data-theme-target="card-heading-text" class="text-xl font-semibold mb-3">Strategic Recovery & Longevity</h3>
                    <p data-theme-target="card-body-text">Implement smart recovery tactics to combat stress, prevent burnout, and ensure you can perform at your best for years to come.</p>
                </div>
                <div id="benefit-card-4" data-theme-target="card-bg-2" class="flex flex-col items-center p-6 rounded-lg shadow-sm hover:shadow-md transition duration-300 ease-in-out">
                    <div data-theme-target="emoji-color" class="text-5xl mb-4">🧠</div> <!-- Emoji for icon -->
                    <h3 data-theme-target="card-heading-text" class="text-xl font-semibold mb-3">Adaptive Movement & Injury Prevention</h3>
                    <p data-theme-target="card-body-text">Learn movement patterns that enhance mobility and stability, drastically reducing your risk of common injuries.</p>
                </div>
                <div id="benefit-card-5" data-theme-target="card-bg-2" class="flex flex-col items-center p-6 rounded-lg shadow-sm hover:shadow-md transition duration-300 ease-in-out">
                    <div data-theme-target="emoji-color" class="text-5xl mb-4">🛡️</div> <!-- Emoji for icon -->
                    <h3 data-theme-target="card-heading-text" class="text-xl font-semibold mb-3">Personalized Action Plans</h3>
                    <p data-theme-target="card-body-text">Custom nutrition and workout strategies designed to fit your unique operational demands and personal goals.</p>
                </div>
                <div id="benefit-card-6" data-theme-target="card-bg-2" class="flex flex-col items-center p-6 rounded-lg shadow-sm hover:shadow-md transition duration-300 ease-in-out">
                    <div data-theme-target="emoji-color" class="text-5xl mb-4">👨‍👩‍👧‍👦</div> <!-- Emoji for icon -->
                    <h3 data-theme-target="card-heading-text" class="text-xl font-semibold mb-3">Sustainable Habits for Life</h3>
                    <p data-theme-target="card-body-text">Develop powerful, lasting habits that support your health, career, and family life without constant struggle.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonial Section -->
    <section id="testimonial-section" data-theme-target="section-bg-1" class="py-16 md:py-24 rounded-lg shadow-md mx-4 md:mx-auto mt-8 max-w-6xl">
        <div class="container mx-auto px-4 text-center">
            <h2 id="testimonial-heading" data-theme-target="section-heading" class="text-3xl md:text-4xl font-bold mb-12 rounded-md">
                Hear From Our Clients
            </h2>
            <div id="testimonial-box" data-theme-target="card-bg-1" class="max-w-3xl mx-auto p-8 rounded-lg shadow-lg">
                <p id="testimonial-text" data-theme-target="testimonial-italic-text" class="text-xl italic mb-6 leading-relaxed">
                    "Before coaching, I was stuck in a rut, feeling tired and out of shape. In just 3 months, I've lost 15 lbs, gained significant strength, and have more energy than I did in my 20s. This program is a game-changer for busy professionals."
                </p>
                <p id="testimonial-author" data-theme-target="card-heading-text" class="text-lg font-semibold">- Mark T., 42, Business Owner</p>
                <div class="mt-4 flex justify-center">
                    <!-- Placeholder for a small client image/avatar -->
                    <img id="testimonial-img" data-theme-target="testimonial-image-border" src="https://placehold.co/80x80/3b82f6/ffffff?text=Mark+T" alt="Client Testimonial Photo" class="w-20 h-20 rounded-full object-cover border-4">
                </div>
            </div>
        </div>
    </section>

    <!-- Latest Articles / Blog Section -->
    <section id="blog-section" data-theme-target="section-bg-2" class="py-16 md:py-24 rounded-lg shadow-md mx-4 md:mx-auto mt-8 max-w-6xl">
        <div class="container mx-auto px-4 text-center">
            <h2 id="blog-heading" data-theme-target="section-heading" class="text-3xl md:text-4xl font-bold mb-12 rounded-md">
                Latest Articles from Our Blog
            </h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Blog Post 1 -->
                <div id="blog-card-1" data-theme-target="card-bg-2" class="rounded-lg shadow-sm hover:shadow-md transition duration-300 ease-in-out overflow-hidden">
                    <img src="https://placehold.co/400x250/2d3748/a0aec0?text=Healthy+Eating" alt="Blog Post Image" class="w-full h-48 object-cover">
                    <div class="p-6 text-left">
                        <h3 data-theme-target="card-heading-text" class="text-xl font-semibold mb-2">Optimal Eating: Fueling Your Body for Peak Performance</h3>
                        <p data-theme-target="card-body-text" class="text-sm mb-4">Discover how to optimize your diet for sustained energy and recovery, based on timeless principles.</p>
                        <a id="blog-link-1" href="#" data-theme-target="blog-link" class="font-medium">Read More &rarr;</a>
                    </div>
                </div>
                <!-- Blog Post 2 -->
                <div id="blog-card-2" data-theme-target="card-bg-2" class="rounded-lg shadow-sm hover:shadow-md transition duration-300 ease-in-out overflow-hidden">
                    <img src="https://placehold.co/400x250/2d3748/a0aec0?text=Strength+Training" alt="Blog Post Image" class="w-full h-48 object-cover">
                    <div class="p-6 text-left">
                        <h3 data-theme-target="card-heading-text" class="text-xl font-semibold mb-2">Functional Fitness for First Responders: Beyond the Gym</h3>
                        <p data-theme-target="card-body-text" class="text-sm mb-4">Learn how to train for real-world demands, enhancing your strength and agility on the job.</p>
                        <a id="blog-link-2" href="#" data-theme-target="blog-link" class="font-medium">Read More &rarr;</a>
                    </div>
                </div>
                <!-- Blog Post 3 -->
                <div id="blog-card-3" data-theme-target="card-bg-2" class="rounded-lg shadow-sm hover:shadow-md transition duration-300 ease-in-out overflow-hidden">
                    <img src="https://placehold.co/400x250/2d3748/a0aec0?text=Mindset" alt="Blog Post Image" class="w-full h-48 object-cover">
                    <div class="p-6 text-left">
                        <h3 data-theme-target="card-heading-text" class="text-xl font-semibold mb-2">Aging with Strength: Longevity Strategies for Men 30+</h3>
                        <p data-theme-target="card-body-text" class="text-sm mb-4">Discover how mental resilience impacts your fitness journey and overall well-being.</p>
                        <a id="blog-link-3" href="#" data-theme-target="blog-link" class="font-medium">Read More &rarr;</a>
                    </div>
                </div>
            </div>
            <div class="mt-12">
                <a href="#" id="blog-view-all-button" data-theme-target="form-submit-button" class="inline-block font-bold py-3 px-8 rounded-full shadow-lg transition duration-300 ease-in-out transform hover:scale-105">
                    View All Articles
                </a>
            </div>
        </div>
    </section>

    <!-- Lead Capture Form Section -->
    <section id="form-section" data-theme-target="form-section-gradient" class="py-16 md:py-24 text-white rounded-lg shadow-md mx-4 md:mx-auto mt-8 mb-8 max-w-6xl">
        <div class="container mx-auto px-4 text-center">
            <h2 id="form-heading" data-theme-target="section-heading" class="text-3xl md:text-4xl font-bold mb-6 rounded-md">
                Ready to Transform Your Health?
            </h2>
            <p id="form-subheading" data-theme-target="hero-span-text" class="text-xl md:text-2xl mb-12 max-w-3xl mx-auto rounded-md">
                Spaces are limited to ensure personalized attention. Apply now for a <span class="font-bold">Free Discovery Call</span> to see if our coaching is the right fit for you.
            </p>

            <div id="form-container" data-theme-target="card-bg-1" class="p-8 md:p-12 rounded-lg shadow-2xl max-w-2xl mx-auto">
                <!-- IMPORTANT: Replace "YOUR_GOOGLE_FORM_ACTION_URL" with your actual Google Form's formResponse URL -->
                <!-- And replace "entry.YOUR_NAME_ENTRY_ID", etc., with your actual Google Form field IDs -->
                <form action="YOUR_GOOGLE_FORM_ACTION_URL" method="POST" target="_blank">
                    <div class="mb-6 text-left">
                        <label id="name-label" data-theme-target="form-label-text" for="name" class="block text-sm font-bold mb-2">Full Name:</label>
                        <input type="text" id="name-input" name="entry.YOUR_NAME_ENTRY_ID" placeholder="John Doe" required
                               data-theme-target="form-input-bg" class="shadow appearance-none border rounded-md w-full py-3 px-4 leading-tight focus:ring-blue-500 focus:border-blue-500 transition duration-200 ease-in-out">
                    </div>
                    <div class="mb-6 text-left">
                        <label id="email-label" data-theme-target="form-label-text" for="email" class="block text-sm font-bold mb-2">Email Address:</label>
                        <input type="email" id="email-input" name="entry.YOUR_EMAIL_ENTRY_ID" placeholder="john.doe@example.com" required
                               data-theme-target="form-input-bg" class="shadow appearance-none border rounded-md w-full py-3 px-4 leading-tight focus:ring-blue-500 focus:border-blue-500 transition duration-200 ease-in-out">
                    </div>
                    <div class="mb-6 text-left">
                        <label id="age-label" data-theme-target="form-label-text" for="age" class="block text-sm font-bold mb-2">Your Age:</label>
                        <input type="number" id="age-input" name="entry.YOUR_AGE_ENTRY_ID" placeholder="e.g., 38" min="30" required
                               data-theme-target="form-input-bg" class="shadow appearance-none border rounded-md w-full py-3 px-4 leading-tight focus:ring-blue-500 focus:border-blue-500 transition duration-200 ease-in-out">
                    </div>
                    <div class="mb-8 text-left">
                        <label id="goals-label" data-theme-target="form-label-text" for="goals" class="block text-sm font-bold mb-2">What are your primary health & fitness goals?</label>
                        <textarea id="goals-textarea" name="entry.YOUR_GOALS_ENTRY_ID" rows="4" placeholder="e.g., Lose weight, build muscle, increase energy, improve health markers..." required
                                  data-theme-target="form-input-bg" class="shadow appearance-none border rounded-md w-full py-3 px-4 leading-tight focus:ring-blue-500 focus:border-blue-500 transition duration-200 ease-in-out"></textarea>
                    </div>

                    <button type="submit" id="form-submit-button" data-theme-target="form-submit-button"
                            class="w-full font-bold py-3 px-6 rounded-full shadow-lg transition duration-300 ease-in-out transform hover:scale-105 focus:outline-none focus:ring-4 focus:ring-blue-300">
                        Submit Application
                    </button>
                </form>
                <!-- Message box for form submission feedback -->
                <!-- Note: With direct Google Form submission, this message box might not be ideal
                     as the page will redirect. You might prefer a "Thank You" page on your site. -->
                <div id="form-message" class="mt-6 p-4 rounded-md text-sm hidden"></div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer id="main-footer" data-theme-target="footer-bg" class="py-8 rounded-t-lg">
        <div class="container mx-auto px-4 text-center text-sm">
            <p id="footer-text" data-theme-target="footer-text">&copy; 2024 Tactical Performance Training. All rights reserved.</p>
            <div class="mt-2">
                <a id="footer-privacy" href="#" data-theme-target="footer-link" class="mx-2">Privacy Policy</a>
                <span id="footer-divider-1" data-theme-target="footer-divider">|</span>
                <a id="footer-terms" href="#" data-theme-target="footer-link" class="mx-2">Terms of Service</a>
                <span id="footer-divider-2" data-theme-target="footer-divider">|</span>
                <a id="footer-blog" href="#" data-theme-target="footer-link" class="mx-2">Blog</a>
            </div>
        </div>
    </footer>
    <script>
        // Define theme configurations
        const themeConfig = {
            'body': {
                dark: ['bg-gray-900', 'text-gray-200'],
                light: ['bg-gray-100', 'text-gray-800']
            },
            'header-gradient': {
                dark: ['from-gray-900', 'to-blue-900'],
                light: ['from-blue-700', 'to-indigo-800']
            },
            'header-main-text': { // New target for main header text
                dark: ['text-white'],
                light: ['text-gray-900'] // Darker text for light theme
            },
            'hero-span-text': {
                dark: ['text-blue-300'],
                light: ['text-blue-700'] // Darker blue for light theme
            },
            'hero-cta-button': {
                dark: ['bg-blue-500', 'hover:bg-blue-600', 'text-white'],
                light: ['bg-white', 'hover:bg-blue-100', 'text-blue-700']
            },
            'section-bg-1': { // Problem/Solution, Testimonial sections
                dark: ['bg-gray-800'],
                light: ['bg-white']
            },
            'section-bg-2': { // Benefits, Blog sections
                dark: ['bg-gray-900'],
                light: ['bg-blue-50']
            },
            'section-heading': {
                dark: ['text-blue-300'],
                light: ['text-gray-800']
            },
            'card-bg-1': { // Problem/Solution cards, Testimonial box, Form container
                dark: ['bg-gray-700'],
                light: ['bg-gray-50']
            },
            'card-bg-2': { // Benefits cards, Blog cards
                dark: ['bg-gray-800'],
                light: ['bg-white']
            },
            'card-heading-text': { // Card headings
                dark: ['text-white'],
                light: ['text-gray-700']
            },
            'card-body-text': { // Card body text, problem-text-bottom
                dark: ['text-gray-300'],
                light: ['text-gray-600']
            },
            'emoji-color': {
                dark: ['text-blue-400'],
                light: ['text-blue-600']
            },
            'testimonial-italic-text': {
                dark: ['text-gray-200'],
                light: ['text-gray-700']
            },
            'testimonial-image-border': {
                dark: ['border-blue-400'],
                light: ['border-blue-200']
            },
            'blog-link': {
                dark: ['text-blue-400', 'hover:text-blue-500'],
                light: ['text-blue-600', 'hover:text-blue-800']
            },
            'form-section-gradient': { // Form section background
                dark: ['from-gray-900', 'to-blue-900'],
                light: ['from-blue-700', 'to-indigo-800']
            },
            'form-label-text': {
                dark: ['text-gray-200'],
                light: ['text-gray-700']
            },
            'form-input-bg': {
                dark: ['bg-gray-800'],
                light: ['bg-white']
            },
            'form-input-text': {
                dark: ['text-white'],
                light: ['text-gray-700']
            },
            'form-submit-button': {
                dark: ['bg-blue-600', 'hover:bg-blue-700', 'text-white'],
                light: ['bg-blue-600', 'hover:bg-blue-700', 'text-white'] // This button is already good
            },
            'form-message-success': {
                dark: ['bg-green-700', 'text-white'],
                light: ['bg-green-100', 'text-green-700']
            },
            'footer-bg': {
                dark: ['bg-gray-900'],
                light: ['bg-gray-800']
            },
            'footer-text': {
                dark: ['text-gray-400'],
                light: ['text-gray-300']
            },
            'footer-link': {
                dark: ['text-gray-500', 'hover:text-white'],
                light: ['text-gray-400', 'hover:text-white']
            },
            'footer-divider': {
                dark: ['text-gray-600'],
                light: ['text-gray-500']
            }
        };

        // Function to apply theme classes to an element
        function applyClasses(element, classesToAdd, classesToRemove) {
            if (!element) return;
            if (classesToRemove) {
                element.classList.remove(...classesToRemove);
            }
            if (classesToAdd) {
                element.classList.add(...classesToAdd);
            }
        }

        // Function to apply theme classes based on a given theme name
        function applyTheme(themeName) {
            const body = document.body;
            // Remove all possible theme classes first to ensure a clean slate
            for (const key in themeConfig) {
                if (themeConfig.hasOwnProperty(key)) {
                    const elements = document.querySelectorAll(`[data-theme-target="${key}"]`);
                    elements.forEach(element => {
                        // Remove both dark and light classes from the element
                        applyClasses(element, null, themeConfig[key]['dark']);
                        applyClasses(element, null, themeConfig[key]['light']);
                    });
                }
            }
            // Also clean body classes
            applyClasses(body, null, themeConfig.body['dark']);
            applyClasses(body, null, themeConfig.body['light']);
            applyClasses(body, null, themeConfig['form-input-text']['dark']); // For inputs
            applyClasses(body, null, themeConfig['form-input-text']['light']); // For inputs
            const formMessage = document.getElementById('form-message');
            if (formMessage) { // Check if formMessage exists before trying to remove classes
                applyClasses(formMessage, null, themeConfig['form-message-success']['dark']);
                applyClasses(formMessage, null, themeConfig['form-message-success']['light']);
            }


            // Set the data-theme attribute
            body.setAttribute('data-theme', themeName);
            localStorage.setItem('theme', themeName); // Save preference

            // Apply classes for the specified theme
            applyClasses(body, themeConfig.body[themeName]);

            document.querySelectorAll('[data-theme-target]').forEach(element => {
                const targetType = element.getAttribute('data-theme-target');
                if (themeConfig[targetType]) {
                    applyClasses(element, themeConfig[targetType][themeName]);
                }
            });

            // Special handling for input text color (as it's often combined with bg)
            document.querySelectorAll('input[data-theme-target="form-input-bg"], textarea[data-theme-target="form-input-bg"]').forEach(input => {
                applyClasses(input, themeConfig['form-input-text'][themeName]);
            });

            // Special handling for form message after submission (it's dynamic)
            if (formMessage && formMessage.textContent && !formMessage.classList.contains('hidden')) { // Only apply if message is visible
                applyClasses(formMessage, themeConfig['form-message-success'][themeName]);
            }
        }


        // Main theme toggling function
        function toggleTheme() {
            const body = document.body;
            let currentTheme = body.getAttribute('data-theme') || 'dark'; // Fallback to dark
            let newTheme = currentTheme === 'dark' ? 'light' : 'dark';
            applyTheme(newTheme); // Use the new applyTheme function
        }

        // Event listener for the theme toggle button
        document.addEventListener('DOMContentLoaded', () => {
            const themeToggleBtn = document.getElementById('theme-toggle');
            if (themeToggleBtn) {
                themeToggleBtn.addEventListener('click', toggleTheme);
            }

            // Force dark theme on initial load, overriding any saved light theme
            applyTheme('dark'); // Always start with dark theme
        });
    </script>
</body>
</html>
