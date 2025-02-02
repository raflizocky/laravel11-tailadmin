## Demo

![Image](https://github.com/user-attachments/assets/257c2d5a-b250-468b-bc34-0632a509e0c1)

## Installation

1. Create the database (ex: `tailadmin_template`)

2. Terminal (Powershell, etc)

    ```shell
    git clone https://github.com/raflizocky/laravel11-tailadmin.git
    ```

    ```shell
    code laravel11-tailadmin
    ```

3. `.env`

    - Terminal:
        ```shell
        cp .env.example .env
        ```
    - Adjust `.env`:
        ```shell
        DB_CONNECTION=mysql
        DB_HOST=127.0.0.1
        DB_PORT=3306
        DB_DATABASE=example-app
        DB_USERNAME=root
        DB_PASSWORD=
        ```

4. Terminal (Powershell, etc)
   ```shell
   composer i ; php artisan key:generate ; php artisan mi ; php artisan serve
   ```
      
## Contributing

If you encounter any issues or would like to contribute to the project, feel free to:

-   Report any [issues](https://github.com/raflizocky/laravel11-tailadmin/issues)
-   Submit a [pull request](https://github.com/raflizocky/laravel11-tailadmin/pulls)
-   Participate in [discussions](https://github.com/raflizocky/laravel11-tailadmin/discussions) for any questions, feedback, or suggestions

## License

Code released under the [MIT License](https://github.com/raflizocky/laravel11-tailadmin/blob/main/LICENSE).
