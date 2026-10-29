<!--
  SETUP
  - Replace USERNAME, YOUR_EMAIL, YOUR_LINKEDIN, YOUR_UPWORK_URL
  - Replace REPO_1 / REPO_2 with repos you want shown (or delete that section)
  - Search for "ADD:" below. Each one is a spot where one real detail from
    you (a number, a story, a mistake you fixed) will make this read like you.
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,60:1E1B4B,100:7C3AED&height=200&section=header&text=Harmander%20Singh&fontSize=46&fontColor=F8FAFC&fontAlignY=40&desc=C%23%20%2F%20.NET%20developer&descSize=18&descAlignY=60&descColor=C4B5FD" width="100%" alt="Harmander Singh, C# / .NET developer" />

<img src="https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt=".NET" />
<img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white" alt="C#" />
<img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white" alt="SQL Server" />
<img src="https://img.shields.io/badge/Open_to_work-10B981?style=flat-square" alt="Open to work" />

</div>

<br/>

Hi, I'm Harmander. I've been working with C# and .NET for about nine years, building and maintaining web applications, desktop apps, background services, and backends using SQL Server and other databases.

I like software that's easy to maintain and fast where it matters. I'd rather ship something simple that works than something clever that nobody wants to touch. <!-- ADD: one sentence about what you actually enjoy or what you're like to work with. -->

I'm open to remote roles and freelance projects. If you've got something that needs a careful .NET developer, [email me](mailto:singhharmander8@gmail.com).

<br/>

## What I work with

- **Languages:** C#, T-SQL
- **Backend:** ASP.NET Core, REST APIs, Entity Framework Core, third-party API integrations
- **Desktop:** WPF, WinForms
- **Windows internals:** Windows Services, local proxies, system-level tools
- **Data:** SQL Server schema design and query tuning
- **Lately:** adding AI models to desktop tools

<div align="center">
<img src="https://skillicons.dev/icons?i=cs,dotnet,visualstudio,azure,git,github,docker&theme=dark" alt="Tools" />
</div>

<br/>

## Things I've built

<details open>
<summary><b>Internet access control for Windows</b></summary>
<br/>

A Windows internet filter with per-user rules. Traffic goes through a local proxy, and only whitelisted apps are allowed online. A Windows service watches the proxy and restarts it if it dies. It's running in production.

```mermaid
flowchart LR
    A[App / process] --> B[Local proxy]
    B --> C{Rules for this user}
    C -->|allowed| D[Internet]
    C -->|blocked| E[Dropped]
    F[Watchdog service] -.-> B
    F <--> C
```

<!-- ADD: the hardest part of this project, in one or two sentences. E.g. a bug that only showed up in production, or how you handled apps that bypass the proxy. -->

</details>

<details>
<summary><b>Football analytics desktop app</b></summary>
<br/>

A desktop app that pulls match data from external sports APIs into SQL Server and lets you dig through it. I spent most of the effort on the database: a normalized schema with proper indexes, so queries stay quick as the history grows, and the UI doesn't freeze while they run.

```mermaid
flowchart LR
    A[Sports APIs] --> B[Async sync job]
    B --> C[(SQL Server)]
    C --> D[Desktop app]
```

<!-- ADD: a real number. E.g. how many rows, or how much faster a slow query got after you fixed it. -->

</details>

<details>
<summary><b>AI response assistant</b></summary>
<br/>

A small desktop tool that drafts business replies using AI models. The calls are async, so the window stays responsive while the answer streams in. I built it for my own daily use first, which is why it's quick and has very few buttons.

<!-- ADD: who uses it, or what it saved you. One honest line is enough. -->

</details>

<br/>

## Activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=harmander-singh&show_icons=true&hide_border=true&bg_color=0D1117&title_color=A855F7&icon_color=7C3AED&text_color=C9D1D9&count_private=true" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=harmander-singh&layout=compact&hide_border=true&bg_color=0D1117&title_color=A855F7&text_color=C9D1D9" alt="Top languages" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/harmander-singh/harmander-singh/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/harmander-singh/harmander-singh/output/github-snake.svg" />
  <img alt="Contribution graph snake" src="https://raw.githubusercontent.com/harmander-singh/harmander-singh/output/github-snake-dark.svg" width="100%" />
</picture>

</div>

<br/>

## Get in touch

I'm looking for long-term remote roles (senior C# / .NET, backend, or desktop) and freelance projects like custom systems, APIs, and SQL performance work. Startups are welcome too.

<div align="center">

<a href="mailto:singhharmander8@gmail.com"><img src="https://img.shields.io/badge/Email-7C3AED?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7C3AED,60:1E1B4B,100:0D1117&height=90&section=footer" width="100%" alt="" />

</div>
