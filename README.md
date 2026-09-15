<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/happys2333/happys2333/main/assets/hero-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/happys2333/happys2333/main/assets/hero-light.svg">
  <img alt="happys — Backend, AI, and open source. Reliable systems. Thoughtful tools." src="https://raw.githubusercontent.com/happys2333/happys2333/main/assets/hero-light.svg" width="100%">
</picture>

<p align="center">
  <a href="https://happys2333.github.io/">Website</a>
  &nbsp; / &nbsp;
  <a href="#open-source">Open source</a>
  &nbsp; / &nbsp;
  <a href="#selected-work">Selected work</a>
  &nbsp; / &nbsp;
  <a href="https://github.com/pulls?q=is%3Apr+author%3Ahappys2333">Pull requests</a>
</p>

## Hi, I'm happys

I build practical tools across **backend engineering and AI**, and contribute fixes to the open-source software I use. I'm interested in reliable systems, useful AI applications, and time-series modeling.

From debugging client lifecycles to comparing forecasting models, I enjoy turning a concrete problem into a working, testable solution.

## Open source

### [Deskflow](https://github.com/deskflow/deskflow)
**Client reliability & event lifecycles**

Fixed client-disconnect cleanup by keeping event handlers alive during dispatch and deferring cleanup until callbacks return. The contribution includes regression tests and AddressSanitizer validation.

`C++` `Qt` `Event-driven systems` &nbsp; · &nbsp; [Merged contribution ↗](https://github.com/deskflow/deskflow/pull/9958)

### [CC Switch](https://github.com/farion1231/cc-switch)
**Provider switching & configuration consistency**

Developed fixes for Codex provider switching across saved sessions, with credential isolation and coordinated state updates. Also submitted an OMO Slim import fix that resolves the active preset while preserving custom configuration fields.

`Rust` `Tauri` `State management` &nbsp; · &nbsp; Submitted PRs: [provider switching ↗](https://github.com/farion1231/cc-switch/pull/5815) / [preset imports ↗](https://github.com/farion1231/cc-switch/pull/7228)

### [Gitea](https://github.com/go-gitea/gitea)
**Pull-request workflow correctness**

Fixed the branch-deletion UI for branches still referenced by an open pull request, aligning the visible action with what the cleanup endpoint can actually perform.

`Go` `Git workflows` `UI/backend consistency` &nbsp; · &nbsp; [Merged contribution ↗](https://github.com/go-gitea/gitea/pull/39193)

## Selected work

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/happys2333/AI-ladder">AI Ladder ↗</a></h3>
      <p><strong>Making AI models easier to compare.</strong></p>
      <p>A model leaderboard and coding-plan explorer that brings benchmark, pricing, and provider information into one interface.</p>
      <p>Multi-source data ingestion, side-by-side comparison of up to three models, and bilingual browsing.</p>
      <p><code>Vue 3</code> <code>Vite</code> <code>Python</code></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/happys2333/DataMiningFinal">DataMiningFinal ↗</a></h3>
      <p><strong>Exploring time-series forecasting.</strong></p>
      <p>A data-mining course project comparing a ConvTrans-based Transformer with LSTM and regression baselines on COVID-19 case time series.</p>
      <p>Data preparation, sliding-window prediction, model comparison, and result visualization.</p>
      <p><code>Python</code> <code>PyTorch</code> <code>pandas</code></p>
      <p><sub>Small-data educational study, not a validated forecasting system.</sub></p>
    </td>
  </tr>
</table>

## Toolkit

| Area | Technologies |
| :--- | :--- |
| Backend & systems | Java · Go · C++ · Rust · Spring |
| AI & data | Python · PyTorch · pandas · NumPy |
| Interfaces & tools | Vue · Qt · Tauri · Git · Linux |

<details>
  <summary><strong>A little activity, a little fun</strong></summary>
  <br>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/happys2333/happys2333/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/happys2333/happys2333/output/github-contribution-grid-snake.svg">
    <img alt="Animated snake tracing my GitHub contribution graph" src="https://raw.githubusercontent.com/happys2333/happys2333/output/github-contribution-grid-snake.svg" width="100%">
  </picture>
</details>

<br>

<p align="center">
  <sub>Community · <a href="https://github.com/SUSTech-OpenSource">SUSTech-OpenSource</a> · <a href="https://github.com/HappysSoft">Happys Soft</a></sub>
  <br>
  <sub>Build with curiosity. Improve with care. Share what works.</sub>
</p>
