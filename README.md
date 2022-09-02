# VOE AIRLINES API

> Projeto com intuito de estudos sobre API.

### ⚙ Especificações

A API foi desenvolvida em base da rotina diária de aviões e suas funções. Aplicado como seria um software de gerenciamento, tendo os seguintes objetivos: 

- [x] Usar o dotnet para criar a API inicial
- [x] Criar um plano relacional de cada entidades baseado em uma empresa de aeronaves
- [x] Estabelecer as propriedades das colunas de cada entidade, como por exemplo: "VooConfiguration"
- [x] Configurar a conexão com banco de dados
- [x] Finalização com PDFs gerados automaticamente

## 💻 Funcionamento

**Clonar o repositório**
```
git clone https://github.com/deyve853/VoeAirlineSenai.git
```

**Restaurar os pacotes**

Navegar para a pasta do projeto clonado e executar o seguinte comando:

```
dotnet restore
```

**Executar a aplicação**

Executar o seguinte comando ou utilizar a ferramenta de Debug do Visual Studio u Visual Studio Code (normalmente pressionando F5):
```
dotnet run
```

## Como testar a API

**Acessar a interface de teste do Swagger***
A UI do Swagger estará disponível na URL https://localhost:7142/swagger (a porta pode variar e deve ser observada no terminal ao executar o projeto).

**Consumir os endpoints**
Possibilidades de aplicação de cada entidade:

1) Criar, editar e excluir Aeronaves
2) Criar, editar e excluir Manutenção
3) Criar, editar e excluir Piloto
4) Criar, editar e excluir Voo


