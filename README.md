# Nightfall — Halloween

Projeto acadêmico do segundo semestre de 2026. Site temático que apresenta história, símbolos, tradições e curiosidades sobre o Halloween. A proposta exercita organização de conteúdo, uso do grid e integração de componentes interativos do Bootstrap.

## Tecnologias

HTML5, Bootstrap 5.3.8, JavaScript e Font Awesome. As dependências utilizadas estão incluídas localmente.

## Recursos

- Menu com navegação por seções e dropdown de países.
- Carrossel de imagens com controles.
- Popovers explicativos nos símbolos, acionados por clique.
- Galeria com três modais.
- Accordion de curiosidades.
- Grid e menu com classes responsivas do Bootstrap.

O campo de pesquisa é um elemento visual e ainda não realiza buscas.

## Como executar

Baixe o ZIP, extraia e abra `index.html` em um navegador moderno. Não é necessário instalar dependências.

Após a publicação no repositório proposto, será possível usar estes comandos.

```bash
git clone https://github.com/Gustass-dark/nightfall-halloween.git
cd nightfall-halloween
```

Abra `index.html` ou, com Python 3 instalado, execute `python -m http.server 8000` e acesse http://localhost:8000.

## Arquivos

| Caminho | Finalidade |
| --- | --- |
| `index.html` | Entrada principal adicionada para hospedagem estática |
| `nightfall.html` | Página original |
| `css/` | Estilos distribuídos pelo Bootstrap |
| `js/` | Scripts distribuídos pelo Bootstrap |
| `fontawesome/` | Ícones, fontes e licença da dependência |
| `img/` | Seis imagens do projeto |
| `codigo nightfall.txt` | Cópia original do código |

## Conferência e demonstração

Os caminhos locais das imagens, CSS e scripts e os destinos das âncoras e componentes foram conferidos estaticamente. A criação de index.html corrigiu o destino do link do logo.

## Demonstração visual

![Página em desktop](docs/desktop.png)

[Captura em celular](docs/mobile.png)

## Autoria e licença

Todo o código autoral do site foi desenvolvido por Gustavo Mesquita, incluindo a estrutura HTML e a integração dos componentes. Bootstrap e Font Awesome são dependências de terceiros, com autoria e licenças próprias.

O código autoral está sob licença MIT, disponível em LICENSE. Bootstrap e Font Awesome mantêm seus avisos de licença originais. O arquivo `fontawesome/LICENSE.txt` acompanha a distribuição. Segundo Gustavo Mesquita, as imagens dos sites foram geradas com inteligência artificial, incluindo o Adobe Firefly. A ferramenta específica usada para cada arquivo não foi individualizada. As imagens e não estão incluídas na licença MIT do código.

## Organização do GitHub

Nome proposto `nightfall-halloween`. Topics sugeridos `html`, `css`, `bootstrap`, `javascript`, `halloween`, `projeto-academico`.

A preparação acrescentou index.html, README.md e .gitignore ao material recebido.

## Verificação em navegador

Página carregada em Chromium nas larguras de 1440 e 390 pixels, com imagens disponíveis, sem erros JavaScript e sem transbordamento horizontal na largura de celular testada.
Menu mobile, popovers, modal da galeria e accordion foram acionados com sucesso. Alguns emojis aparecem como quadrados nas capturas devido às fontes do ambiente de teste.
