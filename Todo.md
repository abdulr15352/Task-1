Please make a RESTful API using FastAPI to authenticate users for a voting system.

We do not need the voting section for this task.

Please ensure the app has the following endpoints:

Registration: To register a user, at least the name, email, and password fields
Login: To log in users using email and password.
Info [Auth]: To get the user payload info decrypted from the JWT token.
Delete [Auth]: A delete endpoint to delete the user if they request.
Please follow the development best practices and manage your packages using Poetry.

Set the token expiration date to 1 minute and attempt to retrieve the user's information a few times within this 1-minute period. The endpoint should fail.

Please make a GitHub repo for all your tasks. Hold each task in a different folder and add my email, Siamak.khatami@kristiania.no, as the collaborator. As the first task, this folder can be named Task 1.

Notes:

[Auth]: This endpoint should be validated using a JWT token.
To add packages manually, you can either use requirements to install packages (not suggested since this will be used by Docker) or use the dependencies list from pyproject.toml with the poetry add command.