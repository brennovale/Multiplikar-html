# Multiplikar Automóveis

## Integrantes

- Andrey Azevedo Veloso
- Brenno Lima do Vale

## Introdução

A Multiplikar Automóveis é uma organização comercial do setor automotivo que atua na compra, venda, troca, consignação e intermediação financeira de veículos.  

O objetivo do portal desenvolvido é fornecer uma presença digital institucional consistente e acessível, apresentando de maneira clara e transparente o catálogo demonstrativo da loja, os critérios de avaliação técnica e laudo cautelar, os modelos de intermediação em consignação, as condições comerciais de venda e financiamento bancário, os procedimentos de atendimento em garantia pós-venda, além de canais diretos para envio de mensagens e requisição de propostas personalizadas.

## Sobre a organização

A Multiplikar Automóveis é uma empresa estabelecida no ramo automotivo, com sede localizada no bairro Vila São Geraldo. A empresa possui aproximadamente dois anos de atuação no mercado e conta com uma equipe formada por cerca de seis funcionários responsáveis pela condução das operações comerciais, vistorias técnicas e atendimento ao público.

As principais atividades operacionais da empresa compreendem:

- Venda de veículos novos, seminovos e usados;
- Compra de veículos de pessoas físicas;
- Veículos em consignação;
- Avaliação de veículos;
- Análise de laudos cautelares;
- Controle de estoque;
- Vendas à vista e financiadas;
- Pagamentos;
- Garantia;
- Indicações e comissões.

## Contato com a organização

O contato inicial e a articulação institucional com a Multiplikar Automóveis foram realizados por meio do integrante do grupo Brenno Lima do Vale, que atua profissionalmente na organização. Aproveitando esse vínculo direto, Brenno intermediou uma breve reunião com o proprietário da empresa.

Durante o encontro, o proprietário autorizou expressamente o grupo a desenvolver a atividade acadêmica tendo a Multiplikar Automóveis como objeto de estudo, prestando esclarecimentos fundamentais a respeito das rotinas operacionais, fluxo de compra e venda de automóveis, critérios de avaliação cautelar e parcerias bancárias vigentes.

Dados do registro da reunião:

- **Forma de contato:** Reunião presencial;
- **Data da reunião:** [28/09/2026];
- **Nome do proprietário entrevistado:** [Regis Umbelino];
- **Local da reunião:** Multiplikar Automóveis, bairro Vila São Geraldo;

## Desenvolvimento

O desenvolvimento da Entrega 1 seguiu rigorosamente os padrões de desenvolvimento voltados à semântica e boas práticas de estruturação em HTML5 puro:

- **Contato com a empresa e levantamento de informações:** A partir do contato articulado pelo integrante Brenno Lima do Vale com o proprietário, foram mapeadas as rotinas reais da loja no bairro Vila São Geraldo, abrangendo as formas de captação de veículos de pessoas físicas, os procedimentos de custódia em consignação, o funcionamento das avaliações e laudos cautelares, as parcerias financeiras com nove instituições bancárias e as diretrizes de garantia de dois meses em veículos elegíveis.
- **Organização das páginas:** O conteúdo foi distribuído em exatamente 10 páginas HTML temáticas e autônomas, interligadas por um menu de navegação global padronizado em todas as páginas, permitindo fluxo de navegação fluido e intuitivo para o usuário.
- **Decisões semânticas:** Em respeito aos princípios do HTML5 e à conformidade com as diretrizes do W3C, foram utilizadas as tags estruturais `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<figure>`, `<figcaption>` e `<footer>`. Cada página possui apenas um elemento `<h1>` lógico no topo de seu conteúdo principal, seguido por desdobramentos ordenados em `<h2>` e `<h3>`, sem salto de níveis de hierarquia. Para listas de etapas foram usados elementos `<ol>`, para itens descritivos `<ul>` e `<dl>`, e para dados tabulares foram estruturadas tabelas com `<caption>`, `<thead>`, `<tbody>`, `<tfoot>`, `<th>` e atributos `scope`.
- **Estruturação dos formulários:** Nas páginas `contato.html` e `orcamento.html`, foram desenvolvidos formulários funcionais em HTML. Todos os campos foram vinculados individualmente aos seus respectivos rótulos através de `<label for="...">` correspondendo a `id="..."`, organizados em blocos temáticos com `<fieldset>` e `<legend>`. Foram aplicados validadores nativos do HTML5, tais como `required`, `type="email"`, `type="tel"`, `type="number"`, `minlength`, `maxlength`, `autocomplete` e expressões regulares específicas via atributo `pattern` com `title` explicativo para números de telefone e documentos (CPF/CNPJ).
- **Incorporação de recursos multimídia:** Foram integrados elementos nativos `<audio>` e `<video>` providos do atributo `controls`, com subelementos `<source>` especificando o caminho relativo dos arquivos (organizados nas pastas `assets/audio/` e `assets/video/`) e mensagens de fallback para navegadores incompatíveis, além de imagens contendo descrições detalhadas no atributo `alt`.
- **Desafios técnicos enfrentados:** O principal desafio residiu na modelagem e integração dos fluxos operacionais e comerciais de uma organização real em uma arquitetura de dez páginas interconectadas. Isso demandou estruturar critérios rigorosos de validação nativa de dados via expressões regulares nos formulários (como formatos de CPF, CNPJ e telefones com DDD), organizar tabelas de dados técnicos e financeiros com acessibilidade adequada para leitores de tela e assegurar uma navegação totalmente consistente e intuitiva em toda a rede de links do portal.

## Estrutura do site

O projeto é constituído por exatamente 10 páginas HTML, distribuídas da seguinte forma:

1. **`index.html` (Página Inicial):** Apresenta o nome e a localização da Multiplikar Automóveis no bairro Vila São Geraldo, o tempo de atuação, tamanho da equipe, objetivos do portal, apresentação multimídia em áudio e vídeo da loja, síntese dos serviços prestados e chamadas para ação.
2. **`contato.html` (Contato e Localização):** Informações operacionais de atendimento, localização na Vila São Geraldo e formulário completo de contato com validação nativa em HTML5 (nome, CPF/CNPJ, telefone, e-mail, cidade, estado, assunto, mensagem, preferência de retorno e aceite).
3. **`orcamento.html` (Solicitação de Orçamento ou Proposta):** Formulário interativo para cotação e negociação de veículos contendo dados cadastrais, finalidade de atendimento (comprar, vender, trocar), veículo de interesse, valor disponível, veículo de entrada, formas de pagamento, preferência de estado do bem e termos de consentimento.
4. **`estoque.html` (Veículos Disponíveis):** Catálogo demonstrativo contendo aviso de conteúdo estrutural de exemplo, tabela comparativa com especificações completas (marca, modelo, ano, cor, km, combustível, câmbio, preço e situação) e fichas detalhadas em artigos individuais para cada veículo com imagens e links de proposta.
5. **`compra-veiculos.html` (Compra de Veículos de Clientes):** Explicação detalhada sobre a aquisição de automóveis pertencentes a pessoas físicas, análise de quilometragem, ano, motor, estrutura e documentação, relevância do laudo cautelar e tabela com matriz de aprovação e reprovação para compra direta.
6. **`consignacao.html` (Veículos em Consignação):** Detalhamento do modelo de intermediação e guarda de veículos, permanência da propriedade vinculada ao cliente até o desfecho da venda, preservação do valor líquido combinado, regras de repasse financeiro e tabela de situações da consignação.
7. **`avaliacao.html` (Avaliação e Laudo Cautelar):** Descrição das vistorias externa e interna, mecânica do motor, verificação de componentes de transmissão e suspensão, identificação técnica (ano, combustível, câmbio e quilometragem), checagem do laudo cautelar, indicação do avaliador responsável e tabela de pareceres finais.
8. **`vendas.html` (Processo de Vendas e Formas de Pagamento):** Abordagem sobre o atendimento consultivo, apresentação de veículos, possibilidades de entrada com veículo usado, registro contratual do cliente e funcionário responsável, detalhamento de valores, descontos, entrada, saldo restante e aceitação flexível de modalidades combinadas de pagamento (dinheiro, Pix, cartão e financiamento).
9. **`financiamento.html` (Financiamento e Instituições Parceiras):** Instruções sobre aquisições financiadas, parâmetros de contrato (valor financiado, parcelas, prazos, aprovação e situação), relação das 9 instituições financeiras parceiras (Itaú, BV, Bradesco, Daycoval, Santander, Banco PAN, C6 Bank, Safra e Volkswagen) e esclarecimento sobre a empresa registrar a aprovação sem controlar os pagamentos individuais das mensalidades.
10. **`garantia.html` (Garantia e Atendimento Pós-Venda):** Esclarecimentos sobre a cobertura de garantia de dois meses para veículos elegíveis, fluxo de abertura de chamados, perícia realizada por mecânicos qualificados, registro de diagnósticos, histórico de atendimentos e salvaguarda legal de cancelamento da compra e devolução quando aplicável.

## Conclusão

O desenvolvimento da Entrega 1 proporcionou uma compreensão aprofundada da importância primordial do HTML5 semântico como fundação de qualquer solução web. Ao abdicar de camadas de estilo e comportamentos programáticos em JavaScript, tornou-se evidente como elementos bem estruturados, tais como tags de seção, cabeçalhos hierárquicos, tabelas acessíveis e atributos nativos de validação de formulários, são capazes de conferir clareza, usabilidade e alta acessibilidade tanto para usuários convencionais quanto para tecnologias assistivas e mecanismos de busca.

O projeto permitiu exercitar a modelagem de dados comerciais de uma organização real, convertendo rotinas de atendimento, estoque, financiamento e pós-venda em documentos web padronizados, organizados e tecnicamente consistentes.
