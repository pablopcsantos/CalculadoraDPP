# Calculadora da Data Provável do Parto (DPP) - Regra de Naegele

O projeto é uma Calculadora da Data Provável do Parto (DPP) baseada na clássica Regra de Naegele. É uma ferramenta web educacional e interativa que vai além de fornecer a data final: ela detalha o cálculo passo a passo (dias, meses e anos). O aplicativo explica de forma didática o uso da Regra do +9 e da Regra do -3 para facilitar o estudo clínico.

## 🚀 Funcionalidades

* **Cálculo da DPP:** Insira a Data da Última Menstruação (DUM) e obtenha a data provável do parto automaticamente.
* **Passo a Passo Didático:** Explicação detalhada de como o cálculo matemático foi feito, dividindo o processo lógico em Dias, Meses e Anos.
* **Regra do +9 e Regra do -3:** Apresentação dinâmica de qual regra aplicar dependendo do mês da DUM (de Janeiro a Março ou de Abril a Dezembro).
* **Casos Extremos (Edge Cases):** Tratamento e explicação em tempo real de viradas de mês, viradas de ano e validação natural de anos bissextos.
* **Design Responsivo:** Interface limpa, voltada para a área da saúde (com *pattern* visual médico sutil) e totalmente adaptada para dispositivos móveis e desktops.
* **Cópia Rápida:** Botão utilitário para copiar rapidamente a data inserida para a área de transferência.

## 🛠️ Tecnologias Utilizadas

Este projeto é *Single File* (Arquivo Único) e não possui dependências externas, garantindo alta portabilidade e velocidade.

* **HTML5:** Estruturação semântica da página.
* **CSS3:** Estilização com uso de variáveis (Custom Properties), animações e design responsivo 100% nativo.
* **JavaScript (Vanilla):** Lógica principal de manipulação de datas, algoritmos condicionais didáticos e renderização dinâmica das explicações no DOM.

## ⚙️ Como Utilizar

1. Faça o download do arquivo `CalculadoradeNagele.html`.
2. Abra o arquivo em qualquer navegador web (Google Chrome, Firefox, Safari, Edge, etc.). *Não é necessário instalar nada nem rodar um servidor local.*
3. Selecione a **Data da Última Menstruação (DUM)** no seletor ou digite a data.
4. Clique no botão **Calcular DPP** (ou pressione a tecla *Enter*).
5. A tela revelará a data final projetada e a demonstração completa da matemática aplicada.

## 📖 Sobre a Regra de Naegele

A regra de Naegele é a fórmula matemática clássica padronizada na prática obstétrica para calcular a Data Provável do Parto:
1. **Dias:** Adiciona-se 7 dias ao dia da última menstruação (DUM).
2. **Meses/Anos:** 
   - **Regra do +9:** Para meses de Janeiro a Março, soma-se 9 meses (o ano do parto será o mesmo).
   - **Regra do -3:** Para meses de Abril a Dezembro, subtrai-se 3 meses e adiciona-se 1 ano (para compensar a transição do ano civil).
