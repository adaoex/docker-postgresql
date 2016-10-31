# docker-postgresql

Imagem Docker para PostgreSQL

**Get it running:**

``$ docker-compose up``

**Testing the running PostgreSQL**

Para testar execute o container criado, pode usar qualquer cliente ou em linha de comando:

``psql -h localhost -p 5432 -U pguser -W pgdb``

Quanto for pedida a senha no prompt, digite: pguser

_Observe que localhost só é válido se você estiver executando o Docker no Ubuntu. Se você é um usuário OSX, você precisa descobrir o ip correto usando: boot2docker ip_
