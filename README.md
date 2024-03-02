# MothoExpress

```Site criado para startup Motho Express com intuito de apresentar a empresa aos clientes.```

### Link de acesso
[mothoexpress.com.br](www.mothoexpress.com.br)

# Tailwindcss
 - O arquivo styles.css é gerado com o tailwind

### É necessário instalar o tailwind.
```node
  npm install
```

#### Para ATUALIZAR o tailwind utilize:
```node
  npm install tailwindcss@latest
```

#### Para utilizar o tailwind em desenvolvimento:

```git
  git checkout develop
```

```node
  npx tailwindcss -i './src/global.css' -o './src/styles.css --watch
```

#### Para gerar a build final do tailwind no styles.css utilize:

```node
  npx tailwindcss -i './src/global.css' -o './src/styles.css --minify
```

``` Após gerar a build final faça o merge na branch "main" ```