# Modelagem Matemática com Apoio Computacional em Python

Apostila prática de **modelagem matemática** para a graduação, construindo do zero a descrição
de fenômenos que mudam com o tempo — da intuição matemática à simulação em Python — com aplicações
em biologia, bioprocessos e biotecnologia.

Cada capítulo traz **teoria**, **exemplos resolvidos no papel** e a **parte computacional** comentada,
usando NumPy, SciPy e Matplotlib.

## 📖 Ler online

As páginas estão publicadas via GitHub Pages:

- **Capítulo 1 — Equações Diferenciais Ordinárias** → [`docs/capitulo-1.html`](docs/capitulo-1.html)
- **Capítulo 2 — Ajuste de Modelos a Dados** → [`docs/capitulo-2.html`](docs/capitulo-2.html)

> Depois de ativar o GitHub Pages, o endereço será algo como
> `https://<seu-usuario>.github.io/<nome-do-repo>/`.

## 📓 Notebooks

| Capítulo | Notebook | Conteúdo |
|---|---|---|
| 1 | [`capitulo_1_equacoes_diferenciais.ipynb`](capitulo_1_equacoes_diferenciais.ipynb) | EDOs: crescimento exponencial e logístico, decaimento, equilíbrios e estabilidade, sistemas (Lotka-Volterra), bioprocessos (Monod) e cinética enzimática (Michaelis-Menten) com `solve_ivp`. |
| 2 | [`capitulo_2_ajuste_de_modelos.ipynb`](capitulo_2_ajuste_de_modelos.ipynb) | Mínimos quadrados, regressão linear, R²/RMSE, linearização, ajuste não linear (`curve_fit`) e calibração de EDOs a dados (`least_squares`). |
| 3 | *(em breve)* | Calibração bayesiana e seleção de modelos. |

## ▶️ Como executar

Requer Python 3.10+ com as bibliotecas científicas:

```bash
pip install numpy scipy matplotlib jupyter
jupyter notebook
```

Ou abra os notebooks diretamente no [Google Colab](https://colab.research.google.com/) — basta
fazer o upload do arquivo `.ipynb`.

## 🗂️ Estrutura

```
.
├── capitulo_1_equacoes_diferenciais.ipynb
├── capitulo_2_ajuste_de_modelos.ipynb
├── docs/                # páginas HTML (GitHub Pages)
│   ├── index.html
│   ├── capitulo-1.html
│   └── capitulo-2.html
└── README.md
```

## 📚 Referências

As referências bibliográficas completas estão ao final de cada capítulo.

## 📄 Licença

Conteúdo livre para uso educacional.
