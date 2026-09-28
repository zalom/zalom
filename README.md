# Zlatko Alomerovic

Security-minded, product-first, AI and software engineer, and engineering lead. I build AI agent systems and use them to run product discovery and delivery.

My blog, [zlatkocodes.com](https://zlatkocodes.com), holds my writing and [more about me](https://zlatkocodes.com/about/). You can also find me on [LinkedIn](https://linkedin.com/in/zlatkoalomerovic) and [X](https://x.com/_zalom).

## About me

Twelve years of experience building and scaling web applications, with a strong focus on code architecture and team workflows optimizations. I deeply care about developer experience (DevEx).

I have led distributed teams, improved software development life cycle (SDLC) processes and owned deliveries across distributed systems. I have run hiring and capability assessment of new engineers, and helped teams actually stick to the systems they adopt.

With Ruby on Rails as my daily driver, I can work on any stack.

A father and husband, an engineer, and a Judo coach. Former tourist guide for major cities and attractions across 10 European countries.

## What I am building

The following sections describe the open-source projects I work on now.

### Plastic

<img src="https://raw.githubusercontent.com/zalom/plastic/main/assets/plastic-logo.svg" alt="Plastic" width="240">

**One command that turns an intent into a durable, linked record of decisions, plans, delivery, and outcomes.**

[![npm version](https://img.shields.io/npm/v/@zalom/plastic)](https://www.npmjs.com/package/@zalom/plastic)
[![GitHub stars](https://img.shields.io/github/stars/zalom/plastic)](https://github.com/zalom/plastic)

Plastic is an intent-based system for AI-assisted work. You start with an intent, such as "I want users who are locked out to recover access safely." Plastic carries that intent through four stages, What, Why, How, and Exec, and leaves a readable record of how the idea became real.

Plastic does the following:

- Keeps one store for each project, in plain Markdown and Git.
- Records each decision with the reason behind it.
- Plans work as a checklist or as a graph of steps, and names the next step.
- Hands work to a team of agents and reports the result.
- Runs in Claude Code and Codex CLI.

To install Plastic for Claude Code, run the following command:

```sh
npx -y @zalom/plastic install --claude
```

To go further, read the [Plastic README](https://github.com/zalom/plastic#readme), the [Plastic quick start](https://github.com/zalom/plastic#quick-start), or the [Plastic manifesto](https://github.com/zalom/plastic/blob/main/MANIFESTO.md).

### Agent skills

[Agent skills](https://github.com/zalom/agent-skills) is my Claude Code plugin marketplace, with skills I write for my own work. Each skill has a `SKILL.md` file that routes the task, and references that load only when the task needs them.

The marketplace has the following five skills:

| Skill | What it does |
|---|---|
| [plain-writing](https://github.com/zalom/agent-skills/tree/main/plain-writing) | Keeps AI-written prose, documentation, commit messages, and replies in one style: the Google developer documentation style guide, plus your own overrides. |
| [ruby-quality-checking](https://github.com/zalom/agent-skills/tree/main/ruby-quality-checking) | Checks a Ruby or Rails change on the changed code only: lint, tests, patch coverage, mutation testing, and change-risk (CRAP) scores. |
| [ruby-testing](https://github.com/zalom/agent-skills/tree/main/ruby-testing) | Writes and refactors Ruby and Rails tests in the project's own framework, Minitest or RSpec. |
| [skill-creating](https://github.com/zalom/agent-skills/tree/main/skill-creating) | Writes or revises an Agent Skill, a subagent, or a lifecycle hook with progressive disclosure. |
| [skill-evaluating](https://github.com/zalom/agent-skills/tree/main/skill-evaluating) | Evaluates skills for correctness, convention compliance, and progressive disclosure. |

To add the marketplace and install a skill, run the following commands:

```sh
claude plugin marketplace add zalom/agent-skills
claude plugin install plain-writing@zalom-skills
```


## From my blog

The following post is the latest on my blog.

<img src="https://zlatkocodes.com/images/posts/my-tech-story-ode-to-ruby/ruby_changed_my_life_thumbnail.webp" alt="The Ruby language banner: a red gem under the words A Programmer's Best Friend." width="480">

**[My tech story (Ode to Ruby)](https://zlatkocodes.com/blog/my-tech-story-ode-to-ruby/)**, March 8, 2026

An engineer traces three decades from wartime Commodore dreams to Ruby on Rails consulting, finding in Ruby the readable syntax that finally made programming feel human. Now he teaches others to keep it simple, grateful that one language opened every door.

Read [all posts on zlatkocodes.com](https://zlatkocodes.com/blog/).

## What I am interested in

- **AI engineering.** Agent systems, agent skills, and the checks that keep agent output correct.
- **Engineering leadership.** Distributed teams, delivery workflows, hiring, and developer experience.
- **Product discovery with AI.** Agents that research, test, and shape an idea before a team builds it.

I use the following tools every day:

<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/ruby/ruby-original.svg" alt="Ruby" title="Ruby" width="40">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/rails/rails-plain.svg" alt="Ruby on Rails" title="Ruby on Rails" width="40">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" alt="JavaScript" title="JavaScript" width="40">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/tailwindcss/tailwindcss-original.svg" alt="Tailwind CSS" title="Tailwind CSS" width="40">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" title="PostgreSQL" width="40">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/sqlite/sqlite-original.svg" alt="SQLite" title="SQLite" width="40">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" alt="Docker" title="Docker" width="40">
</p>

Next, I want to learn AI infrastructure, Go, and Python.

<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/go/go-original-wordmark.svg" alt="Go" title="Go" width="40">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" alt="Python" title="Python" width="40">
</p>

## What others say about my work

The following recommendations come from LinkedIn, quoted as written.

<figure>
  <figcaption>
    <img src="https://zlatkocodes.com/images/about/amir-habhab-avatar_content.webp" alt="" width="56" height="56" align="left">
    <p>
      <strong>Amir F. Habhab</strong><br>
      CEO at Vergence and Manta<br>
      <sub>April 30, 2023, Amir managed Zlatko directly</sub>
    </p>
  </figcaption>
  <blockquote cite="https://www.linkedin.com/in/zlatkoalomerovic/details/recommendations/">
    <p>It has been a great pleasure to collaborate with Zlatko for over two years, and I cannot emphasize enough his remarkable skills and commitment. As a team lead and software developer, he consistently went the extra mile to ensure success. Beyond his technical expertise, Zlatko also fostered a positive culture within our team, creating an environment where everyone felt motivated and engaged. His warm personality and positive attitude were contagious, making it a joy to work alongside him. I wholeheartedly endorse Zlatko and wish him all the best in his future pursuits.</p>
  </blockquote>
</figure>

<p align="center">* * *</p>

<figure>
  <figcaption>
    <img src="https://zlatkocodes.com/images/about/kasper-johnsen-avatar_content.webp" alt="" width="56" height="56" align="left">
    <p>
      <strong>Kasper Johnsen</strong><br>
      Vice President of Engineering @ Homekey.ai<br>
      <sub>June 7, 2023, Kasper managed Zlatko directly</sub>
    </p>
  </figcaption>
  <blockquote cite="https://www.linkedin.com/in/zlatkoalomerovic/details/recommendations/">
    <p>I had the pleasure of working closely with Zlatko at Marketer, where he excelled as a Lead Software Developer. Zlatko's expertise in Ruby on Rails and his ability to develop features for our PropTech products were truly impressive. Throughout his time with us, Zlatko consistently demonstrated his technical prowess and leadership abilities. He played a crucial role in developing new features and addressing bugs, showcasing his attention to detail and dedication to delivering high-quality solutions....</p>
  </blockquote>
</figure>

<p align="center">* * *</p>

<figure>
  <figcaption>
    <img src="https://zlatkocodes.com/images/about/kaisa-eidet-avatar_content.webp" alt="" width="56" height="56" align="left">
    <p>
      <strong>Kaisa Eidet</strong><br>
      HomeKey.ai<br>
      <sub>April 20, 2023, Kaisa worked with Zlatko on the same team</sub>
    </p>
  </figcaption>
  <blockquote cite="https://www.linkedin.com/in/zlatkoalomerovic/details/recommendations/">
    <p>I highly recommend Zlatko as a detail oriented, solution-oriented, and experienced developer. He consistently delivered high-quality work and was a pleasure to work with due to his positive attitude. His expertise in complex software development, critical thinking skills, problem solving and dedication to teamwork make him an invaluable asset to any team.</p>
  </blockquote>
</figure>

<p align="center">* * *</p>

<figure>
  <figcaption>
    <p>
      <strong>João Ferro Rodrigues</strong><br>
      M&amp;A and Strategic Partnerships at HiBob<br>
      <sub>December 15, 2017, João was senior to Zlatko but didn't manage Zlatko directly</sub>
    </p>
  </figcaption>
  <blockquote cite="https://www.linkedin.com/in/zlatkoalomerovic/details/recommendations/">
    <p>Zlatko worked with us remotely as back-end developer (ruby on rails) for several months. He quickly showed excellence in the two critical skills we were looking for that job: good technical ability and high work ethics managing the remote work. Also, Zlatko quickly overcome the physical distance barrier and become 'one of us', bringing lots of enthusiasm and true commitment to our team goals. Therefore, and based in ourjoint work experience, I strongly recommend Zlatko for any position as ruby on rails back-end developer. He is a great developer and (even more importantly) an outstanding human being.</p>
  </blockquote>
</figure>

<p align="center">* * *</p>

<figure>
  <figcaption>
    <img src="https://zlatkocodes.com/images/about/mariusz-mikolajczak-avatar_content.webp" alt="" width="56" height="56" align="left">
    <p>
      <strong>Mariusz Mikołajczak</strong><br>
      Ruby on Rails Developer<br>
      <sub>May 9, 2022, Mariusz reported to Zlatko directly</sub>
    </p>
  </figcaption>
  <blockquote cite="https://www.linkedin.com/in/zlatkoalomerovic/details/recommendations/">
    <p>I had pleasure working with Zlatko. He is great manager and developer. He has a lot of knowledge about software engineering and he is happy to share it. His motto is #team-work and this really work. I would like to have such manager in the future.</p>
  </blockquote>
</figure>

Read [all recommendations on LinkedIn](https://www.linkedin.com/in/zlatkoalomerovic/details/recommendations/).

---

<sub>Keywords:
macOS, Linux, Windows, Ruby, Ruby on Rails, Hotwire, PostgreSQL, SQLite, JavaScript, StimulusJS, AlpineJS, VueJS, EmberJS, Tailwind CSS, Bootstrap, Jekyll, Minitest, RSpec, RubyMine, VSCode, Vim, Zellij + Alacritty, Git, GitHub, GitLab, Heroku, Google Cloud, AWS, Cloudflare, Docker, Bun, Linear, Jira, Trello, Claude Code, Codex CLI, MCP, Augment Code, Google Gemini, Perplexity.ai, LibreChat, ChatGPT, GitHub Copilot, Groq, Ollama</sub>
