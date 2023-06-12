## Initiate Project

### Creating file `package.json`
npm init -y

### Installing `next`, `react`, and `react-dom`:
npm install next@latest react@latest react-dom@latest

### Creating new Folder `/pages` and insede the folder to create new file `index.js`
### Copy and paste this exemple of HomePage
```js
export default function Home() {
    return (
        <>
            <h1>Welcome!</h1>
            <p>
                Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.
            </p>
        </>
    )
}
```

### Now we need to add this code in `package.json`
```json
"scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
    "lint": "next lint"
},
```

### To run in DEV mode:
`npm run dev`



### To run in production mode:
```
npm run build
npm run start
```


### Reference:
https://www.youtube.com/watch?v=qwhMyVVnmKM