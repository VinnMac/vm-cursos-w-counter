# VM Cursos — Landing Page com Contador de Evento

Landing page para venda de cursos com contador regressivo de evento, animações com AOS e pipeline de build com Parcel e otimização de imagens com Sharp.

## 🚀 Demo

🔗 [Acessar projeto ao vivo](https://new-vm-cursos-contador.vercel.app)

---

## 📋 Sobre o projeto

Landing page completa para venda de cursos online, com foco em performance, modularização de código e experiência do usuário. O projeto utiliza Parcel como bundler moderno, SCSS para estilização escalável, e Sharp para otimização automática de imagens. Inclui um contador regressivo interativo e animações de scroll com a biblioteca AOS.

---

## ✨ Funcionalidades

- Contador regressivo de evento interativo
- Animações de scroll com biblioteca AOS (Animate On Scroll)
- Layout responsivo com abordagem Mobile First
- Otimização automática de imagens com Sharp
- Build otimizado para produção com Parcel

---

## 🛠️ Tecnologias utilizadas

- **HTML5** — estrutura semântica
- **SCSS** — pré-processador CSS modular
- **JavaScript** — manipulação de DOM e funcionalidades dinâmicas
- **Parcel** — bundler moderno (build e dev server)
- **Sharp** — otimização de imagens
- **AOS** — biblioteca de animações de scroll
- **Vercel** — deploy contínuo

### Dependências de desenvolvimento
- `parcel` — bundler
- `@parcel/transformer-sass` — suporte a SCSS no Parcel
- `sharp` — otimização de imagens

---

## 📁 Estrutura do projeto

```
new_vm-cursos_contador/
├── src/
│   ├── index.html
│   ├── styles/        # Arquivos SCSS
│   └── scripts/       # JavaScript
├── sharp.config.json  # Configuração de otimização de imagens
└── package.json
```

---

## ▶️ Como rodar localmente

**Pré-requisitos:** Node.js instalado

```bash
# Clone o repositório
git clone https://github.com/VinnMac/vm-cursos-w-counter

# Entre na pasta
cd vm-cursos-w-counter

# Instale as dependências
npm install

# Modo desenvolvimento com hot reload
npm run dev

# Gerar build de produção
npm run build
```

> `npm run dev` → `parcel src/index.html` — servidor local com hot reload  
> `npm run build` → `parcel build src/index.html` — build otimizado para produção

---

## 📚 O que aprendi

- Uso do **Parcel** como bundler moderno (alternativa ao Webpack)
- Organização modular de estilos com **SCSS**
- Otimização de imagens em pipeline de build com **Sharp**
- Implementação de **animações de scroll** com biblioteca AOS
- Estrutura de projeto escalável para landing pages

---

## 👨‍💻 Autor

**Vinícius Machado**
- GitHub: [@VinnMac](https://github.com/VinnMac)
- LinkedIn: [vinn-machado](https://www.linkedin.com/in/vinn-machado/)

---

*Projeto desenvolvido durante o curso Desenvolvedor Full Stack Python — EBAC*
