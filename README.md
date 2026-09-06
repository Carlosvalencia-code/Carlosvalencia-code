# Hi there, I'm Carlos Valencia 👋

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Carlos%20Valencia-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/carlos-valencia-a78520195/)
[![GitHub](https://img.shields.io/badge/GitHub-Carlosvalencia--code-181717?style=for-the-badge&logo=github)](https://github.com/Carlosvalencia-code)
[![Email](https://img.shields.io/badge/Contact-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:crvlinares@gmail.com)

**People & Operations Specialist | Building AI-Assisted Operational Software & Regulatory Workflows**  
*Based in Peru 🇵🇪 • Open to high-impact remote roles worldwide*

</div>

---

### 👨‍💻 About Me

I bring a unique combination of **7+ years in operations, human resources, and project management** with hands-on software engineering focused on **ambient AI, compliance-first architectures, and workflow automation**.

I don't build tech for the sake of tech; I build **pragmatic, production-ready digital products** that eliminate painful administrative bottlenecks in payroll, healthcare, operations, and pre-accounting.

- 🧠 **Focus:** AI Medical Scribes, Local-First LLMs (Ollama / Llama 3), Zero-Retention Architectures, Offline-First Kiosks, Payroll & Pre-Accounting Engines.
- 🛠️ **Core Technologies:** TypeScript, Node.js 24 (native types & SQLite), Python 3.11 (FastAPI, Pydantic v2, SQLModel), React, PostgreSQL (Supabase / RLS), Redis, Docker.
- 📜 **Regulatory Standards:** Peruvian Labor Law (D.L. 1086 MYPE / D.L. 728), SUNAT PDT-PLAME v4.5 flat-files, MTPE Payslips (D.S. 001-98-TR), MINSA Healthcare Standard (NTS N° 139-MINSA), Personal Data Protection (Ley 29733).

---

### 🌟 Featured Flagship Projects

<table>
  <tr>
    <td width="50%">
      <h3 align="center">🇵🇪 VAMOS Payroll Standard</h3>
      <p align="center">
        <a href="https://github.com/Carlosvalencia-code/vamos-payroll-standard"><b>View Repository →</b></a>
      </p>
      <p><b>Peruvian Open-Core Payroll Engine, SUNAT PLAME Compiler & Offline Kiosk</b></p>
      <ul>
        <li><b>Payroll Engine (<code>@payroll/engine</code>):</b> Pure computational rules for MYPE (D.L. 1086) and General (D.L. 728), overtime 25%/35%, night differential, AFP/ONP, Gratificaciones, and CTS.</li>
        <li><b>SUNAT Compiler (<code>@payroll/plame-compiler</code>):</b> Generates official PDT-PLAME v4.5 flat files (<code>.rem</code>, <code>.jor</code>, <code>.snl</code>) with strict CRLF formatting.</li>
        <li><b>Offline Attendance Core (<code>@payroll/attendance-core</code>):</b> Warehouse kiosk on native Node 24 SQLite with <b>SHA-256 tamper-evident hash chaining</b> and PIN brute-force lockout.</li>
        <li><b>Official Payslips (<code>@payroll/payslip-pdf</code>):</b> MTPE-compliant A4 boletas (D.S. 001-98-TR) with number-to-words currency and verification hash.</li>
        <li><i>Stack:</i> TypeScript, Node.js 24, SQLite, Docker • <b>26/26 passing unit tests</b>.</li>
      </ul>
    </td>
    <td width="50%">
      <h3 align="center">🩺 Dokst AI Scribe</h3>
      <p align="center">
        <a href="https://github.com/Carlosvalencia-code/dokst-ai-scribe"><b>View Repository →</b></a>
      </p>
      <p><b>Ambient AI Medical Scribe & Clinical Documentation Assistant</b></p>
      <ul>
        <li>Captures clinical consultations via live microphone or audio upload and structures them into standardized <b>SOAP clinical notes</b>.</li>
        <li>Generates formal PDF prescriptions compliant with Peruvian <b>Ley N° 29459</b> (DCI generic denomination) and patient-friendly WhatsApp summaries.</li>
        <li>Strict <b>Zero-Audio-Retention</b> and <b>Local-First</b> privacy architecture under <b>NTS N° 139-MINSA</b> and Ley 29733 (Personal Data Protection).</li>
        <li><i>Stack:</i> Python 3.11, FastAPI, Ollama (Llama 3), Whisper STT, ReportLab, SQLite, Docker.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3 align="center">📦 Valanze B2B</h3>
      <p align="center">
        <a href="https://github.com/Carlosvalencia-code/Valanzeb2b"><b>View Repository →</b></a>
      </p>
      <p><b>Conversational Kardex, Cash Control & Pre-Accounting for Retail & Food Service</b></p>
      <ul>
        <li>Open-source Telegram bot replacing traditional $80/mo POS systems with zero learning curve for bodegas, retail shops, and food service.</li>
        <li>Real-time discrete inventory with <b>Weighted Average Cost (Kardex)</b>, cash drawer shift close (<code>/caja</code>), and strict role separation (Owner vs Staff).</li>
        <li>Interactive voucher classification (Factura con RUC, Boleta) with automatic 18% IGV breakdown and structured CSV export for external accountants.</li>
        <li>Production-grade architecture with webhook idempotency (<code>update_id</code> deduplication), Supabase RLS, and immutable audit logs.</li>
        <li><i>Stack:</i> Node.js, Telegram Bot API, Supabase (PostgreSQL / RPC), Vercel Serverless.</li>
      </ul>
    </td>
    <td width="50%">
      <h3 align="center">👗 Synthia Style Platform</h3>
      <p align="center">
        <a href="https://github.com/Carlosvalencia-code/proyect1"><b>View Repository →</b></a>
      </p>
      <p><b>AI-Powered Chromatic Analysis & Wardrobe Architecture</b></p>
      <ul>
        <li>Fullstack platform combining facial/chromatic analysis with intelligent wardrobe management.</li>
        <li>Migrated from Flask to high-throughput <b>FastAPI v2.0</b> + PostgreSQL (Prisma ORM) + Redis caching layer.</li>
        <li>Sub-150ms response times for cached analyses, rate limiting, JWT authentication, and structured logging.</li>
        <li>Comprehensive CI/CD pipelines, Docker containerization, and automated test suites.</li>
        <li><i>Stack:</i> FastAPI, PostgreSQL, Redis, Docker, React, TypeScript.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3 align="center">🛡️ CareGuard Onboarding</h3>
      <p align="center">
        <a href="https://github.com/Carlosvalencia-code/careguard-onboarding-app"><b>View Repository →</b></a>
      </p>
      <p><b>Operational Onboarding & Identity Verification Engine</b></p>
      <ul>
        <li>Interactive dashboard streamlining frontline worker onboarding, document validation, and security compliance.</li>
        <li>Direct translation of human resources and operations pain points into an intuitive software flow.</li>
        <li><i>Stack:</i> React, TypeScript, Tailwind CSS, Responsive Design.</li>
      </ul>
    </td>
    <td width="50%">
      <h3 align="center">⚡ Operations & Workflow Automation</h3>
      <p align="center">
        <a href="https://github.com/Carlosvalencia-code?tab=repositories"><b>Explore Repositories →</b></a>
      </p>
      <p><b>Custom Process Architecture & Business Engineering</b></p>
      <ul>
        <li>Designed pragmatic automation pipelines for retail operations, clinic workflows, and accounting handoffs.</li>
        <li>Bridging non-technical operators with high-leverage cloud architectures (Serverless + PostgreSQL + Local-First).</li>
        <li><i>Stack:</i> TypeScript, Python, Node.js, Docker, Webhooks, REST APIs.</li>
      </ul>
    </td>
  </tr>
</table>

---

### 🧰 Tech Stack & Regulatory Domain

<div align="center">

| Area | Technologies & Frameworks |
| :--- | :--- |
| **Backend & AI** | TypeScript, Node.js 24 (native types & SQLite), Python 3.11, FastAPI, Pydantic v2, Ollama (Llama 3), Whisper STT, Telegram Bot API |
| **Frontend** | React, TypeScript, Tailwind CSS, Vite, HTML5 / Web Audio API |
| **Data & Cloud** | PostgreSQL (Supabase / RLS), SQLite (`node:sqlite`), Redis, Vercel Serverless, Docker Compose |
| **Regulatory & Compliance** | SUNAT PDT-PLAME v4.5 (.rem, .jor, .snl), MTPE D.S. 001-98-TR (Boletas), D.L. 1086 (MYPE), NTS N° 139-MINSA, Ley 29733 (Datos Personales) |
| **Operations & Management** | People Operations, Process Mapping, Pre-Accounting & Kardex, Agile Delivery |

</div>

---

### 📈 GitHub Highlights

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Carlosvalencia-code&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Carlosvalencia-code&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</div>

---

<div align="center">
  <sub>Designed & engineered with precision by Carlos Valencia • 2026</sub>
</div>
