# BlazorViaCep

Atividade prática de Usabilidade, Desenvolvimento Web, Mobile e Jogos.

Aluna: Mariele Evangelista

Projeto Blazor WebAssembly para consulta de endereços pela API pública ViaCEP.

## Funcionalidades

- Entrada de CEP e botão Consultar.
- Validação de CEP com oito dígitos.
- Consulta em `https://viacep.com.br/ws/{cep}/json/`.
- Exibição de CEP, logradouro, complemento, bairro, localidade, UF e DDD.
- Mensagens para CEP inválido, não encontrado e falha na requisição.

## Executar

Requer SDK .NET 10.

```bash
dotnet restore
dotnet run
```

Acesse o endereço indicado no terminal. Exemplo de teste: `30130000`.
