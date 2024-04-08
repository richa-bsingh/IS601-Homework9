# RestAPI for Creating QR Codes

The purpose of this assignment is to get you accustomed to running the project and following the steps that the program uses to process requests.

**To submit this assignment, you should make your own repository and add the remote to git and then push your fixed code to your own repo.** 

# Installation instructions:
1. Clone
2. Make virtual environment:  python3 -m venv venv
3. Activate virtual environment: source venv/bin/activate
4. Install requirements: pip install -r requirements.txt
5. **IMPORTANT** run: mkdir qr_codes to create a qr codes directory to save in, permissions will be messed up and the docker container won't be able to write to the qr_codes directory if you don't.
6. Note: make sure docker is started
7. run pytest locally to check that it works locally
8. Start the app with docker compose up --build
9. Goto http://localhost/docs to view openapi spec documentation
10. Click "authorize" input username: admin password: secret
11. Test making,  retrieving, and deleting QR codes on the spec page.

# Screenshots:

![Github action run](<Screenshot 2024-04-08 at 5.51.47 PM.png>)
Link to successful run - https://github.com/richa-bsingh/IS601-Homework9/actions/runs/8607035299/job/23586741129

![Docker img](<Screenshot 2024-04-08 at 5.51.28 PM.png>)