# Manipulação de Arquivos

Este projeto demonstra como manipular arquivos e pastas usando Java, especificamente trabalhando com arquivos CSV. O programa lê dados de um arquivo CSV, realiza cálculos com base nesses dados e escreve os resultados em um novo arquivo CSV.

# Ferramentas Utilizadas:

O projeto utiliza as seguintes ferramentas e conceitos:

Java File I/O: O pacote java.io do Java é usado para lidar com operações de entrada e saída de arquivos. Ele fornece classes como File, FileReader, BufferedReader, FileWriter e BufferedWriter para ler e escrever em arquivos.

Formato de Arquivo CSV: O projeto assume que os dados estão armazenados em um formato de Valores Separados por Vírgula (CSV). O método split é usado para separar os valores com base no delimitador de vírgula.

# Funcionalidade:

O programa executa as seguintes etapas:

Solicitar ao usuário que insira o caminho do arquivo CSV de origem.

Criar um objeto File usando o caminho do arquivo fornecido.

Extrair o caminho da pasta do arquivo de origem usando o método getParent.

Criar uma nova pasta chamada "out" no mesmo diretório do arquivo de origem usando o método mkdir.

Definir o caminho do arquivo de destino como "out/summary.csv" dentro da pasta "out".

Ler os dados do arquivo CSV de origem usando um BufferedReader e FileReader.

Analisar cada linha do arquivo CSV e criar objetos Product com os dados extraídos.

Calcular o valor total para cada produto.

Escrever o nome do produto e o valor total no arquivo CSV de destino usando um BufferedWriter e FileWriter.

Exibir uma mensagem de sucesso se o arquivo de destino for criado, ou uma mensagem de erro se ocorrerem exceções durante o processo.

# Utilização:

Para usar este programa, siga estas etapas:

Clone o repositório em sua máquina local.

Abra o projeto em uma IDE ou compile o arquivo Program.java usando o compilador Java.

Execute o programa compilado.

Insira o caminho do arquivo CSV de origem quando solicitado.

Verifique o arquivo "out/summary.csv" no mesmo diretório para visualizar os resultados.

Certifique-se de que o arquivo CSV de origem contenha dados válidos no formato esperado para garantir o bom funcionamento do programa.

--------------------------------

# File Manipulation

This project demonstrates how to manipulate files and folders using Java, specifically working with CSV files. 
The program reads data from a CSV file, performs calculations based on the data, and writes the results to a new CSV file.

# Tools Used:

The project utilizes the following tools and concepts:

Java File I/O: The Java java.io package is used to handle file input and output operations. It provides classes like File, FileReader, BufferedReader, FileWriter, and BufferedWriter to read from and write to files.

CSV File Format: The project assumes that the data is stored in a Comma-Separated Values (CSV) format. The split method is used to separate the values based on the comma delimiter.

# Functionality:

The program performs the following steps:

Prompt the user to enter the file path of the source CSV file.

Create a File object using the provided file path.

Extract the folder path of the source file using the getParent method.

Create a new folder named "out" in the same directory as the source file using the mkdir method.

Define the target file path as "out/summary.csv" within the "out" folder.

Read the data from the source CSV file using a BufferedReader and FileReader.

Parse each line of the CSV file and create Product objects with the extracted data.

Calculate the total value for each product.

Write the product name and total value to the target CSV file using a BufferedWriter and FileWriter.

Display a success message if the target file is created, or an error message if any exceptions occur during the process.

# Usage:

To use this program, follow these steps:

Clone the repository to your local machine.

Open the project in an IDE or compile the Program.java file using the Java compiler.

Run the compiled program.

Enter the file path of the source CSV file when prompted.

Check the specified "out/summary.csv" file in the same directory to view the results.

Please make sure that the source CSV file contains valid data in the expected format to ensure proper functionality.
