# Guia Passo a Passo: Configuração Visual da Nuvemshop (Rô Modas)
> **Objetivo:** Preencher cada campo do painel da Nuvemshop com os códigos de cores, fontes, tamanhos e ordem de blocos exatos para deixar a loja visualmente impecável para a apresentação.

---

## 1. Cores da Sua Marca (Copie e Cole os Códigos HEX)

No menu **Imagem da sua marca > Cores da sua marca**:

| Campo na Nuvemshop | Código HEX | Prévia / Função |
| :--- | :--- | :--- |
| **Cor de Fundo da Página** | `#FAF8F5` | Off-white / linho suave (passa sensação de loja arejada e elegante, sem a frieza do branco puro). |
| **Cor do Texto Principal** | `#2C2C2C` | Preto grafite suave (leitura nítida e confortável para celular e computador). |
| **Cor de Destaque / Links / Acentos** | `#8E5646` | Terracota da marca Rô Modas (usado em links, preços destacados e detalhes). |
| **Cor do Botão Principal (Comprar)** | `#1E242B` | Preto carvão elegante com texto `#FFFFFF` (padrão de lojas de moda como Zara e Posthaus; transmite sofisticação e tem altíssima taxa de clique). *Opção alternativa:* `#8E5646` (Terracota). |
| **Etiqueta de Promoção (Desconto %)** | `#B91C1C` | Vermelho clássico de promoção (chama a atenção da cliente imediatamente para o desconto). |
| **Etiqueta de Frete Grátis** | `#0E6251` | Verde escuro elegante (transmite benefício financeiro e segurança). |

---

## 2. Tipo de Letra (Tipografia)

No menu **Imagem da sua marca > Tipo de Letra**:

### 2.1. Títulos
- **Fonte:** **Montserrat** ou **Poppins** (se não tiver disponível no seu tema, selecione **Open Sans** ou **Lato**);
- **Estilo:** **Negrito (Bold)**;
- **Tamanho:** **Grande (24px a 28px)**.

### 2.2. Textos e Parágrafos (Descrições, Banners e Mensagens)
- **Fonte:** A mesma família do título (ex: **Montserrat** ou **Open Sans**);
- **Estilo:** **Normal / Regular (400)**;
- **Tamanho do Parágrafo Recomendado:** **14px**
  - *Por que 14px?* 12px fica muito pequeno e cansativo no celular; 16px quebra linhas e empurra o botão de compra para baixo da tela. **14px é o padrão ouro do e-commerce de moda**.

---

## 3. Configurações Avançadas: Cabeçalho

No menu **Configurações avançadas > Cabeçalho**:

### 3.1. Barra de Anúncio Superior (Top Announcement Bar)
- **Ativar barra de anúncio:** Sim
- **Cor de Fundo da Barra:** `#1E242B` (Preto)
- **Cor do Texto:** `#FFFFFF` (Branco)
- **Texto do Anúncio (Copiar e Colar):**
  > `✨ 1ª compra? Use o cupom RO-OFF para 10% OFF | Retirada grátis no Bairro Alto em Matão`

### 3.2. Logo e Favicon
- **Logotipo Principal:** Subir o arquivo da logo nova circular com fundo transparente ou branco;
- **Favicon (Ícone da Aba do Navegador):** Subir a versão quadrada/circular pequena da logo "R" (32x32px).

### 3.3. Cabeçalho em Celulares (Mobile)
- **Alinhamento da Logo:** Centralizado;
- **Ícones Visíveis:** Menu (hambúrguer à esquerda), Busca (lupa) e Carrinho (à direita);
- **Estilo do Ícone de Carrinho:** Ícone de **Sacola de Compras** (passa mais identidade de moda do que carrinho de supermercado).

### 3.4. Cabeçalho em Computadores (Desktop)
- **Alinhamento da Logo:** À esquerda ou centralizado acima do menu;
- **Menu Principal (Ordem das Categorias no Topo):**
  1. `Novidades`
  2. `Vestidos`
  3. `Calças Jeans`
  4. `Blusas & Conjuntos`
  5. `Infantil`
  6. `Calçados`
  7. `Promoções`
- **Barra de Pesquisa:** Ativa e visível no centro do cabeçalho;
- **Links para Conta e Carrinho:**
  - Em computadores, utilize o formato **Ícone + Texto** (Ex: *Minha Conta* e *Sacola (0)*) para facilitar o clique.

### 3.5. Menu Secundário (Links Úteis no Topo ou Rodapé)
- Link 1: `Rastrear Meu Pedido`
- Link 2: `Como Comprar & Fretes`
- Link 3: `Chamar no WhatsApp`

---

## 4. Configurações Avançadas: Página Inicial (Ordem dos Blocos)

No menu **Configurações avançadas > Página inicial**, organize os blocos na seguinte ordem estratégica (idêntica à arquitetura da Posthaus):

```
┌────────────────────────────────────────────────────────┐
│ 1. BANNER PRINCIPAL ROTATIVO (CARROSSEL)               │
├────────────────────────────────────────────────────────┤
│ 2. RÉGUA DE BENEFÍCIOS (FRETE, PIX, RETIRADA)          │
├────────────────────────────────────────────────────────┤
│ 3. PÍLULAS DE CATEGORIAS (ACESSO RÁPIDO COM FOTOS)     │
├────────────────────────────────────────────────────────┤
│ 4. PRODUTOS EM DESTAQUE (VITRINE PRINCIPAL - 8 PEÇAS)   │
├────────────────────────────────────────────────────────┤
│ 5. BANNER DUPLO PROMOCIONAL (FEMININO x JEANS)         │
├────────────────────────────────────────────────────────┤
│ 6. NOVIDADES RECENTES (ÚLTIMOS LANÇAMENTOS - 4 PEÇAS)  │
├────────────────────────────────────────────────────────┤
│ 7. BANNER DA COMUNIDADE VIP WHATSAPP                   │
├────────────────────────────────────────────────────────┤
│ 8. DEPOIMENTOS DE CLIENTES / PROVA SOCIAL              │
└────────────────────────────────────────────────────────┘
```

### Detalhes de Cada Bloco da Página Inicial:

1. **Banner Principal Rotativo (1920x600px desktop / 800x800px mobile):**
   - *Banner 1:* "Nova Coleção Rô Modas — Peças Exclusivas com Caimento Perfeito do 36 ao 48" (Botão: "Ver Lançamentos").
   - *Banner 2:* "Linha Jeans Elegance — Cintura Alta e Máximo Conforto" (Botão: "Comprar Jeans").
   - *Banner 3:* "Retirada Grátis em Matão & Frete Rápido para Todo o Brasil" (Botão: "Conhecer a Loja").
2. **Régua de Benefícios (Ícones com Textos Curtos):**
   - *Benefício 1:* **Retirada Grátis** — Passe na loja física da Av. 15 de Novembro, 2516.
   - *Benefício 2:* **Entrega por Motoboy** — Receba no mesmo dia em Matão.
   - *Benefício 3:* **Pix com Desconto** — Economize 5% pagando à vista.
   - *Benefício 4:* **Troca Fácil em 7 Dias** — Garantia e tranquilidade na sua compra.
3. **Pílulas de Categorias Principais:**
   - Círculos ou retângulos com foto limpa de cada departamento: `Vestidos`, `Jeans`, `Conjuntos`, `Infantil`, `Calçados`.
4. **Produtos em Destaque:**
   - Exibir 8 produtos em grade (4 colunas no computador, 2 colunas no celular).
5. **Banner da Comunidade VIP do WhatsApp:**
   - Imagem chamativa com botão: *"Entre no Grupo VIP e receba as novidades com 24h de antecedência"*.

---

## 5. Lista de Produtos & Detalhe do Produto

### 5.1. Lista de Produtos
- **Proporção das Fotos:** Vertical / Retangular (proporção **3:4** ou **2:3**) — *É o padrão da moda; fotos quadradas cortam vestidos e calças longas*;
- **Efeito ao Passar o Mouse:** Exibir a segunda foto do produto (foto nas costas ou detalhe da costura);
- **Quantidade de Produtos por Linha:**
  - No celular: **2 produtos por linha**;
  - No computador: **4 produtos por linha**.

### 5.2. Detalhe do Produto (Página da Peça)
- **Seletor de Variações:** Configurar como **Botões de Tamanho (P, M, G, GG ou 36 a 48)** e **Amostras de Cor**, em vez de menu suspenso (dropdown);
- **Botão de Compra:** Fixo na parte inferior da tela do celular (facilita o clique imediato com o polegar);
- **Cálculo de Frete:** Exibir o campo de CEP aberto logo abaixo do botão de compra.

---

## 6. Carrinho de Compras

No menu **Configurações avançadas > Carrinho de compras**:
- **Tipo de Carrinho:** Selecionar **Carrinho Lateral (Gaveta / Quick Cart)**.
  - *Por que a gaveta lateral?* Quando a cliente clica em "Comprar", uma aba lateral se abre suavemente sem tirar a cliente da página. Isso permite que ela adicione mais peças (por exemplo, um vestido e uma peça infantil) sem perder a navegação!

---

## 7. Rodapé da Página

No menu **Configurações avançadas > Rodapé da página**:

- **Texto Institucional:**
  > *Rô Modas — Moda feminina, infantil, masculina e jeans com qualidade e preço justo. Mais de 20 anos vestindo famílias com estilo e carinho.*
- **Informações Obrigatórias de Atendimento:**
  - *Endereço:* Avenida Quinze de Novembro, 2516 — Bairro Alto, Matão - SP, CEP 15997-074
  - *WhatsApp Oficial:* (16) 99768-3630
  - *Horário de Atendimento:* Segunda a Sexta das 09h às 18h | Sábados das 09h às 15h
- **Formas de Pagamento e Envio:**
  - Marcar as bandeiras: Pix, Visa, Mastercard, Elo, Hipercard, Correios e Motoboy.
