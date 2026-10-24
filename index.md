<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>School of Computer Science & Engineering - College Information</title>
    <!-- Tailwind CSS CDN for modern responsive layout and visual styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            50: '#f0f7ff',
                            100: '#e0effe',
                            600: '#2563eb',
                            700: '#1d4ed8',
                            900: '#1e3a8a',
                        }
                    }
                }
            }
        }
    </script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased min-h-screen flex flex-col">

    <!-- Header & Hero Section (Requirement 1 & 6) -->
    <header class="bg-gradient-to-r from-brand-900 via-brand-700 to-brand-600 text-white shadow-lg">
        <div class="max-w-6xl mx-auto px-4 py-12 md:py-16 text-center md:text-left">
            <span class="inline-block bg-brand-500/30 text-brand-100 text-xs font-semibold uppercase tracking-widest px-3 py-1 rounded-full mb-3 border border-brand-300/20">
                Assignment 3.3 - HTML Lists & Semantics
            </span>
            <h1 class="text-3xl md:text-5xl font-extrabold tracking-tight mb-4">
                School of Computer Science & Engineering
            </h1>
            <p class="text-lg md:text-xl text-brand-100 max-w-3xl font-light leading-relaxed">
                Empowering future technologists through world-class education, cutting-edge research, and hands-on industry practical learning.
            </p>
        </div>
    </header>

    <!-- Main Content Container (Requirement 6: Structured Layout) -->
    <main class="max-w-6xl mx-auto px-4 py-10 flex-grow w-full space-y-12">

        <!-- Section 1: Introduction (Requirement 1) -->
        <section id="introduction" class="bg-white rounded-2xl p-6 md:p-8 shadow-sm border border-slate-200/80">
            <div class="flex items-center space-x-3 mb-4">
                <div class="p-2 bg-brand-50 rounded-lg text-brand-600">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 16h-1v-4h-1m1-4h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                </div>
                <h2 class="text-2xl font-bold text-slate-900">About the College & Program</h2>
            </div>
            <p class="text-slate-600 leading-relaxed mb-4">
                The <strong>School of Computer Science & Engineering (SCSE)</strong> is dedicated to fostering innovation, critical thinking, and technical mastery. Founded in 2005, the department offers comprehensive undergraduate and postgraduate programs designed to prepare students for the rapidly evolving tech landscape.
            </p>
            <p class="text-slate-600 leading-relaxed">
                With state-of-the-art laboratory facilities, experienced faculty members, and strong industry partnerships, SCSE provides a vibrant academic environment where students can turn ideas into impactful real-world solutions.
            </p>
        </section>

        <!-- Grid layout for Departments & Admission Process -->
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-8">

            <!-- Section 2: Departments & Subjects (Requirement 2: Unordered List <ul>) -->
            <section id="departments" class="bg-white rounded-2xl p-6 md:p-8 shadow-sm border border-slate-200/80 flex flex-col justify-between">
                <div>
                    <div class="flex items-center space-x-3 mb-4">
                        <div class="p-2 bg-brand-50 rounded-lg text-brand-600">
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 11H5m14 0a2 2 0 012 2v6a2 2 0 01-2 2H5a2 2 0 01-2-2v-6a2 2 0 012-2m14 0V9a2 2 0 00-2-2M5 11V9a2 2 0 012-2m0 0V5a2 2 0 012-2h6a2 2 0 012 2v2M7 7h10"></path></svg>
                        </div>
                        <h2 class="text-2xl font-bold text-slate-900">Departments & Focus Areas</h2>
                    </div>
                    <p class="text-slate-600 mb-6 text-sm">
                        Our academic framework spans key computing disciplines to build a strong theoretical and practical foundation:
                    </p>

                    <!-- Requirement 2: Unordered List -->
                    <ul class="space-y-3 list-none pl-0">
                        <li class="flex items-center space-x-3 p-3 rounded-xl bg-slate-50 border border-slate-100 hover:border-brand-200 transition-colors">
                            <span class="h-2.5 w-2.5 rounded-full bg-brand-600"></span>
                            <span class="font-medium text-slate-700">Software Engineering & Architecture</span>
                        </li>
                        <li class="flex items-center space-x-3 p-3 rounded-xl bg-slate-50 border border-slate-100 hover:border-brand-200 transition-colors">
                            <span class="h-2.5 w-2.5 rounded-full bg-brand-600"></span>
                            <span class="font-medium text-slate-700">Artificial Intelligence & Machine Learning</span>
                        </li>
                        <li class="flex items-center space-x-3 p-3 rounded-xl bg-slate-50 border border-slate-100 hover:border-brand-200 transition-colors">
                            <span class="h-2.5 w-2.5 rounded-full bg-brand-600"></span>
                            <span class="font-medium text-slate-700">Data Science & Big Analytics</span>
                        </li>
                        <li class="flex items-center space-x-3 p-3 rounded-xl bg-slate-50 border border-slate-100 hover:border-brand-200 transition-colors">
                            <span class="h-2.5 w-2.5 rounded-full bg-brand-600"></span>
                            <span class="font-medium text-slate-700">Cybersecurity & Network Systems</span>
                        </li>
                        <li class="flex items-center space-x-3 p-3 rounded-xl bg-slate-50 border border-slate-100 hover:border-brand-200 transition-colors">
                            <span class="h-2.5 w-2.5 rounded-full bg-brand-600"></span>
                            <span class="font-medium text-slate-700">Cloud Computing & DevOps</span>
                        </li>
                    </ul>
                </div>
            </section>

            <!-- Section 3: Admission Process (Requirement 3: Ordered List <ol>) -->
            <section id="admission" class="bg-white rounded-2xl p-6 md:p-8 shadow-sm border border-slate-200/80">
                <div class="flex items-center space-x-3 mb-4">
                    <div class="p-2 bg-brand-50 rounded-lg text-brand-600">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2"></path></svg>
                    </div>
                    <h2 class="text-2xl font-bold text-slate-900">Admission Process</h2>
                </div>
                <p class="text-slate-600 mb-6 text-sm">
                    Follow these step-by-step guidelines to complete your registration for the academic session:
                </p>

                <!-- Requirement 3: Ordered List -->
                <ol class="space-y-4 list-decimal list-inside text-slate-700 font-medium">
                    <li class="p-3 bg-slate-50 rounded-xl border border-slate-100">
                        <span class="font-semibold text-slate-900">Submit Online Application:</span> Complete the registration form on the official admissions portal.
                    </li>
                    <li class="p-3 bg-slate-50 rounded-xl border border-slate-100">
                        <span class="font-semibold text-slate-900">Entrance Examination:</span> Appear for the College Scholastic Entrance Test (CSET).
                    </li>
                    <li class="p-3 bg-slate-50 rounded-xl border border-slate-100">
                        <span class="font-semibold text-slate-900">Document Verification:</span> Upload high school transcripts, identity proof, and recommendation letters.
                    </li>
                    <li class="p-3 bg-slate-50 rounded-xl border border-slate-100">
                        <span class="font-semibold text-slate-900">Personal Interview:</span> Participate in a technical and motivational interview with faculty panel.
                    </li>
                    <li class="p-3 bg-slate-50 rounded-xl border border-slate-100">
                        <span class="font-semibold text-slate-900">Enrollment & Fee Payment:</span> Confirm your seat by paying the initial semester tuition fee.
                    </li>
                </ol>
            </section>
        </div>

        <!-- Section 4: Syllabus & Topics Breakdown (Requirement 4: Nested List) -->
        <section id="curriculum" class="bg-white rounded-2xl p-6 md:p-8 shadow-sm border border-slate-200/80">
            <div class="flex items-center space-x-3 mb-6">
                <div class="p-2 bg-brand-50 rounded-lg text-brand-600">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C20.832 18.477 19.246 18 16.5 18c-1.746 0-3.332.477-4.5 1.253"></path></svg>
                </div>
                <h2 class="text-2xl font-bold text-slate-900">Featured Subject Syllabus (Nested Breakdown)</h2>
            </div>

            <!-- Requirement 4: Nested Lists -->
            <div class="bg-slate-50 p-6 rounded-xl border border-slate-200">
                <h3 class="text-xl font-bold text-brand-900 mb-4">Subject: Full-Stack Web Development</h3>
                <ul class="list-disc pl-6 space-y-4 text-slate-700">
                    <li>
                        <strong class="text-slate-900">Module 1: Frontend Development Essentials</strong>
                        <ol class="list-decimal pl-6 mt-2 space-y-2 text-sm text-slate-600">
                            <li>HTML5 Semantic Structures & Web Accessibility (WCAG)</li>
                            <li>Advanced CSS3 Layouts: Flexbox, Grid & Responsive Design</li>
                            <li>JavaScript Foundations (ES6+, DOM Manipulation, Async/Await)</li>
                        </ol>
                    </li>
                    <li>
                        <strong class="text-slate-900">Module 2: Modern Frontend Frameworks</strong>
                        <ul class="list-circle pl-6 mt-2 space-y-2 text-sm text-slate-600">
                            <li>Component-Driven Development with React</li>
                            <li>State Management & React Hooks</li>
                            <li>Styling Frameworks (Tailwind CSS & Utility-First design)</li>
                        </ul>
                    </li>
                    <li>
                        <strong class="text-slate-900">Module 3: Backend & Database Systems</strong>
                        <ol class="list-decimal pl-6 mt-2 space-y-2 text-sm text-slate-600">
                            <li>Server-side Execution with Node.js & Express</li>
                            <li>RESTful API Architecture and Authentication (JWT)</li>
                            <li>Databases: Relational (PostgreSQL) vs Non-Relational (MongoDB)</li>
                        </ol>
                    </li>
                </ul>
            </div>
        </section>

        <!-- Section 5: Faculty & Course Details (Requirement 5: Description List <dl>, <dt>, <dd>) -->
        <section id="faculty" class="bg-white rounded-2xl p-6 md:p-8 shadow-sm border border-slate-200/80">
            <div class="flex items-center space-x-3 mb-6">
                <div class="p-2 bg-brand-50 rounded-lg text-brand-600">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"></path></svg>
                </div>
                <h2 class="text-2xl font-bold text-slate-900">Faculty & Course Directory</h2>
            </div>

            <!-- Requirement 5: Description List -->
            <dl class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div class="bg-slate-50 p-5 rounded-xl border border-slate-100">
                    <dt class="text-lg font-semibold text-brand-900 mb-1">Dr. Eleanor Vance</dt>
                    <dd class="text-xs uppercase tracking-wide font-bold text-brand-600 mb-2">Head of Department & Professor</dd>
                    <dd class="text-slate-600 text-sm leading-relaxed">
                        Specializes in Artificial Intelligence and Neural Networks with 18+ years of academic and industrial research experience.
                    </dd>
                </div>

                <div class="bg-slate-50 p-5 rounded-xl border border-slate-100">
                    <dt class="text-lg font-semibold text-brand-900 mb-1">Prof. Marcus Holloway</dt>
                    <dd class="text-xs uppercase tracking-wide font-bold text-brand-600 mb-2">Lead Instructor - Web Technologies</dd>
                    <dd class="text-slate-600 text-sm leading-relaxed">
                        Former Senior Systems Architect with expertise in Full-Stack Web Development, Cloud Infrastructure, and Distributed Systems.
                    </dd>
                </div>

                <div class="bg-slate-50 p-5 rounded-xl border border-slate-100">
                    <dt class="text-lg font-semibold text-brand-900 mb-1">B.Sc. Computer Science</dt>
                    <dd class="text-xs uppercase tracking-wide font-bold text-brand-600 mb-2">Undergraduate Degree (4 Years)</dd>
                    <dd class="text-slate-600 text-sm leading-relaxed">
                        An intensive 8-semester program covering core computer science principles, algorithms, modern engineering practices, and practical capstone projects.
                    </dd>
                </div>

                <div class="bg-slate-50 p-5 rounded-xl border border-slate-100">
                    <dt class="text-lg font-semibold text-brand-900 mb-1">M.Sc. Data Analytics</dt>
                    <dd class="text-xs uppercase tracking-wide font-bold text-brand-600 mb-2">Postgraduate Degree (2 Years)</dd>
                    <dd class="text-slate-600 text-sm leading-relaxed">
                        Advanced postgraduate curriculum focused on statistical modeling, machine learning pipelines, big data systems, and enterprise business intelligence.
                    </dd>
                </div>
            </dl>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-slate-900 text-slate-400 py-8 border-t border-slate-800 mt-12">
        <div class="max-w-6xl mx-auto px-4 text-center text-sm">
            <p>&copy; Assignment 3.3 Submission - College Information Page.</p>
        </div>
    </footer>

</body>
</html>