# Commerce

**Commerce** is a web application for online auctions that allows users to create and manage listings, place bids, track favorite items, and more.

## Project Overview

Commerce enables users to:
- **Create Listings**: Set images, prices and descriptions for items or services they want to sell.
- **Place Bids & Leave Comments**: Participate in auctions for active listings.
- **Manage Listings**: Edit or deactivate their own listings. When a listing is deactivated, the last bidder wins the auction.
- **Add to Watchlist**: Save active listings to a Watchlist for easy tracking.
- **Login and Registration**: Access the platform using cookies and sessions for authentication.

## Tech Stack

- **Golang**: The backend is built using Golang, providing robust and efficient server-side logic.
- **templ**: Templating engine used to render HTML pages.
- **Bootstrap**: Styling of the website is done with Bootstrap.
- **SQLite3**: Database to store user data, listing items, sessions and more.
- **sqlc**: SQL code generation tool used to interact with the SQLite3 database.

## Installation

1. **Clone the Repository**

    ```bash
    git clone https://github.com/Javohir-Komilov/commerce.git
    cd commerce
    ```

2. **Install Dependencies**

    Ensure you have Golang installed. Install necessary Go modules with:

    ```bash
    go mod tidy
    ```

3. **Set Up the Database**

    Create and configure the SQLite3 database, and run any necessary migrations.

4. **Run the Application**

    Start the application with:

    ```bash
    go run main.go
    ```

5. **Open the Application**

    Navigate to `http://localhost:8080` in your browser to start using the application.
