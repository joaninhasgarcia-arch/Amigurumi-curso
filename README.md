# Curso de Personalização de Amigurumis — Área de Membros

Este pacote foi preparado para hospedagem estática no GitHub Pages.

## Arquivos

- `index.html` — página completa do curso, com CSS, JavaScript e imagens embutidos.
- `README.md` — instruções deste pacote.

## Como publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie os arquivos `index.html` e `README.md` para a raiz do repositório.
3. No GitHub, abra **Settings > Pages**.
4. Em **Build and deployment**, selecione:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
5. Salve e aguarde o GitHub gerar o link da página.

## Observações

- Não existe pasta `assets`: o CSS, JavaScript e as imagens locais foram embutidos dentro do `index.html`.
- Vídeos do YouTube, PDFs externos e fontes do Google continuam carregando pela internet, pois são links externos usados pelo próprio curso.
- O progresso e as anotações do aluno usam `localStorage` do navegador.
