# TOZZ - Terminal de Container

Um site moderno e responsivo para apresentar a plataforma TOZZ, um terminal web completo para gerenciamento de containers Docker.

## 📋 Características

- **Página Inicial Responsiva**: Funciona perfeitamente em desktop, tablet e mobile
- **6 Serviços Principais**: Apresentação clara dos diferenciais da plataforma
- **4 Recursos Destacados**: Funcionalidades principais ilustradas
- **Terminal Interativo**: Box de terminal visual com animação de digitação
- **Formulário de Contato**: Capture leads com formulário integrado
- **Design Moderno**: Gradientes, animações suaves e transições fluidas
- **Otimização SEO**: Meta tags e estrutura semântica

## 🎯 Seções do Site

### 1. **Navegação**
- Logo com tagline
- Links para as principais seções
- Sticky nav com efeito de scroll

### 2. **Hero Section**
- Headline impactante
- Descrição clara da proposta de valor
- Call-to-action principal
- Visualização do terminal

### 3. **Serviços** (6 cards)
- 📦 Gerenciamento de Containers
- 📊 Monitoramento em Tempo Real
- 📋 Visualização de Logs
- 🖥️ Terminal Interativo
- 🏗️ Gerenciamento de Imagens
- 🔐 Segurança e Acesso

### 4. **Recursos** (4 features)
- Dashboard Intuitivo
- Multi-Host Support
- API REST Completa
- Backup e Restauração

### 5. **Call-to-Action**
- Seção destacada para conversão
- Botão grande e visível

### 6. **Contato**
- Informações de contato
- Formulário de mensagem

### 7. **Footer**
- Links importantes
- Redes sociais
- Copyright

## 🎨 Design

- **Cores Principais**:
  - Azul: `#2563eb` (Primary)
  - Verde: `#10b981` (Accent)
  - Cinza Escuro: `#0f172a` (Dark background)
  
- **Tipografia**: Segoe UI, Tahoma, Geneva
- **Espaçamento**: Padding e margin consistentes
- **Breakpoints**: 768px (tablet) e 480px (mobile)

## 🚀 Uso

1. Clone o repositório
2. Abra `index.html` em um navegador web
3. O site carregará com todos os estilos e funcionalidades

Não há dependências externas - tudo é vanilla HTML, CSS e JavaScript!

## ✨ Funcionalidades JavaScript

- ✅ Scroll suave entre seções
- ✅ Animação de digitação no terminal
- ✅ Observador de interseção para animações ao scroll
- ✅ Efeito ripple nos botões
- ✅ Validação e submissão de formulário
- ✅ Sombra dinâmica da navbar

## 📱 Responsividade

O site é totalmente responsivo e se adapta a:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (até 480px)

## 🔧 Customização

Para customizar o site:

1. **Cores**: Modifique as variáveis CSS em `:root` no `style.css`
2. **Textos**: Edite o conteúdo no `index.html`
3. **Funcionalidades**: Adicione mais lógica no `script.js`
4. **Email de Contato**: Implemente backend para enviar emails do formulário

## 📞 Integração com Backend

Para enviar emails do formulário de contato, você precisará:

1. Criar um endpoint backend que receba POST requests
2. Modificar o `script.js` para fazer chamadas AJAX/Fetch
3. Implementar validação e segurança no backend

Exemplo com Node.js/Express:

```javascript
fetch('/api/contact', {
    method: 'POST',
    headers: { 'Content-Type': 'application/json' },
    body: JSON.stringify({ name, email, message })
})
```

## 📋 Estrutura de Arquivos

```
TOZZ/
├── index.html      # Página principal
├── style.css       # Estilos do site
├── script.js       # Funcionalidades JavaScript
└── README.md       # Documentação
```

## 🌐 Implantação

### GitHub Pages
1. Vá para Settings > Pages
2. Selecione Branch `main` (ou `master`)
3. Clique em Save
4. Seu site estará em: `https://username.github.io/TOZZ`

### Vercel
1. Conecte seu repositório GitHub
2. Deploy automático a cada push

### Netlify
1. Arraste a pasta do projeto
2. Deploy instantâneo

## 📄 Licença

MIT License - Sinta-se livre para usar, modificar e distribuir!

---

**TOZZ** - Gerenciamento de Containers Simplificado 🚀
