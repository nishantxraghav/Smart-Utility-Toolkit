# Smart Utility Toolkit

Lab Assignment 1 - Web Dev III (Node.js & Express Backend)

## Requirements

- Node.js
- No external npm packages
- Only Node.js core modules

## Files

- `calculator.js` - CLI calculator using `process.argv`
- `app.js` - custom module demonstration
- `server.js` - HTTP server using `http`
- `fileManager.js` - file CRUD operations using `fs`
- `dice.js` - random dice generator using `crypto`
- `modules/isEven.js` - reusable custom module
- `modules/logger.js` - reusable logger module

## Commands

### Calculator

```bash
node calculator.js add 10 5
node calculator.js subtract 10 5
node calculator.js multiply 10 5
node calculator.js divide 10 5
```

### Custom module

```bash
node app.js
```

### HTTP server

```bash
node server.js
```

Then open:

- http://localhost:3000/
- http://localhost:3000/about
- http://localhost:3000/contact
- http://localhost:3000/anything

Stop the server with `Ctrl+C`.

### File manager

```bash
node fileManager.js
```

### Dice generator

```bash
node dice.js
```
