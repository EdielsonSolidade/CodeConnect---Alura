# CodeConnect 🖥️✨

O **CodeConnect** é uma aplicação web responsiva que simula uma plataforma de compartilhamento de projetos de programação. A interface permite ao usuário fazer upload de imagens, descrever seu projeto, adicionar tags relevantes e realizar uma publicação simulada.

## 🚀 Funcionalidades

- 📤 Upload de imagem para representar o projeto.
- 📝 Formulário com campos para nome do projeto, descrição da imagem e tags.
- 🏷️ Validação de tags: apenas as pré-definidas são aceitas.
- ❌ Remoção de tags adicionadas.
- 📦 Botões de ação para **publicar** ou **descartar** os dados inseridos.
- ⚙️ Simulação de publicação com promessa assíncrona e feedback visual.
- 💡 Interface moderna com design inspirado em plataformas colaborativas.

## 🛠️ Tecnologias Utilizadas

- **HTML5** para estrutura da página.
- **CSS3** para estilização (importação de fontes e layout responsivo).
- **JavaScript (Vanilla)** para toda a lógica interativa do front-end.

## 📂 Estrutura de Arquivos

```bash
├── index.html
├── styles.css
├── scripts.js
├── img/
│   ├── Logo.svg
│   ├── feed.svg
│   ├── account_circle.svg
│   ├── info.svg
│   ├── logout.svg
│   ├── imagem1.png
│   └── close.svg / close-black.svg

📌 Como Usar
Clique no botão Upload Image e selecione uma imagem.

Preencha os campos: nome do projeto, descrição e tags.

Adicione tags válidas (como HTML, CSS, JavaScript, etc).

Clique em Publicar para simular o envio dos dados.

Clique em Descartar para limpar o formulário.

🔒 Observações
O envio do projeto é simulado usando uma Promise com delay e chance de erro/sucesso.

As tags disponíveis estão pré-definidas no código e não podem ser personalizadas pelo usuário final nesta versão.

✍️ Autor
Projeto desenvolvido por Edielson 👨‍💻 — estudante de tecnologia em busca de crescimento e aprendizado constante.
