`Requirements & setup:`


- Install python3 in the cmd.
- make the python fastapi folder in virtual environment.
`python -m venv fastapi-venv`

-To activate the Virtual environment we need to use the command below.
`fastapi-venv\Scripts\activate.bat`

- Once we are in the vitrual env , we can install anything we want.
- `pip  intall fastapi`
- Then we need to install the server, that is "uvicorn"
- `pip install uvicorn`
- Now just open the fastapi folder in the VSCODE & we are ready to go to write our first program.
- now create a file name `app.py` .
- we need to activate the virtual environment to run the file , hence we need to open the "Command Prompt in VS Code" & enter the Command that activates the virtual environment.
- i..e  fastapi-venv\Scripts\activate.bat
- now import the FastAPI library , enter the code & run the uvicorn server to get the ouput of our code.
- `uvicorn app_with_fastapi_object object_name --reload`
- `example: uvicorn main:app --reload`
- fastAPI has an automatic "document generation from swagger-api" which can be found in the directory name `/docs`.
- document tells us about the "functions" we have made for different indexes.
- if we dont like the swagger UI at "/docs" , fasAPI provides another documentation at "/redoc" endpoint.
- use "deactivate" to deactivate the Virtual environment.
-  
