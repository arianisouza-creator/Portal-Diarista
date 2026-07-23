# Portal Diarista

Projeto dedicado ao modulo de `Controle da Diarista`.

## Escopo

Este projeto publica somente o modulo diarista, com:

- cadastro de obras e nomes
- controle de status ativo/inativo
- acompanhamento mensal por competencia
- preenchimento de pedido, valor, protocolado e link

## Arquitetura

- `app.py`: backend Flask
- `controle-internet.html`: interface compartilhada com foco no modulo diarista
- `project-config.json`: define a abertura direta no modulo `diarista`

## Como rodar

```bash
pip install -r requirements.txt
copy .env.example .env
python app.py
```
