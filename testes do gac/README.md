# Site Institucional GAC-PE

Este é o site institucional do Grupo de Ajuda à Criança Carente com Câncer de Pernambuco (GAC-PE).

## Estrutura do Projeto

- `index.html`: Página Inicial
- `about.html`: Sobre Nós (História, Missão, Equipe)
- `projects.html`: Projetos e Programas
- `volunteer.html`: Página de Voluntariado com formulário
- `donate.html`: Página de Doações (PIX, Transferência)
- `news.html`: Notícias e Eventos
- `transparency.html`: Transparência e Documentos
- `contact.html`: Contato e Localização
- `css/`: Arquivos de estilo (style.css)
- `js/`: Arquivos de script (script.js)
- `assets/`: Imagens e ícones (se houver)

## Como Editar o Conteúdo

O site foi construído com HTML5 e CSS3 puro para garantir leveza, performance e facilidade de manutenção.

### Textos
Para alterar os textos, abra o arquivo `.html` correspondente em qualquer editor de texto (Notepad++, VS Code, Sublime Text) e procure pelo texto que deseja alterar.

Exemplo: Para mudar o telefone no rodapé, edite o bloco `<footer>` em qualquer arquivo HTML (recomenda-se usar "Localizar e Substituir" para alterar em todos os arquivos de uma vez).

### Imagens
As imagens estão marcadas como placeholders (espaços reservados) no código. Para adicionar imagens reais:
1. Salve as imagens na pasta `assets/images/`.
2. No HTML, procure por tags como `<div style="background-color: #ddd...">` ou `<img>`.
3. Substitua pelo caminho da imagem: `<img src="assets/images/foto-historia.jpg" alt="Descrição da foto">`.

### Cores
As cores principais estão definidas no arquivo `css/style.css` na seção `:root`.
- `--primary-color`: Azul (#0056b3)
- `--secondary-color`: Laranja (#ff9900)

Alterar esses valores mudará a cor em todo o site automaticamente.

## Hospedagem (Deploy)

Este site é estático e pode ser hospedado gratuitamente em diversos serviços:

### Opção 1: Netlify (Recomendado)
1. Crie uma conta em [netlify.com](https://www.netlify.com).
2. Arraste a pasta do projeto para a área de "Sites".
3. O site estará online em segundos.

### Opção 2: Vercel
1. Crie uma conta em [vercel.com](https://vercel.com).
2. Importe o projeto (se estiver no GitHub) ou use a CLI da Vercel.

### Opção 3: Hospedagem Tradicional (cPanel/FTP)
1. Acesse o gerenciador de arquivos ou FTP da sua hospedagem.
2. Faça o upload de todos os arquivos e pastas para a pasta `public_html`.

## Formulários

Os formulários de contato e voluntariado estão configurados para usar o serviço **Formspree**.
1. Crie uma conta em [formspree.io](https://formspree.io).
2. Crie um novo formulário e copie o "Endpoint" (URL).
3. Nos arquivos `contact.html` e `volunteer.html`, substitua a URL na tag `<form action="...">` pela sua URL do Formspree.

## Licença

Este projeto foi desenvolvido para uso exclusivo do GAC-PE.
