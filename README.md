# Clínica Médica Life

## Descrição do Projeto

Este projeto é um site web desenvolvido para a Clínica Médica Life. Ele fornece informações sobre os serviços oferecidos pela clínica, incluindo especialidades médicas, equipe e contato.

## Estrutura de Pastas

Use o código com cuidado.
```
clinica/
├── CSS
│   ├── estilo.css
│   └── especialidade.css
├── imagens
│   ├── clinica.png
│   ├── fisioterapia.png
│   ├── geriatria.png
│   ├── logo.png
│   ├── logo2.png
│   ├── medico.jpg
│   ├── ortopedia.png
│   ├── ortopedia1.png
│   ├── pediatra.png
│   ├── pediatra2.png
│   ├── psicologo.png
│   ├── recepcao.png
│   └── recepcao2.jpg
├── especialidades.html
├── favicon.ico
└── index.html
```

## Arquivos

* **index.html:** Página inicial do site, contendo a página principal com informações sobre a clínica.
* **especialidades.html:** Página com detalhes sobre as diferentes especialidades médicas oferecidas.
* **estilo.css:** Arquivo CSS principal, responsável por estilizar a página inicial.
* **especialidade.css:** Arquivo CSS específico para estilizar a página de especialidades.
* **favicon.ico:** Ícone utilizado para representar o site nas abas do navegador.
* **imagens:** Pasta contendo todas as imagens utilizadas no site, como logotipos, fotos da equipe e imagens ilustrativas.

## Tecnologias Utilizadas

* **HTML:** Linguagem de marcação para estruturar o conteúdo das páginas.
* **CSS:** Linguagem de estilo para definir a aparência visual das páginas.

## Como Utilizar

1. **Clonar o repositório:** Utilize o Git para clonar este repositório para o seu computador local.
2. **Abrir os arquivos:** Abra os arquivos HTML e CSS em um editor de código de sua preferência.
3. **Visualizar:** Abra o arquivo `index.html` em um navegador para visualizar o site.

## Próximos Passos

* **Adicionar mais funcionalidades:** Implementar formulário de contato, agendamento de consultas, etc.
* **Otimizar para SEO:** Melhorar o posicionamento do site nos resultados de busca.
## Responsividade do Site

### Visão Geral

Este documento detalha as estratégias de design responsivo utilizadas no site da Clínica Médica Life, garantindo uma experiência de usuário consistente em diferentes dispositivos (desktop, tablet e mobile).

### Tecnologias Utilizadas

* **CSS Media Queries:** Utilizadas para aplicar estilos específicos a diferentes faixas de largura de tela.
* **Flexbox:** Empregado para criar layouts flexíveis e adaptáveis, permitindo que os elementos se reorganizem de acordo com o tamanho da tela.

### Princípios de Design Responsivo

* **Priorização de conteúdo:** Os elementos mais importantes são priorizados para garantir uma boa experiência em telas menores.
* **Flexibilidade:** O layout se adapta de forma fluida às diferentes dimensões da tela.
* **Imagens responsivas:** As imagens são otimizadas para diferentes tamanhos de tela, evitando quebras no layout.

### Estratégia de Responsividade

* **Breakpoints:** Definimos os seguintes breakpoints para adaptar o layout:
  * **Mobile:** [425px de largura em pixels]
  * **Tablet:** [768px de largura em pixels]
  * **Desktop:** [100% de largura em pixels]
* **Flexbox:** Utilizamos Flexbox para criar layouts flexíveis em diversas áreas do site, como o cabeçalho, rodapé e seções de conteúdo.
* **Media Queries:** Aplicamos estilos específicos para cada breakpoint, ajustando espaçamentos, tamanhos de fontes e posicionamento de elementos.

### Exemplos de Estilos Responsivos

```css
/* Estilo para telas menores (mobile) */
@media (max-width: 425px) {
  .container {
    width: 90%;
    margin: 0 auto;
  }
  .navbar {
    flex-direction: column;
  }
  /* Outros estilos específicos para mobile */
}

/* Estilo para tablets */
@media (min-width: 768px) and (max-width: 1024px) {
  /* Estilos para tablets */
}

/* Estilo para desktops */
@media (min-width: 1024px) {
  /* Estilos para desktops */
}
```
## Contribuições

Contribuições são bem-vindas! Se você encontrar algum problema ou tiver sugestões de melhoria, por favor, abra um issue.



