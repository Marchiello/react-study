<h1 align="center">React-Study</h1>

-> Projeto que visa estudar o react na prática, revisando boas práticas de Estrutura e de Código:

---

# Estrutura:

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

---

# Pacotes Utilizados:
* styled-components - Estilização em JS
    * Extensão `vscode-styled-components` # Serve para que a IDE visualize o CSS corretamente dentro do JS utilizado para a estilização.