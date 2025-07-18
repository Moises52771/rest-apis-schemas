openapi: 3.0.0
info:
  title: ViaCep API
  version: "1.0"
paths:
  /{cep}/json:
    get:
      summary: Buscar endereço pelo CEP
      parameters:
        - name: cep
          in: path
          required: true
          schema:
            type: string
      responses:
        '200':
          description: Endereço encontrado
          content:
            application/json:
              schema:
                type: object
                properties:
                  cep:
                    type: string
                  logradouro:
                    type: string
                  bairro:
                    type: string
                  localidade:
                    type: string
                  uf:
                    type: string
