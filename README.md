![Captura de tela 2024-04-17 123206](https://github.com/DalilaDeveloperMobile/Conhecendo-Linguagem-Python/assets/29806802/83eba503-c094-4431-b85f-e7b4cc9d92de)
### Passos Iniciais Realizados Nesse Bootcamp Python AI Backend Developer. [dio_me](https://www.dio.me/)
### ✅ Introdução à Programação Orientada a Objetos (POO) com Python.

### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Classes e Objetos:
```
class Bicicleta:
    def __init__(self, cor, modelo, ano, valor):
        self.cor = cor
        self.modelo = modelo
        self.ano = ano
        self.valor = valor

    def buzinar(self):
        print("Plim plim...")

    def parar(self):
        print("Parando bicicleta...")
        print("Bicicleta parada!")

    def correr(self):
        print("Vrummmmm...")

    def __str__(self):
        return f"{self.__class__.__name__}: {', '.join([f'{chave}={valor}' for chave, valor in self.__dict__.items()])}"


b1 = Bicicleta("vermelha", "caloi", 2022, 600)
b1.buzinar()
b1.correr()
b1.parar()
print(b1.cor, b1.modelo, b1.ano, b1.valor)

b2 = Bicicleta("verde", "monark", 2000, 189)
print(b2)
b2.correr()
```
### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Construtores e Destrutores:
```
class Cachorro:
    def __init__(self, nome, cor, acordado=True):
        print("Inicializando a classe...")
        self.nome = nome
        self.cor = cor
        self.acordado = acordado

    def __del__(self):
        print("Removendo a instância da classe.")

    def falar(self):
        print("auau")


def criar_cachorro():
    c = Cachorro("Zeus", "Branco e preto", False)
    print(c.nome)


c = Cachorro("Chappie", "amarelo")
c.falar()

print("Ola mundo")

del c

print("Ola mundo")
print("Ola mundo")
print("Ola mundo")

# criar_cachorro()
```
<h3 align="center"> Made with <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> by Dalila...</h3>
<div align="center"  style="display: inline-block">
  <a href="https://www.linkedin.com/in/dalila-cust%C3%B3dio-046076181/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
  <a href = "mailto:dalila.dalila70@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://instagram.com/dalila.dalila70" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a target="_blank" href="https://api.whatsapp.com/send?phone=5588997138541"><img  alt="Whatsapp" width="117px" src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/></a> 
</div>

