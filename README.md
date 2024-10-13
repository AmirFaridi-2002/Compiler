# Compiler Design

This repository contains the implementation of a custom compiler, developed as part of a project to explore language design and compilation techniques.

## Contents

The repository includes the following components:

- **Grammar Definition**: The grammar for the custom language is implemented using ANTLR, defining the syntactic structure of the language.
- **Lexical and Syntax Analysis**: ANTLR is used to generate a lexer and parser based on the defined grammar, allowing for the tokenization and syntactic analysis of source code.
- **Name and Type Analysis**: Java is used to implement semantic checks, including name resolution and type analysis, ensuring the correctness of the program by enforcing scope and type rules.
  
## Usage

The code is organized into modules, with each component residing in its own directory. The project can be built using a Java build tool like Maven or Gradle.

To test the compiler, run the ANTLR-generated parser on sample input files, followed by name and type analysis in Java. Parameters and test cases can be configured in the project settings.

## About the Project

This project was developed to deepen understanding of compiler design, with a focus on the practical application of language parsing using ANTLR and semantic analysis using Java. The project covers the fundamental stages of compilation, from parsing to semantic verification.
