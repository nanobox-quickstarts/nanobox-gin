![Gin from scratch](https://guides.nanobox.io/assets/quickstart-icons/gin.png)

# Gin from scratch

Run a Gin app locally, install nothing besides nanobox.

<a href="https://nanobox.io/download"><img src="https://guides.nanobox.io/assets/quickstart-icons/download.png" /></a>

## Clone the repo

```bash
# clone the code
git clone https://github.com/nanobox-quickstarts/nanobox-gin.git

# cd into the gin app
cd nanobox-gin
```

## Run the app

```bash
# Add a convenient way to access your app from the browser
nanobox dns add local gin.dev

# Run Gin as you would normally, with Nanobox
nanobox run go run main.go
```

## Check it out

Visit your app at <a href="http://gin.dev:8080/ping" target="\_blank">gin.dev:8080/ping</a>

## Explore
With Nanobox, you don't have to have anything installed on your machine to run your app:

```bash
# drop into a Nanobox console
nanobox run

# where golang is installed,
go version

# git is installed,
git --version

# and your code is mounted
ls
```

## Now What?
For more details about running Gin apps with nanobox visit [guides.nanobox.io/golang/gin/](https://guides.nanobox.io/golang/gin/)

<a href="https://nanobox.io"><img src="https://guides.nanobox.io/assets/quickstart-icons/footer.png" /></a>
