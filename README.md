This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

Run the following command on your local environment:

```shell
npm install / yarn 
```

Then, you can run locally in development mode with live reload:

```shell
npm run dev / yarn dev
```

Open http://localhost:3000 with your favorite browser to see your project.

```shell
.
├── README.md                       # README file
├── .github                         # GitHub folder
├── .vscode                         # VSCode configuration
├── public                          # Public assets folder
├── src
│   ├── assets                      # Assets (dummy data) for the project
│   ├── components                  # General components
│   ├── hooks                       # Custom Hooks
│   ├── pages                       # Next JS Pages
│   ├── store                       # Redux toolkit store
│   ├── styles                      # Styles folder
│   └── utils                       # Utility files
├── tailwind.config.js              # Tailwind CSS configuration
└── tsconfig.json                   # TypeScript configuration
```

### Deploy to production

You can see the results locally in production mode with:

```shell
$ npm run build
$ npm run start
```

The generated HTML and CSS files are minified (built-in feature from Next js). It will also remove unused CSS from [Tailwind CSS](https://tailwindcss.com).

You can create an optimized production build with:

```shell
npm run build-prod
```

Now, your website is ready to be deployed. All generated files are located at `out` folder, which you can deploy with any hosting service.


## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
