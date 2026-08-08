
1) In github create repo under main >> clone project as below steps-
2) C:\AI Projects>git clone https://github.com/rakeshchhapare82/my-followups.git
3) go to the folder C:\AI Projects >> then in type 'code' //auto to open the cmd prompt
4) C:\AI Projects>cd my-followups
5) C:\AI Projects\my-followups>git status
6) C:\AI Projects\my-followups>code . //auto vs will open the VS with project

7) conda deactivate
8) uv venv
9) .venv\Scripts\activate   
10) uv pip install -r .\requirements.txt

to deploy into steramlit
1) give py version 3.11
2) in secret settings give postgrasql url

--for whatsapp feature
uv pip install psycopg2-binary sqlalchemy python-dotenv
uv run python database/test_databaseConn.py

 
