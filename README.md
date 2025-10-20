O MongoDB é uma plataforma de banco de dados orientado a documentos, diferente dos bancos de dados relacionais (como MySQL ou PostgreSQL), que são baseados em tabelas.

Ele armazena dados em documentos JSON-like (no formato BSON — Binary JSON).

Ideal para aplicações que precisam de alta escalabilidade, desempenho e flexibilidade na modelagem de dados.

🧱 Principais características:

NoSQL: Não usa SQL tradicional, nem tabelas. Usa documentos com campos e valores.

Documentos: Dados são armazenados em estruturas similares a JSON.

Escalável: Fácil de escalar horizontalmente (adicionar mais servidores).

Alta performance: Muito usado em aplicações web e móveis.

Flexível: Os documentos de uma mesma coleção podem ter diferentes estruturas (sem schema fixo).

🛠️ Exemplo de documento MongoDB:
{
  "nome": "Maria",
  "idade": 30,
  "email": "maria@email.com",
  "enderecos": [
    {
      "rua": "Rua A",
      "cidade": "São Paulo"
    },
    {
      "rua": "Rua B",
      "cidade": "Rio de Janeiro"
    }
  ]
}

🧩 Componentes da “plataforma” MongoDB:

Se você ouviu falar de “plataforma Mongo”, pode estar se referindo a todo o ecossistema oferecido pela empresa MongoDB Inc., que inclui:

MongoDB Atlas: serviço na nuvem (cloud) para gerenciar bancos MongoDB.

Compass: interface gráfica para visualizar e gerenciar dados.

Drivers: bibliotecas para integrar MongoDB com várias linguagens (Node.js, Python, Java, etc.).

MongoDB Shell: linha de comando para interagir com o banco.
