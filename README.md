# avatar-book
Livro interativo de colorir

Este projeto é um *customizador de avatar* para crianças. Ele permite que a criança (ou os pais) personalize um avatar escolhendo *cabelo, cor do cabelo, roupa, cor da roupa, cor da pele, olhos e boca, e depois **gere um PDF* com o avatar e o nome da criança.

## Como usar

1. Abra a página: https://seu-usuario.github.io/avatar-book/  
2. Digite o nome da criança.  
3. Selecione cada característica do avatar (cabelo, roupa, olhos, boca etc.).  
4. Clique em *Gerar Avatar* → o avatar aparecerá ao vivo.  
5. Clique em *Gerar PDF* → baixe o PDF com o avatar e o nome da criança.

## Tecnologias usadas

- [DiceBear Avataaars](https://dicebear.com/) — geração de avatars via API  
- [jsPDF](https://github.com/parallax/jsPDF) — geração de PDFs no navegador  
- [save-svg-as-png](https://github.com/exupero/saveSvgAsPng) — converter SVG em PNG

## Observações

- Para que o avatar seja gerado corretamente, a página precisa estar *online, seja pelo **GitHub Pages* ou outro servidor (não funciona localmente em file:// devido a restrições de CORS).  
- Você pode atualizar o index.html para adicionar mais opções de cabelo, roupa ou acessórios.
