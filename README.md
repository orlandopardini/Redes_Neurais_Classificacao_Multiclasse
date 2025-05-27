# Classificação Multiclasse com Redes Neurais Artificiais (RNA)

As **Redes Neurais Artificiais (RNAs)** também podem ser aplicadas em tarefas de **classificação multiclasse**, onde o objetivo é identificar a qual entre várias categorias uma amostra pertence (ex: tipo de flor, espécie de animal, tipo de produto, etc.).

Nessas redes, a camada de saída possui **um neurônio por classe**, e geralmente usa a **função softmax** para transformar as ativações em probabilidades.

### Por que usar RNA para multiclasse?

- Lida bem com **relações complexas entre atributos e classes**
- Permite **previsão probabilística** para múltiplas categorias
- Altamente flexível e escalável para qualquer número de classes

### Funcionamento Intuitivo

Imagine uma rede que analisa a largura e o comprimento das pétalas de uma flor e consegue dizer se ela pertence à espécie *Setosa*, *Versicolor* ou *Virginica*. A RNA aprende padrões nos dados de treinamento e realiza previsões com base nos exemplos vistos.

---

## 📂 Estrutura dos Notebooks

### 1. `RNA1_Classificacao_Multiclasse_Simples_Orlando.ipynb`
**📌 Tarefa:** Classificação multiclasse com arquitetura simples  
**📚 Dataset:** Dataset multiclasse (como Iris ou similar)  
**🔍 Destaques:**
- RNA com saída softmax para múltiplas categorias
- Codificação one-hot das saídas
- Avaliação com matriz de confusão

### 2. `RNA2_Classificacao_Multiclasse_Validacao_Cruzada_Orlando.ipynb`
**📌 Tarefa:** Classificação multiclasse com validação cruzada  
**📚 Dataset:** Mesmo conjunto, com validação em `KFold`  
**🔍 Destaques:**
- Avaliação robusta por múltiplas execuções
- Cálculo de métricas por classe
- Comparação de desempenho entre execuções

---

## 📈 Métricas e Avaliação

Para classificação multiclasse, foram utilizadas:

- **Acurácia**
- **Matriz de confusão**
- **Precisão, Recall e F1-score macro e por classe**
- **Curva de aprendizado e validação**

---

## ⚙️ Técnicas Utilizadas

- Função de ativação **softmax**
- Codificação **one-hot**
- Otimizador **Adam**
- Visualizações com `Matplotlib` e `Seaborn`
"""
