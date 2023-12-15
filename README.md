### Hi there 👋

<!--
**LCorderF/LCorderF** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
![Luis Cordero github estatus](https://github-readme-stats.vercel.app/api?username=LCorderF&show_icons=true&theme=nightowl)<br/>
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=LCorderF&theme=nightowl&hide=html,css&langs_count=7)](https://github.com/anuraghazra/github-readme-stats)
<br/>
[ENG] Software developer, and a kind and a gentlemanly full-time nerd.<br/>
[ESP] Desarrollador de software, y un amable y caballeroso nerd a tiempo completo.<br/>
[GER] Software-Entwickler und ein freundlicher und liebenswürdiger Vollzeit-Nerd.<br/>
<br/>
## Follow Me
🔗 Website: https://Grupo-LCF.org/<br/>
📺 Youtube: https://www.youtube.com/<br/>
🐦 Twitter: https://twitter.com/<br/>
👨‍💼 LinkedIn: https://linkedin.com/in/LuisCorderoFalcon<br/>
✉️ Email: luiscorderof.developer@gmail.com<br/>
💬 Ask me about: Software Development, Delphi, Flutter, etc.<br/>
🌱 I’m currently learning: Go, Rust, LowCode/Nocode.<br/>

sequenceDiagram
    participant browser
    participant server

    browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/notes
    activate server
    server-->>browser: HTML document
    deactivate server

    browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/main.css
    activate server
    server-->>browser: the css file
    deactivate server

    browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/main.js
    activate server
    server-->>browser: the JavaScript file
    deactivate server

    Note right of browser: The browser starts executing the JavaScript code that fetches the JSON from the server

    browser->>server: GET https://studies.cs.helsinki.fi/exampleapp/data.json
    activate server
    server-->>browser: [{ "content": "HTML is easy", "date": "2023-1-1" }, ... ]
    deactivate server

    Note right of browser: The browser executes the callback function that renders the notes
