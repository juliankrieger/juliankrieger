## 👋 Welcome to My Profile!

I'm **Julian Krieger**, a passionate developer crafting elegant solutions to complex problems.

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=00D9FF&center=true&vCenter=true&width=435&lines=Full+Stack+Developer;Open+Source+Enthusiast;Problem+Solver" alt="Typing SVG" />
</div>

---

### 🚀 About Me

- 🔭 Currently working on impactful projects that make a difference
- 🌱 Continuously learning new technologies and best practices
- 💡 Passionate about clean code, architecture, and scalability
- 🤝 Always open to collaborating on exciting ideas
- 💬 Ask me about web development, system design, and software best practices
- 📫 [Reach out on LinkedIn](#) | [Say hello via Email](#)
- ⚡ Fun fact: I believe code should be poetry for machines and humans alike

---

### 🛠️ Tech Stack

<div align="center">

**Languages**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vue.js&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwind-css&logoColor=white)

**Backend & Databases**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

**Tools & Platforms**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

</div>

---

### 📊 GitHub Stats

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=juliankrieger&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=juliankrieger&layout=compact&theme=tokyonight" />
</div>

---

### 🎯 Featured Project: BRSKI Collection

<div align="center">
  
  [![Repository](https://img.shields.io/badge/GitHub-open--brski-181717?style=for-the-badge&logo=github)](https://github.com/juliankrieger/open-brski)
  [![Rust](https://img.shields.io/badge/Language-Rust-CE422B?style=for-the-badge&logo=rust)](https://www.rust-lang.org/)
  
</div>

**A comprehensive Rust implementation of BRSKI (Bootstrapping Remote Secure Key Infrastructures) and related protocols for secure device onboarding and certificate management.**

#### Key Features

🔐 **Core Standards**
- **BRSKI** (RFC 8995) — Device pledge bootstrapping and MASA integration
- **EST** (RFC 7030) — Enrollment over Secure Transport with certificate management
- **Vouchers** (RFC 8366) — Cryptographically signed device authorization documents

🌐 **Extended Implementations**
- **BRSKI-PRM** — Privacy-respecting manufacturer variant
- **CBRSKI** — Constrained BRSKI for resource-limited devices
- **CBRSKI-PRM** — Combined privacy and constrained environment support

⚙️ **Architecture Highlights**
- Modular, production-ready design with pluggable cryptographic formats
- **no_std** support for embedded and IoT environments
- Format-agnostic envelope framework with JWS & CBOR support
- Support for modern algorithms: ECDSA, RSA-PSS, HMAC

#### Project Structure

```
crates/
├── envelope/              # Core signing & serialization framework
├── envelope-jws/          # JSON Web Signature implementation
├── cert-types/            # X.509 certificate utilities
├── voucher/               # RFC 8366 voucher implementation
├── voucher-analyzer/      # Helper binary for voucher analysis
├── voucher-macros/        # Procedural macros
└── est/                   # EST client & server implementations
```

#### Use Cases

👨‍💼 **Device Manufacturers** — Issue and manage vouchers via MASA  
🏢 **Network Operators** — Deploy EST servers for certificate management  
🤖 **Embedded Systems** — Lightweight enrollment for constrained devices  
🏭 **Enterprise** — Integrate with existing PKI infrastructure

#### Tech Stack

- **Cryptography**: OpenSSL (vendored), p256, ecdsa, sha2, hmac
- **Serialization**: serde, serde_json, ciborium (CBOR)
- **Async Runtime**: tokio, tower, axum, hyper
- **Standards**: X.509, JWS, CBOR

#### Quick Start

```bash
# Clone and build
git clone https://github.com/juliankrieger/open-brski
cd open-brski

# Build all crates
cargo build --workspace

# Run tests
cargo test --workspace

# Run voucher analyzer
cargo run --bin helper --features serde -- path/to/voucher.json
```

📖 [Explore the full project →](https://github.com/juliankrieger/open-brski)

---

### 🎯 Other Notable Projects

Check out my repositories for more exciting work!

---

### 📫 Get In Touch

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/julian-krieger-29b0b4164/)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=flat-square&logo=twitter&logoColor=white)](https://twitter.com)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:julian@example.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://krieger.cool)

</div>

---

<div align="center">
  
  ⭐️ If you found value in my work, consider giving a star to my repositories!
  
  *Happy coding! 🚀*

</div>
