# Projeto Maven Java 21 - Estrutura Inicial

Este é um **projeto base em Java 21** usando **Maven**, criado para servir como ponto de partida para desenvolvimento de um sistema de gerenciamento de Boards, Columns e Cards.

## Estrutura do Projeto

Projeto Maven Java 21 completo:

1️⃣ Estrutura de pastas e classes:

```
projeto-raiz/
├─ pom.xml
├─ src/main/java/
│  ├─ dto/
│  │  ├─ BoardColumnDTO.java
│  │  ├─ BoardColumnInputDTO.java
│  │  ├─ BoardDTO.java
│  │  ├─ CardDTO.java
│  │  ├─ CardInputDTO.java
│  │  ├─ CardOutputDTO.java
│  │  └─ CardPositionDTO.java
│  ├─ exception/
│  │  ├─ CardNotFoundException.java
│  │  ├─ CardServiceException.java
│  │  └─ EntityNotFoundException.java
│  ├─ factory/
│  │  ├─ ConversionFactory.java
│  │  └─ DTOToDomainConversionFactory.java
│  ├─ model/
│  │  ├─ Board.java
│  │  ├─ BoardColumn.java
│  │  ├─ Card.java
│  │  └─ Entity.java
│  ├─ repository/
│  │  ├─ BoardColumnRepository.java
│  │  ├─ BoardRepository.java
│  │  ├─ CardRepository.java
│  │  └─ EntityRepository.java
│  ├─ service/
│  │  ├─ BoardColumnService.java
│  │  ├─ BoardService.java
│  │  ├─ CardService.java
│  │  ├─ EntityService.java
│  │  └─ BoardBusiness.java
│  └─ Main.java
└─ src/main/resources/
   └─ application.properties
```
