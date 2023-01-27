<h1 align="center"> 
	 - Project for implement Prisma with Supabase.
</h1>

<p align="center">
 <a href="#-setup">Setup</a> •
 <a href="#-technologies">Tecnologies</a> •
 <a href="#-autor">Autor</a> • 
 <a href="#-licence">Licença</a>
</p>


<a id="-setup"></a>

## 💻 First Step
🚀 Fork or Clone this repo, and create the .env file and set this variable:

## ⚙️ Instalações

### BACK-END | TypeScript - TSX - Prisma - Migrate Supabase

Fork or Clone this repo

```bash
git clone git@github.com:hugoalmeidahh/supaprisma.git 
cd supaprisma
```

Install all dependencies.
PS: I Tested with node version 16.x and

```bash
# dependência tsx para compilar .ts para .js (node agora consegue rodar arquivos .ts)
npm install
```

Create the .env file and add the variable database

```
DATABASE_URL="postgresql://postgres:[YouPasswd]@db.[YourId].supabase.co:5432/postgres?schema=public"
```

Create your models inside prisma/schema.prisma.
Run the migrate dev.

```bash
npx prisma migrate dev --name "DescriptionOfYouMigrateModification"
```

Instalando Prisma Client

```bash
npm i @prisma/client
```

Instalando gerador de diagrama para DB Prisma

```bash
npm i -D prisma-erd-generator @mermaid-js/mermaid-cli

# adicionar o código abaixo em schema.prisma
generator erd {
  provider = "prisma-erd-generator"
}
```


&nbsp;
<a id="-technologies"></a>
BACKEND:
- TypeScript
- TSX
- Prisma
- Supabase

---


---

&nbsp;
<a id="-autor"></a>

## 🦸 Autor

Hello, I'm Hugo Almeida, I'm a fullstack architect (mobile++) . I am passionate about technology, programming, processes and planning. I united all these passions in one profession. 
Questions, suggestions and criticism are very welcome. Follow my contacts.

- [Hugo Almeida](https://github.com/hugoalmeidahh)
- hugoalmeidahh@gmail.com.com

&nbsp;

---

&nbsp;
<a id="-licence"></a>

## 📝 Licence

This projects is [MIT licensed](./LICENSE).

##### _#NeverStopLearn
