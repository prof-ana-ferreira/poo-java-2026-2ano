# Programação Orientada a Objetos com Java  
📘 2º Ano – Ensino Médio Técnico Integrado (EMTI)

Este repositório reúne aulas, atividades, exercícios e projetos desenvolvidos na disciplina de **Programação Orientada a Objetos (POO)** utilizando a linguagem **Java**.

Versão oficial adotada na disciplina:

> ✅ Java 25.0.2 LTS (OpenJDK – Eclipse Temurin)

---

# 🎯 Objetivos da Disciplina

- Compreender os princípios da Programação Orientada a Objetos.
- Desenvolver soluções utilizando Java.
- Aplicar conceitos como:
  - Classes e Objetos
  - Encapsulamento
  - Herança
  - Polimorfismo
- Desenvolver organização e boas práticas de código.
- Utilizar ferramentas profissionais de desenvolvimento.

---

# 🛠 Ambiente de Desenvolvimento

## 1️⃣ Instalação do Java (JDK 25 LTS)

### Passo 1 – Download
Acessar o site oficial do [Eclipse Temurin](https://adoptium.net/pt-BR/temurin).

Selecionar:
- Versão: 25 LTS
- Sistema Operacional: Windows
- Arquitetura: x64
- Tipo de pacote: Installer (.msi)

### Passo 2 – Instalação
1. Executar o arquivo baixado.
2. Clicar em **Next**.
3. Marcar as opções:
   - Set JAVA_HOME variable
   - Add to PATH
4. Clicar em **Install**.
5. Finalizar a instalação.

---

## 2️⃣ Verificar se o Java foi instalado corretamente

1. Pressionar `Win + R`.
2. Digitar `cmd`.
3. Executar:

```
java -version
```

Deve aparecer algo semelhante a:

```
openjdk version "25.0.2" LTS
```

Depois executar:

```
javac -version
```

Se aparecer a versão 25, o Java está corretamente instalado.

---

## 3️⃣ Instalação da IDE (IntelliJ IDEA Community Edition)

### Passo 1 – Download
Baixar a IDE [IntelliJ](https://www.jetbrains.com/idea/download/) para Windows no site oficial da JetBrains.

### Passo 2 – Instalação
Durante a instalação, marcar:

- 64-bit launcher
- Add "Open Folder as Project"
- Add bin folder to PATH
- Create Desktop Shortcut

Clicar em Install e depois em Finish.

---

## 4️⃣ Criar um Projeto Java no IntelliJ

1. Abrir o IntelliJ.
2. Clicar em **New Project**.
3. Selecionar **Java**.
4. Em **Project SDK**, selecionar **Java 25**.
   - Caso não apareça, clicar em **Add SDK → JDK** e selecionar a pasta onde o Java foi instalado.
5. Clicar em **Finish**.

---

## 5️⃣ Criando o Primeiro Programa

1. Clicar com o botão direito na pasta `src`.
2. Selecionar **New → Java Class**.
3. Nomear como `Main`.

Inserir o código:

```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Olá, POO!");
    }
}
```

Executar clicando no botão ▶.

Se a mensagem aparecer no console, o ambiente está configurado corretamente.

---

# 📂 Estrutura do Repositório

```
poo-java-2ano-emti/
│
├── aulas/              # Códigos desenvolvidos em aula
├── atividades/         # Atividades propostas
├── exercicios/         # Exercícios de fixação
├── projetos/           # Projetos integradores
├── material-apoio/     # Materiais complementares
└── README.md
```

---

# 📌 Orientações aos Alunos

- Organizar os projetos por aula.
- Utilizar nomes de pastas em letras minúsculas.
- Manter o código organizado e comentado.
- Versionar os projetos utilizando Git.
- Evitar cópia de soluções prontas.
- Praticar constantemente.

---

# 🧠 Ferramentas Utilizadas

- Java 25.0.2 LTS (OpenJDK – Eclipse Temurin)
- IntelliJ IDEA Community Edition
- Git e GitHub

---

# ⚠️ Observações

- Este repositório não contém gabaritos completos de avaliações.
- O material poderá ser atualizado ao longo do ano letivo.
- Uso exclusivamente educacional.

---

## 👩‍🏫 Disciplina: Programação Orientada a Objetos  
Ensino Médio Técnico Integrado – 2º Ano
