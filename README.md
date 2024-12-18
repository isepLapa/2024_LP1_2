[Jira Issue Tracker](https://cpmtr1.atlassian.net/jira/software/projects/LP1/boards/1?atlOrigin=eyJpIjoiYmI4NjIxMzM5ZTQ1NDUwYjk3ZTQyMTA3Zjc2MGNjOGYiLCJwIjoiaiJ9)

Visual Studio Code Extensões: 
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) (Ajuda a manter o código do projeto uniforme)

## Github
- Fazer commits / pull requests com nomes que expliquem a mudança feita.


### Estrutura dos commits
  - Exemplo: ISSUE-ID: Update Readme
  - Exemplo: [LP1-5](https://cpmtr1.atlassian.net/browse/LP1-5): Update Readme

Isto ajuda na integração entre o Jira e o Github para acompanhar melhor as mudanças no projeto



## Possivel Estrutura do Projeto

> [!IMPORTANT]  
>  👀 <strong>Mini desafio para cada um: <br/></strong>
> Criar uma branch apartir da main com o nome: "readme/numero", no README.md alterar o tema(se os escolhidos não vos agradar) e também alterar "(Por definir)" para o vosso nome com um link para o vosso Perfil do Github. Quando tiverem todas as alterações abrir um Pull Request para a main branch

- Página Inicial (ARM vs x86) [Emanuel Lapa](https://github.com/isepLapa)

- Performance (ARM vs x86) [Gonçalo Tavares](https://github.com/GoncaloTavares08)
- Compatibilidade Software (ARM vs x86) (Por definir)
- Preços/Custos/Eficiência/Usos (Por definir)
- Diferenças [JoãoTeixeira](https://github.com/Jp3teixeira)


## Coding Guidelines

```
Utilizar HTML5 e CSS3

Exemplo HTML:

| ✅ Fazer      | ❌ Evitar      |
| ------------- | ------------- |
| <main>        | <div>         |
|   <section>   |    <div>      |
|   </section>  |   </div>      |
| </main>       | </div>        |

```

### Estrutura e Organização

```
├── /assets              # CSS, Imagens e outros dentro desta pasta
│   ├── /css             # Estilização do projeto
│   │   └── estilos.css  # Main stylesheet
│   └── /imagens         # Introduzir imagens neste ficheiro
│       └── cpu_x86.png  # Nomes que identifiquem o ficheiro
├── index.html           # Página Inicial
├── /paginas             # Documentation and resources (optional)
│   ├── nome.html        # Nomear conforme o nome na navbar
│   └── nome.html        # Nomear conforme o nome na navbar

```
