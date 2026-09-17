Herança aplicada a um backend: uma tela de login Cada equipe cria o de login (extremamente simplificado ) da API, seguindo o produtos de referência, que está pronto não já. É a prática parte: o aplicativo manda nome e senha, e uma API responder o que um tem pode usuário do usuário. Quem decide as lesss como herança que você na aula 5. Na Parte B cada equipe informativos de forma encapsulamento e herançaoiao Ki oferta e para a em des minutos.

Como duas partes são para pela equipe, de três a quatro pessoas ja definidas.

O módulo de login O que recebe você pronto Arquivo O que é app/data/sproduto_mock.py Dados mockados dos produtos app/models/.produtopy Modelo do produto e a a função de função_produtos() app/controllers/_productecontroller.py OController app/routes/_routes.py Como rotas GET /api/produtos, GET /aprodutopi/s/categoria/{categoria} e GET /api/produtos/{id} app/data/usuarios_mock.py Os usuários mockados que o seu login vai us main.py Já liga o produtos, com o importar e o include_router O módulo produtos é o modelo. Leia os quatro arquivos antes de ante de: o é é o carro sempre.

main.py -> rotas -> controlador -> modelo -> dados (macio)

Os dados mockados
app/data/usuarios_mock.py

USUARIOS = [ {'id»: 1, «nome»: «bia», «senha»: «bia123», «perfil»: «visitante»}, {'id»: 2, «nome»: «ana», «senha»: «ana123», «perfil»: «contribuidor»}, {'id»: 3, «nome»: «caio», «senha»: «caio123», «perfil»: «moderador»}, ]

São usuários três com três diferentes perfis: virr um precisa um objeto de uma classe. É assim que a herança da equipe é veradura.

Não altere este arquivo. A correção usa estes dados de referência.

Dica: do texto do perfil para uma aula O mock guarda o como texto perfil, 'moderador'. Um modelo de transformação de texto esse na classe Moderador. Duas formas são aceitas:
com se

if u['perfil'] == 'moderador': usuário = Moderador(u['id'], u['nome'], u['senha'])
com um dicionário: em Python a classe é um objeto

PERFIS = {'visitante': Visitante, 'contribuidor' Contribui:, 'moderador': Moderador} usuário = PERFIS[u['perfil']](u['id'], u['nome'], u['senha'])

Esse if é permitido aqui, na hora de criador o objeto. Depois de de criado, ninguém mais o perfil.

Como teste uvicorn main:app --reload

Abra http://127.0.0.1:8000/docs e teste, nesta ordem:

Categoria: Entrega ao clonar o repo, subam para o github, feito em equipe cada cada sobe em sue github e o link do github no teams
