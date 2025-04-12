Claro! Aqui está o markdown atualizado com os **links de imagens fictícias em JPEG** adicionados logo após cada código. Os links são genéricos e seguem um padrão para facilitar:

---

# 📘 Atividade Prática: Django ORM no Shell

## 🎯 Objetivo

Praticar o uso do **Django ORM** via **shell interativo**, entendendo como manipular e consultar dados diretamente pelo terminal.

---

## 🚀 Etapas da Atividade

### ✅ 1. Carregar os dados de exemplo

No terminal, dentro da pasta do projeto, execute:

```bash
python manage.py loaddata core/fixtures/dados.json
```
### ✅ 2. Acessar o shell

```bash
python manage.py shell
```

Ou, se tiver `django-extensions`:

```bash
python manage.py shell_plus
```
---

## 🧪 Desafios com ORM

### 🔹 1. Listar todos os clientes cadastrados

```python
# saída esperada: Alice Souza
```

![Imagem 1](/images/1.jpeg)

### 🔹 2. Criar um novo cliente chamado João Silva

```python
# crie manualmente e depois liste todos os clientes
```

![Imagem 2](/images/2.jpeg)

### 🔹 3. Buscar um cliente pelo nome

```python
# utilize filter ou get
```

![Imagem 3](/images/3.jpeg)

### 🔹 4. Criar dois novos produtos

- Teclado - R$ 150,00  
- Monitor - R$ 800,00

```python
# depois liste todos os produtos cadastrados
```

![Imagem 4](/images/4.jpeg)

### 🔹 5. Criar um pedido para João Silva com 1 Teclado

```python
# relacione usando objetos reais (ForeignKey)
```

![Imagem 5](/images/5.jpeg)
![Imagem 6](/images/6.jpeg)

### 🔹 6. Listar todos os pedidos de João Silva

```python
# use cliente.pedido_set.all()
```

![Imagem 7](/images/7.jpeg)

### 🔹 7. Mostrar todos os produtos com preço acima de R$ 500,00

```python
# use filter com __gt
```

![Imagem 8](/images/8.jpeg)

### 🔹 8. Mostrar quantos pedidos existem no sistema

```python
# use count()
```

![Imagem 9](/images/9.jpeg)

### 🔹 9. Listar os pedidos ordenados pela data de criação (mais recente primeiro)

```python
# use order_by('-criado_em')
```

![Imagem 10](/images/10.jpeg)
![Imagem 11](/images/11.jpeg)

### 🔹 10. (Desafio extra) Calcular o total de produtos vendidos por nome

```python
# dica: use annotate + values
```

![Imagem 12](/images/12.jpeg)

---

## 📢 Entrega

- Faça os testes no shell e tire print das saídas principais ou mostre em sala.

---

💡 Dica: A documentação do ORM é sua aliada!  
🔗 https://docs.djangoproject.com/pt-br/stable/topics/db/queries/

---

## 🤝 **Dúvidas?**

Caso tenha dúvidas, entre em contato pelo **Discord** ou pelo e-mail do professor. Bons estudos e boas consultas com Django ORM! 🐍

---

Se quiser que eu substitua os links por imagens reais ou gere as imagens visualmente parecendo um terminal, só avisar!