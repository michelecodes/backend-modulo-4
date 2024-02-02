# Módulo 4

- Conteúdo da aula: [Modulo 4.pptx](https://github.com/michelecodes/backend-modulo-4/files/14135020/Modulo.4.pptx)

- Sites acessados: https://spring.io/tools

- Conteúdos extras:

### Java no VS Code:
1. Instale o Java Development Kit (JDK):
Certifique-se de ter o JDK instalado em seu sistema. Você pode baixá-lo e instalá-lo a partir do site oficial da Oracle ou de um distribuidor como o OpenJDK.

2. Instale o Visual Studio Code:
Se você ainda não tiver o VS Code instalado, baixe e instale-o a partir do site oficial: Visual Studio Code.

3. Instale a Extensão do Java para o VS Code:
Abra o VS Code e vá para a Visual Studio Code Marketplace. Procure por "Java Extension Pack" e instale-o. Esta extensão inclui várias ferramentas essenciais para o desenvolvimento Java no VS Code.

4. Crie um Novo Projeto Java:
Abra o VS Code e crie um novo diretório para o seu projeto. Em seguida, abra o terminal no VS Code (Ctrl + `) e navegue até o diretório do seu projeto.

5. Inicialize um Projeto Java com Maven (opcional):
Se você deseja usar o Maven para gerenciar as dependências do seu projeto, você pode inicializar um projeto Maven. No terminal, execute o seguinte comando:

bash
Copy code
mvn archetype:generate -DgroupId=com.example -DartifactId=myproject -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
Isso criará uma estrutura básica de projeto Maven.

6. Crie uma Classe Java:
Dentro do diretório do seu projeto, crie uma pasta chamada src/main/java/com/example (ou a estrutura equivalente, dependendo do seu groupId e artifactId) e, dentro dessa pasta, crie sua primeira classe Java. Por exemplo, crie um arquivo chamado MyClass.java:

java
Copy code
package com.example;

public class MyClass {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
7. Execute a Classe Java:
Abra o arquivo MyClass.java no VS Code e clique com o botão direito no código-fonte. Selecione "Run Java" para executar a classe.


# Exercício Java
