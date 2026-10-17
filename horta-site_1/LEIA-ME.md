# Calendário da Horta – como colocar no ar (grátis)

Arquivos: index.html, manifest.webmanifest, sw.js, icon.svg, icon-192.png, icon-512.png.
Mantenha todos juntos na mesma pasta. O site precisa ser HTTPS (as opções abaixo já são).

## Opção 1 – Netlify Drop (mais rápido, sem conta de programador)
1. Abra https://app.netlify.com/drop
2. Arraste a PASTA com os arquivos (ou o zip descompactado) para a página.
3. Pronto: você recebe um endereço público. Dá para trocar o nome nas configurações do site.

## Opção 2 – GitHub Pages
1. Crie uma conta em github.com e um repositório público (ex.: horta).
2. Envie todos os arquivos (Add file > Upload files).
3. Settings > Pages > Branch: main, pasta / (root) > Save.
4. Seu site fica em https://SEU-USUARIO.github.io/horta/

## Instalar no celular
- Android (Chrome): abra o endereço > menu ⋮ > "Instalar app" / "Adicionar à tela inicial".
- iPhone (Safari): botão Compartilhar > "Adicionar à Tela de Início".

## Observações
- O clima usa a API gratuita Open-Meteo e precisa de internet. O calendário e as configurações funcionam offline depois da primeira visita.
- As configurações ficam salvas no navegador de cada pessoa (não são compartilhadas entre aparelhos; use Backup na aba Config).
- Para atualizar o site, troque o index.html e aumente o número "horta-v1" em sw.js (ex.: horta-v2).
