# 🐳 Docker MongoDB & Mongo-Express Setup 🚀
Welcome to the streamlined Docker setup for MongoDB and Mongo-Express! 🎉 Get your NoSQL database and web-based management interface up and running with minimal fuss, and start managing your dynamic data collections effortlessly! 🌟

## 📦 What's Inside?
MongoDB: A powerful, open-source NoSQL database that uses a document-oriented data model and supports high availability, horizontal scaling, and geographic distribution 🗃️.
Mongo-Express: A web-based MongoDB admin interface written in Node.js, allowing you to manage your databases over the web 🌐.
🏁 Quick Start Guide
Here’s how to get MongoDB and Mongo-Express running quickly:

## 1. Clone this Repository 📂
Start by cloning or downloading this repository to your local machine.

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

## 2. Set Up Your Files 📁
Create a directory that will be used as a file drop zone. This is useful for importing data files into MongoDB:

```bash
mkdir -p file_drop_zone
```

## 3. Fire Up Docker Compose 🚀
Execute Docker Compose to launch your Docker containers:

```bash
docker-compose up -d
```

## 4. Access Your Tools 🛠️
Mongo-Express: Navigate to http://localhost:8081 to access Mongo-Express.

```
Username: admin
Password: pass
```

MongoDB: Connect to your MongoDB instance using any MongoDB client at:

```
Host: localhost
Port: 27017
Username: mongoadmin
Password: secret
```

## 5. Drop Files & Go! 📤
Place any MongoDB data files into the file_drop_zone directory. These files can be accessed within the MongoDB container at /my_file_drop_zone for easy data import.

🛠 Configuration
Feel free to tweak the docker-compose.yml file to adjust environment variables such as MongoDB user credentials or to modify the Mongo-Express configuration to fit your needs.

By following these steps, you can have a robust MongoDB setup with an easy-to-use management interface, ideal for development, testing, or even production environments with further customization. Enjoy your efficient and effective data management experience! 🚀

<img width="1478" alt="image" src="https://github.com/sojohnnysaid/mongodb-mongo-express-docker-setup/assets/16521766/773dcb41-6464-40ae-847d-82b4148d4b12">
