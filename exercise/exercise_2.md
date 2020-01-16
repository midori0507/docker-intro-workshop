This exercise is for understanding and using the isolation-advantage of Docker container.

1. Pull my React-app from `asipro/intro-docker-react`.
2. 
    Create a container base on that image, 
    Name `react_app`, 
    Run `yarn start`. 
    Forward port 3000.

    Hint: Try using `run -it`.
3. Open web browser port 3000 to see React app
4. Get inside the container, run `yarn build`.

Extra: Run `yarn build` OR `yarn test` script inside container, without going inside container.