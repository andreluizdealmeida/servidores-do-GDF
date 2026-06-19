# SPA Jurídica de Alta Conversão (Tailwind CSS/JS Vanilla)

Repositório da Landing Page responsiva desenvolvida para o nicho jurídico, especificamente focada na captação de leads (servidores do GDF) impactados pela Operação Juros Zero. O projeto prioriza o **Mobile-First** e o carregamento instantâneo.

## ⚙️ Características do Projeto

O desenvolvimento seguiu a premissa de **Zero Configuração de Build**, permitindo que a página seja hospedada instantaneamente em serviços como GitHub Pages, Netlify ou Vercel apenas realizando o upload do arquivo `index.html`.

* **Arquitetura:** Single Page Application (SPA) em arquivo único.
* **Estilização:** Utilização do **Tailwind CSS via Play CDN**, permitindo o uso de classes utilitárias e design responsivo diretamente no HTML, sem necessidade de configuração do PostCSS ou instalação de dependências Node.js.
* **Responsividade:** Design adaptativo testado para breakpoints de smartphones modernos, tablets e desktops.
* **Interatividade:** JS Vanilla leve para manipulação do FAQ e geração de links parametrizados para o WhatsApp.
* **Assets:** Imagens integradas localmente (geradas via IA para o tema "Legal/Audit Brasília twilight").

## 🛠️ Stack Tecnológica

* HTML5 Semântico
* Tailwind CSS v3+ (via CDN)
* JavaScript (ES6+)
* FontAwesome (Ícones)

## 🔧 Configuração e Deploy

Para colocar a página no ar e configurá-la para o seu funil de atendimento:

1.  Clone o repositório.
2.  Edite o arquivo `index.html`.
3.  Altere a constante `const numeroWhatsApp = "5562994030708";` para o seu número final de atendimento (com DDI/DDD e sem formatação).
4.  Hospede o arquivo `index.html` em qualquer servidor web estático.

## ⚖️ Conformidade e LGPD

O código inclui placeholders e selos visuais para **conformidade blindada** com a Lei Geral de Proteção de Dados (LGPD) e o Provimento 205/2021 do Conselho Federal da OAB, vital para operações de marketing jurídico.
