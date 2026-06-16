<div align="center">

<img src="./assets/2f3abaaf25b5d45cbfc50a00e79fc448.gif" width="230" align="left" title="Neymar Jr" style="margin-right: 40px;" />

<img src="https://capsule-render.vercel.app/api?type=venom&height=300&text=Gabriel%20Santos&fontSize=72&fontColor=00FF66&color=0,0D1117,0,1a1a2e,0,00FF66&stroke=00FF66&strokeWidth=2&animation=fadeIn&desc=Backend%20Engineer%20%E2%80%A2%20Systems%20Architect%20%E2%80%A2%20CEUB%20%E2%80%A2%20Brasília&descSize=18&descFontColor=8892b0&descAlignY=80" width="100%" />

</div>

<br>

<!-- MARIO (extrema direita, solto, grande) -->
<img src="./assets/3cf442eb0574a06127a2db3a6bd6e633.gif" width="140" align="right" title="Mario" style="margin-left: 20px;" />

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&weight=900&size=24&duration=1800&pause=600&color=00FF66&center=true&vCenter=true&width=680&height=56&lines=GABRIEL+SANTOS+%E2%80%94+BACKEND+ENGINEER;NEMESIS+ENGINE+v0.1-alpha+ONLINE;ANALISE+E+DESENVOLVIMENTO+DE+SISTEMAS+%40+CEUB;TCP%2FUDP+%C2%B7+ASYNC+I%2FO+%C2%B7+LOW+LATENCY;BACKPRESSURE+%C2%B7+BULK+INGESTION;NJ10+RUMO+A+COPA+2026" alt="Typing SVG" />

</div>

<br clear="both" /><br>

<div align="center">

🟢 → VER DASHBOARD INTERATIVO COM STATS EM TEMPO REAL ←

Gráficos ao vivo · Atividade · Repos · Streak — atualiza a cada 5 minutos



</div>

╔══════════════════════════════════════════════════════════════════════╗
║  root@nemesis:~$ whoami                                             ║
╠══════════════════════════════════════════════════════════════════════╣
║                                                                      ║
║  Gabriel Santos — Backend Engineer & ADS Student @ CEUB             ║
║  Brasília, DF  ·  ETEC Informática → CEUB Análise e Des. Sistemas  ║
║                                                                      ║
║  > Engenheiro orientado a sistemas distribuídos e dados             ║
║  > Backpressure · Sockets TCP/UDP · Bulk Ingestion                  ║
║  > Se roda, eu otimizo. Se travar, eu debugo.                       ║
║  > Torcedor do Ney desde quando ele driblava na areia. 🇧🇷           ║
║                                                                      ║
╚══════════════════════════════════════════════════════════════════════╝


<div align="center">
[ STACK ]

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
</p>
<p>
  <img src="https://img.shields.io/badge/TCP%2FUDP-Socket%20Engineering-00FF66?style=for-the-badge&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Async%20I%2FO-Backpressure%20Control-00FF66?style=for-the-badge&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Fault%20Tolerant-Ingestion%20Engine-00FF66?style=for-the-badge&labelColor=0D1117" />
</p>
</div>

[ SOBRE ] — Quem é Gabriel Santos

<img align="right" src="./assets/download.jpg" width="90" style="margin-left:16px; border-radius:8px;" />
Gabriel Santos é estudante de Análise e Desenvolvimento de Sistemas no CEUB com formação técnica em Redes de Computadores e Informática pela ETEC — uma combinação que poucos desenvolvedores em início de carreira possuem: domínio do software integrado à infraestrutura.

Graças ao seu background em redes, ele compreende profundamente a camada de transporte, o comportamento de buffers de sockets no SO e o impacto direto do tráfego de rede na performance da aplicação.

<br>
[ ENGENHARIA ] — Capacidade Técnica

<img align="left" src="./assets/pepe.gif" width="60" style="margin-right:16px;" />
Diferente de profissionais que dependem de frameworks de alto nível, Gabriel codifica soluções nativas e robustas. Isso ficou provado no desenvolvimento do Nemesis Engine: um motor de ingestão de dados de alta performance com sockets nativos, concorrência gerenciada e estruturas de dados otimizadas — como collections.deque para garantir operações O(1) e eliminar gargalos de forma cirúrgica.

<br><br>

[ ARQUITETURA ] — Resolução de Gargalos Críticos

ProblemaSolução implementadaSaturação de memória RAMHigh Watermark — gatilho que para a leitura do socket antes do OOMOverhead de I/O em discoBulk Flush — acúmulo em memória + escrita unificada em loteInstabilidade sob cargaBackpressure ativo — o produtor desacelera quando o buffer enchePerda de dados em falhaRetry orchestration com filas tolerantes a falha


[ NEMESIS ENGINE ] — O que estou construindo

python# nemesis_engine/core.py  ·  v0.1-alpha  ·  by Gabriel Santos

class NemesisEngine:
    """
    Motor de ingestão de dados de alta vazão.
    Fault-tolerant · Backpressure-aware · Low-latency
    ──────────────────────────────────────────────────
    collections.deque  →  O(1) enqueue/dequeue
    High Watermark     →  previne OOM proativamente
    Bulk Flush         →  I/O amortecido em lote
    """

    def __init__(self):
        self.author        = "Gabriel Santos — @GabrielSantMAc"
        self.status        = "🟢 ONLINE"
        self.stack         = ["Python", "PostgreSQL", "Docker", "Linux"]
        self.protocols     = ["TCP", "UDP", "WebSocket"]
        self.current_focus = "Memory-efficient buffering + retry orchestration"

    def run(self) -> str:
        return "⚡ NEMESIS ENGINE — sistemas em plena carga."


[ POSICIONAMENTO ] — Onde atuo no mercado

<img align="right" src="./assets/source.gif" width="90" style="margin-left:16px;" />
Gabriel não é só um programador de scripts — é um Engenheiro de Software Backend orientado a Sistemas Distribuídos e Arquitetura de Dados. Seu perfil atende diretamente às demandas de:


Platform Engineering — construção dos motores internos de plataforma
Infraestrutura de Software — pipelines de ingestão de alta vazão
Core Engine Teams — sistemas que sustentam aplicações de grande porte


<br>

<div align="center">
[ STATS ]

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=GabrielSantMAc&show_icons=true&theme=tokyonight&count_private=true&hide_border=true&bg_color=0D1117&title_color=00FF66&icon_color=00FF66&text_color=8892b0&ring_color=00FF66" width="47%" />
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=GabrielSantMAc&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00FF66&text_color=8892b0" width="37%" />
</p>
<p>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=GabrielSantMAc&theme=tokyonight&hide_border=true&background=0D1117&stroke=00FF66&ring=00FF66&fire=FF6B35&currStreakLabel=00FF66&sideLabels=8892b0&dates=8892b0" width="60%" />
</p>
<p>
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=GabrielSantMAc&bg_color=0D1117&color=00FF66&line=00FF66&point=FFFFFF&area=true&hide_border=true&area_color=00FF6622" width="90%" />
</p>

[ CONTATO ]

<p>
  <a href="https://github.com/GabrielSantMAc">
    <img src="https://img.shields.io/badge/GitHub-GabrielSantMAc-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/gabriel-santos-de-macedo-16b40135a/">
    <img src="https://img.shields.io/badge/LinkedIn-Gabriel%20Santos-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  &nbsp;
  <a href="mailto:gabriel.santosm@sempreceub.com">
    <img src="https://img.shields.io/badge/Email-gabriel.santosm%40sempreceub.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>
<br>
<img src="https://capsule-render.vercel.app/api?type=waving&color=0,0D1117,100,00FF66&height=130&section=footer&text=Gabriel+Santos+—+Keep+Building.+Never+Stop.&fontSize=18&fontColor=00FF66&animation=twinkling&fontAlignY=74" width="100%" />
</div>
