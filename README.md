<p align="center">
  <img src="assets/profile-header-v2.png" width="100%" alt="SleepinWei — Building agents, rendering worlds, shipping useful tools." />
</p>

<p align="center">
  <strong>Computer Science master's student at Tongji University · 2024–present</strong><br />
  Exploring agent systems, computer graphics, and AI applications.
</p>

<!-- <p align="center">
  <a href="#projects">Projects</a> &nbsp;·&nbsp;
  <a href="https://sleepinwei.github.io/ValleyTown/">Visit ValleyTown ↗</a>
</p> -->

## Projects

### Jev LongSeq · Browser agents for long tasks

An evidence-grounded browser agent that combines **LLM planning with Jev action selection**. It breaks work into stages, tracks progress across pages, and reads back changes to verify what actually happened.

- **Plan, act, verify:** event-driven replanning, task contracts, and source-linked memory.
- **Inspect the run:** Trace Studio for browser replay, decisions, and model usage.
- **Improve with evidence:** evaluation tooling and an autoresearch loop for testing individual changes.

`Python` `Playwright` `BrowserGym` `Agent Evaluation`

**[Explore the repository →](https://github.com/SleepinWei/Jev-LongSeq)**

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>ValleyTown</h3>
      <a href="https://github.com/SleepinWei/ValleyTown"><img src="https://raw.githubusercontent.com/SleepinWei/ValleyTown/main/docs/images/shared-viewer.png" width="100%" alt="ValleyTown: an HD-2D town with a shared world and resident activity panel" /></a>
      <p><strong>A shared world, with individual stories.</strong></p>
      <p>An HD-2D agent town with 24 residents, individual memories, and evolving relationships. Visitors watch the same world; an administrator's browser runs the simulation.</p>
      <p>Day–night cycles, changing weather, and resident stories make agent behavior something you can explore.</p>
      <p><code>TypeScript</code> <code>React</code> <code>Three.js</code> <code>Supabase</code></p>
      <p><a href="https://sleepinwei.github.io/ValleyTown/"><strong>Live demo ↗</strong></a> · <a href="https://github.com/SleepinWei/ValleyTown">Repository</a></p>
    </td>
    <td width="50%" valign="top">
      <h3>Scene Renderer</h3>
      <a href="https://github.com/SleepinWei/Scene-Renderer"><img src="https://raw.githubusercontent.com/SleepinWei/Scene-Renderer/main/img/sky.png" width="100%" alt="Scene Renderer: physically based sky and a real-time ocean rendered with OpenGL" /></a>
      <p><strong>From atmospheric skies to ocean surfaces.</strong></p>
      <p>A modern OpenGL renderer for natural and indoor scenes: physically based skies, volumetric clouds, PBR materials, soft shadows, and GPU-driven terrain LOD.</p>
      <p>Includes a separate CPU path tracer with BVH acceleration and importance sampling.</p>
      <p><code>C++</code> <code>OpenGL</code> <code>GLSL</code> <code>Path Tracing</code></p>
      <p><a href="https://github.com/SleepinWei/Scene-Renderer"><strong>Repository &amp; gallery →</strong></a><br /><sub>Built with a team for Tongji University's Computer Graphics course.</sub></p>
    </td>
  </tr>
</table>

### ARC Agent / Octos Harness

**Making coding agents easier to measure and improve.** Extends the Octos harness with execution traces, diagnostics, budget tracking, and an autoresearch controller. Candidate changes are compared through controlled experiments and independent acceptance checks, with the aim of reducing token usage and latency while preserving task correctness.

`Python` `Agent Harnesses` `Observability` `Autoresearch`

### LedgerAsk

**From trade documents to a reviewable ledger.** A commodity trade ledger application with invoice uploads, OCR, human review and confirmation, and ledger exports. Multi-tenant roles, private attachments, and durable background jobs support the workflow from document intake to structured records.

`Next.js` `TypeScript` `FastAPI` `PostgreSQL` `OCR`

**[Visit LedgerAsk ↗](https://1000flow.com)**

### More Experiments

| Project | What it does |
| --- | --- |
| **MemoryBridge** | A private, collaborative memory map for close friends. Combines photos, places, dates, and stories into shared memory Pins, with reviewable AI suggestions. Built with Expo and React Native for OpenAI Build Week. |
| **WeChat Notify Bridge** | Connects phone notifications to a desktop workflow studio, with visual editing for business process steps, conditions, and reminders. |

## Toolbox

| Area | Tools I use across these projects |
| --- | --- |
| **Agents & AI** | Python · Playwright · BrowserGym · MCP · model APIs |
| **Graphics** | C++ · OpenGL · GLSL · Three.js |
| **Web & Mobile** | TypeScript · React · Next.js · Expo · React Native |
| **Data & Services** | FastAPI · PostgreSQL · Supabase |

---

<p align="center"><sub>From execution traces to rendered scenes — building things I can inspect, understand, and keep improving.</sub></p>

<!--START_SECTION:waka-->
<!--END_SECTION:waka-->
