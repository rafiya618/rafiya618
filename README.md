<div align="center">

<br/>

# Rafia Malik

<h3>AI Engineer &nbsp;·&nbsp; Backend Engineer &nbsp;·&nbsp; Full Stack Engineer</h3>

<p>
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&pause=1500&duration=3000&color=7C8CF8&center=true&vCenter=true&width=650&lines=Designing+backend+systems+that+scale;Building+products+on+top+of+LLMs;Architecting+RAG+pipelines+and+AI+agents;Node.js+%C2%B7+Spring+Boot+%C2%B7+Django+%C2%B7+Next.js" />
</p>

<p>
I design and build backend systems, distributed architectures, and AI-powered products —
from API design and event-driven services to retrieval-augmented generation and agentic workflows.
</p>

<br/>

<a href="https://github.com/rafiya618"><img src="https://img.shields.io/badge/GitHub-0d1117?style=flat-square&logo=github&logoColor=e6e6e6&labelColor=0d1117" height="28"/></a>
<a href="https://www.linkedin.com/in/rafia-malik-643068251/"><img src="https://img.shields.io/badge/LinkedIn-0d1117?style=flat-square&logo=linkedin&logoColor=7C8CF8&labelColor=0d1117" height="28"/></a>
<a href="mailto:your-email@gmail.com"><img src="https://img.shields.io/badge/Email-0d1117?style=flat-square&logo=gmail&logoColor=e6e6e6&labelColor=0d1117" height="28"/></a>
<a href="https://wa.me/92XXXXXXXXXX"><img src="https://img.shields.io/badge/WhatsApp-0d1117?style=flat-square&logo=whatsapp&logoColor=e6e6e6&labelColor=0d1117" height="28"/></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:7C8CF8,50:9D7CFF,100:0d1117&height=2&width=100%"/>

</div>

<br/>

## About

I work across the stack, but my focus is backend architecture and AI infrastructure — services that need to
stay reliable under load, and AI systems that need to stay grounded in real data. I've spent most of my time
in three areas: designing APIs and distributed services, building retrieval and agent pipelines on top of
LLMs, and shipping the full stack around them when a product needs to exist end to end.

I care about clean architecture, event-driven design, and systems that are easy to reason about six months
after they were written.

**Areas of focus**

`Large Language Models`  `AI Agents`  `Retrieval-Augmented Generation`  `Distributed Systems`
`Cloud Computing`  `Backend Architecture`  `API Design`  `Microservices`  `Performance`  `Open Source`

<br/>

## Engineering Domains

<table>
<tr>
<td width="200"><b>AI Engineering</b></td>
<td>
<img src="https://skillicons.dev/icons?i=openai&theme=dark" height="32"/>
<img src="https://img.shields.io/badge/Gemini-161b22?style=flat-square&logo=googlegemini&logoColor=8ab4f8" height="32"/>
<img src="https://img.shields.io/badge/Claude-161b22?style=flat-square&logo=claude&logoColor=d97757" height="32"/>
<img src="https://img.shields.io/badge/LangChain-161b22?style=flat-square&logo=langchain&logoColor=7C8CF8" height="32"/>
<img src="https://img.shields.io/badge/LlamaIndex-161b22?style=flat-square&logo=llama&logoColor=7C8CF8" height="32"/>
<img src="https://img.shields.io/badge/RAG-161b22?style=flat-square&logo=databricks&logoColor=7C8CF8" height="32"/>
<img src="https://img.shields.io/badge/AI_Agents-161b22?style=flat-square&logo=robotframework&logoColor=7C8CF8" height="32"/>
</td>
</tr>
<tr>
<td><b>Backend Engineering</b></td>
<td>
<img src="https://skillicons.dev/icons?i=nodejs,express,spring,django,fastapi&theme=dark" height="32"/>
</td>
</tr>
<tr>
<td><b>Frontend</b></td>
<td>
<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind&theme=dark" height="32"/>
</td>
</tr>
<tr>
<td><b>Databases</b></td>
<td>
<img src="https://skillicons.dev/icons?i=postgres,mongodb,redis&theme=dark" height="32"/>
</td>
</tr>
<tr>
<td><b>Distributed Systems</b></td>
<td>
<img src="https://skillicons.dev/icons?i=kafka,redis&theme=dark" height="32"/>
<img src="https://img.shields.io/badge/BullMQ-161b22?style=flat-square&logo=redis&logoColor=DC382D" height="32"/>
<img src="https://img.shields.io/badge/Redis_Streams-161b22?style=flat-square&logo=redis&logoColor=DC382D" height="32"/>
</td>
</tr>
<tr>
<td><b>Cloud &amp; DevOps</b></td>
<td>
<img src="https://skillicons.dev/icons?i=docker,kubernetes,aws,linux,nginx,githubactions,git&theme=dark" height="32"/>
</td>
</tr>
<tr>
<td><b>Automation</b></td>
<td>
<img src="https://img.shields.io/badge/n8n-161b22?style=flat-square&logo=n8n&logoColor=EA4B71" height="32"/>
</td>
</tr>
<tr>
<td><b>Languages</b></td>
<td>
<img src="https://skillicons.dev/icons?i=cpp,java,py,js,ts&theme=dark" height="32"/>
</td>
</tr>
</table>

<br/>

## How I Work

A representative shape of how I architect AI-backed products — request in, grounded response out.

```mermaid
flowchart TD
    A[Users] --> B[Frontend — React / Next.js]
    B --> C[API Gateway]
    C --> D[Auth Layer]
    D --> E[Backend Services]

    E --> F[(Redis Cache)]
    E --> G[Kafka Event Bus]
    G --> H[Background Workers]

    E --> I[(PostgreSQL)]
    E --> J[(MongoDB)]
    H --> K[(Vector Database)]

    K --> L{LLM Router}
    L --> M[OpenAI]
    L --> N[Gemini]
    L --> O[Claude]

    M --> P[Response Layer]
    N --> P
    O --> P
    P --> B

    classDef client fill:#161b22,stroke:#7C8CF8,color:#e6e6e6;
    classDef service fill:#161b22,stroke:#3f4a8a,color:#e6e6e6;
    classDef data fill:#0d1117,stroke:#565f89,color:#c9d1d9;
    classDef ai fill:#161b22,stroke:#d97757,color:#e6e6e6;

    class A,B client
    class C,D,E,G,H,L,P service
    class F,I,J,K data
    class M,N,O ai
```

<br/>

## Open Source

I contribute to and maintain projects across backend tooling and AI infrastructure. Active contributions and
repository activity are reflected in the graph below.

<br/>

## GitHub Analytics

<div align="center">

<img src="https://streak-stats.demolab.com?user=rafiya618&hide_border=true&background=0D1117&border=161B22&ring=7C8CF8&fire=9D7CFF&currStreakLabel=9D7CFF&sideLabels=C9D1D9&currStreakNum=E6E6E6&sideNums=E6E6E6&dates=8B949E"/>

<br/>

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=rafiya618&hide_border=true&bg_color=0D1117&color=9D7CFF&line=7C8CF8&point=E6E6E6&area=true&area_color=7C8CF8"/>

</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1117,100:0d1117&height=2&width=100%"/>

<div align="center">

<br/>

<pre>
$ ship()

→ one service at a time.
</pre>

<br/>

</div>
