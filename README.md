# Desafio controle de fluxo - Java Básico | Bootcamp Santander 2024

Repositório destinado a aplicação dos principais conceitos apredidos na aula de Java Básico no Bootcamp Santander 2024.

### <span style="font-size: smaller;">Diagrama UML | Case Iphone</span>

```mermaid
classDiagram
    iPhone ..|> ReprodutorMusical
    iPhone ..|> AparelhoTelefonico
    iPhone ..|> NavegadorNaInternet

    class iPhone {
      + tocar()
      + pausar()
      + selecionarMusica(String musica)
      + ligar(String numero)
      + atender()
      + iniciarCorreioVoz()
      + exibirPagina(String url)
      + adicionarNovaAba()
      + atualizarPagina()
    }

    class ReprodutorMusical {
      + tocar()
      + pausar()
      + selecionarMusica(String musica)
    }

    class AparelhoTelefonico {
      + ligar(String numero)
      + atender()
      + iniciarCorreioVoz()
    }

    class NavegadorNaInternet {
      + exibirPagina(String url)
      + adicionarNovaAba()
      + atualizarPagina()
    }
