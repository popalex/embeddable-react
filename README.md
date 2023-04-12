# embeddable-react

This is the starting point to [this article](https://observiq.com/blog/embed-react-in-golang/)

# Dev mode

In main folder run:

```bash
go run .
```

In `ui` folder run:

```bash
npm start
```

At last, open the browser at http://localhost:3000 .

# Production mode

In the main folder run:

```bash
cd ui && npm run build && cd ..  && go build && ./embeddable-react
```

At last, open the browser at http://localhost:4000 .