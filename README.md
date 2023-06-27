# :zap: **PyBoost**

:thinking: **O motivo dessa branch é para adicionar o schema do arquivo pyboost.json**

## :pushpin: **Tarefas**

- [x] Configurar o Typer
- [x] Configurar o Rich
- [ ] Gerar o esquema do pyboost.json
- [ ] Desenvolver as opções do CLI
  - [ ] Geração de um projeto Django com dotenv
  - [ ] Integração de um projeto Django com Tailwind

## :thinking: **Como usar?**

:point_right: Para ver as opções disponíveis, digite:

```console
$ poetry run pyboost --help
```

:point_right: Para criar um arquivo de configuração do PyBoost (pyboost.json), basta inserir as opções desejadas para o seu projeto ao executar o CLI. Automaticamente, um arquivo pyboost.json será gerado no diretório em que você estiver executando o comando.

```console
$ poetry run pyboost -np test_py_boost -pv 3.10
```

```console
# Output
Generate pyboost.json ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 100% 0:00:00
{
  "name_project": "test_py_boost",
  "add_python_version": "3.10",
  "add_poetry": false,
  "add_dotenv": false,
  "add_format": false,
  "add_makefile": false,
  "with_django": false,
  "with_tailwind": false
}

test_py_boost configured! 🚀
```

## :warning: **Avisos**

É importante notar a PyBoost está em fase desenvolvimento. Mas se você quiser utilizar mesmo assim, você terá que:

1. Clonar esse repósitório e acessar essa branch feature.
2. Ter o Poetry instalado na sua máquina.
3. Instalar todas as dependências do projeto: `poetry install`

:rocket: Pronto, agora é só utilizar a PyBoost com `poetry run pyboost --help`

## :rotating_light: **Licença**

O projeto PyBoost é distribuído sob a licença MIT, o que significa que é um software livre e que pode ser utilizado, modificado e distribuído livremente, desde que seja incluída uma cópia da licença.
