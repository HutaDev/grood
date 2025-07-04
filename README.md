﻿# Grood

Secção Hero moderna e responsiva para páginas web, desenvolvida com HTML e CSS, com foco em desempenho e clareza visual. Este projecto fornece a base para páginas institucionais, aplicações SaaS e sites corporativos.

## Clonagem do repositório

Para obter uma cópia local do projecto, execute o seguinte comando no terminal:

```bash
git clone https://github.com/HutaDev/grood.git
```

Em seguida, aceda à pasta do projecto:

```bash
cd grood
```

Abra o ficheiro `index.html` no navegador ou num editor de código à sua escolha.


## Utilização da CDN de estilos

Este projecto utiliza folhas de estilo externas através de CDN para facilitar a manutenção e garantir carregamento rápido.

### Inserção correcta das CDNs

No ficheiro `index.html`, localize a secção `<head>` e adicione as seguintes ligações dentro dela:

```html
<!-- Estilos principais via jsDelivr -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/HutaDev/style@main/style.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/HutaDev/style@main/responsividade.css">
```

Estas CDNs devem ser inseridas antes da tag de encerramento `</head>`. Exemplo:

```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hero Section - Grood</title>

    <!-- Folhas de estilo externas -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/HutaDev/style@main/style.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/HutaDev/style@main/responsividade.css">
</head>
```

Estas folhas de estilo contêm as definições visuais principais e regras de responsividade utilizadas no layout da secção Hero.
