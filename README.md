☠️ MIKASA BOT ☠️

> “Se você não lutar, você não pode vencer.”



<div align="center"><img src="https://raw.githubusercontent.com/AyumiBotOficial/links-img/main/fotos/1768943446533_kr7422.jpg" width="100%" alt="Mikasa Bot">   

</div>
---

📡 VISÃO GERAL

O Mikasa Bot é um sistema avançado de automação para WhatsApp, desenvolvido em Node.js utilizando Baileys.
Projetado com foco total em segurança, desempenho e controle, utilizando SQLite criptografado para proteger sessões e dados.

Possui arquitetura híbrida de plugins, sistema de hierarquia de usuários e ferramentas inteligentes de administração de grupos (Sistema X9).


---

<details>
<summary>🛠️ FUNÇÕES DO SISTEMA</summary>⚙️ Módulos Principais

Módulo	Status	Descrição

CORE	🟢	Conexão rápida via QR Code com auto-reconnect
SQLITE CRYPTO	🟢	Banco de dados SQLite criptografado
X9 TRACKER	🟢	Monitoramento de etiquetas e membros suspeitos
HIERARCHY	🟢	Sistema de Dono, Sub-dono e Premium
SECURITY	🟢	Anti-link, Anti-spam, Anti-fake, Ban automático
PLUGINS	🟢	Comandos dinâmicos sem reiniciar o bot
RPG	🟡	Economia, níveis e duelos (em desenvolvimento)


</details>
---

<details>
<summary>📜 CHANGELOG</summary>v2.0.0 — The Shingeki Update

Migração completa para Baileys (WhiskeySockets)

Integração do SQLite criptografado

Sistema X9 de rastreamento

Otimização de consumo de RAM

Correções de reconexão


v1.0.0 — Origins

Lançamento inicial

Sistema básico de administração

Estrutura de plugins


</details>
---

💀 INSTALAÇÃO E DEPLOY

<details>
<summary>💻 VPS (UBUNTU / DEBIAN)</summary># Atualizar sistema
sudo apt update && sudo apt upgrade -y

# Dependências
sudo apt install -y git ffmpeg curl imagemagick build-essential libwebp-dev

# Node.js 18
curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
sudo apt install -y nodejs

# Clonar projeto
git clone https://github.com/LucasLisboa/Mikasa-Bot.git
cd Mikasa-Bot

# Instalar dependências
npm install

# Iniciar bot
npm start

</details><details>
<summary>📱 TERMUX (ANDROID)</summary>termux-setup-storage
pkg update && pkg upgrade -y
pkg install git nodejs ffmpeg imagemagick libwebp -y

git clone https://github.com/LucasLisboa/Mikasa-Bot.git
cd Mikasa-Bot

npm install
npm start

</details><details>
<summary>🦅 PTERODACTYL PANEL</summary>Egg: Node.js Generic

Node Version: 18

Install Command:


npm install

Startup Command:


npm start

Envie os arquivos (exceto node_modules)

Inicie o servidor e escaneie o QR Code no console


</details>
---

🧬 ESTRUTURA DE PLUGINS

Mikasa-Bot/
├── assets/          # Mídias e imagens
├── database/        # SQLite (NÃO EDITAR)
├── lib/             # Funções internas
├── plugins/         # Sistema de comandos
│   ├── admin/       # Administração de grupos
│   ├── owner/       # Comandos do dono
│   ├── rpg/         # Sistema RPG
│   └── tools/       # Utilidades
├── config.js        # Configuração principal
└── index.js         # Inicialização


---

⚠️ AVISO LEGAL

> Este projeto é destinado exclusivamente para fins educacionais e de estudo.
O uso de bots no WhatsApp pode violar os Termos de Serviço da plataforma.
O desenvolvedor não se responsabiliza por banimentos ou uso indevido.




---

<div align="center">███╗   ███╗██╗██╗  ██╗ █████╗ ███████╗ █████╗ 
 ████╗ ████║██║██║ ██╔╝██╔══██╗██╔════╝██╔══██╗
 ██╔████╔██║██║█████╔╝ ███████║███████╗███████║
 ██║╚██╔╝██║██║██╔═██╗ ██╔══██║╚════██║██╔══██║
 ██║ ╚═╝ ██║██║██║  ██╗██║  ██║███████║██║  ██║
 ╚═╝     ╚═╝╚═╝╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝

MIKASA BOT PROJECT — EST. 2026
Developed by Lucas Lisboa

</div>
