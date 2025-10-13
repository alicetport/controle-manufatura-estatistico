# 🎯 MVP

## 📋 Sobre o Projeto
MVP (Minimum Viable Product) desenvolvido para a disciplina de **Controle Estatístico de Processos**. Implementa sistema de Cartas de Controle para análise de qualidade em manufatura. O conjunto de dados analisado apresenta informações sobre 500 peças produzidas por cada um dos 20 operadores de uma indústria em um determinado período. Cada operador possui uma formação e um nível de treinamento distintos, o que permite observar diferenças nas dimensões das peças fabricadas. As variáveis analisadas incluem o número identificador da peça (Item_No), comprimento (Length), largura (Width), altura (Height) e o operador responsável pela produção (Operator).

## 🔗 Links do Projeto
- [**🔗 Google Colab - Código Executável**](https://colab.research.google.com/drive/12DMlvTqrunXDUG2UsAU9j05BKaPaX51L#scrollTo=GJ778wAvgaU3)
- [**📊 Dataset Original: "Parts Manufacturing - Industry Dataset"**](https://www.kaggle.com/datasets/gabrielsantello/parts-manufacturing-industry-dataset)


## 📊 Resultados Obtidos

### 📈 Análise das Variáveis:
| Variável | Status | Linha Central | LSC | LIC | Observação |
|----------|--------|---------------|-----|-----|------------|
| **Comprimento** | ⚠️ Instável | 99.77 | 104.40 | 95.14 | Alta variabilidade |
| **Largura** | ✅ Estável | 49.93 | 52.55 | 47.32 | Processo controlado |
| **Altura** | ✅ Estável | 20.29 | 21.66 | 18.93 | Baixa variabilidade |

### 🎯 Conclusões:
- **66% do processo estável** (Largura e Altura)
- **Comprimento requer ajustes** - alta variação entre peças
- **Sistema eficaz** para detecção de problemas

## 👨‍💻 Autor
Maria Alice Teixeira Portilho - 232013069
