<div align="center">
    <img src="https://github.com/devicons/devicon/blob/master/icons/react/react-original.svg" width="100vw"/>
    <h1>React-Study</h1>
</div>

➡️ Projeto que visa estudar o react na prática, revisando boas práticas de Estrutura e de Código:

---
<details>
    <summary><h2> 🧱 Estrutura:</h2></summary>
    
    ```
    raiz/
    │ 
    ├── public/ # Arquivos estáticos independentes do código da aplicação, como icones,
    │           favicon.ico, SEO, manifest.json, index.html(html base da aplicação). 
    │
    └── src/ # Recursos do projeto
        ├── assets/ # Imagens, Icones
        │
        ├── components/ # Onde ficam componentes(Ex: Botões) do projeto.
        │   └── Button/ 
        │   
        ├── containers/ # Páginas do projeto
        │   ├── Home/
        │   ├── Cart/
        │   └── Register/
        │
        ├── context/ # Arquivos que compartilham dados entre multiplos componentes
        │            (Temas, Autenticação, Carrinho, etc).
        │
        ├── services/ # Onde ficarão serviços e chamadas de API.
        │
        ├── types/ # Arquivos de definições de tipos com Typescript( Interfaces,
        │          types e enums)
        │
        └── styles/ # Estilos globais
    ```
</details>

---

<details>
    <summary><h2> 📦 Pacotes Utilizados:</h2></summary>
    <ul>
        <li>
            styled-components - Estilização em JS
            <ul>
                <li>
                Extensão `vscode-styled-components` # Serve para que a IDE visualize o CSS corretamente dentro do JS utilizado para a estilização.
                </li>
            </ui>
        </li>
    </ul>
</details>
