# Artur Gonçalves
![Artur's Avatar](https://mir-s3-cdn-cf.behance.net/project_modules/max_1200/9bc27292880429.5e569ff84e4d0.gif)


## Welcome:

<html>
  <head>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.23.0/themes/prism.min.css" />
    <script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.23.0/components/prism-core.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.23.0/plugins/autoloader/prism-autoloader.min.js"></script>
  </head>
  <body>
    <div id="welcome-code"></div>

    <script>
      const codes = [
        { language: 'C', code: '#include <stdio.h>\nint main() {\n  printf("Welcome to my GitHub profile!\\n");\n  return 0;\n}' },
        { language: 'C++', code: '#include <iostream>\nint main() {\n  std::cout << "Welcome to my GitHub profile!" << std::endl;\n  return 0;\n}' },
        { language: 'Python', code: 'print("Welcome to my GitHub profile!")' },
        { language: 'C#', code: 'using System;\nclass Program {\n  static void Main() {\n    Console.WriteLine("Welcome to my GitHub profile!");\n  }\n}' },
        { language: 'JavaScript', code: 'console.log("Welcome to my GitHub profile!");' }
      ];

      function displayRandomCode() {
        const randomCode = codes[Math.floor(Math.random() * codes.length)];
        document.getElementById('welcome-code').innerHTML = `
          <pre><code class="language-${randomCode.language.toLowerCase()}">${randomCode.code}</code></pre>
        `;
        // Re-initialize Prism.js after code is inserted into the DOM
        Prism.highlightAll();
      }

      // Call the function to display code when the page loads
      window.onload = displayRandomCode;
    </script>
  </body>
</html>




## About Me
I'm a passionate software developer with a focus on industrial programming and Industry 4.0 solutions. Currently learning at 42 Porto and building innovative solutions for manufacturing systems and automation.

## Skills:
- **Languages**:
  - Low-level: ASM x86
  - High-level: C, C++, Python, JavaScript, C#, VB
  - Automation: Ladder, STL, FBD

- **Technologies**:
  - Web Development: Node.js, React, Django
  - Database Management: SQL, MySQL
  - Dev Tools: Docker, Visual Studio Code, GitHub

- **Industrial Automation**:
  - Machine Programming: Siemens, Omron, Beckhoff
  - Industry 4.0 Solutions: Data analysis, IoT, smart manufacturing

## Goals:
- Working Full-Time as a Software Developer, creating efficient, reliable, and scalable systems
- Contributing to Industry 4.0 by developing smart manufacturing solutions that integrate automation, data, and machine learning


## Contact
- [LinkedIn](https://www.linkedin.com/in/arturg04/)
- [Email](mailto:your.email@example.com)

## Follow Me
- [GitHub](https://github.com/Arturg04)
- [Twitter](https://twitter.com/arturg04)
- [Instagram](https://www.instagram.com/arturg04/)
