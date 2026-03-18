# 🚀 Simulador de Alavancagem de Crédito - Ademicon Joinville

[cite_start]Este projeto é uma ferramenta de simulação financeira desenvolvida para auxiliar consultores da **Ademicon** (Unidade Joinville) na criação de propostas de alavancagem de crédito[cite: 21]. [cite_start]O sistema permite simular múltiplas fases de contemplação, calculando de forma precisa os valores de entrada, parcelas e taxas de transferência[cite: 5, 11].

## 🛠️ Tecnologias Utilizadas

* [cite_start]**HTML5/CSS3:** Estrutura e interface personalizada com tema Dark (Preto/Vermelho) e layout responsivo[cite: 7, 18].
* [cite_start]**JavaScript (Vanilla):** Lógica financeira e manipulação dinâmica do DOM para inclusão de fases[cite: 13].
* [cite_start]**CSS Print:** Otimização para geração de PDFs profissionais com papel timbrado e rodapé fixo[cite: 23, 24].

## 📊 Diferenciais Técnicos

### 1. Precisão Financeira (Lógica HP12C)
[cite_start]Diferente de simuladores comuns, este projeto utiliza a fórmula de **Amortização Progressiva (Tabela Price)** para replicar exatamente o comportamento de uma calculadora financeira HP12C[cite: 5, 14]. 

O cálculo da parcela (PMT) é baseado no Saldo Devedor ($PV$), onde:
$$PV = Crédito Total - Valor de Entrada$$

### 2. Alavancagem Multi-Fase
[cite_start]O sistema permite a inclusão de até 5 fases em uma única página de PDF, onde cada fase pode utilizar o crédito da anterior como base para novas estratégias de investimento[cite: 12, 16].

### 3. Personalização de Saída
* [cite_start]**Valor Líquido Editável:** Flexibilidade para ajustar o valor líquido conforme a necessidade real do grupo de consórcio[cite: 6, 9].
* [cite_start]**PDF Profissional:** Gerador de proposta com informações de contato e assinatura do sócio-gerente Anderson L. Marini[cite: 19, 20].

## 🚀 Como utilizar

1. Insira o **Crédito Inicial** e o **Prazo** desejado.
2. Clique em **"Gerar Proposta"**.
3. Utilize o botão **"Incluir Próxima Fase"** para simular a alavancagem manual.
4. Ajuste o **Valor Líquido** se necessário.
5. Clique em **"Imprimir PDF"** para gerar o documento final (Lembre-se de desmarcar "Cabeçalhos e rodapés" nas configurações de impressão do navegador).

---
Desenvolvido como ferramenta de suporte para a Ademicon - Joinville.