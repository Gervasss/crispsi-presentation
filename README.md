# Landing Page - Cristiane Gonçalves Neuropsicóloga

Uma landing page moderna e responsiva para Cristiane Gonçalves, Neuropsicóloga baseada em Vitória da Conquista-BA (CRP: 03/4791). Desenvolvida com React, TypeScript, Tailwind CSS, Framer Motion e Locomotive Scroll.

## 🎨 Design Features

- **Design Profissional**: Paleta de cores da psicologia (lavenderBlush, bege,paletVioletRed)
- **Totalmente Responsivo**: Mobile-first approach
- **Animações Suaves**: Implementadas com Framer Motion
- **Scroll Suave**: Locomotive Scroll para experiência premium
- **Componentes Modernos**: Utilizando shadcn/ui
- **Header Profissional**: Com separadores e navegação fluida
- **WhatsApp Integration**: Botão flutuante com modal interativo e efeitos de digitação
- **Seção Instagram**: Carrossel automático de posts com CTA
- **Seção Benefícios**: Cards interativos sobre terapia online

## 🚀 Funcionalidades

- Header fixo com menu hambúrguer animado
- Hero section com animações palavra por palavra
- Seção sobre com design cards inspirado em layouts modernos
- Carrossel de serviços
- **Nova**: Seção "Como o atendimento psicológico online pode te ajudar" com 8 cards interativos:
  - Autoconhecimento
  - Traumas
  - Emoções Intensas
  - Ansiedade
  - Relacionamento
  - Depressão
  - Luto
  - Diagnóstico Neurodivergente
- **Melhorada**: Seção de posts do Instagram com:
  - Carrossel automático de posts
  - Design inspirado no Instagram
  - CTA para seguir no Instagram
  - CTA para conversar no WhatsApp
  - Efeitos visuais aprimorados
- Modal do WhatsApp com:
  - Efeito de digitação realista
  - Mensagens rápidas pré-definidas
  - Campo para mensagem personalizada
  - Animações fluidas
- **Novo**: Locomotive Scroll em todo o projeto para scroll suave e paralaxe
- Seção de depoimentos
- Formulário de contato
- Footer completo

## 🛠️ Tecnologias Utilizadas

- **React** 18.2.0
- **TypeScript** 5.0.2
- **Tailwind CSS** v4.0
- **Framer Motion** (via motion/react)
- **Locomotive Scroll** 5.0.0-beta.13
- **Lucide React** (ícones)
- **shadcn/ui** (componentes)
- **React Hook Form** 7.55.0

## 📋 Pré-requisitos

- Node.js (versão 16 ou superior)
- npm ou yarn

## 🔧 Instalação e Execução

### 1. Clone o repositório
```bash
git clone <url-do-repositorio>
cd cris-psi
```

### 2. Instale as dependências
```bash
npm install
# ou
yarn install
```

### 3. Execute o projeto em modo de desenvolvimento
```bash
npm run dev
# ou
yarn dev
```

### 4. Abra o navegador
Acesse `http://localhost:5173`

### 5. Para build de produção
```bash
npm run build
# ou
yarn build
```

## 📁 Estrutura do Projeto

```
src/
├── components/
│   ├── ui/                      # Componentes shadcn/ui
│   ├── Header.tsx               # Header com navegação
│   ├── HeroSection.tsx          # Seção principal
│   ├── AboutSection.tsx         # Seção sobre o psicólogo
│   ├── ServicesSection.tsx      # Serviços oferecidos
│   ├── TherapyBenefitsSection.tsx # Nova seção de benefícios
│   ├── InstagramSection.tsx     # Posts do Instagram melhorada
│   ├── WhatsAppFloat.tsx        # Modal WhatsApp
│   └── ...
├── hooks/
│   └── useLocomotiveScroll.ts   # Hook para Locomotive Scroll
├── styles/
│   └── globals.css              # Estilos globais e Locomotive Scroll
└── App.tsx                      # Componente principal
```

## 🎨 Paleta de Cores

A paleta de cores foi cuidadosamente escolhida para transmitir confiança e acolhimento:

- **PaletVioletRed** (`#DB7093`) - Confiança e profissionalismo
- **LavanderBlush** (`#FFF0F5`) - Equilíbrio e bem-estar
- **Bege/Areia** (`#F4E1D2`) - Acolhimento e tranquilidade
- **Cinza Médio** (`#6D6875`) - Neutralidade e sofisticação
- **Branco Gelo** (`#FAFAFA`) - Pureza e clareza

## 📱 Responsividade

O projeto foi desenvolvido com abordagem mobile-first, garantindo uma excelente experiência em:
- 📱 Smartphones (320px+)
- 📱 Tablets (768px+)
- 💻 Desktop (1024px+)
- 🖥️ Telas grandes (1440px+)

## 🎭 Animações

- **Locomotive Scroll**: Scroll suave e efeitos de paralaxe em todo o site
- **Entrada suave** dos elementos conforme o scroll
- **Animações de palavra por palavra** no hero
- **Efeito de digitação** no modal WhatsApp
- **Cards interativos** na seção de benefícios
- **Carrossel automático** na seção Instagram
- **Micro-interações** em botões e elementos interativos

## 📞 Integração WhatsApp

O botão flutuante do WhatsApp inclui:
- Número configurado: `+55 77 98143-5696`
- Modal com interface similar ao WhatsApp
- Mensagens rápidas pré-definidas
- Campo para mensagens personalizadas
- Efeito de digitação realista


## 💡 Seção Benefícios da Terapia Online

7 cards interativos cobrindo:
- **Autoconhecimento** - Desenvolvimento pessoal
- **Traumas** - Processamento seguro de experiências
- **Emoções Intensas** - Regulação emocional
- **Ansiedade** - Estratégias de enfrentamento
- **Relacionamento** - Habilidades interpessoais
- **Depressão** - Suporte e estratégias
- **Luto** - Apoio compassivo no processo
- **Diagnóstico Neurodivergente** - Entendimento das particularidades com diagnóstico preciso

## 🎯 SEO e Otimizações

- Meta tags otimizadas para Vitória da Conquista-BA
- Estrutura semântica HTML5
- Lazy loading de imagens
- Performance otimizada com Next
- Locomotive Scroll otimizado para performance

## 📝 Scripts Disponíveis

- `npm run dev` - Inicia o servidor de desenvolvimento
- `npm run build` - Gera build para produção
- `npm run preview` - Visualiza o build de produção
- `npm run lint` - Executa o linter

## 🤝 Contribuição

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## 📧 Contato

**Cristiane Gonçalves** - Neuropsicóloga
📱 WhatsApp: (77) 98143-5696 
🏥 CRP: 03/4791  
📍 Vitória da Conquista-BA  
📸 Instagram: @cris_psy

---

Desenvolvido com ❤️ para proporcionar uma experiência digital acolhedora e profissional na área de saúde mental.
