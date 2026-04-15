---
layout: page
title: Fundamentos da Linguagem Java e JVM
---

# Fundamentos da Linguagem Java e JVM ☕

## 🎯 Objetivos de Aprendizagem
* Entender o histórico e a filosofia da linguagem Java.
* Compreender o conceito de **"Write Once, Run Anywhere"** (Escreva uma vez, execute em qualquer lugar).
* Identificar os componentes do ambiente Java: **JVM, JRE e JDK**.
* Criar e executar o primeiro programa ("Hello World").

---

## 📖 Conteúdo Teórico

### 1. O que é Java?
Criada pela Sun Microsystems em 1995 (hoje mantida pela Oracle), o Java é uma linguagem:
* **Orientada a Objetos:** Tudo é tratado como um objeto.
* **Portável:** Independente de plataforma.
* **Segura:** Possui mecanismos rigorosos de verificação de código.

### 2. A Máquina Virtual Java (JVM)
Diferente das linguagens puramente compiladas (como C), o Java não gera um arquivo executável direto para o processador. Ele gera um **Bytecode**.

* **Compilação:** O código `.java` é transformado em `.class` (Bytecode).
* **Execução:** A **JVM** lê esse Bytecode e o traduz para a linguagem específica do sistema operacional (Windows, Linux, macOS).

```mermaid
graph LR
    A[Arquivo .java] -->|Compilador javac| B[Bytecode .class]
    B --> C{JVM}
    C --> D[Windows]
    C --> E[Linux]
    C --> F[macOS]
    ```
### 3. JDK vs. JRE
* **JRE** (Java Runtime Environment): Ambiente necessário para executar aplicativos Java. Contém a JVM e bibliotecas.

* **JDK** (Java Development Kit): Kit completo para desenvolver em Java. Inclui o JRE + Compilador (javac) + Ferramentas de depuração.

##💻 Estrutura Básica de um Programa
Todo código Java precisa estar dentro de uma Classe e a execução começa pelo método main.
```
// O nome da classe deve ser igual ao nome do arquivo (HelloWorld.java)
public class HelloWorld {
    
    // Ponto de entrada do programa
    public static void main(String[] args) {
        // Exibe uma mensagem no console
        System.out.println("Olá, Mundo! Bem-vindos ao curso de Java 2026.");
    }
}
```
##🔍 Explicação do Código:
* public class: Define o acesso e o nome da entidade.

* static: Indica que o método pertence à classe e não precisa de um objeto para ser chamado.

* void: O método realiza uma tarefa, mas não retorna nenhum valor.

* System.out.println: Comando padrão para saída de dados.

##🛠️ Ferramentas Sugeridas
* Para as nossas aulas de Desenvolvimento de Software, utilizaremos:

* JDK 17 ou superior.

IDE: IntelliJ IDEA (Recomendado), VS Code ou Eclipse.

##🏋️ Atividade Prática
* Configuração: Verifique se o Java está instalado no seu terminal usando o comando java -version.

* Primeiro Código: Crie um arquivo chamado OlaNome.java.

* Personalização: Modifique o código acima para exibir o seu nome e o curso que você está cursando.

Desafio: Utilize o caractere de escape \n para pular uma linha na saída do texto.

##📚 Referências Acadêmicas
* DEITEL, Paul J. Java: Como Programar. 10ª Edição.

* ORACLE. Java Documentation. Disponível em: docs.oracle.com

[⬅️ Voltar ao Início](README.md)
