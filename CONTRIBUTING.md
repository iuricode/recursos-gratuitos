# Como contribuir?

Este é um projeto totalmente livre que aceita contribuições via pull requests no GitHub. Este documento tem a responsabilidade de alinhar as contribuições de acordo com os padrões estabelecidos no mesmo. Em caso de dúvidas, [abra uma issue](https://github.com/iuricode/recursos-gratuitos/issues/new).

## Passos

1. Crie um fork deste repositório.
2. Adicione os links de acordo com o estilo padronizado neste guia.
3. Verifique se o recurso é realmente gratuito e se o link abre.
4. Envie seus commits em português.
5. Insira um pequeno resumo sobre o que foi adicionado.
6. Solicite um pull request.

## O que pode entrar

- O recurso precisa ser gratuito. Se só parte dele for gratuita, deixe isso claro no resumo do pull request.
- Não adicione conteúdo pirata nem que viole direitos autorais.
- Não repita um recurso que já está na lista. Procure pelo nome e pelo endereço antes de adicionar.

## Como adicionar um link

Todo o conteúdo fica em [`materiais/readme.md`](materiais/readme.md). Cada categoria é uma tabela, com um recurso por linha e em **ordem alfabética**. Para adicionar, acrescente uma linha na posição correta:

```md
| [Nome do recurso](https://exemplo.com/) | <img src="../imagem/eua.png" width="28" height="20" alt="Inglês"> |
```

- Para um recurso em português, use `../imagem/br.png` e `alt="Português"`.
- Em **Cursos**, use a tabela _Cursos e plataformas_ e informe na coluna **Certificado** se há certificado (`Sim` ou `Não`).
- Canais do YouTube entram na tabela _Canais do YouTube_, dentro de **Cursos**.

## Estilo dos links

Um link precisa ser adicionado em sua forma mais autêntica, isso é:

- Você não pode adicionar encurtadores de links.
- Você não pode adicionar redirecionadores (mesmo que da própria aplicação).
- Você não pode adicionar links de afiliados (ou com parâmetros rastreadores).

Para manter um padrão geral em todos os links, você deve:

- Adicionar um link direto para o conteúdo.
- Adicionar um título condizente ao título do conteúdo.
- Adicionar uma bandeira (português ou inglês) para simbolizar o idioma do link.

## Recomendação (opcional)

Para uma melhor semântica nos commits, recomendamos nosso repositório sobre [padrões de commits](https://github.com/iuricode/padroes-de-commits). Assim ficará mais fácil para avaliar seu pull request.
