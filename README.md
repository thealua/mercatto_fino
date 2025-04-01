# 🛒 Sistema Web para Minimercado

# README - Mercatto Fino

## Visão Geral
Este projeto é um site completo para um minimercado, desenvolvido com HTML, CSS (Bootstrap) e JavaScript. O site inclui seções de produtos, serviços, formulários de cadastro e agendamento, além de recursos de acessibilidade.

## Funcionalidades Implementadas

### 1. Carrossel de Destaques
- **Tecnologia**: Bootstrap Carousel
- **Recursos**:
  - 3 slides rotativos com imagens e textos descritivos
  - Navegação por setas e indicadores de posição
  - Rodagem automática a cada 5 segundos
  - Responsivo para todos os tamanhos de tela

### 2. Formulário de Cadastro do Cliente
- **Campos incluídos**:
  - Nome completo (obrigatório)
  - CPF com validação (obrigatório)
  - E-mail (obrigatório)
  - Telefone (obrigatório)
  - Endereço completo (obrigatório)
  - Sexo (opções de rádio button)
  - Preferências (checkboxes opcionais)
  - Aceite de termos (checkbox obrigatório)

- **Validações**:
  - Campos obrigatórios
  - Formato de e-mail válido
  - Validação de CPF com algoritmo
  - Feedback visual para campos inválidos

### 3. Sistema de Agendamento
- **Opções de serviço**:
  - Retirada no local
  - Tele-entrega (com campo de endereço adicional)

- **Recursos**:
  - Seletor de data (apenas dias futuros)
  - Seletor de horário (dentro do horário comercial)
  - Campo de observações
  - Validação de todos os campos

### 4. Seção de Produtos
- **Organização**:
  - Categorias: Alimentos, Bebidas, Higiene
  - Produtos em cards com:
    - Imagem com descrição alternativa
    - Nome do produto
    - Preço formatado

### 5. Seção de Serviços
- **Serviços oferecidos**:
  - Entrega em domicílio
  - Pagamento via PIX
- Apresentados em cards com ícones e descrição

### 6. Recursos de Acessibilidade
- **Implementados**:
  - Atributos `alt` em todas as imagens
  - Botão de alto contraste
  - Controles para aumentar/diminuir fonte
  - Navegação por teclado
  - Textos descritivos para elementos não textuais
  - Modo de alto contraste ativável

## Estrutura de Arquivos
```
minimercado-xyz/
├── index.html          # Página principal
├── produtos.html       # Página de produtos
├── servicos.html       # Página de serviços (contém os formulários)
├── contato.html        # Página de contato
├── assets/             # Pasta de recursos
│   ├── images/         # Imagens do site
│   │   ├── logo.png
│   │   ├── arroz.jpg
│   │   ├── feijao.jpg
│   │   ├── suco.jpg
│   │   ├── refrigerante.jpg
│   │   ├── sabonete.jpg
│   │   ├── shampoo.jpg
│   │   ├── destaque1.jpg
│   │   ├── destaque2.jpg
│   │   └── destaque3.jpg
├── css/
│   └── style.css       # Folha de estilos principal
└── js/
    └── script.js       # JavaScript customizado
```

## Tecnologias Utilizadas
- **HTML5**: Estrutura semântica do site
- **CSS3/Bootstrap 5**: Estilização e layout responsivo
- **JavaScript**: Validações e interatividade
- **Font Awesome**: Ícones
- **Google Fonts**: Tipografia

## Instruções de Instalação
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/minimercado-xyz.git
   ```
2. Navegue até a pasta do projeto:
   ```bash
   cd minimercado-xyz
   ```
3. Abra o arquivo `index.html` no seu navegador.

## Como Contribuir
1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## Licença
Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

## Contato
Desenvolvedor: Luara Pontes  
Email: luara.pontes@edu.pucrs.br  

