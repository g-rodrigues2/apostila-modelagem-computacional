# Modelagem Matemática com Apoio Computacional em Python

Apostila prática de **modelagem matemática** para a graduação, construindo do zero a descrição
de fenômenos que mudam com o tempo — da intuição matemática à simulação em Python — com aplicações
em biologia, bioprocessos e biotecnologia.

Cada capítulo traz **teoria**, **exemplos resolvidos no papel** e a **parte computacional** comentada,
usando NumPy, SciPy e Matplotlib.

## 📖 Ler online

As páginas estão publicadas via GitHub Pages:

- **Capítulo 1 — Equações Diferenciais Ordinárias** → [`docs/capitulo-1.html`]( -https://g-rodrigues2.github.io/apostila-modelagem-computacional/capitulo-1.html)
- **Capítulo 2 — Ajuste de Modelos a Dados** → [`docs/capitulo-2.html`](https://g-rodrigues2.github.io/apostila-modelagem-computacional/capitulo-2.html)
- **Capítulo 3 — Calibração Bayesiana e Seleção de Modelos** → [`docs/capitulo-3.html`](https://g-rodrigues2.github.io/apostila-modelagem-computacional/capitulo-3.html)


## 📓 Notebooks

| Capítulo | Notebook | Conteúdo |
|---|---|---|
| 1 | [`capitulo_1_equacoes_diferenciais.ipynb`](capitulo_1_equacoes_diferenciais.ipynb) | EDOs: crescimento exponencial e logístico, decaimento, equilíbrios e estabilidade, sistemas (Lotka-Volterra), bioprocessos (Monod) e cinética enzimática (Michaelis-Menten) com `solve_ivp`. |
| 2 | [`capitulo_2_ajuste_de_modelos.ipynb`](capitulo_2_ajuste_de_modelos.ipynb) | Mínimos quadrados, regressão linear, R²/RMSE, linearização, ajuste não linear (`curve_fit`) e calibração de EDOs a dados (`least_squares`). |
| 3 | [`capitulo_3_calibracao_bayesiana.ipynb`](capitulo_3_calibracao_bayesiana.ipynb) | Teorema de Bayes, verossimilhança e priors, posteriori em grade, Metropolis-Hastings do zero, `emcee` e diagnóstico de cadeias (trace, τ, burn-in), verificações preditivas a priori/a posteriori, bandas de incerteza, calibração global de coortes, comparação bayesiana entre grupos e seleção de modelos por BIC. |

## ▶️ Como executar

Requer Python 3.10+ com as bibliotecas científicas:

```bash
pip install numpy scipy matplotlib jupyter
pip install emcee          # necessário apenas para o Capítulo 3
jupyter notebook
```

Ou abra os notebooks diretamente no [Google Colab](https://colab.research.google.com/) — basta
fazer o upload do arquivo `.ipynb`.

## 🗂️ Estrutura

```
.
├── capitulo_1_equacoes_diferenciais.ipynb
├── capitulo_2_ajuste_de_modelos.ipynb
├── capitulo_3_calibracao_bayesiana.ipynb
├── docs/                # páginas HTML (GitHub Pages)
│   ├── index.html
│   ├── capitulo-1.html
│   ├── capitulo-2.html
│   └── capitulo-3.html
└── README.md
```

## 📚 Referências

As referências bibliográficas completas estão ao final de cada capítulo.

## 📄 Licença

Conteúdo livre para uso educacional.
