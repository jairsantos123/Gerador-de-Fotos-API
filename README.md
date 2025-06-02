# 🐱 Gerador de Fotos de Gatos

Uma aplicação web simples e divertida que gera fotos aleatórias de gatos utilizando APIs públicas. Perfeito para alegrar o seu dia com fotos fofas de gatinhos!

## 📋 Sobre o Projeto

O Gerador de Fotos de Gatos é uma aplicação web desenvolvida com HTML, CSS e JavaScript que consome uma API de fotos de gatos para exibir imagens aleatórias. Com interface clean e intuitiva, basta clicar em um botão para carregar uma nova foto adorável de gatos.

## ✨ Funcionalidades

- 🐾 **Geração Aleatória** - Carrega fotos diferentes de gatos a cada clique
- 🖼️ **Display Responsivo** - Exibe as imagens em tamanho otimizado
- ℹ️ **Informações da Imagem** - Mostra ID e dimensões da foto carregada
- ✅ **Feedback Visual** - Confirma quando a imagem é carregada com sucesso
- 🎨 **Interface Limpa** - Design minimalista e focado na experiência
- 📱 **Layout Responsivo** - Funciona em diferentes dispositivos
- ⚡ **Carregamento Rápido** - Interface otimizada para performance

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura da aplicação
- **CSS3** - Estilização e layout responsivo
- **JavaScript (ES6+)** - Lógica e consumo de API
- **API REST** - Integração com serviço de fotos de gatos
- **Fetch API** - Requisições HTTP assíncronas

## 🎨 Interface

### Layout Principal
- **Título**: "Gerador de Fotos de Gatos"
- **Botão**: "Carregar Nova Foto" (verde, destacado)
- **Feedback**: Mensagem de confirmação
- **Container**: Área para exibição da imagem
- **Informações**: ID e dimensões da foto atual

### Design
- **Fundo**: Cinza claro elegante
- **Botão**: Verde vibrante (#4CAF50)
- **Card**: Fundo branco com bordas arredondadas
- **Tipografia**: Fonte moderna e legível
- **Espaçamento**: Layout bem estruturado

## 🔧 Como Funciona

### Fluxo da Aplicação

1. **Carregamento**: Página inicializa sem imagem
2. **Clique**: Usuário clica em "Carregar Nova Foto"
3. **Requisição**: JavaScript faz chamada para API
4. **Resposta**: API retorna dados da imagem
5. **Exibição**: Imagem é renderizada na tela
6. **Informações**: Dados técnicos são mostrados

## 🌐 API Utilizada

A aplicação consome uma API pública de fotos de gatos que fornece:

- **Imagens Aleatórias**: Diferentes fotos a cada requisição
- **Metadados**: Informações sobre dimensões e ID
- **Formato JSON**: Resposta estruturada
- **CORS Habilitado**: Permite requisições do browser

## 📱 Responsividade

O projeto é totalmente responsivo e funciona em:

- 📱 **Mobile**: 320px - 768px
- 📱 **Tablet**: 768px - 1024px  
- 💻 **Desktop**: 1024px+
- 🖥️ **Large Screens**: 1440px+

## 🎯 Funcionalidades Detalhadas

### Carregamento de Imagens
- Requisições assíncronas para melhor UX
- Tratamento de erros de conexão
- Loading state durante carregamento
- Cache de imagens para performance

### Informações Técnicas
- **ID da Imagem**: Identificador único
- **Dimensões**: Largura e altura em pixels
- **Status**: Confirmação de carregamento

### Experiência do Usuário
- Interface intuitiva e amigável
- Feedback imediato nas ações
- Design focado na simplicidade
- Carregamento suave das imagens

## 🐛 Tratamento de Erros

A aplicação possui tratamento para:

- **Erro de Conexão**: Quando não há internet
- **API Indisponível**: Quando o serviço está fora do ar
- **Imagem Inválida**: Quando a URL não carrega
- **Timeout**: Quando a requisição demora muito

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para detalhes.

## 👤 Autor

Projeto desenvolvido por: Jairo Rocha.

Orientador: Luan Oliveira.
