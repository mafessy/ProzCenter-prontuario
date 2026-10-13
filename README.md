# PROZ CENTER — versão organizada para hospedagem

O pacote contém duas opções:

- **`PRONTUARIO_HTMLY.html`** — arquivo único e autônomo, com CSS e JavaScript internos. Use esta opção se o HTMLy permitir inserir/publicar um HTML completo em uma única página.
- **`index.html`, `style.css`, `script.js` e `setembro-amarelo.jpg`** — versão modular, mais fácil de manter. Esses arquivos precisam ficar juntos na mesma pasta.
- **`favicon-32.png`, `apple-touch-icon.png` e `og-image.png`** — imagens originais do projeto, mantidas com seus nomes.

## Hospedagem

1. Para usar a versão modular, envie todos os arquivos para a mesma pasta e abra `index.html`.
2. Se o HTMLy aceitar somente um arquivo/código HTML, use `PRONTUARIO_HTMLY.html`. Como ele é autônomo, não depende de `style.css`, `script.js` ou da imagem externa para renderizar a imagem de campanha.
3. Se o HTMLy bloquear JavaScript, scripts inline ou armazenamento local, o sistema pode não funcionar corretamente. Nesse caso, será necessário habilitar esses recursos ou usar uma hospedagem estática que os permita.

## Observações

- A configuração original continua usando `localStorage` (`backend: 'local'`), portanto os dados ficam no navegador utilizado e não são sincronizados entre dispositivos.
- O código passou por verificação sintática do JavaScript (`node --check`). Isso não substitui um teste completo de todas as telas e fluxos no navegador.
- Este é um sistema demonstrativo para fins educacionais; não use dados reais ou identificáveis de pacientes em uma publicação pública.
