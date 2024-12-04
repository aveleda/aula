# Plano de Aula

Título da Aula: Arquiteturas Paralelas

Duração: 50 minutos

Objetivos da Aula:
- Visão geral das arquiteturas paralelas 
- Compreender os conceitos fundamentais de arquiteturas paralelas na computação.
- Diferenciar entre as arquiteturas SIMD e MIMD.
- Entender as características das arquiteturas NUMA.
- Explorar as características dos clusters e das redes de interconexão.
- Entender o funcionamento e a importância dos sistemas de arquivos paralelos.

Estrutura da Aula:

1. Introdução (3 minutos)
- Boas-vindas e Apresentação do Tema: Introdução rápida ao assunto da aula.
- Explicar a importância das arquiteturas paralelas na eficiência do processamento computacional.

2. SIMD (Single Instruction, Multiple Data) (5 minutos)
- Conceito e Funcionamento: Explicar como o SIMD funciona com exemplos práticos (e.g., processamento de gráficos).

3. MIMD (Multiple Instruction, Multiple Data) (7 minutos)

a. Arquiteturas MIMD com Memória Compartilhada:
- Descrição e exemplos práticos, como sistemas multiprocessadores.

b. Arquiteturas MIMD com Memória Distribuída:
- Explicação sobre como a comunicação acontece entre nós diferentes.
- Exemplo de uso em supercomputadores.

4. Arquiteturas NUMA (Non-Uniform Memory Access) (5 minutos)
- Conceito e Vantagens: Explicar como NUMA melhora o acesso à memória em relação a sistemas SMP (Symmetric Multiprocessing).

5. Clusters de Computadores: (10 minutos)
- Introdução aos clusters e sua configuração típica.
- Exemplos de uso em ambientes de pesquisa e corporativos.

6. Redes de Interconexão: (10 minutos)
- Explicação sobre a importância das redes de alta velocidade na comunicação entre nós de um cluster.

7. Sistemas de Arquivos Paralelos (10 minutos)
- Conceito e Importância: Explanação sobre como sistemas de arquivos paralelos ajudam no acesso rápido e eficiente a grandes volumes de dados.
- Exemplos de Implementação: Discussão sobre sistemas como Lustre, BeeGFS, GPFS, e seus usos em HPC.

Resumo dos Tópicos: Recapitular os principais pontos discutidos na aula.

Material de Leitura Complementar:
- An Introduction to Parallel Programming, Peter S. Pacheco. Morgan Kaufmann, 2011.
- Programação Paralela e Distribuída com MPI, OpenMP e OpenACC para computação de alto desempenho, Gabriel P. Silva, Calebe P. Bianchini, Evaldo B. Costa, Casa do Código, 2022
