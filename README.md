# dio-desafio-poo-uml
Desafio para criar um simples diagrama de UML do iphone

classDiagram
    class ReprodutorMusical {
        -Musica[] playList
        +tocar()
        +parar()
        +selecionarMusica(Musica musica)
        +addMusicaPlayList(Musica musica)
    }
    class Telefone {
        -String[] agenda
        +ligar(String numero)
        +atender()
        +iniciarCorreioVoz()
    }
    class NavegadorInternet {
        +exibirPagina(String url)
        +adicionarAba()
        +atualizarPagina()
    }
    class Iphone {
    }
    Iphone --> ReprodutorMusical
    Iphone --> Telefone
    Iphone --> NavegadorInternet
