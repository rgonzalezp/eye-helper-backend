## Eye Helper back-end

Based on a typescript boilerplate. This back-end server is responsible of connecting the front-end with the Amazon Alexa Skills by changing the states of the application.

### Setup

```bash
npm install
```

### Development with nodemon and tsc --watch

```bash
npm run dev
```

Then visit `http://localhost:3000/cats`

### Run without nodemon and tsc --watch

```bash
npm start
```

Then visit `http://localhost:3000/cats`

## Modes

There are two modes that we will switch in between as a proof of concept: Creating things and Destroying things.

If on creation mode, the eye tracker is supposed to create figures (Circles, squares, triangles) within the canvas (This part is not implemented yet)
If on destruction mode, the eye tracker is supposed to destroy figures within the canvas (This part is not implemented yet)
