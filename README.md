
# Laravel Passport OAuth2.0 Authentication

This project is a robust implementation of OAuth2.0 authentication using Laravel Passport. It provides a feature similar to "Sign in with GitHub" or "Sign in with Google," allowing users to use their accounts on this project to access other sites seamlessly.

## Features

- **OAuth2.0 Authentication**: Secure and reliable OAuth2.0 authentication using Laravel Passport.
- **Token Management**: Efficient management of access tokens, refresh tokens, and personal access tokens.
- **Scopes and Permissions**: Fine-grained control over user permissions with customizable scopes.
- **User-Friendly Interface**: Intuitive and user-friendly interface for managing OAuth clients and tokens.
- **API Integration**: Easy integration with third-party applications to allow users to authenticate using their accounts on this project.
- **Secure**: Built-in security features to protect user data and ensure secure authentication.

## Getting Started

### Prerequisites

- PHP 7.3 or higher
- Composer
- Laravel 8.x
- MySQL or any other supported database

### Installation

1. Clone the repository:
   ```sh
    git clone https://github.com/ryanfranklin237/sign-in-with-platform.git
    cd sign-in-with-platform
    ```

2. Install dependencies:
    ```sh
    composer install
    ```

3. Copy the example environment file and configure the environment variables:
    ```sh
    cp .env.example .env
    ```

4. Generate an application key:
    ```sh
    php artisan key:generate
    ```

5. Run the database migrations:
    ```sh
    php artisan migrate
    ```

6. Install Laravel Passport:
    ```sh
    php artisan passport:install
    ```
7. Start the development server:
    ```sh
    php artisan serve
    ```

## Usage

### Registering OAuth Clients

1. Navigate to the OAuth clients management page.
2. Create a new client by providing the necessary details such as client name, redirect URL, etc.
3. Use the generated client ID and client secret to integrate with third-party applications.

### Authenticating Users

1. Direct users to the authorization endpoint to obtain an authorization code.
2. Exchange the authorization code for an access token.
3. Use the access token to authenticate API requests on behalf of the user.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](https://laravel.com/docs/contributions) before submitting a pull request.

## License

This project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

## Contact

For any inquiries or support, please contact [My email](mailto:ngometune@gmail.com).

---

By leveraging Laravel Passport and OAuth2.0, this project aims to provide a seamless and secure authentication experience, empowering users to access multiple sites using their accounts on this platform.
