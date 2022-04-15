# hello-mockoon

## setup

```shell
$ npm install
```

## npm run
```
"start": "mockoon-cli start --data ./api_data/demo.json; mockoon-cli list",
"list": "mockoon-cli list",
"stop": "mockoon-cli stop 'all'; mockoon-cli list"
```

## docker

```shell
$ docker build -t mockoon-cli . && docker run -p 3000:3000 -v /absolute_path/api_data:/data --name mockoon-cli mockoon-cli -d data/demo.json -p 3000
```
