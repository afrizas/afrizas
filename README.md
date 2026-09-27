<!--
  =============================================================
  GITHUB PROFILE README — Muhammad Afriza Ardiansyah (afrizas)
  =============================================================
  ONE THING TO REPLACE BEFORE USING:

  1. REPLACE_WITH_YOUR_BANNER_URL -> link to your banner image
     (upload it to this repo under /assets and use the raw
     githubusercontent link, or host it on imgur/postimg)

  All stats widgets already use the username: afrizas

  How to set up:
  Create a new repo with a name EXACTLY matching your GitHub
  username (i.e. "afrizas"), then put this file's content into
  that repo's README.md. GitHub will automatically display it
  on your profile page.
  =============================================================
-->

<div align="center">

<img src="https://i.ibb.co.com/LhskpwN7/file-00000000c030821186bbd0d544b9b855.png" alt="Banner" width="100%"/>

</div>

<div align="center">

# Muhammad Afriza Ardiansyah

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=800&color=58A6FF&center=true&vCenter=true&multiline=true&repeat=true&width=750&height=90&lines=Full-Stack+Developer+%26+UI%2FUX+Designer;Vibecoder+%7C+100%25+Coding+from+Android;Building+with+Code%2C+Crafting+with+Taste" alt="Typing SVG" />

<br/>

<img src="https://komarev.com/ghpvc/?username=afrizas&label=PROFILE%20VIEWS&color=58A6FF&style=for-the-badge" alt="Profile Views"/>
<img src="https://img.shields.io/github/followers/afrizas?label=FOLLOWERS&style=for-the-badge&color=58A6FF&logo=github&logoColor=white" alt="Followers"/>
<img src="https://img.shields.io/badge/STATUS-OPEN%20TO%20COLLAB-3FB950?style=for-the-badge&logo=statuspage&logoColor=white" alt="Status"/>

<br/><br/>

<img src="https://img.shields.io/badge/100%25-MOBILE%20DEVELOPER-3DDC84?style=for-the-badge&logo=android&logoColor=white"/>
<img src="https://img.shields.io/badge/UI%2FUX-ENTHUSIAST-A371F7?style=for-the-badge"/>
<img src="https://img.shields.io/badge/NIGHT%20OWL-CODER-1F6FEB?style=for-the-badge"/>
<img src="https://img.shields.io/badge/VIBE-CODING-F778BA?style=for-the-badge"/>

</div>

<br/>

![](https://img.shields.io/badge/-ABOUT%20ME-161B22?style=for-the-badge&logo=github&logoColor=58A6FF)

I'm **Muhammad Afriza Ardiansyah**, a *vibecoder* who enjoys building things from scratch, from the very first line of code all the way to an interface that actually feels good to look at. To me, programming and design aren't two separate worlds, they're one creative process that constantly feeds into each other.

What makes my journey a bit different: **my entire coding workflow runs 100% on Android**, from writing code and running local servers to pushing to GitHub, all through Termux and mobile apps. To me, hardware limitations aren't a wall, they're fuel for creativity.

I also love keeping up with the latest tech trends heading into 2026, from AI-assisted development and agentic coding workflows to increasingly intelligent design systems. Coding today isn't just about correct syntax anymore, it's about the vibe, how fast an idea can turn into something real.

<table>
<tr>
<td width="50%" valign="top">

**Quick Profile**

| | |
|---|---|
| Location | Indonesia |
| Role | Full-Stack Developer & UI/UX Designer |
| Device | 100% Mobile (Android) |
| Go-To Terminal | Termux |
| Go-To Editor | Acode & Vim (via Termux) |

</td>
<td width="50%" valign="top">

**2026 Focus Radar**

| | |
|---|---|
| Currently Learning | AI-Assisted / Agentic Development |
| Exploring | Mobile-First Development Workflow |
| Exploring | Edge Computing & WebAssembly |
| Exploring | AI-Powered Design Systems |
| Principle | Clean Code, Clean UI |

</td>
</tr>
</table>

<br/>

![](https://img.shields.io/badge/-VIBECODING%20WORKFLOW-161B22?style=for-the-badge&logo=googlemaps&logoColor=A371F7)

```mermaid
flowchart LR
    A[Idea & Trend Research] --> B[Brainstorm with AI]
    B --> C[Design UI/UX on Figma Mobile]
    C --> D[Code in Acode & Termux]
    D --> E[Test & Debug]
    E --> F[Deploy from Android]
    F --> G[Iterate & Optimize]
    G --> A

    style A fill:#0D1117,stroke:#58A6FF,color:#ffffff
    style B fill:#0D1117,stroke:#A371F7,color:#ffffff
    style C fill:#0D1117,stroke:#F778BA,color:#ffffff
    style D fill:#0D1117,stroke:#3FB950,color:#ffffff
    style E fill:#0D1117,stroke:#DB6D28,color:#ffffff
    style F fill:#0D1117,stroke:#58A6FF,color:#ffffff
    style G fill:#0D1117,stroke:#A371F7,color:#ffffff
```

<br/>

![](https://img.shields.io/badge/-GITHUB%20STATS-161B22?style=for-the-badge&logo=githubactions&logoColor=58A6FF)

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=afrizas&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub Stats" width="49%"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=afrizas&theme=tokyonight&hide_border=true" alt="GitHub Streak" width="49%"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=afrizas&layout=compact&theme=tokyonight&hide_border=true&langs_count=12" alt="Top Langs" width="49%"/>
<img src="https://github-profile-trophy.vercel.app/?username=afrizas&theme=tokyonight&no-frame=true&row=2&column=4&margin-w=8&margin-h=8" alt="Trophy" width="49%"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=afrizas&theme=tokyo-night&hide_border=true&area=true" alt="Activity Graph" width="100%"/>

</div>

<details>
<summary><b>Bonus: Contribution Snake Animation</b></summary>

<br/>

This feature needs a one-time GitHub Actions setup on your profile repo (it runs automatically on GitHub, so no PC required).

1. Create the file `.github/workflows/snake.yml` in the `afrizas/afrizas` repo
2. Paste in the following workflow:

```yaml
name: Generate Snake
on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
  push:
    branches: [ main ]

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: dist/github-contribution-grid-snake.svg
      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

3. Once the workflow has run, add this line to your README:

```md
![Snake animation](https://raw.githubusercontent.com/afrizas/afrizas/output/github-contribution-grid-snake.svg)
```

</details>

<br/>

![](https://img.shields.io/badge/-ALL%20PROGRAMMING%20LANGUAGES-161B22?style=for-the-badge&logo=codeforces&logoColor=58A6FF)

<div align="center">

<img src="https://skillicons.dev/icons?i=c,cpp,cs,java,kotlin,swift,dart,py,js,ts,php,ruby,go,rust,r&theme=dark&perline=15" alt="Programming Languages 1"/>
<img src="https://skillicons.dev/icons?i=scala,perl,lua,haskell,elixir,erlang,clojure,ocaml,nim,crystal,julia,zig,solidity,groovy,vala&theme=dark&perline=15" alt="Programming Languages 2"/>
<img src="https://skillicons.dev/icons?i=bash,powershell,coffeescript,actionscript,haxe,elm,scheme,forth,ceylon,matlab,graphql,fortran&theme=dark&perline=12" alt="Programming Languages 3"/>

</div>

<br/>

![](https://img.shields.io/badge/-MARKUP%20%26%20STYLING-161B22?style=for-the-badge&logo=w3c&logoColor=58A6FF)

<div align="center">
<img src="https://skillicons.dev/icons?i=html,css,sass,less,tailwind,bootstrap,materialui,styledcomponents,md,latex,svg,regex,wasm&theme=dark&perline=13"/>
</div>

<br/>

![](https://img.shields.io/badge/-FRAMEWORKS%20%26%20LIBRARIES-161B22?style=for-the-badge&logo=react&logoColor=58A6FF)

<div align="center">
<img src="https://skillicons.dev/icons?i=react,vue,angular,svelte,next,nuxtjs,gatsby,astro,flutter,jquery,threejs,d3,redux,vite,webpack,babel,gulp,rollup&theme=dark&perline=13"/>
</div>

<br/>

![](https://img.shields.io/badge/-BACKEND%20%26%20API-161B22?style=for-the-badge&logo=nodedotjs&logoColor=58A6FF)

<div align="center">
<img src="https://skillicons.dev/icons?i=nodejs,express,nestjs,django,flask,fastapi,laravel,rails,spring,symfony,ktor,deno&theme=dark&perline=12"/>
</div>

<br/>

![](https://img.shields.io/badge/-DATABASES%20%26%20STORAGE-161B22?style=for-the-badge&logo=postgresql&logoColor=58A6FF)

<div align="center">
<img src="https://skillicons.dev/icons?i=mysql,postgres,mongodb,redis,sqlite,cassandra,dynamodb,firebase,supabase,planetscale,neo4j,oracle,mariadb&theme=dark&perline=13"/>
</div>

<br/>

![](https://img.shields.io/badge/-CLOUD%20%26%20DEVOPS-161B22?style=for-the-badge&logo=docker&logoColor=58A6FF)

<div align="center">
<img src="https://skillicons.dev/icons?i=docker,kubernetes,aws,gcp,azure,githubactions,jenkins,terraform,ansible,nginx,apache,vercel,netlify,heroku,cloudflareworkers,digitalocean,grafana,prometheus&theme=dark&perline=13"/>
</div>

<br/>

![](https://img.shields.io/badge/-VERSION%20CONTROL%20%26%20COLLABORATION-161B22?style=for-the-badge&logo=git&logoColor=58A6FF)

<div align="center">
<img src="https://skillicons.dev/icons?i=git,github,gitlab,npm,yarn,pnpm,postman,notion,slack,discord,figma&theme=dark&perline=12"/>
<img src="https://img.shields.io/badge/GitHub%20Mobile-181717?style=for-the-badge&logo=github&logoColor=white"/>
</div>

<br/>

![](https://img.shields.io/badge/-CODE%20EDITORS%20%26%20IDE%20ON%20ANDROID-161B22?style=for-the-badge&logo=android&logoColor=58A6FF)

<div align="center">

<img src="https://skillicons.dev/icons?i=vim,neovim,emacs&theme=dark&perline=12"/>

<img src="https://img.shields.io/badge/Acode-2E7D32?style=for-the-badge"/>
<img src="https://img.shields.io/badge/AIDE-FF6D00?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Spck%20Editor-0288D1?style=for-the-badge"/>
<img src="https://img.shields.io/badge/QuickEdit-455A64?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Pydroid%203-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/CxxDroid-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>
<img src="https://img.shields.io/badge/C4Droid-5C6BC0?style=for-the-badge"/>

</div>

<br/>

![](https://img.shields.io/badge/-TESTING-161B22?style=for-the-badge&logo=testinglibrary&logoColor=58A6FF)

<div align="center">
<img src="https://skillicons.dev/icons?i=jest,mocha&theme=dark&perline=12"/>
</div>

<br/>

![](https://img.shields.io/badge/-DATA%20SCIENCE%20%26%20AI%2FML-161B22?style=for-the-badge&logo=tensorflow&logoColor=58A6FF)

<div align="center">
<img src="https://skillicons.dev/icons?i=tensorflow,pytorch,opencv,jupyter,numpy,pandas,sklearn,matplotlib&theme=dark&perline=12"/>
</div>

<br/>

![](https://img.shields.io/badge/-DESIGN%20%26%20MULTIMEDIA%20ON%20ANDROID-161B22?style=for-the-badge&logo=figma&logoColor=58A6FF)

<div align="center">

<img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"/>
<img src="https://img.shields.io/badge/Canva-00C4CC?style=for-the-badge&logo=canva&logoColor=white"/>
<img src="https://img.shields.io/badge/CapCut-000000?style=for-the-badge&logo=capcut&logoColor=white"/>
<img src="https://img.shields.io/badge/Alight%20Motion-E4007C?style=for-the-badge"/>
<img src="https://img.shields.io/badge/KineMaster-1AA3E8?style=for-the-badge"/>
<img src="https://img.shields.io/badge/VN%20Video%20Editor-6C63FF?style=for-the-badge"/>
<img src="https://img.shields.io/badge/PixelLab-FF6F00?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Picsart-FF5900?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Adobe%20Photoshop%20Express-31A8FF?style=for-the-badge&logo=adobephotoshop&logoColor=white"/>
<img src="https://img.shields.io/badge/Adobe%20Lightroom%20Mobile-31A8FF?style=for-the-badge&logo=adobelightroom&logoColor=white"/>
<img src="https://img.shields.io/badge/ibisPaint%20X-FF7F50?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Autodesk%20SketchBook-000000?style=for-the-badge"/>

</div>

<br/>

![](https://img.shields.io/badge/-ANDROID%20%26%20TERMUX%20ENVIRONMENT-161B22?style=for-the-badge&logo=linux&logoColor=58A6FF)

<div align="center">

<img src="https://skillicons.dev/icons?i=android,linux,ubuntu,debian,kali,arch&theme=dark&perline=12"/>

<img src="https://img.shields.io/badge/Termux-000000?style=for-the-badge&logo=termux&logoColor=00E676"/>
<img src="https://img.shields.io/badge/Termux%3AAPI-000000?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Termux%3AStyling-000000?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Termux%3AWidget-000000?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Termux%3ABoot-000000?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Termux%3AFloat-000000?style=for-the-badge"/>

</div>

<br/>

![](https://img.shields.io/badge/-AI%20ASSISTED%20%2F%20VIBECODING%20ON%20MOBILE-161B22?style=for-the-badge&logo=openai&logoColor=58A6FF)

<div align="center">

<img src="https://img.shields.io/badge/Claude%20AI-D97757?style=for-the-badge&logo=anthropic&logoColor=white"/>
<img src="https://img.shields.io/badge/ChatGPT-74AA9C?style=for-the-badge&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub%20Copilot-000000?style=for-the-badge&logo=githubcopilot&logoColor=white"/>
<img src="https://img.shields.io/badge/Replit-000000?style=for-the-badge&logo=replit&logoColor=white"/>
<img src="https://img.shields.io/badge/Perplexity-1FB8CD?style=for-the-badge&logo=perplexity&logoColor=white"/>
<img src="https://img.shields.io/badge/Midjourney-000000?style=for-the-badge&logo=midjourney&logoColor=white"/>

</div>

<br/>

![](https://img.shields.io/badge/-2026%20TECH%20TREND%20RADAR-161B22?style=for-the-badge&logo=trendmicro&logoColor=58A6FF)

| Trend | Why It's Worth Watching |
|---|---|
| AI-Assisted / Agentic Development | Coding workflows are shifting toward human + AI agent collaboration |
| Mobile-First Development | Building full software from just a smartphone is becoming more viable |
| Edge Computing & WebAssembly | Web app performance is closing the gap with native apps |
| AI-Powered Design Systems | Automated consistency, from components down to color tokens |
| Green Software Engineering | Energy efficiency is becoming a real code quality metric |
| Low-Code meets Pro-Code | Rapid prototyping without giving up technical control |

<br/>

<div align="center">

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="Quote"/>

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,100:58A6FF&height=120&section=footer" width="100%"/>

**Thanks for stopping by my profile.**

</div>
