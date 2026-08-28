<!--
  Sube ESTE README.md y la carpeta assets/ al repo:
  https://github.com/Edgar-Devloper/Edgar-Devloper

  El banner tiene que existir en:
  /assets/banner.svg
-->

<div align="center">
  <img src="./banner.png" alt="Edgar Velázquez — Full-Stack & Backend Engineer" width="100%" />
</div>

<br />

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com/?font=Fira+Code&size=18&duration=2800&pause=1200&background=0B1220&color=3ECF8E&center=true&vCenter=true&width=780&lines=Full-Stack+%26+Backend+Engineer;Decentralized+Apps+%7C+REST+APIs;Solidity+%7C+React+%7C+Node.js;Production-ready+Systems)](https://git.io/typing-svg)

<br />

[![Email](https://img.shields.io/badge/email-edgara.velazquezg%40gmail.com-0b1220?style=flat-square&logo=gmail&logoColor=3ee8ff)](mailto:edgara.velazquezg@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-edgar--velazquez-0b1220?style=flat-square&logo=linkedin&logoColor=3ee8ff)](https://www.linkedin.com/in/edgar-velazquez-9a1459266/)
[![GitHub](https://img.shields.io/badge/GitHub-Edgar--Devloper-0b1220?style=flat-square&logo=github&logoColor=3ee8ff)](https://github.com/Edgar-Devloper)
[![Repos](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2FEdgar-Devloper&query=%24.public_repos&label=repos&color=3ecf8e&style=flat-square&labelColor=0b1220)](https://github.com/Edgar-Devloper?tab=repositories)

</div>

---

```bash
$ edgar --profile
Full-Stack & Backend Engineer · Venezuela · Remote · Open to work

$ edgar --about
Construyo sistemas de producción: APIs REST, frontends React y contratos Solidity.
Código limpio · arquitectura modular · lógica de negocio bien abstraída.
```

## `~/stack`

<p align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,ts,js,express,php,laravel,react,nextjs,html,css,postgres,mysql,mongodb,solidity,git,github&perline=9" alt="Stack" />
</p>

```
backend   │  Node.js 18+ · TypeScript · Express · Laravel (PHP)
frontend   │  React · Next.js · HTML5 · CSS3
data       │  PostgreSQL · MySQL · MongoDB
web3       │  Solidity · Smart Contracts · Tokens · NFT
practice   │  Clean Code · Modular Architecture · Agile
```

## `~/architecture`

### `web3` · Solidity + Frontend (descentralizado)

```mermaid
flowchart TB
  subgraph PRESENTATION["Presentation Layer"]
    UI[Components + Views]
  end

  subgraph APPLICATION["Application Layer"]
    H[Hooks + State Management]
  end

  subgraph WALLET["Wallet Layer"]
    W[Connect + Session]
    SIG[Sign Transactions]
  end

  subgraph INTEGRATION["Integration Layer"]
    SVC[Contract Services]
    ABI[ABI Bindings + Types]
  end

  subgraph BLOCKCHAIN["Blockchain Layer"]
    SC[Solidity Smart Contracts]
    RPC[EVM RPC Network]
  end

  UI --> H --> W
  W --> SIG
  H --> SVC --> ABI
  SIG --> SVC
  ABI --> SC --> RPC
```

```
Presentation → Application → Wallet → Integration → Blockchain
```

### `backend` · REST API (centralizado)

```mermaid
flowchart TB
  subgraph CLIENT["Presentation Layer"]
    APP[Web Client + Admin UI]
  end

  subgraph SERVER["Application Layer"]
    R[Routes / Controllers]
    S[Services · Business Logic]
    D[Repositories · Data Access]
  end

  subgraph DATA["Data Layer"]
    DB[(PostgreSQL / MySQL / MongoDB)]
  end

  APP -->|HTTPS · REST · JSON| R --> S --> D --> DB
```

```
Presentation → Application → Data
```

## `~/projects`

<table>
  <tr>
    <td valign="top" width="50%">
      <h3><a href="https://github.com/Edgar-Devloper/Pollos_v2_Backend">Pollos_v2_Backend</a></h3>
      API TypeScript de un producto en producción.<br/><br/>
      <code>TypeScript</code> · <code>Node.js</code> · <code>API</code>
    </td>
    <td valign="top" width="50%">
      <h3><a href="https://github.com/Edgar-Devloper/Pollo_v2_Admin">Pollo_v2_Admin</a></h3>
      Panel de administración del mismo producto.<br/><br/>
      <code>JavaScript</code> · <code>Dashboard</code>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <h3><a href="https://github.com/Edgar-Devloper/Front-Products">Front-Products</a></h3>
      Frontend de catálogo / productos.<br/><br/>
      <code>TypeScript</code> · <code>React</code>
    </td>
    <td valign="top">
      <h3><a href="https://github.com/Edgar-Devloper/solidity-governance-vault">solidity-governance-vault</a></h3>
      Vault de gobernanza con decay de voting power.<br/><br/>
      <code>Solidity</code> · <code>Web3</code>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <h3><a href="https://github.com/Edgar-Devloper/backend-usuarios">backend-usuarios</a></h3>
      API de gestión de usuarios.<br/><br/>
      <code>JavaScript</code> · <code>Auth</code>
    </td>
    <td valign="top">
      <h3><a href="https://github.com/Edgar-Devloper/Front-End-Poll">Front-End-Poll</a></h3>
      Frontend en TypeScript.<br/><br/>
      <code>TypeScript</code> · <code>UI</code>
    </td>
  </tr>
</table>

## `~/connect`

```ts
const contact = {
  email:    "edgara.velazquezg@gmail.com",
  linkedin: "linkedin.com/in/edgar-velazquez-9a1459266",
  github:   "github.com/Edgar-Devloper",
  openTo:   ["full-time remote", "contract"],
};
```

**mailto: [edgara.velazquezg@gmail.com](mailto:edgara.velazquezg@gmail.com)**  
**linkedin: [edgar-velazquez](https://www.linkedin.com/in/edgar-velazquez-9a1459266/)**  
**github: [Edgar-Devloper](https://github.com/Edgar-Devloper)**
