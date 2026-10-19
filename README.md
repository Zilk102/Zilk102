<div align="center">

# Hi, I'm Zilk 👋

**TypeScript developer building with an AI-first workflow**<br>
Real-time multiplayer, 3D in the browser, and developer tools for working with AI assistants

**English** · [Русский](#ru)

</div>

## What I work on

I design systems and direct AI coding agents to build them, then audit and harden the result myself. My projects are end to end: from the game loop and netcode to the REST API, database, and deployment.

## Featured projects

<table>
<tr>
<td width="50%" valign="top">

### 🔮 [Sphere3D](https://github.com/Zilk102/spherio)
Real-time multiplayer 3D arena in the browser. Authoritative Colyseus server, Rapier 3D physics, client-side prediction, bots, accounts, skins and shop.

`TypeScript` `Babylon.js` `Colyseus` `Rapier` `PostgreSQL` `Redis` `Docker`

<a href="https://github.com/Zilk102/spherio"><img src="https://raw.githubusercontent.com/Zilk102/spherio/master/docs/media/05-gameplay.png" alt="Sphere3D gameplay" width="100%"></a>

</td>
<td width="50%" valign="top">

### 🗺️ [CodeMaps](https://github.com/Zilk102/CodeMaps)
Visualizes codebase architecture as a living dependency graph and acts as an MCP server, giving AI assistants architectural context: blast radius, health score, structure. Runs fully locally.

`TypeScript` `MCP` `tree-sitter` `AST analysis`

</td>
</tr>
</table>

## Tech I use

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=anthropic&logoColor=white)

Also: Babylon.js, Colyseus, Rapier physics, WebGL, JWT auth, Model Context Protocol.

## How I work with AI

- I write the spec and the architecture, the agent writes the first draft.
- I review the output and run it for real, not just read it.
- I audit for security and correctness. For Sphere3D that audit found and fixed forgeable tokens and an unauthenticated leaderboard endpoint, and the full write-up is public: [docs/AUDIT.md](https://github.com/Zilk102/spherio/blob/master/docs/AUDIT.md).

---

<a id="ru"></a>

## 🇷🇺 По-русски

**TypeScript-разработчик, работаю по AI-first подходу.** Делаю реалтайм-мультиплеер, 3D в браузере и инструменты для работы с ИИ-ассистентами.

- 🔮 **[Sphere3D](https://github.com/Zilk102/spherio)** — многопользовательская 3D-арена в браузере: авторитетный сервер на Colyseus, физика Rapier, клиентское предсказание, боты, аккаунты, скины и магазин.
- 🗺️ **[CodeMaps](https://github.com/Zilk102/CodeMaps)** — визуализация архитектуры кода в виде графа зависимостей и MCP-сервер, который даёт ИИ-ассистентам контекст архитектуры.

Процесс: я пишу спецификацию и архитектуру, агент делает черновик, я проверяю результат запуском и аудитирую безопасность.
