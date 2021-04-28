#README

To build from scratch:
```
docker build --no-cache -t symptom-cluster-tool .
```

To run:
```
docker run --rm -p 3838:3838 -v $PWD/srv/shinyapps/:/srv/shiny-server/ -v $PWD/srv/shinylog/:/
var/log/shiny-server/ symptom-cluster-tool
```