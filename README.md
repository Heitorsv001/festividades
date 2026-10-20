# Festividades de Fim de Ano

Site informativo sobre o Ano Novo Chinês, desenvolvido com HTML, CSS e JavaScript. O projeto apresenta tradições, celebrações e personagens culturais em páginas estáticas conectadas por links.

[Acessar o site](https://heitorsv001.github.io/festividades/) · [Repositório original](https://github.com/Heitorsv001/festividades)

## Conteúdo e navegação

- Página inicial com apresentação do tema e menu para as demais páginas.
- Celebrações e atividades: ceia da véspera, zodíaco e Festival das Lanternas.
- Organização: informações sobre a ceia e o roteiro das comemorações.
- Personalidades: Nian, Deus da Cozinha e Imperador de Jade.
- Página com links para vídeos externos no YouTube.
- Formulário de contato com campos obrigatórios, tipo de entrada para e-mail, limites de caracteres e botão de limpeza.

O formulário envia seus campos por GET para `processa.html`. Essa página carrega `js/script.js`, que exibe um alerta e redireciona para a página inicial. Trata-se de uma simulação: não há envio de e-mail, armazenamento das mensagens ou processamento em servidor. Os campos aparecem na URL; utilize somente dados fictícios ao experimentar.

## Tecnologias e arquivos

HTML estrutura as páginas; CSS utiliza Flexbox para a organização visual; JavaScript executa o alerta e o redirecionamento. A fonte Roboto Slab é carregada pelo Google Fonts. Não há framework, gerenciador de dependências ou banco de dados.

```text
index.html              # Apresentação e navegação principal
celebracoes.html        # Tradições e atividades
organizacao.html        # Informações sobre a comemoração
personalidades.html     # Personagens culturais
videos.html             # Links externos para vídeos
contato.html            # Formulário demonstrativo
processa.html           # Alerta e redirecionamento
css/style.css           # Estilos compartilhados
js/script.js            # Comportamento da página de processamento
images/                 # Imagens de conteúdo
wireframes/             # WireFrames.pdf
```

O [wireframe em PDF](wireframes/WireFrames.pdf) é um artefato de planejamento, não uma captura do site em execução.

## Execução local

É necessário apenas um navegador com JavaScript habilitado. Não há instalação de pacotes, configuração de ambiente ou etapa de compilação.

```sh
git clone https://github.com/Heitorsv001/festividades.git
cd festividades
```

Abra `index.html` no navegador. Como alternativa, se tiver Python 3 instalado, sirva a pasta localmente:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Acesse `http://127.0.0.1:8000/`. Encerre o servidor com `Ctrl+C`. O acesso à internet é necessário para Google Fonts, vídeos e outras referências externas.


## Créditos

O rodapé e `leia-me.txt` registram Heitor Silva Vareiro e Joao Guilherme Rodrigues, na disciplina Desenvolvimento Web 1. O repositório é mantido na conta [Heitorsv001](https://github.com/Heitorsv001).
