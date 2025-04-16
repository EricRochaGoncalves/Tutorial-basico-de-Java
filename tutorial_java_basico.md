
# Tutorial Básico de Java

## Introdução

Este é um tutorial básico de Java, ideal para quem está começando a aprender programação e deseja entender os fundamentos dessa linguagem poderosa e versátil. Vamos cobrir os conceitos essenciais e fornecer exemplos simples para que você possa começar a programar em Java de forma eficiente.

## 1. Instalação do Java

### Passo 1: Baixar e Instalar o JDK

Para começar a programar em Java, você precisa instalar o JDK (Java Development Kit). Siga os passos abaixo para instalar:

1. Acesse o [site oficial do JDK](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).
2. Baixe a versão correspondente ao seu sistema operacional.
3. Siga as instruções de instalação.

### Passo 2: Configurar o Ambiente

Após a instalação, você precisará configurar as variáveis de ambiente para poder usar o Java em qualquer diretório.

1. **No Windows**: Acesse as variáveis de ambiente e adicione o caminho para a pasta `bin` do JDK.
2. **No Linux/Mac**: Adicione o caminho do JDK ao seu arquivo `.bashrc` ou `.zshrc`:
    ```bash
    export PATH=$PATH:/caminho/para/o/jdk/bin
    ```

### Passo 3: Verificar a Instalação

Abra o terminal ou prompt de comando e execute:
```bash
java -version
```
Isso deve exibir a versão do Java instalada.

---

## 2. Primeiros Passos com Java

Vamos começar escrevendo o tradicional "Hello, World!" em Java.

### Exemplo 1: "Hello, World!" em Java

```java
// Este é um exemplo simples em Java que imprime "Hello, World!" no console.
public class HelloWorld {
    public static void main(String[] args) {
        // O método System.out.println é usado para exibir uma mensagem no console
        System.out.println("Hello, World!");
    }
}
```

### Explicação:
- `public class HelloWorld`: Define a classe principal do programa.
- `public static void main(String[] args)`: O método `main` é o ponto de entrada do programa.
- `System.out.println()`: Exibe a mensagem no console.

### Como compilar e executar:
1. Salve o arquivo como `HelloWorld.java`.
2. Abra o terminal e navegue até o diretório onde o arquivo está salvo.
3. Compile o programa:
   ```bash
   javac HelloWorld.java
   ```
4. Execute o programa:
   ```bash
   java HelloWorld
   ```

---

## 3. Variáveis e Tipos de Dados

Em Java, você pode armazenar diferentes tipos de dados em variáveis. Aqui estão alguns exemplos:

### Exemplo 2: Declaração de Variáveis

```java
public class Variaveis {
    public static void main(String[] args) {
        // Declarando variáveis de tipos diferentes
        int idade = 25; // inteiro
        double altura = 1.75; // ponto flutuante
        boolean isEstudante = true; // valor lógico
        String nome = "Eric"; // texto

        // Exibindo as variáveis no console
        System.out.println("Idade: " + idade);
        System.out.println("Altura: " + altura);
        System.out.println("É estudante? " + isEstudante);
        System.out.println("Nome: " + nome);
    }
}
```

### Explicação:
- `int idade`: Tipo de dado inteiro.
- `double altura`: Tipo de dado para números com casas decimais.
- `boolean isEstudante`: Tipo lógico, pode ser `true` ou `false`.
- `String nome`: Tipo de dado para texto.

---

## 4. Estruturas de Controle

As estruturas de controle permitem que você execute ações com base em condições.

### Exemplo 3: Condicional `if` e `else`

```java
public class Condicional {
    public static void main(String[] args) {
        int idade = 18;

        // Verificando se a pessoa é maior de idade
        if (idade >= 18) {
            System.out.println("Você é maior de idade.");
        } else {
            System.out.println("Você é menor de idade.");
        }
    }
}
```

### Explicação:
- `if (condição)`: Executa o bloco de código se a condição for verdadeira.
- `else`: Executa o bloco de código alternativo caso a condição não seja verdadeira.

---

## 5. Laços de Repetição

Os laços de repetição permitem executar um bloco de código várias vezes.

### Exemplo 4: Laço `for`

```java
public class Repeticao {
    public static void main(String[] args) {
        // Laço que imprime números de 1 a 5
        for (int i = 1; i <= 5; i++) {
            System.out.println("Número: " + i);
        }
    }
}
```

### Explicação:
- `for (int i = 1; i <= 5; i++)`: A variável `i` começa com 1 e vai até 5, incrementando de 1 em 1.

---

## 6. Métodos

Métodos são blocos de código que podem ser reutilizados.

### Exemplo 5: Método Simples

```java
public class Metodo {
    // Método que retorna a soma de dois números
    public static int somar(int a, int b) {
        return a + b;
    }

    public static void main(String[] args) {
        // Chamando o método somar
        int resultado = somar(3, 4);
        System.out.println("Resultado da soma: " + resultado);
    }
}
```

### Explicação:
- `public static int somar(int a, int b)`: Método que recebe dois parâmetros e retorna um valor do tipo `int`.
- `somar(3, 4)`: Chama o método passando os valores 3 e 4.

---

## Conclusão

Parabéns! Agora você já aprendeu alguns conceitos básicos de Java. Este é apenas o começo, e há muitos outros tópicos a explorar, como orientação a objetos, tratamento de exceções, coleções e muito mais. Continue praticando e explorando novos conceitos!

---

## Recursos Adicionais

- [Documentação Oficial do Java](https://docs.oracle.com/javase/8/docs/)
- [Tutorial de Java no W3Schools](https://www.w3schools.com/java/)
