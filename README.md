
<div align="center">

<img src="https://raw.githubusercontent.com/AyumiBotOficial/links-img/main/fotos/1768943446533_kr7422.jpg" alt="Mikasa Glitch" width="100%">

# ☠️ ＭＩＫＡＳＡ － ＢＯＴ ☠️

> *"Se você não lutar, você não pode vencer."*

[![Node.js](https://img.shields.io/badge/Node.js-18.x-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![Baileys](https://img.shields.io/badge/Baileys-Library-blue?style=for-the-badge&logo=whatsapp)](https://github.com/WhiskeySockets/Baileys)
[![Status](https://img.shields.io/badge/STATUS-ONLINE-red?style=for-the-badge&logo=security)](https://github.com/)
[![Owner](https://img.shields.io/badge/OWNER-LUCAS%20LISBOA-purple?style=for-the-badge&logo=github)](https://github.com/LucasLisboa)

</div>

---

### 📡 VISÃO GERAL
O **Mikasa Bot** é um sistema de automação de elite para WhatsApp, desenvolvido em **Node.js** utilizando a arquitetura **Baileys**. O foco do projeto é privacidade e controle total, operando com um banco de dados **SQLite Criptografado** para garantir que nenhuma mensagem ou sessão seja exposta. Possui sistema híbrido de plugins e ferramentas de inteligência para administração de grupos (Sistema X9).

---

<details>
<summary><h2>🛠️ FUNÇÕES DO SISTEMA (Expandir)</h2></summary>

| Módulo | Status | Descrição |
| :--- | :---: | :--- |
| **CORE** | 🟢 | Conexão QR Code rápida com auto-reconect. |
| **SQLITE CRYPTO** | 🟢 | Banco de dados criptografado para máxima segurança. |
| **X9 TRACKER** | 🟢 | Monitoramento de membros fantasmas e etiquetas ocultas. |
| **HIERARCHY** | 🟢 | Sistema de Dono, Sub-dono e Premium. |
| **SECURITY** | 🟢 | Anti-Link, Anti-Fake, Anti-Spam e Banimento automático. |
| **PLUGINS** | 🟢 | Instalação de comandos sem desligar o bot. |
| **RPG** | 🟡 | Sistema de economia e duelos (Em Desenvolvimento). |

</details>

<details>
<summary><h2>📜 CHANGELOG</h2></summary>

### v2.0.0 - *The Shingeki Update*
- [x] Migração completa para Baileys Whiskeysockets.
- [x] Integração do SQLite Criptografado.
- [x] Adicionado sistema de identificação de fantasmas (X9).
- [x] Otimização de memória RAM (Fix memory leak).

### v1.0.0 - *Origins*
- [x] Lançamento inicial.
- [x] Comandos de administração.

</details>

---

## 💀 INSTALAÇÃO E DEPLOY

<details>
<summary><h3>💻 VPS (UBUNTU / DEBIAN)</h3></summary>

```bash
# 1. Atualize os pacotes
sudo apt update && sudo apt upgrade -y
sudo apt install -y git ffmpeg curl libwebp-dev build-essential imagemagick

# 2. Instale o Node.js 18
curl -fsSL [https://deb.nodesource.com/setup_18.x](https://deb.nodesource.com/setup_18.x) | sudo -E bash -
sudo apt install -y nodejs

# 3. Clone o repositório
git clone [https://github.com/LucasLisboa/Mikasa-Bot.git](https://github.com/LucasLisboa/Mikasa-Bot.git)
cd Mikasa-Bot

# 4. Instale
npm install

# 5. Inicie
npm start

</details>
<details>
<summary><h3>📱 TERMUX (ANDROID)</h3></summary>
termux-setup-storage
pkg update && pkg upgrade -y
pkg install git nodejs ffmpeg libwebp imagemagick yarn -y
git clone [https://github.com/LucasLisboa/Mikasa-Bot.git](https://github.com/LucasLisboa/Mikasa-Bot.git)
cd Mikasa-Bot
npm install
npm start

</details>
<details>
<summary><h3>🦅 PTERODACTYL PANEL</h3></summary>
 * Crie um servidor com o Egg Node.js Generic.
 * Defina a versão do Node para 18.
 * Install Command: npm install
 * Startup Command: npm start
 * Suba os arquivos (menos a node_modules).
 * Inicie e escaneie o QR Code no Console.
</details>
🧬 ESTRUTURA DE PLUGINS
Mikasa-Bot/
├── assets/          # Mídia e Imagens
├── database/        # SQLite DB (NÃO MEXA)
├── lib/             # Funções do Baileys
├── plugins/         # Seus comandos ficam aqui
│   ├── admin/       # Comandos de Grupo
│   ├── owner/       # Comandos do Lucas Lisboa
│   ├── rpg/         # Sistema de Níveis
│   └── tools/       # Ferramentas Úteis
├── config.js        # Configuração do Dono
└── index.js         # Arquivo Principal

⚠️ AVISO LEGAL
> Este software é para fins de aprendizado e teste de segurança. O uso de bots no WhatsApp pode violar os Termos de Serviço. O desenvolvedor (Lucas Lisboa) não se responsabiliza pelo mau uso ou banimento de números.
> 
<div align="center">
  _                      _     _     _              
 | |   _   _  ___ __ _  | |   (_)___| |__   ___   __ _ 
 | |  | | | |/ __/ _` | | |   | / __| '_ \ / _ \ / _` |
 | |__| |_| | (_| (_| | | |___| \__ \ |_) | (_) | (_| |
 |_____\__,_|\___\__,_| |_____|_|___/_.__/ \___/ \__,_|
                                                       
          MIKASA BOT PROJECT | EST. 2026

Developed by Lucas Lisboa
</div>

