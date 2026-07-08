# Listas

Uma lista é a unidade principal do OOInfo. Ela reúne itens de um mesmo assunto e define como esses itens devem ser preenchidos, exibidos e compartilhados.

## Quando criar uma lista

Crie uma lista quando você tiver muitos registros parecidos. Por exemplo:

- diretório de instituições;
- catálogo de cursos;
- biblioteca de materiais;
- agenda de eventos;
- base de projetos;
- lista de contatos públicos.

## Antes de montar

Uma lista funciona melhor quando cada item representa uma coisa do mesmo tipo. Evite misturar assuntos diferentes no mesmo lugar.

| Se você quer registrar | Melhor modelagem |
| --- | --- |
| Livros e autores | Uma lista de livros e outra de autores, conectadas por relação. |
| Eventos e participantes | Uma lista de eventos e outra de pessoas ou inscrições. |
| Instituições e projetos | Uma lista de instituições e outra de projetos relacionados. |
| Documentos e categorias | Uma lista de documentos com campo de categoria ou relação. |

## Estrutura recomendada

Uma boa lista tem:

- nome claro;
- descrição curta;
- campos bem definidos;
- visualização adequada ao público;
- regras de visibilidade e contribuição.

## Nome e descrição

O nome deve dizer o que a lista contém. A descrição deve explicar o recorte.

Bom exemplo:

```text
Nome: Bibliotecas Comunitárias
Descrição: Espaços de leitura comunitários com endereço, formas de contato e atividades públicas.
```

Evite nomes genéricos como "Dados", "Cadastro" ou "Base geral".

## Visibilidade

A visibilidade controla quem pode ver a lista. Escolha a opção mais restrita que ainda permita o uso desejado.

| Opção | Quando usar |
| --- | --- |
| Pública | Quando qualquer pessoa pode consultar os dados. |
| Usuários logados | Quando a lista deve ficar disponível somente para contas autenticadas. |
| Privada | Quando o conteúdo é restrito a pessoas convidadas. |

## Permissões de trabalho

Além da visibilidade, pense em quem pode trabalhar na lista:

- **Leitores** consultam o conteúdo.
- **Colaboradores** sugerem ou inserem dados.
- **Revisores** avaliam mudanças quando há fluxo de revisão.
- **Gestores da lista** ajustam estrutura, campos, visualizações e regras.

## Visualizações

Use a visualização de acordo com a tarefa:

- **Tabela** para comparar muitos campos.
- **Cards** para navegação visual.
- **Galeria** para conteúdos com imagens.
- **Documento** para leitura contínua.
- **Hierarquia** para categorias e estruturas em árvore.
- **Mapa de relações** para explorar conexões.

## Organização por categorias

Use categorias quando o público precisa navegar por temas. Use tags quando a classificação é mais livre e pode ter várias palavras-chave por item.

## Sinais de uma lista bem construída

- Usuários entendem o objetivo pelo nome e pela descrição.
- Itens diferentes usam os mesmos campos de forma consistente.
- Filtros principais aparecem sem depender de texto livre.
- A visualização principal combina com a tarefa mais comum.
- Regras de contribuição estão claras para quem participa.
