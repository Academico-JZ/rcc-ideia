# StudyVet — Portal de Apoio aos Estudos em Medicina Veterinária

Trabalho prático desenvolvido na disciplina de **Desenvolvimento Web I (RCC0218)**  
**Curso:** Tecnologia em Redes de Computadores — IFC Campus Araquari  
**Estudante:** Jairuzalôn Maguidiel Vieira  

---

## 1. Sobre o Projeto

O **StudyVet** é um portal educativo estático criado com HTML5 semântico e CSS3 (Flexbox). O objetivo principal é disponibilizar resumos organizados, materiais de estudo e questões de revisão das disciplinas da graduação em Medicina Veterinária (como Imunologia, Fisiologia e Patologia), auxiliando os estudantes a encontrar o conteúdo de forma rápida e visual.

---

## 2. Estrutura do Site (Mapa de Páginas)

O portal é composto por 4 páginas interligadas através do menu de navegação:

- **Início (`index.html`):** Apresentação do portal, visão geral dos temas e destaques rápidos de matérias.
- **Biblioteca de Conteúdos (`conteudos.html`):** Resumos por tópicos com cards organizados via Flexbox.
- **Casos e Exercícios (`pratica.html`):** Questões de fixação e estudo de casos clínicos introdutórios.
- **Contato e Dúvidas (`contato.html`):** Formulário de envio de dúvidas e sugestões com validação nativa de campos do HTML5.

---

## 3. Tecnologias Utilizadas na Versão 1

- **HTML5 Semântico:** Uso correto de tags estruturais (`header`, `nav`, `main`, `section`, `article`, `figure`, `footer`).
- **CSS3 Moderno:** Layout construído com Flexbox, espaçamentos padronizados com `gap`, tipografia com Google Fonts e estilização responsiva para desktop, tablet e celular.
- **Acessibilidade básica:** Atributos `alt` em imagens e labels vinculados a inputs no formulário.

---

## 4. Funcionalidades Planejadas para a Versão 2 (JavaScript)

Conforme os critérios da disciplina, as seguintes funcionalidades interativas estão planejadas para implementação futura em JavaScript:

| Funcionalidade | Página | Elementos Envolvidos | Ação do Usuário | Comportamento Esperado |
| :--- | :--- | :--- | :--- | :--- |
| **Filtro de Disciplinas** | `conteudos.html` | Botões de filtro e cards | Clicar no botão da matéria (ex: Imunologia) | Exibir apenas os cards da matéria escolhida, ocultando as demais. |
| **Validação Interativa do Formulário** | `contato.html` | Formulário e mensagens de erro | Clicar em enviar | Checar se os campos obrigatórios estão preenchidos antes do envio e exibir alerta amigável. |
| **Alternador de Tema (Modo Escuro)** | Todas as páginas | Botão no cabeçalho e classe no `body` | Clicar no botão de alternar tema | Alternar as cores de fundo e texto entre modo claro e modo escuro. |

---

## 5. Como Executar Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/Academico-JZ/rcc-ideia.git
   ```
2. Abra a pasta do projeto no VS Code.
3. Abra o arquivo `index.html` com a extensão **Live Server** ou diretamente no seu navegador.
