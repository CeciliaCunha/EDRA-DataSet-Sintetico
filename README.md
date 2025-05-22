# EDRA-DataSet-Sintetico

## 🚀 Objetivo

O objetivo deste repositório é centralizar:

- O dataset sintético gerado para simular as condições das missões da SAE AeroDesign.
- As anotações feitas com o software [AnyLabeling](https://github.com/ozendelait/AnyLabeling).
- Scripts de apoio para conversão de anotações, organização de dados e preparação para treino de modelos.
- Notebooks para treinamento e validação utilizando o YOLOv11 no Google Colab.

## 🔗 Branches

- `main` — Versão estável do projeto, com dataset e scripts validados.
- `dev` — Desenvolvimento de scripts, testes e melhorias.
- `annotations` — Branch focada nas anotações do dataset (geração e ajustes).

## 📦 Dataset

As imagens estão organizadas na pasta `dataset/images`. As anotações são feitas utilizando o **AnyLabeling**, com suporte à segmentação automática.

## 🏗️ Como colaborar

1. Crie uma branch a partir da `dev` ou `annotations`:
   ```bash
   git checkout -b nome-da-sua-branch
