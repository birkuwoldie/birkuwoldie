<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Birku Woldie - Full Stack Developer Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://cdn.jsdelivr.net/npm/react@18/umd/react.development.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/react-dom@18/umd/react-dom.development.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@babel/standalone@7/babel.min.js"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body class="bg-gray-900 text-white font-sans">
  <div id="root"></div>

  <script type="text/babel">
    function App() {
      return (
        <div className="max-w-5xl mx-auto p-6">
          {/* Header Section */}
          <header className="text-center mb-12">
            <div className="relative overflow-hidden rounded-lg shadow-xl mb-6 h-64">
              <img
                src="https://images.unsplash.com/photo-1555066931-4365d14bab8c?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80"
                alt="Code Background"
                className="w-full h-full object-cover absolute inset-0"
              />
              <div className="absolute inset-0 bg-gradient-to-t from-gray-900 to-transparent flex items-end justify-center p-6">
                <div>
                  <h1 className="text-5xl font-bold mb-2 text-blue-400">Birku Woldie</h1>
                  <p className="text-xl text-gray-300 mb-4">Full Stack Developer (React/Next.js, Django, Python, React Native)</p>
                  <div className="flex justify-center space-x-4">
                    <a href="mailto:birkuwoldie98@gmail.com" className="text-gray-300 hover:text-blue-400 transition-colors">
                      <i className="fas fa-envelope text-2xl"></i>
                    </a>
                    <a href="https://www.linkedin.com/in/birku-woldie" className="text-gray-300 hover:text-blue-400 transition-colors">
                      <i className="fab fa-linkedin text-2xl"></i>
                    </a>
                    <a href="https://github.com/birkuwoldie" className="text-gray-300 hover:text-blue-400 transition-colors">
                      <i className="fab fa-github text-2xl"></i>
                    </a>
                  </div>
                </div>
              </div>
            </div>
          </header>

          {/* Professional Summary */}
          <section className="mb-16">
            <h2 className="text-4xl font-semibold mb-4 text-blue-400 border-b border-blue-500 pb-2">Professional Summary</h2>
            <div className="bg-gray-800 p-8 rounded-lg shadow-lg">
              <p className="text-gray-300 leading-relaxed">
                I am a highly skilled Full Stack Developer with over two years of experience in developing scalable web and mobile applications. 
                Proficient in React, Next.js, TypeScript, Python (Django), and React Native, I excel at building seamless user experiences 
                and robust back-end solutions. With expertise in Tailwind CSS, Material UI, Mantine UI, and various databases (SQL/NoSQL), 
                I have successfully developed dynamic applications, including e-commerce platforms and real-time data-driven solutions. 
                I am passionate about solving complex problems with clean, scalable, and responsive code.
              </p>
            </div>
          </section>

          {/* Experience Section */}
          <section className="mb-16">
            <h2 className="text-4xl font-semibold mb-4 text-blue-400 border-b border-blue-500 pb-2">Work Experience</h2>
            <div className="space-y-6">
              {/* Perago */}
              <div className="bg-gray-800 p-6 rounded-lg shadow-lg hover:shadow-xl transition-shadow">
                <div className="flex flex-col md:flex-row md:justify-between md:items-center mb-4">
                  <h3 className="text-2xl font-semibold text-blue-300">Front-End and Mobile App Developer</h3>
                  <span className="text-gray-400">07/2023 - Present</span>
                </div>
                <h4 className="text-xl text-gray-200 mb-2">Perago Information Systems | Addis Ababa, Ethiopia</h4>
                <ul className="list-disc list-inside space-y-2 text-gray-300 pl-4">
                  <li>Developed cross-platform mobile applications using React Native and Restful APIs</li>
                  <li>Implemented front-end features using React, Next.js, and Mantine UI for seamless user experiences</li>
                  <li>Utilized Redux/Toolkit for efficient state management and integrated Firebase, Restful APIs, and Supabase for back-end services</li>
                  <li>Collaborated in a team environment with clear communication and effective project management</li>
                  <li>Microservices architecture setup using NX with next and react native with expo</li>
                </ul>
              </div>

              {/* Risidio */}
              <div className="bg-gray-800 p-6 rounded-lg shadow-lg hover:shadow-xl transition-shadow">
                <div className="flex flex-col md:flex-row md:justify-between md:items-center mb-4">
                  <h3 className="text-2xl font-semibold text-blue-300">Front-End Developer</h3>
                  <span className="text-gray-400">01/2024 - 06/2024</span>
                </div>
                <h4 className="text-xl text-gray-200 mb-2">Risidio | London, United Kingdom</h4>
                <ul className="list-disc list-inside space-y-2 text-gray-300 pl-4">
                  <li>Designed and developed web applications using React and Vite.js with TypeScript</li>
                  <li>Integrated Tailwind CSS and SCSS for responsive and aesthetic designs</li>
                  <li>Worked with Restful APIs and gained hands-on experience in Web3 concepts, NFTs, and cryptosystems</li>
                  <li>Actively contributed to a collaborative team environment</li>
                </ul>
              </div>

              {/* InfoBytes */}
              <div className="bg-gray-800 p-6 rounded-lg shadow-lg hover:shadow-xl transition-shadow">
                <div className="flex flex-col md:flex-row md:justify-between md:items-center mb-4">
                  <h3 className="text-2xl font-semibold text-blue-300">Web Development Intern</h3>
                  <span className="text-gray-400">06/2023 - 08/2023</span>
                </div>
                <h4 className="text-xl text-gray-200 mb-2">InfoBytes | New Delhi, India</h4>
                <ul className="list-disc list-inside space-y-2 text-gray-300 pl-4">
                  <li>Completed three projects utilizing JavaScript, HTML, and CSS to create functional web solutions</li>
                </ul>
              </div>
            </div>
          </section>

          {/* Education Section */}
          <section className="mb-16">
            <h2 className="text-4xl font-semibold mb-4 text-blue-400 border-b border-blue-500 pb-2">Education</h2>
            <div className="bg-gray-800 p-8 rounded-lg shadow-lg">
              <div className="mb-6">
                <h3 className="text-2xl font-semibold text-blue-300">Bachelor's Degree in Electronics and Communication Engineering</h3>
                <p className="text-gray-400">NIT Andhra Pradesh, India | 2019 - 2023</p>
                <p className="text-gray-300 mt-2">
                  Awarded prestigious SII Scholarship for academic excellence. This scholarship recognized my academic achievements 
                  and allowed me to broaden my global perspective and enhance my skills in engineering.
                </p>
              </div>
              <div>
                <h3 className="text-2xl font-semibold text-blue-300">Electromechanical Engineering</h3>
                <p className="text-gray-400">Addis Ababa Science and Technology University (AASTU), Ethiopia | 2017 - 2019</p>
                <p className="text-gray-300 mt-2">
                  Excelled academically and earned the prestigious SII Scholarship to study abroad in India.
                </p>
              </div>
            </div>
          </section>

          {/* Skills Section */}
          <section className="mb-16">
            <h2 className="text-4xl font-semibold mb-4 text-blue-400 border-b border-blue-500 pb-2">Skills</h2>
            <div className="bg-gray-800 p-8 rounded-lg shadow-lg">
              <div className="grid grid-cols-1 md:grid-cols-2 gap-6">
                {/* Front-End */}
                <div>
                  <h3 className="text-xl font-semibold text-blue-300 mb-3">Front-End Development</h3>
                  <div className="flex flex-wrap gap-2">
                    <span className="bg-gray-700 px-3 py-1 rounded-full text-sm">React</span>
                    <span className="bg-gray-700 px-3 py-1 rounded-full text-sm">Next.js</span>
                    <span className="bg-gray-700 px-3 py-1 rounded-full text-sm">TypeScript</span>
                    <span className="bg-gray-700 px-3 py-1 rounded-full text-sm">Tailwind CSS</span>
                    <span className="bg-gray-700 px-3 py-1 rounded-full text-sm">Material UI</span>
                    <span className="bg-gray-700 px-3 py-1 rounded-full text-sm">Mantine UI</span>
                    <span className="bg-gray-700 px-3 py-1 rounded-full text-sm">JavaScript</span>
                    <span className="bg-gray-700 px-3 py-1 rounded-full text-sm">HTML/CSS</span>
                  </div>
                </div>
                
                {/* Mobile */}
                <div>
                  <h3 className="text-xl font-semibold text-blue-300 mb-3">Mobile Development</h3>
                  <div className="flex flex-wrap gap-2">
                    <span className="bg-gray-700 px-3 py-1 rounded-full text-sm">React Native</span>
                    <span className="bg-gray-700 px-3 py-1 rounded-full text-sm">Flutter</span>
                  </div>
                </div>
                
                {/* Back-End */}
                <div>
                  <h3 className="text-xl font-semibold text-blue-300 mb-3">Back-End Development</h3>
                  <div className="flex flex-wrap gap-2">
                    <span className="bg-gray-700 px-3 py-1 rounded-full text-sm">Python (Django)</span>
                    <span className="bg-gray-700 px-3 py-1 rounded-full text-sm">Node.js</span>
                    <span className="bg-gray-700 px-3 py-1 rounded-full text-sm">REST API</span>
                    <span className="bg-gray-700 px-3 py-1 rounded-full text-sm">Express.js</span>
                  </div>
                </div>
                
                {/* Tools */}
                <div>
                  <h3 className="text-xl font-semibold text-blue-300 mb-3">Tools & Technologies</h3>
                  <div className="flex flex-wrap gap-2">
                    <span className="bg-gray-700 px-3 py-1 rounded-full text-sm">Git/GitHub</span>
                    <span className="bg-gray-700 px-3 py-1 rounded-full text-sm">Firebase</span>
                    <span className="bg-gray-700 px-3 py-1 rounded-full text-sm">Supabase</span>
                    <span className="bg-gray-700 px-3 py-1 rounded-full text-sm">PostgreSQL</span>
                    <span className="bg-gray-700 px-3 py-1 rounded-full text-sm">MySQL</span>
                    <span className="bg-gray-700 px-3 py-1 rounded-full text-sm">NoSQL</span>
                    <span className="bg-gray-700 px-3 py-1 rounded-full text-sm">Web3</span>
                    <span className="bg-gray-700 px-3 py-1 rounded-full text-sm">SCSS</span>
                    <span className="bg-gray-700 px-3 py-1 rounded-full text-sm">Redux/Toolkit</span>
                    <span className="bg-gray-700 px-3 py-1 rounded-full text-sm">Azure</span>
                    <span className="bg-gray-700 px-3 py-1 rounded-full text-sm">GitLab</span>
                    <span className="bg-gray-700 px-3 py-1 rounded-full text-sm">Bootstrap</span>
                    <span className="bg-gray-700 px-3 py-1 rounded-full text-sm">WordPress</span>
                  </div>
                </div>
              </div>
            </div>
          </section>

          {/* Certifications Section */}
          <section className="mb-16">
            <h2 className="text-4xl font-semibold mb-4 text-blue-400 border-b border-blue-500 pb-2">Certifications</h2>
            <div className="bg-gray-800 p-8 rounded-lg shadow-lg">
              <div className="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div className="border-l-4 border-blue-500 pl-4">
                  <h3 className="text-xl font-semibold text-gray-200">Meta Back-End Developer Professional Certificate</h3>
                </div>
                <div className="border-l-4 border-blue-500 pl-4">
                  <h3 className="text-xl font-semibold text-gray-200">React Native Certificate (Coursera)</h3>
                </div>
                <div className="border-l-4 border-blue-500 pl-4">
                  <h3 className="text-xl font-semibold text-gray-200">Advanced React Certificate (Coursera)</h3>
                </div>
              </div>
            </div>
          </section>

          {/* Languages Section */}
          <section className="mb-16">
            <h2 className="text-4xl font-semibold mb-4 text-blue-400 border-b border-blue-500 pb-2">Languages</h2>
            <div className="bg-gray-800 p-8 rounded-lg shadow-lg">
              <div className="flex flex-wrap gap-8">
                <div>
                  <h3 className="text-xl font-semibold text-gray-200 mb-2">English</h3>
                  <div className="w-full bg-gray-700 rounded-full h-2.5">
                    <div className="bg-blue-500 h-2.5 rounded-full" style={{width: '90%'}}></div>
                  </div>
                  <p className="text-gray-400 mt-1">Proficient</p>
                </div>
                <div>
                  <h3 className="text-xl font-semibold text-gray-200 mb-2">Amharic</h3>
                  <div className="w-full bg-gray-700 rounded-full h-2.5">
                    <div className="bg-blue-500 h-2.5 rounded-full" style={{width: '100%'}}></div>
                  </div>
                  <p className="text-gray-400 mt-1">Native</p>
                </div>
              </div>
            </div>
          </section>

          {/* Projects Section */}
          <section className="mb-16">
            <h2 className="text-4xl font-semibold mb-4 text-blue-400 border-b border-blue-500 pb-2">Projects</h2>
            <div className="grid grid-cols-1 md:grid-cols-2 gap-6">
              {/* Project 1 */}
              <div className="bg-gray-800 p-6 rounded-lg shadow-lg hover:shadow-xl transition-shadow">
                <div className="h-40 bg-gradient-to-r from-blue-600 to-purple-600 rounded-lg mb-4 flex items-center justify-center">
                  <i className="fas fa-code text-6xl text-white opacity-80"></i>
                </div>
                <h3 className="text-xl font-semibold text-blue-300 mb-2">Netflix Clone</h3>
                <p className="text-gray-300 mb-4">A Netflix clone built with React, featuring responsive design and dynamic content rendering.</p>
                <div className="flex flex-wrap gap-2 mb-4">
                  <span className="bg-gray-700 px-2 py-1 rounded text-xs">React</span>
                  <span className="bg-gray-700 px-2 py-1 rounded text-xs">Firebase</span>
                  <span className="bg-gray-700 px-2 py-1 rounded text-xs">Tailwind CSS</span>
                </div>
                <a href="https://github.com/birkuwoldie/netflix" className="text-blue-400 hover:text-blue-300 flex items-center">
                  <i className="fab fa-github mr-2"></i> View on GitHub
                </a>
              </div>
              
              {/* Project 2 */}
              <div className="bg-gray-800 p-6 rounded-lg shadow-lg hover:shadow-xl transition-shadow">
                <div className="h-40 bg-gradient-to-r from-purple-600 to-pink-600 rounded-lg mb-4 flex items-center justify-center">
                  <i className="fas fa-laptop-code text-6xl text-white opacity-80"></i>
                </div>
                <h3 className="text-xl font-semibold text-blue-300 mb-2">Portfolio Website</h3>
                <p className="text-gray-300 mb-4">Personal portfolio website developed with Next.js, showcasing skills and projects with a modern design.</p>
                <div className="flex flex-wrap gap-2 mb-4">
                  <span className="bg-gray-700 px-2 py-1 rounded text-xs">Next.js</span>
                  <span className="bg-gray-700 px-2 py-1 rounded text-xs">Tailwind CSS</span>
                  <span className="bg-gray-700 px-2 py-1 rounded text-xs">React</span>
                </div>
                <a href="https://github.com/birkuwoldie/portfolio" className="text-blue-400 hover:text-blue-300 flex items-center">
                  <i className="fab fa-github mr-2"></i> View on GitHub
                </a>
              </div>
            </div>
          </section>

          {/* GitHub Stats */}
          <section className="mb-16">
            <h2 className="text-4xl font-semibold mb-4 text-blue-400 border-b border-blue-500 pb-2">GitHub Activity</h2>
            <div className="grid grid-cols-1 md:grid-cols-2 gap-6">
              <div className="bg-gray-800 p-6 rounded-lg shadow-lg">
                <img 
                  src="https://github-readme-stats.vercel.app/api?username=birkuwoldie&show_icons=true&theme=radical" 
                  alt="GitHub Stats" 
                  className="w-full h-auto"
                />
              </div>
              <div className="bg-gray-800 p-6 rounded-lg shadow-lg">
                <img 
                  src="https://github-readme-stats.vercel.app/api/top-langs/?username=birkuwoldie&layout=compact&theme=radical" 
                  alt="Top Languages" 
                  className="w-full h-auto"
                />
              </div>
            </div>
          </section>

          {/* Contact Section */}
          <section className="mb-16">
            <h2 className="text-4xl font-semibold mb-4 text-blue-400 border-b border-blue-500 pb-2">Contact Me</h2>
            <div className="bg-gray-800 p-8 rounded-lg shadow-lg">
              <div className="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div>
                  <h3 className="text-xl font-semibold text-blue-300 mb-3">Get in Touch</h3>
                  <ul className="space-y-3">
                    <li className="flex items-center">
                      <i className="fas fa-phone-alt text-blue-400 mr-3"></i>
                      <span className="text-gray-300">+251 965 879 898 / +251 960 663 713</span>
                    </li>
                    <li className="flex items-center">
                      <i className="fas fa-envelope text-blue-400 mr-3"></i>
                      <a href="mailto:birkuwoldie98@gmail.com" className="text-gray-300 hover:text-blue-400">birkuwoldie98@gmail.com</a>
                    </li>
                    <li className="flex items-center">
                      <i className="fas fa-map-marker-alt text-blue-400 mr-3"></i>
                      <span className="text-gray-300">Addis Ababa, Ethiopia</span>
                    </li>
                  </ul>
                </div>
                <div>
                  <h3 className="text-xl font-semibold text-blue-300 mb-3">Connect With Me</h3>
                  <div className="flex space-x-4">
                    <a href="https://www.linkedin.com/in/birku-woldie" className="text-gray-300 hover:text-blue-400 text-3xl">
                      <i className="fab fa-linkedin"></i>
                    </a>
                    <a href="https://github.com/birkuwoldie" className="text-gray-300 hover:text-blue-400 text-3xl">
                      <i className="fab fa-github"></i>
                    </a>
                    <a href="https://twitter.com/" className="text-gray-300 hover:text-blue-400 text-3xl">
                      <i className="fab fa-twitter"></i>
                    </a>
                  </div>
                </div>
              </div>
            </div>
          </section>

          {/* Footer */}
          <footer className="text-center py-8 border-t border-gray-700">
            <p className="text-gray-400">© {new Date().getFullYear()} Birku Woldie. All rights reserved.</p>
            <div className="mt-4">
              <img 
                src="https://komarev.com/ghpvc/?username=birkuwoldie&color=brightgreen" 
                alt="Profile Views" 
                className="inline-block"
              />
            </div>
          </footer>
        </div>
      );
    }

    ReactDOM.render(<App />, document.getElementById('root'));
  </script>
</body>
</html>
