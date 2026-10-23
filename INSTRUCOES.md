# Instalação — perfil GitHub Arvak Labs

Esta pasta é o conteúdo do repositório especial `danielrosajr/danielrosajr` — **não** do repositório `danielrosajr.github.io`.

## Caminhos que precisam existir

- `README.md`
- `assets/arvak-banner.svg`
- `.github/workflows/snake.yml`

## Pelo site do GitHub, sem terminal

1. Abra https://github.com/danielrosajr/danielrosajr (ou crie-o como repositório público se ainda não existir).
2. Crie/edite `README.md` e cole o conteúdo correspondente.
3. Clique em **Add file → Create new file**, informe o caminho `assets/arvak-banner.svg`, cole o conteúdo do arquivo SVG, e salve.
4. Repita para `.github/workflows/snake.yml`, colando o workflow YAML. Pastas ocultas geralmente não são carregadas no uploader do navegador, portanto prefira **Create new file** com o caminho completo.
5. Abra https://github.com/danielrosajr/danielrosajr/actions, selecione **Update contribution snake**, clique em **Run workflow** e acompanhe o resultado. A saída será publicada na branch `output`.
6. Abra https://github.com/danielrosajr/ e confirme o banner, ícones, cards, imagens e animação.

## Se a animação falhar

Em Settings → Actions → General, confira se Actions está habilitado. O workflow pede `contents: write`; se a organização ou as políticas impedirem gravação, será necessário permitir a gravação necessária. O perfil é funcional mesmo sem a animação.

## Limitações e cuidados

- Os cards de estatísticas, a linha de digitação e os ícones dependem de serviços públicos externos e podem ficar indisponíveis por períodos curtos.
- Links de páginas seguem a convenção do GitHub Pages de cada repositório com Pages habilitado. Confira os links de demonstração antes de divulgá-los.
- O perfil README é publicado pelo GitHub automaticamente; não precisa instalar Node.js, GitHub Pages ou gerar build.
- Para personalizar o texto, edite `README.md`; o banner visual está em `assets/arvak-banner.svg`.
