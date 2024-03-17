# next-impl-cache base example

Basic example of using [next-impl-cache-adapter](https://github.com/vordgi/next-impl-cache/tree/main/packages/next-impl-cache-adapter) with [next-impl-cache-in-memory](https://github.com/vordgi/next-impl-cache/tree/main/packages/next-impl-cache-in-memory) as cacheHandler

For a full check, you need to start the server:

```bash
cd server
npm install
npm run start
```

Now you can build and run the application itself:

```bash
cd site
npm run build
npm run start
```

You can also run a copy of the application to check the health of the shared cache:

```bash
npm run start:clone
```

Now both instances of one assembled application have a common cache - a running server. It can be placed anywhere, the main thing is to point the url to it. More details on the [next-impl-cache-adapter](https://github.com/vordgi/next-impl-cache/tree/main/packages/next-impl-cache-adapter) page.

## Links

- [next-impl-cache-adapter](https://github.com/vordgi/next-impl-cache/tree/main/packages/next-impl-cache-adapter);
- [next-impl-cache-in-memory](https://github.com/vordgi/next-impl-cache/tree/main/packages/next-impl-cache-in-memory).