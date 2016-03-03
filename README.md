# The Active Admin Store
[![Travis CI](https://img.shields.io/travis/activeadmin/activeadmin/master.svg)           ](https://travis-ci.org/activeadmin/activeadmin)

This is a test application to demo Active Admin.

http://demo.activeadmin.info

## Installation
- Before running `bundle install` you might have to install the correct version of ruby on your system.

- After the correct version of ruby is install run `bundle install`

-  **DO NOT RUN THE ACTIVEADMIN INSTALL GENERATOR COMMAND** The Active Admin Demo repo already has the generated files for Active Admin to run.

- If you want the seed data from the demo, then migrate and seed your database before starting the server:
  ```sh
  rake db:migrate
  rake db:seed
  rails server
  ```

