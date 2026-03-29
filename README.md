# helpdesk-lab-windows-linux
Laboratório prático simulando atividades reais de suporte técnico, com foco em comandos básicos, instalação de programas, gerenciamento de serviços e análise de logs em ambientes Windows e Linux.

---

🎯 Objetivo

Demonstrar na prática tarefas comuns do dia a dia de um profissional de suporte técnico, comparando ferramentas e comandos entre Windows e Linux.

---

🛠️ Tecnologias Utilizadas
VirtualBox
Windows
Linux (Ubuntu)
Terminal / Prompt de Comando

---

🔎 Etapas do Laboratório

🪟 Windows

1- Informações do sistema

Comando: systeminfo

![Windows info](img/win-info.png)

---

2. Teste de conectividade

❌ Ping com erro

Comando: ping 192.168.0.254

![Windows ping](img/ping-win-erro.png)

✅ Ping com sucesso

Comando:
ping google.com

![Windows ping](img/ping-win-ok.png)

---

3. Instalação e remoção de programa

📥 Instalação

![Windows Instalação](img/instalacao-win.png)

---

🗑️ Remoção

![Windows Remoção](img/desinstalacao-win.png)

---

4. Gerenciamento de serviços

⏹️ Serviço Parado
 
Comando:
service.msc

![Windows Serviço ](img/stop-win.png)


▶️ Serviço rodando

![Windows Serviço ](img/servico-running-win.png)

---

🐧 Linux
1. Informações do sistema

Comando: 
uname -a

![Linux Serviço ](img/p1-linux-info.png)

---

2. Teste de conectividade

❌ Ping com erro

Comando: 
ping -c 4 192.168.0.254

![Linux Ping ](img/ping-linux-erro.png)

---

✅ Ping com sucesso

Comando: 
ping google.com

![Linux Ping ](img/ping-linux-ok.png)

---

3. Instalação e remoção de programa

📥 Instalação

comandos:

sudo apt install 


![Linux Instalação](img/apt-linux.png)

![Linux Instalação](img/htop-linux.png)









