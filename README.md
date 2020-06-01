- Start watching files `npm run start`
- Delete `test.js`

Get the output

```
×  Cannot read property 'type' of undefined
    at Bundler.createBundleTree (...\parcel\node_modules\parcel\src\Bundler.js:654:54)
    at Bundler.createBundleTree (...\node_modules\parcel\src\Bundler.js:721:12)
    at Bundler.bundle (...\parcel\node_modules\parcel\src\Bundler.js:298:14)
    at processTicksAndRejections (internal/process/task_queues.js:93:5)
```

- Restore the file using `git checkout test.js`
