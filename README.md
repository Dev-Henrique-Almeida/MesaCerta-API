<h1 align="center">MesaCerta</h1>

O **MesaCerta** é a solução perfeita para quem deseja unir praticidade e
experiências gastronômicas de qualidade. Com ele, você pode avaliar
restaurantes e pratos, compartilhando suas opiniões para ajudar outros
usuários a fazerem as melhores escolhas. Além disso, o sistema permite
consultar avaliações confiáveis de outros clientes, garantindo que você
sempre encontre o lugar ideal para sua refeição.

Outra funcionalidade essencial é a possibilidade de **agendar horários** de forma rápida e prática, eliminando qualquer complicação na hora de reservar sua mesa. Seja para um **almoço casual, um jantar especial ou uma experiência culinária única**, o **MesaCerta** conecta você aos melhores restaurantes, otimizando seu tempo e garantindo que cada momento seja perfeito.

**MesaCerta: Seu lugar, seu sabor, na hora certa!** 🚀

---

## 📌 Instalação

```bash
$ npm install
```

---

## 🚀 Rodando o projeto

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# gerar o sql dos models no schema
$ npx prisma generate

# criar as tabelas
$ npx prisma migrate dev
```

## 🔐 Variáveis de Ambiente `(.env)`

```bash
DATABASE_URL="postgresql://user:password@localhost:5432/database"
JWT_SECRET=anything
```
