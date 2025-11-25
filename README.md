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

## Installation
flutter pub get
flutter pub run build_runner build --delete-conflicting-outputs
***
# 📄 Modèle : lib/data/models/post.dart

<img width="2559" height="1340" alt="image" src="https://github.com/user-attachments/assets/1ad5aa6d-af88-47c2-adb1-00401c0bcbc3" />


# 🌐 Interface Retrofit : lib/data/network/rest_client.dart

<img width="2559" height="1343" alt="image" src="https://github.com/user-attachments/assets/31868037-e4b2-4533-a4ca-c9acc01eddcc" />


# 💻 Interface utilisateur : lib/ui/posts_page.dart

<img width="2559" height="1347" alt="image" src="https://github.com/user-attachments/assets/830a4f44-02e7-4435-968a-75a2ce582c87" />

# 🧾 Conclusion

**Ce projet** montre comment intégrer Retrofit dans Flutter pour :
Consommer des API REST externes,

Gérer les données JSON facilement,

Afficher les résultats de manière dynamique et élégante.

✨ Ce modèle peut servir de base à n’importe quelle application Flutter connectée à une API.
***
# 📱 Application GitHub Users
## 📝 Description

Ce projet est une application Flutter permettant de rechercher et consulter des profils GitHub grâce à l'API GitHub REST.
L’application affiche une liste d’utilisateurs, puis en sélectionnant un utilisateur, elle présente des informations détaillées telles que :

Nom et pseudo

Localisation

Entreprise

Site web

Nombre de dépôts

Followers et Following

L’application utilise :

✅ Flutter
✅ Dio (client HTTP)
✅ API GitHub
✅ Architecture propre et modulaire
<img width="576" height="1143" alt="image" src="https://github.com/user-attachments/assets/0f4c70cb-587f-40c7-8d26-5c3d8a0d0c08" />
# 👤 Détails d’un utilisateur

## 🧪 Fonctionnalités Implémentées

✅ Récupération des utilisateurs via l’API GitHub

✅ Recherche d’utilisateurs

✅ Affichage des détails d’un profil

✅ Gestion des erreurs

✅ Support du token d’accès GitHub

✅ Interface fluide et responsive

<img width="316" height="446" alt="image" src="https://github.com/user-attachments/assets/3f243328-1bf9-4fd4-a655-0c2bb6fa03fe" />

## ✅ Conclusion

Ce projet m’a permis de découvrir et d’appliquer l’intégration d’API dans Flutter, d’améliorer mes compétences en conception d’interface, ainsi que de mettre en place des requêtes réseau avec Dio.
L’application offre une expérience simple et efficace pour explorer des profils GitHub.
---

## 🌦️ Page Météo 
📝 Description

Cette section de l’application permet d’afficher en temps réel les informations météorologiques d’une ville marocaine.
L’utilisateur peut saisir le nom d’une ville (par défaut : Casablanca), puis consulter :

Température actuelle

Ressenti

Conditions météo (ensoleillé, couvert, pluie…)

Vitesse du vent

Humidité

Pression atmosphérique

Les données sont récupérées via l’API :

✅ OpenWeatherMap / Weather API
✅ Format JSON
✅ Requête HTTP avec Dio
<img width="580" height="1252" alt="image" src="https://github.com/user-attachments/assets/c3cff6ca-f357-420d-8c0b-abc13502afc2" />
## 🧪 Fonctionnalités Implémentées

✅ Recherche météo par ville

✅ Récupération des données en temps réel

✅ Gestion du chargement (loading)

✅ Affichage des détails météorologiques

✅ Interface simple et intuitive
# ✅ Conclusion

Cette fonctionnalité m’a permis de mettre en pratique l’intégration d’une API externe dans Flutter, la gestion des requêtes HTTP avec Dio, ainsi que l’affichage dynamique d’informations sur l’interface.
La page météo offre une expérience claire et utile pour consulter rapidement le climat d’une ville marocaine.

