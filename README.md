# Connect local-based MySQL DB to JetBrains Rider
### Start

- Open your JetBrains Rider and create a New Project
- Open ‘Tools’ menu, and select ‘Connect to Database’ option
  ![image](https://github.com/Tabatskyi/Connect-MySQL-to-Rider/assets/115981919/1166ec1d-365a-472a-aa3a-0a686468b1b0)
- Select ‘Add data source manually’
- Press the ‘Next’ button
  ![image](https://github.com/Tabatskyi/Connect-MySQL-to-Rider/assets/115981919/3f2ccc88-1ed2-4ac8-8cd3-830c434e454a)


### First Step
- In ‘Host’ field put ‘localhost’
- Then put port, selected when you created server (by default ‘3306’) in the related field and press the ‘Next’ button
  ![image](https://github.com/Tabatskyi/Connect-MySQL-to-Rider/assets/115981919/2e214a05-522a-4692-9a9e-6d9780f0781a)

### Second Step
- Authentication: select ‘User & Password’
- User: put user name, selected when you created server (by default ‘root’)
- Save: responsible for what time Rider will remember your authentication credentials
- Database: if you already have one, you can choose it here (if you don't, you will create one soon)
- Press the ‘Connect to Database’ button
  ![image](https://github.com/Tabatskyi/Connect-MySQL-to-Rider/assets/115981919/78612682-59dd-4cdc-bab7-a0433e56aea7)

Congratulations! You just connected Rider with MySQL!


