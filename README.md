# DIO-verificadorCPF

Implante o Azure Function no Azure.

Obtenha a URL do Function (ex: https://seu-app.azurewebsites.net/api/ValidateCpfMicroservice).

Teste via URL (GET):

.../ValidateCpfMicroservice?cpf=12345678909

Teste via Corpo (POST - JSON):

JSON

{
  "cpf": "123.456.789-09"
}
