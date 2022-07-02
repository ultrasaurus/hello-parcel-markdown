


```
yarn global add parcel-bundler
yarn init -y
yarn add parcel-transformer-markdown --save-dev
```

create `src/index.md`
add `.parcelrc` with [config](https://www.npmjs.com/package/parcel-transformer-markdown)

add `.markedrc` (figured out by reading code, didn't see docs on this)
```
{
    "marked": true,
    "html": true
}
```