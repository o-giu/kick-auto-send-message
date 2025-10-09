# 🤖 Kick Auto Send Message

<img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Flag_of_Brazil.svg" alt="Bandeira do Brasil" width="20"/> O arquivo .js contém um script JavaScript que automatiza o envio de um emote aleatório no chat de uma live da Kick. O código foi projetado para ser executado no console do DevTools.<br>
<img src="https://upload.wikimedia.org/wikipedia/en/a/a4/Flag_of_the_United_States.svg" alt="Bandeira dos EUA" width="20"/> The .js file contains a JavaScript script that automates sending a random emote in the chat of a Kick live stream. The code is designed to run in the DevTools console.

---

## 📖 Índice / Index
- <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Flag_of_Brazil.svg" alt="Bandeira do Brasil" width="20"/> [Português (BR)](#-português-br)
- <img src="https://upload.wikimedia.org/wikipedia/en/a/a4/Flag_of_the_United_States.svg" alt="Bandeira dos EUA" width="20"/> [English (EN)](#-english-en)
- [Aviso / Disclaimer](#-disclaimer--aviso)

---

## <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Flag_of_Brazil.svg" alt="Bandeira do Brasil" width="20"/> Português (BR)

### Como usar
| Passo | Descrição |
|-------|-----------|
| **0 (Pré-requisito)** | **Popule a barra de emotes**: O script seleciona emotes da sua barra de acesso rápido ("quick emotes"). **Envie manualmente seus emotes favoritos no chat pelo menos uma vez** para que eles apareçam lá. |
| 1 | **Abra uma live na Kick**: Acesse a transmissão ao vivo na Kick onde você deseja enviar os emotes. |
| 2 | **Abra o DevTools**: No seu navegador, pressione `F12` ou `Ctrl + Shift + I` (Windows/Linux) ou `Cmd + Option + I` (Mac). |
| 3 | **Vá para a aba Console**: No DevTools, selecione a aba "Console". |
| 4 | **Cole o código**: Copie o código JavaScript fornecido e cole-o no console. |
| 5 | **Pressione Enter**: Após colar o código, pressione `Enter` para executá-lo. |
| 6 | **Observe o funcionamento**: O script começará a enviar um emote aleatório da sua barra de acesso rápido a cada 10 a 15 minutos. Mensagens como `Clicando no emote: [nomeDoEmote]` e `Próximo envio de emote em X minutos.` serão exibidas no console. |

### É seguro usar?
| Pergunta | Resposta |
|----------|----------|
| A Kick pode detectar o uso do script? | A Kick não consegue distinguir entre cliques feitos manualmente por um usuário e cliques feitos por um script executado no DevTools, pois a ação é a mesma. |
| Há riscos de bloqueio? | Se você diminuir muito o intervalo de tempo e enviar muitas mensagens, a Kick pode detectar atividade de spam e limitar sua conta. O intervalo padrão de 10-15 minutos é seguro. |

### Personalização
| Opção | Descrição |
|-------|-----------|
| **Alterar os emotes enviados** | O script seleciona um emote da sua barra de "quick emotes". Para mudar os emotes que podem ser enviados, use emotes diferentes no chat para que eles apareçam nessa barra. |
| **Mudar o intervalo de tempo** | Na linha `const delay = rand(10, 15) * 60 * 1000;`, altere os valores `10` e `15` para definir um novo intervalo mínimo e máximo (em minutos). |

---

## <img src="https://upload.wikimedia.org/wikipedia/en/a/a4/Flag_of_the_United_States.svg" alt="Bandeira dos EUA" width="20"/> English (EN)

### How to use
| Step | Description |
|------|-------------|
| **0 (Prerequisite)** | **Populate the emote bar**: The script selects emotes from your "quick emotes" bar. **You must manually send your favorite emotes in the chat at least once** for them to appear there. |
| 1 | **Open a Kick live stream**: Go to the live stream on Kick where you want to send emotes. |
| 2 | **Open DevTools**: In your browser, press `F12` or `Ctrl + Shift + I` (Windows/Linux) or `Cmd + Option + I` (Mac). |
| 3 | **Go to the Console tab**: In DevTools, select the "Console" tab. |
| 4 | **Paste the code**: Copy the provided JavaScript code and paste it into the console. |
| 5 | **Press Enter**: After pasting the code, press `Enter` to execute it. |
| 6 | **Observe the operation**: The script will start sending a random emote from your quick emotes bar every 10 to 15 minutes. Messages like `Clicking on emote: [emoteName]` and `Next emote submission in X minutes.` will appear in the console. |

### Is it safe to use?
| Question | Answer |
|----------|--------|
| Can Kick detect the use of the script? | Kick cannot distinguish between clicks made manually by a user and clicks performed by a script running in DevTools, as the action is identical. |
| Are there any risks of being banned? | If you significantly decrease the time interval and send too many messages, Kick might detect spam activity and limit your account. The default 10-15 minute interval is safe. |

### Customization
| Option | Description |
|--------|-------------|
| **Change the sent emotes** | The script selects an emote from your "quick emotes" bar. To change which emotes can be sent, use different emotes in the chat so they will appear on that bar. |
| **Change the time interval** | In the line `const delay = rand(10, 15) * 60 * 1000;`, change the values `10` and `15` to set a new minimum and maximum interval (in minutes). |

---

## ⚠️ Disclaimer / Aviso

<table>
  <tr>
    <th>Language</th>
    <th>Message</th>
  </tr>
  <tr>
    <td width="150"><img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Flag_of_Brazil.svg" alt="Bandeira do Brasil" width="20"/> Português</td>
    <td>Este script é apenas para fins educacionais. Use-o por sua conta e risco. O autor não se responsabiliza por qualquer bloqueio ou restrição imposta pela Kick.</td>
  </tr>
  <tr>
    <td width="150"><img src="https://upload.wikimedia.org/wikipedia/en/a/a4/Flag_of_the_United_States.svg" alt="Bandeira dos EUA" width="20"/> English</td>
    <td>This script is for educational purposes only. Use it at your own risk. The author is not responsible for any bans or restrictions imposed by Kick.</td>
  </tr>
</table>
