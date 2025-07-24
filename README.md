# 🛠️ Django Setup with Tailwind CSS

This project is a basic Django web app with **Tailwind CSS** integrated using the `django-tailwind` package. It includes setup for `daisyUI`, live reloading with `npm run dev`, and is ready to be extended for real-world applications.

---

## 🔧 Features

- ✅ Django 5.2.4
- ✅ Tailwind CSS 3
- ✅ daisyUI installed
- ✅ Live CSS rebuilding with `npm run dev`
- ✅ Proper theme app setup with `django-tailwind`

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/Sarishhma/django-setup-with-tailwind-css.git
cd django-setup-with-tailwind-css


2. Create a virtual environment & activate it

Copy code
python -m venv venv
venv\Scripts\activate  # On Windows

3. Install Python dependencies
bash
Copy code
pip install -r requirements.txt

4. Install npm dependencies
bash
Copy code
cd myproject/theme
npm install
cd ..

🚀 Running the Project
1. Start Tailwind CSS watcher
bash
Copy code
python manage.py tailwind start

2. In another terminal, run the Django server
bash
Copy code
python manage.py runserver
Now visit: http://127.0.0.1:8000

🎨 Example Code in Template
Example of Tailwind + daisyUI usage:

html
Copy code
<h1 class="text-3xl font-bold text-center bg-blue-500 text-white p-4">
  Hello from Tailwind + Django!
</h1>


📝 Notes
Tailwind CSS is configured inside the theme app.

The CSS is generated from theme/static_src/src/styles.css.

You can edit the styles and daisyUI theme here as needed.

📂 Folder Structure
graphql
Copy code
myproject/
├── app/                 # Main Django app
├── theme/               # Tailwind CSS theme app
│   └── static_src/      # Source for Tailwind/daisyUI
├── manage.py
└── requirements.txt
📃 License
MIT License — free to use for personal or commercial projects.

Made by Sarishhma
