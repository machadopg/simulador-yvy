[README.md](https://github.com/user-attachments/files/29147723/README.md)
# Simulador Comercial — YVY Home

## Como publicar
Envie toda a pasta para uma hospedagem estática (Netlify, Vercel, GitHub Pages, servidor próprio ou similar). O arquivo inicial é `index.html`.

## Como usar
- O seletor de unidades exibe exclusivamente registros com status `DISPONIVEL`.
- Registros `VENDIDO` e `RESERVA TEC` ficam automaticamente fora da lista.
- **Financiamento bancário:** exibe as parcelas de entrada e o saldo estimado para financiar no banco.
- **Financiamento direto:** calcula parcelas mensais com juros padrão de 1% a.m., prazo de 0 (à vista) a 180 meses e balões anuais/semestrais opcionais.
- A entrada é sempre dividida em parcelas iguais: uma parcela é sinal e as demais são as parcelas de entrada. Ex.: 20% em 5x = sinal de 4% + 4 parcelas de 4%.

## Adaptar para outro empreendimento
Use o botão **Importar base** e selecione uma configuração JSON. Atualize no JSON:
- `brand`: nome e cores da marca;
- `units`: unidades, status e preços;
- `settings`: parâmetros-padrão do empreendimento.

A logo pode ser substituída em `assets/logo-yvy-home.png`. Para produzir uma versão definitiva para outro empreendimento, copie a pasta, troque a logo e atualize o JSON.

> Observação: o simulador é comercial e os valores devem passar por aprovação conforme as regras vigentes.
