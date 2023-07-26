# Postgres DB-Configuration
```cmd
1. cd /etc/postgresql/15/main
```
```cmd
2. vi pg_hba.conf
```
3. Add your local IP
   Example- This is how pg_hba.conf will look like
   ![image](https://github.com/akashmittal18/PostgresDB-Cofiguration/assets/47140557/0b348bd2-ac57-4abb-94ce-358c895c757e)

4. save the changes.
5. Restart the Postgres server using
   ```cmd
   sudo systemctl restart postgresql
   ```


# How to make Postgres DB accessible to other hosts?

![image](https://github.com/akashmittal18/PostgresDB-Cofiguration/assets/47140557/e0d9c8a8-ab13-43aa-8352-d693959949f6)
![image](https://github.com/akashmittal18/PostgresDB-Cofiguration/assets/47140557/85fdb12a-d85a-4327-ade1-ef7472a4085b)
![image](https://github.com/akashmittal18/PostgresDB-Cofiguration/assets/47140557/715878a8-0d9a-4040-96fb-049b685d482e)
