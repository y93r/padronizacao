# Padronização
**Objetivo:** Automatizar a padronização de dados textuais e reduzir atividades manuais.

## Funcionalidades
- Criar funções para padronização dos campos de cidade e UF.
    - Cidade: remover espaços excedentes, remover acentos e aplicar formato capitalização de título.
      Exemplo: "são paulo" → "Sao Paulo".
    - UF: remover espaços excedentes, remover acentos e converter para letras maiúsculas.
      Exemplo: "sp" → "SP".

- Salvar o tratamento em um arquivo.

### Instalação das bibliotecas
```
pip install pandas
pip install unidecode
```
