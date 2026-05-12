# Atividade Prática: Visualizador 3D com Three.js

Este projeto é uma aplicação web interativa que utiliza a biblioteca **Three.js** para renderizar e manipular modelos 3D carregados via **Sketchfab**. A atividade faz parte dos requisitos da disciplina de Computação Gráfica
.

## 🚀 Funcionalidades Implementadas
*   **Carregamento de Modelo 3D**: Uso do `GLTFLoader` para processar arquivos no formato `.glb`.
*   **Interatividade**: Implementação do `OrbitControls` para rotação (botão esquerdo), zoom (scroll) e pan (botão direito).
*   **Iluminação Dinâmica**: Sistema com luz ambiente e luz direcional para realce de texturas.
*   **Design Responsivo**: Ajuste automático da câmera e do renderizador ao redimensionar a janela.
*   **Loop de Animação**: Uso eficiente de `requestAnimationFrame` para renderização contínua.

## 📦 Modelo Utilizado
*   **Nome do Modelo:** [Pokemon] Sylveon 
*   **Autor:** StarlightLambda64
*   **Link Original:** https://sketchfab.com/3d-models/pokemon-sylveon-6558f02e893b4f00a1da1de383a0aa43
*   **Licença:** Free Standard

## 🛠️ Tecnologias
*   [Three.js](https://threejs.org/) (via CDN)
*   JavaScript (ES6 Modules)
*   HTML5 / CSS3

## ⚙️ Como executar o projeto

Devido à política de segurança (CORS) dos navegadores modernos para módulos ES6 e carregamento de arquivos locais, o projeto **não** deve ser aberto clicando diretamente no arquivo `index.html`. É necessário um servidor local.

1.  **Usando VS Code (Recomendado):**
    *   Instale a extensão **Live Server**.
    *   Clique com o botão direito no arquivo `index.html`.
    *   Selecione **"Open with Live Server"**.

2.  **Usando Python:**
    ```bash
    # No diretório do projeto, execute:
    python -m http.server 8000
   Acesse no navegador: `http://localhost:8000`

