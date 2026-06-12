# Face Anti-Spoofing com PatchNet (Seminário de Visão Computacional — UFG)

Este repositório contém a implementação e os notebooks desenvolvidos para o trabalho final da disciplina de **Visão Computacional** do Bacharelado em Inteligência Artificial da Universidade Federal de Goiás (UFG).

## Integrantes do Grupo
* Henrique M. M. Miranda
* Nickolas I. B. Silva (Nikolas)
* Victor P. S. Pires
* Luiany G. Carvalho

## Conteúdo do Repositório

* **`patchnet_experimento_real (nikolas) v2.ipynb`**: Notebook final contendo a resolução completa do problema com todos os experimentos e melhorias desenvolvidas:
  * **Experimento A:** Baseline (ResNet-18 com face inteira + Cross-Entropy)
  * **Experimento B:** PatchNet Puro (patches de alta resolução + AM-Softmax)
  * **Experimento C:** Proposta de Melhoria 1 — Ensemble estatístico simples (Baseline + PatchNet)
  * **Experimento D:** Proposta de Melhoria 2 — Arquitetura Global-Local de dois ramos (face inteira + patch) com AM-Softmax
* **`patchnet_experimento_real (nikolas).ipynb`**: Notebook da etapa preliminar.

## Dataset Utilizado
* **LCC-FASD** (*Large Crowd-collected Facial Anti-Spoofing Dataset*), disponível no Kaggle em `faber24/lcc-fasd`.
