# Avaliação de Segurança e versionamento

Avaliação pode ser feita em dupla e com consulta.

Você deverá clonar esse documento, responder as questões e versioná-lo de volta no seu repositório. Ao final deverá me mandar o link.


## Nomes:

Aluno1: Leonardo Lima

Aluno2: Mauro dos Santos

## Usage

```python
1 - Explique com suas palavras o que é SQL Injection:
R: É uma falha de segurança onde um código mal intencionado é passado pelo SQL.

```

```python
2 - Ao ser contratado para uma empresa como consultor
de segurança, ao analisar o código qual seria a primeira falha de segurança
que você procuraria?
R: O acesso não limitado do usuário root. 

```

```python
3 - Escreva um exemplo de injeção de SQL que você  tentaria:
R:  ‘ or 1=1
    
    SELECT * FROM TAB_USUARIOS WHERE E-MAIL = ” OR 1=1

```
```python
4 - O que você faria para resolver o problema de senhas
 em texto plano no banco de dados
do seu cliente
R: usaria o hash para criptografar.

```

```python
5  a) O que é XSS request forgery:
R: É uma falha que explora a vulnerabilidade de um usuário leigo, permitindo que virtualmente  qualquer ação especifica possa ser realizada no sistema sem consentimento do usuário final.
b) Como você resolveria essa falha?

```geraria um token com códigos especificos para complementar a verificação de autenticidade.







