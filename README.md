# Processo Seletivo Universidade Stark

## Descrição do Projeto

Este projeto foi desenvolvido como parte de um trabalho prático da disciplina **Algoritmos e Estruturas de Dados** da PUC Minas. O objetivo é implementar um sistema para gerenciar o processo seletivo da Universidade Stark, onde cada curso possui um número restrito de vagas e os candidatos são classificados com base na média simples das notas obtidas nas provas de Redação, Matemática e Linguagens.

## Funcionalidades

O programa oferece as seguintes funcionalidades:

- **Cálculo da média das notas:** A média simples das notas das provas de Redação, Matemática e Linguagens é utilizada para classificar os candidatos.
- **Critério de desempate:** Em caso de empate nas médias, a nota da Redação é utilizada como critério de desempate.
- **Gerenciamento de filas de espera:** Candidatos não selecionados para sua primeira opção de curso são colocados em filas de espera, seguindo regras específicas para inclusão.
- **Geração de relatórios:** O programa gera um arquivo de saída contendo a lista de candidatos selecionados e a fila de espera para cada curso, em ordem decrescente de nota.

## Estrutura do Projeto

O projeto está organizado em várias classes para facilitar a manutenção e compreensão do código. As principais classes são:

- **Curso:** Representa um curso da universidade, contendo informações sobre o código do curso, nome, número de vagas e a lista de candidatos selecionados e na fila de espera.
- **Candidato:** Armazena as informações de um candidato, como nome, notas das provas e as opções de curso.
- **GerenciadorDeProcessoSeletivo:** Classe principal responsável por gerenciar o processo seletivo, incluindo a leitura do arquivo de entrada e a geração do arquivo de saída.
- **ListaSimples:** Implementação de uma lista flexível para armazenar os candidatos e cursos.
- **Fila:** Implementação de uma fila flexível para gerenciar a fila de espera dos cursos.

## Entrada e Saída

- **Arquivo de Entrada (entrada.txt):** O arquivo de entrada contém as informações dos cursos e candidatos, conforme o formato especificado.
- **Arquivo de Saída (saida.txt):** O arquivo de saída é gerado pelo programa, contendo a lista de candidatos selecionados e as filas de espera para cada curso, em ordem decrescente de nota.

## Desenvolvimento

- **Estrutura de Dados:** Foi implementada uma estrutura de dados de Lista e Fila flexíveis para gerenciar os candidatos e as filas de espera.
- **Ordenação:** Utilizamos o método de ordenação [informe o método de ordenação escolhido] para organizar os candidatos em ordem decrescente de nota.
- **Desenvolvimento em Grupo:** O projeto foi desenvolvido em grupo, com cada integrante responsável por partes específicas do código.

## Testes

Realizamos diversos testes com diferentes cenários para garantir o funcionamento correto do programa. Os resultados foram validados conforme as regras especificadas no problema.

## Licença

Este projeto é de uso acadêmico e segue as diretrizes da PUC Minas para trabalhos práticos.


