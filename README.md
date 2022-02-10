# DeslocamentoApi
	É um uma api de modelo utilizada como base para o curso de back-end C# no Biopark Connect

## Migrations

Para iniciar dotnet-ef
```
	dotnet tool install --global dotnet-ef
```

Para criar uma migration
```	
	dotnet ef migrations add <aqui_um_nome_para_migration> --project .\DelocamentoApp.Data --startup-project .\DeslocamentoApp.WebAPI --context ApplicationDbContext
```
	dotnet ef migrations add CarregamentoInicial --project .\Delocamento.Data --startup-project .\Deslocamento.WebAPI --context ApplicationDbContext

Para executar a migration
```
	dotnet ef database update --project .\Delocamento.Data --startup-project .\Deslocamento.WebAPI --context ApplicationDbContext
```

# EuAceito
