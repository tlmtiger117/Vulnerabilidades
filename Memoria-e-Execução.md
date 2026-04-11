# 11/04/26
# Memória e Execução

- Memória(RAM): Onde os dados temporários de um programa são armazenados e repassados para o processador(CPU) executar os dados
                recebidos e armazenados.

- Execução: Fluxo de como os dados se comportam dentro da RAM.

- Stack: Guarda dados das funções em execução(função = execução específica do programa), principalmente:
   - pra onde o programa deve voltar depois (retorno, se é para o arquivo main(do programa), outra função, arquivo externo)
   - variáveis locais: (ex: ip, porta, serviço)
   - parâmetros:Valores que você passa pra uma função executar(ip,porta,timeout)

   - Ideia simples:
      - É o controle de “voltar pra linha certa do programa” depois de uma função.

- Heap: Guarda dados dinâmicos(variáveis que mudam de tamanho) enquanto o programa está rodando

   - dados que podem mudar de tamanho(dados/informações grandes recebidas)
   - dados que continuam existindo mesmo depois que a função termina

   - Ideia simples:
      - É um espaço pra guardar dados que precisam durar mais tempo

- Fluxo de execução: É o caminho que o programa segue

   - Ex:

      - começa no main
      - chama funções
      - volta pro main
      - segue executando funções.

   - Ideia simples:
      - é a ordem das “linhas” que o programa percorre

- Controle de execução: Decide qual é a próxima instrução (ou “linha do programa” seguir)

   - pode ser a próxima normal
   - pode pular (if, loop)
   - pode ir pra função
   - pode voltar (return)

    - Ideia simples:
       - É quem escolhe a próxima linha que vai rodar

Resumo:

   - Stack → guarda retornos(caminhos,main,arquivos externos) e dados das funções(ip,porta,timeout)
   - Heap → guarda dados dinâmicos (dados/informações grandes recebidos)
   - Fluxo → caminho do programa (main, função, retorno pro main)
   - Controle de execução → próxima linha a executar no programa



    

