# curriculoBasico
#  Roadmap de Estudos Front-End | Desafio 01: Currículo Semântico (HTML Only)

## Sobre o Projeto
Este projeto faz parte de uma das etapas fundamentais do meu Roadmap de estudos em desenvolvimento Front-End. O objetivo principal deste desafio é aplicar conceitos de **HTML5 Estrutural e Semântico** na criação de um Currículo Vitae (CV) de página única.

A proposta do desafio exige focar estritamente na estrutura e organização dos dados (dados pessoais, habilidades, educação e experiência), garantindo que o documento seja acessível, bem indexado e logicamente encadeado, deixando a estilização visual (CSS) para uma etapa posterior do Roadmap.

> **Status do Desafio:**  Concluído (Fase de Estruturação)

---

##  Objetivos de Aprendizado (Skills Praticadas)
* **Semântica HTML5:** Utilização correta de tags estruturais (`<header>`, `<main>`, `<footer>`).
* **Hierarquia de Títulos:** Organização de conteúdo utilizando a ordem lógica de `<h1>`, `<h2>`, `<h3>` e `<h4>`.
* **Agrupamento de Dados:** Uso de listas não ordenadas (`<ul>` e `<li>`) para exibição de competências e conquistas.
* **Separação de Escopos:** Criação de divisões limpas (`<div>`) com IDs e classes para futura manipulação de estilo.
* **Meta Tags e Responsividade:** Configuração inicial de `viewport` e `charset` no `<head>`.

---

##  Tecnologias Utilizadas
* **HTML5** (Linguagem de Marcação de Hipertexto)
* *Nota: O arquivo `style.css` já foi devidamente linkado no `<head>` para a próxima fase do roadmap, porém o foco atual manteve-se 100% na estrutura pura.*

---

##  Estrutura do Documento HTML
A arquitetura do arquivo `index.html` foi dividida nas seguintes seções:

1.  **Header (`<header>`)**: Bloco de identidade contendo o nome principal (`<h1>`), cargo atual e informações de contato (endereço, telefone e e-mail).
2.  **Main Content (`<main>`)**: O corpo central da página, segmentado em três grandes áreas:
    * **Skills (`.skill`)**: Listagem técnica de tecnologias, frameworks e ferramentas de design (Figma, Postman, MySQL, etc.).
    * **Education (`.education`)**: Histórico acadêmico com ênfase nos projetos práticos desenvolvidos no SESI (como o *HealthFlow*, criação de APIs e bancos de dados).
    * **Experience (`.experience`)**: Espaço reservado para o histórico profissional.
3.  **Footer (`<footer>`)**: Rodapé dedicado às redes profissionais e portfólios (LinkedIn e GitHub).

---

##  Como Visualizar o Projeto Localmente

Para rodar este projeto na sua máquina local, siga os passos abaixo:

1. Clone este repositório:
   ```bash
   git clone https://github.com/contatemurilodejesus/curriculoBasico.git
