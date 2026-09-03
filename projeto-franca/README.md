# Vive la France - Site sobre a França

Projeto de TCC - Desenvolvimento de Sistemas

## Estrutura do Projeto

```
projeto-franca/
├── index.html          # Página principal (Sobre a França + História)
├── cultura.html        # Página sobre Cultura Francesa
├── pontos-turisticos.html  # Página sobre Pontos Turísticos
└── css/
    └── style.css       # Arquivo de estilos
```

## Como usar no VSCode

1. Abra a pasta `projeto-franca` no VSCode
2. Clique com o botão direito no arquivo `index.html`
3. Selecione "Open with Live Server" (se tiver a extensão instalada)
   - Ou abra o arquivo diretamente no navegador (duplo clique)

## Melhorias realizadas em relação ao código original

### Correções:
- Tag `<nave>` corrigida para `<nav>` (tag HTML correta)
- Idioma alterado de `en` para `pt-BR`
- Links de navegação funcionais (3 páginas completas)
- Imagem da "Balança da Justiça" substituída por emblema SVG temático da França
- Rodapé com conteúdo real

### Design e Visual:
- Paleta de cores profissional (tons terrosos e azuis que remetem à cultura francesa)
- Fonte Crimson Pro (elegante, adequada para temas históricos/culturais)
- Layout responsivo (funciona em celulares, tablets e computadores)
- Navegação fixa no topo com destaque da página ativa
- Hero com emblema SVG e representação da bandeira francesa
- Cards com efeito hover
- Linha do tempo interativa para a história
- Ícones SVG inline (sem dependências externas)

### Conteúdo:
- **Página Inicial**: Informações básicas (capital, população, idioma, moeda), texto sobre a França, citação, linha do tempo histórica, cards de navegação
- **Cultura**: 6 cards detalhados sobre Literatura, Arte, Gastronomia, Moda, Cinema e Música + seção sobre tradições
- **Pontos Turísticos**: 9 cards detalhados sobre os principais pontos (Torre Eiffel, Louvre, Versalhes, Notre-Dame, Mont Saint-Michel, Provença, Champs-Élysées, Costa Azul, Vale do Loire) + dica de viagem

### Regras seguidas:
- Sem emojis (usados ícones SVG no lugar)
- Código semântico (HTML5 correto)
- CSS organizado com variáveis de cor
- Acessibilidade básica
- Sem dependências externas além da fonte do Google Fonts

## Personalização

- Para alterar cores: edite as variáveis no início do arquivo `css/style.css` (dentro de `:root`)
- Para alterar a fonte: troque o link do Google Fonts no `<head>` e a propriedade `font-family` no CSS
- Para adicionar conteúdo: basta editar os arquivos `.html` dentro das tags `<main>`
