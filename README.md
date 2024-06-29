# Desafio Dio - Publicando Seu Portfólio Profissional no GitHub Pages



Segue um guia mais completo e abrangente sobre como publicar seu portfólio profissional no GitHub Pages, com mais código e exemplos:**

### **Pré-requisitos:**

- Conta do GitHub
- Conhecimento básico de HTML, CSS e JavaScript
- Editor de código (como Visual Studio Code ou Sublime Text)



### **Passos:**



**1. Criar um Repositório no GitHub**

- Acesse o GitHub e faça login em sua conta.
- Clique no botão "Novo" e selecione "Repositório".
- Dê um nome ao seu repositório (por exemplo, "meu-portfolio") e adicione uma descrição (opcional).
- Selecione "Inicializar este repositório com um README" e clique em "Criar repositório".



### **2. Criar os Arquivos do Portfólio**



- Abra seu editor de código e crie um novo arquivo chamado `index.html`.
- Adicione o seguinte código HTML básico:



plaintext



```plaintext
<!DOCTYPE html>
<html>
<head>
  <title>Meu Portfólio</title>
</head>
<body>
  <h1>Olá, mundo!</h1>
</body>
</html>
```



- Crie outros arquivos HTML, CSS e JavaScript conforme necessário para o seu portfólio.



### **3. Adicionar os Arquivos ao Repositório**



- Abra o Terminal ou Prompt de Comando.

- Navegue até o diretório do seu portfólio.

- Adicione os arquivos ao repositório usando o comando `git add`:

  

plaintext



```plaintext
git add .
```



### **4. Confirmar as Alterações**



- Confirme as alterações no repositório usando o comando `git commit`:

plaintext



```plaintext
git commit -m "Adicionar arquivos do portfólio"
```



### **5. Enviar as Alterações**



- Envie as alterações para o GitHub usando o comando `git push`:

plaintext



```plaintext
git push origin main
```



### **6. Acessar Seu Portfólio**

- Seu portfólio estará disponível em `https://<seu-nome-de-usuário>.github.io/<nome-do-repositório>`.



### **Dicas:**



- Use um tema do GitHub Pages para dar estilo ao seu portfólio.
- Adicione uma página "Sobre" para fornecer informações sobre você e seu trabalho.
- Inclua exemplos de seus projetos e trabalhos anteriores.
- Mantenha seu portfólio atualizado com seus trabalhos mais recentes.
- **Exemplo de tema do GitHub Pages:**

plaintext



```plaintext
theme: jekyll-theme-cayman
```



- **Exemplo de página "Sobre":**

plaintext



```plaintext
<section id="sobre">
  <h2>Sobre Mim</h2>
  <p>Olá, sou um desenvolvedor web com experiência em HTML, CSS e JavaScript. Estou apaixonado por criar sites bonitos e funcionais.</p>
</section>
```



- #### **Exemplo de exibição de projetos:**

plaintext



```plaintext
<section id="projetos">
  <h2>Projetos</h2>
  <ul>
    <li><a href="#">Projeto 1</a></li>
    <li><a href="#">Projeto 2</a></li>
    <li><a href="#">Projeto 3</a></li>
  </ul>
</section>
```



### **Conclusão:**

Seguindo esses passos, você pode criar e publicar facilmente um portfólio profissional no GitHub Pages. Isso permitirá que você mostre seu trabalho para possíveis empregadores e clientes.
