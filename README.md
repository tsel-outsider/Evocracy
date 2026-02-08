# Evocracy

<p align="center">
  <img src="assets/symbol/evocracy-symbol.svg" width="150" alt="Evocracy symbol">
</p>

Evocracy is a formal governance architecture based on immutable axioms, cryptographic anchoring, and strict separation between canonical foundations and evolutionary layers.

Эвократия — это формальная архитектура власти, основанная на неизменяемых аксиомах, криптографической фиксации и строгом разделении канона и эволюции.

---

## 📌 Repository Status

**Current status:** PRE-GENESIS  
This repository is a working space. Canonical status applies only after Genesis anchoring.

**Текущий статус:** PRE-GENESIS  
Этот репозиторий является рабочей средой. Канонический статус возникает только после Genesis-якорения.

GitHub is not the source of truth.  
See: [`STATUS.md`](STATUS.md), [`MANIFEST.md`](MANIFEST.md), [`LANGUAGES.md`](LANGUAGES.md)

---

## 🧱 Architecture Overview / Архитектура

Evocracy is built as a layered system:

### 1) Core (Axioms) — Immutable / Ядро (аксиомы) — неизменно
- Fundamental axioms of the system / фундаментальные аксиомы системы  
- Published **once** / публикуется **один раз**  
- Anchored in Arweave / якорится в Arweave  
- Cryptographically signed / подписывается криптографически  
- Never modified / не изменяется никогда  

> The Core does not evolve. / Ядро не эволюционирует.

### 2) Outer Core — Evolvable / Внешнее ядро — эволюционирует
- Procedures / процедуры  
- Parameters / параметры  
- Constraints / ограничения  
- Pilot mechanisms / механизмы пилота  
- Validation logic / логика проверки  

The Outer Core may evolve without violating the Core axioms.  
Внешнее ядро может развиваться, не нарушая аксиомы Ядра.

### 3) Glossary — Canonical (RU) / Глоссарий — каноничный (RU)
- Canonical terminology / каноничная терминология  
- Semantic precision / семантическая точность  
- Prevents interpretational drift / предотвращает дрейф интерпретаций  

Before Genesis the glossary may evolve; after Genesis it is fixed for the given Core.  
До Genesis глоссарий может изменяться; после Genesis — фиксируется для данного Ядра.

### 4) Templates / Utilities (future) / Шаблоны и утилиты (в будущем)
- Reference implementations / эталонные реализации  
- Examples / примеры  
- Pilot artifacts / артефакты пилота  
- Validation helpers / вспомогательные инструменты проверки  

---

## 🧬 Genesis

Genesis is a one-time event when the Core becomes canonical.

Genesis consists of:
- Final Core publication
- Cryptographic signature
- Hash publication
- Arweave anchoring (TxID)

After Genesis:
- The Core becomes immutable
- Any modification constitutes a fork
- Evolution continues only via Outer Core and non-canonical layers

---

## 🌐 Languages / Языки

Canonical meaning is bound to **Russian (RU)** texts stored under: `canon/ru/`.

Translations (EN/JA/ZH/…) are for accessibility and are not canonical sources of meaning.  
See: [`LANGUAGES.md`](LANGUAGES.md)

---

## 🔐 Canonical Source of Truth

After Genesis, the only canonical reference will be:
- Arweave-anchored canonical artifacts
- Verified by published hashes and signatures

GitHub serves as:
- a development space
- a mirror
- a discussion surface

Public verification keys are published under: `keys/`

---

## 🌱 Repository Structure

```text
/
├── README.md                 # EN landing (this file)
├── STATUS.md                 # PRE-GENESIS status and rules
├── LANGUAGES.md              # canonical language + translation rules
├── MANIFEST.md               # pre-genesis scope and boundaries
│
├── canon/
│   ├── README.md             # what "canon" means in this project
│   └── ru/
│       ├── README.md         # canonical RU layer
│       ├── core/             # canonical Core (anchored at Genesis)
│       ├── outer-core/       # evolvable layer (RU reference)
│       ├── templates/        # (optional/future) RU reference templates
│       └── pilot/            # (optional/future) minimal pilot example
│
├── translations/             # official translations (non-canonical)
│   ├── en/
│   ├── ja/
│   └── zh/
│
├── keys/                     # public keys for verification
│   └── README.md
│
└── community/                # proposals, forks guidance, non-canonical work
    ├── forks/
    ├── proposals/
    └── glossary/
```

Draft texts will live in a dedicated `draft` branch.  
Черновики будут жить в отдельной ветке `draft`.

---

## 🌐 Fork Semantics

- Forks **before Genesis** are normal development.
- Forks **after Genesis** represent new systems.
- There is no “partial fork” of the Core.

---

## 🧭 Intent / Замысел

Evocracy is not:
- a political movement
- a party
- a protest manifesto

Evocracy is:
- a formal system
- a verifiable architecture
- a constraint-based governance model

Note: an explanatory manifesto is available under `/manifesto/`. It does not define canon. 
Примечание: объяснительный “манифест” находится в каталоге `/manifesto/` и не определяет канон.

---

## 🕊️ Authorship

The system may be maintained by one or many contributors.  
Authority derives from axioms and verification, not from identity.

---

## 📎 Notes

- No timelines are promised.
- No adoption is assumed.
- The system stands or falls on its internal coherence.
