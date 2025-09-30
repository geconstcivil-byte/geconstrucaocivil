# GE Construção Civil - Website

Website profissional para a empresa GE Construção Civil, especializada em serviços de construção e acabamentos.

## 🏗️ Sobre o Projeto

Este website foi desenvolvido para apresentar os serviços da GE Construção Civil, incluindo:

- **Alvenaria**: Construção de paredes com tijolos e argamassa
- **Assentamento de Porcelanato**: Instalação profissional de pisos e revestimentos
- **Pintura de Fachadas**: Pintura externa de edifícios
- **Aplicação de Grafiato**: Acabamentos texturizados
- **Efeito Marmorizado**: Técnicas especiais de pintura decorativa

## 🚀 Funcionalidades

- ✅ Design responsivo para todos os dispositivos
- ✅ Carrossel interativo com 10 imagens dos projetos
- ✅ Navegação suave entre seções
- ✅ Botões para WhatsApp e Instagram
- ✅ Animações e efeitos visuais
- ✅ Otimizado para SEO
- ✅ Compatível com GitHub Pages

## 📁 Estrutura dos Arquivos

```
/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── script.js           # Funcionalidades JavaScript
├── logo.jpg            # Logo da empresa
├── alvenaria_1.png     # Imagem: Alvenaria Profissional
├── alvenaria_2.png     # Imagem: Acabamento em Alvenaria
├── porcelanato_1.png   # Imagem: Assentamento de Porcelanato
├── porcelanato_2.png   # Imagem: Resultado Final Porcelanato
├── pintura_fachada_1.png # Imagem: Pintura de Fachadas
├── pintura_fachada_2.png # Imagem: Detalhes de Pintura
├── grafiato_1.png      # Imagem: Aplicação de Grafiato
├── grafiato_2.png      # Imagem: Acabamento Grafiato
├── efeito_marmorizado_1.png # Imagem: Técnica Marmorizada
├── efeito_marmorizado_2.png # Imagem: Efeito Marmorizado Final
└── README.md           # Este arquivo
```

## 🌐 Como Hospedar no GitHub Pages

### Passo 1: Criar Repositório no GitHub

1. Acesse [GitHub.com](https://github.com) e faça login
2. Clique em "New repository" (Novo repositório)
3. Nome sugerido: `ge-construcao-civil-website`
4. Marque como "Public" (Público)
5. Clique em "Create repository"

### Passo 2: Fazer Upload dos Arquivos

**Opção A - Via Interface Web:**
1. No repositório criado, clique em "uploading an existing file"
2. Arraste todos os arquivos do projeto para a área de upload
3. Adicione uma mensagem de commit: "Adicionar website da GE Construção Civil"
4. Clique em "Commit changes"

**Opção B - Via Git (se você tem Git instalado):**
```bash
git clone https://github.com/SEU_USUARIO/ge-construcao-civil-website.git
cd ge-construcao-civil-website
# Copie todos os arquivos para esta pasta
git add .
git commit -m "Adicionar website da GE Construção Civil"
git push origin main
```

### Passo 3: Ativar GitHub Pages

1. No repositório, vá para "Settings" (Configurações)
2. Role para baixo até encontrar "Pages" no menu lateral
3. Em "Source", selecione "Deploy from a branch"
4. Em "Branch", selecione "main" e "/ (root)"
5. Clique em "Save"

### Passo 4: Acessar o Site

Após alguns minutos, seu site estará disponível em:
```
https://SEU_USUARIO.github.io/ge-construcao-civil-website/
```

## 🔧 Personalização

### Alterar Informações de Contato

Edite o arquivo `index.html` e procure pela seção `#contato`:

```html
<!-- Altere os links do WhatsApp e Instagram -->
<a href="https://wa.me/5511999999999" target="_blank" class="social-btn whatsapp-btn">
<a href="https://instagram.com/geconstrucaocivil" target="_blank" class="social-btn instagram-btn">

<!-- Altere as informações de contato -->
<span>Telefone: (11) 99999-9999</span>
<span>Email: contato@geconstrucao.com.br</span>
```

### Alterar Cores do Site

Edite o arquivo `styles.css` e procure pelas variáveis de cor:

```css
/* Cor principal dourada */
#d4a574

/* Cor secundária */
#2c3e50

/* Gradientes */
background: linear-gradient(135deg, #d4a574 0%, #b8956a 100%);
```

### Adicionar Mais Imagens ao Carrossel

1. Adicione as novas imagens ao repositório
2. Edite o arquivo `index.html` na seção `#projetos`
3. Adicione novos slides seguindo o padrão existente
4. Atualize os indicadores do carrossel

## 📱 Recursos Incluídos

- **Responsivo**: Funciona perfeitamente em celulares, tablets e desktops
- **Carrossel Automático**: Troca de slides a cada 5 segundos
- **Navegação por Toque**: Suporte a swipe em dispositivos móveis
- **Animações Suaves**: Efeitos de fade-in e transições
- **SEO Otimizado**: Meta tags e estrutura semântica
- **Acessibilidade**: ARIA labels e navegação por teclado

## 🎨 Tecnologias Utilizadas

- HTML5 semântico
- CSS3 com Flexbox e Grid
- JavaScript ES6+
- Font Awesome (ícones)
- Google Fonts (tipografia)

## 📞 Suporte

Para dúvidas sobre hospedagem ou personalização, consulte a documentação do GitHub Pages:
- [GitHub Pages Documentation](https://docs.github.com/en/pages)

## 📄 Licença

Este projeto foi desenvolvido especificamente para a GE Construção Civil. Todos os direitos reservados.

---

**GE Construção Civil** - Excelência em cada projeto 🏗️
