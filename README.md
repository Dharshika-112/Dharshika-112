<style>
@import url('https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;600&family=Space+Grotesk:wght@300;400;600;700&display=swap');
*{margin:0;padding:0;box-sizing:border-box}
.hero{width:100%;background:#ffffff;border-radius:16px;position:relative;overflow:hidden;display:flex;flex-direction:column;align-items:center;justify-content:center;padding:2.8rem 2rem;text-align:center;border:1px solid #ede9fe;min-height:320px}
.bg-dots{position:absolute;inset:0;pointer-events:none;background-image:radial-gradient(circle,#c4b5fd 1px,transparent 1px);background-size:30px 30px;opacity:0.12}
.greeting{font-family:'Space Grotesk',sans-serif;font-size:34px;font-weight:300;color:#1e1b4b;display:flex;align-items:center;justify-content:center;gap:0.4rem;flex-wrap:wrap;animation:fadeUp 0.6s ease forwards;opacity:0}
.name-grad{font-family:'Space Grotesk',sans-serif;font-size:36px;font-weight:700;background:linear-gradient(90deg,#7c3aed,#0ea5e9,#7c3aed);background-size:200%;-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;animation:fadeUp 0.6s ease forwards,shimmer 3s 0.8s linear infinite;opacity:0}
@keyframes shimmer{to{background-position:200% center}}
.wave{display:inline-block;font-size:32px;animation:fadeUp 0.6s 0.1s ease forwards,wave 1.5s 1s ease-in-out 3;opacity:0;transform-origin:70% 70%}
@keyframes wave{0%,100%{transform:rotate(0deg)}20%{transform:rotate(20deg)}60%{transform:rotate(-10deg)}}
.role-row{display:flex;align-items:center;justify-content:center;gap:10px;margin:1.1rem 0 0.6rem;flex-wrap:wrap;animation:fadeUp 0.6s 0.2s ease forwards;opacity:0}
.badge{font-family:'Fira Code',monospace;font-size:12px;padding:6px 16px;border-radius:24px;border:1.5px solid #7c3aed;color:#5b21b6;background:#faf5ff;letter-spacing:0.3px}
.typing-row{font-family:'Fira Code',monospace;font-size:13px;color:#7c3aed;margin:0.3rem 0 0.8rem;animation:fadeUp 0.6s 0.35s ease forwards;opacity:0;min-height:20px}
.cursor{display:inline-block;width:2px;height:13px;background:#7c3aed;vertical-align:middle;margin-left:2px;animation:blink 1s step-end infinite}
@keyframes blink{50%{opacity:0}}
.divider{width:60px;height:2.5px;background:linear-gradient(90deg,#7c3aed,#0ea5e9);border-radius:2px;margin:0.2rem auto 1rem;animation:fadeUp 0.6s 0.5s ease forwards,grow 0.8s 0.5s ease forwards;opacity:0}
@keyframes grow{from{width:0}to{width:60px}}
.quote{font-family:'Space Grotesk',sans-serif;font-size:14px;color:#4c1d95;font-style:italic;line-height:1.7;max-width:500px;animation:fadeUp 0.6s 0.65s ease forwards;opacity:0}
.quote span{font-style:normal;font-weight:600;color:#7c3aed}
.tags{display:flex;flex-wrap:wrap;gap:8px;justify-content:center;margin-top:1.1rem;animation:fadeUp 0.6s 0.8s ease forwards;opacity:0}
.tag{font-family:'Fira Code',monospace;font-size:11px;color:#6d28d9;padding:3px 12px;border:1px solid #ddd6fe;border-radius:6px;background:#faf5ff}
@keyframes fadeUp{from{opacity:0;transform:translateY(10px)}to{opacity:1;transform:translateY(0)}}
</style>

<h2 class="sr-only">Dharshika D S — AI Developer profile banner</h2>

<div class="hero">
  <div class="bg-dots"></div>

  <div class="greeting">
    <span>I'm</span>
    <span class="name-grad">Dharshika D S</span>
    <span class="wave">👋</span>
  </div>

  <div class="role-row">
    <span class="badge">🤖 AI Developer</span>
    <span class="badge">📊 Data Scientist</span>
    <span class="badge">🌐 Full-Stack</span>
  </div>

  <div class="typing-row">&gt; <span id="typed"></span><span class="cursor"></span></div>

  <div class="divider"></div>

  <p class="quote">
    <span>"</span> Data is the new oil, but intelligence is the refinery —<br>
    I build the machines that turn raw data into decisions. <span>"</span>
  </p>

  <div class="tags">
    <span class="tag">#AgenticAI</span>
    <span class="tag">#MachineLearning</span>
    <span class="tag">#ComputerVision</span>
    <span class="tag">#RAG</span>
    <span class="tag">#OpenSource</span>
  </div>
</div>

<script>
const phrases=["Pre-Final Year @ KIT","Building Agentic AI systems...","LeetCode Top 28% Globally","Turning data into decisions..."];
let pi=0,ci=0,del=false;
const el=document.getElementById('typed');
function type(){
  const p=phrases[pi];
  if(!del){el.textContent=p.slice(0,++ci);if(ci===p.length){del=true;setTimeout(type,1800);return;}setTimeout(type,55);}
  else{el.textContent=p.slice(0,--ci);if(ci===0){del=false;pi=(pi+1)%phrases.length;setTimeout(type,400);return;}setTimeout(type,28);}
}
setTimeout(type,900);
</script>
<div align="center">

<!-- Animated Header Banner -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Dharshika%20D%20S&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20%26%20Data%20Science%20Engineer%20%7C%20Full-Stack%20Developer%20%7C%20Problem%20Solver&descAlignY=58&descSize=16&descColor=a78bfa"/>

</div>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-dharshika-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/dharshika)
[![GitHub](https://img.shields.io/badge/GitHub-dharshika-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/dharshika)
[![Gmail](https://img.shields.io/badge/Gmail-dsdharshika5@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dsdharshika5@gmail.com)
[![LeetCode](https://img.shields.io/badge/LeetCode-Top%2028%25%20Globally-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com)

</div>

---

## 👩‍💻 About Me

```python
class Dharshika:
    def __init__(self):
        self.name        = "Dharshika D S"
        self.degree      = "B.Tech – Artificial Intelligence & Data Science"
        self.university  = "KIT – Kalaignar Karunanidhi Institute of Technology, Coimbatore"
        self.year        = "Pre-Final Year (2024–2027)"
        self.cgpa        = 8.35

    @property
    def focus_areas(self):
        return ["Agentic AI", "Machine Learning", "Full-Stack Development", "Computer Vision"]

    @property
    def currently(self):
        return {
            "building"  : "AI-powered platforms that solve real-world problems",
            "learning"  : "RAG pipelines, LLM fine-tuning & cloud-native architectures",
            "competing" : "LeetCode (1670 ⭐) | CodeChef 2★ | Codeforces (1166)"
        }

    def __str__(self):
        return "Turning data into decisions, ideas into intelligent systems 🚀"
```

---

## 🛠️ Languages & Tools

<div align="center">

### 💻 Programming
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![DSA](https://img.shields.io/badge/DSA-FF6B6B?style=for-the-badge&logo=leetcode&logoColor=white)

### 🌐 Web Development
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)

### 🤖 AI / ML & Data Science
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google%20Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logo=yolo&logoColor=black)

### ☁️ Tools & Platforms
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)

</div>

---

## 🚀 Featured Projects

<div align="center">

### 🎯 CareerBoost AI
> *AI-Driven Career Intelligence Platform*

[![Demo](https://img.shields.io/badge/🌐%20Live%20Demo-4CAF50?style=for-the-badge)](https://your-demo-link.com)
[![GitHub](https://img.shields.io/badge/📂%20Source%20Code-181717?style=for-the-badge&logo=github)](https://github.com/dharshika)

```
Stack: React · FastAPI · MongoDB · ML · Python · Agentic AI
```

- 🧠 **Skill-Gap Analysis** using ML models across **218+ career roles**
- 📄 **ATS Resume Scoring** with real-time, actionable feedback
- 🗺️ **Personalized Career Roadmaps** — from where you are to where you want to be
- 🎨 Responsive React.js UI with Framer Motion animations & CSS Grid/Flexbox layouts

---

### 🐝 INTELLBEE
> *Multilingual AI Chatbot Platform*

[![Demo](https://img.shields.io/badge/🌐%20Live%20Demo-4CAF50?style=for-the-badge)](https://your-demo-link.com)
[![GitHub](https://img.shields.io/badge/📂%20Source%20Code-181717?style=for-the-badge&logo=github)](https://github.com/dharshika)

```
Stack: React · Flask · Google Gemini · JWT
```

- 🌍 **Multilingual** — Tamil, English & Hindi voice communication
- 🎙️ **Real-time Speech-to-Text / Text-to-Speech** processing
- 🖼️ **Multimodal** — image & audio analysis capabilities
- 🔐 Secure JWT-based authentication + conversation history management

---

### 👁️ SAFEVISION
> *Real-Time Computer Vision Safety System*

[![Demo](https://img.shields.io/badge/🌐%20Live%20Demo-4CAF50?style=for-the-badge)](https://your-demo-link.com)
[![GitHub](https://img.shields.io/badge/📂%20Source%20Code-181717?style=for-the-badge&logo=github)](https://github.com/dharshika)

```
Stack: Python · OpenCV · YOLO · ByteTrack · Streamlit · FastAPI · SQLite
```

- 🚦 **Traffic Safety Monitoring** — helmet violation detection & crowd analytics
- 📍 **Zone-Based Tracking** with rider-to-bike association logic
- 📸 **Automated Evidence Capture** with PDF report generation
- 🗄️ SQLite database logging for incident records

</div>

---

## 💼 Experience

| Role | Company | Period |
|------|---------|--------|
| 🌐 **Web Development Intern** | LearnLogicify Technologies, Coimbatore | Jun 2025 |
| 🤖 **AI & ML Implant Training** | CodeBind Technologies | Dec 2024 |

---

## 🏆 Competitive Programming

<div align="center">

| Platform | Rating | Rank / Solved | Badges |
|----------|--------|---------------|--------|
| 🟡 **LeetCode** | 1670 | Top 28% Globally · 200+ solved | 🔥 50 & 100 Day Streak |
| ⭐ **CodeChef** | 1521 | 2★ · 250+ solved | 🥇 Contest Contender · Problem Solver Gold |
| 🟦 **Codeforces** | 1166 | 50+ solved | — |

</div>

---

## 📜 Certifications

- ☁️ **AWS** – Cloud Foundations
- 🐍 **Infosys Springboard** – Python & Java Foundation
- 🌐 **Cisco Networking** – Python Essentials 1 & 2
- 🔵 **Juniper Networks** – Cloud / Mist AI (JNCIA)
- 📊 **Coursera** – Foundations of DSA (5 courses)
- 🤖 **Salesforce Trailhead** – AgentBlazer Champion Badge 🏆

---

## 🌟 Achievements

- 🎤 **Innovators Conclave 2025** @ BITS Pilani, Hyderabad — Presented a real-world solution at a national-level innovation event
- 💡 **Women's Hackathon** — Competed emphasizing innovation and collaborative problem-solving under time constraints
- 🏆 **Salesforce AgentBlazer Champion** — Demonstrated strong automation and AI skills
- 🎓 **Junior Mentorship & Technical Training** — Guided juniors on project tools and development workflows

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=dharshika&show_icons=true&theme=midnight-purple&include_all_commits=true&count_private=true"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=dharshika&layout=compact&langs_count=8&theme=midnight-purple"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=dharshika&theme=midnight-purple&hide_border=true)](https://git.io/streak-stats)

</div>

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer&animation=fadeIn"/>

*"Building intelligent systems, one model at a time."* ✨

**⭐ If you like what I build, consider starring my repos!**

</div>
