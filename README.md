# Geoportal — Uso do Solo (Jaguariúna)

Geoportal interativo para consulta do mapeamento de uso e ocupação do solo do município de Jaguariúna/SP.

🔗 **Acesse ao vivo:** https://mirianniz-debug.github.io/Uso-do-solo-em-Jaguariuna/

👤 **Parte do portfólio de:** https://mirianniz-debug.github.io/Portfolio/

## Sobre

Mapa web com as classes de uso do solo do município, permitindo consulta espacial das categorias mapeadas (urbano, agrícola, vegetação nativa, corpos d'água, entre outras).

## Tecnologias

- Leaflet.js
- QGIS (exportado via QGIS2Web)
- HTML/CSS/JavaScript puro (sem build/dependências)

## Como visualizar localmente

Não há dependências ou build — basta abrir `index.html` diretamente no navegador, ou servir a pasta com um servidor estático simples:

```bash
python3 -m http.server 8000
```

Depois acesse `http://localhost:8000` no navegador.

## Incorporando o geoportal em outro site (iframe)

O `index.html` é responsivo, mas isso só funciona se o `<iframe>` que o incorpora também for responsivo. Use sempre largura em porcentagem, nunca um valor fixo em pixels:

```html
<iframe src="URL_DO_GEOPORTAL" style="width:100%; border:0;" height="600" loading="lazy"></iframe>
```

## Licença

Todos os direitos reservados. Ver [LICENSE](LICENSE).
