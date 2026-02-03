# Court.iq
Basketball analytics website with a dashboard to display stats. 

Will begin learning and implementing the FARM(D) tech stack in order to accomplish this:


Fa (FastAPI - the backbone)

  -> Fast due to its asynchronous nature and also a developer friendly framework
  
R (React - the interface)

  -> Efficient state management, virtual DOM to increase performance and feel, works seamlessly with FastAPI async
  
M (MongoDB - the storage)

  -> NoSQL db based on documents, high performance, flexible schema, and built to scale
  
(D) (Docker - the container)

  -> Reduce dependency issues, easy to set up app anywhere, scalable
  


Current Project Structure

.

├── backend/               # FastAPI source code

│   ├── app/

│   │   ├── models/        # Pydantic schemas (Data validation)

│   │   ├── routes/        # API endpoints

│   │   └── database.py    # Motor (Async) connection logic

├── frontend/              # React application

│   └── src/

│       ├── components/    # Reusable UI elements

│       └── services/      # API abstraction layer (Axios/fetch)

└── docker-compose.yml     # Orchestration for the entire stack

