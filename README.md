# AI Todo App

This is an AI-powered Todo List application that allows users to manage tasks by adding, viewing, updating, and deleting them. The application uses OpenAI's GPT model to interact with users and perform actions on a PostgreSQL database.

## Project Structure


## Setup

### Prerequisites

- Node.js
- Docker
- PostgreSQL

### Installation

1. Clone the repository:

```
git clone git@github.com-Harsh-oo7:Harsh-oo7/ai-todo-app.git
cd ai-todo-app
```

2. Install dependencies:

```
npm install
```

3. Create a .env file in the root directory with the following content:

```
DATABASE_URL=postgresql://admin:admin@localhost:5431/postgres
OPENAI_API_KEY=your_openai_api_key
```

4. Start the PostgreSQL database using Docker:

```
docker-compose up -d
```

5. Generate and migrate the database schema:

```
npm run generate
npm run migrate
```

## Setup

1. Start the application:

```
node index.js
```

### Example Interaction

```
>> Add a task for shopping groceries.
Output: Can you tell me what all items you want to shop for?
>> I want to shop for milk, kurkure, layes.
Output: Your todo has been added successfully
```

