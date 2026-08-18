<!-- ─────────────────────────────  HEADER  ───────────────────────────── -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=24&height=230&section=header&text=Yuvraj%20Singh&fontSize=64&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Software%20Development%20Engineer&descAlignY=56&descSize=18&descColor=e2d9ff" alt="Yuvraj Singh, Software Development Engineer" />

<p align="center">
  <a href="https://github.com/yuvrajnode">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1400&color=A78BFA&center=true&vCenter=true&width=760&height=42&lines=I+fix+bugs+in+libraries+I+use+every+day;transformers+%C2%B7+vet+%C2%B7+fish-speech+%C2%B7+cal.diy;Building+a+voice+AI+platform+at+work;Voice+cloning%2C+RAG%2C+and+a+phone+assistant+that+answers" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  SDE at Innovativus &nbsp;·&nbsp; B.Tech CSE, VIT &nbsp;·&nbsp; Uttarakhand, India
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/yuvrajnode"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white&labelColor=0d1117" alt="LinkedIn" /></a>
  &nbsp;
  <a href="mailto:yuvrajsingh9027249999@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white&labelColor=0d1117" alt="Email" /></a>
  &nbsp;
  <a href="https://github.com/yuvrajnode"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white&labelColor=0d1117" alt="GitHub" /></a>
  &nbsp;
  <a href="https://www.instagram.com/yuvrajyx/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white&labelColor=0d1117" alt="Instagram" /></a>
  &nbsp;
  <img src="https://komarev.com/ghpvc/?username=yuvrajnode&label=views&color=7c3aed&style=flat-square" alt="Profile views" />
</p>

<br/>

<!-- ─────────────────────────────  OPEN SOURCE  ───────────────────────────── -->
<img width="100%" src="assets/divider.svg" alt="" />

<h2 align="center">Open Source</h2>

<p align="center">
  Six projects, about 470k stars between them. Three of my patches are in main.<br/>
  Mostly small correctness fixes in code I hit while building something else.
</p>

<br/>

<table align="center" width="100%">
<tr>
<th align="left" width="24%">Project</th>
<th align="center" width="12%">Stars</th>
<th align="left" width="48%">What I changed</th>
<th align="center" width="16%">State</th>
</tr>

<tr>
<td valign="top">

**[huggingface/&#8203;transformers](https://github.com/huggingface/transformers)**
<br/><sub>Python · the model library</sub>

</td>
<td align="center" valign="top">

<img src="https://img.shields.io/github/stars/huggingface/transformers?style=flat-square&labelColor=0d1117&color=FFD21E" alt="stars" />

</td>
<td valign="top">

[**#47509**](https://github.com/huggingface/transformers/pull/47509)
Phi-4 Multimodal fell back to the wrong value when initialising vision position embeddings, so image embeddings were sized off the wrong dimension.

[**#47558**](https://github.com/huggingface/transformers/pull/47558)
`Pix2StructTextAttention` built its projection from `hidden_size` when it should use `d_kv`.

</td>
<td align="center" valign="top">

`merged`

`open`

</td>
</tr>

<tr>
<td valign="top">

**[safedep/vet](https://github.com/safedep/vet)**
<br/><sub>Go · supply-chain scanner</sub>

</td>
<td align="center" valign="top">

<img src="https://img.shields.io/github/stars/safedep/vet?style=flat-square&labelColor=0d1117&color=4B9BFF" alt="stars" />

</td>
<td valign="top">

[**#757**](https://github.com/safedep/vet/pull/757)
Errors during a GitHub org scan were swallowed, so a failed scan looked like a clean one. They propagate now.

[**#760**](https://github.com/safedep/vet/pull/760)
The trusted npm registry check compared whole URLs, which a lookalike host could slip past. It compares hostnames instead.

</td>
<td align="center" valign="top">

`merged`

`merged`

</td>
</tr>

<tr>
<td valign="top">

**[fishaudio/&#8203;fish-speech](https://github.com/fishaudio/fish-speech)**
<br/><sub>Python · TTS and voice cloning</sub>

</td>
<td align="center" valign="top">

<img src="https://img.shields.io/github/stars/fishaudio/fish-speech?style=flat-square&labelColor=0d1117&color=22d3ee" alt="stars" />

</td>
<td valign="top">

Three fixes found while wiring it into our voice pipeline:

[**#1317**](https://github.com/fishaudio/fish-speech/pull/1317) `list_files()` accepted a `recursive` argument and then ignored it.

[**#1318**](https://github.com/fishaudio/fish-speech/pull/1318) `ReferenceLoader.load_audio()` branched on tuple length rather than type.

[**#1319**](https://github.com/fishaudio/fish-speech/pull/1319) Bad reference arguments failed quietly instead of up front.

</td>
<td align="center" valign="top">

`open`

`open`

`open`

</td>
</tr>

<tr>
<td valign="top">

**[calcom/cal.diy](https://github.com/calcom/cal.diy)**
<br/><sub>TypeScript · scheduling</sub>

</td>
<td align="center" valign="top">

<img src="https://img.shields.io/github/stars/calcom/cal.diy?style=flat-square&labelColor=0d1117&color=f472b6" alt="stars" />

</td>
<td valign="top">

[**#29954**](https://github.com/calcom/cal.diy/pull/29954)
Duration badges on event types sorted as strings, so 120 min came before 15 min.

</td>
<td align="center" valign="top">

`open`

</td>
</tr>

<tr>
<td valign="top">

**[n8n-io/n8n](https://github.com/n8n-io/n8n)**
<br/><sub>TypeScript · workflow automation</sub>

</td>
<td align="center" valign="top">

<img src="https://img.shields.io/github/stars/n8n-io/n8n?style=flat-square&labelColor=0d1117&color=EA4B71" alt="stars" />

</td>
<td valign="top">

[**#20393**](https://github.com/n8n-io/n8n/pull/20393)
A timezone-aware `formatDateForUI` across the frontend, 269 lines over 6 files. Good discussion, but they went another way.

</td>
<td align="center" valign="top">

`closed`

</td>
</tr>

<tr>
<td valign="top">

**[processing/p5.js](https://github.com/processing/p5.js)**
<br/><sub>JavaScript · creative coding</sub>

</td>
<td align="center" valign="top">

<img src="https://img.shields.io/github/stars/processing/p5.js?style=flat-square&labelColor=0d1117&color=FF6B6B" alt="stars" />

</td>
<td valign="top">

[**#9027**](https://github.com/processing/p5.js/pull/9027)
`p5.Vector` is always three components, which catches people out in 2D sketches where `z` is quietly 0. Documented it.

</td>
<td align="center" valign="top">

`closed`

</td>
</tr>
</table>

<p align="center">
  <sub>
    <a href="https://github.com/search?q=is%3Apr+author%3Ayuvrajnode&type=pullrequests&s=updated&o=desc">All pull requests</a>
    &nbsp;·&nbsp;
    <a href="https://github.com/search?q=is%3Apr+author%3Ayuvrajnode+is%3Amerged&type=pullrequests">Merged only</a>
  </sub>
</p>

<br/>

<!-- ─────────────────────────────  ABOUT  ───────────────────────────── -->
<img width="100%" src="assets/divider.svg" alt="" />

<table border="0" cellpadding="18" width="100%">
<tr>
<td width="56%" valign="top">

### About

I'm a software engineer at Innovativus. Day to day I'm building a voice AI platform: two people, one of them a model, talking over a real phone line with no awkward pause in between.

That means zero-shot voice cloning with F5-TTS and Supertonic, a Twilio assistant that runs speech to text, then an LLM, then text to speech fast enough to feel like a conversation, and a RAG layer so it answers from your documents instead of guessing.

Before this I spent most of my time on full-stack work, and I still do — Next.js and Postgres on one side, Kubernetes and Grafana on the other. Some Solana on weekends.

If you want to talk about TTS latency, retrieval quality, or why your fine-tune got worse, I'm at
[yuvrajsingh9027249999@gmail.com](mailto:yuvrajsingh9027249999@gmail.com).

</td>
<td width="44%" valign="middle" align="center">

<img src="assets/ai-core.svg" width="86%" alt="Animated illustration of a glowing neural core with an audio waveform"/>

<p><sub>Roughly what it feels like in there</sub></p>

</td>
</tr>
</table>

<br/>

<!-- ─────────────────────────────  STACK  ───────────────────────────── -->
<img width="100%" src="assets/divider.svg" alt="" />

<h2 align="center">Stack</h2>
<br/>

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,ts,js,java,rust,solidity,bash&theme=dark&perline=7" alt="Python, TypeScript, JavaScript, Java, Rust, Solidity, Bash" />
</p>

<br/>

<p align="center">
  <b>AI, LLMs and voice</b>
  <br/><br/>
  <img src="https://skillicons.dev/icons?i=pytorch&theme=dark" alt="PyTorch" />
  &nbsp;
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face" />
  <img src="https://img.shields.io/badge/LangChain%20%2F%20LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain and LangGraph" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI" />
  <img src="https://img.shields.io/badge/Twilio-F22F46?style=flat-square&logo=twilio&logoColor=white" alt="Twilio Voice" />
  <br/>
  <img src="https://img.shields.io/badge/RAG-pgvector%20%7C%20Pinecone-7c3aed?style=flat-square&labelColor=0d1117" alt="RAG with pgvector and Pinecone" />
  <img src="https://img.shields.io/badge/fine--tuning-LoRA%20%7C%20RLHF-A78BFA?style=flat-square&labelColor=0d1117" alt="Fine-tuning with LoRA and RLHF" />
  <img src="https://img.shields.io/badge/agents-tool%20use%20%7C%20evals-6E56CF?style=flat-square&labelColor=0d1117" alt="Agents, tool use and evals" />
  <img src="https://img.shields.io/badge/voice-F5--TTS%20%7C%20Supertonic%20%7C%20STT-f472b6?style=flat-square&labelColor=0d1117" alt="Voice: F5-TTS, Supertonic, speech to text" />
</p>

<br/>

<table align="center" width="100%">
<tr>
<td align="center" width="50%">

**Frontend**
<br/>
<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,figma&theme=dark&perline=6" alt="React, Next.js, Tailwind, Figma" />

</td>
<td align="center" width="50%">

**Backend and data**
<br/>
<img src="https://skillicons.dev/icons?i=nodejs,express,redis,postgres,mongodb,mysql,prisma&theme=dark&perline=7" alt="Node.js, Express, Redis, Postgres, MongoDB, MySQL, Prisma" />

</td>
</tr>
<tr>
<td align="center">

**Infra**
<br/>
<img src="https://skillicons.dev/icons?i=docker,kubernetes,aws,githubactions,nginx,grafana,prometheus&theme=dark&perline=7" alt="Docker, Kubernetes, AWS, GitHub Actions, Nginx, Grafana, Prometheus" />

</td>
<td align="center">

**Chain and tools**
<br/>
<img src="https://skillicons.dev/icons?i=solana,ethereum,git,postman,neovim,vscode&theme=dark&perline=6" alt="Solana, Ethereum, Git, Postman, Neovim, VS Code" />

</td>
</tr>
</table>

<br/>

<!-- ─────────────────────────────  ACTIVITY  ───────────────────────────── -->
<img width="100%" src="assets/divider.svg" alt="" />

<h2 align="center">Activity</h2>
<br/>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=yuvrajnode&theme=tokyonight&hide_border=true&border_radius=10&ring=A78BFA&fire=A78BFA&currStreakLabel=A78BFA" height="165" alt="Commit streak" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=yuvrajnode&theme=tokyo-night&hide_border=true&border_radius=10&area=true&area_color=7c3aed&color=A78BFA&line=7c3aed&point=A78BFA" width="100%" alt="Contribution activity over the past year" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yuvrajnode/Yuvrajnode/output/github-contribution-grid-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/yuvrajnode/Yuvrajnode/output/github-contribution-grid-snake.svg" />
    <img src="https://raw.githubusercontent.com/yuvrajnode/Yuvrajnode/output/github-contribution-grid-snake.svg" width="100%" alt="Snake eating the contribution graph" />
  </picture>
</p>

<p align="center">
  <img src="profile-3d-contrib/profile-night-rainbow.svg" width="100%" alt="The same contributions as an isometric 3D city" />
</p>

<br/>

<img width="100%" src="assets/divider.svg" alt="" />

<p align="center">
  <sub>Rebuilt every night by a workflow that has never once asked for credit.</sub>
</p>
