1. (Optional)
`docker pull asipro/intro-docker-react`

2.
`docker container run -p 3000:3000 --name=react_app -it asipro/intro-docker-react yarn start`
3.
`docker container exec -it react_app bash`
4.
`yarn build`

extra
`docker container run -p 3000:3000 --name=react_app -it asipro/intro-docker-react yarn build && yarn test`