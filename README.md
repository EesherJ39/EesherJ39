<div align="center">
  <img src="./assets/terminal-profile.svg" alt="Animated terminal introducing Eesher Janda" width="780" />

  <br />

  <a href="https://www.linkedin.com/in/eesher-singh-janda-b8439434a/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:eeshersjanda@gmail.com"><img src="https://img.shields.io/badge/Email-eeshersjanda%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://komarev.com/ghpvc/?username=EesherJ39&style=flat-square&color=2f81f7&label=Profile+views" alt="Profile views" />
</div>

## About

I'm a Computer Science student at the **University of Guelph** focused on software engineering, distributed systems, developer infrastructure, and real-time applications. My project work emphasizes failure recovery, concurrency, durability, observability, and reproducible testing.

- **Seeking:** Summer 2027 software engineering internships
- **Currently exploring:** reliability engineering, distributed protocols, developer productivity, and performance
- **Community:** Volunteer and hackathon participant with Google Developer Groups on Campus - University of Guelph
- **Engineering approach:** define failure modes, test adversarial cases, and report reproducible measurements

## Featured engineering work

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/EesherJ39/TriageCI">TriageCI</a></h3>
      <p><strong>CI failure intelligence for engineering teams.</strong></p>
      <p>Ingests signed GitHub webhooks and JUnit reports, separates flaky tests from sustained regressions, applies idempotency and backpressure, and exposes operational metrics.</p>
      <p><code>TypeScript</code> <code>Node.js</code> <code>SQLite</code> <code>Docker</code></p>
      <p>
        <a href="https://github.com/EesherJ39/TriageCI/actions/workflows/ci.yml"><img src="https://github.com/EesherJ39/TriageCI/actions/workflows/ci.yml/badge.svg" alt="TriageCI CI" /></a>
        <img src="https://img.shields.io/badge/coverage-89.5%25-2ea44f?style=flat-square" alt="89.5 percent line coverage" />
      </p>
      <sub>375,000 observations across three 64-client stress runs at a median 12,261 observations/s.</sub>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/EesherJ39/raft-kv">RaftKV</a></h3>
      <p><strong>A fault-tolerant key-value store built from scratch.</strong></p>
      <p>Implements Raft consensus, persisted logs and snapshots, conflict repair, quorum-checked reads, and a C11/JNI write-ahead log with torn-tail recovery.</p>
      <p><code>Java</code> <code>C11</code> <code>JNI</code> <code>Python</code> <code>Docker</code></p>
      <p>
        <a href="https://github.com/EesherJ39/raft-kv/actions/workflows/ci.yml"><img src="https://github.com/EesherJ39/raft-kv/actions/workflows/ci.yml/badge.svg" alt="RaftKV CI" /></a>
        <img src="https://img.shields.io/badge/fault_scenarios-1%2C000-2ea44f?style=flat-square" alt="1,000 fault scenarios" />
      </p>
      <sub>Passed 8/8 protocol and recovery tests; verified a concurrent live history as linearizable with 186 ms failover.</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/EesherJ39/SyncLab">SyncLab</a></h3>
      <p><strong>An encrypted, local-first collaborative editor.</strong></p>
      <p>Combines an operation-based CRDT, persistent offline outbox replay, AES-GCM encryption, and an ordered ASP.NET Core WebSocket relay.</p>
      <p><code>C#</code> <code>ASP.NET Core</code> <code>React</code> <code>TypeScript</code></p>
      <p>
        <a href="https://github.com/EesherJ39/SyncLab/actions/workflows/ci.yml"><img src="https://github.com/EesherJ39/SyncLab/actions/workflows/ci.yml/badge.svg" alt="SyncLab CI" /></a>
        <img src="https://img.shields.io/badge/replica_observations-250k-2ea44f?style=flat-square" alt="250,000 replica-operation observations" />
      </p>
      <sub>Validated convergence over 200 randomized trials with temporary loss, duplicate delivery, and five replicas.</sub>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/EesherJ39/RepoLens">RepoLens</a></h3>
      <p><strong>Multi-language source indexing and exploration.</strong></p>
      <p>Extracts symbols and imports across C++, C#, Java, and Python, then exposes ranked search and repository dependency views through an ASP.NET Core API.</p>
      <p><code>C++</code> <code>C#</code> <code>SQLite</code> <code>React</code></p>
      <p>
        <a href="https://github.com/EesherJ39/RepoLens/actions/workflows/ci.yml"><img src="https://github.com/EesherJ39/RepoLens/actions/workflows/ci.yml/badge.svg" alt="RepoLens CI" /></a>
      </p>
      <sub>A supporting portfolio project; the three systems above are the current resume focus.</sub>
    </td>
  </tr>
</table>

## Engineering toolbox

`Java` `C` `C++` `C#` `Python` `TypeScript` `JavaScript` `SQL` `React` `ASP.NET Core` `Node.js` `PostgreSQL` `SQLite` `Redis` `Docker` `CMake` `GitHub Actions` `Linux`

## Verification

The featured repositories include reproducible tests, CI, architecture notes, security boundaries, benchmark methodology, and documented limitations.
