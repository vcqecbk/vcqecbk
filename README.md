# Profile of Dolly Powlowski 💻👋

Hi, I'm Dolly, a passionate software developer with a love for building scalable applications using TypeScript.

## About Me

* Primary language: TypeScript 💡
* Databases: SQL 📈
* Frameworks: Node.js 🚀
* UI: Tailwind 🎨

## Get in Touch

* Email: dolly_dolly71@yahoo.com

## Projects

Check out my GitHub projects to see what I've been working on!

## Contributing

Feel free to fork and contribute to my projects! I'd love to hear from you.

## License

MIT License

## Acknowledgments

Inspired by the open-source community.

## GitHub Actions


## test.yml

name: Build and Test

on:

- push

jobs:

  build-and-test:

    runs-on: ubuntu-latest

    steps:

      - name: Checkout code

        uses: actions/checkout@v2

      - name: Setup Node.js

        uses: actions/setup-node@v2

        with:

          node-version: '14'

      - name: Install dependencies

        run: npm install

      - name: Run build

        run: npm run build

      - name: Run test

        run: npm run test

      - name: Always succeed

        run: echo 'Success!'