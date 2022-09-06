Tema:
 - Programação Dinâmica

# PD_A_Escolha

**Conteúdo da Disciplina**: Programação Dinâmica<br>

## Alunos
|Matrícula | Aluno |
| -- | -- |
| 19/0125829 |  Ian Costa  |
| 19/0129221 |  Murilo Souto|

## Sobre 
Jogo desenvolvido em c++ utilizando a biblioteca sfml. O peso máximo de uma mochila é dado, a sua tarefa é escolher os itens que entraram nela. Você precisa realizar a melhor combinação para levar na mochila levando em consideração o peso do objeto e o valor do objeto.

## Screenshots
<table>
    <tr>
        <td>Jogo</td><td>Próxima Fase</td><td>Jogo</td>
    </tr>
    <tr>
        <td><img src="/1.png" width="200"></td><td><img src="/2.png" width="200"></td><td><img src="/3.png" width="200"></td>
    </tr>
</table>

## Instalação 
**Linguagem**: C++<br>
**Framework**: Drogon<br>
Sistema que utiliza APT:

##### Abra o terminal
- Baixe o projeto e entre no diretório
> $ git clone https://github.com/projeto-de-algoritmos/Greed_O_Rolo && cd Greed_O_Rolo
- Instale os requisitos
> $ ./instalacao.sh
- Ou instale manualmente
> $ sudo apt install git gcc g++ cmake libjsoncpp-dev uuid-dev openssl libssl-dev zlib1g-dev
> - Baixe o Framework
> $ git clone https://github.com/an-tao/drogon && cd drogon
- Baixe os submódulos
> $ git submodule update --init
- Crie uma pasta para o build
> $ mkdir build
- Entre na pasta
> $ cd build
- Compile
> $ cmake .. && $ make && sudo make install
- Entre no diretório build, compile, gere o executável e rode o programa
- Entre no build dentro do diretório rolo
> $ cd build && cmake .. && make && ./rolo
- Agora é só digitar no seu navegador o endereço 127.0.0.1:5055 

## Uso 
Após acessar o site, adicione um arquivo .txt e envie para o site. Após o processamento, ele já disponibilizará o arquivo .bin para você baixar.<br> Faça o mesmo procedimento para descompactar o arquivo .bin
