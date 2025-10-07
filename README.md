# ic-av1-cfc: Circular Connect
## Projeto AV 1 - Cesar School

A Circular Connect é uma plataforma fictícia de Economia Circular que conecta estabelecimentos geradores de resíduos orgânicos (como restaurantes e indústrias) a transformadores (como composteiras e startups de bioeconomia). Nosso objetivo é transformar o que seria desperdício em novos recursos e valor econômico. Este site foi construído seguindo os princípios de HTML semântico, CSS puro e acessibilidade básica.

### Autores e Papéis

Dev 1 – Estrutura e Acessibilidade (HTML): Henrique
Dev 2 – Layout e Componentes (Flex, cards): Pedro
Dev 3 – Estilo e Documentação (Paleta, tipografia, README, otimização de imagens): Luis

### Paleta de Cores e Tipografia

Paleta de Cores (Definidas em :root)
Variável CSS | Cor (Hexadecimal) | Uso Principal
`--color-primary` | `#38761D` | Verde Principal, Títulos, Botões de CTA 
`--color-secondary` | `#6AA84F` | Verde Secundário, Links Hover, Borda de Títulos 
`--color-accent` | `#B6854D` | Laranja/Marrom de Destaque, Preços 
`--color-text` | `#333333` | Cor de Texto Padrão, Fundo do Footer 
`--color-background` | `#F8F8F8` | Fundo de Seções Claras 
`--color-light` | `#FFFFFF` | Fundo de Header, Texto do Hero 

Fontes Usadas (Google Fonts)
Títulos (`--font-heading`): 'Roboto', sans-serif
Corpo (`--font-body`): 'Open Sans', sans-serif

### Decisões de Design/Código

1. Uso de Variáveis CSS (`:root`): Implementamos a paleta de cores completa utilizando variáveis CSS, o que garante a coesão visual e facilita futuras manutenções.
2. Design Responsivo (Desafio Bônus): Implementação de `media queries` em 900px e 768px para adaptar o layout (empilhamento de cards, menu de navegação e ajustes de fonte), garantindo a acessibilidade em dispositivos móveis.
3. Semântica HTML e Acessibilidade: Uso rigoroso de `<header>`, `<main>`, `<nav>` e `<footer>`, e aplicação de `alt` em todas as imagens, priorizando a ordem lógica de títulos (`h1` a `h3`).

### Como Abrir o Projeto

Basta abrir o arquivo `index.html` em qualquer navegador.

### Checklist (copiar a seção do item 8 preenchida)

Item | Status 
[x] 3 páginas mínimas (Home/Sobre/Contato) + links funcionando. | OK 
[x] `header`, `nav`, `main`, `footer` usados com propósito. | OK 
[x] Hero na página principal | OK 
[x] Tabela simples presente. | OK 
[x] Paleta no :root (variáveis CSS). | OK 
[x] Google Fonts. | OK 
[x] Imagens otimizadas com alt descritivo. | OK 
[x] README com papéis, paleta, fontes e decisões. | OK 
[x] Site no ar. | OK 
