# Simple Parcel Start App

Steps:

```bash
git init
npm init -y
npx license mit > LICENSE
npx gitignore node
yarn add --dev parcel@next
```

- Added `.parcel-cache` to `.gitignore`
- Added `package.json#source` as `src/index.html`
- Filled `src/index.html` with example on parcel `README.md`
- Ran `yarn parcel .`
- 404 page displayed
