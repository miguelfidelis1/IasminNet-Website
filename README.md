# README - IasminNet

## 🌸 Sobre o Projeto
**IasminNet** é uma plataforma pessoal de streaming criada especialmente para a Iasmin assistir suas séries favoritas. Um presente digital com design elegante e funcionalidades personalizadas.

## ✨ Recursos Principais
- **Catálogo Organizado**: Séries categorizadas por gênero e preferências
- **Player Integrado**: Assistir episódios diretamente no site
- **Design Personalizado**: Temas roxos e elementos românticos
- **Responsivo**: Acessível em todos os dispositivos

## 🎨 Guia de Estilo
### Paleta de Cores
```css
:root {
    --rosa-claro: #ffebf3;
    --roxo-romantico: #d8a7ff;
    --roxo-principal: #b56bff;
    --roxo-profundo: #7d3cff;
    --destaque-iasmin: #ff4dcc;
}
```

### Tipografia
- Títulos: "Pacifico", cursive (romântico)
- Texto: "Quicksand", sans-serif (legível)

## 📂 Estrutura do Projeto
```
iasminnet/
├── index.html          # Portal de entrada
├── series/             # Páginas de séries
│   ├── romance.html
│   ├── drama.html
│   └── fantasia.html
├── episodios/          # Players de episódios
│   ├── s01e01.html
│   └── s01e02.html
├── assets/
│   ├── css/style.css   # Estilos principais
│   ├── js/             # Interações
│   └── img/            # Capas e thumbnails
└── extras/
    ├── mensagens.html  # Recados especiais
    └── memoria.html    # Galeria de momentos
```

## 💌 Como Personalizar
1. **Adicionar Séries**:
   ```html
   <!-- Dentro de /series/romance.html -->
   <div class="serie-card" style="--destaque: var(--destaque-iasmin)">
     <img src="assets/img/serie-poster.jpg" alt="Série Romântica">
     <h3>Nome da Série</h3>
     <a href="../episodios/s01e01.html" class="heart-button">
       <i class="fas fa-heart"></i> Assistir
     </a>
   </div>
   ```

2. **Adicionar Episódios**:
   ```html
   <!-- Em /episodios/s01e01.html -->
   <div class="player-wrapper">
     <iframe src="SEU_LINK_AQUI"></iframe>
     <div class="marcador-iasmin">Episódio especial para Iasmin</div>
   </div>
   ```

## 🌟 Recursos Especiais
- **Botão Coração**: Navegação com efeito de pulsar
- **Easter Eggs**: Mensagens escondidas ao passar o mouse
- **Modo Noturno**: Alternância suave para maratonas noturnas
- **Playlist Romântica**: Seção especial para séries favoritas

## 📱 Responsividade
| Dispositivo  | Layout Adaptado |
|--------------|-----------------|
| Desktop      | Grade completa (6 séries/linha) |
| Tablet       | 4 séries/linha  |
| Mobile       | 2 séries/linha  |
| TV Smart     | Modo cinema     |

## 💝 Toques Finais
1. Adicione fotos de vocês dois na pasta `/assets/img/memories/`
2. Edite `extras/mensagens.html` com recados pessoais
3. No `footer`, adicione uma data especial:
```html
<p>Desde nosso primeiro filme juntos em 20/12/2020</p>
```

## 🚀 Publicação
Recomendamos hospedar no Netlify ou Vercel para:
- Deploy contínuo ao fazer atualizações
- Domínio personalizado (ex: iasmin.netlify.app)
- Certificado SSL gratuito

---

Desenvolvido com todo carinho para horas especiais de streaming juntos! 💜
