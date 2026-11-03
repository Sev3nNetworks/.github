<div align="center">
<a href="https://github.com/Sev3nNetworks"><img src="https://github.com/Sev3nNetworks.png" width="95" height="95" alt="Sev3nSoftware Logo" /></a>

## Sev3nSoftware

<p>Divisão oficial de software e utilitários de código aberto do ecossistema Sev3nNetworks.</p>
<a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/Licen%C3%A7a-MIT-0284c7?style=flat&logo=opensourceinitiative&logoColor=white" alt="Licença MIT" />
</a>
</div>

---

**Sev3nSoftware** atua como o braço de desenvolvimento tecnológico da casa-mãe **Sev3nNetworks**, inserida num ecossistema estruturado em três frentes operacionais:

| Divisão | Foco de Atuação | Estado |
| :--- | :--- | :--- |
| **`Sev3nSoftware`** | Engenharia de software, utilitários abertos, scripts e desenvolvimento de aplicações | **Ativo** |
| **`Sev3nHost`** | Infraestrutura de rede, servidores dedicados, VPS e gestão DNS | Em estruturação |
| **`Sev3nDesign`** | UI/UX, identidades visuais corporativas e desenvolvimento de interfaces | Em estruturação |

## Tecnologias & Stacks de Engenharia
<div align="left">

* **Linguagens & Motores:** `Python 3`, `Shell Script / Bash`, `C# / .NET Runtime`, `HTML / PHP / JavaScript / Node.js`
* **Plataformas Homologadas:** `Windows (10 / 11)`, `Linux (Mint, Debian, Ubuntu)`
* **Protocolos & Dados:** `REST APIs`, `JSON Schemas`, `HTTP Microservices`
* **Automação & Orquestração:** `Systemd Services & Timers`, `Git / GitHub Actions`
</div>

## Projetos em Destaque
<div align="left">

### [Sev3n-MetricsBridge](https://github.com/Sev3nNetworks/Sev3n-MetricsBridge)
Agente e ponte de telemetria multiplataforma desenhado para recolher, filtrar e exportar métricas de sistema em esquemas universais JSON (compatível com a app **OHMClient**, widgets de desktop e dashboards web).

* **Windows (`/win`):** Integração com o ecossistema `LibreHardwareMonitor` (WMI) para leitura de CPU, memória RAM, discos físicos, gráficas dedicadas e interfaces de rede. Disponibiliza micro-servidor local e interface web de preferências em `/definicoes`.
* **Linux / Unix (`/unix`):** Motor ultraleve em Python puro com leitura nativa de nós virtuais do kernel (`/proc` e `/sys`). Suporta dois modos de entrega:
  - **Modo Servidor / VPS:** Execução por Systemd Timer gerando ficheiro estático `data.json`, aproveitando o servidor HTTP já existente (Nginx/Apache) sem processos residentes em memória.
  - **Modo Autónomo (Desktop / Portátil):** Micro-servidor HTTP embutido para utilizadores domésticos (Linux Mint, Debian, Ubuntu), sem necessidade de instalar ou configurar servidores web adicionais.
</div>

---
<div align="center">
<sub>Sev3nSoftware · Divisão oficial de software da **Sev3nNetworks** · Todos os direitos reservados.</sub>
</div>
