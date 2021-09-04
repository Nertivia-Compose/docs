1. Clone nertivia-compose repo using `git clone https://github.com/Nertivia-Compose/instance`
2. Enter the repo directory using `cd instance`
3. Rename `.env.example` to `.env` using `mv .env.example .env`
4. Open `.env` file using `vim .env` and switch to insert mode using `i` key
5. Change values on:
   
   - line 2 to `http://ip[IP]-[ID]-8080.direct.labs.play-with-docker.com`
   - line 3 to `http://ip[IP]-[ID]-8181.direct.labs.play-with-docker.com`
   - line 4 to `http://ip[IP]-[ID]-8282.direct.labs.play-with-docker.com`

6. Save changes and exit using `esc` and `:wq`
7. Run instance using `docker-compose up` and wait for it to run completely
8. Open webclient by clicking on port `8080`