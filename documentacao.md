# Documentação do Projeto FoodCam AI - Landing Page

Este documento detalha o projeto da Landing Page do FoodCam AI, incluindo sua finalidade, arquitetura, tecnologias utilizadas e um histórico das modificações realizadas.

## 1. O que é o Projeto?

A Landing Page do FoodCam AI é a página de entrada principal para o aplicativo FoodCam AI. Seu objetivo é apresentar o produto, suas funcionalidades e benefícios, capturar o interesse dos visitantes e direcioná-los para o cadastro ou download do aplicativo.

## 2. O que ele faz?

A Landing Page:
*   Apresenta o conceito do FoodCam AI.
*   Destaca as principais funcionalidades e como o aplicativo funciona.
*   Exibe depoimentos de usuários.
*   Fornece informações de contato e links para políticas legais.
*   Serve como um ponto de conversão para novos usuários.

## 3. Arquitetura e Tecnologias

A Landing Page é construída com tecnologias web padrão, focando na simplicidade e desempenho para uma experiência de usuário rápida e responsiva.

*   **HTML5:** Estrutura semântica da página.
*   **CSS (Tailwind CSS):** Framework CSS para estilização rápida e responsiva. O Tailwind CSS é incluído via CDN.
*   **JavaScript:** Para funcionalidades interativas básicas, como navegação suave e menu mobile.
*   **Fontes:** Google Fonts ('Inter' para o corpo do texto e 'Pacifico' para o logo, embora o logo agora use 'Inter' em negrito para um visual mais moderno).
*   **Ícones:** Remixicon.
*   **Imagens:** Imagens de mockup e ilustrações são carregadas de serviços externos (readdy.ai).

A arquitetura é de uma Single Page Application (SPA) estática, onde todo o conteúdo é carregado inicialmente, e a navegação entre seções é feita via rolagem suave (scroll-to-anchor).

## 4. Histórico de Alterações

Este é um registro das principais modificações realizadas no projeto:

*   **28 de Maio de 2025 - Implementação Inicial e Otimizações:**
    *   **Adição de Ferramentas de Análise:**
        *   Google Analytics (GA4) snippet adicionado ao `<head>` de `Landing-Page.html`.
        *   Facebook Pixel snippet adicionado ao `<head>` de `Landing-Page.html`.
    *   **Atualização da Marca:**
        *   Nome "FoodCam" alterado para "FoodCam AI" no título da página, cabeçalho e rodapé de `Landing-Page.html`.
        *   Fonte do logo "FoodCam AI" atualizada para 'Inter' em negrito em `Landing-Page.html` e `sobre-nos.html`, `Politicas-de-Privacidade.html`, `termos-de-uso.html`, `Politicas-de-Cookies.html`, `lgpd.html` para corresponder ao formato da imagem fornecida.
    *   **Remoção de Conteúdo:**
        *   Links "Blog", "Imprensa" e "Guias Nutricionais" removidos do rodapé de `Landing-Page.html`.
    *   **Atualização de Contato:**
        *   Emails foodcamai@gmail.com e contato@lm7upgrade.com.br adicionados à seção de suporte no rodapé de `sobre-nos.html`.
    *   **Criação/Preenchimento de Páginas Legais:**
        *   Conteúdo genérico adicionado a `Politicas-de-Privacidade.html`, `termos-de-uso.html`, `Politicas-de-Cookies.html` e `lgpd.html`.
    *   **Otimização de Links e Botões:**
        *   Todos os botões de chamada para ação (`Experimente Grátis`, `Saiba Mais`, `Experimente Agora`, `Experimente o FoodCam AI`, `Crie Sua Conta`) na `Landing-Page.html` foram atualizados para direcionar para `https://foodcamai.com/auth`.
*   **Janeiro de 2025 - Atualização de Links da Aplicação:**
    *   Todos os botões que direcionam para o aplicativo foram atualizados para `https://oficial.foodcamai.com` em todos os arquivos HTML do projeto (`index.html`, `Landing-Page.html`, `sobre-nos.html`, `termos-de-uso.html`, `Politicas-de-Privacidade.html`, `Politicas-de-Cookies.html`, `lgpd.html`).

*   **Janeiro de 2025 - Correção de Problemas Tipográficos e de Formatação:**
    *   **Resolução de Conflitos de Git:** Removidos todos os marcadores de conflito de merge (`<<<<<<< HEAD`, `=======`, `>>>>>>> hash`) que estavam aparecendo no cabeçalho das páginas.
    *   **Correção de Formatação Tipográfica:** Convertida toda formatação Markdown incorreta (`**texto**`) para HTML apropriado (`<strong>texto</strong>`) nas páginas de políticas legais.
    *   **Limpeza do Favicon:** Corrigidos links duplicados e conflitantes do favicon em todos os arquivos HTML.
    *   **Tipografia Profissional:** Garantida uma apresentação limpa e profissional em todas as páginas, removendo caracteres de formatação indevidos.
        *   Botões de download "App Store" e "Google Play" removidos da `Landing-Page.html` para simplificar o design.
        *   Sobrenomes dos depoimentos (`Gabriela Martins`, `Rafael Oliveira`, `Carolina Santos`) removidos, deixando apenas o primeiro nome (`Gabriela`, `Rafael`, `Carolina`).
        *   Link "Sobre Nós" no rodapé de `Landing-Page.html` corrigido para `sobre-nos.html`.

*   **Janeiro de 2025 - Otimização do Footer e Informações de Suporte:**
    *   **Adição de Emails de Suporte:** Incluídos os emails `foodcamai@gmail.com` e `contato@lm7upgrade.com.br` na seção "Recursos" do footer em `index.html` e `Landing-Page.html`.
    *   **Melhorias na Estrutura do Footer:** Ajustada a estrutura do copyright e ícones de pagamento para melhor alinhamento e responsividade.
    *   **Padronização de Footers:** Todos os footers das páginas legais (`termos-de-uso.html`, `Politicas-de-Privacidade.html`, `Politicas-de-Cookies.html`, `lgpd.html`) foram padronizados com a mesma estrutura da página principal, incluindo:
        *   Redes sociais (Instagram, Facebook, Twitter/X, YouTube)
        *   Emails de suporte organizados em seção própria
        *   Ícones de pagamento (Visa, Mastercard, PayPal, Apple Pay)
        *   Melhor alinhamento responsivo e estrutura visual consistente
    *   **Unificação de Landing Pages:** Eliminada a duplicação entre `index.html` e `Landing-Page.html`:
        *   Arquivo `Landing-Page.html` removido para evitar conteúdo duplicado
        *   Todas as navegações de páginas legais agora direcionam para `index.html`
        *   Melhor consistência de navegação e experiência do usuário
        *   Eliminação de problemas de responsividade conflitantes entre as duas versões
    *   **Atualização da Documentação:** README.md completamente reescrito com instruções detalhadas de como executar o projeto, tecnologias utilizadas e comandos úteis.

*   **13 de Junho de 2025 - Atualizações na Seção de Vídeo e Conteúdo:**
    *   **Adição de Frase de Expectativa:**
        *   Frase "Expectativa para os próximos anos" adicionada abaixo da seção de vídeo na `index.html`.
    *   **Incorporação de Vídeo do YouTube:**
        *   O placeholder de vídeo (tag `<video>` com `poster`) na `index.html` foi substituído por um `iframe` para incorporar um vídeo do YouTube (`https://www.youtube.com/embed/9Z2Xv_Nl4Do`).
        *   A incorporação utiliza CSS inline (`style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden;"` no contêiner e `style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"` no iframe) para manter a proporção 16:9 e garantir que o vídeo preencha o espaço designado.
    *   **Atualização de Depoimento:**
        *   O texto do depoimento da "Carolina" na `index.html` foi alterado para focar no alcance de resultados através do monitoramento de alimentos e na menor necessidade de usar balança.
    *   **Remoção de Funcionalidade:**
        *   O card da funcionalidade "Alertas de Alérgenos" foi removido da seção "Funcionalidades" na `index.html`, pois o serviço ainda não está disponível.

## 5. Manutenção e Atualizações

É crucial manter esta documentação atualizada. **Após cada alteração significativa no código ou na estrutura do projeto, este documento deve ser revisado e atualizado** para refletir as novas modificações, tecnologias ou decisões de arquitetura. Isso garante que a documentação permaneça uma fonte de informação precisa e útil para todos os envolvidos no projeto.
