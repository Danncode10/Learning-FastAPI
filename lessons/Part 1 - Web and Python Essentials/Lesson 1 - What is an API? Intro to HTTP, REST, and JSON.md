# Lesson 1 - What is an API? Intro to HTTP, REST, and JSON.md
---
## 🎯 What is an API? (For Total Beginners)

Imagine this:
You go to **Jollibee**. You talk to the **cashier** and say,

> “Hi po, isang Chickenjoy with rice at iced tea please.”

You’re not cooking the food. You’re not entering the kitchen.
You're just **sending a request**, and the cashier gives you **a response** — your food.

That **cashier** is the API.

You (the frontend) don’t need to know how the chicken is cooked (the backend).
You just need to send a clear **request**, and the API gives you a nice **response**.

---

### 🧠 In tech terms:

* You = frontend (like React)
* Cashier = API (like FastAPI)
* Kitchen = backend logic, AI models, databases

You (React) send a request like:

> “Hey FastAPI, here’s a sentence. Tell me if it’s happy or sad.”

FastAPI responds:

> “Sure, that sentence is **sad** 😢”

That’s how an API works. It’s like a bridge or messenger between the **frontend** and the **backend**.

---

## 🌐 What is HTTP?

When you open a website or use an app that connects to the internet, your computer is always doing this thing called an **HTTP request**.

It’s just a fancy way of saying:

> “Hey server, give me this data please.”

HTTP is like the language both computers understand to **talk**.

---

## 🧹 What is CRUD?

CRUD is just the **four things** most websites/apps do with data.

| Action | Everyday Meaning | In Tech |
| ------ | ---------------- | ------- |
| Create | Add new data     | POST    |
| Read   | Get data         | GET     |
| Update | Change something | PUT     |
| Delete | Remove something | DELETE  |

Think Facebook posts:

* You create a post → **POST**
* You view your timeline → **GET**
* You edit a post → **PUT**
* You delete a post → **DELETE**

Boom! That’s CRUD.

---

## 🧾 What is JSON?

JSON is how your app sends and receives data — like a text message, but formatted like this:

```json
{
  "name": "Lester",
  "age": 21,
  "is_student": true
}
```

It’s clean, organized, and easy to understand — even your computer likes it.

So when FastAPI answers a question, it might say:

```json
{
  "sentiment": "positive"
}
```

---

## 🛣️ What is a RESTful API?

It just means the API is **organized** and follows some rules:

1. Use the correct method (GET, POST, etc.)
2. Use clean URLs (`/users`, `/posts`, `/ai`)
3. Don’t remember anything — each request is complete on its own (no memory unless you give it)

That’s it!

---

### 💬 Final Analogy

Think of a **vending machine**.

You press:

> Button A2 → You want iced tea

The machine doesn’t know your name. It doesn’t care who you are.
You gave a request. It gave a response. That’s **stateless**.

FastAPI is that vending machine. React is the person pressing the buttons.

---

## 🧠 Summary in Baby-Simple Terms

* **API** = a menu you can talk to
* **HTTP** = the language for talking over the internet
* **CRUD** = the 4 things every app does: Add, View, Edit, Delete
* **JSON** = the way we format data when sending it
* **RESTful** = just means the API is clean, organized, and follows rules

---

Want a quick practice?
If I said:

```http
GET /users
```

You’d say:
👉 "Oh! That means: Show me the list of users."

If I said:

```http
POST /users
```

You’d say:
👉 "Add a new user!"