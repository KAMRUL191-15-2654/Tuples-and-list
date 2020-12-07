# Tuples-and-list
lab work
{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "name": "Lab_Session_4 (3).ipynb",
      "provenance": [],
      "include_colab_link": true
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    }
  },
  "cells": [
    {
      "cell_type": "markdown",
      "metadata": {
        "id": "view-in-github",
        "colab_type": "text"
      },
      "source": [
        "<a href=\"https://colab.research.google.com/github/Meem2634/week-4-lab-report/blob/main/(4).ipynb\" target=\"_parent\"><img src=\"https://colab.research.google.com/assets/colab-badge.svg\" alt=\"Open In Colab\"/></a>"
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "dv5fgiINPQhy",
        "outputId": "42658691-a946-49ad-f5e4-a5f24998e919",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 67
        }
      },
      "source": [
        "#creating list of python\n",
        "\n",
        "lst1=[11,12,13,42,12.23,53.23,\"python\",[12,42,13]]\n",
        "print(lst1)\n",
        "lst2=[]\n",
        "print(lst2)\n",
        "lst3=list()\n",
        "print(lst3)"
      ],
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "[11, 12, 13, 42, 12.23, 53.23, 'python', [12, 42, 13]]\n",
            "[]\n",
            "[]\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "OzhLaNmjPibF",
        "outputId": "501d1c50-1af2-4d57-d149-e84f116b12ef",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 33
        }
      },
      "source": [
        "#iterating list of the oop\n",
        "\n",
        "lst1=[11,12,13,42,12.23,53.23,\"python\",[12,42,13]]\n",
        "for i in lst1:\n",
        "    print(i,end=' ')\n",
        "print('')"
      ],
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "11 12 13 42 12.23 53.23 python [12, 42, 13] \n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "KNxT03XVQl1s",
        "outputId": "e505c50d-49fb-4c68-b0f9-bab74dc52509",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 84
        }
      },
      "source": [
        "#iterating list  of the python expression\n",
        "\n",
        "lst0=[1,2,3,4,2.23,3.23,\"python\",[2,4,3]]\n",
        "print(lst0[2])\n",
        "print(lst0[6])\n",
        "print(lst0[-2])\n",
        "print(lst0[7])"
      ],
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "3\n",
            "python\n",
            "python\n",
            "[2, 4, 3]\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "068-O8s6RPqT",
        "outputId": "6ab584a5-8047-489f-b593-deb0a8663134",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 167
        }
      },
      "source": [
        "#List operations of the method to the oop\n",
        "\n",
        "lst1=[11,12,13,42,12.23,53.23,\"python\",[12,42,13]]\n",
        "\n",
        "print(len(lst1))                #len( ) gives the length of the list\n",
        "\n",
        "lst1.append([12,2,12,2])        #append( ) inserts an element to the end of the list\n",
        "print(lst1)\n",
        "\n",
        "lst1.insert(12,\"panda\")         #insert( ) insertes an element on a given index\n",
        "print(lst1)\n",
        "\n",
        "lst1.remove(13)                  #remove( ) removes first occurence of an element\n",
        "print(lst0)\n",
        "\n",
        "print(lst1.index(\"python\"))     #index( ) returns index of first occurence of an element\n",
        "\n",
        "print(lst1.count('pandas'))     #count( ) reuturns the number of occurence of an element\n",
        "\n",
        "print(lst1.reverse())           #reverse( ) makes a reverse list\n",
        "\n",
        "lst1=lst0.copy()                #copy( ) makes a copy of list\n",
        "print(lst1)\n",
        "\n",
        "lst0.clear()                    #clear( ) makes the list empty\n",
        "print(lst0)"
      ],
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "8\n",
            "[11, 12, 13, 42, 12.23, 53.23, 'python', [12, 42, 13], [12, 2, 12, 2]]\n",
            "[11, 12, 13, 42, 12.23, 53.23, 'python', [12, 42, 13], [12, 2, 12, 2], 'panda']\n",
            "[1, 2, 3, 4, 2.23, 3.23, 'python', [2, 4, 3]]\n",
            "5\n",
            "0\n",
            "None\n",
            "[1, 2, 3, 4, 2.23, 3.23, 'python', [2, 4, 3]]\n",
            "[]\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "Efc_Q8FCU1RZ",
        "outputId": "909e933e-2e23-4e17-a1d8-457c4724f861",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 84
        }
      },
      "source": [
        "#lsit slicing of the oop\n",
        "\n",
        "lst0=[11,12,13,42,12.23,53.23,\"python\",[12,42,13]]\n",
        "\n",
        "print(lst0[2:7])\n",
        "print(lst0[2:])\n",
        "print(lst0[:5])\n",
        "print(lst0[:])"
      ],
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "[13, 42, 12.23, 53.23, 'python']\n",
            "[13, 42, 12.23, 53.23, 'python', [12, 42, 13]]\n",
            "[11, 12, 13, 42, 12.23]\n",
            "[11, 12, 13, 42, 12.23, 53.23, 'python', [12, 42, 13]]\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "VcznBtQPWFD1",
        "outputId": "cb64928a-0ffe-4970-9495-fa5a849bf33c",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 67
        }
      },
      "source": [
        "#list sorting\n",
        "\n",
        "lst1=[11,12,14,12,14,12,14,12,15,16,17,14]\n",
        "\n",
        "lst2=sorted(lst1)\n",
        "print(lst2)\n",
        "print(lst1)\n",
        "lst2.sort()\n",
        "print(lst1)"
      ],
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "[11, 12, 12, 12, 12, 14, 14, 14, 14, 15, 16, 17]\n",
            "[11, 12, 14, 12, 14, 12, 14, 12, 15, 16, 17, 14]\n",
            "[11, 12, 14, 12, 14, 12, 14, 12, 15, 16, 17, 14]\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "CsnsqMPsWn6m",
        "outputId": "cebd5e00-abc7-4dc4-fef0-e0deaaec864d",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 67
        }
      },
      "source": [
        "#creating tuple\n",
        "\n",
        "tp1=(11,12,13,42,12.23,53.23,\"python\",[12,42,13])\n",
        "print(tp1)\n",
        "tp2=()\n",
        "print(tp2)\n",
        "tp3=tuple()\n",
        "print(tp3)"
      ],
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "(11, 12, 13, 42, 12.23, 53.23, 'python', [12, 42, 13])\n",
            "()\n",
            "()\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "zqLQKHBrXNxY",
        "outputId": "de175a23-7ec2-4328-8ceb-097da02fcea4",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 33
        }
      },
      "source": [
        "#iterating tuple\n",
        "\n",
        "tp1=(11,12,13,42,12.23,53.23,\"python\",[12,42,13])\n",
        "for i in tp1:\n",
        "    print(i,end=' ')\n",
        "print('')"
      ],
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "11 12 13 42 12.23 53.23 python [12, 42, 13] \n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "KZUEXf9KXyFq",
        "outputId": "237d90bd-28ea-4a94-f5e9-11be520ddf5c",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 84
        }
      },
      "source": [
        "#iterating tuple of the method\n",
        "\n",
        "tp1=(1,2,3,4,2.23,3.23,\"python\",[2,4,3])\n",
        "print(tp1[2])\n",
        "print(tp1[6])\n",
        "print(tp1[-2])\n",
        "print(tp1[7])"
      ],
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "3\n",
            "python\n",
            "python\n",
            "[2, 4, 3]\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "J0R9_6tYYU6j",
        "outputId": "220b75a8-9bde-42c6-fd87-47b205e3c1df",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 33
        }
      },
      "source": [
        "#inserting into tuple of the method\n",
        "\n",
        "tp1=(11,12,13,42,12.23,53.23,\"python\",[12,42,13])\n",
        "tp1+=(\"panda\",121312,13,121312,13)\n",
        "print(tp0)"
      ],
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "(11, 12, 13, 42, 12.23, 53.23, 'python', [12, 42, 13], 'panda', 121312, 13, 121312, 13)\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "ZWp59vSEZfJJ",
        "outputId": "e57f46ab-5a18-4ba6-b620-ee8033d91287",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 84
        }
      },
      "source": [
        "#unpacking sequences of the method\n",
        "\n",
        "lst1=[12,13,141213,1413]\n",
        "x,y,z,d=lst1\n",
        "print(x)\n",
        "print(y)\n",
        "print(z)\n",
        "print(d)"
      ],
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "12\n",
            "13\n",
            "141213\n",
            "1413\n"
          ],
          "name": "stdout"
        }
      ]
    },
    {
      "cell_type": "code",
      "metadata": {
        "id": "o-2Xal8TZ1mo",
        "outputId": "7237c4ca-509a-4f89-e317-5473540e5988",
        "colab": {
          "base_uri": "https://localhost:8080/",
          "height": 84
        }
      },
      "source": [
        "#unpacking sequences\n",
        "\n",
        "tp1=(12,13,141213,1413)\n",
        "x,y,z,d=tp1\n",
        "print(x)\n",
        "print(y)\n",
        "print(z)\n",
        "print(d)"
      ],
      "execution_count": null,
      "outputs": [
        {
          "output_type": "stream",
          "text": [
            "12\n",
            "13\n",
            "141213\n",
            "1413\n"
          ],
          "name": "stdout"
        }
      ]
    }
  ]
}
