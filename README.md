![imagem inicial](https://github.com/ClarisseAlvarenga/imersao-dados-desafio-final/blob/main/Imagens/pharmacology1.jpg?raw=true)

# Desafio Final Imersão Dados

## **BUSCA DE COMPOSTOS QUE ATIVEM MECANISMOS DE ATIVAÇÃO GENÉTICOS DO TIPO INIBIDOR!**

Neste repositório você vai encontrar meu projeto final da 3ª Edição da Imersão Dados da Alura.

### **OBJETIVO**
O objetivo do programa é construir um projeto de Data Science com análise exploratória e desenvolvimento de um modelo de machine learning para auxiliar na descoberta de novos medicamentos, aplicando todo o conhecimento que você irá adquirir na imersão e criando um projeto no github.

 ### **ESCOPO**
O Escopo definido para este projeto foi um mecanismo específico de ação de um composto, no caso os mecanismos inibidores. Segundo o trabalho [Enzyme Inhibition: Mechanisms and Scope](https://cdn.intechopen.com/pdfs/36550/InTech-Enzyme_inhibition_mechanisms_and_scope.pdf) de Rakesh Sharma, os inibidores de enzima são compostos químicos de baixo peso molecular que reduzem ou inibem completamente a atividade catalisadora da enzima, seja de forma reversível ou permanente. O inibidor pode alterar um aminoácido, ou várias cadeias laterais requeridas pela atividade catalisadora da enzima. 

Ainda no mesmo estudo, Sharma nos lembra que no processo de descoberta de medicamentos, vários compostos são criados com o propósito de inibir enzimas específicas, ainda que haja outros mecanismos (como antitoxinas) que tenham ação semelhante. A descoberta de novos inibidores era feita totalmente manualmente, por tentativa e erro, numa busca por uma extensiva biblioteca de compostos. Nosso estudo tem por objetivo automatizar parte do processo, auxiliando cientistas a definir se um composto gera algum mecanismo de ação inibidor, para separá-lo dos mais de 30 tipos de mecanismos de ação, reduzindo o escopo de uma pesquisa.

### **NOSSOS DADOS**

Os dados a que temos acesso combina expressões gênicas e dados de viabilidade de células. Os dados se baseiam numa nova tecnologia que mede simultaneamente (numa amostra) as respostas aos medicamentos em 100 diferentes tipos de células (resolvendo o problema de identificar antecipadamente quais tipos celulares são melhores para um composto específico). Além disso, temos acesso às anotações de MOA de aproximadamente 5000 compostos.

O desafio do Kaggle de onde tiramos os dados é criar um classificador multilabel que determine os compostos que ativam uma ou mais de uma classe de MOA. A ideia seria determinar quais os MoAs ativados por um composto, a partir de sua assinatura genética.

No entanto, devido à escassez de tempo para a confecção deste projeto, nosso escopo será reduzido.

Fonte: [Kaggle](https://www.kaggle.com/c/lish-moa/overview/description)

Links úteis:

Materiais sobre **biologia** utilizados no projeto:

- [Drug discovery: passado, presente e futuro](https://docs.google.com/document/d/10EhrQBChlyYIcff3to7PrCQi5HcNk2r-zd2ZCKPtcz8/edit?usp=sharing)
- [Expressão gênica: o caminho da informação biológica](https://docs.google.com/document/d/1TR-Q1cb2k_-S_MZC-60PMN2CbVGZbLMKT0Lr_didPY0/edit?usp=sharing)
- [Enzyme Inhibition: Mechanisms and Scope](https://cdn.intechopen.com/pdfs/36550/InTech-Enzyme_inhibition_mechanisms_and_scope.pdf)

Relatório gerado pelo Sweetviz:
- [Sweetviz_Experimentos](https://1drv.ms/u/s!AohJMgiIw---kBrkDpNoclLSJG0M?e=tCUa8g)

Materiais usados no desenvolvimento do **README**:

- [Criando anotações com Markdown](https://www.alura.com.br/artigos/criando-anotacoes-com-markdown)\

