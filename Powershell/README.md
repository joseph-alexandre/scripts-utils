## Powershell Utils

### add_env_variables

Define as variáveis de ambiente em ambiente Windows, carregadas a partir de um arquivo .env que deve estar no mesmo diretório do script.

### remove_env_variables

Remove as variáveis de ambiente definidas no arquivo .env.

### Observação

É necessário executar os scripts como Administrador, bem como ajustar a política de execução de scripts de terceiro do Powershell. Necessário reiniciar a máquina para que o Windows carregue devidamente as variáveis, e os programas que as utilizam consigam reconhecê-las.
