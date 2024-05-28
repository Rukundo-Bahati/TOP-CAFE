# TOP-CAFE

TOP-CAFE is a web application designed to help users find and review the best cafes around. Whether you're looking for a cozy spot to enjoy your morning coffee or a vibrant place to meet friends, TOP-CAFE provides detailed information and user reviews to help you make the best choice.

## Features

- **Cafe Listings**: Browse through a comprehensive list of cafes with detailed descriptions, photos, and ratings.
- **User Reviews**: Read reviews from other users to find the best cafes and leave your own reviews.
- **Search and Filter**: Easily find cafes by name, location, or rating using the search and filter options.
- **User Accounts**: Sign up and log in to manage your reviews and favorite cafes.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript, React
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Deployment**: Heroku

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or later)
- [MongoDB](https://www.mongodb.com/)

### Installation

1. **Clone the repository**:

    ```sh
    git clone https://github.com/Rukundo-Bahati/TOP-CAFE.git
    cd TOP-CAFE
    ```

2. **Install dependencies**:

    ```sh
    npm install
    ```

3. **Set up environment variables**:

    Create a `.env` file in the root directory and add the following:

    ```env
    NODE_ENV=development
    PORT=5000
    MONGO_URI=your_mongodb_uri
    JWT_SECRET=your_jwt_secret
    ```

4. **Run the application**:

    ```sh
    npm run dev
    ```

    The app should now be running on [http://localhost:5000](http://localhost:5000).

## Usage

### Searching for Cafes

Use the search bar to find cafes by name or location. Filter options are available to narrow down your search based on ratings and other criteria.

### Leaving a Review

To leave a review, sign up for an account and log in. Navigate to the cafe you want to review and click on "Add Review."

### Managing Your Account

Once logged in, you can manage your reviews and favorite cafes from your user profile.

## Contributing

Contributions are welcome! Please follow these steps:

1. **Fork the repository**
2. **Create a new branch**: `git checkout -b feature/your-feature-name`
3. **Commit your changes**: `git commit -m 'Add some feature'`
4. **Push to the branch**: `git push origin feature/your-feature-name`
5. **Open a pull request**

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or suggestions, feel free to contact me:

- **Name**: Rukundo Bahati Samuel
- **Email**: [your-email@example.com](mailto:your-email@example.com)
- **GitHub**: [Rukundo-Bahati](https://github.com/Rukundo-Bahati)

---

Thank you for using TOP-CAFE! Enjoy your coffee hunting!
