# Global Study Brain Initiative 🧠🌐
### Análise de Evidência Clínica: Volume Ventricular vs. Severidade de Sintomas

Este repositório contém o pipeline de análise quantitativa utilizado para correlacionar o volume dos ventrículos laterais (mensurado via segmentação 3D) com a escala de severidade neurológica em coortes clínicas (Controles vs. Patológicos).

---

### 📊 Metodologia e Tecnologias

* **Linguagem:** R (v4.5.3) & RStudio
* **Pacotes Principais:** `ggplot2`, `tidyverse`, `scales` para visualização e modelagem de alta resolução.
* **Ferramentas de Segmentação:** 3D Slicer / Formato NRRD.
* **Análise:** Modelagem de regressão linear para avaliação de biomarcadores estruturais.

---

### 📈 Resultados Obtidos

O gráfico gerado demonstra uma correlação linear positiva robusta entre o aumento volumétrico ventricular e o agravamento do score sintomático no grupo patológico.

![Clinical Evidence](brain_study_evidence_plot.png)

> **Interpretação Bioestatística:** A correlação linear positiva ($R^2 > 0.95$, $p < 0.001$) valida a dilatação ventricular bilateral como biomarcador morfométrico quantitativo sensível para estratificação de risco e seguimento clínico.

---

### 🏛️ Liderança e Governança Executiva

* **Iniciativa:** Global Study Brain Initiative
* **Liderança:** Chief Executive Officer (CEO)
* **Padrões e Princípios:** *Open Science*, Reprodutibilidade Estatística, Diretrizes PRISMA 2020 e Integridade Científica (ICMJE).
* **Licença:** MIT License (Código Aberto para Pesquisa e Ensino).
