# Desafio Dio Iphone

### Diagrama UML (Mermaid)
```mermaid
classDiagram
    class IReprodutorMusical {
        +tocar()
        +pausar()
        +selecionarMusica(String musica)
    }    

    class IAparelhoTelefonico {
        +ligar(String numero)
        +atender()
        +iniciarCorreioVoz()
    }

    class INavegadorInternet {
        +exibirPagina(String url)
        +adicionarNovaAba()
        +atualizarPagina()
    }

    class iPhone {
        +tocar()
        +pausar()
        +selecionarMusica(String musica)
        +ligar(String numero)
        +atender()
        +iniciarCorreioVoz()
        +exibirPagina(String url)
        +adicionarNovaAba()
        +atualizarPagina()
    }

    iPhone ..|> IReprodutorMusical
    iPhone ..|> IAparelhoTelefonico
    iPhone ..|> INavegadorInternet
```
