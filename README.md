# 🚀 URL Shortener Backend Service

This component serves as the backend of a MERN app. Its primary function is to take long, unattractive URLs and transform them into short, memorable links. Additionally, it provides tracking capabilities, allowing users to monitor the number of times each short URL is visited. Built with love using the latest web technologies, including [Express](https://expressjs.com/), [MongoDB](https://www.mongodb.com/), [TypeScript](https://www.typescriptlang.org/), it's designed to streamline your URL management experience.

## ✨ Features

- **Shorten URLs**: Transform lengthy URLs into concise, easy-to-share links.
- **Retrieve URLs**: Effortlessly access and manage your shortened URLs.
- **View Clicks**: Monitor the number of times each short URL is visited.
- **Delete URLs**: Seamlessly remove unnecessary short URLs.
- **Secure**: Protect your data with robust security measures.
- **Analytics**: Track the performance of your short URLs with detailed analytics. (Coming Soon)

## 🛠️ Installation

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/rahulranjan937/url-shortener-backend.git
    ```

2. **Install Dependencies**:

    ```bash
    cd url-shortener-backend
    npm install
    ```

3. **Set Up Environment Variables**:

    Copy the `.env.example` file to `.env`:

    ```bash
    cp .env.example .env
    ```

    Customize the `PORT` , `MONGO_URI` and other environment variables as needed.

4. **Build the Project**:

    ```bash
    npm run build
    ```

5. **Start the Server**:

    ```bash
    npm start
    ```

6. **Access Your Short URLs**:

    Navigate to `http://localhost:3333` in your web browser to begin using the Short URL Service!

## 🚀 Usage

### Creating a Short URL

To create a short URL, send a POST request to `/api/url/` with the following JSON payload:

```json
{
    "longUrl": "https://github.com/rahulranjan937/URL-Shorten-Backend"
}
```

### Retrieving Short URLs

To retrieve all short URLs, send a GET request to `/api/url`.

### Deleting a Short URL

To delete a short URL, send a DELETE request to `/api/url/:urlCode`, replacing `:urlCode` with the code of the short URL you want to delete.

## 🤝 Contributing

Contributions are warmly welcomed! Whether you have suggestions for improvements, bug fixes, or new features, please don't hesitate to submit a pull request or open an issue.

## 📄 License

This project is licensed under the MIT License. For more information, please see the [LICENSE](LICENSE) file.

## Author

👤 **Rahul Ranjan**
