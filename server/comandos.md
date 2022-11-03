## Iniciar projeto node
```
npm init -y
```

## Iniciar projeto typescript

```
npx tsc --init -> NPX executa pacotes do node
```

## Configuração do prisma utilizando SQLite

```
npx prisma init --datasource-provider SQLite
```

## Rodar migrations com o prisma (caso haja alguma modificação no schema, irá pedir um nome para a nova migration que será criado)

```
npx prisma migrate dev
```

## Abre o banco de dados no navegador (similar a uma IDE de banco)

```
npx prisma studio
```

## Gera um diagrama ERD (Entidade Relacional)

```
npx prisma generate
```