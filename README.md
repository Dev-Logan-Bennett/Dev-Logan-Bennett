<h1 align="center">Hey 👋, I'm Logan</h1>

<h3><em>Research Coordinator in the <a href="https://poldracklab.org/">Poldrack Lab</a> at <a href="https://www.stanford.edu/">Stanford University</a></em></h3>

- ⚙️ use daily: `.js`, `.html`, `.css`, `.py`
- 🌱 learning `.rs` and `.go`
- 💬 ping me about: gaming, mountain biking, watercoloring
- 🎂 guilty pleasure: reality tv 

---

### 💭 About me 

<details>
  <summary><strong>TS interfaces</strong></summary>

  
  ```typescript
  interface Job {
  employer: string;
  department: string;
  mentors: string[];
}

interface Seeking {
  actively: boolean;
  ofInterest: string[];
}

interface Interests {
  research: string[];
  seeking: Seeking;
}

interface Education {
  degree: string;
  institution: string;
  year: number;
  honors: string;
}

interface Me {
  code: string[];
  tools: string[];
  research: string[];
  job: Job;
  interests: Interests;
  hobbies: string[];
  education: Education;
}
  ```
</details>

```typescript
const Logan: Me = {
  code: ["JavaScript", "TypeScript", "HTML", "CSS", "Python"],
  tools: ["Tailwind CSS", "React", "Node", "Next.js", "Styled-Components", "Docker"],
  research: ["fMRI", "EEG", "open-source", "reproducibility", "cognitive tasks"],
  job: {
    employer: "Stanford University",
    department: "Psychology",
    mentors: ["Patrick Bissett", "Russell Poldrack"],
  },
  interests: {
    research: ["software for science", "cognitive neuroscience", "neuroimaging"],
    seeking: {
      actively: false,
      ofInterest: ["PhD", "Software Engineer"]
    }
  },
  hobbies: ["biking", "hiking", "volleyball"],
  education: {
      degree: "BSc in Neuroscience",
      institution: "Temple University",
      year: 2023,
      honors: "Summa Cum Laude"
  }
};
```

---

#### Can you find my middle name? (And other hidden words?): 

| R | A | D | J | A | N | G |
|---|---|---|---|---|---|---|
| U | J | S | T | A | T | O |
| S | S | O | H | B | M | T |
| T | P | N | R | C | C | Y |
| L | S | O | E | D | L | P |
| A | O | T | E | N | A | E |
| N | G | E | E | C | I | N |

<details>
  <summary><strong>Give up? Click for the solution:</strong></summary>
  
#### **X** marks the spot:

| R | A | D | J | A | N | G |
|---|---|---|---|---|---|---|
| U | X | S | T | A | T | O |
| S | S | X | H | B | M | T |
| T | P | N | X | C | C | Y |
| L | S | O | E | X | L | P |
| A | O | T | E | N | X | E |
| N | G | E | E | C | I | X |

</details>
<!--
**Dev-Logan-Bennett/Dev-Logan-Bennett** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
