# Aplicaçõem com FastAPI

## O que é o FastAPI?

FastAPI é um framework moderno e rápido (alta performance) para construção de APIs em Python, baseado em tipos Python 3.7+ e suportado pelo ASGI (Asynchronous Server Gateway Interface). Ele é conhecido por sua facilidade de uso, velocidade e suporte nativo a operações assíncronas.

![FastAPI Logo](https://fastapi.tiangolo.com/img/logo-margin/logo-teal.png)

---

## Por que usar o FastAPI?

- **Alta Performance**: Comparável a Node.js e Go, graças ao uso do ASGI.
- **Fácil de Aprender**: Sintaxe simples e intuitiva.
- **Validação de Dados Automática**: Baseada em tipos Python e Pydantic.
- **Documentação Automática**: Gera automaticamente documentação interativa (Swagger UI e ReDoc).
- **Suporte a Operações Assíncronas**: Ideal para aplicações que exigem alta concorrência.

---

## Instalação do FastAPI

Para começar, você precisa instalar o FastAPI e um servidor ASGI, como o Uvicorn.

```bash
pip install fastapi uvicorn
```

## Criando arquivo python

``` python
from fastapi import FastAPI

# Instância do FastAPI
app = FastAPI()

# Rota raiz
@app.get("/")
def read_root():
    return {"message": "Bem-vindo ao FastAPI!"}

# Rota com parâmetro
@app.get("/items/{item_id}")
def read_item(item_id: int, q: str = None):
    return {"item_id": item_id, "q": q}
```

## Executando servidor

```bash
uvicorn main:app --reload
```
## Acessar API
Abra o navegador e acesse:

- API: http://127.0.0.1:8000/
- Documentação Interativa (Swagger UI): http://127.0.0.1:8000/docs
- Documentação Alternativa (ReDoc): http://127.0.0.1:8000/redoc

## Estrutura básica do fastAPI

```
meu_projeto/
│
├── main.py            # Ponto de entrada da aplicação
├── routers/           # Rotas da API
│   └── items.py
├── models/            # Modelos Pydantic
│   └── item.py
├── schemas/           # Esquemas de validação
│   └── item.py
├── dependencies.py    # Dependências compartilhadas
└── requirements.txt   # Dependências do projeto
```


O FastAPI é uma ferramenta poderosa e moderna para construir APIs em Python. Com sua sintaxe simples, validação automática de dados e suporte a operações assíncronas, ele é ideal para projetos de todos os tamanhos.

Siga os passos deste tutorial para começar a criar suas próprias APIs com FastAPI. Para mais detalhes, consulte a [documentação oficial](https://fastapi.tiangolo.com/).