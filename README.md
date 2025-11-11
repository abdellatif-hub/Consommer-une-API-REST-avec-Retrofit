# 🧩 Atelier : Consommer une API REST avec Retrofit (Flutter)

## 🎯 Objectif du projet
Ce projet montre comment **consommer une API REST** dans une application **Flutter** en utilisant **Retrofit** et **Dio**.  
L’application récupère une **liste de posts** depuis l’API publique [JSONPlaceholder](https://jsonplaceholder.typicode.com/posts)  
et permet d’afficher **le détail d’un post** lors d’un clic.

---

## 🏗️ Structure du projet
lib/
├── data/
│ ├── models/
│ │ └── post.dart
│ └── network/
│ └── rest_client.dart
├── ui/
│ └── posts_page.dart
└── main.dart
