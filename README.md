# ECommerce-Back-End


![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

### Description:  
- This Nodejs uses mysql2 as a way of creating a database intended to keep track of employee details, role, department and their corresponding manager.
- Options to see, the list of the organization's different departments, positions/title, employees.
- You can add departments, roles/position/title, and an employee(s).
- This application also included option to delete an employee.
- Other options to delete, and update information on the database are still under construction.
- Different information presentation are still under construction as well.
- This application will stop upon chosing 'EXIT' option or forcibly stopping by 'CTRL + C'.
- This application requires MYSQL to be installed in your computer system.

## TABLE OF CONTENTS:

* [Installation](#installation)
* [Usage](#usage)
* [Contributing](#contributing)
* [Tests](#tests)
* [Demo](#demo)
* [Questions](#questions)
* [License](#license)

### Installation:    
- Fork or copy the whole directory.
- You must have MYSQL and insomnia installed in your computer.
- Under console, command prompt, or terminal, change to directory where index.js is located.
- Type 'npm i'.
- Create .env file on the root directory (where server.js is located).
    - The file must contain the following:
       - DB_NAME=ecommerce_db
       - DB_USER= root
       - DB_PW='password'  <--- The "password" refers to your mysql password. 
- Create a .gitignore file as needed and must contain:
    - node_modules
    - .DS_Store
    - .env
- From the root directory go to the /db sub-directory.
    - Type 'mysql -u root -p' on the CLI or Terminal.
    - Enter your mysql password.  
    - Once successful, type in your CLI or Terminal "source schema.sql; source seeds.sql;
- Type 'npm start' to start under CLI or Terminal. Alternatively, should you want to make changes in the code, type 'npm watch' to run the server and be able to change the code without having to restart the server every time.
- Open insomnia.  The server is will be hosting under localhost:3001.  See demo videos for details.


### Usage:  
- Can be used for any device.

### Contributing:  
- None

### Tests:  
- None

### Demo:  
- Demo page: 

![alt text][logo]

[logo]: Assets/demo/demo-01.gif "E-commerce Back-End demo"

- Video link:  [Video: Category](https://drive.google.com/file/d/1q4l_tl_GvmR4kw3qaUc51PIPfPwQayCi/view)
- Video link:  [Video: Product](https://drive.google.com/file/d/1hqTTsaCguHt-DdhI8Zmisv2IqU8w9AHK/view)
- Video link:  [Video: Tags](https://drive.google.com/file/d/1c40iXHZ45Kkj3sPKb_8WqrphgNUqic63/view)

### Questions: 

Github:  [eugene32](https://github.com/eugene32)

Email:   [ekahiyang@gmail.com](mailto:ekahiyang@gmail.com)


### License:  
The MIT License

	Permission is hereby granted, free of charge, to any person obtaining a 
      copy of this software and associated documentation files (the "Software"), 
      to deal in the Software without restriction, including without limitation 
      the rights to use, copy, modify, merge, publish, distribute, sublicense, 
      and/or sell copies of the Software, and to permit persons to whom the Software 
      is furnished to do so, subject to the following conditions:

      The above copyright notice and this permission notice shall be included in all 
      copies or substantial portions of the Software.
      
      THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, 
      INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A 
      PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT 
      HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF 
      CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE 
      OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

[MIT License link](https://opensource.org/licenses/MIT)
