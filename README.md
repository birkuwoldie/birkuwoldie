<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Birku Woldie - Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://cdn.jsdelivr.net/npm/react@18/umd/react.development.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/react-dom@18/umd/react-dom.development.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/@babel/standalone@7/babel.min.js"></script>
</head>
<body class="bg-gray-900 text-white font-sans">
  <div id="root"></div>

  <script type="text/babel">
    function App() {
      return (
        <div className="max-w-5xl mx-auto p-6">
          {/* Header Section */}
          <div className="text-center mb-12">
            <img
              src="https://birku98.vercel.app/assets/git-banner.jpg"
              alt="Welcome Banner"
              className="w-full h-auto rounded-lg shadow-xl mb-6 transform transition-transform hover:scale-105"
            />
            <h1 className="text-5xl font-bold mb-2 text-blue-300">Hi, I’m Birku Woldie</h1>
            <p className="text-xl text-gray-300 mb-4">Full Stack Developer (React/Next.js, Django, Python, React Native)</p>
          </div>

          {/* About Me Section */}
          <section className="mb-16">
            <h2 className="text-4xl font-semibold mb-4 text-blue-200">🌟 About Me</h2>
            <div className="bg-gray-800 p-8 rounded-lg shadow-lg transform transition-transform hover:scale-[1.02]">
              <p className="mb-4 text-gray-300">
                I'm a passionate software developer from Addis Ababa, Ethiopia, dedicated to crafting efficient, scalable, and user-friendly applications. With a strong foundation in full-stack and mobile development, I thrive on solving complex problems and contributing to innovative projects.
              </p>
              <ul className="list-disc list-inside space-y-2 text-gray-300">
                <li><strong>Interests:</strong> Full-Stack Development, Mobile App Development, Open Source Contributions, Cloud Computing, AI and Machine Learning</li>
                <li><strong>Currently Learning:</strong> Advanced React and Next.js, Tailwind CSS, Material-UI, Python for Data Science, DevOps with Docker and Kubernetes</li>
                <li><strong>Looking to Collaborate On:</strong> Open Source Projects, Innovative Startups, Community-driven Tech Initiatives</li>
                <li><strong>Location:</strong> Addis Ababa, Ethiopia</li>
              </ul>
            </div>
          </section>

          {/* Contact Section */}
          <section className="mb-16">
            <h2 className="text-4xl font-semibold mb-4 text-blue-200">📫 How to Reach Me</h2>
            <div className="flex flex-wrap justify-center gap-4">
              <a href="mailto:birkuwoldie9@gmail.com" className="inline-block transform transition-transform hover:scale-110">
                <img src="https://img.shields.io/badge/-Email-%2312100E?style=flat&logo=gmail" alt="Email" />
              </a>
              <a href="https://www.linkedin.com/in/birkuwoldie" className="inline-block transform transition-transform hover:scale-110">
                <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" />
              </a>
              <a href="https://github.com/birkuwoldie" className="inline-block transform transition-transform hover:scale-110">
                <img src="https://img.shields.io/badge/-GitHub-%23181717?style=flat&logo=github&logoColor=white" alt="GitHub" />
              </a>
            </div>
          </section>

          {/* Education Section */}
          <section className="mb-16">
            <h2 className="text-4xl font-semibold mb-4 text-blue-200">🎓 Education</h2>
            <div className="bg-gray-800 p-8 rounded-lg shadow-lg">
              <div className="mb-6">
                <h3 className="text-2xl font-semibold text-gray-200">Bachelor's in Electronics and Communication Engineering</h3>
                <p className="text-gray-400">NIT Andhra Pradesh, India | 2018 - 2022</p>
                <p className="text-gray-300">Awarded a prestigious SI program scholarship for academic excellence, enabling global exposure and advanced engineering studies.</p>
              </div>
              <div>
                <h3 className="text-2xl font-semibold text-gray-200">Electromechanical Engineering</h3>
                <p className="text-gray-400">Adama Science and Technology University (AASTU), Ethiopia | 2016 - 2018</p>
                <p className="text-gray-300">Excelled academically, laying a strong foundation in engineering principles before pursuing further studies abroad.</p>
              </div>
            </div>
          </section>

          {/* Work Experience Section */}
          <section className="mb-16">
            <h2 className="text-4xl font-semibold mb-4 text-blue-200">💼 Work Experience</h2>
            <div className="bg-gray-800 p-8 rounded-lg shadow-lg">
              <div className="mb-6">
                <h3 className="text-2xl font-semibold text-gray-200">Senior Software Developer</h3>
                <p className="text-gray-400"> Droja Consulting, Onsite|  Aprile, 2025 - present</p>
                <ul className="list-disc list-inside space-y-2 text-gray-300">
                  <li>Developed scalable web and mobile applications using React, Next.js, and React Native for various clients.</li>
                  <li>Designed RESTful APIs and integrated databases like PostgreSQL and Supabase for seamless data management.</li>
                  <li>Collaborated on open-source projects, enhancing skills in Web3 and state management with Redux/Toolkit.</li>
                </ul>
              </div>
              <div className="mb-6">
                <h3 className="text-2xl font-semibold text-gray-200">Mobile App and Fronend Developer</h3>
                <p className="text-gray-400"> Perago Systems, Onsite| july, 2023 - Aprile, 2025</p>
                <ul className="list-disc list-inside space-y-2 text-gray-300">
                  <li>Developed scalable web and mobile applications using React, Next.js, and React Native for various clients.</li>
                  <li>Designed RESTful APIs and integrated databases like PostgreSQL and Supabase for seamless data management.</li>
                  <li>Collaborated on open-source projects, enhancing skills in Web3 and state management with Redux/Toolkit.</li>
                </ul>
              </div>
              <div>
                <h3 className="text-2xl font-semibold text-gray-200">Frontend Developer</h3>
                <p className="text-gray-400">Residio, London, UK, Remote |june, 2024 - october 2024</p>
                <ul className="list-disc list-inside space-y-2 text-gray-300">
                  <li>Built responsive front-end interfaces using Vite.js and Tailwind CSS for e-commerce platforms.</li>
                  <li>Contributed to back-end development with Node.js and Express.js, optimizing server performance.</li>
                  <li>Implemented CI/CD pipelines using GitLab and Azure for efficient deployment workflows.</li>
                </ul>
              </div>
            </div>
          </section>

          {/* Projects Section */}
          <section className="mb-16">
            <h2 className="text-4xl font-semibold mb-4 text-blue-200">🛠️ Projects</h2>
            <div className="space-y-6">
              <div className="bg-gray-800 p-6 rounded-lg shadow-lg transform transition-transform hover:scale-[1.02]">
                <a href="https://github.com/birkuwoldie/netflix" className="inline-block mb-2">
                  <img src="https://img.shields.io/badge/Project%201-Netflix%20Clone-black?style=for-the-badge&logo=github" alt="Netflix Clone" />
                </a>
                <p className="text-gray-300">Netflix Clone built with HTML, JavaScript, and CSS, featuring a responsive UI and dynamic content rendering.</p>
              </div>
              <div className="bg-gray-800 p-6 rounded-lg shadow-lg transform transition-transform hover:scale-[1.02]">
                <a href="https://github.com/birkuwoldie/portfolio" className="inline-block mb-2">
                  <img src="https://img.shields.io/badge/Project%202-Portfolio-black?style=for-the-badge&logo=github" alt="Portfolio" />
                </a>
                <p className="text-gray-300">Personal portfolio website developed with Next.js, showcasing my skills and projects with a modern, responsive design.</p>
              </div>
              <div className="bg-gray-800 p-6 rounded-lg shadow-lg transform transition-transform hover:scale-[1.02]">
                <a href="https://github.com/birkuwoldie/" className="inline-block mb-2">
                  <img src="https://img.shields.io/badge/Project%203-Another%20Project-black?style=for-the-badge&logo=github" alt="Another Project" />
                </a>
                <p className="text-gray-300">Explore my other project repositories for innovative solutions in web and mobile development.</p>
              </div>
            </div>
          </section>

          {/* Achievements Section */}
          <section className="mb-16">
            <h2 className="text-4xl font-semibold mb-4 text-blue-200">🏆 Achievements</h2>
            <div className="bg-gray-800 p-8 rounded-lg shadow-lg">
              <ul className="list-disc list-inside space-y-2 text-gray-300">
                <li>Awarded a prestigious SI program scholarship to pursue a Bachelor's degree in Electronics and Communication Engineering at NIT Andhra Pradesh, India.</li>
                <li>Excelled in Electromechanical Engineering at Adama Science and Technology University (AASTU), earning the opportunity to study abroad.</li>
              </ul>
            </div>
          </section>

          {/* Certifications Section */}
          <section className="mb-16">
            <h2 className="text-4xl font-semibold mb-4 text-blue-200">📜 Certifications</h2>
            <div className="bg-gray-800 p-8 rounded-lg shadow-lg">
              <ul className="list-disc list-inside space-y-2 text-gray-300">
                <li>Meta Back-End Developer Professional Certificate</li>
                <li>React Native Certificate (Coursera)</li>
                <li>Advanced React Certificate (Coursera)</li>
              </ul>
            </div>
          </section>

          {/* Skills Section */}
          <section className="mb-16">
            <h2 className="text-4xl font-semibold mb-4 text-blue-200">🛠️ Skills</h2>
            <div className="bg-gray-800 p-8 rounded-lg shadow-lg">
              <ul className="list-disc list-inside space-y-2 text-gray-300">
                <li><strong>Front-End Development:</strong> React, Next.js, Vue.js, TypeScript, Tailwind CSS, Material UI, Mantine UI, JavaScript/HTML, CSS</li>
                <li><strong>Mobile Development:</strong> React Native, Flutter</li>
                <li><strong>Back-End Development:</strong> Python (Django), Node.js, REST API, Express.js</li>
                <li><strong>Tools:</strong> Git/GitHub, Firebase, Supabase, PostgreSQL, MySQL, NoSQL</li>
                <li><strong>Additional:</strong> Web3, SCSS, Responsive Design, State Management (Redux/Toolkit), Azure, GitLab, Bootstrap, WordPress</li>
              </ul>
            </div>
          </section>

          {/* Languages Section */}
          <section className="mb-16">
            <h2 className="text-4xl font-semibold mb-4 text-blue-200">🗣️ Languages</h2>
            <div className="bg-gray-800 p-8 rounded-lg shadow-lg">
              <ul className="list-disc list-inside space-y-2 text-gray-300">
                <li><strong>English:</strong> Proficient</li>
                <li><strong>Amharic:</strong> Native</li>
              </ul>
            </div>
          </section>

          {/* Testimonials Section */}
          <section className="mb-16">
            <h2 className="text-4xl font-semibold mb-4 text-blue-200">🌟 Testimonials</h2>
            <div className="bg-gray-800 p-8 rounded-lg shadow-lg">
              <div className="mb-6">
                <p className="text-gray-300 italic">"Birku's expertise in full-stack development transformed our project, delivering a seamless and responsive application ahead of schedule."</p>
                <p className="text-gray-400 mt-2">- Client, Freelance Project</p>
              </div>
              <div>
                <p className="text-gray-300 italic">"Working with Birku was a pleasure; his collaborative spirit and technical proficiency significantly improved our platform's performance."</p>
                <p className="text-gray-400 mt-2">- Team Lead, Tech Startup</p>
              </div>
            </div>
          </section>

          {/* GitHub Stats Section */}
          <section className="mb-16">
            <h2 className="text-4xl font-semibold mb-4 text-blue-200">📊 GitHub Stats</h2>
            <div className="flex flex-wrap justify-center gap-4">
              <img src="https://github-readme-stats.vercel.app/api?username=birkuwoldie&show_icons=true&theme=radical" alt="Birku's GitHub stats" className="w-full md:w-[49%]" />
              <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=birkuwoldie&layout=compact&theme=radical" alt="Top Languages" className="w-full md:w-[49%]" />
            </div>
          </section>

          {/* Footer */}
          <footer className="text-center text-gray-400 py-6">
            <p>© 2025 Birku Woldie. All rights reserved.</p>
            <img src="https://komarev.com/ghpvc/?username=birkuwoldie&color=brightgreen" alt="Profile Views" className="mt-4" />
          </footer>
        </div>
      );
    }

    ReactDOM.render(<App />, document.getElementById('root'));
  </script>
</body>
</html>
