# Estimativa de Posição GPS com Método de Newton

Este projeto simula a posição de um receptor GPS usando sinais enviados por satélites. Ele estima a posição tridimensional (x, y, z) e o erro do relógio (w) com dois métodos:

- 📌 **Mínimos Quadrados**: uma aproximação inicial baseada em um sistema linear.
- 🚀 **Método de Newton Multivariado**: refina a solução resolvendo um sistema não linear.

---

## ▶️ Executar no Google Colab

Você pode rodar o notebook diretamente online:

https://colab.research.google.com/drive/11CqpEyx04bhh8myteLhN3MDhgFNIafkI?usp=sharing

---

## 📂 Conteúdo

- `Cópia_de_EP1_GPS_Newton_KATHERYNE.ipynb` – Notebook com todo o passo a passo do projeto.
- `gps_newton_katheryne.html` – Versão HTML interativa do notebook.
- `README.md` – Este arquivo explicando o projeto.

## 📎 Tecnologias Utilizadas

- Python (NumPy, Matplotlib)
- Álgebra Linear e Otimização Numérica
- Visualização 3D com Matplotlib

## 🛰️ Visualização 3D

A simulação mostra:
- Satélites (pontos azuis)
- Estimativa por mínimos quadrados (verde)
- Estimativa refinada por Newton (vermelho)

---

© 2025 Katheryne Dias Lopes – Projeto acadêmico Poli-USP
