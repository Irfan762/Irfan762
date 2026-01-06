class SoftwareEngineer {
  constructor() {
    this.profile = {
      name: "Irfan Ramjan Tamboli",
      location: "Pune, India",
      education: {
        degree: "B.Tech in Information Technology",
        institute: "JSPM's RSCOE",
        cgpa: 8.88
      },
      contact: {
        email: "irfantamboli762@gmail.com",
        phone: "+91 8010204669"
      }
    };

    this.skills = {
      languages: ["C", "C++", "JavaScript", "Python", "SQL"],
      frontend: ["React.js", "HTML5", "CSS3", "Tailwind CSS", "Bootstrap"],
      backend: ["Node.js", "Express.js"],
      databases: ["MongoDB", "MySQL"],
      tools: ["Git", "GitHub", "Linux", "VS Code"]
    };

    this.interests = [
      "Full-Stack Development",
      "AI-powered Applications",
      "Scalable System Design",
      "Competitive Programming"
    ];
  }

  achievements() {
    return [
      "🏆 Winner – IIT Kharagpur Hackathon (1st / 5000+ teams)",
      "🥈 Finalist – VNIT Hackathon (Top 10 / 1500+ teams)",
      "🏅 4× Ideathon Winner",
      "💼 Training & Placement Coordinator (2000+ students)",
      "💻 Solved 300+ DSA problems on LeetCode (C++)"
    ];
  }

  currentlyLearning() {
    return [
      "Advanced Data Structures & Algorithms",
      "Machine Learning Fundamentals",
      "Three.js for Interactive Web Experiences"
    ];
  }

  introduction() {
    return `
Hi 👋 I'm ${this.profile.name},
a passionate Software Engineering student who enjoys
building scalable web applications and solving real-world problems.
Always excited to learn, collaborate, and create impact 🚀
    `;
  }
}

const irfan = new SoftwareEngineer();
console.log(irfan.introduction());
