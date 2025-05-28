# EDRA-DataSet-Sintetico - Branch Annotations

🗂️ **Branch dedicada às anotações do dataset**

Esta branch é destinada exclusivamente às imagens base utilizadas para anotação e aos arquivos de anotações gerados com o software **AnyLabeling**, no formato JSON.

## 📂 Estrutura da branch

```
Imagens_Labels
├───Bases
│   ├───Imagens
│   └───Label
├───Linha
│   ├───Imagens
│   └───Label
├───Mangueira
│   ├───Imagens
│   └───Label
└───Postes
    ├───Imagens
    └───Label
```

## 🏗️ Como foram feitas as anotações

- As anotações foram realizadas com o software **[AnyLabeling](https://github.com/lllyasviel/AnyLabeling)**, utilizando a ferramenta de **segmentação automática** para acelerar o processo.
- Cada arquivo JSON corresponde a uma imagem e contém informações de segmentação, bounding boxes ou classes, dependendo da configuração utilizada.

## 🔀 Conversão para outros formatos

> ⚠️ As anotações aqui estão no formato nativo do AnyLabeling (JSON).  
Para utilizar em frameworks como YOLO, COCO ou Pascal VOC, utilize os scripts disponíveis na branch `dev`.

## 🚀 Status

✔️ Anotações concluídas em andamento. Novas imagens e labels podem ser adicionados conforme necessidade.

## 🔗 Link útil

👉 [Google Colab - Treinamento do modelo](https://colab.research.google.com/drive/1KxAICycvb0RySuOXY7-nr1obotJ2oebA?usp=sharing)

*(O treinamento dos modelos utiliza as anotações presentes nesta branch.)*

## 🏗️ Como colaborar

1. Crie sua branch a partir da `annotations`:

```bash
git checkout annotations
git pull
git checkout -b nome-da-sua-branch
