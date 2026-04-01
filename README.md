# 🧠 Knowledge Base — Ciberseguridad + IA/NLP
> Roadmap, recursos y plantillas Emacs/Org-mode para estudiante junior con objetivo docencia UNAM.
> Actualizado: 2026-03 | Nivel: Junior → Avanzado

---

## 📁 Estructura del repositorio

```
knowledge-base/
├── README.md                        ← este archivo (condensado principal)
├── COMO-USAR-CON-EMACS.md          ← git + Magit + flujo de trabajo
├── emacs/
│   ├── INSTRUCCIONES-CONFIG.md     ← qué agregar a tu config.el (paso a paso)
│   ├── config-snippets.el          ← fragmentos listos para copiar a config.el
│   └── plantillas/
│       ├── plantilla-paper.org     ← para leer papers académicos
│       └── plantilla-academia.org  ← referencia (ya tienes una en notas/)
└── roadmap/                        ← (expandir conforme avances)

# Tus notas reales viven en:
~/Documents/Clases/notas/
├── inbox.org               ← destino de SPC X (todas las capturas)
├── retos-ctf.org           ← destino de SPC X r
├── plantilla-academia.org
├── plantilla-uni.org
├── plantilla-curso.org
└── plantilla-paper.org
```

---

## 🗺️ Roadmap: Visión General

```
FASE 1 (Meses 1–6)     FASE 2 (Meses 7–12)    FASE 3 (Año 2+)
Fundamentos sólidos  → Integración + proyectos → Especialización avanzada
Ciber 60% / IA 30%     Ciber + IA combinados     OSCP + LLMs + docencia
```

### Objetivo final: Perfil T-shaped
- **Barra vertical**: Ciberseguridad profunda
- **Barra horizontal**: IA/NLP + Cómputo paralelo + Docencia
- **Ventaja competitiva**: Detección de amenazas con ML, análisis forense con NLP

---

## 🔐 Blogs Ciberseguridad — Inglés (Tier 1–3)

### Tier 1: Investigación y vulnerabilidades
| Blog | URL | Por qué leerlo |
|------|-----|----------------|
| Google Project Zero | https://googleprojectzero.blogspot.com | 0-days y exploits reales |
| Krebs on Security | https://krebsonsecurity.com | Cibercrimen investigativo |
| Trail of Bits | https://blog.trailofbits.com | Auditorías + tools OSS |
| PortSwigger Research | https://portswigger.net/research | Web security avanzado |
| NCC Group Research | https://research.nccgroup.com | Whitepapers técnicos |

### Tier 2: Threat Intelligence
| Blog | URL | Por qué leerlo |
|------|-----|----------------|
| Mandiant (Google) | https://www.mandiant.com/resources/blog | APT groups + IR |
| CrowdStrike | https://www.crowdstrike.com/blog | Threat hunting |
| SANS ISC | https://isc.sans.edu | Alertas diarias |
| Bleeping Computer | https://www.bleepingcomputer.com | Noticias rápidas |
| Recorded Future | https://www.recordedfuture.com/blog | Geopolítica + ciber |

### Tier 3: Técnico/Ofensivo
| Blog | URL | Por qué leerlo |
|------|-----|----------------|
| LiveOverflow | https://liveoverflow.com | Binary exploitation |
| Orange Tsai | https://blog.orange.tw | Web hacking avanzado |
| 0x00sec | https://0x00sec.org | Malware + exploits |
| Gynvael Coldwind | https://gynvael.coldwind.pl | CTF + RE |
| Daniel Miessler | https://danielmiessler.com | Filosofía de seguridad |

### Tier 4: IA + Ciberseguridad
| Blog | URL | Por qué leerlo |
|------|-----|----------------|
| Adversa AI | https://adversa.ai/blog | Adversarial ML |
| Robust Intelligence | https://www.robustintelligence.com/blog | AI security testing |
| MLSecOps | https://mlsecops.com | ML en producción seguro |

---

## 🔐 Blogs Ciberseguridad — Español

| Blog | URL | Nivel |
|------|-----|-------|
| INCIBE Blog | https://www.incibe.es/incibe/blog | Básico–Intermedio |
| Security Art Work (S2) | https://www.securityartwork.es | Intermedio–Avanzado |
| WeLiveSecurity (ESET) | https://www.welivesecurity.com/es | Básico–Intermedio |
| Segu-Info | https://blog.segu-info.com.ar | Intermedio |
| CyberSecurity News ES | https://cybersecuritynews.es | Noticias |
| Tanya Janca | https://shehackspurple.ca | AppSec / DevSecOps |

---

## 🤖 Blogs IA / NLP — Los que leen investigadores

### Laboratorios top
| Blog | URL |
|------|-----|
| DeepMind Blog | https://deepmind.google/discover/blog/ |
| OpenAI Blog | https://openai.com/news/ |
| Anthropic Blog | https://www.anthropic.com/news |
| Google AI Blog | https://ai.googleblog.com/ |
| Meta AI Research | https://ai.meta.com/blog/ |
| Berkeley AI (BAIR) | https://bair.berkeley.edu/blog/ |
| Stanford AI Lab | https://ai.stanford.edu/blog/ |
| AI2 (Allen Institute) | https://allenai.org/blog |

### NLP y LLMs específicamente
| Blog | URL | Especial |
|------|-----|---------|
| Hugging Face Blog | https://huggingface.co/blog | Práctico, modelos nuevos |
| Lil'Log (Lilian Weng) | https://lilianweng.github.io | Investigadora OpenAI, muy técnico |
| Sebastian Ruder | https://ruder.io | NLP Newsletter mensual |
| Jay Alammar | https://jalammar.github.io | Visualizaciones de transformers |
| The Gradient | https://thegradient.pub | Análisis profundo |

### Agregadores / análisis
| Blog | URL |
|------|-----|
| Papers with Code | https://paperswithcode.com |
| Ahead of AI | https://magazine.sebastianraschka.com |
| The Batch (Andrew Ng) | https://www.deeplearning.ai/the-batch/ |
| Distill.pub | https://distill.pub |

---

## 📰 Newsletters recomendadas

| Newsletter | URL | Frecuencia | Para qué |
|------------|-----|-----------|---------|
| TLDR AI | https://tldr.tech/ai | Diario | Resumen IA rápido |
| TLDR Sec | https://tldrsec.com | Semanal | Resumen ciber |
| Import AI (Jack Clark) | https://jack-clark.net | Semanal | Análisis + seguridad IA |
| The Algorithm (MIT TR) | https://technologyreview.com/newsletters | Semanal | Tendencias profundas |
| Hacker News digest | https://hackernewsletter.com | Semanal | Tech general |
| AI Security (Adversa) | https://adversa.ai | Quincenal | IA + ciber |

---

## 🎥 Canales YouTube esenciales

### Ciberseguridad
| Canal | URL | Nivel | Especial |
|-------|-----|-------|---------|
| S4vitar | https://www.youtube.com/@s4vitar | Básico–Avanzado | En español, HTB walkthroughs |
| IppSec | https://www.youtube.com/@ippsec | Intermedio–Avanzado | HackTheBox retiros |
| John Hammond | https://www.youtube.com/@_JohnHammond | Básico–Avanzado | CTF + malware |
| LiveOverflow | https://www.youtube.com/@LiveOverflow | Avanzado | Binary exploitation |
| David Bombal | https://www.youtube.com/@davidbombal | Básico | Networking + hacking |

### IA / NLP
| Canal | URL | Nivel | Especial |
|-------|-----|-------|---------|
| Yannic Kilcher | https://www.youtube.com/@YannicKilcher | Avanzado | Papers explicados en profundidad |
| Andrej Karpathy | https://www.youtube.com/@AndrejKarpathy | Intermedio–Avanzado | GPT desde cero, implementación |
| Hugging Face | https://www.youtube.com/@HuggingFace | Intermedio | Transformers, fine-tuning, RAG |
| Two Minute Papers | https://www.youtube.com/@TwoMinutePapers | Básico | Resúmenes visuales de papers |
| StatQuest | https://www.youtube.com/@statquest | Básico–Intermedio | ML explicado paso a paso |
| Stanford CS224N | https://www.youtube.com/playlist?list=PLoROMvodv4rOSH4v6133s9LFPRHjEmbmJ | Avanzado | Curso completo NLP deep learning |

---

## 📄 Revistas académicas (para publicar y leer a nivel doctoral)

| Revista | Publisher | Área | Acceso |
|---------|-----------|------|--------|
| Neural Networks | Elsevier | IA + redes neuronales | Pago (Sci-Hub) |
| Neurocomputing | Elsevier | Computación neuronal | Pago |
| IEEE Trans. Neural Networks | IEEE | IA aplicada Q1 | Pago |
| Nature Machine Intelligence | Nature | IA top-tier | Pago |
| Journal of Machine Learning Research | JMLR | ML teórico | Open Access |
| Neuromorphic Computing & Eng. | IOP | Hardware neuromórfico | https://iopscience.iop.org/journal/2634-4386 |
| Frontiers in Neuroscience | Frontiers | Neuro-ingeniería | Open Access |
| Neural Computing & Applications | Springer | Aplicaciones | Pago |

### Conferencias tier-1 (donde debes apuntar a publicar)
- **NeurIPS** — https://neurips.cc
- **ICML** — https://icml.cc
- **ICLR** — https://iclr.cc
- **USENIX Security** — https://www.usenix.org/conference/usenixsecurity
- **IEEE S&P** — https://ieee-security.org

---

## 📡 arXiv: Categorías esenciales por área

> arXiv es donde los investigadores publican antes de la revisión formal.
> Suscríbete a las categorías que te interesan en https://arxiv.org/

### 🤖 IA / NLP / ML
| Categoría | URL | Qué contiene |
|-----------|-----|-------------|
| cs.AI | https://arxiv.org/list/cs.AI/recent | Inteligencia artificial general |
| cs.LG | https://arxiv.org/list/cs.LG/recent | Machine learning (la más activa) |
| cs.CL | https://arxiv.org/list/cs.CL/recent | NLP y procesamiento de lenguaje |
| cs.CV | https://arxiv.org/list/cs.CV/recent | Visión por computadora |
| cs.NE | https://arxiv.org/list/cs.NE/recent | Redes neuronales y cómputo evolutivo |
| stat.ML | https://arxiv.org/list/stat.ML/recent | ML desde perspectiva estadística |

### 🔐 Ciberseguridad
| Categoría | URL | Qué contiene |
|-----------|-----|-------------|
| cs.CR | https://arxiv.org/list/cs.CR/recent | **Cryptography and Security** — la principal |
| cs.NI | https://arxiv.org/list/cs.NI/recent | Redes (ataques de red, protocolos) |
| cs.OS | https://arxiv.org/list/cs.OS/recent | Sistemas operativos (ataques a kernel) |
| cs.SE | https://arxiv.org/list/cs.SE/recent | Software engineering (fuzzing, análisis estático) |

### 🔑 Criptografía (especializada)
| Repositorio | URL | Qué contiene |
|------------|-----|-------------|
| IACR ePrint | https://eprint.iacr.org | **El arXiv de criptografía** — papers de cripto antes de publicarse |
| IACR recientes | https://eprint.iacr.org/eprint-bin/search.pl?last=100 | Últimos 100 papers de cripto |

> **IACR ePrint** es donde salen papers de criptografía clásica y post-cuántica antes de aparecer en conferencias como Crypto, Eurocrypt, Asiacrypt o CCS.

### ⚡ Cómputo paralelo / sistemas
| Categoría | URL | Qué contiene |
|-----------|-----|-------------|
| cs.DC | https://arxiv.org/list/cs.DC/recent | Computación distribuida y paralela |
| cs.AR | https://arxiv.org/list/cs.AR/recent | Arquitectura de computadoras (GPUs, FPGAs) |
| cs.PF | https://arxiv.org/list/cs.PF/recent | Performance de sistemas |

### 🔗 IA aplicada a Seguridad (intersección)
Busca en arXiv con estos términos:
- `adversarial machine learning` → ataques a modelos de ML
- `LLM security` → vulnerabilidades en LLMs
- `intrusion detection deep learning` → IDS con ML
- `malware classification neural network` → clasificación de malware
- `fuzzing neural` → fuzzing inteligente con IA
- `post-quantum cryptography` → cripto resistente a computadoras cuánticas

---

## 📄 Papers fundamentales — por área

### NLP (leer en este orden)

1. **Attention Is All You Need** (2017) — Base de todos los transformers → https://arxiv.org/abs/1706.03762
2. **BERT** (2018) — Transfer learning en NLP → https://arxiv.org/abs/1810.04805
3. **GPT-3** (2020) — Scaling + few-shot learning → https://arxiv.org/abs/2005.14165
4. **RAG** (2020) — Retrieval Augmented Generation → https://arxiv.org/abs/2005.11401
5. **Chain-of-Thought** (2022) — Razonamiento en LLMs → https://arxiv.org/abs/2201.11903
6. **Constitutional AI** (Anthropic, 2022) — RLHF y alineación → https://arxiv.org/abs/2212.08073
7. **LLaMA 2** (Meta, 2023) — LLMs open source → https://arxiv.org/abs/2307.09288
8. **Mixtral of Experts** (2023) — Arquitecturas MoE → https://arxiv.org/abs/2401.04088

### 🔐 Ciberseguridad / Criptografía (papers que todo profesional debe conocer)

1. **SoK: Eternal War in Memory** (2013, IEEE S&P) — Fundamentos de explotación de memoria → https://ieeexplore.ieee.org/document/6547101
2. **OWASP Top 10** — No es un paper pero es la referencia de vulnerabilidades web → https://owasp.org/Top10/
3. **Smashing the Stack for Fun and Profit** (Aleph One, 1996) — Clásico de buffer overflows → http://phrack.org/issues/49/14.html
4. **ZMap: Fast Internet-Wide Scanning** (2013, USENIX) — Escaneo masivo de internet → https://www.usenix.org/system/files/conference/usenixsecurity13/sec13-paper_durumeric.pdf
5. **Sok: Security and Privacy in Machine Learning** (2019, IEEE S&P) — Seguridad en ML → https://arxiv.org/abs/1811.01134
6. **Attacking Machine Learning with Adversarial Examples** (Goodfellow, 2014) → https://arxiv.org/abs/1412.6572
7. **BERT-Attack: Adversarial Attack Against BERT** (2020) — Ataques a LLMs → https://arxiv.org/abs/2004.09984
8. **Towards Evaluating the Robustness of Neural Networks** (Carlini & Wagner, 2017) → https://arxiv.org/abs/1608.04644

### 🔑 Criptografía esencial (IACR papers)

1. **New Directions in Cryptography** (Diffie & Hellman, 1976) — Inventó la criptografía de clave pública
2. **CRYSTALS-Kyber** (2017) — Criptografía post-cuántica, ya estándar NIST → https://eprint.iacr.org/2017/634
3. **CRYSTALS-Dilithium** (2017) — Firmas digitales post-cuánticas → https://eprint.iacr.org/2017/633
4. **How to Share a Secret** (Shamir, 1979) — Esquemas de umbral
5. **The TLS 1.3 Protocol** (RFC 8446) — El protocolo TLS moderno → https://www.rfc-editor.org/rfc/rfc8446

### 🔗 IA aplicada a Seguridad (papers integradores — tu ventaja competitiva)

1. **Deep Neural Network Based Malware Detection** (2017) → https://arxiv.org/abs/1710.10563
2. **Intrusion Detection with Neural Networks** — buscar en cs.CR + cs.LG
3. **LLM Security: Prompt Injection** (2023) → https://arxiv.org/abs/2302.12173
4. **Jailbreaking Black Box Large Language Models** (2023) → https://arxiv.org/abs/2307.02483
5. **Generative AI for Cybersecurity** (2024) — survey completo → buscar en arXiv cs.CR

---

## ⏰ Gestión de tiempo: balance profesional

```
DURANTE PRÁCTICAS (semana laboral)
───────────────────────────────────
08:00–17:00  Prácticas profesionales
19:00–21:00  Estudio enfocado (2h — alterna ciber/IA)
21:00–22:00  Lectura ligera (blogs/newsletters)

SÁBADO
───────
09:00–13:00  Proyecto personal integrador (4h)
14:00–16:00  Curso online o paper profundo
16:00–18:00  CTF / HackTheBox / Kaggle

DOMINGO
────────
10:00–12:00  Repaso semanal + Notion/Emacs sync
12:00–14:00  Papers o videos técnicos
Tarde        Descanso (obligatorio)
```

### Distribución por fase
| Fase | Ciber | IA/NLP | Cómputo paralelo |
|------|-------|--------|-----------------|
| Meses 1–6 | 60% | 30% | 10% |
| Meses 7–12 | 50% | 40% | 10% |
| Año 2+ | 40% | 40% | 20% |

---

## 🔧 Emacs: Atajos de referencia rápida

### Captura de notas (SPC X)
| Atajo | Acción |
|-------|--------|
| `SPC X` | Abrir menú de captura |
| `SPC X c` | Captura clase academia → pide Tema + Mentor |
| `SPC X u` | Captura materia universidad → pide Materia + Tema |
| `SPC X k` | Captura curso online → pide Plataforma + Tema |
| `SPC X d` | Captura duda rápida → pide Concepto + Contexto |
| `SPC X r` | Captura reto CTF → pide Nombre + Categoría + Dificultad |
| `SPC X p` | Captura paper → pide Título + Venue + Año + URL + Área |
| `C-c C-c` | Confirmar y guardar captura |
| `C-c C-k` | Cancelar captura sin guardar |

### Archivos y buffers
| Atajo | Acción |
|-------|--------|
| `SPC f f` | Abrir archivo (find file) |
| `SPC f r` | Archivos recientes |
| `SPC f c` | Copiar archivo actual con nuevo nombre |
| `SPC f s` | Guardar archivo |
| `SPC f P` | Abrir config.el directamente |
| `SPC b b` | Cambiar entre buffers abiertos |
| `SPC b d` | Cerrar buffer actual |

### Org-mode: navegación y edición
| Atajo | Acción |
|-------|--------|
| `TAB` | Colapsar/expandir sección bajo el cursor |
| `S-TAB` | Colapsar/expandir TODO el documento |
| `SPC m h` | Insertar heading del nivel correcto |
| `SPC m t` | Toggle TODO/DONE en tarea actual |
| `SPC m s` | Insertar snippet (plantilla de bloque) |
| `SPC m d s` | Insertar fecha con calendario |
| `C-c C-c` | Ejecutar bloque de código (babel) |
| `C-c C-t` | Cambiar estado TODO del heading |
| `C-c C-s` | Programar tarea con SCHEDULED |
| `C-c C-d` | Poner DEADLINE a una tarea |
| `M-RET` | Insertar nuevo item/heading al mismo nivel |
| `M-↑ / M-↓` | Mover heading arriba o abajo |
| `M-→ / M-←` | Promover/degradar nivel de heading |
| `SPC n a` | Abrir agenda (tareas y fechas) |

### Exportación
| Atajo | Acción |
|-------|--------|
| `C-c C-e l O` | Exportar a PDF Beamer y abrir en Zathura |
| `C-c C-e l P` | Exportar a PDF Beamer sin abrir |
| `C-c C-e l p` | Exportar a PDF artículo normal |
| `C-c C-e m m` | Exportar a Markdown (para NotebookLM) |
| `C-c C-e h h` | Exportar a HTML |

### Temas y configuración
| Atajo | Acción |
|-------|--------|
| `SPC T g` | Tema Gruvbox (código general) |
| `SPC T t` | Tema Tokyo Night (CTF/hacking) |
| `SPC T c` | Tema Catppuccin (notas largas) |
| `SPC T o` | Tema Doom One (neutro) |
| `SPC h r r` | Recargar config sin cerrar Emacs |
| `SPC o k` | Abrir knowledge base (README) |
| `F5` | Exportar PDF Beamer (en org-mode) |

### Splits y workspaces
| Atajo | Acción |
|-------|--------|
| `SPC w v` | Split vertical (dos columnas) |
| `SPC w s` | Split horizontal (dos filas) |
| `SPC w h/j/k/l` | Moverse entre splits |
| `SPC w d` | Cerrar split actual |
| `SPC TAB n` | Crear workspace nuevo |
| `SPC TAB 1-9` | Cambiar al workspace número N |

> **Sugerencia de workspaces**: 1=academia, 2=uni, 3=cursos, 4=código, 5=papers

---

## 📋 Plantilla: Lectura de Papers (nueva)

Archivo: `emacs/plantillas/plantilla-paper.org`

```org
#+TITLE: [Paper] - Título completo
#+DATE: %T
#+AUTHORS: 
#+VENUE: arXiv / NeurIPS / USENIX / IEEE S&P
#+YEAR: 
#+FILETAGS: :paper:nlp:  (cambia según área: :ciber: :ml: :cómputo:)
#+STARTUP: overview

* Resumen en una oración
  ¿Qué problema resuelve y cómo?

* Contexto
  ¿Por qué importa este paper?
  ¿Qué trabajos previos supera o complementa?

* Contribuciones principales
  1.
  2.
  3.

* Método / Arquitectura
  (diagrama mental o descripción del approach)

* Resultados clave
  | Métrica | Valor | Baseline |
  |---------+-------+----------|
  |         |       |          |

* Limitaciones
  - 

* Conexión con mi trabajo
  ¿Cómo aplica esto a ciberseguridad / NLP / mis proyectos?

* Términos que no entendí
  | Término | Definición | Fuente |
  |---------+------------+--------|
  |         |            |        |

* Para NotebookLM
  Conceptos clave: X, Y, Z
  Pregunta principal: ¿...?

* Recursos relacionados
  - Código: [[https://][paperswithcode link]]
  - Paper: [[https://arxiv.org/abs/][arXiv]]

* Siguiente acción
  - [ ] SCHEDULED: <%%(org-date-from-calendar)>
```
---

## 🎯 Flujo de trabajo diario en Emacs

```
ANTES DE CLASE/ESTUDIO
   SPC X c  →  llenar Tema y Mentor  →  queda cursor en %?  →  listo

DURANTE
   i (insert mode)  →  escribir sin filtro
   TAB              →  colapsar secciones
   SPC X d          →  capturar duda sin salir

DESPUÉS
   SPC f f          →  abrir nota en inbox.org
   C-c C-e m m      →  exportar Markdown → subir a NotebookLM
   C-c C-e l O      →  exportar PDF si es presentación
   SPC n a          →  revisar agenda y tareas

PARA PAPERS (nueva rutina)
   SPC f f  →  abrir plantilla-paper.org
   SPC f c  →  guardar como: 2026-YYYY-apellido-titulo-corto.org
   Llenar secciones mientras lees
   SPC n r f (org-roam)  →  buscar conexiones con notas anteriores
```

---

## 📌 RSS Reader: estructura Feedly/Inoreader

```
📁 CYBERSECURITY
├── 📰 Daily News     → Bleeping Computer, The Hacker News
├── 🔬 Research       → Project Zero, Trail of Bits, PortSwigger
├── 🎯 Threat Intel   → Mandiant, CrowdStrike, SANS ISC
├── 🛠️ Ofensivo       → 0x00sec, LiveOverflow, Orange Tsai
└── 🇲🇽 Español        → INCIBE, Security Art Work, WeLiveSecurity

📁 AI & NLP
├── 📄 Papers         → arXiv cs.CL, cs.AI, cs.CR
├── 🧪 Labs           → OpenAI, DeepMind, Anthropic, Meta AI
├── 🤗 Práctico       → Hugging Face, Papers with Code
└── 🔐 AI Security    → Adversa AI, Robust Intelligence

📁 TECH GENERAL
├── 💼 Industry       → MIT Tech Review, The Verge
├── 🐍 Python         → Real Python, Talk Python
└── ☁️ Cloud          → AWS Blog, Azure Updates
```

**Rutina diaria (30 min):**
- Mañana (10 min): scan de Daily News, marcar artículos
- Tarde (15 min): leer 1–2 artículos técnicos, notas en Emacs
- Noche (5 min): revisar papers de la semana, agregar a lista

---

## 🏫 Objetivo docencia UNAM

Materias meta: Sistemas Operativos / Bases de Datos / Ciberseguridad

### Habilidades académicas a desarrollar en paralelo
- Leer y citar papers correctamente (formato IEEE/APA)
- Redactar en LaTeX (org-mode exporta a .tex directamente)
- Presentar con Beamer (ya tienes las plantillas)
- Mantener un portafolio de proyectos documentados en GitHub

### Certificaciones estratégicas por fase
| Fase | Certificación | Para qué |
|------|--------------|---------|
| Meses 1–6 | CompTIA Security+ | Empleabilidad inmediata |
| Meses 7–12 | CEH o AWS Security | Diferenciación |
| Año 2 | OSCP | Reconocimiento máximo en ciber |
| Paralelo | TensorFlow Developer | Credencial IA |

---

*Repositorio personal — uso académico y profesional.*
*Actualiza este README cada mes al hacer tu revisión semanal del domingo.*
