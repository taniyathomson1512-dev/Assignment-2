# Employee App Backend Integration

The supplied frontend build is kept unchanged. The original starter `app.js` scaffold/comments and required frontend fallback are preserved; implementation is added in the TODO sections.

## Run
1. Run `npm install` in this folder.
2. Create `.env` using `.env.example` and set `MONGODB_URI` to your MongoDB Atlas connection string.
3. In Atlas, create a database user and allow your current IP in Network Access.
4. Run `npm start`, then open `http://localhost:3000`.

API endpoints: `GET /api/employeelist`, `GET /api/employeelist/:id`, `POST /api/employeelist`, `PUT /api/employeelist`, `DELETE /api/employeelist/:id`.

The three versions have different backend handler organization, but the frontend intentionally looks the same because the assignment prohibits changing the build files.
