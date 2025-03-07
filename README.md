# CourseCritique 🚀

CourseCritique is a modern course feedback and rating system designed to help educators and learners share insights and improve course quality. Built with **FastAPI** (Python) for the backend and **React** for the frontend, it provides a seamless experience for collecting reviews, managing ratings, and exploring courses.

---

## Features ✨

- **Course Listing**: Browse and explore available courses.
- **Reviews & Ratings**: Submit and view reviews with star ratings.
- **User Authentication**: Secure login and registration using JWT.
- **Admin Panel**: Manage courses and reviews.
- **Responsive Design**: Built with React for a smooth user experience.

---

## Tech Stack 💻

- **Backend**: FastAPI (Python)
- **Frontend**: React
- **Database**: Supabase (PostgreSQL)
- **Authentication**: Supabase
- **Styling**: Tailwind CSS + Daisy UI

---

## Installation 🛠️

### Backend (FastAPI)

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/CourseCritique.git
   cd CourseCritique/backend
   ```

2. Install dependencies:

```bash
pip install -r requirements.txt
```
3. Set up the database:

  - Update the ```database.py``` file with your MySQL credentials.

  - Run the schema script to create tables.

4. Start the server:

```bash
uvicorn main:app --reload
```

## API Endpoints 🌐
  - ```GET /courses```: Fetch all courses.

  - ```GET /courses/{course_id}```: Fetch details of a specific course.

  - ```POST /courses/{course_id}/reviews```: Submit a review for a course.

  - ```GET /courses/{course_id}/reviews```: Fetch reviews for a course.

  - ```POST /register```: User registration.

  - ```POST /login```: User login (returns JWT token).

## Contributing 🤝
We welcome contributions! If you'd like to contribute, please follow these steps:

  - Fork the repository.

  - Create a new branch ```(git checkout -b feature/YourFeatureName)```.

  - Commit your changes ```(git commit -m 'Add some feature')```.

  - Push to the branch ```(git push origin feature/YourFeatureName)```.

  - Open a pull request.

## License 📄
This project is licensed under the MIT License. See the LICENSE file for details.

## Screenshots 📸
Course List
Course Detail

## Live Demo 🌍
Check out the live demo here.

