# Importação por CSV

CSV é indicado para adicionar muitos itens de uma vez.

## Quando usar

Use CSV quando:

- você já tem dados em planilha;
- precisa importar muitos registros;
- quer padronizar preenchimento em lote;
- vai revisar os dados antes de publicar.

## Estrutura do arquivo

Um CSV é uma tabela em texto. A primeira linha contém os nomes das colunas, e cada linha seguinte representa um item.

Exemplo:

```csv
Nome,Cidade,Site,Tags
Biblioteca Aurora,São Paulo,https://exemplo.org,leitura;comunidade
Casa de Cultura Norte,Recife,https://exemplo.org/cultura,cultura;formação
```

## Preparar arquivo

1. Baixe ou copie o modelo da lista.
2. Mantenha os nomes das colunas iguais aos campos.
3. Preencha uma linha por item.
4. Revise caracteres especiais, datas, números e links.
5. Salve como `.csv`.

## Mapear colunas

Cada coluna deve corresponder a um campo da lista. Se uma coluna não tem campo equivalente, decida antes se ela deve:

- virar um novo campo;
- ser incorporada a uma descrição;
- ser descartada;
- virar relação com outra lista.

## Cuidados

- Não altere o cabeçalho sem ajustar a lista.
- Evite células mescladas.
- Use formatos consistentes para datas e números.
- Para tags, mantenha separadores consistentes.
- Para relações, use o mesmo rótulo exibido na lista relacionada.

## Conferência antes do envio

Abra o arquivo em um editor de texto ou planilha e confira:

- se acentos aparecem corretamente;
- se não há colunas vazias sem necessidade;
- se cada linha tem a mesma quantidade de colunas;
- se links começam com `http://` ou `https://`;
- se datas seguem o mesmo padrão;
- se campos obrigatórios estão preenchidos.

## Após enviar

Depois do upload, acompanhe o resultado. Se houver erro, corrija o arquivo e envie novamente.

Quando a lista exige revisão, itens importados podem ficar pendentes antes de aparecer para todos.

## Erros comuns

| Problema | Como resolver |
| --- | --- |
| Cabeçalho diferente do campo | Renomeie a coluna ou ajuste o campo da lista. |
| Data em formatos misturados | Padronize antes de importar. |
| Relação não encontrada | Confira se o item relacionado já existe e se o nome está igual. |
| Texto quebrado por vírgulas | Use exportação CSV adequada no editor de planilhas. |
| Duplicidade | Pesquise a lista antes de importar um lote grande. |
