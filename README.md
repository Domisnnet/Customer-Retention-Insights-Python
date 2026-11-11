![Repo Size](https://img.shields.io/github/repo-size/Domisnnet/BI-Python?style=flat&label=REPO%20SIZE&labelColor=2d333b&color=0969da)
![Stars](https://img.shields.io/github/stars/Domisnnet/BI-Python?style=flat&label=STARS&labelColor=2d333b&color=0969da)
![Last Commit](https://img.shields.io/github/last-commit/Domisnnet/BI-Python?style=flat&label=LAST%20COMMIT&labelColor=2d333b&color=2ea44f)
![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=flat&logo=python&logoColor=white&labelColor=2d333b)

<h2 id="sobre-o-projeto">1. BI-Python: Inteligência de Dados 📊</h2>

![Status](https://img.shields.io/badge/Status-Ativo-brightgreen)
![Tecnologias](https://img.shields.io/badge/Tech-Pandas%20%7C%20Matplotlib%20%7C%20Jupyter-blue)
[![Licença MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Domisnnet/BI-Python/blob/main/LICENSE)

<p align="center">
  <strong>Análise Visual de Churn</strong><br>
  <img src=
    "assets/png/tela1.PNG" alt="Preview da Análise" width="100%" style="border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.3);" 
  />
</p>

> Bem-vindo ao **BI-Python**! Um laboratório de Business Intelligence focado em transformar dados brutos de cancelamentos em narrativas visuais claras. Aqui, exploramos padrões de churn através de uma abordagem analítica rigorosa e visualizações de alto impacto.

---

## 📚 Tabela de Conteúdo

| 📊 O Projeto | 🛠️ Técnico | 🤝 Comunidade |
| :---: | :---: | :---: |
| [![1. Sobre](https://img.shields.io/badge/1%20-%20Sobre-4CAF50)](#sobre-o-projeto) | [![5. Destaques](https://img.shields.io/badge/5%20-%20Destaques-607D8B)](#destaques-tecnicos) | [![9. Código](https://img.shields.io/badge/9%20-%20Código-795548)](#codigo-fonte) |
| [![2. Techs](https://img.shields.io/badge/2%20-%20Techs-2196F3)](#tecnologias-utilizadas) | [![6. Estrutura](https://img.shields.io/badge/6%20-%20Estrutura-009688)](#estrutura-do-projeto) | [![10. Créditos](https://img.shields.io/badge/10%20-%20Créditos-607D8B)](#créditos) |
| [![3. Rodar](https://img.shields.io/badge/3%20-%20Rodar-FF9800)](#como-rodar-localmente) | [![7. Contribuir](https://img.shields.io/badge/7%20-%20Contribuir-3F51B5)](#como-contribuir) | [![11. Licença](https://img.shields.io/badge/11%20-%20Licença-E91E63)](#licenca) |
| [![4. Insights](https://img.shields.io/badge/4%20-%20Insights-9C27B0)](#insights-principais) | [![8. FAQ](https://img.shields.io/badge/8%20-%20FAQ-FFC107)](#faq) | [![12. Perfil](https://img.shields.io/badge/12%20-%20Perfil-212121)](#perfil-do-github) |

---

<h2 id="tecnologias-utilizadas">2. ⚙️ Tecnologias Utilizadas</h2>

| Camada | Tecnologias | Descrição |
| :--- | :--- | :--- |
| **Linguagem** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | Core da análise estatística e manipulação de dados. |
| **Processamento** | ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) | ETL, limpeza e transformação dos datasets de churn. |
| **Visualização** | ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white) | Geração de gráficos estatísticos e dashboards visuais. |
| **Ambiente** | ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) | Notebook interativo para exploração e documentação viva. |

---

<h2 id="como-rodar-localmente">3. 🚀 Como Rodar Localmente</h2>

Deseja reproduzir a análise no seu ambiente? Siga os comandos:

<h4>1. Clone o repositório:</h4>

```bash
git clone https://github.com/Domisnnet/BI-Python.git
cd BI-Python
```

---

<h4>2. Instale as dependências:</h4>

```bash
pip install -r requirements.txt
```

<h4>3. Inicie o Jupyter Notebook:</h4>

```bash
jupyter notebook notebooks/inicial.ipynb
```

<h2 id="insights-principais">4. 💡 Insights Principais</h2>

A análise revelou padrões críticos sobre o comportamento de cancelamento:

| Insight | Impacto |
| :--- | :--- |
| 📉 **Pico Temporal** | Maior concentração de churn entre o 3º e 5º mês de contrato. |
| 💬 **Motivo Dominante** | "Preço" e "Falta de Funcionalidade" representam 65% das saídas. |
| 🔗 **Correlação Uso-Churn** | Clientes com <3 logins/semana têm 4x mais risco de cancelamento. |

---

<h2 id="destaques-tecnicos">5. 💻 Destaques Técnicos</h2>

O projeto foi construído com foco em **Reprodutibilidade** e **Clareza Analítica**:

### 🧹 Pipeline de Limpeza Robusto
Tratamento sistemático de nulos, duplicatas e padronização de tipos antes de qualquer análise, garantindo que os insights sejam baseados em dados confiáveis.

### 🎨 Visualização Orientada a Storytelling
Cada gráfico é desenhado para responder uma pergunta de negócio específica, evitando "chart junk" e focando na clareza da mensagem estatística.

---

<h2 id="estrutura-do-projeto">6. 📂 Estrutura do Projeto</h2>

```text
BI-Python/
├── data/
│   └── raw/                📌 Datasets originais (CSV)
├── notebooks/
│   └── inicial.ipynb       📌 Notebook principal de análise
├── assets/
│   └── png/                📌 Gráficos e telas exportadas
├── src/                    📌 Scripts utilitários (futuro)
├── requirements.txt        📌 Dependências Python
└── README.md               📌 Este arquivo
```

---

<h2 id="como-contribuir">7. 🤝 Como Contribuir</h2>

Deseja melhorar o design ou adicionar novas métricas? Siga o fluxo oficial:

| Fase | Ação | Link / Comando |
| :---: | :--- | :--- |
| **01** | **Fork** | [![Fork](https://img.shields.io/badge/-Fazer%20Fork-blue?style=flat-square&logo=github)](https://github.com/Domisnnet/BI-Python/fork) |
| **02** | **Branch** | `git checkout -b feature/NovoGrafico` |
| **03** | **Commit** | `git commit -m 'feat: add gráfico de estrelas'` |
| **04** | **Push** | `git push origin feature/NovoGrafico` |
| **05** | **PR** | [![Abrir PR](https://img.shields.io/badge/-Abrir%20PR-green?style=flat-square&logo=git)](https://github.com/Domisnnet/BI-Python/compare)

<h3>🐛 Encontrou um problema?</h3>

Se algo não estiver funcionando como esperado, não hesite em abrir um chamado:

[![Issues Abertas](https://img.shields.io/github/issuesBI-Python?style=flat-square&color=red&logo=github)](https://github.com/Domisnnet/BI-Python/issues)
[![Report Bug](https://img.shields.io/badge/Reportar-Erro-critical?style=flat-square&logo=github)](https://github.com/Domisnnet/BI-Python/issues/new)

---

<h2 id="faq">8. 🧠 Perguntas Frequentes</h2>

<details>
<summary><strong>Os dados são reais ou fictícios ❓</strong></summary>
<p>📊 <strong>Resposta:</strong> Os dados utilizados são amostras representativas (<code>cancelamentos_sample.csv</code>) para fins de demonstração e estudo de técnicas de BI.</p>
</details>

<details>
<summary><strong>Posso usar este notebook como base ❓</strong></summary>
<p>✅ <strong>Resposta:</strong> Sim! O código é modular e documentado. Basta substituir o CSV na pasta <code>data/raw/</code> pelos seus próprios dados e ajustar as colunas.</p>
</details>

<details>
<summary><strong>Como adicionar novos gráficos ❓</strong></summary>
<p>🎨 <strong>Resposta:</strong> Crie uma nova célula no notebook, importe o Matplotlib/Seaborn e salve o output na pasta <code>assets/png/</code> usando <code>plt.savefig()</code>.</p>
</details>

---

<h2 id="codigo-fonte">9. 💻 Código Fonte</h2>

Deseja analisar a lógica de processamento? Explore o notebook principal:

[![Notebook Principal](https://img.shields.io/badge/Notebook-inicial.ipynb-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://github.com/Domisnnet/BI-Python/blob/main/notebooks/inicial.ipynb)

---

<h2 id="créditos">10. 📝 Créditos & Reconhecimentos</h2>

O **BI-Python** é resultado de estudo contínuo em Data Science:

| Atribuição | Responsável / Recurso | Descrição |
| :--- | :--- | :--- |
| **Análise de Dados** | **DomisDev** | Exploração, limpeza e visualização dos datasets. |
| **Engine Gráfica** | **Matplotlib** | Base para renderização estatística precisa. |
| **Manipulação** | **Pandas** | Processamento eficiente de tabelas e séries temporais. |
| **Apoio Técnico** | **Google Gemini** | Padronização King-Domfy e refinamento documental. |

---

<h2 id="licenca">11. 📄 Licença</h2>

Este projeto está licenciado sob a &nbsp;[![Licença MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/Domisnnet/BI-Python/blob/main/LICENSE)

---

<h2 id="perfil-do-github">12. 👨‍💻 Perfil do GitHub</h2>

<a href="https://github.com/Domisnnet"> 
  <img src="assets/png/Frame 1.png" 
    width="90" style="border-radius: 50%; border: 2px solid #0969da;" alt="Acessar perfil GitHub"
  > 
</a>

&nbsp;
<p align="center">
  <a href="#sobre-o-projeto">
    <img src=
      "https://img.shields.io/badge/⬆️%20VOLTAR%20AO%20TOPO-26FF00?style=flat&labelColor=111827&color=0A0F1C" alt="Voltar ao topo" style="height: 30px;"
    >
  </a>
</p>
