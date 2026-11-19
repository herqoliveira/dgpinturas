# DG Pinturas — portfólio

Site estático feito com HTML e CSS, sem dependências.

## Como trocar os espaços por fotos

1. Salve as imagens em uma pasta `images` dentro de `dist`.
2. Em `dist/index.html`, troque cada bloco `.photo-placeholder` por uma imagem, por exemplo:

   ```html
   <img class="photo-image" src="images/apto-moema-01.jpg" alt="Ambiente do Apto. Moema após a pintura">
   ```

3. Para mais imagens no mesmo serviço, duplique um elemento `<figure class="photo-card">` dentro de `.photo-grid`.
4. Para um novo serviço, duplique um `<article class="work-group">` e ajuste o título.
5. A logo do cabeçalho é carregada de `dist/images/logo.png`. Troque esse arquivo mantendo o mesmo nome ou ajuste o caminho no HTML. Atualize também as informações de apresentação e contato.

## Como configurar o botão do WhatsApp

No `dist/index.html`, substitua `55SEUNUMERO` no link do botão pelo telefone completo, apenas com dígitos: código do país + DDD + número. Exemplo: `5511987654321`.

Para colocar a foto de perfil, salve a imagem em `dist/images/perfil-pintor.jpg` e substitua o marcador circular no card por uma tag `<img class="whatsapp-profile-photo" src="images/perfil-pintor.jpg" alt="Foto do pintor">`.

Os quadros coloridos são marcadores temporários para facilitar a troca pelas fotos reais de cada trabalho.
