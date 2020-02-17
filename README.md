# README

## Figaro gem
- Figaro was written to make it easy to securely configure Rails applications.
 https://github.com/laserlemon/figaro
 ```
  gem "figaro"

  bundle exec figaro install
 ```

 ## config gem
 - Gem config giúp quản lý và sử dụng dễ dàng các settings trong project.

  ```
   gem "config"

   rails g config:install
  ```

  ## paranoia gem
  - Add column deleted_at to model
   ```
    gem "paranoia"

    acts_as_paranoid # add to model use deleted_at column

    ```
