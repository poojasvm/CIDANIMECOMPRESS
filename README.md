#### Deploy on HEROKU
[![Deploy on HEROKU](https://www.herokucdn.com/deploy/button.svg)](https://dashboard.heroku.com/new?template=https%3A%2F%2Fgithub.com%2F2204852%2FCIDANIMECOMPRESS)

#### Deploy on Railway
[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/P2jqdk)



### Variables
`APP_ID` `API_HASH` `BOT_TOKEN`

`OWNER` : Put Id Of Auth Users with a space between it

`THUMBNAIL` : Put telegraph link of a picture for use of Thumbnail.

`FFMPEG` : Put Your FFMPEG Code with "{}" as input and output. (Eg. `ffmpeg -i '{}' -preset veryfast -c:v libx264 -crf 26 -map 0:v -c:a aac -map 0:a -c:s copy -map 0:s? '{}' -y`)

### updated

now you can use full ffmpeg 

### local and vps Deployment:
With Docker:

Install Docker
Clone repository to your preferred location
Run:

`docker build . -t enc`

`docker run enc`


⚠️ haven't tested by me so try it if you want 
