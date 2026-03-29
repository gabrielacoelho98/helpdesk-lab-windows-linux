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

## 🪟 Windows

### 1- Informações do sistema

Comando: systeminfo

![Windows info](img/win-info.png)

---

### 2. Teste de conectividade

❌ Ping com erro

Comando: ping 192.168.0.254

![Windows ping](img/ping-win-erro.png)

✅ Ping com sucesso

Comando:
ping google.com

![Windows ping](img/ping-win-ok.png)

---

### 3. Instalação e remoção de programa

📥 Instalação

![Windows Instalação](img/instalacao-win.png)

---

🗑️ Remoção

![Windows Remoção](img/desinstalacao-win.png)

---

### 4. Gerenciamento de serviços

⏹️ Serviço Parado
 
Comando:
services.msc

![Windows Serviço ](img/stop-win.png)


▶️ Serviço rodando

![Windows Serviço ](img/servico-running-win.png)

---

🐧 Linux
### 1. Informações do sistema

Comando: 
uname -a

![Linux Serviço ](img/p1-linux-info.png)

---

### 2. Teste de conectividade

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

### 3. Instalação e remoção de programa

📥 Instalação

Comando:
sudo apt  update

![Linux Instalação](img/apt-linux.png)

---

Comando: 
sudo apt install htop

![Linux Instalação](img/install-htop-linux.png)


![Linux Instalação](img/htop-linux.png)


---

🗑️ Remoção

Comando: 
sudo apt remove htop

![Linux Remoção](img/remove-htop-linux.png)

---

## 4. Gerenciamento de serviços

▶️ Serviço rodando

Comando:
systemctl status cups

![Linux Serviço](img/servico-linux.png)

---

⏹️ Serviço parado

Comando:
sudo systemctl stop cups

![Linux Serviço](img/stop-servico-linux.png)

---

🔄 Serviço iniciado novamente

Comando:
sudo systemctl start cups

![Linux Serviço](img/servico-running-linux.png)

---

### 5. Visualização de logs

📸 Logs em tempo real:

Comando:
journalctl -f

![Linux Logs](img/linux-log.png)

---

📸 Geração de eventos:

Comando:
sudo apt update

![Linux Logs](img/log2-linux.png)

---

📚 Aprendizados

Diagnóstico de problemas de conectividade

Interpretação de erros de rede

Instalação e remoção de programas

Gerenciamento de serviços no sistema

Análise de logs para troubleshooting

---

🧪 Conclusão

Este laboratório simulou cenários reais enfrentados por profissionais de suporte técnico, como falhas de rede, controle de serviços e análise de logs, proporcionando uma visão prática das diferenças entre Windows e Linux.

---

🚀 Autor

Projeto desenvolvido para fins de estudo em suporte técnico e infraestrutura de TI.

