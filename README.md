# Calculadora de IMC

Este é um projeto que consiste em uma calculadora de Índice de Massa Corporal (IMC) desenvolvida usando a linguagem Dart. O projeto é dividido em duas pastas: uma contendo a calculadora IMC feita apenas com Dart e executada no terminal, e outra contendo a mesma calculadora, porém implementada com Flutter e executada em um aplicativo desktop.

## Pré-requisitos

Certifique-se de ter os seguintes itens instalados antes de executar o projeto:

- Dart SDK
- Flutter SDK (apenas para a versão do aplicativo desktop)

## Estrutura do Projeto

O projeto está organizado da seguinte maneira:

```
|- .exe Flutter
   |- fluttercalculadora.exe
|- Dart
   |- calculadora_imc_dart
      |- bin
         |- calculadora.dart
|- Flutter
   |- calculadora_imc_dart_flutter
      |- lib
         |- main.dart
|- README.md
```

- A pasta `Dart` contém a implementação da calculadora IMC em Dart puro, executada no terminal.
- A pasta `Flutter` contém a implementação da calculadora IMC usando Flutter, permitindo a execução do aplicativo desktop.
- O arquivo `calculadora.dart` e `main.dart` em cada pasta é o ponto de entrada do respectivo projeto.
- A pasta ".exe Flutter" contém o executável do aplicativo Flutter. O arquivo fluttercalculadora.exe é o executável final do aplicativo.
- Outros arquivos e diretórios relevantes para cada projeto podem estar presentes, mas foram omitidos aqui para simplificar.

## Executando o projeto

### Calculadora IMC em Dart

1. Navegue até a pasta `Dart/calculadora_imc_dart/bin` no terminal.
2. Execute o seguinte comando para iniciar o programa:

```bash
dart calculadora.dart
```

3. Siga as instruções exibidas no terminal para calcular o IMC com base nos valores inseridos.

### Calculadora IMC em Flutter (aplicativo desktop)

1. Certifique-se de que o Flutter SDK esteja instalado corretamente.
2. Navegue até a pasta `Flutter/calculadora_imc_dart_flutter` no terminal.
3. Execute o seguinte comando para baixar as dependências necessárias:

```bash
flutter pub get
```

4. Inicie o aplicativo com o seguinte comando:

```bash
flutter run
```

5. O aplicativo será compilado e iniciará em um emulador ou dispositivo conectado.

## Licença

Este projeto está licenciado sob a [Licença MIT](https://github.com/seu-usuario/nome-do-repositorio/blob/main/LICENSE).

## Contato

Se tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato:

- Email: mariahelenarocha54@gmail.com
- GitHub: [mHelenaR](https://github.com/mHelenaR)
