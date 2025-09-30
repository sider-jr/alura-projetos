{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": []
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "source": [
        "## Aula 1"
      ],
      "metadata": {
        "id": "oWwIJdTn3hUW"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "print(\"I Competição de Programação da Start\")"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "As7u4tl6vASU",
        "outputId": "1f85debe-4ab6-433e-e49d-88122e1c34d0"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "I Competição de Programação da Start\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "ano = \"II\"\n",
        "\n",
        "print(ano, \"Competição de Programação da Start\")"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "-kLPKftcxTAl",
        "outputId": "7a51392d-a057-4a8f-d9dc-7605bc5c7f8d"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "II Competição de Programação da Start\n"
          ]
        }
      ]
    },
    {
      "cell_type": "code",
      "source": [
        "print(f\"{ano} Competição de Programação da Start\")"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "WLUAVjl4xvuW",
        "outputId": "ef030785-6a16-4fdb-80d5-b6cc267ef6ff"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "II Competição de Programação da Start\n"
          ]
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "## Aula 2"
      ],
      "metadata": {
        "id": "f1KsTmx03lxi"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "Contexto:\n",
        "\n",
        "Uma escola está promovendo uma campanha de incentivo à leitura, em que cada estudante recebe pontos ao concluir livros. Esses pontos podem ser trocados por diferentes premios da escola. As categorias de livros têm valores de pontos diferentes:\n",
        "\n",
        "* Livro de ficção: 10 pontos\n",
        "* Livro de não-ficção: 8 pontos\n",
        "* Livro infantil: 6 pontos\n",
        "\n",
        "**Problema:**\n",
        "\n",
        "Rodrigo leu um livro de cada categoria. Agora ele quer saber quantos pontos acumulou com sua leitura.\n",
        "\n",
        "Nosso objetivo é criar um programa em Python que:\n",
        "\n",
        "* Armazene a pontuação de cada categoria de livro em uma variável.\n",
        "* Calcule o total de pontos acumulados por Rodrigo.\n",
        "* Mostre na tela o total de pontos acumulados por Rodrigo."
      ],
      "metadata": {
        "id": "UiUmhq023phx"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "livro_ficcao = 10\n",
        "livro_nficcao = 8\n",
        "livro_infantil = 6\n",
        "\n",
        "pontos_rodrigo = livro_ficcao + livro_nficcao + livro_infantil\n",
        "\n",
        "print(f\"Os pontos totais do Rodrigo são: {pontos_rodrigo}\")"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "GQRpxCIk4B_O",
        "outputId": "cad1f838-f515-4a70-9cc5-ef516de4b45c"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Os pontos totais do Rodrigo são: 24\n"
          ]
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "### Desafio\n",
        "\n",
        "Ana também participou da campanha e leu 2 livros de ficção e 5 livros infantis.\n",
        "\n",
        "Como podemos calcular o total de pontos de Ana? Será que é possível calcular o total de pontos acumulados por Rodrigo e Ana juntos?"
      ],
      "metadata": {
        "id": "SwK66FFS44_1"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "## Aula 3\n"
      ],
      "metadata": {
        "id": "EDZC6pjHbhA8"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "Divisão do tesouro: https://olimpiada.ic.unicamp.br/passadas/OBI2020/fase1/programacao-b/\n",
        "\n",
        "A turma do 2º ano encontrou um envelope cheio de figurinhas. Para garantir uma divisão justa, todos concordaram com a sugestão de João, o dono do envelope:\n",
        "\n",
        "Cada amigo, exceto João, deve receber exatamente o mesmo número de figurinhas. João deve receber o dobro da quantidade que cada amigo recebe. Pode ser que o fato de João ser o dono do envelope tenha ajudado a convencer os amigos, mas também contribuiu o fato de que, do jeito proposto, a divisão era exata, sem sobrar nem faltar figurinhas.\n",
        "\n",
        "**Problema:**\n",
        "\n",
        "Crie um programa que determine a quantidade de figurinhas que João recebeu, dado o número total de figurinhas no envelope e o número de amigos de João.\n",
        "\n",
        "**Entrada:**\n",
        "\n",
        "* A primeira linha contém um número inteiro `total_figurinhas`, que representa o número de figurinhas no envelope.\n",
        "* A segunda linha contém um número inteiro `numero_amigos`, que representa a quantidade de amigos de João (excluindo o próprio João)."
      ],
      "metadata": {
        "id": "Yd3mUA12bj7g"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "total_figurinhas = int(input(\"Digite o total de figurinhas: \"))\n",
        "numero_amigos = int(input(\"Digite o número de amigos: \"))\n",
        "\n",
        "figurinhas_amigos = total_figurinhas // (numero_amigos + 2)\n",
        "figurinhas_joao = 2 * figurinhas_amigos\n",
        "\n",
        "print(f\"João recebeu {figurinhas_joao} figurinhas.\")\n"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "aL5npKxJheU8",
        "outputId": "c2b64655-67b7-42c2-8c88-afd54d9315c6"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Digite o total de figurinhas: 100\n",
            "Digite o número de amigos: 5\n",
            "João recebeu 28 figurinhas.\n"
          ]
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "### Desafio\n",
        "\n",
        "Depois de dividir as figurinhas no recreio, João percebeu que ainda havia algumas figurinhas extras em sua mochila. Ele decidiu que essas figurinhas extras também devem ser distribuídas de forma justa entre ele e seus amigos, mantendo a mesma regra:\n",
        "\n",
        "Cada amigo recebe uma quantidade igual de figurinhas.\n",
        "João recebe o dobro da quantidade de figurinhas que cada amigo recebe.\n",
        "Ajude João a distribuir todas as figurinhas, incluindo as extras, de maneira justa, sem deixar nenhuma figurinha sobrando.\n",
        "\n",
        "Entrada\n",
        "\n",
        "* número total de figurinhas no envelope.\n",
        "* número de amigos de João (excluindo o próprio João).\n",
        "* número de figurinhas extras encontradas na mochila de João.\n",
        "* calcular a nova quantidade total de figurinhas, somando as extras.\n",
        "* dividir as figurinhas entre João e seus amigos, garantindo que João receba o dobro de figurinhas que cada amigo.\n",
        "exibir a quantidade de figurinhas que João recebeu."
      ],
      "metadata": {
        "id": "SPWpMScwjCrj"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "## Aula 4\n",
        "\n",
        "Bondinho - link: https://olimpiada.ic.unicamp.br/pratique/pj/2017/f1/bondinho/\n",
        "\n",
        "\n",
        "A turma de um colégio está organizando uma excursão para a serra e, para chegar ao pico da montanha, todos os alunos e monitores devem usar um bondinho. No entanto, a cabine do bondinho tem uma capacidade máxima de 50 pessoas por viagem.\n",
        "\n",
        "Você precisa criar um programa que verifique se todos os alunos e monitores podem ser transportados em apenas uma viagem.\n",
        "\n",
        "**Entrada**\n",
        "\n",
        "* Um número inteiro `numero_alunos`, representando a quantidade de alunos na excursão.\n",
        "* Um número inteiro `numero_monitores`, representando a quantidade de monitores na excursão."
      ],
      "metadata": {
        "id": "b1CiW6EUjo6L"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "numero_alunos = int(input(\"Digite a quantidade de alunos: \"))\n",
        "numero_monitores = int(input(\"Digite a quantidade de monitores: \"))\n",
        "resposta_positiva = \"Pode ir\"\n",
        "resposta_negativa = \"Não pode ir\"\n",
        "\n",
        "if numero_alunos + numero_monitores <= 50:\n",
        "  print(resposta_positiva)\n",
        "else:\n",
        "  print(resposta_negativa)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "O7W6sA7HodAk",
        "outputId": "d651b0ed-10f5-40e1-a383-c5d1b9164265"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Digite a quantidade de alunos: 10\n",
            "Digite a quantidade de monitores: 10\n",
            "Pode ir\n"
          ]
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "### Desafio\n",
        "\n",
        "Agora, imagine que infelizmente o bondinho que carrega 50 pessoas está em manutenção e agora todo mundo vai precisar usar um bondinho menos sofisticado e ele só pode levar 30 pessoas. Além disso, 8 professores do colégio também vão participar da excursão. Como fazemos para garantir que o número total de pessoas no bondinho (alunos, monitores e professores) não ultrapasse a capacidade máxima de 30 pessoas?\n",
        "\n",
        "Seu desafio é escrever um programa que verifique se é possível ou não levar todos em apenas uma viagem."
      ],
      "metadata": {
        "id": "jHx2aNirp7wu"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "## Aula 5\n",
        "\n",
        "**Flíper:** https://olimpiada.ic.unicamp.br/pratique/pj/2014/f1/fliper/\n",
        "\n",
        "\n",
        "Flíper é um jogo em que uma bolinha de metal cai por um labirinto até chegar à parte de baixo. O jogador ganha pontos dependendo do caminho que a bolinha percorre. Ele pode controlar o trajeto da bolinha movendo algumas portinhas no labirinto. Cada portinha pode estar em duas posições: 0 (virada para a esquerda) ou 1 (virada para a direita).\n",
        "\n",
        "No flíper mostrado na imagem, há duas portinhas. A portinha P está na posição 1 (virada para a direita) e a portinha R está na posição 0 (virada para a esquerda). Isso faz com que a bolinha caia no caminho B.\n",
        "\n",
        "O programa que você deve escrever precisa, dado o valor das posições de P e R, informar por qual dos três caminhos (A, B ou C) a bolinha vai cair.\n",
        "\n",
        "**Entrada**\n",
        "\n",
        "As entradas correspondem a um valor inteiro P (0 ou 1) e um valor inteiro R (0 ou 1) que indicam as posições das portinhas do flíper.\n",
        "\n"
      ],
      "metadata": {
        "id": "wd9oUhCYqW2u"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "![image.png](data:image/png;base64,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PpyJJw7LRIbzOhJAYDqmRs8FETDbXlu3bv3qV786b968TIxwWCYynNeOAALTLjIaLoiA2fbauXPn17/+dcuyioqK3nzzzUykcFgmMpzXiwAC0ysvui2IgNn22rp169lnny0+vPg3v/lNdlI4LDsfrmpBAIFpERNNekDAbHt9+OGHudtL0MRhHuwqSgRKAIEFip/J/SIQHnv99re/zR3q7t27v/GNbzh/cSYWiz3//PO5D+dOCARLAIEFy5/Z/SCAvbJQbm5uxmFZ+HBJZQIITOV06M0DAorYKx6PNzQ0LFq06MCBA4mr+vnPf37DDTfccsstTz311HvvvZd4KZfjDz/88KyzzhIvoe68885chqTeg8NSmXBGCwIITIuYaNIlARXs9Yc//GHkyJFdu3bt3bv3lVdeuXXr1sTFPPzww3fdddesWbMmTJgwcuTIxEsdHntiLzELDuuQNjcoSACBKRgKLXlDQAV72ba9/PjXoUOH8l3VihUr5s6d+8knn6QduGXLlsJfeyVWxmGJNDjWggAC0yImmsybgJ/2Wrx4cXNzs2ixpaXl4YcfzrvddAPWr1//r//6rxUVFT/72c8+/vhjccuuXbv++Mc/Jtrrd7/7XbrRbs7hMDfUGBMcAQQWHHtmlkbAT3utX7++srJy27ZtbW1tv/vd76qqqm644YZ4PO7V4pqamqZPn15VVbV7927btrdt21ZRUXHGGWeIf/fy0F6iYRzmVXDU8YEAAvMBMlP4SsBPex07dmzw4MHz5s179dVXe/fuPW7cuI0bN8pY7d69e0XZhoaGrl27CnvdddddMubCYTKoUlMGAQQmgyo1AyPgp71s254/f/6FF1549OjR1157bdmyZe3t7W1tbTIW39bW1t7e3tDQ0LNnT2Gv7373uzImEjVxmDy2VPaQAALzECalAibgs70++uijr3zlK85731966aWBAwd69Q9gSSgfeOCBvn37VlVVCXv17du3a9eu27ZtS7rNw4c4zEOYlJJEAIFJAktZvwn4bC/btseMGXPrrbfatr169eqhQ4eef/75K1askLTshoYGx17XXnvt7NmzTz311KFDh3r4j22pneOwVCacUYoAAlMqDppxScB/ez399NOVlZXvvvvuxIkTzzzzzNra2vb2dpfddzQs8SeHkydPPvvss8eNG3frrbd26dLlwQcf7Gh0Qddx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)"
      ],
      "metadata": {
        "id": "-LxGAw-XvT_x"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "p = int(input(\"Digite a posição da porta (0 ou 1):\"))\n",
        "r = int(input(\"Digite a posição da porta (0 ou 1):\"))\n",
        "\n",
        "if p==0 and r==0:\n",
        "  print(\"C\")\n",
        "elif p==0 and r==1:\n",
        "    print(\"C\")\n",
        "elif p==1 and r==1:\n",
        "  print(\"A\")\n",
        "else:\n",
        "  print(\"B\")"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "5Iw3f45Sy3qM",
        "outputId": "9fe38478-3165-4f0c-a590-e384848e7873"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "name": "stdout",
          "text": [
            "Digite a posição da porta (0 ou 1):1\n",
            "Digite a posição da porta (0 ou 1):0\n",
            "B\n"
          ]
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "### Desafio\n",
        "\n",
        "Agora, imagine que o jogo de flíper ficou mais complexo e há 3 portinhas que podem influenciar o caminho da bolinha.\n",
        "\n",
        "As portinhas funcionam da seguinte forma:\n",
        "\n",
        "* A portinha P decide entre os caminhos iniciais.\n",
        "* A portinha R ajusta o trajeto no meio.\n",
        "* Uma nova portinha Q foi adicionada. Ela define se o caminho final incluirá uma letra extra, D, quando estiver na posição 1.\n",
        "\n",
        "Atualize o programa para incluir a lógica da terceira portinha:\n",
        "\n",
        "Se a portinha Q estiver na posição 1, deve ser exibida a letra D.\n",
        "No final do programa, continue imprimindo o caminho completo como antes."
      ],
      "metadata": {
        "id": "x3VImxWm0jdh"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "## Aula 6\n",
        "\n",
        "**Problema:** https://olimpiada.ic.unicamp.br/pratique/pj/2019/f1/idade/\n",
        "\n",
        "Dona Mônica é mãe de três filhos com idades diferentes. Este ano, a soma das idades de seus três filhos é igual à idade dela.\n",
        "\n",
        "Você deve escrever um programa que, dada a idade de Dona Mônica e as idades conhecidas de dois de seus filhos, determine a idade do terceiro filho e identifique quem é o mais velho.\n",
        "\n",
        "**Entrada**\n",
        "\n",
        "* Um número inteiro `idade_monica` representando a idade de Dona Mônica.\n",
        "* Um número inteiro `idade_filho1` representando a idade de um dos filhos.\n",
        "* Um número inteiro `idade_filho2` representando a idade de outro filho."
      ],
      "metadata": {
        "id": "Fm4esSgd1U0a"
      }
    },
    {
      "cell_type": "code",
      "source": [
        "def calcula_idade_maior(idade_monica, idade_filho1, idade_filho2):\n",
        "  idade_filho3 = idade_monica - idade_filho1 - idade_filho2\n",
        "\n",
        "  idade_maxima = max(idade_filho1, idade_filho2, idade_filho3)\n",
        "\n",
        "  return idade_filho3, idade_maxima\n",
        "\n",
        "calcula_idade_maior(68, 12, 30)"
      ],
      "metadata": {
        "colab": {
          "base_uri": "https://localhost:8080/"
        },
        "id": "EBIUtz6T5ftK",
        "outputId": "cff9aeaf-2884-487b-85b7-77392211c754"
      },
      "execution_count": null,
      "outputs": [
        {
          "output_type": "execute_result",
          "data": {
            "text/plain": [
              "(26, 30)"
            ]
          },
          "metadata": {},
          "execution_count": 24
        }
      ]
    },
    {
      "cell_type": "markdown",
      "source": [
        "### Desafio\n",
        "\n",
        "Agora imagine que nós queremos descobrir qual livro da biblioteca tem a maior quantidade de páginas.\n",
        "\n",
        "Para isso nós começamos com os 5 maiores livros que pegamos da biblioteca da escola.\n",
        "\n",
        "O nosso programa vai precisar receber 5 números inteiros que representa a quantidade de páginas e imprimir um único número representando o maior número de páginas entre ele.\n",
        "\n",
        "Para isso, vocês precisam escrever um código usando uma função def que vocês vão nomear da forma que vocês acharem mais correta."
      ],
      "metadata": {
        "id": "YqQG1RnV7hQA"
      }
    },
    {
      "cell_type": "markdown",
      "source": [
        "## Aula 8\n",
        "\n",
        "Nós resolvemos muitos problemas nessa unidade. Para resolver esse problema nós seguimos diversos caminhos, mas o essencial que precisamos considerar na hora de resolver problemas é:\n",
        "\n",
        "1. Ler o problema com calma e atenção e entender o que ele está pedindo de fato\n",
        "2. Identificar os dados fornecido\n",
        "3. Identificar o que precisa ser descoberto\n",
        "4. Planejar a solução (vou precisar de variáveis? funções? quais parametros, quais calculos são realizados, quais as entradas, quais as saídas)\n",
        "5. Resolver o problema"
      ],
      "metadata": {
        "id": "kqpSkfmT8N8N"
      }
    }
  ]
}
