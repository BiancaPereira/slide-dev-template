# Talk: Nome da talk
> Feito usando [Slidev](https://github.com/slidevjs/slidev)!

Esse template pode ser utilizado para criar apresentações simples, elegantes e dinâmicas utilizando o [Slidev](https://github.com/slidevjs/slidev). 

O **SlideDev** te ajuda a criar apresentações escrevendo em **markdown** e com o benefício e flexibilidade de utilizar HTML, CSS e até mesmo incluir componentes em **Vue.js**.

---

### Rodando localmente

Para rodar os slides localmente:

1. `npm install`
2. `npm run dev`
3. Acesse <http://localhost:3030>

---

### Deploy usando o Github Page

Para publicar a sua apresentação pelo Github Pages é bem tranquilo, pois o workflow de deploy já está quase todo configurado em `.github/worflow`.

O primeiro passo é editar o arquivo `.github/workflow` na **linha 16** e trocar `REPOSITORY-NAME` pelo nome do seu repositório.

Depois, você precisa habilitar o deploy no Github Pages:
1. Ir em **Settings** na página do repositório;
2. Clicar no menu lateral **Pages**;
3. Selecionar **Source** como **Deploy from a branch**;
4. E **Branch** você seleciona `gh-pages` e `root`.

Você pode ver as ações rodando na aba **Actions**.
