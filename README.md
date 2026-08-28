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

[![Typing SVG](https://readme-typing-svg.demolab.com/?font=Fira+Code&size=18&duration=2800&pause=1200&color=3EE8FF&center=true&vCenter=true&width=780&lines=Full-Stack+%26+Backend+Engineer;Decentralized+Apps+%7C+REST+APIs;Solidity+%7C+React+%7C+Node.js;Production-ready+Systems)](https://git.io/typing-svg)

<br />

[![Email](https://img.shields.io/badge/email-edgara.velazquezg%40gmail.com-0b1220?style=flat-square&logo=gmail&logoColor=3ee8ff)](mailto:edgara.velazquezg@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-edgar--velazquez-0b1220?style=flat-square&logo=linkedin&logoColor=3ee8ff)](https://www.linkedin.com/in/edgar-velazquez-9a1459266/)
[![GitHub](https://img.shields.io/badge/GitHub-Edgar--Devloper-0b1220?style=flat-square&logo=github&logoColor=3ee8ff)](https://github.com/Edgar-Devloper)
[![Repos](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Fusers%2FEdgar-Devloper&query=%24.public_repos&label=repos&color=3ecf8e&style=flat-square&labelColor=0b1220)](https://github.com/Edgar-Devloper?tab=repositories)

</div>

---

```bash
$ whoami
edgar.velazquez  —  Full-Stack & Backend Engineer
$ cat mission.txt
Diseño sistemas que llegan a producción: APIs REST, frontends
y bases relacionales. Código limpio, arquitectura modular,
lógica de negocio bien abstraída.
$ status --hire
available_for_hire: true
location: Venezuela · Remote
```

## `~/stack`

<p align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,ts,js,express,php,laravel,react,nextjs,html,css,postgres,mysql,solidity,git,github&perline=8" alt="Stack" />
</p>

```
backend   │  Node.js 18+ · TypeScript · Express · Laravel (PHP)
frontend   │  React · Next.js · HTML5 · CSS3
data       │  PostgreSQL · MySQL
web3       │  Solidity · Smart Contracts · Tokens · NFT
practice   │  Clean Code · Modular Architecture · Agile
```

## `~/architecture`

Dos enfoques de producto que construyo por separado — sin mezclar capas.

### `web3` · Solidity + Frontend (descentralizado)

dApp híbrida: estado financiero y lógica de negocio **on-chain**, con frontend que firma transacciones vía wallet y servicios tipados sobre ABIs.

```mermaid
flowchart TB
  subgraph FE["Frontend · React + TypeScript"]
    UI[UI + Feature Containers]
    H[Hooks + Query Cache]
  end

  subgraph WALLET["Wallet Layer"]
    W[Web3 Provider · Connect / AutoConnect]
    SIG[Sign · Approve · Send Tx]
  end

  subgraph INT["Integration Layer"]
    ABI[Typed ABIs + Contract Bindings]
    SVC[Domain Services · readContract / sendTransaction]
  end

  subgraph ONCHAIN["Smart Contracts · Solidity"]
    NFT[Identity NFT + Sale]
    STK[Staking Manager]
    SUB[Subscription / LP Pools]
    TOK[Tokens · ERC-20 Approve / Transfer]
    BNS[Bonus · Rewards · Referral Tree]
  end

  RPC[EVM RPC · Mainnet / Testnet]

  UI --> H --> W
  W --> SIG
  H --> SVC --> ABI
  SIG --> SVC
  ABI --> ONCHAIN --> RPC
```

```
UI → Hooks → Wallet → Services → ABIs → Smart Contracts → Blockchain
```

### `backend` · REST API (centralizado)

Productos web clásicos: frontend consume APIs, la lógica vive en el servidor y la persistencia en base relacional.

```mermaid
flowchart TB
  subgraph CLIENT["Frontend · React / Next.js"]
    APP[Web App + Admin Panel]
  end

  subgraph SERVER["Backend · Node.js / Laravel"]
    R[Routes / Controllers]
    S[Services · Business Logic]
    D[Repositories · ORM / Queries]
  end

  subgraph DATA["Data Layer"]
    DB[(PostgreSQL / MySQL)]
  end

  APP -->|HTTPS · REST · JSON| R --> S --> D --> DB
```

```
Client → REST API → Services → Repositories → Database
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
