![Express from scratch](https://guides.nanobox.io/assets/quickstart-icons/express.png)

# Express from scratch

Run an Express app locally, install nothing besides nanobox. 

<a href="https://nanobox.io/download"><img src="https://guides.nanobox.io/assets/quickstart-icons/download.png" /></a>


## Clone the repo

```bash
# clone the code
git clone https://github.com/nanobox-quickstarts/nanobox-express.git

# cd into the express app
cd nanobox-express
```

## Run the app

```bash
# Run express as you would normally, with Nanobox
nanobox run npm start
```

## Check it out

```bash
# Add a convenient way to access your app from the browser
nanobox dns add local express.dev
```

Visit your app at <a href="http://express.dev:3000" target="\_blank">express.dev:3000</a>

## Explore

With Nanobox, you don't have to have anything installed on your machine to run your app:

```bash
# drop into a Nanobox console
nanobox run

# where node is installed,
node -v

# your packages are available,
npm list

# and your code is mounted
ls
```

## Now What?
For more details about running express apps with nanobox visit [guides.nanobox.io/nodejs/express/](https://guides.nanobox.io/nodejs/express/)

<a href="https://nanobox.io"><img src="https://guides.nanobox.io/assets/quickstart-icons/footer.png" /></a>
