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

- `post.dart` → contient le modèle de données.
- `rest_client.dart` → interface Retrofit pour les appels API.
- `posts_page.dart` → interface utilisateur principale.
- `main.dart` → point d’entrée de l’application.

---

## ⚙️ Dépendances nécessaires (pubspec.yaml)
```yaml
dependencies:
  dio: ^5.7.0
  retrofit: ^4.9.0
  logger: ^2.6.0
  json_annotation: ^4.9.0

dev_dependencies:
  retrofit_generator: ^10.0.1
  build_runner: ^2.6.0
  json_serializable: ^6.10.0
```
***
## Installation
flutter pub get
flutter pub run build_runner build --delete-conflicting-outputs
***
# 📄 Modèle : lib/data/models/post.dart
...
<img width="2559" height="1340" alt="image" src="https://github.com/user-attachments/assets/1ad5aa6d-af88-47c2-adb1-00401c0bcbc3" />
***

# 🌐 Interface Retrofit : lib/data/network/rest_client.dart
...
<img width="2559" height="1343" alt="image" src="https://github.com/user-attachments/assets/31868037-e4b2-4533-a4ca-c9acc01eddcc" />
***
# 💻 Interface utilisateur : lib/ui/posts_page.dart
...
<img width="2559" height="1347" alt="image" src="https://github.com/user-attachments/assets/830a4f44-02e7-4435-968a-75a2ce582c87" />
# 🧾 Conclusion

Ce projet montre comment intégrer Retrofit dans Flutter pour :
Consommer des API REST externes,

Gérer les données JSON facilement,

Afficher les résultats de manière dynamique et élégante.

✨ Ce modèle peut servir de base à n’importe quelle application Flutter connectée à une API.

