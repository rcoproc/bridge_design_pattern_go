# BRIDGE Design Pattern

Fonte:

(Golang by Example)[https://golangbyexample.com/bridge-design-pattern-in-go/]

## Definição

O padrão de projeto de ponte(Bridge) é um padrão de projeto estrutural que permite separar a abstração de sua implementação. Parece confuso? Não se preocupe, ficará mais claro à medida que avançarmos.

Este padrão sugere a divisão de uma grande classe em duas hierarquias separadas

+ Abstração - é uma interface e os filhos da Abstração são chamados de Abstração Refinada. A abstração contém uma referência à implementação.

+ Implementação - também é uma interface e os filhos da implementação são chamados de implementação concreta

## Exemplo

    go run main.go

## Resultado:

    Print request for mac
    Printing by a HP Printer

    Print request for mac
    Printing by a EPSON Printer

    Print request for windows
    Printing by a HP Printer

    Print request for windows
