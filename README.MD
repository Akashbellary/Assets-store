# 3DAssetStore [3DMarket]

This project is aimed at building a 3D asset store for the 3D Modeller community I'm part of. Our community is small, but we make high-quality content. The main goal of this project was to master HTML, Tailwind CSS while working on something that will be used in production. The site will be hosted very soon, and any 3D modelling artist can sell his 3D arts on the site. As i am a freelancer 3D Artist too, I am trying to fix issues 3D artists face with selling their 3D Models.

![Home Page](Home_page.jpg)
![Product Page](product_view.jpg)

## Used Tools

- **Frontend:** HTML and Tailwind CSS
- **Backend:** Django

## Features

- **Home Screen:** Showcases all the assets available.
- **Sign In & Sign Up:** Fully functional authentication system built with Django's auth features.
- **Account Management:** After creating an account, you can add new 3D models you built and delete existing ones in your account.
- **Contact Artists:** Buy and sell 3D models by contacting other artists.
- **Search Option:** Search assets by typing related texts (e.g., searching "firearm" will list guns even if they have different titles by considering the text in the product description).
- **Category Option:** Choose 3D models from different categories.

## Project Structure

### Frontend (HTML and Tailwind CSS)

- Create a responsive and visually appealing interface using Tailwind CSS.
- Build a simple and user-friendly layout for browsing and managing 3D models.

### Backend (Django)

- Set up the Django application and create models for user accounts and 3D assets.
- Implement authentication and authorization features using Django's built-in auth system.
- Handle CRUD operations for 3D models (Create, Read, Update, Delete).

## Getting Started

### Prerequisites

- Python
- Django
- Tailwind CSS

### Follow these steps to execute the project locally.

- Use git clone or download the project files manually. Locate to the Project location.
  -Assumning you are in the folder 'AssetsStore'

Activate the virtual environment:

```bash
.\env\Scripts\activate
```

Move into the Main folder:

```bash
cd puddle
```

Move into the Main folder:

```bash
python manage.py runserver
```

These steps will deploy the '3DMarket' store locally

Do share your reviews, ideas, and improvement suggestions through LinkedIn.
