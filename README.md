# Documentação do Módulo deConexão

## Descrição
Este projeto implenta um padrão de conexão segura com o banco de dados, utilizando **Desing Pattern** para evitar *hard coding*.


## O que foi feito
- [X] Criação do repositorio
- [ ] Implementação da conexão
- [ ] Resolução de conflito de Merge
- [ ] Separação de concflitos

## Exemplo de uso 
Abaixo, o codigo padrão utilizado pelo arquiteto:

'''python
# constante de confuguração 
DB_HOST = "192.168.0.1"

def conctar_banco():
"""Conecta usando  constante definida"""
return f"Conctando ao {DB_HOST}"
