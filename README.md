### Maires Souza

```typescript
export const maires = pgTable('desenvolvedor', {
  papel: text().default('Full stack'),
  stack: text().array().default([
    'TypeScript', 'Java', 'NestJS', 'Spring Boot', 'React',
    'Next.js', 'Vue', 'PostgreSQL', 'Redis', 'Kafka', 'Docker',
  ]),
  gosta: text().array().default([
    'problema que ninguém pegou ainda',
    'query lenta que vira rápida',
  ]),
  cafe: integer().notNull(),
});
```

Hoje trabalho num CRM com chat de WhatsApp integrado. Antes disso passei um tempo no sistema legado da mesma empresa, feito em Vue e Express, e acabei participando da migração de uma stack pra outra.

Costumo pegar o que ninguém fez ainda. A outra parte que gosto é performance: pegar uma tela que trava, entender o que o banco está fazendo por baixo e devolver ela respondendo em milissegundos.

[LinkedIn](https://www.linkedin.com/in/mairess/) · [trabalho.maires@gmail.com](mailto:trabalho.maires@gmail.com)
