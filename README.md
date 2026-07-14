nome = input("escreva seu nome: ")
idade = input("escreva sua idade: ")
class user():
    def __init__(self, nome, idade):
        self.nome = nome
        self.idade = idade
    def falar(self):
        print(f"{self.nome} tem {self.idade} anos e disse oi")
usuario = user(nome, idade)
usuario.falar()
