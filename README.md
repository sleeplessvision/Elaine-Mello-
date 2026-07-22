# Elaine Mello Tricot — Landing Page

Landing page de página única para a Elaine Mello Tricot (atacado, varejo e loja física em Jacutinga - MG).

## Stack

HTML + Tailwind CSS (via CDN) + JavaScript puro. Sem build step — é só abrir o `index.html` no navegador.

- [Tailwind CSS](https://tailwindcss.com/) via CDN (`cdn.tailwindcss.com`)
- [lucide](https://lucide.dev/) para ícones
- [Google Fonts](https://fonts.google.com/): Playfair Display (títulos) e Inter (texto)
- Canvas 2D para a animação de fundo "silk" do hero
- `IntersectionObserver` para as animações de entrada ao rolar a página

## Como visualizar

Basta abrir `index.html` diretamente no navegador (duplo clique) — não precisa de servidor nem instalar nada.

## Estrutura

```
index.html          página inteira (marcação, estilos e scripts)
assets/
  logo-elaine-mello.png   logo (PNG com transparência)
  foto-1.jpg .. foto-4.jpg  fotos usadas no carrossel "Quem é a Elaine Mello"
```

## Seções da página

1. Hero — logo, menu de navegação, animação de fundo, tagline
2. Quem é a Elaine Mello — carrossel contínuo de fotos
3. Por aqui, você decide o caminho — botões de Varejo / Atacado / Site / Grupo VIP
4. Escolha quem te atende — contato direto com Kellen e Fran
5. Onde nos encontrar — endereço, telefone, horário e mapa
6. Rodapé — navegação, contato e redes sociais

## Pendências

- **Redes sociais do rodapé**: os links de Instagram, WhatsApp e Facebook no rodapé ainda estão como placeholder (`href="#"`) — falta confirmar quais mostrar e os links reais.
- **Handle do Instagram**: útil para uma auditoria visual rápida (paleta, tipografia, tom das fotos) e ajustar o hero se necessário.
