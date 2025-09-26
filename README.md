# BeroLinks 🔗

Um template minimalista e responsivo de página de links pessoais, inspirado no design clean e moderno.

## ✨ Características

- ✅ Totalmente responsivo (mobile, tablet, desktop)
- ✅ Design moderno com glassmorphism
- ✅ Animações suaves e interativas
- ✅ Fácil de personalizar
- ✅ Sem dependências complexas (usa apenas Tailwind CSS via CDN)

## 🚀 Como usar

### 1. Clone o repositório

```bash
git clone https://github.com/BeroLab/berolinks.git
cd berolinks
```

### 2. Personalize suas informações

Abra o arquivo `index.html` e edite as seguintes seções:

#### **Título da página (linha 7):**
```html
<title>Seu Nome | BeroLinks</title>
```

#### **Informações pessoais (linhas 22-35):**
```html
<!-- Sua foto de perfil -->
<img src="SUA_FOTO_AQUI" alt="Seu Nome">

<!-- Seu nome -->
<h1 class="text-white text-2xl sm:text-3xl font-bold">Seu Nome</h1>

<!-- Seu username -->
<h1 class="text-zinc-400 text-lg sm:text-xl">@seuusername</h1>
```

#### **Seus links (linhas 40-83):**
Substitua os links pelos seus próprios:

```html
<!-- Exemplo: Twitter/X -->
<a href="https://x.com/seuusername" target="_blank" rel="noopener noreferrer">
    <!-- Mantenha o SVG do ícone -->
    Seu Texto do Link
</a>
```

#### **Rodapé (linha 87):**
```html
<a href="https://seusite.com" target="_blank" rel="noopener noreferrer">
    Feito com ❤️ por Seu Nome
</a>
```

### 3. Personalize a imagem de fundo

Substitua a URL da imagem de fundo na linha 12:

```html
<img src="SUA_IMAGEM_DE_FUNDO_AQUI" alt="background">
```

### 4. Teste localmente

Abra o arquivo `index.html` diretamente no seu navegador ou use um servidor local:

```bash
# Com Python
python -m http.server 8000

# Com Node.js (http-server)
npx http-server

# Com PHP
php -S localhost:8000
```

### 5. Faça deploy

Você pode hospedar gratuitamente em:

- **GitHub Pages**: Commit e push para o GitHub, depois ative o GitHub Pages
- **Netlify**: Arraste e solte a pasta no Netlify
- **Vercel**: Conecte seu repositório GitHub ao Vercel
- **Surge.sh**: `npx surge` na pasta do projeto

## 🎨 Personalização avançada

### Mudando cores

O projeto usa Tailwind CSS. Você pode alterar as cores modificando as classes:

- `bg-black/50` - Cor do fundo do card
- `border-white` - Cor da borda
- `text-white` - Cor do texto
- `hover:shadow-indigo-500` - Cor do hover nos botões

### Adicionando novos links

Para adicionar um novo botão, copie um dos botões existentes e modifique:

1. **URL** no atributo `href`
2. **Ícone SVG** (você pode encontrar ícones em sites como [Heroicons](https://heroicons.com) ou [Tabler Icons](https://tabler-icons.io))
3. **Texto** do botão

### Mudando o layout

O layout é totalmente responsivo usando Tailwind CSS. As principais classes responsivas são:

- `sm:` - Tablets (640px+)
- `lg:` - Desktop (1024px+)
- Sem prefixo - Mobile (padrão)

## 📱 Responsividade

O template funciona perfeitamente em:

- 📱 **Mobile** (320px - 640px)
- 📱 **Tablet** (640px - 1024px)
- 💻 **Desktop** (1024px+)

## 🔧 Estrutura do projeto

```
berolinks/
├── index.html          # Página principal
├── README.md          # Este arquivo
└── .git/              # Controle de versão
```

## 🤝 Contribuindo

1. Fork o projeto
2. Crie sua branch (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## 🚀 Créditos

Desenvolvido com ❤️ por [Duca](https://github.com/igorfelipeduca) da [BeroLab](https://berolab.app)

---

**Gostou do projeto? Deixe uma ⭐!**