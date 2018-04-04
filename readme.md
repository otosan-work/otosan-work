## setting

```
$ brew install hugo
$ git clone --recursive https://github.com/otosan-work/otosan-work.git
```

## add an new article

```
$ cd otosan-work
$ hugo new blog/{title}.md
```

edit {title}.md 

## local test

```
$ hugo server
$ open localhost:1313
```

## deploy

```
$ sh deploy.sh
```