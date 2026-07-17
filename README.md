
<h3 align="center">Programa de Pós-graduação em Engenharia Elétrica e de Computação (PPGEEC) <br>
Disciplina: Inteligência Computacional Aplicada (ICA) (BBP1026) - 2022.2 </h3>

<br>

Neste repositório, encontram-se os códigos implementados em cada projeto realizado na disciplina de ICA. Além disso, todos os códigos foram atualizados e melhorados. <br>

Ao todo foram realizados 03 (três) projetos ao longo da disciplina, conforme apresentado na Tabela a seguir:

| Projeto | Descrição | Link |
| --- | --- | --- |
| Seminário | Primeiro trabalho da disciplina: Apresentação do seminário| [Link para acesso](https://github.com/AlanMarquesRocha/ppgeec_inteligencia_computacional_aplicada/tree/master/t00_ica_semin%C3%A1rio)
| 1º projeto | Implementação de RNA-MLP e RBF para Análise de Sucesso Acadêmico| [Link para acesso](https://github.com/AlanMarquesRocha/ppgeec_inteligencia_computacional_aplicada/tree/master/t01_ica_rna_mlp_rbf)
| 2º projeto | Rede Neural Convolucional para Classificação de Imagens | [Link para acesso](https://github.com/AlanMarquesRocha/ppgeec_inteligencia_computacional_aplicada/tree/master/t02_ica_cnn)
| Projeto Final | Classificação de Defeitos em Células de Módulos Fotovoltaicos | [Link para acesso](https://github.com/AlanMarquesRocha/ppgeec_inteligencia_computacional_aplicada/tree/master/t03_ica_final_project)

<br>

Todas as implementações foram feitas através do ``Google Colab``, logo podem ser acessadas e replicadas em qualquer computador com acesso a internet. Em suma, os projetos foram desenvolvidos utilizando a linguagem ``Python`` e as libs ``TensorFlow``, ``Keras``, ``sklearn``, ``OpenCV`` e ``skimage``.

A seguir, será dada uma breve descrição de cada projeto desenvolvido na disciplina:

- **1º projeto: Implementação de RNA-MLP e RBF para Análise de Sucesso Acadêmico**

Neste projeto foi realizado a implementação de duas topologias de Redes Neurais Artificiais (RNA), a saber: Perceptron Múlti-camadas (MLP) e Radial Basis Function (RBF) para realizar a previsão de sucesso acadêmico de alunos de graduação do dataset **Predict students' dropout and academic success**, disponível nesse [link](https://archive-beta.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success). O cojunto de dados possui três classes desbalanceadas, logo foi necessário realizar técnicas de balanceamento de classes (SMOTE) para que os algoritmos realizassem o processe de aprendizagem de forma a evitar o overfitting.

---

- **2º Projeto: Rede Neural Convolucional para Classificação de Imagens**

Neste projeto, foi feita a implementação de uma Rede Neural Convolucional (do inglês, Convolutional Neural Network (CNN)) para realizar o processo de classificação de peças de roupas do conjunto de dados ``Fashion-MNIST``, disponível nesse [link](https://github.com/zalandoresearch/fashion-mnist). Com o projeto, foi possível averiguar através da implementação da rede os conceitos teóricos da CNN, como por exemplo: Camadas de convolução, pooling e camadas totalmente conectadas. O algoritmo proposto obteve uma acurácia de 0.92.

---

- **Projeto Final: Classificação de Defeitos em Células de Módulos Fotovoltaicos**

O projeto final da disciplina envolveu um estudo de caso dentro da área de pesquisa do PPGEEC. Neste caso, foi implementada uma CNN para classificação de defeitos em imagens de células fotovoltaicas (FVs) de silício monocristalino, classificando-as em funcionais (0.0) e defeituosas (1.0). Um processo de extração de atributos baseado em Padrão Binário Local (do inglês, Local Binary Pattern (LBP)) foi realizado para extrair as características das imagens das células, melhorando o processo de aprendizagem da rede. O algoritmo proposto, embora possua uma topologia simples, obteve uma acurácia de 0.88.

---
