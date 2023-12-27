# Criar-Pedido
Criar pedidos para teste local no backoffice

# Passo 1

## Editar Ambiente

* Caminho: 
* xxxxxxxx
* xxxxxxxx


# Passo 2
## Criar Pedido

* Caminho: Postman  
    Método: POST  
    URL: http://localhost:8085/webservices/v1/pedido
  
            http://localhost:8085/webservices/v1/pedido
    <br>  
    Script:
    
      {
        "idServico": "SELLER_VV",
        "numeroNf": "30597641",
        "serieNf": "001",
        "chaveAcesso": "35230696585005000100550020000101221196012862",
        "identificacaoCliente": "2357958754",
        "qtdVolumes": 1,
        "pesoTotal": 1.5,
        "cubagemTotal": 0.0093,
        "totalNota": 1080.00,
        "valorICMS": "309.20",
        "codigoCarga": "12062019",
        "tipoDocumento": "PVE",
        "idTipoDocumento": "NOTA_FISCAL",
        "tipoEntrega": "NORMAL",
        "origem": "VIA",
        "dataPrevisaoEntrega": "2023-05-11T03:00:00.000Z",
        "consumidor": {
            "nome": "Joarez da Copel",
            "cpf": "092.975.590-18",
            "inscricaoEstadual": "Isento",
            "logradouro": "RUA JEREMIAS DE PAULA EDUARDO",
            "numero": " 164",
            "bairro": "cidade monçoes",
            "cidade": "São Paulo",
            "cep": "13203-421",
            "uf": "SP"
        },
        "emitente": {
            "nome": "Seller VV - Carlos",
            "cnpj": "89625038000163",
            "inscricaoEstadual": "432932835447",
            "logradouro": "Avenida Engenheiro Caetano Álvares",
            "numero": " 123",
            "bairro": "Limão",
            "cidade": "São Paulo",
            "cep": "02546-000",
            "uf": "SP",
            "complemento": "Casa"
        },
        "volumes": [
            {
                "id": 1,
                "etiqueta": "VV124566324BR",
                "codigoBarras": null,
                "peso": 11.3,
                "cubagem": 0.115943,
                "altura": 0.71,
                "largura": 0.71,
                "profundidade": 0.23
            }
        ],
        "itens": [
            {
                "id": 0,
                "etiqueta": "VV124566324BR",
                "codigoBarras": null,
                "descricao": "Fogão Brastemp",
                "peso": 40.8,
                "cubagem": 1.2,
                "altura": 0.87,
                "largura": 0.5,
                "profundidade": 0.6,
                "codigo": null,
                "tipo": null,
                "qtde": 1
            }
        ]
      }

Exemplo:  
![image](https://github.com/CarlosLiveira/Criar-Pedido/assets/89557656/7078b3e4-026d-4204-a65b-c2df0d956487)



