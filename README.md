# 🗺️ Mapa da Coleta Seletiva - Altos do Indaiá

**Status:** Concluído | **Versão:** 1.0.0 | **Licença:** MIT

Um mapa interativo e colaborativo para localizar pontos de coleta seletiva no bairro Altos do Indaiá em Dourados/MS. Este projeto foi desenvolvido como uma ferramenta prática para fortalecer a cultura da reciclagem na comunidade.

---

### Tabela de Conteúdos
1.  [Sobre o Projeto](#sobre-o-projeto)
    - [A Necessidade da Reciclagem](#a-necessidade-da-reciclagem)
    - [Conexão com os Objetivos de Desenvolvimento Sustentável (ODS)](#conexão-com-os-objetivos-de-desenvolvimento-sustentável-ods)
2.  [Funcionalidades](#funcionalidades)
3.  [Tecnologias Utilizadas](#tecnologias-utilizadas)
4.  [Como Utilizar](#como-utilizar)
5.  [Autor](#autor)
6.  [Licença](#licença)

---

## Sobre o Projeto

A gestão de resíduos sólidos é um dos grandes desafios urbanos do século XXI. Muitas vezes, a boa vontade dos cidadãos em separar seus resíduos recicláveis esbarra na falta de informação sobre onde descartá-los corretamente.

Este projeto nasceu para ser a ponte entre o cidadão e o descarte correto. Através de uma interface simples e intuitiva, o mapa permite que qualquer pessoa encontre o ponto de coleta mais próximo de sua casa, incentivando a prática da reciclagem e contribuindo para um bairro mais limpo e sustentável.

Esta aplicação foi concebida como um **Projeto de Extensão (PEX)** do curso de **Engenharia da Computação**, com o objetivo de aplicar conhecimentos acadêmicos na criação de uma solução tecnológica com impacto social e ambiental positivo.

### A Necessidade da Reciclagem
A reciclagem é um pilar fundamental da sustentabilidade por diversas razões:
-   **Reduz o volume de lixo** enviado para aterros sanitários, aumentando sua vida útil e diminuindo o impacto ambiental.
-   **Conserva recursos naturais**, como madeira, água e minerais, ao reintroduzir materiais no ciclo produtivo.
-   **Economiza energia** e reduz a emissão de gases de efeito estufa, uma vez que produzir a partir de materiais reciclados consome menos energia do que a partir de matéria-prima virgem.
-   **Gera renda** para milhares de pessoas que trabalham em cooperativas de catadores e na indústria da reciclagem.

### Conexão com os Objetivos de Desenvolvimento Sustentável (ODS)
Este projeto está diretamente alinhado com a Agenda 2030 da ONU e contribui para os seguintes ODS:

* **ODS 11: Cidades e Comunidades Sustentáveis**
    > Ao fornecer uma ferramenta que melhora a gestão de resíduos sólidos urbanos e promove a participação cidadã na manutenção de um ambiente mais limpo e organizado.

* **ODS 12: Consumo e Produção Responsáveis**
    > Ao incentivar e facilitar a prática da reciclagem, um componente essencial para a transição para uma economia circular, onde o desperdício é minimizado e os recursos são aproveitados ao máximo.

## Funcionalidades
-   ✅ **Mapa Interativo:** Visualização de todos os pontos de coleta georreferenciados no bairro.
-   ℹ️ **Detalhes dos Pontos:** Informações sobre endereço e tipos de materiais aceitos em cada local.
-   ➕ **Sugestão Colaborativa:** Usuários podem sugerir novos pontos de coleta através de um formulário.
-   📍 **Ajuste Fino da Localização:** Um mapa de ajuste com pino arrastável permite que o usuário defina a localização exata da sua sugestão.
-   💾 **Persistência de Dados:** Por ser penas um protótipo, nesta fase as sugestões enviadas ficam salvas no navegador do usuário (`localStorage`).
-   🗑️ **Remoção de Sugestões:** É possível remover sugestões pendentes de aprovação.
-   📱 **Interface Responsiva:** Funciona de forma otimizada em desktops, tablets e celulares.

## Tecnologias Utilizadas
Este projeto foi construído utilizando tecnologias modernas de desenvolvimento front-end:
-   **HTML5**
-   **CSS3** com **Bootstrap 5**
-   **JavaScript (ES6+)**
-   **Leaflet.js** para o mapa interativo
-   **OpenStreetMap** como provedor dos dados do mapa
-   **Font Awesome** para os ícones

## Como Utilizar
Como este projeto é um arquivo HTML único e autocontido, não há necessidade de um servidor web ou processo de build.

1.  Faça o download do arquivo `index.html`.
2.  Abra o arquivo em qualquer navegador de internet moderno (Google Chrome, Firefox, etc.).
3.  A aplicação carregará e estará pronta para uso.

## Autor
Projeto idealizado e desenvolvido por **Carlos Henrique C. Oliveira** como parte das atividades de Projeto de Extensão do curso de Engenharia da Computação.

## Licença
Distribuído sob a Licença AGPL. Veja o arquivo `LICENSE` para mais informações.
