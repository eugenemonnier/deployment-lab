# LAB - 00

## Proof of Life Server

### Author: Eugene Monnier/John Cokos

### Links & Resources
- [submission PR]
- [travis]
- [front-end] (when apllicable)

### Documentation
- [jsdoc](http://localhost:3000/docs/)

### Modules

#### `pos.js`
#### Exported Values and Methods

##### `isAlive() -> boolean`
Return true to indicate the server works

### Setup

#### `.env` requirements
- `PORT` - Port number

#### Running the app
- `npm start`
- Endpoint: `/`
  - Returns true or false
- Endpoint: `/docs`
  - Renders developer documentation

#### Tests
- Unit Tests: `npm run test`
- Lint Tests: `npm run lint`
- Assertions made
  - Assert that isAlive() properly returns a boolean
- Assertions remaining
  - future tests

#### UML

![UML Diagram](whiteboard.jpg)