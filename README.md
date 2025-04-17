# image-classifier-web-app
A project to learn Django and FastAI

# 🧠 3-Day Bootcamp: FastAI + Django + React (Full Stack ML App)

**Goal**: Build a full-stack web app that classifies images using a FastAI model, with a Django backend and a React frontend.

---

## 🗓️ Day 1 — Django + FastAI Basics + Project Setup

### Morning: Django Crash Course
- Set up a Django project
- Learn about:
  - Models
  - Views
  - Django REST Framework (DRF)
  - Serializers and basic API
- Add CORS support for React frontend

**Mini Task**: Build an image upload API  
**Resources**:
- https://www.django-rest-framework.org/tutorial/quickstart/
- https://learndjango.com/tutorials/django-image-upload-tutorial

---

### Afternoon: FastAI Basics
- Install `fastai` and `jupyter`
- Use `ImageDataLoaders.from_folder` to create a simple image classifier
- Train model and export with `learn.export()`

**Mini Task**: Train and export a classifier on a small dataset  
**Resources**:
- https://course.fast.ai/Lessons/lesson1.html

---

## 🗓️ Day 2 — Connect Backend + AI + Build API

### Morning: FastAI Inference in Django
- Load your model using `load_learner()`
- Create a Django view that:
  - Accepts image uploads
  - Returns model predictions in JSON

**Mini Task**: Build `/predict` API endpoint  
**Resources**:
- https://towardsdatascience.com/productionizing-fastai-models-part-1-cfe4ec5084b6

---

### Afternoon: Integrate Backend API
- Finalize image upload + prediction flow
- Store images locally
- Test the full backend API with Postman

**Mini Task**: Full test — upload image → get JSON label

---

## 🗓️ Day 3 — React Frontend + Full App Polish

### Morning: Build React Frontend
- Create React file upload component
- Send `POST` request to Django `/predict` API
- Show prediction + uploaded image

**Mini Task**: React page to upload image and show result  
**Resources**:
- https://blog.logrocket.com/how-to-upload-files-in-react-with-node-js-and-express/

---

### Afternoon: Polish UI + Optional Deployment
- Add loading and error states
- Style with Tailwind or other CSS framework
- Optional: deploy backend to Render, frontend to Vercel

**Mini Task**: Finish frontend and polish UI  
**Bonus**: Add "Prediction History" list to frontend

---

## ✅ Final Project: Full Stack Image Classifier
- **Frontend**: React
- **Backend**: Django + DRF
- **ML**: FastAI image classification
- **Functionality**: Upload image → get prediction → show results

---

