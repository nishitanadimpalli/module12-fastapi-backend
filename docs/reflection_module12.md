Reflection

In this module, I learned how to build a secure and fully tested backend application using FastAPI, SQLAlchemy, Pydantic, Docker, and GitHub Actions. One of the biggest takeaways was understanding the importance of secure password handling. Instead of storing plain text passwords, I used the bcrypt hashing algorithm to safely hash and verify passwords. This made me realize how essential proper authentication practices are for any real-world application.

Another important concept was data validation using Pydantic schemas. Defining separate models for creation (UserCreate, CalculationCreate) and reading (UserRead, CalculationRead) helped enforce data integrity and avoid invalid inputs, such as invalid emails or division by zero. These schemas also made API responses consistent and predictable.

A major challenge I faced was with GitHub Actions and setting up CI/CD. Issues like indentation errors, Docker tags, and PostgreSQL test container configuration initially caused workflow failures. By debugging the YAML file, adding secrets correctly, and ensuring proper environment variables, I was able to make the tests pass and successfully push images to Docker Hub. This process helped me understand how automated testing and continuous integration work in professional environments.

Overall, this module strengthened my backend development skills and gave me confidence in building secure, test-driven, and production-ready APIs.