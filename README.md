# Landing page — BARBER

Landing page responsiva para barbearia, feita em HTML, CSS e JavaScript puro. Não precisa de servidor, banco de dados ou processo de build.

## Antes de publicar

Abra `index.html` e personalize:

1. **WhatsApp:** no final do arquivo, troque `WHATSAPP_NUMBER = "5587999999999"` pelo número da barbearia com código do país e DDD, apenas números. Exemplo: `5511991234567`.
2. **Marca:** substitua `BARBER` pelo nome real da barbearia.
3. **Serviços e preços:** atualize os cards e as opções do formulário para refletir os serviços reais.
4. **Depoimentos:** troque os depoimentos de exemplo por avaliações verdadeiras.
5. **Fotos:** as imagens atuais vêm do Unsplash e precisam de internet para carregar. Você pode substituí-las por fotos próprias.

O formulário não reserva automaticamente nem verifica disponibilidade. Ele monta a mensagem e abre o WhatsApp; a equipe confirma o horário por lá.

## Publicar no GitHub Pages

1. Entre no GitHub e abra o repositório do site.
2. Clique em **Add file → Upload files** e envie `index.html` (e este README, se quiser).
3. Vá em **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Em **Branch**, selecione `main` e a pasta `/(root)`, depois clique em **Save**.
6. Aguarde a publicação e abra o endereço mostrado na seção Pages. Geralmente será `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

Se os arquivos já estão no repositório, basta substituir o `index.html` atual e fazer commit. Pode levar alguns minutos para a alteração aparecer.

## Estrutura

- `index.html` — página, estilos e comportamento do formulário.
