## Ports

Prefix: None

Suffix: `_PORT`

### CLIENT
 - The port client is running on

### SERVER
 - The port server is running on

### MONGODB
 - The port database server in running on (no use if connected to remote database)

### CDN
 - The port CDN is running on

## Caddyfile

Prefix: `CADDYFILE_`

Suffix: None

### SERVER_URL
 - The URL where the server is accessible

### CLIENT_URL
 - The URL where the client is accessible

### CDN_URL
 - The URL where the CDN is accessible

## Server

Prefix: None

Suffix: None

### MONGODB_ADDRESS
 - Database URL

### JWT_SECRET
 - Server JWT secret (keep it private)

### SESSION_SECRET
 - Session secret (keep it private)

### REDIS_HOST
 - Cache server URL

### REDIS_PORT
 - Cache server port

### REDIS_PASS
 - Cache server password (leave empty for no password)

### CAPTCHA_KEY
 - hCaptcha key used for server

### CLIENT_DOMAIN
 - The domain your client is running at

### ALLOWED_ORIGINS
 - Origins allowed to connect to the server

## SMTP

Prefix: `SMTP_`

Suffix: None

### SERVICE
 - Service used for sending mails

### USER
 - The name of mail sender

### PASS
 - Mail account password

### FROM 
 - Mail account e-mail

## Google Drive

Prefix `DRIVE_`

Suffix: None

### CLIENT_ID
 - Google Drive client id

### CLIENT_SECRET
 - Google Drive client secret

### URL
 - Google Drive URL

### KEY
 - Google Drive key

## DEV_MODE
- Nertivia developer mode (disables captcha and ratelimits)

## CLIENT

Prefix: `VUE_APP_`

Suffix: None

### MAIN_APP_URL
 - URL the client is running at (with / at the end)

### SOCKET_URL
 - URL the server is running at (no / at the end)

### FETCH_PREFIX
 - API URL (no / at the end)

### NERTIVIA_CDN
- Nertivia CDN URL (with / at the end)

### CAPTCHA_SITE_KEY
 - hChaptcha site key used for client

### TWEMOJI_LOCATION
 - Emoji pack location (with / at the end)

### IMAGE_PROXY_URL
 - URL for image proxy (no / at the end)

## FIREBASE

Prefix: `VUE_APP_FCM_`

Suffix: None

## API_KEY
 - Firebase API key

## AUTH_DOMAIN
 - Firebase auth domain

## DATABASE_URL
 - Firebase database URL

## PROJECT_ID
 - Firebase project ID

## STORAGE_BUCKET
 - Firebase storage bucket URL

## SENDER_ID
 - Firebase sender ID

## APP_ID
  - Firebase app ID