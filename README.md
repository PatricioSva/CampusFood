# CampusFood 🍽️

**Protótipo acadêmico de consulta de alimentação universitária**, desenvolvido durante a graduação em Ciência da Computação no UNIESP.

O CampusFood reúne, em uma interface simples, estabelecimentos, cardápios e produtos organizados por categoria e faixa de preço. A proposta é ajudar o estudante a encontrar opções de alimentação e consultar informações antes de escolher onde comer.

## Funcionalidades

- Página inicial com estabelecimentos em destaque.
- Três cardápios demonstrativos: Cantina Central, Café Universitário e Restaurante Campus.
- Categorias **Até R$ 10**, **Almoço**, **Café**, **Lanches**, **Doces** e **Bebidas**.
- Navegação entre páginas e seções por links e âncoras.
- Layout adaptável a desktop e celular com CSS Grid, Flexbox e media queries.
- Tela de login **demonstrativa** (sem autenticação ou armazenamento de credenciais).

> **Aviso:** este projeto é um protótipo acadêmico. Estabelecimentos, localizações, avaliações, horários, preços e disponibilidade são **dados ilustrativos**, não informações oficiais nem atualizadas em tempo real. A seleção de categorias utiliza âncoras e a pseudoclasse CSS `:target`; não realiza consultas a banco de dados.

## Tecnologias

- **HTML5:** estrutura semântica, navegação, formulários e organização dos conteúdos.
- **CSS3:** identidade visual, componentes, layout responsivo e exibição de categorias via `:target`.
- **Sem JavaScript**, conforme a proposta acadêmica desta versão.

## Executar localmente

1. Baixe ou clone este repositório.
2. Abra o arquivo `index.html` no navegador. Não é necessário instalar dependências.
3. Opcionalmente, abra a pasta no VS Code e utilize a extensão **Live Server**.

## Estrutura

```text
CampusFood/
├── index.html
├── Cardápio/
│   ├── cardapio.html
│   ├── cafe-universitario.html
│   └── restaurante-campus.html
├── Estabelecimentos/
│   └── estabelecimentos.html
├── paginas/
│   ├── categorias.html
│   └── login.html
└── css/
    ├── style.css
    ├── cardapio.css
    ├── categorias.css
    └── estabelecimentos.css
```

## Decisões de implementação

- Arquivos CSS específicos complementam o `style.css` para facilitar a manutenção.
- Links relativos permitem abrir as páginas localmente ou hospedá-las em um site estático.
- A página de categorias utiliza `:target` para mostrar o grupo selecionado sem JavaScript.
- O formulário de login existe somente para demonstração de interface. **Não realiza login real.**
- Produtos e preços são mantidos manualmente nos arquivos HTML, sem atualização automática.

## Próximas melhorias

- Substituir dados fictícios por informações autorizadas e verificadas.
- Centralizar cadastro de produtos e preços em uma fonte de dados.
- Implementar pesquisa e autenticação reais, se o escopo futuro permitir tecnologias adicionais.
- Aprimorar acessibilidade, testes de navegação e interface mobile.

## Créditos

**Liderança, arquitetura e desenvolvimento principal:** Alysson Henrique Patrício da Silva ([@PatricioSva](https://github.com/PatricioSva)).

**Equipe acadêmica:** Ana Lúcia, Bya, João Vitor, Neto e Samuel.

Desenvolvido como atividade acadêmica no **UNIESP**. Os créditos acima não atribuem tarefas técnicas específicas aos demais integrantes.
