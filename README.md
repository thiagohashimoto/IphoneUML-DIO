# IphoneUML-DIO
UML diagram for a challenge on DIO platform

@startuml
class IPhone {
    + ReproducaoMusical reproducaoMusical
    + FuncionamentoTelefonico funcionamentoTelefonico
    + NavegadorInternet navegadorInternet
}

class ReproducaoMusical {
    + tocar()
    + pausar()
    + selecionarMusica()
}

class FuncionamentoTelefonico {
    + ligar()
    + atender()
    + iniciarChamada()
    + correioDeVoz()
}

class NavegadorInternet {
    + exibirPagina()
    + adicionarNovaAba()
    + atualizarPagina()
}

IPhone *-- ReproducaoMusical
IPhone *-- FuncionamentoTelefonico
IPhone *-- NavegadorInternet
@enduml
