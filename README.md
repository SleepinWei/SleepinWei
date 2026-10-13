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

### Our Where · A shared photo atlas

**Give every memory a place.** A photo map for revisiting trips and sharing places with friends, available on the web, iOS, and Android.

<a href="https://memorybridge-photo-map-zhuyunwei123456-8595.vercel.app/"><img src="assets/our-where-preview.jpg" width="100%" alt="Our Where running on iOS: a Shanghai photo map with photo thumbnails, green photo clusters, and a member selector" /></a>

<sub>Preview from an iOS recording using AI-generated Shanghai sample photos.</sub>

- **Explore your photos:** import photos, read capture locations when available, and unfold nearby shots on an interactive map. Photos without GPS are welcome too.
- **Share a space:** public and private spaces, invitation links, and membership controls for a shared photo collection.
- **Keep memories close:** full-size photo viewing, location edits with undo, and cached photo previews for offline viewing.

`JavaScript` `Node.js` `Leaflet` `Supabase` `Swift` `Java`

**[Open Our Where ↗](https://memorybridge-photo-map-zhuyunwei123456-8595.vercel.app/)** · **[Android beta](https://github.com/SleepinWei/our-where-releases/releases/latest)** · **[iOS TestFlight](https://testflight.apple.com/join/T3RZgGg7)**

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
      <a href="https://github.com/SleepinWei/Scene-Renderer"><img src="assets/scene-renderer-cover-v3.jpg" width="100%" alt="Scene Renderer cover montage: realtime underwater sun shafts and procedural forest, path-traced fur, and photon-mapped pool caustics" /></a>
      <p><sub>Cover montage adapted from project captures; path-traced panels use OIDN. <a href="assets/scene-renderer-cover-v3.sources.md">Cover sources</a> · <a href="https://github.com/SleepinWei/Scene-Renderer/blob/main/docs/rendering-gallery.md">Original renders</a></sub></p>
      <p><strong>Real-time worlds and offline light transport.</strong></p>
      <p>A C++17 renderer with native Metal and Vulkan backends, a shared RHI, and a common GLSL shader pipeline. Immutable scene snapshots connect the logic and render threads.</p>
      <p>Real-time PBR, GTAO, soft shadows, atmospheric scattering, voxel clouds, and FFT water; underwater views add sun shafts, refraction, and seabed caustics. Procedural forests and virtual-textured terrain extend the natural scenes.</p>
      <p>CPU/Metal/Vulkan path tracing shares geometry BLAS/TLAS and supports textured materials, fur, cloth, refraction, and medium scattering. CPU BDPT and fixed-radius photon mapping render caustics; OIDN denoising is optional.</p>
      <p><code>C++17</code> <code>Metal</code> <code>Vulkan</code> <code>GLSL</code> <code>Path Tracing</code></p>
      <p><a href="https://github.com/SleepinWei/Scene-Renderer"><strong>Repository →</strong></a> · <a href="https://github.com/SleepinWei/Scene-Renderer/blob/main/docs/rendering-gallery.md">Gallery</a> · <a href="https://github.com/SleepinWei/Scene-Renderer/blob/main/docs/system-design.md">System design</a><br /><sub>Started as a team project for Tongji University's Computer Graphics course; expanded through continued iteration.</sub></p>
    </td>
  </tr>
</table>

### ARC Agent / Octos Harness

**Making coding agents easier to measure and improve.** Extends the Octos harness with execution traces, diagnostics, budget tracking, and an autoresearch controller. Candidate changes are compared through controlled experiments and independent acceptance checks, with the aim of reducing token usage and latency while preserving task correctness.

`Python` `Agent Harnesses` `Observability` `Autoresearch`

### LedgerAsk

**From trade documents to a reviewable ledger.** A commodity trade ledger application with invoice uploads, OCR, human review and confirmation, and ledger exports. Multi-tenant roles, private attachments, and durable background jobs support the workflow from document intake to structured records.

<a href="https://sleepinwei.github.io/ledgerask/"><img src="assets/ledgerask-preview.webp" width="100%" alt="LedgerAsk running in a demo environment: invoice and contract summaries, a document review workflow, matching, and ledger exports" /></a>

<sub>Application preview from an isolated demo environment using synthetic trade documents.</sub>

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
| **Graphics** | C++17 · Metal · Vulkan · OpenGL · GLSL · Three.js |
| **Web & Mobile** | TypeScript · React · Next.js · Expo · React Native |
| **Data & Services** | FastAPI · PostgreSQL · Supabase |

---

<p align="center"><sub>From execution traces to rendered scenes — building things I can inspect, understand, and keep improving.</sub></p>

<!--START_SECTION:waka-->
<!--END_SECTION:waka-->

