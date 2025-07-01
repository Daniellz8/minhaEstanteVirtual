# Paleta de Cores para "iEstanteVirtual"

Esta paleta de cores foi escolhida para a "MyShelf" com o objetivo de transmitir calma, conhecimento e um toque de modernidade, garantindo ao mesmo tempo uma excelente legibilidade e um visual profissional.

---

## As Cores:

1.  **Base (Fundo da Página): `#F9F7F3`**
    * Um branco muito suave, quase um creme claríssimo. Proporciona uma sensação de acolhimento e limpeza, remetendo à cor do papel de um livro, de forma sutil e não cansativa para os olhos.

2.  **Fundo dos Cards/Conteúdo Principal: `#FFFFFF`**
    * Branco puro. Utilizado para o fundo dos cards de livros, seções de texto e outras áreas onde o conteúdo precisa de destaque e clareza máxima.

3.  **Cor Primária (Títulos, Destaques Principais): `#4A6D7C`**
    * Um **Teal Acinzentado** ou **Azul Petróleo Suave**. Essa cor evoca conhecimento, calma, profissionalismo e um certo requinte. Ideal para o título principal da página ("MyShelf"), títulos de seções (`<h2>`, etc.) e elementos de navegação importantes.

4.  **Cor Secundária (Detalhes, Links, Destaques Menores): `#A7D9B4`**
    * Um **Verde Pastel Suave**. Complementa o tom azul-acinzentado da cor primária, adicionando um toque de frescor, natureza e leveza. Pode ser usado para links, pequenos ícones, bordas sutis ou indicadores de status.

5.  **Texto Principal (Corpo do Texto): `#333333`**
    * Um **Cinza Escuro** quase preto. Garante excelente legibilidade para o corpo do texto (sinopses, descrições longas), sendo mais suave que o preto puro e menos cansativo para os olhos em leituras prolongadas.

6.  **Texto Secundário/Detalhes (Autor, Gênero, Notas): `#777777`**
    * Um **Cinza Médio**. Perfeito para informações secundárias nos cards (como nome do autor, gênero, ano de publicação), que precisam ser lidas, mas não devem competir visualmente com o título ou a sinopse principal.

7.  **Cor de Acento/Interação (Opcional - Botões, Hover): `#E07A5F`**
    * Um **Coral/Terracota Suave**. Uma cor mais quente e convidativa, ideal para elementos interativos como botões de ação ("Marcar como Lido", botões de filtro) ou para efeitos de `hover`, proporcionando um "pop" visual sutil.

---

## Exemplo de Uso no CSS (Variáveis):

Para facilitar a manutenção e a aplicação das cores, é recomendado definir essas cores como Variáveis CSS (Custom Properties) no seu arquivo `main-styles.css`:

```css
:root {
    --color-background-page: #F9F7F3;
    --color-background-card: #FFFFFF;
    --color-primary