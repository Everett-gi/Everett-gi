<h1 align="center">Gildean Monteiro</h1>

<p align="center">
  <b>Desenvolvedor Full Stack · Java, Spring Boot, Cloud e Segurança</b><br>
  Petrópolis, RJ · Aberto a estágio e vagas júnior (presencial, híbrido ou remoto)
</p>

<p align="center">
  <a href="https://portfolio-ten-livid-56.vercel.app/"><img src="https://img.shields.io/badge/Portfólio-0a0807?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfólio"></a>
  <a href="https://www.linkedin.com/in/gm-nascimento"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:gmonteiro0808@gmail.com"><img src="https://img.shields.io/badge/E--mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail"></a>
  <a href="https://portfolio-ten-livid-56.vercel.app/curriculo/Gildean_Monteiro_Curriculo.pdf"><img src="https://img.shields.io/badge/Currículo_PDF-2E7D32?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Currículo"></a>
</p>

---

## Sobre mim

Construo, **protejo** e mantenho sistemas reais no ar. Sou estudante de Tecnologia da Informação e Comunicação na **FAETERJ Petrópolis** (último período) e idealizei, desenvolvi e opero o **Hub Atlética Dragões**, plataforma em produção usada pelos alunos do curso. Faço o ciclo completo: modelagem do banco, back-end, interface, servidor, CI/CD e deploy.

- 🔐 **Segurança como diferencial:** certificação em Ethical Hacking (HackerX) e formação em Cibersegurança pelo **Hackers do Bem (MCTI/RNP)**
- 🧪 **Qualidade antes do deploy:** testes automatizados, migrações ensaiadas em cópia do banco e rollback por versão
- 🗣️ **Comunicação e liderança:** ex-subgerente de operação com 700+ clientes/dia, Conselheiro Acadêmico e Presidente da Atlética Dragões
- 🌎 **Inglês C2** (EF SET 82/100)

---

## ⭐ Projeto em destaque: Hub Atlética Dragões

> Plataforma dos alunos de TIC da FAETERJ: notas e simulador de aprovação, cronograma, conteúdos de estudo, carteirinha digital com QR verificável, reserva de salas, campeonatos de e-sports e assistente com IA.

<table>
  <tr>
    <td align="center"><b>80+</b><br>contas ativas</td>
    <td align="center"><b>1.275</b><br>testes automatizados</td>
    <td align="center"><b>~290</b><br>endpoints REST</td>
    <td align="center"><b>46</b><br>migrações Flyway</td>
    <td align="center"><b>R$ 170 → R$ 0</b><br>custo mensal após migrar AWS → Oracle Cloud</td>
  </tr>
</table>

```mermaid
flowchart LR
    U[PWA<br>HTML, CSS, JS] -->|HTTPS| C[Caddy<br>TLS automático]
    C --> A[API Spring Boot 3.5<br>Java 21]
    A --> DB[(PostgreSQL<br>Flyway)]
    A --> EXT[Google OAuth2 · Groq LLM<br>Cloudflare R2 · SMTP · Web Push]
    GH[GitHub Actions] -->|imagem| R[GHCR] -->|deploy| C
```

**Segurança aplicada:** JWT + BCrypt, OAuth2, rotas protegidas por padrão, rate limiting, CSP/HSTS, defesa contra XSS e SQL injection, exportação e exclusão de dados do titular (LGPD).

🔗 **No ar:** [atleticadragoes.com.br](https://atleticadragoes.com.br) (modo visitante, sem login)
🔒 O código é privado porque o sistema guarda dados de alunos reais. Apresento arquitetura e código em entrevista técnica.

---

## 🧩 Outros projetos

| Projeto | O que é | Stack |
|---|---|---|
| **OmniRate** | Plataforma de avaliações de cultura pop (filmes, séries, jogos, livros, álbuns e HQs) com autenticação JWT e aceite de termos conforme a LGPD; publicada na Oracle Cloud | Java 21 · Spring Boot · React 18 · PostgreSQL · Docker · Caddy |
| **DocSage** *(em desenvolvimento)* | Aplicação RAG para perguntar sobre documentos, com busca semântica por embeddings | Python · FastAPI · pgvector · API da Anthropic |
| [**Portfólio**](https://github.com/Everett-gi/portfolio) | Site bilíngue sem dependências nem build, com cabeçalhos de segurança (CSP, HSTS, X-Frame-Options) | HTML · CSS · JavaScript · Vercel |

---

## 🛠️ Stack

**Back-end**
<br>
<img src="https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white">
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white">
<img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white">
<img src="https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white">
<img src="https://img.shields.io/badge/JUnit_5-25A162?style=flat-square&logo=junit5&logoColor=white">
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white">

**Front-end**
<br>
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB">
<img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black">
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white">
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/PWA-5A0FC8?style=flat-square&logo=pwa&logoColor=white">

**Dados**
<br>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">
<img src="https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white">
<img src="https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white">

**Cloud & DevOps**
<br>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white">
<img src="https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat-square&logo=oracle&logoColor=white">
<img src="https://img.shields.io/badge/AWS_EC2-232F3E?style=flat-square">
<img src="https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white">
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black">
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">

**Segurança & IA**
<br>
<img src="https://img.shields.io/badge/OWASP_Top_10-000000?style=flat-square&logo=owasp&logoColor=white">
<img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white">
<img src="https://img.shields.io/badge/OAuth2-3C4043?style=flat-square">
<img src="https://img.shields.io/badge/LGPD-2E7D32?style=flat-square">
<img src="https://img.shields.io/badge/LLMs_·_RAG-8A2BE2?style=flat-square">

---

## 🎓 Formação e certificações

- **Tecnologia da Informação e Comunicação** · FAETERJ Petrópolis (em curso, último período)
- **Formação em Cibersegurança** · Hackers do Bem, MCTI/RNP (em curso desde abr/2026)
- **Ethical Hacking & Cybersecurity** · HackerX (2026): Pentest, OWASP Top 10, OSINT, XSS, SQL injection, MITM
- **Residência em TIC** · Serratec (2025): Python, IoT, IA e Cloud
- **Formação Iniciante em Programação G8** · Oracle Next Education + Alura (2025)
- **Inglês C2 Proficient** · EF SET 82/100

📜 [Ver os 40+ certificados](https://portfolio-ten-livid-56.vercel.app/certificados.html)

---

<details>
<summary>🇺🇸 <b>English version</b></summary>
<br>

**Full Stack Developer · Java, Spring Boot, Cloud & Security** · Petrópolis, Brazil · Open to internships and junior roles (on-site, hybrid or remote).

I build, **secure** and run real systems in production. Final-semester Information and Communication Technology student at FAETERJ. I designed, built and operate **Hub Atlética Dragões**, a production platform used by 80+ students: Java 21 and Spring Boot 3.5, PostgreSQL with 46 Flyway migrations, a vanilla JS PWA, Docker and Caddy on Oracle Cloud, CI/CD with GitHub Actions and GHCR. It ships with **1,275 automated tests** and ~290 REST endpoints, and migrating from AWS to Oracle Cloud cut hosting costs to zero.

Certified in Ethical Hacking (HackerX), currently in the Hackers do Bem cybersecurity program (MCTI/RNP). Former assistant manager of a 700+ customers/day operation. English: C2 (EF SET 82/100).

📄 [Resume (PDF)](https://portfolio-ten-livid-56.vercel.app/curriculo/Gildean_Monteiro_Resume_EN.pdf) · 💼 [LinkedIn](https://www.linkedin.com/in/gm-nascimento) · ✉️ gmonteiro0808@gmail.com

</details>

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Everett-gi/Everett-gi/output/github-snake-dark.svg">
  <img alt="Contribuições" src="https://raw.githubusercontent.com/Everett-gi/Everett-gi/output/github-snake.svg">
</picture>
